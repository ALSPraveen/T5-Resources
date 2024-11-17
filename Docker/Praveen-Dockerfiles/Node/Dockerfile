
From node:21-alpine3.18

COPY . .  

# We are copying the files to container.Unlike for web servers we dont need to copy it to any particular location to display our static cotent.We just run the server.js file 

EXPOSE 8070 
#In node , there wont be any port tagged by default for running container unlike in nginx or httpd web severs.(You can find that from dockerhub ->image).When we expose to 80 , it means we are opening port 80 for container to run.We further need to bind it to other cotainer in our host machine to see the output.*/

CMD ["node","server.js"]
