# Besoin Utilisateur – Menu Maker

Ce document regroupe toutes les **User Stories** fournies par le client et collectées dans Notion pour le projet **Menu Maker**.  
Chaque User Story est détaillée avec son **ID**, **Epic**, **Description**, **Critères de succès**, **Spécifications fonctionnelles et techniques**, ainsi que l’**assignation et le sprint**.

---

### 1) Landing non Connectée : 
* ID : US01
* Priorité : P1
* Epic : Landing
* User story
En tant qu'internaute ne connaissant pas forcément Menu Maker, je veux pouvoir comprendre l'utilité de cette application.
* Succès
L'internaute doit pouvoir avoir accès aux différentes sections de la landing page non connectée :
- [ ]  Bannière
- [ ]  Personnalisez votre menu
- [ ]  Explications étape par étape

### 2) Page login
* ID : US02
* Priorité : P1
* Epic : Connexion
* User stories
- En tant que restaurateur ayant un compte, je veux pouvoir me connecter.
- En tant qu'internaute, je veux pouvoir créer un compte automatiquement avec mon adresse mail.
* Succès
- [ ]  Cette fenêtre s'ouvre sous forme de modale
- [ ]  L'utilisateur peut entrer son adresse mail
- [ ]  Qu'il se soit déjà connecté ou non, un mail lui est envoyé pour lui permettre de s'authentifier, ou au contraire de confirmer son mail pour accéder pour la première fois à l'application
- [ ]  Un lien "Besoin d'aide” permet d'envoyer directement un e-mail à nos équipes

### 3) Catégorie de plat
* ID : US03
* Priorité : P1
* Epic : Création de menu
* User story
En tant que restaurateur inscrit, je veux renseigner une catégorie de plat (par exemple, "Entrées”, "Plats”, etc.).
* Succès
L'utilisateur doit pouvoir :
- Créer une nouvelle catégorie
- La création de catégorie s'ouvre dans une modale spécifique, et doit pouvoir être validée
- Sélectionner une catégorie créée précédemment

### 4) Création de plat
* ID : US04
* Priorité : P1
* Epic : Création de menu
* User story
En tant que restaurateur, je veux pouvoir ajouter un plat / des plats dans mon menu.
* Succès
Le restaurateur doit pouvoir :
- [ ]  Sélectionner une catégorie
- [ ]  Modifier la catégorie sélectionnée
- [ ]  Entrer les informations de son plat
- [ ]  Une modale s'ouvre pour saisir les différents plats de la catégorie
- [ ]  Chaque plat peut avoir :
    - [ ]  Une photo associée
    - [ ]  Un nom
    - [ ]  Un prix
    - [ ]  Une description
- [ ]  Il est possible de créer autant de plats que l'on souhaite

### 5) Style de menu
* ID : US05
* Priorité : P1
* Epic : Création de menu
* User story
En tant que restaurateur connecté, je veux pouvoir personnaliser le style de mon menu.
* Succès
Le restaurateur doit pouvoir :
- [ ]  Visualiser le menu actuellement créé
- [ ]  Sélectionner une typographie
- [ ]  Choisir une couleur de texte

### 6) Exportation PDF
* ID : US06
* Priorité : P1
* Epic : Création de menu
* User story
En tant que restaurateur, je veux exporter mon menu en PDF.
* Succès
- [ ]  Le restaurateur doit pouvoir en un clic télécharger le fichier PDF correspondant à son menu

### 7) Commander l’impression d’un menu
* ID : US07
* Priorité : P1
* Epic : Back Office
* User story
En tant que restaurateur, je dois pouvoir commander en un clic l'impression d'un menu
* Succès
- [ ]  L'encart "Imprimer un menu” doit être visible depuis la page d'accueil
- [ ]  Il s'agit d'un lien qui s'ouvre dans un nouvel onglet
- [ ]  Le lien doit être fait vers le back-office de Qwenta

### 8) Menus précédents
* ID : US08
* Priorité : P1
* Epic : -
* User story
En tant que restaurateur, je dois pouvoir avoir accès à une vue regroupant les menus créés précédemment.
* Succès
- [ ]  Au clic sur "Mes menus”, le restaurateur doit avoir accès aux menus créés précédemment
- [ ]  La date de création s'affiche
- [ ]  Il est possible de modifier un menu précédent
- [ ]  Il est possible de supprimer un menu précédent
- [ ]  Sur la même vue, le restaurateur doit pouvoir créer un nouveau menu

