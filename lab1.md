# Lab 1: Create a Linux virtual machine with the AWS CLI

1. Launch AWS Cloud Shell:This is done From the AWS Management Console,To launch the Cloudshell, i Chose the AWS CloudShell icon.
3. Create virtual machine: I created a virtual machine with amazon lightsail. The virtual machine created was ubuntu lts.
4. Open port 80 for web traffic: To do this, i clicked the "Network & Security" -> Security Group settings in the left hand navigation, Found the Security Group that my instance is apart of,Clicked on Inbound Rules and Used the drop down and add HTTP (port 80)
5. Connect to virtual machine: To do this i visited  the Azure portal to connect to a VM. Searched for and selected Virtual machines.I Selected the virtual machine from the list. At the beginning of the virtual machine page, i selected Connect.
6. Install web server: To install a webserver (nginx), i ran the following bash script sudo apt-get -y update and 
sudo apt-get -y install nginx
7. View the web server in action

### Notes:

Quickstart: Create a Linux VM
* https://aws.amazon.com/getting-started/launch-a-virtual-machine-B-0/

Quickstart for AWS CloudShell
* https://docs.aws.amazon.com/cloudshell/latest/userguide/working-with-cloudshell.html
