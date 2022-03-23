##INSTALL JAVA AND MAVEN
#(raspbian has Java SE by default)
sudo apt-get install maven

## INSTALL LIBS

cd libs
sh mvn_install.sh 

## LOCAL TEST

cd iot-gateway
mvn spring-boot:run

curl http://localhost:8080/send?temp=20



