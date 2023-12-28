# Version 2.5.2 - L'énergie

&#x20;:arrows\_clockwise: = En cours de développement\
:thumbsup:= Développement fini et implémentation en cours en jeu

## Ajouts

* **Missions du serveur** : Le but est de faire des missions hebdomadaire que tous le serveur y participent. L'ensemble des gains seront divisés en fonction de la participation des joueurs. :arrows\_clockwise:
* **Missions hebdomadaire** : En plus des missions du serveur en hebdomadaire, il y aura aussi des missions hebdomadaire pour chaque joueur (complémentaire aux missions journalières) :arrows\_clockwise:
* **Challenges d'île** : Dans le même principe que les challenges par joueur, il y aura de nouveaux challenges spécialement conçu pour les îles. :arrows\_clockwise:
* **Autocrafteur** : Vous pourrez crafter automatiquement des items vanilla ou custom. En échange, il faudra alimenter l'autocrafteur par l'électricité. :arrows\_clockwise:
* **Pompe à pétrole** : Pour pouvoir compenser du fait que l'électricité devient de plus en plus importante, il y aura un type de pompe à pétrole à crafter ou acheter en boutique afin de créer automatiquement de l'essence. :arrows\_clockwise:
* **Pompe à LumiFluid** : Comme son nom l'indique, cette va créer du lumifluid automatiquement. Il faudra en plus l'alimenter à l'électricité. :arrows\_clockwise:
* **Shop d'items sacrés** : En plus du /shop actuel, vous aurez une nouvelle catégorie d'achat d'items custom :arrows\_clockwise:
* **Nouveaux minerais** : Mithril, Adamantine. Pas d'indication en plus pour le moment. :arrows\_clockwise:
* **Nouvelles armures** : Tanzanite, Fluorite, Mithril, Adamantine. Pas d'indication en plus pour le moment. :arrows\_clockwise:
* **Empreinte carbone** : Taxe ou Bonus sur l'empreinte carbone que chaque joueur fait sur le serveur (pompe pétrole, fusée, etc.....) :arrows\_clockwise:
* **API de Skylord** : Ajouts de certaines routes à l'api : Classements (île, vote, jobs, money), informations des joueurs (money, wallet, jobs, grade, rang, étoiles), informations d'île (membres, level, place dans le top, banque) :arrows\_clockwise:
* **Seau d'eau infini** : Un Seau d'eau infini va faire son apparition. Il sera disponible en craft et en boutique. Il devra être rempli en fonction des utilisations au forgeron. (C'est logique, ne vous inquiétez pas) :arrows\_clockwise:
* **Troisième donjon** : Un nouveau donjon fait son apparition, disponible dans les voyages :arrows\_clockwise:
* **Spawners** : Ajouts des spawners à poulpe et Noyé :arrows\_clockwise:
* **Passe de combat** : Ajout d'un passe de combat afin de centraliser les missions. Informations à venir. :arrows\_clockwise:

## Modifications des crafts

* **Redstone sacré** : 160 > 120 :thumbsup:
* **Bague de saturation** : 8 bloc de chaque > 4 bloc de chaque. :thumbsup:
* **Armures level 8** : Tout passer de 32 de chaque a 16 de chaque :thumbsup:
* **Coeur de bucheron** : 30 bloc de chaque > 20 bloc de chaque :thumbsup:
* **Coeur de mineur** : 25 bloc de chaque > 15 bloc de chaque :thumbsup:
* **Coeur de pêcheur** : 25 bloc de chaque > 20 bloc de chaque :thumbsup:
* **Coeur d'architecte** : 15 bloc de chaque > 10 bloc de chaque :thumbsup:
* **Coeur de fermier** : 48 bloc de chaque > 25 bloc de chaque :thumbsup:
* **Bagues de vie / résistance / regeneration / mineur level 3** : 2 coeurs > 1 coeur :thumbsup:
* **Baisser le craft des pelles** : (6 : 32 bloc > 16 bloc // 7 : 64 bloc > 32 bloc // 8 : 128 bloc > 64 bloc) :thumbsup:

## Modifications divers

* **Missions journalières** : Un message au milieu de l'écran apparait pour dire que vous fini la mission. :thumbsup:
* **Ganon** est maintenant plus simple :arrows\_clockwise:
* **Changement du sucre sacré par canne à sucre sacré** :arrows\_clockwise:
* **Miner avec l'inventaire plein** :arrows\_clockwise:
* **Transformation du cube féerique en générateur.** Plus d'explication à venir :arrows\_clockwise:
* Refonte des parchemins céleste :arrows\_clockwise:
* Modification des haches avec des Bonus. Plus d'explication à venir :arrows\_clockwise:
* Les coquilles de nautilus peuvent être échangées au pêcheur :arrows\_clockwise:
* Le sable des âmes fait son apparition dans le métier d'architecte :arrows\_clockwise:
* Intégration de la fortune dans les haches :arrows\_clockwise:

## Les corrections de bugs

* Prix de vente palier 6 :arrows\_clockwise:
* Bug bottes level 7 qui donne level 9 au forgeron :arrows\_clockwise:
* "Quand on tue des gobelins sur mécanica la monture ne gagne pas d'exp et ne perds pas de pv mais inflige des dégats" :arrows\_clockwise:
* "Impossible d'allumer le rig qu'on a loué car il demande à être relié à un Network Wallet." :arrows\_clockwise:
* "Certains items sacrés n'ont plus l'effets enchanté tels que : toutes les bûches sacrés sauf le chêne, le poulet sacré, le saumon sacré, le poisson globe sacré, le tropical fish sacré, le nautilus sacré, poche d'encre sacré, la stone brick sacré et le verre sacré" :arrows\_clockwise:
* "Quand on tombe sur arborea on est plus tp" :arrows\_clockwise:
* "Les box boutiques sont bug" :arrows\_clockwise:
* Sur Oréus, la stone ne se reset pas (sur les bords de l'île) :arrows\_clockwise:
* La hache magique avec la pompe améliorée de scotty ne fonctionne pas très bien :arrows\_clockwise:
* On peut utiliser la hache magique sans avoir /mine buy :arrows\_clockwise:
* Le challenge 1 palier 10 fait que de ce reset sur les minerais normaux (j'étais à environ 1000 de chaque) :arrows\_clockwise:
* Le palier 9 challenge 5 j'ai enchant les 128 houes en bois de une ça me la pas compté de 2 je suis a 0/128 :arrows\_clockwise:
* Lors ce que l'on retire l'affichage de scotty, les effets sont enlevés aussi (au changement de planète) :arrows\_clockwise:
* Toujours le bug du shop les joueurs ne peuvent pas vendre quand je suis pas sur mon ile :arrows\_clockwise:
* Les montures font ont un problème de spawn :arrows\_clockwise:
* Bug dans la quete "va voir scotty au spawn" :arrows\_clockwise:
* Probleme avec les panneaux de vente/shop les gens de peuvent pas vendre si je sui sur mon ile :arrows\_clockwise:
* Le /baltop dit d'aller derriere vous sauf qu'il n'y a rien :arrows\_clockwise:
* "J'ai rename des shulks avec sacrée dedans, et quand je veux les poser ca me dis que je peux pas d'item sacrée x)" :arrows\_clockwise:
* "la gemme que le kit joueur donne ne se stack pas avec les autres alors que c'est exactement la même" :arrows\_clockwise:
* "quête journalière pêche elle ne fonctionne pas, que ça soit avec une canne à pêche vanilla ou la clochette" :thumbsup:
* Les mushrooms cow ne se stackent que par 2500  :arrows\_clockwise:
* elle a fumé je crois ... dès que je lance l'hameçon et le récupère elle m'envoie un message  "canne à pêche cyber" :arrows\_clockwise:
* Le casque level 5 n'a pas de barre de dura comme sur le reste de l'armure :arrows\_clockwise:
* La tanzanite n'est pas prise en compte pour cette quete, les autres minerais j'ai pas testé mais ça n'a pas l'air non plus :arrows\_clockwise:
* J'ai ouvert une caisse bonus et j'ai eu cette item qui n'est plus a jour :arrows\_clockwise:
* "J'suis aller réparer mes 42 cg, je faisais full remplir les slots vide, un moment ca a remplis que 2 (alors que j'en avais plus a réparer) donc refait instant remplir, et ca ma delet les deux qui étaient avant ... #RIP mes deux 4090" :arrows\_clockwise:
* Quand on fait /bugreport report, il dit qu'on peut consulter la liste des reports mais en faisant la commande, c'est écrit de faire /bugreport report (bug) :arrows\_clockwise:
* Le /ticket à revoir :arrows\_clockwise:
* Les houes custom ne coupent pas les lianes :arrows\_clockwise:
* "je récupère pas mes clés votes lorsque je vote" :arrows\_clockwise:
* Challenge 5 palier 7 il faut tondre 250mouton ca marche pas :arrows\_clockwise:
* Sur une de mes rigs je peux aps mettre la 14eme CG (elle y était avant, j'ai été réparé et je peux plus) :arrows\_clockwise:
* /ap ne fonctionne pas sur la cobble stone et ancient débris :arrows\_clockwise:
* "le /is expansion team 11 PSEUDO ne fonctionne pas même lorsque le joueur est mvp+, il s'arrête à 9" :arrows\_clockwise:
* La pierre de teleportation te permet de glitch tout les block au spawn :arrows\_clockwise:
* "Quand on n'a l'inventaire full de graine mais que un slot n'est que a 14graine par exemple bah on n'obtient pas la graine mais on perd la thune" :arrows\_clockwise:
* "quand on met pret avant que l'autre mette l'item ca fait bug le trade" :arrows\_clockwise:
* "les pets attaquent bien mais ne gagne pas d'xp" :arrows\_clockwise:
* "j'ai une carte graphique dans un rig qui na pas d'usure (en gros elle me raporte de la thune mais reste a 0% d'usure)" :arrows\_clockwise:
* "Je peut capturer mes pets alors qu'ils sont a moi" :arrows\_clockwise:
* "capturer une monture dans la l'espace" à corriger" :arrows\_clockwise:
* "ça fait 2 fois que j'ai une clé boutique dans une clé nebuleuse et que je fais bug les caisse a cause de cette clé" :arrows\_clockwise:
* "8 joueurs dans le /voyage alors qu'on est 5" :arrows\_clockwise:
* "J'ai vendu des clés à 6M au /ah et j'ai reçu 2x les 6M ;-;" :arrows\_clockwise:
* "il y a un bug ou on peux fly dans l'évent" :arrows\_clockwise:
* Upgrade hopper chunk sur la boutique obtenu avec la caisse boutique :arrows\_clockwise:
* La quête journalière des saumons ne marche pas je suis à 0/15 alors que j'en ai pêcher 34 :arrows\_clockwise:
* "iminent le /fly est activé au spawn au joueurs" :arrows\_clockwise:
* Coinflip le pile gagne a 100% et 0% face :arrows\_clockwise:
* "J'ai fait remplir les slots vide au technicien informatique, il en as refill 2 (jen avais plus) donc j'ai refait remplir, et les 2 déja dedan ont été delet ..." :arrows\_clockwise:
* "les Dory sont des saumons basiques" :arrows\_clockwise:
* Sur phoenotis les herbe pour avoir la pierre des ames il y a le massage comme quoi ont la mais elle n'ai pas drop dans l'inventaire :arrows\_clockwise:
* le spawn via les iles marche pas tu es obligé d'aller chez ifa pour aller spawn et le /fusée ne tp sur aucun planete sa marque ( you don't have permissions for that action) :thumbsup:
* Scotty :&#x20;
  * Il peut maintenant planter et récolter les pastèques / citrouilles :arrows\_clockwise:
  * &#x20;la hache magique avec la pompe améliorée de scotty ne fonctionne pas très bien :arrows\_clockwise:
  * Il mange toute la lumifluid :arrows\_clockwise:
  * L'analyse du parcours prend beaucoup de temps pour + 1000 blocs :arrows\_clockwise:
  * l'inventaire de scotty n'est pas compatible avec les houes custom :arrows\_clockwise:
  * Lorsque l'on jette plus d'un stack d'item, les items vont se split et prendre 2 places dans  l'inventaire. :arrows\_clockwise:
  * le bouton "aujouter l'inventaire" ajoute l'armure dans l'inventaire de scotty :arrows\_clockwise:
  * Scotty à poser de la grass alors qu'il avait de la dirt dans l'inventaire mais au bout d'un moment il s'est mit à remettre de la dirt (il avait juste des patates et de la dirt dans l'inventaire) :arrows\_clockwise:
  * Lorsque l'on jette plus d'un stack d'item (2 stack par exemple) seulement 1 stack rentre dans l'inventaire :arrows\_clockwise:
  * Lorsque 2 slots comportent plus de 2 stack d'item, un autre type d'item ne peut pas rentrer :arrows\_clockwise:
  * Quand on enlève l'affichage de Scotty, après avoir changé de serveur, les pouvoirs repartent :arrows\_clockwise:
  * Ne peut pas récolter les Pastèques/citrouilles :arrows\_clockwise:
  * Ne peut pas planter les patates/carottes :arrows\_clockwise:
  * Quand il effectue ses actions, il n'ajoute rien à son inventaire :arrows\_clockwise:
