docker-drupal
=============
### Learning Docker http://docker.io/ by creating a drupal

### To build:

	Spostarsi nella directory e lanciare il comando
    sudo docker build -t tornabene/docker-drupal .
### To run:
    sudo docker run -d --name db -t  tornabene/docker-drupal
    sudo docker run -P -d --name drupal --link db:DB  tornabene/docker-drupal

 
 
