# ansible-playbooks

## How to run

Clone Repo 
```bash
git clone https://github.com/RKolibri/ansible-playbooks.git 
```
Change `dir`  into that directory
```bash
cd ansible-playbooks
```

* Edit `inventory` to your liking
* Remember to change ``variable`` for `username` and change the  `password` field on the  `/playbooks/main.yml`

Then run

```bash
ansible-playbook playbooks/main.yml -i inventory
```
