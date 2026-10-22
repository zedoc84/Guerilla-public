# Guérilla — Vetrarhríð

*Nivôse, une île sous la glace, huit forages, et une guerre de partisans à skis.*

*Nivôse: an island locked in ice, eight geothermal wells, and a partisan war fought on skis.*

**[Français](#fr)** · **[English](#en)**

---

<a id="fr"></a>
## Français

Jeu de stratégie au tour par tour sur une carte d'état-major, et de combat à la première personne en 3D. Vous commandez la Garde des Hameaux contre les colonnes blindées de la Concession, qui veulent s'emparer des forages géothermiques qui chauffent l'île.

---

### Installation

#### Dans le navigateur — `Guerilla.html`

1. Téléchargez `Guerilla.html`.
2. Ouvrez-le avec un navigateur récent : Chrome, Edge, Firefox ou Safari.
3. Une connexion Internet est nécessaire au lancement : le moteur 3D et les polices se chargent en ligne.

Le jeu tient en un seul fichier ; il n'y a rien d'autre à installer. Il faut un ordinateur avec clavier et souris ; une manette est reconnue en vue 3D.

#### Application Mac — `Guerilla-mac-AppleSilicon.zip`

Pour Mac à puce Apple (M1 et suivants), macOS 12 ou plus récent. L'application fonctionne hors ligne, sauf pour télécharger une carte réelle.

1. Décompressez le fichier et glissez **Guerilla** dans le dossier **Applications**.
2. Double-cliquez sur l'application. macOS affiche un avertissement, car elle n'est pas encore certifiée par Apple.
3. Ouvrez **Réglages Système > Confidentialité et sécurité** et cliquez sur **Ouvrir quand même**.
4. Si macOS indique que l'application est « endommagée », ouvrez le Terminal et tapez :
   ```
   xattr -cr /Applications/Guerilla.app
   ```

#### Où sont les sauvegardes ?

Les parties, la clé premium et vos cartes restent dans le navigateur (ou dans l'application Mac) qui a servi à jouer. Effacer les données du navigateur les efface aussi. Pour garder une partie ou la passer sur un autre ordinateur : **Menu > Exporter la partie** (un texte à copier), puis **Importer** sur l'écran titre.

---

### Version gratuite et version premium

Il n'y a **qu'un seul fichier**. Le jeu complet est gratuit ; une **clé de licence** débloque la version premium dans ce même fichier.

#### Version gratuite

- **L'île de Nivôse** et sa campagne complète, sans limite de durée.
- **Trois niveaux de difficulté** (Doux, Rude, Rigoureux) et des options : mortiers guidés par avion, chasseur d'attaque, brouillard de guerre, première mission guidée.
- **Toutes les fonctionnalités de jeu** décrites plus bas.
- **Sauvegarde automatique, trois emplacements de sauvegarde**, export et import des parties.

#### Version premium

- **Île aléatoire** : un relief neuf, des hameaux et des installations répartis autrement, un point de départ tiré au sort. Chaque île porte un numéro.
- **Carte réelle** : un vrai lieu, tel qu'il est : le relief, les villages et tous leurs bâtiments (jusqu'à 6 000), les routes et les chemins, les rivières, les lacs, les forêts, les aérodromes et les ponts, d'après OpenStreetMap. Tapez un nom (Chamonix, mont Ventoux, Lofoten…) ou des coordonnées (`45.92, 6.87`, `45°55'N 6°52'E`, ou un lien Google Maps ou OpenStreetMap). Choisissez une zone de 20, 40 ou 60 km et regardez l'aperçu avant de jouer. Les hameaux de la Garde s'installent dans de vrais villages ; églises, chapelles, magasins, garages, gendarmeries et refuges servent comme dans le jeu ; les colonnes suivent les grandes routes et passent les rivières sur les ponts, que l'on peut faire sauter. Le téléchargement prend d'une demi-minute à deux minutes et demande une connexion Internet.
- **Éditeur** : avant la partie, déplacez les hameaux, les installations de la Concession et les pistes ; ajoutez ou retirez des bâtiments ; postez des patrouilles ; choisissez le point de départ du commandant.
- **Mes cartes** : gardez vos créations, **exportez-les** en fichier `.carte-guerilla.json` et **importez** celles des autres joueurs.

#### Activer la version premium

1. Achetez une clé : `[LIEN D'ACHAT]`.
2. Sur l'écran titre, touchez **★ Premium**.
3. Collez votre clé et touchez **Activer la clé**.

La clé est vérifiée sur votre ordinateur, sans compte ni connexion. Le joueur qui reçoit une de vos cartes a besoin de sa propre clé pour y jouer.

---

### Fonctionnalités

- **Le temps** : chaque tour dure deux heures pour chaque membre de la Garde. Jouez-les l'un après l'autre, puis **synchronisez les montres** : la Concession joue à son tour.
- **Rallier** : 31 habitants à rallier autour de votre commandant ; chacun ne suit que certaines personnes (un frère, une fiancée, un vieil ami…).
- **Vue 3D** : à skis, à pied, en motoneige, en deltaplane, en téléphérique et en avion. Les pentes, la poudreuse, le fart, les peaux de phoque et les chutes comptent.
- **Combat** : couteau, pistolet, pistolet-mitrailleur, fusil d'assaut, fusil de chasse, fusil à lunette, grenades et roquettes.
- **Positions de tir** : debout, accroupi ou allongé ; se pencher derrière un arbre ou un mur ; tirer du haut d'un clocher.
- **Escouade** : les recrues présentes au même endroit vous suivent en 3D. On leur donne des ordres et on peut porter un camarade blessé.
- **Garnisons, pisteurs et chiens** ; les tirs sur la Garde ou sur les habitants ont des conséquences.
- **Sabotage** : lignes télégraphiques, ponts, dépôt, usine, relais radio, postes de garde.
- **Bâtiments** : maisons, cabanes, églises, casemates, magasins, garages, stations radio, poudrières…
- **Météo et survie** : le temps change tout seul (neige, tempête, brouillard), et il faut gérer le froid, la faim, les engelures, les avalanches et la glace qui cède. On peut allumer un feu de camp ou creuser un abri de neige.
- **Jumelles** : zoom de ×2 à ×16, vision nocturne et thermique, télémètre, désignation des cibles.
- **Brouillard de guerre** : la carte ne montre que ce que vos recrues et les hameaux amis voient.
- **Gagner** : faites sauter le Bastion, ou détruisez l'usine puis toutes les colonnes. Vous perdez si la Concession tient les huit forages.

Le manuel complet est dans le jeu : **Comment jouer**, sur l'écran titre ou dans le menu.

---

### Les touches

Sur un clavier **AZERTY**, les touches de déplacement sont **Z Q S D** et se pencher se fait avec **A / E**. Sur un clavier **QWERTY**, c'est **W A S D** et **Q / E**. L'aide du jeu affiche les lettres de votre clavier.

#### Sur la carte

| Action | Touche |
|---|---|
| Recrue suivante | N |
| Partir (itinéraire tracé) | Entrée |
| Annuler | Échap |
| Passer en vue 3D | 3 |
| Choisir une recrue, un hameau, une destination | clic |
| Déplacer la carte, zoomer | glisser, molette |

#### En vue 3D

| Action | AZERTY | QWERTY |
|---|---|---|
| Pousser sur les bâtons / accélérer | Z | W |
| Chasse-neige (freiner) | S | S |
| Tourner (à skis) | Q / D ou souris | A / D ou souris |
| Recherche de vitesse (maintenir) | Maj | Shift |
| Regarder | souris | souris |
| Chausser · déchausser les skis | I | I |
| À pied : avancer, reculer | Z / S | W / S |
| À pied : pas de côté | Q / D | A / D |
| À pied : courir | Maj | Shift |
| Se pencher à gauche · à droite (maintenir) | A / E | Q / E |
| Position : accroupi, puis allongé | C | C |
| Se relever · sauter | Espace | Space |
| Tirer · frapper | clic gauche | left click |
| Viser · lunette · lancer le couteau | clic droit | right click |
| Choisir une arme | 1 … 6 ou molette | 1 … 6 or wheel |
| Arme précédente (appui bref) | A | Q |
| Recharger | R | R |
| Mode de tir (coup par coup, rafale) | B | B |
| Coup de couteau rapide | V | V |
| Grenade / roquette | G | G |
| Interagir (appui bref) : hameau, porte, engin, poteau, pont, camarade | E | E |
| Jumelles (molette : zoom) | J | J |
| Vision nocturne · thermique | N ou clic droit | N or right click |
| Allumer · éteindre un feu de camp | H | H |
| Manger une ration | X | X |
| Creuser un abri de neige | K | K |
| Peaux de phoque | P | P |
| Réparer une fixation | U | U |
| Ordre à l'escouade · discipline de feu | O · L | O · L |
| Accélérer le temps | T | T |
| Fusée de détresse | F | F |
| Retour à la carte | M | M |
| Pause | Échap | Esc |

#### En avion

| Action | AZERTY | QWERTY |
|---|---|---|
| Gaz | Z / S | W / S |
| Inclinaison | Q / D ou souris | A / D or mouse |
| Profondeur (lever, baisser le nez) | souris ou flèches | mouse or arrows |
| Freins au sol | Espace | Space |

#### Manette (vue 3D)

| Action | Bouton |
|---|---|
| Avancer, tourner | stick gauche |
| Regarder | stick droit |
| Tirer · frapper | RT |
| Viser · lancer le couteau | LT |
| Sauter | A |
| Schuss (maintenir) · à l'arrêt : changer de position | B |
| Interagir · recharger | X |
| Arme suivante | Y |
| Grenade | LB |
| Jumelles | RB |
| Mode de tir · zoom + | croix haut |
| Couteau · zoom − | croix bas |
| Feu de camp | clic du stick droit |
| Temps ×4 | clic du stick gauche |
| Carte | Select |
| Pause | Start |

---

### Conseils

- **Si le jeu est lent**, baissez la qualité graphique dans le menu de pause (Bas, Moyen, Haut).
- **La nuit** (de 18 h à 6 h), les colonnes bivouaquent : c'est l'heure des sabotages.
- **Lisez les dossiers** des habitants avant de les recruter.
- **Une première mission guidée** s'active sur l'écran titre.

---

### Crédits et licences

Île, personnages, récit, graphismes, sons et musique : création originale. Corps et visages dérivés de MakeHuman (CC0). Moteur 3D three.js (licence MIT). Polices Barlow Semi Condensed, Big Shoulders Display, Cormorant Garamond et Cormorant SC (SIL Open Font License 1.1). Cartes réelles : lieux, bâtiments, routes, rivières, lacs, forêts, aérodromes et ponts © contributeurs OpenStreetMap (ODbL), relief Terrain Tiles (Mapzen, AWS Open Data) et leurs sources. La liste complète est dans le jeu : **Crédits et licences**, en bas de l'écran titre.

© 2026 — tous droits réservés.

---

<a id="en"></a>
## English

A turn-based strategy game played on a military map, combined with first-person 3D combat. You command the Hamlet Guard against the armoured columns of the Concession, which wants to seize the geothermal wells that keep the island warm.

The game itself is in French.

---

### Installation

#### In a web browser — `Guerilla.html`

1. Download `Guerilla.html`.
2. Open it in a recent browser: Chrome, Edge, Firefox or Safari.
3. An Internet connection is needed at launch: the 3D engine and the fonts load online.

The whole game is a single file; there is nothing else to install. You need a computer with a keyboard and mouse; a gamepad works in the 3D view.

#### Mac app — `Guerilla-mac-AppleSilicon.zip`

For Apple silicon Macs (M1 and later), macOS 12 or newer. The app works offline, except for downloading a real-world map.

1. Unzip the file and drag **Guerilla** into your **Applications** folder.
2. Double-click the app. macOS shows a warning because the app is not yet certified by Apple.
3. Open **System Settings > Privacy & Security** and click **Open Anyway**.
4. If macOS says the app is "damaged", open Terminal and type:
   ```
   xattr -cr /Applications/Guerilla.app
   ```

#### Where are my saves?

Games, the premium key and your maps are stored in the browser (or in the Mac app) you play in. Clearing your browser data also deletes them. To keep a game or move it to another computer, use **Menu > Exporter la partie** (export the game as text), then **Importer** on the title screen.

---

### Free version and premium version

There is **only one file**. The full game is free; a **licence key** unlocks the premium version in that same file.

#### Free version

- **The island of Nivôse** with its full campaign, no time limit.
- **Three difficulty levels** (Doux, Rude, Rigoureux) and options: aircraft-guided mortars, attack fighter, fog of war, guided first mission.
- **Every gameplay feature** listed below.
- **Autosave, three save slots**, game export and import.

#### Premium version

- **Random island**: new terrain, hamlets and installations placed differently, and a random starting point. Each island has a number.
- **Real-world map**: a real place as it is: the terrain, the villages and all their buildings (up to 6,000), roads and tracks, rivers, lakes, forests, airfields and bridges, from OpenStreetMap. Type a name (Chamonix, Mont Ventoux, Lofoten…) or coordinates (`45.92, 6.87`, `45°55'N 6°52'E`, or a Google Maps or OpenStreetMap link). Choose a 20, 40 or 60 km area and preview it before you play. The Guard's hamlets settle in real villages; churches, chapels, shops, garages, police stations and mountain huts work as they do in the game; enemy columns follow the main roads and cross rivers on bridges, which you can blow up. The download takes from half a minute to two minutes and needs an Internet connection.
- **Editor**: before the game, move hamlets, Concession installations and airstrips; add or remove buildings; post patrols; choose where the commander starts.
- **My maps** ("Mes cartes"): keep your creations, **export** them as `.carte-guerilla.json` files and **import** maps made by other players.

#### Activating premium

1. Buy a key: `[PURCHASE LINK]`.
2. On the title screen, click **★ Premium**.
3. Paste your key and click **Activer la clé** (activate key).

The key is checked on your own computer, with no account and no connection. A player who receives one of your maps needs their own key to play it.

---

### Features

- **Time**: each turn lasts two hours for each Guard member. Play them one after another, then **synchronise watches**: the Concession then takes its turn.
- **Recruiting**: 31 villagers to rally around your commander; each one only follows certain people (a brother, a fiancée, an old friend…).
- **3D view**: on skis, on foot, by snowmobile, hang-glider, cable car and aeroplane. Slopes, powder snow, ski wax, climbing skins and falls all matter.
- **Combat**: knife, pistol, submachine gun, assault rifle, hunting rifle, scoped rifle, grenades and rockets.
- **Firing positions**: standing, crouching or prone; lean out from behind a tree or a wall; shoot from the top of a church tower.
- **Squad**: recruits in the same place follow you in 3D. You can give them orders and carry a wounded comrade.
- **Garrisons, trackers and dogs**; firing on the Guard or on villagers has consequences.
- **Sabotage**: telegraph lines, bridges, the depot, the factory, the radio relay, guard posts.
- **Buildings**: houses, cabins, churches, bunkers, shops, garages, radio stations, powder magazines…
- **Weather and survival**: the weather changes on its own (snow, storms, fog), and you have to manage cold, hunger, frostbite, avalanches and ice that gives way. You can light a campfire or dig a snow shelter.
- **Binoculars**: ×2 to ×16 zoom, night and thermal vision, rangefinder, target designation.
- **Fog of war**: the map only shows what your recruits and friendly hamlets can see.
- **Winning**: blow up the Bastion, or destroy the factory and then every column. You lose if the Concession holds all eight wells.

The full manual is in the game: **Comment jouer** (how to play), on the title screen or in the menu.

---

### Controls

Movement keys follow their **position** on the keyboard: **W A S D** on QWERTY, **Z Q S D** on AZERTY. Lean with **Q / E** on QWERTY, **A / E** on AZERTY. The in-game help shows the letters of your own keyboard.

#### On the map

| Action | Key |
|---|---|
| Next recruit | N |
| Set off (planned route) | Enter |
| Cancel | Esc |
| Switch to 3D view | 3 |
| Select a recruit, hamlet or destination | click |
| Pan, zoom | drag, mouse wheel |

#### In the 3D view

| Action | QWERTY | AZERTY |
|---|---|---|
| Pole push / accelerate | W | Z |
| Snowplough (brake) | S | S |
| Turn (on skis) | A / D or mouse | Q / D or mouse |
| Tuck for speed (hold) | Shift | Maj |
| Look around | mouse | mouse |
| Put on / take off skis | I | I |
| On foot: forward, back | W / S | Z / S |
| On foot: sidestep | A / D | Q / D |
| On foot: run | Shift | Maj |
| Lean left / right (hold) | Q / E | A / E |
| Stance: crouch, then prone | C | C |
| Stand up · jump | Space | Espace |
| Fire · strike | left click | clic gauche |
| Aim · scope · throw knife | right click | clic droit |
| Select weapon | 1 … 6 or wheel | 1 … 6 ou molette |
| Previous weapon (tap) | Q | A |
| Reload | R | R |
| Fire mode (single, burst) | B | B |
| Quick knife strike | V | V |
| Grenade / rocket | G | G |
| Interact (tap): hamlet, door, vehicle, pole, bridge, comrade | E | E |
| Binoculars (wheel: zoom) | J | J |
| Night · thermal vision | N or right click | N ou clic droit |
| Light · put out a campfire | H | H |
| Eat a ration | X | X |
| Dig a snow shelter | K | K |
| Climbing skins | P | P |
| Repair a binding | U | U |
| Squad order · fire discipline | O · L | O · L |
| Speed up time | T | T |
| Distress flare | F | F |
| Back to the map | M | M |
| Pause | Esc | Échap |

#### Flying

| Action | QWERTY | AZERTY |
|---|---|---|
| Throttle | W / S | Z / S |
| Bank | A / D or mouse | Q / D ou souris |
| Pitch (nose up, down) | mouse or arrows | souris ou flèches |
| Wheel brakes | Space | Espace |

#### Gamepad (3D view)

| Action | Button |
|---|---|
| Move, turn | left stick |
| Look | right stick |
| Fire · strike | RT |
| Aim · throw knife | LT |
| Jump | A |
| Tuck (hold) · when stopped: change stance | B |
| Interact · reload | X |
| Next weapon | Y |
| Grenade | LB |
| Binoculars | RB |
| Fire mode · zoom + | D-pad up |
| Knife · zoom − | D-pad down |
| Campfire | right stick click |
| Time ×4 | left stick click |
| Map | Select |
| Pause | Start |

---

### Tips

- **If the game runs slowly**, lower the graphics quality in the pause menu (Bas, Moyen, Haut — low, medium, high).
- **At night** (6 pm to 6 am), the columns make camp: the best time for sabotage.
- **Read the villagers' files** before you try to recruit them.
- **A guided first mission** can be switched on from the title screen.

---

### Credits and licences

Island, characters, story, graphics, sounds and music: original work. Bodies and faces derived from MakeHuman (CC0). 3D engine three.js (MIT licence). Fonts Barlow Semi Condensed, Big Shoulders Display, Cormorant Garamond and Cormorant SC (SIL Open Font License 1.1). Real-world maps: places, buildings, roads, rivers, lakes, forests, airfields and bridges © OpenStreetMap contributors (ODbL), terrain from Terrain Tiles (Mapzen, AWS Open Data) and their sources. The full list is in the game: **Crédits et licences**, at the bottom of the title screen.

© 2026 — all rights reserved.
