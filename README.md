# docker_compose
1. sudo curl -L "https://github.com/docker/compose/releases/download/1.28.5/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
2. sudo chmod +x /usr/local/bin/docker-compose
3. docker-compose --version
4. docker swarm init
5. cd /home
6. ls
7. mkdir docker_compose
8. chmod -r 777 docker_compose/
9. chmod -r 0777 docker_compose/
10. chmod -R 0777 docker_compose/
11. ls -la
12. cd docker_compose/
13. ls -la
14. git clone https://github.com/dockersamples/example-voting-app.git
15. ls
16. cd example-voting-app/
17. nano docker-compose-vote.yaml
18. nano docker-compose-result.yaml
19. nano docker-compose-worker.yaml
20. nano docker-compose-redis.yaml
21. nano docker-compose-db.yaml
22. edit docker-compose-db.yml  docker-compose-redis.yml  docker-compose-result.yml  docker-compose-vote.yml  docker-compose-worker.yml
23. docker-compose -f docker-compose-db.yml -f docker-compose-redis.yml -f docker-compose-result.yml -f docker-compose-vote.yml -f docker-compose-worker.yml up -d
24. http://34.67.17.135:5001/ итог голосования
25. http://34.67.17.135:5000/ голосование
