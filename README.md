# Run redis instance
docker run redis

# This is to run image 
docker-compose up
# Or to launch it in background
docker-compose up -d

# --build startup our image with all the chnegs
docker-compose up --build

# To validate all the available images
docker ps --all
docker ps

# To stop all containers
docker-compose down

# to remove all the images from syste
docker system prune
-------------------------------------------------


