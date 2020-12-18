#Jenkins docker
Jenkins CI with docker client
-------------------------------------------

make sure to change the "998" or line 9 with the GID(group ID) your docker group has on your system. To check run: 

"cat /etc/group |grep docker"
  or alternatively
"getent group docker"

to find the group id of docker on your system.
