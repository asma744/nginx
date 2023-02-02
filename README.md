Installaion docker ( https://www.docker.com )
Télécharger une image Nginx : docker pull nginx
Exécuter l'image : docker run nginx
Exporter le port sur 8081 : docker run -p 8081:80 nginx
Exporter l'image en arriére plan : docker run -tdi -p 8081:80 nginx
Changer le nom du containeur : docker run -tdi -p 8081:80 --name nom-container nom-image


les containeur actif : docker ps
tous les containeurs : docker ps -a

entrer dans le containeur : docker exec -it id-containeur /bin/bash 
pour modifier le contenue de fichier : cd /usr/share/nginx/html/ puis vim et puis vi index.html pour ouvrir le fichier index.html et faire des modifications

