---
equipemoa: sportandu
nomcode: sportu
groupetd: 1
guide: http://casisbelli.insa-rouen.fr/wiki/pmwiki.php?n=FilRouge.RedigerCdc
---

# Cahier des Charges - Sports&U

## FONDEMENT DU PROJET

### 1. But du projet
  L’équipe à l’origine de ce projet est parti d’un constat de base simple : aujourd’hui, avec l’importance des réseaux sociaux dans notre manière d'interagir avec la société, il n’existe pas à l’heure actuelle un moyen convaincant de mettre en relation les acteurs du monde sportif. La démocratisation des smartphones et de l’accès à Internet permet ainsi une interconnexion permanente entre les utilisateurs, et donc des sportifs, qu’ils soient débutants, confirmés ou professionnels. Ce produit est ainsi conçu pour aider les gens qui n'osent pas faire du sport via des moyens basiques, ou, qui ne savent pas comment s'y prendre pour faire du sport et des rencontres.
    A terme, l’objectif serait de développer des partenariats avec des marques liées au monde sportif pourront être établis pour proposer des concours, des produits ou des publicités ciblées.
    
### 2. Organismes impliqués dans le projet
  L'entreprise Sport&U est composée de 4 associés diplômés de l'INSA de Rouen, prestigieuse école d'ingénieurs de Normandie. 
  
### 3. Utilisateurs du produit

#### a. Utilisateurs directs du produit
  Les utilisateurs seront des sportifs, amateurs ou confirmés, qui souhaiteraient être accompagnés dans leur carrière sportive et faire des rencontres pour pratiquer.

#### b. Utilisateurs maintenance du produit
  Les responsables des nouvelles sportives qui déposent des nouvelles courantes, les administrateurs de forum, les employés qui renouvellent des informations plus récentes sur paris des matchs. Clairement, mise en opération d’une application nous demande une coopération multilatérale.
  
## CONTRAINTES SUR LE PROJET


### 4. Contraintes non négociables

#### a. Contraintes sur la conception de la solution

* Le produit doit pouvoir être implanté et utilisé sur IOS et Android : le produit étant multiplateforme, les versions Android et IOS doivent être strictement identiques.
* Le programme source doit être maintenable et réutilisable par l’entreprise Sports&U.
* Les bases de données utilisateurs seront strictement cryptées, et ne seront accessible que par l'entreprise Sport&U ainsi que les autorités compétentes
* La solution sera accompagnée d'une documentation technique et d'une notice d'utilisation détaillée.

#### b. Environnement de fonctionnement du système actuel

* Le produit devra pouvoir être installé sur des ordinateurs, sur des Smartphones ou encore des tablettes. 
* Le produit requiert une connexion internet sauf pour le module "espace personnel".
* Chaque section du produit dans un espace, comme, "mon compte" ou "sport à plusieurs" devra être représentée par un bloc ajustable pour faciliter la lisibilité. Les principaux espaces devront être présent dans un menu vertical sur le côté de l'écran, menu "refermable".

#### c. Applications partenaires 
L'application Sport&U devra utiliser les outils des applications suivantes :
* AppStore pour la distribution sur IOS
* PlayStore pour la distribution sur Android
* Google Maps pour les fonctionnalités de géolocalisation
* Decathlon, partenaire de Sport&U, pour proposer des produits aux utilisateurs
* AdSense pour les publicités
* L'Equipe pour diffuser des contenus sur le monde du sport

#### d. "COTS" : Progiciels ou composants commerciaux
L'application utilisera uniquement des outils Open Source, aucun progiciel n'est pour l'instant à prévoir.


#### e. Lieux de fonctionnement prévus
L'application sera accessible par tout utilisateur disposant d'un smartphone, tablette ou autre support adapté dôté d'une connexion Internet.

#### f. De combien de temps les développeurs disposent-ils pour le projet ?
Les développeurs disposeront de 25 semaines pour livrer le produit. Un livrable intermédiaire devra être fourni à la fin de la 15ème semaine.

### 5. Glossaire et conventions de dénomination
SportAndU/Sport&U : Nom du projet

### 6. Faits et hypothèses utiles

#### a. Faits

* Tout les utilisateurs ont accès aux articles et publications publiques sur l'application : aucune restriction ne leur sera imposée (par exemple, un groupe innaccessible aux débutants...).
* Les produits proposés par l'application doivent impérativement être disponibles chez nos partenaires

#### b. Hypothèses

* Le projet se présente comme étant le seul réseau social multisports sur le marché actuellement

### 7. Portée du travail
#### a. La situation actuelle
Actuellement nous avons déjà certaines applications avec une partie des fonctionnements ce que l'on veut avoir dans le monde, mais honnêtment, il n'y a pas une application qui peut avoir des fonctionnements tellement riches comme nous. De plus, en France, même Europe, il manque des applications de même type. Nous pensons qu'il y a un grand marché à exploiter.
  
#### b. Contexte de travail
N/A

