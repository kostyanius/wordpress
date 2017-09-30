# wordpress
Automatic deploy on vagrant host with docker images: wordpress, mysql and traefik reverse proxy using ansible playbook provisioning

### Execute in shell next commands:
```
1. git clone https://github.com/kostyanius/wordpress.git             
```
Run this command under root user or another one which is in sudoers list
```
2. cd wordpress && ansible-playbook playbook-all-sudo.yml --ask-sudo-pass        		 
```
