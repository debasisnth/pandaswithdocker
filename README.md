# pandas with docker, Jupyter 


# 1. Where to put project CVS 
place your csv in 'data' folder first,  where 'a.txt' is located



# 2. Docker and Docker-compose should be installed

# 3.  Docker build , container run  in background  (VVI)
sudo docker-compose  up -d --build

or
sudo docker-compose up --build --force-recreate --no-deps


# Docker related

# 4. to check the  <container name>
docker ps -a

# 5. docker exec:   bash inside the container (VVI)
docker exec -it  <container name>  bash

eg:	
docker exec -it  v12_app_1  bash

# 6. to check the list to copy the Jupyter link! 

jupyter notebook list


eg:
http://0.0.0.0:8888/?token=6be51449d83048fbb273b6654309ada0564b9ba86b730b60


