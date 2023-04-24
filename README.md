# Example Shell
## Current Documentation Version:
- Latest Update Version 1.0.0, updated by matthew branche on 02/02/2023

## Introduction
This repo is to provide an example Jenkins pipeline used to deploy configurations, and specifically in this example a pipeline that uses a dockerized Ansible playbook to install Python 3.11 with a virtual environment, Docker, Docker Compose, and Make on Ubuntu 22.04, RHEL 9.1, and AlmaLinux 9.1.

## Running Shell
- To run this jenkins file, requires a deployed jenkins instance, with a slave already setup, with docker installed, as well as the docker plugin on jenkins installed and ready for pipelines.
- Please fill out the necessary server_inventory.ini with your list of servers, and build pipeline.

## Reference Documentation
- https://www.jenkins.io/doc/pipeline/tour/hello-world/
- https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_intro.html
- https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-22-04
- https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-compose-on-ubuntu-22-04

## License
[MIT](https://choosealicense.com/licenses/mit/)
