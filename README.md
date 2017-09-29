# wordpress
Docker HA image automate wordpress deploy on vagrant host with mysql and reverse proxy using ansible playbook 

Execute in shell next commands:
1. git clone https://github.com/kostyanius/wordpress.git             
2. cd wordpress && ansible-playbook playbook.yml --ask-sudo-pass   #run this command under user thay is in sudoers list
