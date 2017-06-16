# Install_Jenkins

1  sudo apt-get update
    2  sudo apt-get install oracle-java8-installer
    3  sudo add-apt-repository ppa:webupd8team/javasudo add-apt-repository ppa:webupd8team/javasudo add-apt-repository ppa:webupd8team/java
    4  sudo add-apt-repository ppa:webupd8team/java
    5  sudo apt-get update
    6  sudo apt-get install oracle-java8-installer
    7  javac -ersion
    8  javac -version
    9  java -version
   10  sudo apt-get install oracle-java8-set-default
   11  sudo nano /etc/environment
   12  sudo apt-get install language-pack-en
   13  wget -q -O - http://pkg.jenkins-ci.org/debian/jenkins-ci.org.key | sudo apt-key add -
   14  echo "deb http://pkg.jenkins-ci.org/debian binary/" | sudo tee -a /etc/apt/sources.list.d/jenkins.list
   15  sudo apt-get update
   16  sudo apt-get install jenkins
