Ce site présente le projet Formation en Génie Logiciel pour le développement d’applications en support à la population vieillissante, financé par le programme Samuel de Champlain. 



## Comment administrer le site ?


### Les compétences 

Toutes les compétences sont décrites dans le fichier _data/competences.yml
Chacune d'entre elles est composée de trois éléments : un nom (name), une courte description (short) et une image représentative (image). 

Elles sont affichées dans la page d'accueil, home. Cet affichage peut être modifié dans _layouts/home.html 


### L'équipe 

Tous les membres de l'équipe sont décrits dans le fichier _data/authors.yml
Il y a, pour le moment, trois types de membres de l'équipe : 
    - les membres principaux de l'équipe, dont la position est "equipe". Pour ces membres, on doit y renseigner le nom (name), l'avatar (avatar), une url externe si voulu (url), l'institution (institution) et une courte description (short). 
    - les institutions impliquées dans le projet, dont la position est "institution". On doit ajouter le nom de l'institution (name) et le logo (logo). 
    - les intervenants, dont tla position est "intervenant". Pour eux, il faut entrer le nom (name), d'où vient cet intervenant (institution), la date de l'intervention (date), et sa contribution (contribution). 
    
Les paramètres de la page de l'équipe peuvent être modifiés dans le fichier pages/aequipe.html. On peut notamment y modifier le titre de la page et l'image du header. 
Le contenu de la page peut être modifié dans le fichier _includes/equipe.html
Enfin, le style de la page peut être modifié dans le fichier _sass/includes/_equipe.scss. 


### Les enseignements 

Chaque enseignement correspond à un fichier .md du dossier _enseignements/ 
La cartouche d'un enseignement doit à minima contenir :
    - un layout (enseignement)
    - un title
    - une date 
    - des authors (séparés par une virgule s'il y en a plusieurs, et correspondant aux noms des authors spécifiés dans le fichier _data/authors.yml)

On peut y rajouter les cartouches suivantes : 
    - level (un entier entre 0 et 10 qui décrit la difficulté de l'enseignement)
    - institution 
    - link (qui correpond au lien externe de l'enseignement)
    - ihm (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Interaction Homme-Machine dans cet enseignement)
    - user (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Prise en compte de l'utilisateur dans cet enseignement)
    - ia (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Intelligence Artificielle dans cet enseignement)
    - io (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Internet des Objets dans cet enseignement)
    - gl (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Génie Logiciel dans cet enseignement)
    - techno (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Technologies dans cet enseignement)
    

### Les supports de cours  

Chaque support de cours correspond à un fichier .md du dossier _supportscours/ 
La cartouche d'un support de cours doit à minima contenir :
    - un layout (support)
    - un title
    - une date 
    - des authors (séparés par une virgule s'il y en a plusieurs, et correspondant aux noms des authors spécifiés dans le fichier _data/authors.yml)
    - un enseignement (l'enseignement dans lequel ce support a été utilisé)

On peut y rajouter les cartouches suivantes : 
    - level (un entier entre 0 et 10 qui décrit la difficulté du support de cours)
    - institution 
    - link (qui correpond au lien externe du support de cours)
    - ihm (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Interaction Homme-Machine dans ce support de cours)
    - user (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Prise en compte de l'utilisateur dans ce support de cours)
    - ia (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Intelligence Artificielle dans ce support de cours)
    - io (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Internet des Objets dans ce support de cours)
    - gl (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Génie Logiciel dans ce support de cours)
    - techno (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Technologies dans ce support de cours)


### Les travaux étudiants  

Chaque travail étudiant correspond à un fichier .md du dossier _travauxetudiants/ 
La cartouche d'un travail étudiant doit à minima contenir :
    - un layout (travail)
    - un title
    - une date 
    - des etudiants (séparés par une virgule s'il y en a plusieurs)
    - un enseignement (l'enseignement dans lequel ce travail a été réalisé)

On peut y rajouter les cartouches suivantes : 
    - level (un entier entre 0 et 10 qui décrit la difficulté du support de cours)
    - institution 
    - link (qui correpond au lien externe du travail étudiant)
    - ihm (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Interaction Homme-Machine dans ce travail étudiant)
    - user (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Prise en compte de l'utilisateur dans ce travail étudiant)
    - ia (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Intelligence Artificielle dans ce travail étudiant)
    - io (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Internet des Objets dans ce travail étudiant)
    - gl (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Génie Logiciel dans ce travail étudiant)
    - techno (un entier entre 1 et 5 qui représente à quel point on a abordé la compétence Technologies dans ce travail étudiant)








