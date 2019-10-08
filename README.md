# CloneBdCodeSignal
Reproduction de la base de données de la plateforme codeSignal

CAHIER DES CHARGES


REPRODUCTION DU FONCTIONNEMENT INTERNE DE LA PLATEFORME CODESIGNAL

I- INSCRIPTION 

	Email:
	FulName
	Password:

II- CONNEXION

	email/username:
	password:

II-DASBOARD
	a- Panneau challenge
	b- Historique d'activité
	c- Challenge entreprise
	d- Challenge entre équipe
	e- Interview pour vsiteur
	f- Lien direct vers le niveau arcade actuel
  
  
  
  -----------------------------------------------------ARCADE--------------------------------------------------------------

A-Arcade
	A-1) Liste des rubriques(Nom de la rubrique, informations sur le nombre de texte résolu et nombre d'exercice totale)
	 

B-Contenu rubrique:
	B-1) Section des exercices

C-Section exercice:
	-Liste des series d'exercice 

D-Section d'exerce:
	-Titre de l'exercice
	-Description(énoncé et résultat attendu)
	-La difficulté de l'exercie
	-Le nombre de points
	-Etat de validité
	

III- LE MENU DRAFTS
	- Affiche la liste des solutions de l'exercice en fonction du langage de programmation(Date, le langage,le score)
	- Enregistrement du code

IV-LES SOLUTIONS

	-Le nombres de toutes les solutions, les users, les langages, le vote

V- LES COMMENTAIRES
	-Forum de discussion lié à l'exercie en cours(User,date,message,reponse)
	-Report Commentaire
  
----------------------------------------------------DAILY CHALLENGE------------------------------------------------------

.-----.Status(public,private...)
.-----.All statuts(Visible...)
.-----.Niveau de difficulté(facile,difficile...)
.-----.Categorie(front-end, Database...)
.-----.Nombre de challenge resolus
.-----.Total challenge affiché
->Challenge(status,titre,categorieDate,user,nombre d'inscrire, nombre_commentaire, recompense)

NB: L'interface du challenge est identique à l'interface de l'arcade, à la difference qu'il y a un temps de résolution qui decompte.

-------------------------------------------------COMPAGNY CHALLENGE---------------------------------------------------------
ENTREPRISE:
  . Nom
  . Situation géographique
  . Date de création entreprise
  . Nombre d'employés
  . Domaine d'activité(d'intervention)
  . Medias(image,video,url)
  . Description entreprise(about,langage)
  Exercice : (titre,nombre souscripteur,recompense,le chrono, difficulté


-----------------------------------------------------INTERVIEW PRATICE------------------------------------------------------------

-Affichage des categories des plans d'étude(Crash course, fundamentals,extra credits,freestyle)
-Contenus detaillé des categories des etudes
-Contenue de l'exercice(titre,nombre challenge)
-Contenu du test(titre,entreprise,difficulté;chrono,nombre inscrit,nombre commentaire,recompense)



------------------------------------------------------------TOURNOIR----------------------------------------------------------------

.Trois Onglets dont:
  -Regular
  -Marathou
  -Private
  
  .Un bouton create
  .Plusieurs épreuves dont:
    -Nombre de participants
    -Exactements cinqs exercices
    -La duréé de l'exercice(maximun 5 min)
    -La récompense
    -Commentaires
  
  .Un Etat
    -Running
    -Finished

--------------------------------------------------------------MY PROFILE-----------------------------------------------------
On distaingue:
  4 Onglets:
    -Overview
    -CodeFriends
    -Mytasks
    -Badges
    
    1-OVERVIEW
      User info
      Fullname
      Username
      Image
      email
      level
      Experience(ou tu as travaillé)
      Eductaion(ou tu as étudié)
      
    2-CODE FRIEND
    3-MY TASKS
    4-BADGES
      .Description
      .Pourcentage
      .Logo
      .Plusieurs type de badge
      
-----------------------------------------------FORUM-------------------------------------------------------
-Les categories(10 exactements)
-Poste
  .Reactions
  .commentaires
  .category
  .nom(posté par qui)
  .photo
  .titre
  .date
-+new poste

    
