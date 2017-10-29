# express-first-docker
reference url is:http://blog.mpayetta.com/node.js/docker/mongodb/2016/09/04/dockerizing-node-mongo-app/

**Build**
`docker-compose build`

**Run**
`docker-compose up`

**Test**

* get 

`curl http://<your-ip>:3000/data/from/db`

* post

`curl -X POST -H "Content-type: application/json" http://<your-ip>:3000/data/into/db \
    -d '[ { "a": 1 }, { "b": 2 }, { "c": 3 } ]'`
