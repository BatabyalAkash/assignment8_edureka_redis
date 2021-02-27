# redis-cache-express-api

# start redis-server in a terminal

redis-server

# start redis-cli in a teminal

redis-cli
keys \*

# start express server

cd assignment8_edureka_redis
npm install
npm start

# open a browser and navigate to the following url

localhost:3300/getWiki?country=india

# refresh the browser & the 2nd query will come from redis

# use redis-cli to check the cache

127.0.0.1:6379> keys \*

1. "wiki:india"
