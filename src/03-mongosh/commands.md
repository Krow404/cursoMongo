
## connect to container mongosh

docker-compose exec mongodb bash

# connect with mongosh

mongosh "mongodb://root:2332@localhost:27017/?tls=false"

show dbs
show collection

