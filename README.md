# Dossier UX

## Membres du groupe
Milhet Elsa & 
Mellé Florestan

## Description générale de l'application
Ce projet a pour but de mettre en œuvre les enseignements des modules “Design d’expérience”, “Développement Front et intégration”, “Développement Back”, “Gestion de projet”, et “Déploiement de services. 

Notre sujet est la réalisation d’une application web & mobile permettant l’adoption d’un animal.
L’objectif est d’avoir une plateforme qui centralise des animaux à la recherche d’un nouveau foyer. Les utilisateurs de l’application pourront donc consulter les animaux qui sont mis à l’adoption et ajouter son animal afin de lui trouver un nouveau foyer.


## Fonctionnalités / Ecrans

Menu de navigation
- Accès aux principales pages de l’application 

Inscription
- Formulaire permettant aux utilisateurs de s’inscrire 
- Imposer un mot de passe sécurisé 
- Crypter les mots de passes

Connexion
- Formulaire de connexion grâce à l’adresse email et le mot de passe 
- Possibilité de se souvenir de l’utilisateur 

Animaux
- Liste de tous les animaux à adopter dans l’application 
- Filtrer par critères (type, race, localisation, âge, taille, sexe, nb de likes, … ) 
- Recherche par critères

Animal
- Page qui affiche toutes les informations relatives à un animal (prenom, race, images, age, sexe, … )
- Informations du maître
- Possibilité de like
- Possibilité de signaler
- Message / Téléphone 

Espace utilisateur
- Consulter ses informations personnelles
- Liste des animaux mis à l’adoption
- Possibilité d’ajouter un animal

Like
- Liste de tous les animaux likés 

Ajout Animal
- Accessible depuis l’espace utilisateur, cette page permet d’ajouter son animal

Gestion Animal
- Possibilité de mettre à jour et supprimer un animal

Administration
- Ajouter/supprimer des utilisateurs 
- Mise à jour de tous les éléments administrables 
- Suppression des animaux/utilisateurs après signalement


### Navigation

Nous avons opté pour un menu burger pour optimiser l'espace visuel de la page d'accueil. Étant donné que la page d'accueil est destinée à mettre en avant les animaux disponibles pour l'adoption, réduire la visibilité du menu principal permet de mettre l'accent sur le contenu principal.
Le menu burger offre également une apparence épurée et moderne à la page d'accueil.

En cliquant sur le menu burger, les utilisateurs peuvent accéder à un menu déroulant qui permet de naviguer sur les différentes pages de l'application, telles que :
Mes Favoris : Page renvoyant une liste des animaux gardés en favoris.
Mon Profil : Page complète qui permet de visualiser ses informations personnelles, ses animaux, ainsi que d'ajouter et/ou modifier ceux-ci.

### Accueil

Notre header est constitué d'un menu burger qui permet la navigation vers les différentes pages ainsi que du profil de l'utilisateur.

Au-dessous du header, nous avons intégré une section de recherche qui permet aux utilisateurs de trouver rapidement un animal spécifique en entrant des mots-clés et un bouton afin de filtrer sa recherche. Ces fonctionnalités sont essentielles pour les utilisateurs qui ont déjà une idée précise de l'animal qu'ils souhaitent adopter.

Juste en dessous de la section de recherche, nous avons inclus des filtres de recherche avancée. Ces filtres permettent aux utilisateurs de restreindre leurs résultats en fonction de critères spécifiques tels que l'âge, le sexe, la taille, etc. Nous avons choisi d'inclure cette fonctionnalité pour permettre aux utilisateurs d'affiner leur recherche et de trouver plus facilement l'animal qui correspond à leurs préférences et à leurs besoins.

Nous avons mis en avant un menu, listant les animaux disponibles à l'adoption. Par défaut, la page affiche tous les animaux disponibles, ce qui permet aux utilisateurs d'avoir une vue d'ensemble de toutes les options disponibles dès leur arrivée sur le site.

