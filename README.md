docker-libreoffice-convert for java spring 
=========================


### To build:
	Spostarsi nella directory e lanciare il comando
    `sudo docker build -t tornabene/convert .`
 

### To run:
  
    `sudo docker run -ti  -d -p 12022:12022  tornabene/convert  /usr/bin/java -Xms256m -Xmx768m  -jar  xxx.jar  --spring.profiles.active=prod `
    