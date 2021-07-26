# redis


redis-cli -p 6379 --tls --cert /app/ssl/certs/redis/server.crt --key /app/ssl/certs/redis/redis.key --cacert /app/ssl/certs/redis/rootca.crt

redis-cli -p 26379 --tls --cert /app/ssl/certs/redis/server.crt --key /app/ssl/certs/redis/redis.key --cacert /app/ssl/certs/redis/rootca.crt

AUTH your_password
