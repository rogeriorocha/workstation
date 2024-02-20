# workstation


sudo apt update && sudo apt install -y unzip ansible git 

git clone https://github.com/rogeriorocha/workstation.git

ansible-playbook tools/ubuntu.yml --ask-become-pass