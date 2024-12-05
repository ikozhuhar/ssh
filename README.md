# ssh

cat ~/.ssh/id_rsa.pub | ssh root@ip-адрес-сервера 'cat >> ~/.ssh/authorized_keys'

ssh name@server_address 'mkdir -pm 700 ~/.ssh; echo ' $(cat ~/.ssh/id_rsa.pub) ' >> ~/.ssh/authorized_keys; chmod 600 ~/.ssh/authorized_keys'

ssh/config

![image](https://github.com/user-attachments/assets/b47ca297-d507-4387-ba56-ce56c4c0f87c)
