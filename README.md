# Fdf
<!DOCTYPE html>
<html>
<body>
<h1>Projet "Fdf" réalisé à l'école 42</h1>
<p>Il s'agit d'un projet graphique, dont le but est d'afficher une carte en relief entrée par l'utilisateur. La carte correspond à un fichier texte, avec des points disposés de la sorte :</p>
<ul>
	<li>Leur numéro de colonne correspond à leur position sur l'axe x</li>
	<li>Leur numéro de ligne correspond à leur position sur l'axe y</li>
	<li>Leur valeur correspond à leur position sur l'axe z (Altitude)</li>
</ul>
<p>Ainsi, le programme lit ces données et ouvre la carte dans une fenêtre graphique à l'aide de la minilibx.</p>
<h2>Voici la carte de la martinique :</h2>
<img src="images/Martinique.png">
<h2>Voici la carte de la réunion :</h2>
<img src="images/reunion.png">
<h2>Voici la carte du monde :</h2>
<img src="images/monde.png">
<h1>Contenu du dossier</h1>
<p>Le dossier contient un Makefile ainsi que tous les fichiers nécessaires à la compilation du programme. Il contient aussi un dossier maps dans leque se situent des cartes que vous pourrez ouvrir.</p>
<h1>Utilisation</h1>
<p>Après avoir téléchargé le dossier, rendez-vous à la racine de celui ci. Lancez la commande **make** dans votre terminal. Le programme se compile, il a pour nom "fdf".</p>
<p>Exécutez-le avec en paramètre le fichier que vous souhaitez, par exemple comme ceci :</p>
<p>**./fdf maps/martinique.fdf**</p>
<h1>Commandes d'utilisation :</h1>
<p>Appuyez sur la flèche du haut ou la flèche du bas pour faire varier la hauteur de l'élément. Les flèches de droite et de gauche permettent de le faire tourner sur lui-même.</p>
<p>Les touches **i** et **o** permettent de respectivement zoomer et dézoomer.</p>
<p>Enfin, les commandes **z**, **q**, **s** et **d** permettent de se déplacer dans la carte.</p>
</body>
</html>