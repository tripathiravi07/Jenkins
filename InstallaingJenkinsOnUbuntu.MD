Jenkins Installation

apt-get install -y openjdk-8-jdk
apt-get install -y git maven
wget http://mirrors.jenkins.io/war-stable/latest/jenkins.war
java -jar jenkins.war

After installation,access http://public_ip:8080
Put the admin password and then create a user
