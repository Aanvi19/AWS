##Password less authentication for 2 servers##

**for accessing one server from another**
```
ssh -i .pemfile username@ip of the remote server(public ip)
```
##To create a passwordless authentication##

**Amazon linux**
ssh-keygen -t rsa
cd /root/.ssh
id.rsa --- > Private key
id.rsa.pub ---> public key

**Ubuntu**
cd /root/.ssh
need to add public key on the remote root server --- 
authorized_keys -- you need to put the content of the id_rsa.pub into the authorized_keys.
