**Preparation**: git clone https://github.com/skuzmin90/ansible_epam.git && cd ansible_epam

## Task 1
* **Install apache**: ansible-playbook playbooks/task1.yaml --tags install_apache  
* **Delete apache:** ansible-playbook playbooks/task1.yaml --tags delete_apache  
* **Configure grub:** ansible-playbook playbooks/task1.yaml --tags configure_grub  
* **tags**: install_apache; delete_apache; configure_grub

## Task 2  
* **Command to use**: ansible-playbook playbooks/task2.yaml --vault-password-file=vault_pass  

## Task 3  
