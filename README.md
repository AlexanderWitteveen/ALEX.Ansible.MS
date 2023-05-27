# Ansible Collection - alex.ms collection
Documentation for the collection.

# Install
ansible-galaxy collection install git+https://github.com/AlexanderWitteveen/ALEX.Ansible.MS.git

# Use playbook
vars="{\"args_host\":\"hostname\"}"  
export ANSIBLE_CONFIG=/etc/ansible/ansible.cfg  
ansible-playbook alex.ms.install.dotnet -vv --extra-vars "$vars"  

