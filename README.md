# Ansible-Roles

Continuous Integration Server:

yum install java-1.*

or
sudo amazon-linux-extras install java-openjdk11

alternatives --config java


sudo wget -O /etc/yum.repos.d/jenkins.repo http://pkg.jenkins-ci.org/redhat/jenkins.repo

sudo rpm --import https://jenkins-ci.org/redhat/jenkins-ci.org.key

sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key

sudo yum install jenkins -y

sudo systemctl enable jenkins

sudo systemctl start jenkins
