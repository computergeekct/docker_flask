# http://containertutorials.com/docker-compose/flask-compose.html
cd ~/IdeaProjects/docker_flask/
sudo docker ps -a
sudo docker build -t carlvdl/docker_flask .
sudo  docker run -d -p 5000:5000 carlvdl/docker_flask
#sudo docker run -p 49160:8080 -d carlvdl/docker_flask
# http://localhost:5000/
sudo docker ps -a
sudo docker rmi imagename
sudo docker rm -f imageid
sudo docker logs df97177245d8

#localhost:5000
