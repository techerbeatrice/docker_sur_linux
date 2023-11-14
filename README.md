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

![image](https://github.com/techerbeatrice/docker_sur_linux/assets/138071140/4119a4d4-08d4-4f3f-be74-ae468a427a74)

![image](https://github.com/techerbeatrice/docker_sur_linux/assets/138071140/596a711c-be0c-4e1b-ac70-58c0db88da00)

![image](https://github.com/techerbeatrice/docker_sur_linux/assets/138071140/4d1ea58c-4bcd-40b0-ac10-cfe82db4babf)

![image](https://github.com/techerbeatrice/docker_sur_linux/assets/138071140/3eef6874-a036-4b16-9c1f-f677e979d3f1)

![image](https://github.com/techerbeatrice/docker_sur_linux/assets/138071140/f0793e36-4dd7-427c-8178-6d75f9f24a3f)

____

🔬 Lancement d'un conteneur serveur  

![image](https://github.com/techerbeatrice/docker_sur_linux/assets/138071140/f864036c-b100-4643-bc48-ada261f551e4)

On peut aussi vérifier que le port 8000 est bien ouvert sur le système hôte.   

![image](https://github.com/techerbeatrice/docker_sur_linux/assets/138071140/839c027d-cffb-48f2-b9a3-00d3bc8f2c41)

Et surtout plus intéréssant, on peut maintenant se connecter sur le serveur web en insérant http://localhost:8000 dans la barre d'adresse.    

![image](https://github.com/techerbeatrice/docker_sur_linux/assets/138071140/ca70bb80-d04f-4311-9069-531d36c3682d)
