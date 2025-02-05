# todo-project

### Prerequisite: Docker
https://docs.docker.com/engine/install/

### Installation Guide
Download the docker-compose.yaml from this repo

Clone the repositories from \
https://github.com/ClintonTSR/todo-node-server \
https://github.com/ClintonTSR/react-todo-app 

Put the cloned repositories into the same folder as docker-compose.yaml, \
the folder structure should look like this:
```
app (root folder)
 | - docker-compose.yaml
 | - todo-node-server
 | - react-todo-app
```

Open Terminal from that folder \
Execute the following two commands: 

`docker-compose build` 

`docker-compose up`

### How to use
Once installation completed, visit http://localhost:3000 to access the web page.
