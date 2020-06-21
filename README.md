# ansible-personal

Run this locally so you can set stuff up

### Setup Raspberry Pis

Check the `inventory/pis.yaml` file to ensure that all of the pis are on this list.
```bash
$ ansible-playbook -i inventory/pi.yaml setuppi.yaml 
```


### Add user accounts to all machines
```bash
$ ansible-playbook -i inventory/all.yaml user_accounts.yaml 
```