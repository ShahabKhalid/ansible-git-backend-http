Git Backend HTTP
===========

This ansible deploys git server http on your ubuntu machine.

OS Support:
- Ubuntu


How To?
-------------

Update your ubuntu machine ip in `production` file!

    [git-server]
    git_server ansible_ssh_host='192.168.100.10'
    
Update path to ssh private id `ansible.cfg`

    private_key_file=id_rsa

Run Playbook
-------

	ansible-playbook gitserver.yaml


Pre Req.
------------

cql-migrate requires pyparsing and the datastax python cassandra driver.

	sudo apt-get install ansible