#### c. Division du travail en événements métier
N/A

### 8. Portée du produit

#### Description des cas d’utilisations

 * Les acteurs principaux de cette application sont les membres, qui auront la possibilitées de partager des conseils, photos, vidéos, anecdotes… avec les autres membres. Ils auront aussi accès à l’actualité sportive et à des structures de paris sportifs. Ils pourront enfin aider à l’amélioration de l’application en reportant des bugs éventuels.
 * Les administrateurs de l’application seront en charge de l’approvisionnement des actualités sportives et de la modération des ressources partagées par les membres.
  Les développeurs devront s'assurer de bon fonctionnement de l’application tout en améliorant les fonctionnalités proposées.
 * Enfin les paris sportifs seront gérer par des sous-contractants.

### 9.Exigences fonctionnelles
| ID 	| Catégories 	| Description 	| Justification 	| Origine 	| Critères de satisfaction 	| Contentement MOA 	| Mécontentement MOA 	| Exigences Dépendantes 	| Exigences conflictuelles 	|
|----	|------------	|-------------	|---------------	|---------	|--------------------------	|------------------	|--------------------	|-----------------------	|--------------------------	|
|  06 	|       Information    	|        Récolter des données sur la position d'un membre    	|   Permet l'association logique de personnes pour des rencontres sportives     |      Remue-méninges   	| Obtenir les coordonnées d'un membre quand celui-ci l'autorise   	|               	|                   	|                       	|                          	|
|   08 	|     Gestion/Sociale       	|       Permet d'ajouter, de retirer de classer les contacts d'un membre      	|             Extension de l'exigence numéro 02 	|    Remue-méninges     	| Gestion efficace des contacts d'un membre	|                  	|                    	|                       	|                          	|
|   10 	|       Sociale/Sport     	|       Créer un groupe, s'ajouter à un groupe, gérer des groupes     	|    Permet la mise en place de rencontres sportives       	|     Remue-méninges    	| Outil de création et de gestion de groupes	|                  	|                    	|                       	|                          	|
|   19 	|  Marketing        	|      Ajout à l'interface de publicités cohérentes avec le thème du projet       	|           Informer les membres, créer des liens avec des partenaires et gagner de l'argent    	|    Remue-méninges     	| Bannières publicitaires non intrusives et expliciter les offres partenaires avec un logo "Sponso"	|                  	|                    	|                       	|                          	|
|    21	|       Information     	|       Affichage d'articles sportifs      	|        Permet à l'membre de suivre l'actualité du sport en général ou des sports       	|      Remue-méninges   	|Outil de création et de publication d'articles pour suivre l'actualité|                  	|                    	|                       	|                          	|
|    28	|      Pratique et utile      	|        Environnement propre à l'membre, onglet des informations relatives à l'membre (sports suivis, stats, poids, taille etc.)    	|        Permet à l'membre d'avoir une interface propre et ergonomique relatant ses données       	|     Remue-méninges    	| Système de menu(s), interface modulaire                           	|                  	|                    	|                       	|                          	|
|    29	|       Information     	|       Recherche rapide et intuitive      	|         Gain de temps      	|     Remue-méninges    	| Barre de recherche, croisement de filtres                          	| 
|    34	|      Information      	|      Actualité de "tous" les sports       	| La plateforme est multisports : la grande majorité des sports populaires doivent y être valorisés          	|    Remue-méninges     	| Indication visuelle en fonction du sport (logo, pictogramme...)                         	|                  	|                    	|                       	| |                    	|                       	| 
|    38	|     Accessibilité      	|       Possibilité d'accéder à l'application via un site internet ou une application mobile     	|        Accès multiplateformes       	|      Remue-méninges   	| Utilisation et rendu des informations identiques suivant la plateforme. Accessibilité en continu.                           	|                  	|                    	|  

## Exigences non fonctionnelles
### Numéro de l’exigence : 10       	 
* Type d’exigence : Ergonomie et convivialité du produit 
* Description : Le produit doit être facilement utilisable, épuré et attractif. Le membre pourra organiser son espace comme il le désire (emplacement des rubriques).
* Justification : Le membre devra se sentir "chez lui", naviguer de manière personnelle (interface personnalisée) entre les différents espaces pour s'y retrouver le plus facilement possible.
* Critère de satisfaction : Système de menu(s), interface modulaire
* Contentement du maître d’ouvrage: Le membre peut personnaliser son espace en utilisant des blocs pour modéliser les rubriques        	
* Mécontentement du maître d’ouvrage: Le membre de possède pas d'espace personnalisable.

### Numéro de l’exigence : 52     	 
* Type d’exigence : Exigences culturelles et politiques 
* Description : Base de données de citations et diffusion d'une citation en fonction du membre et de ses intérêts, ça peut aider les utilisateurs faire du sport continuellement.
* Justification : Le membre devra se sentir d’avoir reçu les citations proprement, ils peuvent prendre encouragements de la part de l’application.








