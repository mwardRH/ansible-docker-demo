# ansible-docker-demo

Requires: 
ansible 2.1.0.0
python >=2.6
docker-py >=1.7.0
Docker API >=1.20

This demo shows how to use ansible to deploy a simple docker container. The docker container will simply echo "I'm Here." The "I'm Here" section will not show during the ansible-playbook run. To validate it worked, run "docker ps -a". You will see the container in recent history. 

When running this playbook make sure you change the host section. 

Run "ansible-playbook dockerHere.yaml" 