### 9) Informations légales
* ID : US09
* Priorité : P2
* Epic : Landing
* User story
En tant qu'internaute, je dois pouvoir accéder au contenu "Mentions légales" dans une modale, et l'information “Tous droits réservés” doit être affichée.
* Précisions
Les éléments texte contenus dans la modale sont statiques et ne sont pas amenés à bouger pour le moment ; elle peut donc être statique.
* Succès
- [ ]  L'internaute doit pouvoir cliquer sur "Mentions légales” depuis les pages connectées et déconnectées
- [ ]  La modale s'ouvre alors
- [ ]  La mention "Tous droits réservés” doit figurer sur la page d'accueil et sur toutes les autres pages

### 10) Tarifs
* ID : US10
* Priorité : P2
* Epic : Landing
* User story
En tant qu'internaute, je dois pouvoir avoir accès aux tarifs de MenuMaker. 
* Précisions
La page va être créée côté Qwenta. Je n'ai pas encore l'URL, mais elle suivra la logique. `https://URL_DE_QWENTA/tarifs/menumaker`
* Succès
L'internaute doit pouvoir cliquer sur l'onglet Tarifs, et ouvrir un nouvel onglet

### 11) Exportation Deliveroo
* ID : US11
* Priorité : P2
* Epic : Création de menu
* User story
En tant que restaurateur, je veux pouvoir exporter mon menu en un clic vers l'application Deliveroo.
* Remarques
⇒ Quelle connexion avec Deliveroo ?
* Succès
- [ ]  L'encart "Diffuser sur Deliveroo” doit s'afficher dans la catégorie "Exportez et diffusez”
- [ ]  Au clic sur l'encart, l'utilisateur doit être redirigé sur l'application Deliveroo

### 12) Partage sur Instagram
* ID : US12
* Priorité : P2
* Epic : Création de menu
* User story
En tant que restaurateur, je veux pouvoir partager mon menu sur Instagram facilement.
* Remarques
⇒ Quelle connexion avec Instagram ?
* Succès
- [ ]  L'encart "Partager sur Instagram” doit s'afficher dans la catégorie "Exportez et diffusez”
- [ ]  Au clic sur l'encart, des images du menu au format carré (pour les mettre sur Instagram) sont générées
- [ ]  Le restaurateur est redirigé vers son compte Instagram avec les photos carrées des menus

### 13) Déconnexion
* ID : US13
* Priorité : P2
* Epic : Connexion
* User story
En tant que restaurateur, je dois pouvoir me déconnecter.
* Succès
- [ ]  Le restaurateur doit pouvoir se déconnecter depuis n'importe quelle page connectée

### 14) Infos utilisateur
* ID : US14
* Priorité : P2
* Epic : -
* User story
En tant que restaurateur, je veux pouvoir modifier mes informations utilisateur.
* Succès
Le restaurateur doit pouvoir :
- [ ]  Lier plusieurs adresses e-mail à son compte
- [ ]  Modifier son adresse e-mail de base

### 15) Dashboard
* ID : US15
* Priorité : P2
* Epic : - 
* User story
En tant que restaurateur, je veux pouvoir avoir accès à un dashboard qui regroupe :
- La création de menu
- La diffusion de menu
- L'impression de menu
- Les 3 derniers articles du blog de Qwenta qui parlent de MenuMaker
* Succès
L'internaute doit pouvoir avoir accès :
- [ ]  À l'encart "Créer un menu”
- [ ]  À l'encart "Diffuser un menu”
- [ ]  À l'encart "Imprimer un menu”
- [ ]  À la section “Pour aller plus loin”
- [ ]  Aux 3 derniers articles de blog qui parlent de MenuMaker
- Titre
- Photo de couverture
- Lien

### 16) Branding restaurateur
* ID : US16
* Priorité : P3
* Epic : - 
* User story
En tant que restaurateur, je veux pouvoir créer le branding de mon restaurant.
* Succès
Le restaurateur doit pouvoir ajouter / modifier / supprimer les éléments suivants :
- Logo
- Couleurs de base
**
