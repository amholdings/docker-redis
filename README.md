# docker-redis
amholdings/docker-redis

Docker Conainer for Redis on CentOS7

# Build Container:
git clone https://github.com/amholdings/docker-redis.git

cd docker-redis

docker build --tag="docker-redis" .

# Run Container as daemon:

docker run -d --name "docker-redis" -p 6379:6379 amholdings/docker-redis
