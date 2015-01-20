# Découverte de git

## Modifier un fichier

	Un fichier modifié est pris en compte locallement par git, lorsqu'il est soumis.
	La commande de soumission est 
		git commit -m"résumé des mofofications" [les fichiers]
	
## Ajouter un fichier

	Lorsqu'un fichier est créé, pour que git le connaisse, il faut utiliser la commande add
	1. git add [les fichiers]. Une fois qu'il a été ajouté il faut ensuite le soumettre,
	2. git commit -m"message" [les fichiers]
	
## Partager les modifications

	Une fois les modifications soumises, pour les partager avec un autre dépot, c'est la commande push que l'on utilise :
	git push origin/[nom de la branche]
	
## En cas de conflit
	
	Si votre branche à été modifiée sur le dépot distant, votre dépot ne peut pas être partagé. 
	Il faut en préalable mettre votre dépot a jour avec la commande pull
		git pull
	Et résoudre les conflits éventuels, c'est à dire corriger les fichiers qui n'ont pas pu être mergés.
	
### Corriger les conflits
	Les fichiers non mergés sont fusionnés de cette façon 
	<<<<<<< HEAD:[file]
	ce qui est dans la branche originale
	=======
	ce qui vient de l'autre branche
	>>>>>>> prob53:[file]
	
	Corriger les conflits c'est supprimer intelligemment les lignes qui n'ont rien à faire dans la version fusionnée.

#Instructions

1. Dans votre branche créée à l'étape "branches", ajoutez un fichier nommé 
		modifier-[votre nom]
2. Soumettez et publiez

3. Positionnez vous sur la branche merge, lisez les explications, et suivez les instructions

	
	
