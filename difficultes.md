### Remarques

À chaque étape, j'ai notifié toute difficulté rencontrée. Voici maintenant les remarques indépendantes des étapes précédentes.

1. Combinaison d'impression normale et avec Octoprint :
La combinaison de l'impression normale et celle avec Octoprint n'est pas toujours aisée. Par exemple, si une impression a été lancée avec Octoprint, il peut être difficile de l'arrêter manuellement. Cependant, certaines actions, comme enfiler le filament ou calibrer le plateau, sont plus faciles à exécuter manuellement. Pour optimiser l'utilisation de l'imprimante, j'ai réalisé un guide indiquant quelles actions effectuer manuellement et lesquelles utiliser avec Octoprint.

2. Connexion de l'imprimante à Octoprint :
Lorsque vous connectez votre imprimante à Octoprint, assurez-vous que le **Baudrate** est défini sur **AUTO**, surtout si vous ne connaissez pas les valeurs nécessaires pour votre imprimante. Dans le cas contraire, vous pourriez rencontrer des erreurs de connexion.

3. Mises à jour d'Octoprint :
Il est essentiel de toujours effectuer les mises à jour d'Octoprint pour éviter des erreurs. L'erreur rencontree icic signale un probleme de connectivité malgré que la connection fonctionne tres bien. Cela se matérialise par cette icone en fome de chaine barrée:
![Problem](assets/chaine.png)
Pour résoudre ce type de problème, j'ai commencé par désactiver **Connectivity Check** sous Settings --> Server, puis j'ai redémarré Octoprint, réactivé la connexion et effectué les mises à jour.
