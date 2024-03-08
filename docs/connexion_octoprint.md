# Connexion de Octoprint a l’imprimante 3D

## Branchement

Votre Raspberry Pi éteinte, connectez votre micro processeur à l’imprimante 3D avec le bon câble USB. Une fois cela fait, allumez l’imprimante 3D, connectez le Pi à une source d’énergie et allumez-le.

Vous pouvez vous murir d'un écran à brancher via HDMI avec le Pi pour suivre l'application de toutes les configurations faites. Pour une première fois, cela peut prendre un peu de temps mais après ce sera beaucoup plus rapide. Vous savez que l'opération est terminée lorsque vous voyez un prompt qui vous invite à vous connecter.

## Acces a Octoprint

Après un démarrage réussi, connectez vous via n'importe quel navigateur mais sur le réseau qui a été configuré avec OctoPi. 
Pour accéder a l'interface web d'Octoprint, vous pouvez utiliser une de ces 2 URLs:

###### http://[nom].local/ avec nom, le nom d'hote que vous auriez mis lors de l'installation de l'image de OctoPi
###### http://[ip] avec ip, l'adresse ip de la raspberry

## Configuration des paramètres

Les principaux parametres incluent:

###### Le controle d'accès
Vous devez y renseigner le nom d'utilisateur et le mot de passe nécessaires pour se connecter à l'interface web d'Octoprint. 

###### Suivi anonyme de l’utilisation
Vous decidez si vous souhaitez qu'OctoPrint collecte de maniere anonyme ou non des donnees de votre part.

###### Verification de la connectivite en ligne

###### Liste noire de plugins
Vous pouvez sélectionner certains plugins que vous mettrez dans votre liste noire.

###### Configuration du profil de l'imprimante
Vous devez mettre un nom pour votre imprimante et renseigner les valeurs correspondantes à votre imprimante.

###### Commandes du serveur
Vous pouvez configurer les commandes du serveur qu’OctoPrint prendra en charge. 

###### Enregistrements par webcam et en accéléré
Vous pouvez configurer les paramètres de votre webcam et mettre en place des enregistrements en accéléré.
Des lors, des que vous cliquez sur "Next" ou "Suivant", vous tomberez sur la page d'Octoprint en elle meme.

## Connexion
Au niveau des paramètres en haut à gauche, cochez les cases "Save connection settings" et "Auto-connect on server startup".
Laissez "Serial Port" et "Baudrate" définis sur AUTO.
Cliquez ensuite sur "Connect" et c'est bon.

Vous n'aurez à faire cette étape qu'une fois.
Toutes les autres fois, votre imprimante sera connectée à moins que vous vous soyez déconnecter.

