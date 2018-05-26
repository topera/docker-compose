# Topera's Hello World #017
## Docker Compose
This hello world shows how to use Docker Compose.
In this docker compose we are starting a Jenkins and a Sonar server at same time.

## How to download this source code
* Use the `Clone or download` button above the get the url of this repository
* In IntelliJ IDEA: File → New → Project From Version Control -> Git -> put the url of this repository

## How to test
* Create a folder that Jenkins will use
    * `$ mkdir ~/jenkins; chmod 777 ~/jenkins`
* Start dockers
    * `$ sudo docker-compose up -d`
        * The `-d` is from daemon, that is, to run in background
* See logs
    * `$ sudo docker-compose logs`
* Access Jenkins in http://localhost:8080
* Access SonarQube in http://localhost:8081
* To see docker containers running:
    * `$ sudo docker ps`
* To stop all containers of this composer:
    * `$ sudo docker-compose stop`

## Tech Stack
* Intellij IDEA 2018.1
* Docker version 18.03.1-ce

To take a look in other projects, please see https://github.com/topera/index


