# Redis client connect with TLS

redis-cli -p 6379 --tls --cert /app/ssl/certs/redis/server.crt --key /app/ssl/certs/redis/redis.key --cacert /app/ssl/certs/redis/rootca.crt

redis-cli -p 26379 --tls --cert /app/ssl/certs/redis/server.crt --key /app/ssl/certs/redis/redis.key --cacert /app/ssl/certs/redis/rootca.crt

AUTH your_password


# To enable TLS for client connections

> tls-cert-file "/app/ssl/certs/server.crt"
> 
> tls-key-file "/app/ssl/certs/server.key"
> 
> tls-ca-cert-file "/app/ssl/redis/rootca.crt"
> 
> tls-port 6379
> 
> tls-auth-clients yes
> 
> tls-protocols "TLSv1.2"
> 
> tls-replication yes
