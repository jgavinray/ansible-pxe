# ansible-personal

Run this locally so you can set stuff up.
Download and extract https://github.com/dw/mitogen/archive/master.zip into the /opt directory

### Setup Raspberry Pis

Check the `inventory/pis.yaml` file to ensure that all of the pis are on this list.
```bash
$ ansible-playbook -i inventory/pis.yaml playbooks/setuppi.yaml 
```


### Add user accounts to all machines
```bash
$ ansible-playbook -i inventory/all.yaml playbooks/user_accounts.yaml 
```