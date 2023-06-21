■This is an Ansible Repository with Roles


■Roles
・common(yum update,swap,SELinux,firewalld,Timezone,useradd)
・httpd
・mysql
・php

■Deploy
1. Change user,Keys,playbook.yml,hosts,vhosts,index.html
2. Dry run
ansible-playbook --private-key {PATH} -i {PATH} hosts {PATH} -C
3. Run 
ansible-playbook --private-key {PATH} -i {PATH} hosts {PATH}