L'idée c'est d'écrire un rapport de projet à plusieurs, chaque personne pourra écrire ses parties pour ensuite les mettres en commun avec les autres personnes.

Pour ce projet nous avons decidé de travailler sur :
une branche main qui va servir de rendu final
une branche develop où les features seront ajouté 
deux branches features ou Ismaël et Alpha vont developper les fonctionnalités


pour créer les branches nous utilisons les commandes :

    - dans main :
        git checkout -d develop
    - dans develop :
        git branch featureIsma
        git branch featureAlpha

du coté d'Alpha il va devoir initialiser le projet ainsi que le recuperer:

        git remote add origin https://github.com/ismaelwa93/esgi-git-ismael-aw.git
        git clone https://github.com/ismaelwa93/esgi-git-ismael-aw.git

Ismael et Alpha se place chacun dans leur branche feature pour commencer a travailler :

        git checkout feature(Alpha ou Isma)

chaque personne travail dans sa propre branche, on se deplace en utilisant la commande :
	git checkout <nom-de-la-branche>
ensuite une fois qu'une personne fini une partie, par exemple l'intro qui a été fait par Ismël, elle le met dans sa branche ensuite la fusionne avec la branche Develop pour cela :
	
	git add .
	git commit -m "nom du commit"
	git push


