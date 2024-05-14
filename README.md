"# nostr-jamps" 

This readmefile has the information on the nostr project

#First step is to build a image to the dockerfile in the rnostr relay 

docker build -t rnostr/rnostr

#then run this docker image and port the host port 7000 to the 8080 port in the container

docker run -p 7000:8080 rnostr/rnostr

you can access this relay on your web browser on 

http://localhost:7000/

you can stop the relay as follows 

docker stop rnostr/rnostr


ajs branch

This is the nostr repo 