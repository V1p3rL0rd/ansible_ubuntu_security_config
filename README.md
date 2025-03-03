# Ansible ubuntu basic security configuration
This is a very simple Ansible playbook will help you configure basic security settings on Ubuntu hosts.

The playbook contains several tasks:

1) Ensure UFW is installed
2) Allow SSH through UFW
3) Allow HTTP through UFW
4) Allow HTTPS through UFW
5) Allow Zabbix Server through
6) Enable UFW
7) Ensure fail2ban is installed
8) Configure fail2ban for SSH
9) Ensure fail2ban is enabled and started
10) Ensure AppArmor is installed
11) Ensure AppArmor is enabled and started 
