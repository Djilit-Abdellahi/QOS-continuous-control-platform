# ELK setup with docker
* First you need to install docker.
* To install the images, you should run from the current directory, the command `docker compose up`
* After the downloading and the install of the images (be patient it might take some time), you can run the following commands to check if everything is ok:
    * Elastic: `curl -I http://localhost:9200/`
    * Kibana: `curl -I http://localhost:5601/app/home#/`    
    * Logstash: `curl -I http://localhost:9600/`

In all the commands above, you should get a response containing `200 OK` for the services to work normally. 