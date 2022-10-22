# Lab_3_Full-Stack_Docker
ssh-keygen
 
 docker build -t simpleweb -f Dockerfile .
 
 docker tag simpleweb damianflis1999/simpleweb
 
 docker run -p 8080:8080 -d simpleweb
