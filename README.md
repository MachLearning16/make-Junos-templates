# Using Ansible to create Junos templates
The AnsibleGuide_vXX.docx will guide you to create a template file, variable file and a playbook to merge your template with your desired variables

In order to execute a playbook you need to install Ansible onto your system.

##Installing Ansible on a Linux OS
1) Install Ansible using command:  
  * sudo apt-get install ansible -y  
   
##Installing Ansible on a Windows OS
1) You will need to install Cygwin (which is a unix-like environment)
  * https://cygwin.com/install.html
    
2) You will need python modules on Cygwin to allow you to run Ansible commands  
  * http://everythingshouldbevirtual.com/ansible-using-ansible-on-windows-via-cygwin   
    
##Running a playbook  
In order to run a playbook you need to navigate to the folder in which your playbook is located
  * cd **_Playbook_Folder_Path_**  
    
You will then need to run your playbook using the command:  
  * ansible-playbook **_Playbook_Folder_Path_**/main_play.yaml
   
### End result     
There we have it, you will have a completed Junos template file named "test.conf" in the same location as your playbook.  
  
###Troubleshooting  
If you have issues running the playbook, read the error messages you get and use google
