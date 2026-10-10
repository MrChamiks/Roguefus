# Changelog

## 0.3

Cette version réunit les nouveautés des 0.2.7 et 0.2.8.

**Arène des âmes**
- Nouvelle Taverne des âmes : le soleil à côté du panneau des contrats y mène. Ilyzaelle, la maîtresse des âmes, y vend les pierres d'âme du jeu (petites, moyennes et grandes ; hasardeuses, normales et heureuses).
- Capture comme dans Dofus : une pierre d'âme en main, lancez le sort « Capture d'âmes » pendant un combat de chasse, de donjon ou de la Tour. À la victoire, tentez votre chance sur chaque monstre vaincu avec une pierre assez puissante pour son niveau (sinon : « Pierre d'âme de niveau supérieur requise »). La pierre est utilisée même si l'âme s'échappe ; les chances sont celles de la pierre plus le bonus du sort, moitié moins contre un boss.
- Bestiaire : jusqu'à 60 âmes, avec leur grade, leur niveau et leurs sorts.
- Combats d'âmes : une équipe de 3 âmes contre des âmes de son niveau (facile, normal, difficile), sur le plateau des combats, avec les vrais sorts des monstres. Une âme vaincue est seulement K.O. ; les victoires rapportent des kamas et font monter les âmes de grade (jusqu'à 5). Pas de capture dans l'arène. En solo pour l'instant.
- Les pierres d'âme achetées en 0.2.8 deviennent des Petites Pierres d'âme dans le sac.

