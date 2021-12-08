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
   - Backup : `bash -c 'mongodump -u root -p password --archive' > ./db/all-collections.archive`
   - Restore : `mongorestore /dump`
   
4. Docker-compose :
   - docker-compose up 
   - docker-
5. React :
   - 
# Reference