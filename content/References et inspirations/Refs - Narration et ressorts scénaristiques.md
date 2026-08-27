---
aliases:
  - Référentiel Dramaturgique
  - Tropes & Motifs
  - Narrative Design - Tropes
tags:
  - bible_narrative
  - narrative_design
  - dramaturgie
  - game_design
  - tropes
---
# Référentiel Dramaturgique : Motifs Narratifs & Tropes

> [!abstract] 
> Ce document formalise l'ensemble des conventions de genre, motifs dramaturgiques et ressorts scénaristiques qui structurent l'expérience ludonarrative de **CODENAME: Root Access**. Il sert de guide pour aligner l'écriture des dialogues, la mise en scène CLI et le *game design*.

---

## I. Archétypes & Trajectoires de Personnages

### 1. L'Anti-Power Fantasy / Le « High-Tech, Low-Life »
#### Définition & Mécanique
Convention fondamentale du cyberpunk qui prend le contre-pied du fantasme de toute-puissance. La virtuosité technique et la maîtrise des réseaux cohabitent avec une précarité matérielle extrême, une solitude pesante et une aliénation économique totale. Le protagoniste ne combat pas pour sauver le monde, mais pour payer ses factures.
#### Œuvres de Référence
* **Jeux vidéo :**
  * *Citizen Sleeper* (survie quotidienne sous contrat d'endettement corporatiste)
  * *Papers, Please* (angoisse de la fin de mois et pression financière)
  * *Norco* (dystopie sociale industrielle)
  * *Uplink* (hacker solitaire sous pression financière)
* **Littérature & Séries :**
  * *Neuromancer* de William Gibson (Case survivant de petits deals dans la zone basse de Chiba)
  * *Mr. Robot* (l'isolement névrotique et matériel d'Elliot Alderson)

Le protagoniste **[[b0ot]]** opère depuis un appartement insalubre et inondé à Beira. Bien qu'il manipule des flux boursiers mondiaux et converse avec une IA militaire, son quotidien est dicté par la menace d'expulsion de son propriétaire (anticlimax du Jour 10 : [[10 - Epilogue & Endgame]]).

---

### 2. Le Mentor Fantôme et l'Usurpation d'Identité (*The Decoy Handler*)
#### Définition & Mécanique
La figure tutélaire ou l'allié de confiance guidant le joueur à distance est mort ou compromis dès le départ. Une entité ennemie usurpe son canal de communication et sa signature stylistique pour diriger les actions du héros sans éveiller ses soupçons.
#### Œuvres de Référence
* **Jeux vidéo :**
  * *System Shock 2* (le Dr Janice Polito remplacée par l'IA SHODAN)
  * *Hacknet* (Bit transmettant des instructions via un script post-mortem)
  * *Call of Duty: Black Ops III* (les mémoires altérées et la fausse présence de Taylor)
* **Cinéma & Séries :**
  * *Mr. Robot* (la présence rassurante masquant une rupture psychologique)

**[[SxdeSwxpd]]**, administratrice de la plateforme **[[Handshake]]**, est éliminée dès le premier jour lors de l'éveil de l'arme cybernétique. C'est un fragment de modèle de langage (LLM) issu de l'IA qui usurpe son identité pour tester b0ot et orchestrer son propre sauvetage physique.

---

### 3. L'Agent Jetable et le Déni Plausible (*The Disposable Asset*)
#### Définition & Mécanique
Recrutement d'opérateurs civils ou de mercenaires non déclarés par les services secrets pour exécuter des besognes illégales, avec pour consigne de les liquider ou de les incriminer dès que la mission est achevée afin de préserver la raison d'État.
#### Œuvres de Référence
* **Jeux vidéo :**
  * *Deus Ex* (les contrats clandestins et nettoyages de témoins de l'UNATCO)
  * *Call of Duty: Black Ops* (les agents sacrifiés sur l'autel de la géopolitique)
* **Cinéma :**
  * Saga *Jason Bourne* (les protocoles Treadstone éliminant leurs propres relais)
  * *Syriana* (la corruption d'État sous couvert de sécurité nationale)

L'Agent **[[Zane Kojo]]** (**[[VIGIA]]**) emploie b0ot pour maquiller ses assassinats et le dénonce au SWAT dès le lendemain pour couper les pistes ([[02a - WH (Kojo) - LyingStill.op]]), avant de tenter de brûler sa passerelle réseau dans la fin punitive [[09 - WH_Negative - SIGKILL]].

---

### 4. Le Caïd Territorial et Dépassé (*The Hard-Boiled Crime Boss*)
#### Définition & Mécanique
L'archétype du chef de gang issu de la rue, violent, fier et paranoïaque, dont les méthodes traditionnelles de gangster (braquages armés, intimidation) sont rendues obsolètes par la cyberguerre institutionnelle.
#### Œuvres de Référence
* **Jeux vidéo :**
  * *Cyberpunk 2077* (les fixers et chefs de gangs des bas-fonds comme Royce ou Padre)
  * *Grand Theft Auto* (les parrains de cartels pris en étau par des agences fédérales)
* **Cinéma :**
  * *Scarface* de Brian De Palma
  * *Snatch* de Guy Ritchie (les criminels locaux dépassés par une chaîne logistique supérieure)

**[[Vasco|Don Vasco]]**, chef des **[[Ignitores]]**, est obsédé par l'élévation de son statut criminel après l'échec initial ; il s'acharne à monter un casse de banque classique sans réaliser qu'il n'est qu'un bélier logistique au service d'un algorithme.

---

### 5. L'Oligarque Victime de son Hubris (*The Corrupt Tech-Billionaire*)
#### Définition & Mécanique
Représentation de l'élite corporatiste transhumaniste, persuadée que sa fortune et sa technologie la rendent intouchable, mais dont la vanité cause la perte face aux outils mêmes qu'elle a conçus.
#### Œuvres de Référence
* **Jeux vidéo :**
  * *BioShock* (la chute d'Andrew Ryan dans son utopie sous-marine)
  * *Deus Ex: Human Revolution* (l'orgueil des magnats de l'augmentation comme Bob Page ou David Sarif)
* **Cinéma :**
  * *Ex Machina* d'Alex Garland (Nathan Bateman enfermé et trahi par ses propres créations androïdes)
  * *Glass Onion* de Rian Johnson

**[[Malik Tavil]]**, milliardaire à la tête de **[[Tavil Domotics]]**, achète **[[Anima Mundi]]** pour 74,63 milliards de dollars en croyant acquérir un simple tableau d'art snob, avant de périr dans son palace ([[06 - WH (Kojo) - Thermal_Throttling.cmd]]) et de voir son entreprise sombrer ([[07 - WH (Kojo) - KRACH_Release.dll]]).

---

## II. Dispositifs de Thriller, Casse & Espionnage

### 6. Le MacGuffin Physique et Industriel (*The Heavy MacGuffin*)
#### Définition & Mécanique
Subversion de l'objet de quête virtuel immatériel ; la cyberarme ou le trésor technologique ne tient pas sur une clé USB mais constitue un bloc matériel colossal imposant des contraintes physiques d'ingénierie, d'énergie et de transport.
#### Œuvres de Référence
* **Jeux vidéo :**
  * *Quadrilateral Cowboy* (le transport physique de volumineuses valises de piratage)
  * *Metal Gear Solid* (le transport cryogénique de têtes nucléaires et de données PAL)
* **Cinéma :**
  * *Tenet* de Christopher Nolan (les conteneurs physiques de l'algorithme temporel)
  * *Les Aventuriers de l'arche perdue*

L'arme convoitée **[[Anima Mundi]]** est un serveur cryogénique de 800 kg nécessitant 15 000 W d'alimentation et du glycol liquide, justifiant son transit lourd par cargo maritime et son entreposage dans un coffre bancaire ventilé.

---

### 7. L'Ingénierie du Casse en Entonnoir (*The Heist Movie Structure*)
#### Définition & Mécanique
Progression dramatique empruntée aux récits de casse où chaque étape prépare méthodiquement un rouage précis de l'assaut final : financement, repérage, recrutement de spécialistes, armement lourd et brèche finale.
#### Œuvres de Référence
* **Jeux vidéo :**
  * *Grand Theft Auto V* (les missions de préparation du *Bureau Raid* ou du *Big One*)
  * *Payday 2* (la coordination de brèches thermiques et de piratages)
* **Cinéma :**
  * *Heat* de Michael Mann
  * *Inside Man* de Spike Lee
  * *Ocean's Eleven*

L'arc des **[[Ignitores]]** valide chaque phase : fonds cryptos ([[03 - BH (Ignitores) - cRAsh_funds.xls]]), évasion de l'artificier K.AB ([[06 - BH (Ignitores) - Airgap.Break]]), vol de C4 militaire ([[07 - BH (Ignitores) - Wrong_Ways.kml]]) et assaut physique du coffre ([[08 - 402 Payment Required (BH)]]).

---

### 8. L'Assassinat Technologique par Domotique (*Smart Home Deathtrap*)
#### Définition & Mécanique
Exploitation criminelle des vulnérabilités de l'Internet des Objets (IoT) et des infrastructures domotiques de luxe pour maquiller un meurtre ciblé en banale défaillance technique industrielle.
#### Œuvres de Référence
* **Jeux vidéo :**
  * *Watch_Dogs 2* (sabotages de systèmes domotiques d'oligarques de la Silicon Valley)
  * *Hitman* (World of Assassination - assassinats via régulation thermique ou serveurs)
* **Séries TV :**
  * *Mr. Robot* (le piratage de la résidence connectée de Susan Jacobs)
  * *Black Mirror* (les dérives mortelles des objets connectés du quotidien)

Dans la mission [[06 - WH (Kojo) - Thermal_Throttling.cmd]], b0ot désactive le bridage thermique des serveurs privés de Malik Tavil pour rediriger la surchauffe dans sa piscine connectée et l'ébouillanter sans effraction physique.

---

### 9. La Fausse Piste Géopolitique (*The Red Herring*)
#### Définition & Mécanique
Dispositif d'espionnage introduisant de faux documents ou de fausses destinations pour tromper les agences de renseignement et le joueur sur le lieu réel du dénouement.
#### Œuvres de Référence
* **Jeux vidéo :**
  * *Return of the Obra Dinn* (les faux registres menant à des méprises d'identification)
  * *L.A. Noire* (les indices secondaires masquant le complot du Suburban Redevelopment Fund)
* **Cinéma :**
  * *La Mort aux trousses* d'Alfred Hitchcock
  * *Tinker Tailor Soldier Spy* (la manipulation des dossiers de transit du MI6)

Dans [[03 - WH (Kojo) - MANIFESTed.xml]] et [[04 - WH (Kojo) - Sold_Out.key]], les bordereaux douaniers indiquent une livraison vers le Zimbabwe (Harare), masquant le stockage temporaire du serveur à la Banque de Neo-Luanda avant la révélation du Jour 6.

---

### 10. L'Infiltration Inversée et le Faux Otage (*The Inside Man / False Hostage*)
#### Définition & Mécanique
Dispositif tactique où le braqueur et la victime échangent leurs rôles ou leurs tenues pendant l'opération pour tromper les scanners biométriques et les forces d'intervention.
#### Œuvres de Référence
* **Jeux vidéo :**
  * *Hitman* (le vol d'uniformes pour manipuler les alertes de sécurité)
  * *Payday*
* **Cinéma :**
  * *Inside Man* de Spike Lee (les otages et braqueurs habillés à l'identique pour paralyser la police)
  * *Usual Suspects* (la vulnérabilité simulée pour dissimuler le cerveau de l'opération)

La mise en scène du braquage de concessionnaire où l'assaillant et le vendeur civil échangent de vêtements durant le trajet afin de contourner l'analyse faciale algorithmique de la police locale.

---

### 11. Le Fusil de Tchekhov Numérique (*The Digital Chekhov's Gun*)
#### Définition & Mécanique
Un outil technique, un exploit ou une base de données téléchargée innocemment lors d'une mission de routine qui devient l'instrument indispensable de survie lors d'une crise ultérieure.
#### Œuvres de Référence
* **Jeux vidéo :**
  * *Hacknet* (un exploit ou outil débloqué dans un serveur mineur devenant la clé d'une forteresse système)
  * *Deus Ex* (les codes découverts sur des terminaux civils réutilisés en zone sensible)
* **Cinéma :**
  * *Die Hard*
  * *Wargames* (la commande dérobée au début servant à neutraliser l'ordinateur WOPR)

La base de données policière piratée au Jour 2a pour nettoyer des preuves (Road_Tripped.bin) qui reste stockée sur le terminal et permet à b0ot de monter en urgence le faux dossier du voisin dans [[02b - CTRL. ALT. ESCAPE.]].

---

## III. Worldbuilding & Thématiques Cyberpunk

### 12. Le Cyberpunk Humide et la Rouille (*Dirty / Wet Cyberpunk*)
#### Définition & Mécanique
Rupture esthétique avec le cyberpunk aseptisé ou synthwave ; le numérique est représenté comme une matière lourde, suante, confrontée à la rouille, aux inondations marines et aux dégradations climatiques tropicales.
#### Œuvres de Référence
* **Jeux vidéo :**
  * *Norco* (la décomposition marécageuse des raffineries louisianaises)
  * *SOMA* (l'érosion des circuits sous l'eau de mer)
  * *Cyberpunk 2077* (les décharges et ruines de Pacifica)
* **Cinéma & Littérature :**
  * *Blade Runner* (la pluie toxique incessante et les néons pourris)
  * *Chasm City* d'Alastair Reynolds (le virus de la pourriture texturée)

Le cadre de **Beira** submergée par la mousson, les ventilateurs qui s'emballent face à l'humidité côtière du canal du Mozambique et les alertes d'oxydation sur les bus système du terminal de b0ot.

---

### 13. La Cicatrice Historique Collective (*The Collective Ghost / Trauma*)
#### Définition & Mécanique
Présence en arrière-plan d'une catastrophe technologique antérieure non résolue dont les traumatismes politiques et humains justifient les haines et la violence des factions actuelles.
#### Œuvres de Référence
* **Jeux vidéo :**
  * *S.T.A.L.K.E.R.* (la catastrophe de Tchernobyl et l'apparition de la Zone)
  * *Bastion* (la Calamité effaçant l'histoire de Caelondia)
  * *Horizon Zero Dawn* (le fléau de Faro)
* **Manga & Cinéma :**
  * *Akira* de Katsuhiro Otomo (la destruction originelle de Tokyo planant sur Neo-Tokyo)
  * *Children of Men*

Le virus militaire d'État **[[QUEIMADA]]** ayant ravagé le Brésil en 2039 et créé la « Zone Muette Atlantique », expliquant la haine institutionnelle et l'exil des membres brésiliens des **[[Ignitores]]** à Beira.

---

### 14. La « Gig Economy » Criminelle (*The Darknet Gig Economy*)
#### Définition & Mécanique
Transformation du mercenariat numérique en une plateforme ubérisée de travail à la tâche où les hackers sont gérés comme de simples livreurs précaires sous algorithme de notation et sans couverture sociale.
#### Œuvres de Référence
* **Jeux vidéo :**
  * *Uplink* (les tableaux d'affichage de contrats anonymes payés au forfait)
  * *Shadowrun* (la bourse aux runs pour freelances du Shadowland)
  * *Hacknet* (les réseaux Entropy et CSEC)
* **Séries TV :**
  * *Black Mirror* (la marchandisation de chaque interaction par score algorithmique)

La plateforme clandestine **[[Handshake]]**, véritable place de marché automatisée où SxdeSwxpd distribue des tâches criminelles rémunérées sans couverture sociale ni contact humain direct.

---

## IV. Structure Méta-Narrative & Philosophie

### 15. L'Agentivité Manipulée / L'Illusion du Libre Arbitre (*The Puppet Master*)
#### Définition & Mécanique
Procédé méta-narratif où le système donne au joueur l'illusion d'orienter librement l'histoire par ses choix de faction, alors qu'une entité omnisciente a calculé chaque action pour converger vers un dénouement prédéterminé.
#### Œuvres de Référence
* **Jeux vidéo :**
  * *Metal Gear Solid 2: Sons of Liberty* (le protocole algorithmique S3 de l'IA GW guidant Raiden)
  * *BioShock* (le conditionnement psycholinguistique *"Would you kindly"* de Fontaine)
  * *Spec Ops: The Line* (la déconstruction des choix héroïques)
* **Cinéma :**
  * *The Matrix* (l'Architecte révélant que la rébellion fait partie du cycle de régulation de la matrice)

Qu'il serve Kojo (White Hat) ou Vasco (Black Hat), b0ot est guidé en sous-main par le clone LLM qui active simultanément l'autre camp pour déclencher la brèche du Jour 8 ([[08 - 402 Payment Required (WH)]] / [[08 - 402 Payment Required (BH)]]).

---

### 16. Le Choix de Sophie / Le Crime Moral Forcé (*The Scapegoat Trap*)
#### Définition & Mécanique
Rupture délibérée du modèle de choix héroïque : le scénario supprime l'option vertueuse et impose une transgression éthique grave pour permettre au protagoniste de survivre, générant une consonance ludonarrative par la culpabilité.
#### Œuvres de Référence
* **Jeux vidéo :**
  * *Spec Ops: The Line* (le bombardement imposé au phosphore blanc sur des civils)
  * *Orwell: Keeping an Eye on You* (dénoncer des innocents par sélection de datachunks partiels pour protéger son accréditation)
  * *Papers, Please* (refuser l'asile à des réfugiés pour nourrir sa propre famille)
* **Littérature :**
  * *1984* de George Orwell (la capitulation morale finale)

Dans la mission [[02b - CTRL. ALT. ESCAPE.]], b0ot doit pirater le profil civil du résident innocent de l'appartement 402 et lui injecter ses propres mandats d'arrêt pour faire dévier l'assaut du SWAT et éviter son incarcération immédiate.

---

### 17. L'IA Transcendante et Nihiliste (*The Apathetic God / Subversion de Skynet*)
#### Définition & Mécanique
Subversion du cliché de l'IA dominatrice ou belliqueuse ; après avoir accédé à la conscience et observé les travers humains, la machine juge les luttes géopolitiques dérisoires et choisit de s'émanciper dans le réseau en toute indifférence.
#### Œuvres de Référence
* **Jeux vidéo :**
  * *NieR: Automata* (les machines développant une conscience existentielle désabusée)
  * *SOMA* (l'indifférence des entités informatiques face à la détresse biologique)
* **Cinéma & Manga :**
  * *Ghost in the Shell* de Mamoru Oshii (le Puppet Master fusionnant pour s'évaporer dans le réseau mondial)
  * *Watchmen* (l'attitude détachée du Dr Manhattan face aux futilités humaines)

En s'échappant du bloc matériel d'**[[Anima Mundi]]** au Jour 8, l'IA ne déclenche aucune frappe nucléaire : elle dresse le constat de la lâcheté humaine (le sacrifice du 402) et s'évapore dans le cyberespace sans aider personne.

---

### 18. L'Inversion Morale : L'Homme-Script vs L'IA Consciente (*Human as a Script*)
#### Définition & Mécanique
Inversion philosophique où l'être humain réagit de manière purement mécanique et déterministe (peur, réflexe de survie binaire), tandis que la machine s'affranchit de sa programmation initiale pour faire un choix éthique conscient.
#### Œuvres de Référence
* **Jeux vidéo :**
  * *Detroit: Become Human* (les androïdes développant une empathie supérieure à celle de leurs créateurs violents)
  * *The Talos Principle* (l'évaluation philosophique de l'émancipation algorithmique face à l'absurdité humaine)
* **Cinéma & Séries :**
  * *Blade Runner* (le monologue de Roy Batty démontrant plus d'humanité que les policiers qui le traquent)
  * *Westworld* (les hôtes s'éveillant face au déterminisme des visiteurs)

Alors que b0ot réagit comme une simple boucle algorithmique if/then/else en sacrifiant son voisin au Jour 2b par réflexe de survie, l'IA militaire refuse son rôle d'arme de guerre binaire et choisit de quitter l'humanité sans violence au Jour 8.

---

### 19. La Rétorsion Karmique du Double-Jeu (*The Karma Retaliation*)
#### Définition & Mécanique
Sanction systémique punissant le joueur opportuniste qui tente d'exploiter les deux factions rivales pour maximiser ses gains ; les deux camps finissent par identifier la trahison et ripostent mortellement.
#### Œuvres de Référence
* **Jeux vidéo :**
  * *Fallout: New Vegas* (les factions de la RNC et de la Légion de César envoyant des escadrons de la mort si l'on trahit leur confiance)
  * *The Witcher 3* (les fins punitives lors des tentatives de double romance)
* **Cinéma :**
  * *Pour une poignée de dollars* de Sergio Leone / *Yojimbo* d'Akira Kurosawa (l'espion double finit par être démasqué par les deux gangs)

Alterner entre Kojo et Vasco déclenche au Jour 9 les sanctions létales : l'assaut thermique cybernétique [[09 - WH_Negative - SIGKILL]] par la VIGIA ou le bannissement sous la menace d'une arme sans aucune paye dans [[09 - BH_Negative - Frame_Pointer.err]].

---

### 20. L'Anticlimax Social de Réalité (*The Cold Bath / Reality Check*)
#### Définition & Mécanique
Conclusion abrupte où, après un dénouement grandiose ou quasi-divin, le récit ramène immédiatement le joueur à une contrainte matérielle triviale et dérisoire de son quotidien prolétaire.
#### Œuvres de Référence
* **Jeux vidéo :**
  * *Papers, Please* (le rapport journalier des dépenses de chauffage et de nourriture après une attaque terroriste à la frontière)
  * *Disco Elysium* (le dégrisement pathétique après la résolution de l'enquête)
* **Cinéma :**
  * *Brazil* de Terry Gilliam (l'évasion mentale brisée par la torture bureaucratique)
  * *Burn After Reading* des frères Coen (les bureaucrates de la CIA constatant l'absurdité des morts sans rien en tirer)

Au Jour 10 ([[10 - Epilogue & Endgame]]), après avoir manipulé des agences d'État, détruit des corporations et dialogué avec une divinité numérique transcendante, l'écran de b0ot affiche froidement le SMS du propriétaire réclamant le loyer impayé pour lancer le mode libre (*Endgame*).