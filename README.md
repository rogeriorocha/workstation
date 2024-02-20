# workstation


## prepare
sudo apt update && sudo apt install -y unzip ansible git 

## clone
git clone https://github.com/rogeriorocha/workstation.git

## ansible run
ansible-playbook workstation/ubuntu-workstation.yml --ask-become-pass