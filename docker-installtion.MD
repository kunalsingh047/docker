
yum install http://vault.centos.org/centos/7.3.1611/extras/x86_64/Packages/container-selinux-2.9-4.el7.noarch.rpm

Type the following command to install the latest version of Docker CE (community edition):

sudo yum remove docker docker-common docker-selinux docker-engine

sudo yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo

sudo yum install docker-ce

systemctl enable docker.service


 sudo systemctl start docker.service ## <-- Start docker ##
	
 sudo systemctl stop docker.service ## <-- Stop docker ##
	
 sudo systemctl restart docker.service ## <-- Restart docker ##
	
 sudo systemctl status docker.service ## <-- Get status of docker
