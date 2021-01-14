# Devasc_Skills
I am going to present the practical tasks of the Netacad DevAsc Skills-Based exam.
## Task 1 -- Github Skills Test
### Preparation
* Git has to be installed on your local machine
* Registered account on Github
* A text editor to modify the README.md file
### Implementation
* Cloned the repository using `git clone repo url`
* Took screenshots and added to the local repository
* Added all file to the staging area
```
git add .
git commit -m 'Task 1 -- Github Skills Test'
```
* Pushed all the changes to the repository
```
git push
```
### Verification

![Cloning Repository](https://github.com/whitehacker/Devasc_Skills/blob/main/sc1.png?raw=true)
![Cloning Repository](https://github.com/whitehacker/Devasc_Skills/blob/main/sc2.png?raw=true)

## Task 2 - Ansible Skills Test
### Preparation:
* Installed Ansible
* Create three files - IOS_COMMANDS_PB.yaml (Ansible Playbook), hosts (Hosts file to access the hosts), and ansible.cfg (Ansible Configuration File)
### Implementation:
* The playbook name was sat in IOS_COMMANDS_PB.yaml file as follow:
```
---
- name: IOS_COMMANDS_PB
```
* Added the following lines to the hosts file
```
routers]
CSR1kv_1 ansible_user=cisco ansible_password=cisco123! ansible_host=192.168.173.130
CSR1kv_2 ansible_user=cisco ansible_password=cisco123! ansible_host=192.168.173.130
```
* Used the `ansible-playbook`command to run the playbook
```
> ansible-playbook IOS_COMMANDS_PB.yaml
```
