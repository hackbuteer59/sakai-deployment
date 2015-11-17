
cd docker-sakai

docker build -t docker-sakai

docker run -p 8080:8080 docker-sakai 