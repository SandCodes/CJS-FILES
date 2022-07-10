# Notes for Saturday June 9, 2022

### Things covered today:

1. docker-compose.yml file syntax and conventions *link to compose file*
2. the concepts of running docker in swarm mode *link to swarm docs*
3. how to initialize a git repository
4. how to connect an authorized user's local repo to a remote github repo
5. how to push your files to github
6. learned some of the features of github
   1. issues *link to purpledurple issues*
   2. projects *link to purpledurple proj board*
   3. github markdown syntax *get gh md cheatsheet*
7. networking
   1. ip address and port numbers
   2. tcp and udp protocols

***
## Docker Swarm Notes
### Features of Docker Swarm
1. Decentralized Access
2. High Security
3. Auto Load Balancing
4. High Scalability
5. Roll-Back Environment To A Previous State (Safer Environment, If Needed)
   
### Containers & Services
- In Swarm, containers are launched using rest services.
   - Services are a collection of containers of the same image that are launched together.
  
### Requirements for Docker Swarm
- Manager Node and Client/Worker Node are needed to deploy a service in docker swarm.
  - Manager node maintains cluster management tasks (Like a server)
    - Can see the status of all the worker nodes in a cluster!
  - Worker node receives and excecutes tasks from the manager node. (Like a client)
    - If manager tells worker to run as a mySQL environment, the worker will convert to a mySQL environment.

# Communication between Manager and Worker Nodes are done by using a REST API
