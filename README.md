# Docker sur linux   

___

![image](https://github.com/techerbeatrice/docker_sur_linux/assets/138071140/ab169a9c-3886-4670-89c7-ef7ee459701f)

![image](https://github.com/techerbeatrice/docker_sur_linux/assets/138071140/7441ebd0-9f71-4438-9a0d-1eb1f66ff53d)

![image](https://github.com/techerbeatrice/docker_sur_linux/assets/138071140/39c57e40-3bdf-406e-b2c0-fef610c91ea4)

____

**docker image ls** pour afficher la liste des images   

![image](https://github.com/techerbeatrice/docker_sur_linux/assets/138071140/cd1648bc-e48e-49ec-b459-87d0a451f71c)

___

**docker image pull hello-world** pour récupérer une image

![image](https://github.com/techerbeatrice/docker_sur_linux/assets/138071140/4c5b6b91-84bd-4fa3-a32a-7218978f7e18)

___

Il est possible de supprimer des images locales avec la commande docker image **rm (ou docker rmi en raccourci)**.      

___

👉 Lancer un conteneur   
L'exécution d'une image consiste pour Docker à créer un conteneur.   

**docker run hello-world** exécute l'image **hello-world**  

![image](https://github.com/techerbeatrice/docker_sur_linux/assets/138071140/ecf9a687-3e65-44b7-8970-adefc0bc6cc3)

![image](https://github.com/techerbeatrice/docker_sur_linux/assets/138071140/949e14b4-5001-4b6a-9e8c-d9b2f3e61c8b)

___

🔬 Lancement d'un conteneur serveur    
Tentons maintenant d'exécuter un conteneur serveur.   
Lance directement le conteneur avec la commande docker run -dp 8000:80 httpd.   
L'option d pour l'executer en tâche de fond, et l'option p 8000:80 pour indiquer de mettre en port 8000 de l'hôte en écoute et de transferer les paquets qui y arrivent sur le port 80 du conteneur.   

![image](https://github.com/techerbeatrice/docker_sur_linux/assets/138071140/4119a4d4-08d4-4f3f-be74-ae468a427a74)

____

