
# To crete image 
docker build -t cuckoo/visits .
# To run image as container
docker run -p 9090:8081 cuckoo/visits

# To validate all the available images
docker ps --all
docker ps

# to remove all the images from syste
docker system prune