Chaque animal est présenté par une card, avec une photo, son nom, son âge, son sexe, sa race ainsi que le lieu où il réside. Cette présentation permet aux utilisateurs d'avoir un aperçu rapide des animaux disponibles et de décider lesquels ils souhaitent explorer davantage. Aussi, si ceux-ci ont marqué leur esprit, il y a la possibilité de mettre un like sur l'animal.

### Ecran 1 / Page 1
![Démarrage Elsa](https://github.com/mmicastres/sae401-milhet_elsa_melle_florestan/assets/144545254/639db913-2539-4c84-9e08-3ce208747200)
<br>

Première page : on retrouve une icone de présentation, un petit slogan en rapport avec l'application, un bouton inscription et un bouton pour accéder a l'application sans se connecter.

### Ecran 2 / Page 2

![Connexion Elsa](https://github.com/mmicastres/sae401-milhet_elsa_melle_florestan/assets/144545254/46af839e-b1e2-4faf-82f4-4544b469c267)
<br>
Page de connexion comprenant deux input (mail et mot de passe) afin de se connecter. En plus, il y a un bouton "valider" la connexion ainsi que la possibilité de s'inscrire si l'utilisateur n'a pas de compte.


### Ecran 3 / Page 3

![Inscription Elsa](https://github.com/mmicastres/sae401-milhet_elsa_melle_florestan/assets/144545254/0b5321ef-f917-46c9-8994-db6a3dd1c995)
<br>
Page d'inscription comprenant les différents input pour s'inscrire et deux boutons "suivant" et "annuler".

### Ecran 4 / Page 3

![Inscription2](https://github.com/mmicastres/sae401-milhet_elsa_melle_florestan/assets/150163972/e9867f51-8bfd-4968-be71-5e8e296f311e)
<br>
Suite page inscription comprenant les inputs pour la ville et l'âge, un bouton pour rajouter une photo de profil et enfin deux boutons pour préciser son sexe

### Ecran 5 / Page 4
![accueilsansco](https://github.com/mmicastres/sae401-milhet_elsa_melle_florestan/assets/150163972/2c62d60b-e7ca-44ff-9b52-640d9552267d)
<br>
Page d'accueil comprenant différentes cards dans lesquels sont affichés les animaux pour un utilisateur non connecté on retrouve un profil pour se connecter ( en haut à gauche ) et un bouton filtre pour ajouter des paramètres de recherche, un slider permettant de choisir le type d'animal recherché, une barre de recherche pour chercher un paramètre spécifique et enfin des boutons like sur chaque card pour ajouter l'animal aux favoris

### Ecran 6 / Page 4
![Accueil Elsa](https://github.com/mmicastres/sae401-milhet_elsa_melle_florestan/assets/144545254/7fe67da7-57a7-4f2e-a63c-2706f81b9c28)
<br>
Page d'accueil comprenant différentes cards dans lesquels sont affichés les animaux pour un utilisateur connecté on retrouve un profil accéder a son espace personnel ( en haut à gauche ), un bouton filtre pour ajouter des paramètres de recherche, un slider permettant de choisir le l'espèce recherchée, une barre de recherche pour chercher un paramètre spécifique et enfin des boutons like sur chaque card pour ajouter l'animal aux favoris

### Ecran 7 / Page 4
![Accueil chien Elsa](https://github.com/mmicastres/sae401-milhet_elsa_melle_florestan/assets/144545254/c9adf60b-263b-4e65-b081-6cf949b0e826)
<br>
Page d'accueil avec les chiens séléctionnés comme espèce. Toutes les pages des espèces sont faites de la même manière ayant juste la couleur qui change.

### Ecran 8 / Page 5
![Animal Elsa](https://github.com/mmicastres/sae401-milhet_elsa_melle_florestan/assets/144545254/97f796e0-8c98-4b98-bf0a-1400695c8d13)
<br>
Page Animal comprenant les différentes informations sur l'animal concerné : Photos, Prénom, Localisation, Sexe, Age, Poids, Taille, Description et enfin Spécificités. On retrouve également le nom et prénom du propriétaire ainsi que sa photo de profil et dans la section haute de la page on peut trouver un autre bouton like ( icone de coeur ) pour ajouter l'animal a ses favoris et un bouton pour signaler l'animal en cas de problème ( icone de cloche ).

### Ecran 9 / Page 6
![Espace utilisateur](https://github.com/mmicastres/sae401-milhet_elsa_melle_florestan/assets/150163972/97341173-8a1e-4d8d-a8be-180ae3747dd5)
<br>
Page Espace Utilisateur avec la possibiité de modifier chaque informations de l'utilisateurs sauf son mot de passe.

### Ecran 10 / Page 7
![Modifier Profil Elsa](https://github.com/mmicastres/sae401-milhet_elsa_melle_florestan/assets/144545254/6b1f6707-5597-4ae3-8007-c2923721fae2)
<br>
Page Modification Profil sur laquelle on retrouve son image profil ainsi qu'un bouton pour la changer, ses informations personnelles, ses animaux avec leurs likes et un bouton pour modifier le profil d'un animal ainsi qu'un bouton pour ajouter un animal. Dans le Header on retrouve simplement un bouton pour revenir à l'accueil.

### Ecran 11 / Page 7
![Modifier2 Profil Elsa](https://github.com/mmicastres/sae401-milhet_elsa_melle_florestan/assets/144545254/447eea5a-a34a-4a76-a6bc-d46f8872eb75)
<br>
Suite de la Page Modification Utilisateur.

### Ecran 12 / Page 8
![Ajouter Animal Elsa](https://github.com/mmicastres/sae401-milhet_elsa_melle_florestan/assets/144545254/1e9a92b8-9e5a-474c-b36e-c661b1e36612)
<br>
Page Ajouter un Animal avec les informations basiques.

### Ecran 13 / Page 8
![Ajouter2 Animal Elsa](https://github.com/mmicastres/sae401-milhet_elsa_melle_florestan/assets/144545254/02c5855f-4120-4ab8-a947-5d9be80f36cd)
<br>
Suite de la Page Ajouter un Animal: le poids est par défault en kg et l'âge en années, c'est selon nous le plus utilisé et le plus probable.

### Ecran 14 / Page 9
![Modifier Animal Elsa](https://github.com/mmicastres/sae401-milhet_elsa_melle_florestan/assets/144545254/0697670c-433d-4739-9a94-7e5db6aade23)
<br>
Page Modifier un Animal: avec la reprise dess informations de l'animal.

### Ecran 15 / Page 9
![Modifier2 Animal Elsa](https://github.com/mmicastres/sae401-milhet_elsa_melle_florestan/assets/144545254/adc636d7-5bcc-4ebd-aa22-576df24037f2)
<br>
Suite de la Page Modifier un Animal.

### Ecran 16 / Page 10
![Like Elsa](https://github.com/mmicastres/sae401-milhet_elsa_melle_florestan/assets/144545254/dd42e29e-23f5-4820-b8ee-de594aad6107)
<br>
Page Favoris : c'est la même schéma que l'accueil avec uniquement les animaux mis en favoris par l'utilisateur.

## Maquettes finales
Quels design system ont été utilisés. Lequel a été sélectionné pour l'integration.

### Maquette Mobile Elsa
https://www.figma.com/file/DskeYvLuwb0MeeW0h3MXxW/SAE-401?type=design&node-id=0%3A1&mode=design&t=GaUnqXG7wlMfBKax-1

### Maquette Desktop Elsa
https://www.figma.com/file/8sdNFLWOD7gDr2NZAxJF6i/SA%C3%89-DESKTOP?type=design&node-id=0%3A1&mode=design&t=MEIon05gE5BecWAk-1
