# Redis-Master-Slave-Docker-Compose
1. Create a Directory# mkdir /redis
2. cd /redis
3. Clone repository Inside the /redis directory
4.    git clone https://github.com/manjurulsys0101/Redis-Master-Slave-Docker-Compose.git
5. docker-compose up -d
6. docker ps -a
7. docker exec -it redis-master /bin/bash
8.       redis-cli
9.       auth my_pass
10.       ping
11.      info Replication
12. docker exec -it redis-slave-1 /bin/bash
13.      redis-cli
14.      auth my_pass
15.      ping
16.      info Replication
17. docker exec -it redis-slave-2 /bin/bash
18.      redis-cli
19.      auth my_pass
20.      ping
21.      info Replication
