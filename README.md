#provission it
sudo docker build -t "toradex"
# run it
sudo docker run -it -t "toradex" /bin/bash
#clean up 
docker system prune -a
#clean up even more
sudo docker system prune -a

