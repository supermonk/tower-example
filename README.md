tower-example
=============

Ansible Tower Example Playbooks


### Execution Steps
1. Add file called "hosts" in project root.
```text
[server]
<ip>:<port>
```
2. Runs Hello World and get output to local and uploads to s3
```bash
ansible-playbook -i hosts helloworld.yml -u <user> --private-key=/../ssh

```
