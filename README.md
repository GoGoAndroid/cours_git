# Découverte de git

## A quoi sert git ?
	C'est un système de gestion de version décentralisé.
	
	Il permet le développement en groupe,
	de disposer de l'historique complet des changements d'un code source,
	de gérer des développements concurents sur un même projet (release, dev, alpha, beta, ...) .
	

## Installation de git

	Windows : http://msysgit.github.io
	Mac : http://sourceforge.net/projects/git-osx-installer/
	Linux : 
		yum install git
		apt-get install git
		
	
## Initialisation d'un dépot

	Création d'un dépot vide : git init
	Création d'un dépot à partir d'un dépot : glit clone [url]
	
### L'url
	Ici : url = https://github.com/GoGoAndroid/cours_git.git
	Git dispose de différents protocoles de transfert que vous pouvez utiliser. 
	Notre exemple  utilise le protocole 
		https:// , mais pouvez aussi voir
		git://  ou,
		utilisateur@serveur:/chemin.git , qui utilise le protocole de transfert SSH.
		

### Procéder à la découverte

	1 Récupérer, lire et comprendre la branche d'explication des branches avec git checkout les_branches
	2 Récupérer, lire et comprendre la branche d'explication des soumissions : "modifier"
	3 Récupérer, lire et comprendre la branche d'explication de la configuration  : "la_configutation_de_git"
	==
		I Une fois ces explications bien comprises, ajouter son nom dans le fichier bien_compris.txt de chacune des branches
			master
			Init
			checkout les_branches
			la_configutation_de_git
		II Faire évoluer la faq dans le master : faq.txt
		III Récupérer lire et comprendre chacun des README.md de chacune des branches du dépot
		Ajouter son nom dans chacune des branches pour indiquer que les instructions ont été réalisées
		
	
	
	
	
