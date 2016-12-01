# ni16-alf-Repo-Share
   Projet Java sous ECM Alfresco

===================================================
     Prérequis:
     ----------
     1-Maven
     2-JDK 7 ou 8
     3-Navigateur
===================================================
     Mettre en route:
     ----------------
     1-Git clone /ou telecharger le projet et le decompresser
     2-avec la terminal ou console se positionner sur la racine du projet et lancer la commande:
              ~:ni16-alf-Repo-Share mvn clean package
     3-Lancer le Repository Alfresco:
              ~ni16-alf-Repo-Share/alfApp-Repo mvn integration-test -Pamp-to-war
     4-Lancer le Share Alfresco:
              ~ni16-alf-Repo-Share/alfApp-Share mvn integration-test -Pamp-to-war
     5-http://localhost:808O/alfresco
     6- http://localhost:8081/share/page/  (login= admin, pwd= admin)
     7-créer un site public/privé...
     8-Créer des documents.
     9-Editer les proprietés des document pour modification de contenu de type, application des aspects....