# wekan
Project Collaboration Tool Like Kanban/Trello

## Download 
````
git clone https://github.com/otn4mrehus/wekan_docker.git
cd wekan_docker
````

## Run Containers
````
docker-compose -p 'wekan' up --build -d --remove-orphans
````

#### Remove Containers
````
docker-compose -p 'wekan' down -v --remove-orphans
````

#### Start/Stop Containers
````
docker-compose -p 'wekan' start | stop
````

## Browse Project
````
http://127.0.0.1:8080
user: admin
Pass: admin123
````
