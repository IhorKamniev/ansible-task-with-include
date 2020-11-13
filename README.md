# ansible-task-with-include
Updated version of ansible-task

Setup

    1. Move hosts file to /etc/ansible/hosts. Change hosts IP addresess according to actual ones.
    2. Specify path to private key in hosts file.
    3. Run command:
    $ sudo ansible-playbook envs_playbook.yml -e '{"install":false}'
    to skip install of packages task


