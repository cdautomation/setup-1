1  apt-get update
    2  apt-get install zip unzip git sudo tree 
    3  apt-get install wget curl
    4  git --version
    5  cd /opt
    6  wget http://mirrors.estointernet.in/apache/maven/maven-3/3.6.0/binaries/apache-maven-3.6.0-bin.zip
    7  wget http://mirrors.estointernet.in/apache/tomcat/tomcat-8/v8.5.37/bin/apache-tomcat-8.5.37.zip
    8  cat /etc/os-release
    9  sudo add-apt-repository ppa:webupd8team/java
   10  apt-get install add-apt-repository
   11  sudo apt update && sudo apt install oracle-java8-installer
   12  java -version
   13  sudo apt update && sudo apt-get install oracle-java8-installer
   14  sudo apt-get update && sudo apt-get install oracle-java8-installer
   15  sudo apt-get install software-properties-common
   16  sudo add-apt-repository ppa:webupd8team/java
   17  sudo apt-get update
   18  sudo apt-get install oracle-java8-installer
   19  java -version
   20  sudo add-apt-repository -r ppa:webupd8team/java
   21  echo "JAVA_HOME=$(which java)" | sudo tee -a /etc/environment
   22  source /etc/environment
   23  echo $JAVA_HOME
   24  sudo apt-get install openjdk-8-jdk
   25  sudo apt-get install openjdk-8-jre
   26  ls
   27  unzip apache-tomcat-8.5.37.zip 
   28  ls
   29  cd apache-tomcat-8.5.37
   30  ls
   31  cd conf/
   32  ls
   33  vi server.xml 
   34  apt-get install vim
   35  vi server.xml 
   36  history
   37  chmod +x /opt/apache-tomcat-8.5.37/bin/startup.sh shutdown.sh
   38  chmod +x /opt/apache-tomcat-8.5.37/bin/shutdown.sh
   39  find / -name context.xml
   40  vi /opt/apache-tomcat-8.5.37/webapps/host-manager/META-INF/context.xml
   41  vi /opt/apache-tomcat-8.5.37/webapps/manager/META-INF/context.xml
   42  cd ../bin/startup.sh 
   43  cd ..
   44  ls
   45  cd bin/
   46  ls
   47  ./startup.sh 
   48  chmod +x catalina.sh 
   49  ./startup.sh 
   50  history
   
   
   
   
   https://vitux.com/how-to-install-and-configure-apache-web-server-on-ubuntu/
