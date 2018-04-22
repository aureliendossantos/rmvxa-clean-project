# RPG Maker VX Ace Clean Project

Lors de la création d'un nouveau projet, RPG Maker VX Ace inclut de nombreuses entrées dans la base de données, et impose l'utilisation des RTP. Utiliser des ressources personnelles demande un nettoyage fastidieux de la base de données dans chaque nouveau projet.

Ce projet vierge permet d'éviter cette étape. Il est indépendant des RTP, et contient seulement les fichiers nécessaires au lancement du jeu. La base de données est entièrement vidée pour plus de confort, à l'exception des termes de l'écran-titre.

## Personnalisation

Les termes de l'écran-titre et du script `Vocab` sont en français par défaut. Pour utiliser les termes anglais, copiez les fichiers de `DataEnglish` dans `Data`.

Vous pouvez supprimer le dossier `DataEnglish`, qui n'est pas utilisé par le jeu.

Pour utiliser les RTP, ouvrez le fichier `Game.ini` et ajoutez la ligne `RTP=RPGVXAce`.