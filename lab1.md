# Lab 1: Create a Linux virtual machine with the AWS CLI

1. Launch AWS Cloud Shell:This is done From the AWS Management Console,To launch the Cloudshell, i Chose the AWS CloudShell icon.
3. Create virtual machine: I created a virtual machine with amazon lightsail. The virtual machine created was ubuntu lts.
4. Open port 80 for web traffic: To do this i ran  az vm open-port --port 80 --tayo --ubuntu
5. Connect to virtual machine: to do this i ran ssh azureuser@40.68.254.141
6. Install web server: To install a webserver (nginx), i ran the following bash script sudo apt-get -y update and 
sudo apt-get -y install nginx
7. View the web server in action

### Notes:

Quickstart: Create a Linux VM
* https://aws.amazon.com/getting-started/launch-a-virtual-machine-B-0/

Quickstart for AWS CloudShell
* https://docs.aws.amazon.com/cloudshell/latest/userguide/working-with-cloudshell.html