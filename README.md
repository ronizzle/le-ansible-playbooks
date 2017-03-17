# LeAnsible Playbooks


1. ping

Ping if the server is available 

``ansible -i hosts all -m ping -u ec2-user``


```
52.220.53.163 | SUCCESS => {
    "changed": false, 
    "ping": "pong"
}
```
you need the key for the ec2 hosts 


2. install-python

Install python on remote instance ``ansible-playbook -i hosts -s install.yml``

3. nginx-site-install
Install nginx + copy files to the remote server 

``ansible-playbook -i hosts -s deply.yml``


---------------------------------------------------------
#####NB
 - add your aws pem file via `ssh-add keyfilefromaws.pem`