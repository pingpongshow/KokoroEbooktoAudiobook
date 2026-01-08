The aim of this project is to convert ebooks to audiobooks using Kokoro TTS. The application supports voice mixing and compression to the audiobooks with minimal noticable quality change. 
It runs within a docker environment the host a web based GUI for user interactions. Both CPU and NVIDIA GPU are supported. 

Installation is done by placing the docker-compose folder in your desired directory and making modifications to this file to suit your needs. 
Therefore it is essential that you have docker and docker compose installed on your system. 
this was tested on an unraid system and is fully functional with a Nvidia RTX 3080. 

Change your desired port number ebook and audiobook mountpoints. 

docker-compose build --no-cache
docker-compose up -d

Access your web based gui at http://yourip:port

