L’exécution de cet algorithme nécessite l’import de 12 images. Celles-ci sont fournies en annexe et nous vous invitons à compléter les deux premières lignes du programme de la manière suivante :

icone = "emplacement de chess.png"

Imagepieces = "emplacement de Images/png"

Veuillez également corriger chaque slash, backslash, double slash selon ce qui est lisible par votre interpréteur et selon la syntaxe de votre système d'exploitation. 
Exemple sur Windows:

icone = "C:/Users/NomUtilisateur/Documents/chess.png"

Imagepieces = "C:/Users/NomUtilisateur/Documents/Images/"

Notez que le second chemin doit finir par un slash (ou anti-slash selon).

A chaque sélection d’une pièce jouable, le programme affiche par coloration les déplacements possibles. Les situations d’échecs « simples » ne sont pas signalées mais sont donc repérables en testant les pièces.
Les situations de Pat, de jeu nul et de Mat sont signalées par un texte mettant fin à la partie.
Il est possible d’abandonner la partie grâce au clic droit. Le bouton vert valide l’abandon, le bouton rouge permet d’annuler.
Un compteur situé en contre-bas droit du plateau référence le nombre de coups effectués depuis la dernière capture ou la dernière poussée de pion. Elle permet au joueur intéressé de recourir à la règle des 50 coups et de demander ainsi la partie nulle. 
Les pièces capturées sont régulièrement affichées à droite.
Au moment de la promotion d’un pion, les choix s’affichent automatiquement.
