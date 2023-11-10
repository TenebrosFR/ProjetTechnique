# ProjetTechnique
Contrôles : 
 - Avec E on peut passer en mode construction.
 - Avec ZQSD on se déplace. Espace pour sauter.
 - Avec I on peut ouvrir l'inventaire pour choisir l'objet à construire.
 - Avec le clic droit on peut pivoter un objet en mode construction.
 - Avec le clic gauche on peut poser l'objet en mode construction.

 Feature :
 - Inventaire dynamique qui se génère avec les éléments de la structure (mesh et image car je n'ai pas réussi a prendre la thumbnail comme image de texture). (Pas eu le temps de trouver comment rendre les images de même taille en prenant la taille de la cellule)
 - Snap de l'objet en cour sur le coté droit et gauche. Permettant de mieux pouvoir l'aligner. (Axe d'amélioration : le rendre possible sur chaque coté et le centre.) 
 Le snap est dynamique en prennant les bounds et les normales de collision pour calculer la position. Du moment que le pivot du mesh est bien placer l'ajout d'un objet de construction ne prend pas plus qu'un cliquer glisser.
 - Rotation.

 Pas réussi à réaliser le fait d'empecher la construction en cas de clip, ce n'était soit pas précis soit trop précis et je ne pouvais pas snap et rotate juste un peu car cela collidais.
