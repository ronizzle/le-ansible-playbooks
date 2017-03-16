# le ansible playbooks

##ping

ansible -i hosts all -m ping -u ec2-user or ubuntu 

```
52.220.53.163 | SUCCESS => {
    "changed": false, 
    "ping": "pong"
}
```
you need the key for the ec2 hosts 
add via `ssh-add keyfilefromaws.pem`