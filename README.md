# Les templates HTML

## Qu'est ce qu'un template HTML?
	
	Un template ou modèle permet de séparer les données du code HTML
	Ainsi, plusieurs jeux de données produiront autant de pages HTML avec un même modèle.

## rainTPL
	raintpl est un système de template simple en php, disponible sous git-hub

# Instructions

	1. Créez un clone de raintpl sur votre machine
	2. Créez un fichier php nommé cv_data.php contenant la structure suivante 

		$personne = array( 
			"prenom" => "[mon nom]", 
			"nom" => "[mon prénom]", 
			"telephone" => "[mon tel]"
			"formations"=>array(
				1=>array(
					"entree"=>"01/01/01",
					"sortie"=>"01/01/01", 
					etablissement=>"etablissement",
					formation=>"intitulé de la formation"),

				2=>array(
					"entree"=>"01/01/01",
					"sortie"=>"01/01/01", 
					etablissement=>"etablissement",
					formation=>"intitulé de la formation"),
				...
				),
			),
			"expériences professionelles"=>array(
				1=>array(
					"entree"=>"01/01/01",
					"sortie"=>"01/01/01", 
					etablissement=>"etablissement",
					formation=>"description de la mission"),

				2=>array(
					"entree"=>"01/01/01",
					"sortie"=>"01/01/01", 
					etablissement=>"etablissement",
					mission=>"description de la mission"),
				...
				)
			),
		);
		3. Soumettez votre fichier
		4. Créez un tepmplate raintpl HTML pour réaliser votre CV nommé [nom_nom].cv
		5. Créer un ficher build.php qui génère votre CV
		


		




	
		
	
	
	
	
