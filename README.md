# Redis-Master-Slave-Docker-Compose
1. Create a Directory# mkdir /redis
2. cd /redis
3. Clone repository Inside the /redis directory
4.    git clone https://github.com/manjurulsys0101/Redis-Master-Slave-Docker-Compose.git
5. docker-compose up -d
6. docker exec -it redis-master /bin/bash
7.       redis-cli
8.       auth my_pass
9.       ping
10.      info Replication
11. docker exec -it redis-slave-1 /bin/bash
12.      redis-cli
13.      auth my_pass
14.      ping
15.      info Replication
16. docker exec -it redis-slave-2 /bin/bash
17.      redis-cli
18.      auth my_pass
19.      ping
20.      info Replication
