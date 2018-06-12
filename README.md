# build image
docker build . -t marklogic9

# run image
docker run -d --name=mark9 -p 8001:8001 marklogic9 

# http://localhost:8001
https://developer.marklogic.com/blog/building-a-marklogic-docker-container
