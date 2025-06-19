# Ansible
What is ansible playbook?
it is a list of plays which contains modules that can do specific task.
#commandvs Shell
ansible.builtin.command
command -- simple command (secure) (it will not go inside server)
ansible.builtin.shell
shell  - complex commands (pipes, re-directions) it will go inside server and get the work done