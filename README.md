# random-ansible-playbooks

#ping

ansible -i hosts all -m ping -u ec2-user

```
52.220.53.163 | SUCCESS => {
    "changed": false, 
    "ping": "pong"
}
```