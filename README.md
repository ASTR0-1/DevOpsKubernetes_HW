docker build . -t dukhovny/docker_hw_kubernetes
docker run -p 49160:80 -m 100m --cpus="2" -d dukhovny/docker_hw1