**Combat**
- Fin de combat comme dans Dofus : durée et nombre de tours, challenges réussis ou échoués, tableau des gagnants et des perdants (niveau et barre d'expérience, XP gagnée, kamas, objets gagnés), puis le journal (niveaux, sorts, succès).
- Défaite : le même tableau, puis une stèle pour chaque personnage mort, avec le portrait de sa classe.
- Placement sans fenêtre : le bouton de fin de tour sert de « Prêt ». En coop, on l'annule pour bouger encore, et les épées croisées de Dofus apparaissent au-dessus des joueurs prêts.
- Ordre de jeu fidèle à Dofus : les équipes jouent chacune leur tour, et l'ordre s'affiche dès le placement.
- IA : les monstres blessés se battent jusqu'au bout, ceux qui frappent au corps à corps ne restent plus à distance, et un glyphe n'est traversé que s'il n'y a pas d'autre chemin (plus de monstres qui refusent d'attaquer).
- Niveau des combattants dans leur fiche, et au survol pendant le placement.
- Durées des effets : le tour où on se lance un sort ne compte plus (Mot de Prévention 1 tour tient jusqu'à la fin du tour suivant).
- Sorts qui ne touchent que certaines cibles : l'Épée Divine ne blesse plus les alliés, et ainsi de suite pour tous les sorts concernés.
- Ennemis invisibles vraiment invisibles : ni silhouette, ni son, ni fiche ou portée au survol, et ils ne bloquent plus la ligne de vue ; marcher sur l'un d'eux arrête le personnage : « Quelque chose bloque le passage ».
- « Fin du tour » pendant une action : le tour passe une fois l'action finie.
- Animations de sorts corrigées : Flèche Enflammée, Destructrice, Punitive et une vingtaine d'autres ; Couper et plusieurs effets ne se rejouent plus en boucle.
- Sons : coup critique et échec critique remis à l'endroit, sons des attaques sur dragodinde et de l'arc du Crâ.
- Icônes d'effets juste au-dessus des têtes ; la file d'attente ne coupe plus le combattant actif.

**Équilibrage**
- Monstres et personnages tels que dans Dofus : plus de monstres affaiblis quand on est peu nombreux, plus de monstres renforcés dans la Tour, et la vie des classes redevient celle d'origine (fin des bonus de vie du Féca et du Pandawa).
- Chasses : on dose le combat par la composition du groupe, dont le niveau total suit celui des personnages (le niveau de groupe de Dofus), selon la difficulté choisie. La fenêtre de chasse indique le niveau des monstres.
- Tour sans Fin : elle se durcit par la composition de ses étages, plus par les caractéristiques des monstres.
- Donjons : tels que dans le jeu de base en difficulté normale (Héroïque et Mythique gardent leurs monstres renforcés).
- Expérience : une salle de donjon ou un étage de la Tour rapporte toujours plus qu'une chasse difficile de son niveau.

**Village et donjons**
- La barre d'icônes ne mène plus aux PNJ : on va voir le forgeron, la chasse, les donjons et l'arène des âmes sur l'île. Icônes de Dofus pour l'Équipe, les Succès, le Multijoueur et les Émotes.
- Cliquer sur un soleil fait changer de lieu, comme dans Dofus.
- Course sur les longs trajets, et en tenant Maj (LT à la manette) en déplacement libre.
- Soin complet entre chaque salle de donjon et chaque étage de la Tour.
- Dragodindes : le cavalier porte sa coiffe, sa cape et son équipement, et les autres joueurs le voient monté.
- Toujours pleine vie au village (un malus de vitalité ne retire plus de PV).

**Objets**
- Pierres d'âme : tenues en main à la place de l'arme, elles donnent le sort « Capture d'âmes ».
- Résistances fixes (Amulette de l'Homme Ours…) et prospection prises en compte (la prospection augmente les chances de butin).
- Sacs à dos : portés à la place de la cape et dessinés sur le personnage ; certains complètent une panoplie (Sac-Cawotte du Wabbit…).
- Les pièces de panoplie qui ne donnent rien seules (Ceinture du Bouftou, Ceinture en Mousse…) se trouvent de nouveau, pour compléter leur panoplie.
- Retirés du jeu : la panoplie du Champion, les armes éthérées et les objets qui ne donnaient rien (hors panoplie).

**Interface**
- Plus aucune fenêtre du navigateur : les confirmations (supprimer un personnage, duel à mort, réinitialiser, restaurer une sauvegarde…) s'ouvrent dans le style du jeu.


## 0.2.6

**Combat**
- Menu du personnage en bas à droite (caractéristiques, sorts, équipement), modifiable pendant le placement uniquement, en solo comme en coop.
- Icônes des effets au-dessus des combattants (bonus en bleu, malus en rouge), masquables.
- Clic sur un combattant : sa fiche reste épinglée (buffs, poisons, états).
- Survol de la file d'attente : le combattant est mis en évidence sur le plateau.
- Montrer une case à l'équipe : Alt + clic ou bouton ▼.
- Duels à mort, avec confirmation des deux côtés, et trois succès.
- Partie privée : elle n'apparaît plus dans la liste, on la rejoint avec son code.
- Abandon : une chance sur deux de perdre tout l'équipement porté, sinon le personnage meurt.
- Temps par tour fixé à 60 s.
- Manette : le curseur reste dans les cases de déplacement.

**Village**
- Ambiance sonore (vagues, vent, oiseaux), avec son propre réglage.
- Un clic pendant la marche change la destination.
- Barre d'icônes repliable (animée à l'ouverture et à la fermeture), au style de l'encadré du personnage.
- Points de capital et de sort à dépenser : icônes à côté de l'encadré.
- Forgeron : panoplies triées par niveau, filtre ± 10 niveaux, filtres par bonus (agilité, PA…).
- Coffres refaits : objets hors panoplie, la rareté fixe la qualité des jets, et un légendaire peut gagner une ligne bonus (1 % +1 PA, 2 % +1 PM, 3 % +1 PO).
- Kamas : un combat rapporte bien plus quand le groupe ennemi est de haut niveau, et les donjons et la Tour sans Fin rapportent toujours plus que les chasses (bonus à chaque salle, doublé contre un boss).
- Mort définitive renforcée : restaurer une ancienne sauvegarde ne ramène plus un personnage mort.
- Barres de sorts : retirer un sort, éditeur affiché à la demande.
- Fenêtres déplaçables à la souris.

**Interface**
- Mise à jour en un clic depuis le jeu (écran titre ou Options) : téléchargement, installation, redémarrage. Personnages et fichiers du jeu gardés.
- Échap ou Start ouvre les Options : son, raccourcis (onglet à part), retour à l'écran titre, quitter.
- Boutons Musique / Sons / Ambiance retirés de l'écran (ils sont dans les Options).
- Thème sombre : chat, menu de la manette et barre d'icônes harmonisés.

**Corrections**
- Objets de maître de jeu (MJ) retirés du jeu et des sauvegardes (+300 dans toutes les caractéristiques au niveau 1…).
- Apparence (coiffe, bouclier, « objet porté ») fausse au village.
- Molette du village qui sautait des crans.
- Bande sombre en bas de l'écran du village.
- Musique du village parfois absente au premier passage.
