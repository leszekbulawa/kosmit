Repo with configs for vps.
Most likely it won't be reusable for any other setup.

#### Requirements
* ansible
* sshpass

#### Playbook root.yaml
Creates a user, copies ssh key, enables passwordless sudo and disables password ssh.

To run:
```bash
ansible-playbook -i inventory.yaml -u root -k root.yaml
```