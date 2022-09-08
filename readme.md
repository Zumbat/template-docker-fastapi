#Genero immagine docker
docker build -t myimage .

#avvio docker container
docker run -d --name mycontainer -p 80:80 myimage