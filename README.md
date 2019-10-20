# KB

ssh-keygen -t rsa
cat localhost-private_key.pub >> ~/.ssh/authorized_keys
ssh localhost -i localhost-private_key

ansible-playbook -i hosts playbook.yml

chmod 600 /Users/sm/.ssh/authorized_keys


https://www.youtube.com/watch?v=ZkFIozGY0IA
