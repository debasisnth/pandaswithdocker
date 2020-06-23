# pandas with docker, Jupyter 


# 1. Where to put project CVS 
place your csv in 'data' folder first,  where 'a.txt' is located



# 2. Docker and Docker-compose should be installed

# 3.  Docker build , container run  in background  (VVI)
sudo docker-compose  up -d --build



# Docker related

# 4. to check the  <container name>
docker ps -a

# 5. docker exec:   bash inside the container 
docker exec -it  <container name>  bash

eg:	
docker exec -it  v12_app_1  bash

# 6. to check the list to copy the Jupyter link! 
jupyter notebook list



