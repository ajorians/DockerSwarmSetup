# DockerSwarmSetup
Setup files with Docker Swarm.

Because this uses Ansible; first configure SSH. I did with no password:
ssh-keygen -b 4048 -t rsa -C "root login" -N ""

And then for each host:
ssh-copy-id root@client1
