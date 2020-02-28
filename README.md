# Talker et subscriber en ROS

L'objectif de ce git est de partager les ressources pour réaliser un talker/subcriber avec ROS. C'est à dire réaliser deux noeuds qui vont communiquer ensemble, le premier qui envoi une information, le soncond qui la reçoit et l'affiche. 


## Créer un Workspace et un package puis y inserer les codes

Si ce n'est pas déjà fait il vous faut déja disposer d'un WorkSpace dans lequel travailler et placer vos codes. 
Si vous n'en avez pas encore créé un voici la méthode:
### Créer son WS

suivre la partie consernant cela dans ce tuto: http://wiki.ros.org/ROS/Tutorials/CreatingPackage

### Tutoriel

vous pouvez maintenant suivre le tutoriel: http://wiki.ros.org/ROS/Tutorials/WritingPublisherSubscriber%28c%2B%2B%29

vous trouverez tous les documents décrit dans ce tuto dans ce même git.

## Lancer la communication

suivre le tuto: http://wiki.ros.org/ROS/Tutorials/ExaminingPublisherSubscriber


## Aller plus loin.

Maintenant que l'on sait envoyer une information d'un code à l'autre, une idée serait d'envoyer d'un noeud un angle. Puis le second noeud utilise cet angle pour trouver la vitesse à imposer aux deux roues du robot en commande linéaire par exemple. 
Pour les STIC/IA cela resemble beaucoup au TP1 de AUT202.
