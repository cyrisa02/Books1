# Books1
Appli avec Redux et React
Formulaire bootstrap redux https://www.youtube.com/watch?v=IVjj7v5E1N4&t=408s

Tuto validation du formulaire https://www.youtube.com/results?search_query=donkey+geek+redux

ds addbooks (=formulaire) enregistrer les infos-> besoin d'un état local -> hook useState pour générer variable d'état déstrucuter la variable et modifier la varable par le setter on a besoin d'une valeur initiale qui sera un objet (const -> title et author)

puis dans le input du form il faut changer l'évenement avec onchange qui attend une value (title pour le titre et author pour auteur)->NewData.title la modif (=le setter) se fait sur le onchange, avec e (event objet) et on a besoin de la target, target qui attend la value

+valdiation du form avec onSubmit dans balise form avec une méthode handleSubmit (fonction que l'on crée)

dispatch vers redux
