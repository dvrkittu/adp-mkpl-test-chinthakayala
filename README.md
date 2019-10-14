# adp-mkpl-test-chinthakayala
Dev-Ops exercise of Jenkins,Ansible
Here we do few execises on 

Getting Started
This repo is used to install nodejs and npm package in Suse 
nodejs_setup is the ansible role created 
nodejs_setup.yml is the file which needs to be executed by ansible ,which inturn calls nodejs_setup role

ansible-playbook nodejs_setup.yml -e nodejs_version=nodejs10
