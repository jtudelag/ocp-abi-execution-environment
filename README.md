# Instructions

1. Go to to the `ocp4.12` or `ocp4.14` folder.

2. Generate ansible.cfg
```bash
cd ocp4.14
cp ansible.cfg.example ansible.cfg
```

3. Add your [Red Hat Autmation Hub token](https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/2.4/html/getting_started_with_automation_hub/hub-create-api-token#proc-create-api-token) to your `ansible.cfg`.
```bash
vi ansible.cfg
```

4. Build the EE
```bash
bash -x ./build_ee.sh -a
```
