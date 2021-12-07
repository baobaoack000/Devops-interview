# Getting Started
- Tools : Cirle-CI , Github , Docker , Git .
- Installation : MongoDB, Express , React , Node.JS
# How to boot up
1. Express :
   - docker build . -t <your username>/express-node
   - docker run -p 49160:8080 -d <your username>/express-node
   - docker logs <container id>
   - curl -i localhost:8080
3. Mongodb :
   - mongo -u "root" -p "password"
   - Backup : `docker-compose exec db sh -c 'exec mongodump -d test --archive' > ./db/all-collections.archive`
   
4. Docker-compose :
   - docker-compose up 
5. React :
   - 
# Reference