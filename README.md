# Altschool-ansible-task
This repository shows how Ansible can be used to automate apache and php from one server to another

##STEPS 
* set up 2 vagrant machines (control and target)
* updated and upgraded the vm
* installed python3 using the apt command
* installed ansible on the control vm 
* Generated an ssh key on the control vm and copied it to the target vm
* Added my hosts to my inventory file
* created a playbook to automate the tasks

## Ansible playbook file 
![ansible playbook to install apache and php](![setup](https://user-images.githubusercontent.com/102290896/198741607-00e20a00-681b-4592-97b1-7dee861699bf.png)

## Copy of systemctl status apache2
![A copy of the index.php file added to the target vm](![Apache2 restart ](https://user-images.githubusercontent.com/102290896/198742310-2ab5b569-77f1-471f-a878-1cc0e96483c5.png)

## Rendered page 
![A copy of the rendered image after executing the ansible playbook](![rendered page](https://user-images.githubusercontent.com/102290896/198745342-7200c10a-3fb3-47aa-95e0-a042e7f4afe4.png)



