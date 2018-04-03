# Local Ansible Setup

This is my repo for storing ansible roles and playbooks to set up my local computer. I have organized the repo into OS directories since a lot of steps will be OS specific.

Most of the roles set a version in `defaults/main.yml` and need to be periodically updated to ensure the latest versions are installed. I try and keep everything as idempotent as possible so that this can be run over and over.
