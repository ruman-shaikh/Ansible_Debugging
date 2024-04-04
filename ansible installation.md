1. Download the SSH key file
2. Open terminal and naviaget to the downloaded folder and chnage the SSH key file permission
`chmod 400 <filename.pem>` - Example: `chmod 400 ubuntu.pem`
3. Now onnect with the ubuntu machine by running the following command
`ssh -i <filename.pem> <username>@<public_IP_address> -p 2223`
Example: `ssh -i ubuntu.pem itzuser@163.74.88.66 -p 2223`
4. Run the follwing commands to install ansible
`sudo apt update`
`sudo apt install software-properties-common`
`sudo apt-add-repository --yes --update ppa:ansible/ansible`
`sudo apt install ansible`
5. Run the following to check if ansible is installed
`ansible --version`