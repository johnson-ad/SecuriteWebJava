# MavenProject_Compte-Droit
Ceci est un projet maven intégré du web

<groupId>com.groupeisi</groupId>
<artifactId>Project_JPA</artifactId>
<version>0.0.1-SNAPSHOT</version>
<packaging>war</packaging>
<name>Project_JPA</name>
cription>Project maven & web</description>


Tout d'abord, nous avons ajouté toutes les dépendances nécessaire au bon fonctionnement du projet dans le fichier "pom.xml".
Pour ensuite créer nos différents packages dans "src/main/java" à savoir :
- com.project.config : pour y configurer la connexion à la base de données en utilisant JPA.
- com.project.dto : qui compose nos entités.
- com.project.dao : composé d'interfaces et de classes qui implémentent ces interfaces. C'est là où on definit l'ensemble des opérations effectuables.
- com.project.filter : pour gérer la gestion de la sécurité.
- com.project.web : qui compose l'ensemble de nos servlets.

En ce qui concerne les vues, nous avons créé un fichier "index.jsp" dans "src/main/webapp/" puis un fichier "home.jsp" dans "src/main/webapp/WEB-INF/" .
Ainsi, nous avons aussi créé un dossier "view" dans "src/main/webapp/WEB-INF/" et dans "view" nous avons deux sous dossiers à savoir : "compte" et "droit" .
Dans chacun de ces dossiers nous avons les fichiers "add.jsp" et "list.jsp" pour pouvoir ajouter ou lister.


======== AUTHENTIFICATION =========


![login](https://user-images.githubusercontent.com/95770196/213324465-887857ed-c302-4c0d-9ea2-c58eccf4f518.PNG)



======== ADD DROIT =========


![image](https://user-images.githubusercontent.com/95770196/213323783-704e0600-6070-4f2e-99e1-8cb0101c07e5.png)



======== LIST DROIT =========


![image](https://user-images.githubusercontent.com/95770196/213323880-a0e65dd4-e49d-4870-9376-dcfb3919c75d.png)



======== ADD COMPTE =========


![image](https://user-images.githubusercontent.com/95770196/213324177-c0995bc8-c3ca-4038-953e-1dc4973d7ce0.png)


======== LIST COMPTE =========
![image](https://user-images.githubusercontent.com/95770196/213324268-9f4d6a67-0de8-429d-8923-7db9b468781e.png)
