# jenkins_ansible
this is a simple ansible playbook to install jenkins on your server
# Note:
you need to define group on nodes that you want in /etc/ansible/hosts
for example in this  playbook i defiend a group on server named it jenkins.
don't forget to config ansbile_ssh_user in /etc/ansbile/group_vars/servers
example: /etc/ansible/group_vars/servers --- ansible_ssh_user: root
