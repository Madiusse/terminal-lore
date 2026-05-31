## Pitch

Quelqu'un a vendu la mèche. Un ex-associé, une personne à qui vous faisiez confiance, un adversaire ou juste les services secrets ou la police. Peu importe - vous avez joué avec le feu, vous et aujourd'hui vous en payez le prix. 

Mais tout n'est pas perdu. Il reste encore un peu de temps. Les forces de l'ordre seront bientôt là, en bas de votre immeuble. Vous imaginez déjà les cris des sirènes, des policiers, et des habitants. 

Mais vous avez encore le temps - et les compétences - pour sauver votre peau. Ils ne seront pas dupes, ils savent à qui ils ont affaire, et un changement d'adresse ou un retrait de l'alerte de leurs serveurs ne fonctionnera pas, plus maintenant. Trop facile. Mais vous ne l'êtes pas non plus. 

Ils n'arrêteront pas n'importe qui, mais ils n'hésiterons pas à agir vite non plus - c'est loin d'être des experts comme vous êtes après tout. Impulsifs comme ils sont.

Le temps joue contre vous. Mais prenez au moins le temps de respirer un coup. Allez, au travail.

---
## "Black Hat"
Le but est de faire accuser et arrêter un autre habitant à votre place. Y'a forcément un gus dans ce taudis qui s'y connait un minimum en informatique, non ?
#### 1. Les serveurs des forces de l'ordre
- S'informer sur les moyens qui sont mis à disposition pour votre arrestation, et les informations qu'ils possèdent : un nom ? un pseudonyme ? une apparence ? 
  Comment vous identifier d'un point de vue technique : logiciels utilisés, documents, dossiers, exécutables...
- Identifier les voitures de polices qui arrivent, trouver des manières de gagner du temps (traffic / feux de circulation ?) 
#### 2. Les habitants de l’immeuble
- Analyser les adresses IPs du bâtiment et les ordinateurs connectés.
	- Trouver les IPs avec au moins deux ordinateurs connectés.
	- Croiser avec des informations complémentaires (sexe/genre ? âge ?).
- Trouver les plans du bâtiment pour choisir un appartement à un étage inférieur ; la police ouvrira chaque porte en commençant par le bas (ou le haut ? C'est le futur, ils ont des navettes).
#### 3. Déposer vos fichiers
Grâce aux informations récupérées sur les serveurs de police, vous savez ce que les policiers chercheront sur les ordinateurs des résidents.
- Accéder au.x PC.s du résident idéal à qui faire porter le chapeau.
- Déposer les fichiers nécessaires, sans mettre plus d'informations
- (Supprimer les données plus personnelles du PC infecté ; des choses qui pourraient donner la puce à l'oreille aux enquêteurs).
- Partir sans laisser de traces.

---
## "White Hat"
Le but est de supprimer l'intégralité de vos données et/ou de les uploader sur un serveur en backup pour les récupérer plus tard. Vu votre installation, vous passerez sûrement une nuit musclée au poste. Mais bon, avec du recul, tout est mieux que la prison.
#### 1. Les serveurs des forces de l'ordre
- S'informer sur les moyens qui sont mis à disposition pour votre arrestation, et les informations qu'ils possèdent : ~~un nom ? un pseudonyme ? une apparence ?~~ 
  *... bon pas de bol, trop tard pour se raser la tête ou se faire une teinture.* 
  Comment vous identifier d'un point de vue technique : logiciels utilisés, documents, dossiers, exécutables...
- Identifier les voitures de polices qui arrivent, trouver des manières de gagner du temps (traffic / feux de circulation ?) 

#### 2. Uploader les fichiers nécessaires

On peut imaginer deux versions en fonction de l'évolution/gameplay/logique/histoire.

- ##### 2a. Mettre les fichiers sur un service cloud 
	- Pirater le site de service de cloud
	- Se créer un compte via la base de donnée
	- S'attribuer un serveur
	- Uploader les fichiers
	- Effacer les traces
- ##### 2b. Mettre les fichiers sur un/des serveur.s privé.s
	- Se connecter au serveur privé OU en pirater un.
	- Uploader ses fichiers
	- Effacer les traces

>[!note]+
>Il y a deux points de vue différents qui chacun amènent des points positifs et négatifs :
>
>- 2a ; Plus de mécaniques différentes et plus de choses à faire, mais aussi une certaine dissonance ludo-narrative : quel genre de hacker n'a pas de NAS, ou de serveur privé ? Un hacker qui se connecte à Google Drive, ça fait bizarre. Mais on pourrait toujours le justifier en disant que nos serveurs privés on été saisis et fermés - de par l'informateur qui nous a vendu, et que c'est donc la seule solution sur le moment
>- 2b ; Ca semble plus "facile", plus logique d'un point de vue narratif aussi, mais aussi moins interactif. La solution serait de dire que les serveurs sont limités en taille et que l'intégralité de nos données ne peuvent pas être sur un seul serveur et/ou que le temps d'upload est trop long, et donc qu'il faut charger sur plusieurs serveurs ou disques à la fois.
>
>*En tout cas, l'idée est qu'ensuite on repart sur un ordinateur sans ses fonctions de hacking, et qu'on doit se débrouiller pour récupérer nos logiciels avec les moyens du bord.*
>
>L'idée est que, si jamais on part sur cette manière de résoudre ce scénario, de choisir à mon avis  une méthode ou l'autre à développer, au lieu de proposer les deux. Mais ça reste mon avis personnel, de peur de perdre le joueur, ou alors ça peut justement être une force du gameplay de proposer cette flexibilité. 
>
>"Food for thought".

---
## Intentions de scénario et gameplay
>[!info]+
>L'idée serait donc de à la fois ralentir la police le temps qu'ils arrivent à l'immeuble, et en même temps d'uploader les fichiers sur l'ordinateur cible ou les serveurs. On peut imaginer un système de timer qui décompte et qui ajoute du temps pour chaque fois qu'on ralentit la police - qui serait obligatoire si le PC cible et lent, ou si sa connexion est lente.
>
>L'idée est d'imaginer une réaction du joueur comme "Merde, l'upload des fichiers et/ou le croisement des données (analyse des adresses IPs, etc) va être trop long, ils vont arriver avant, il faut que je trouve un moyen de gagner du temps." Ou alors "évidemment que dès que je suis en danger, tout est lent et long". La loi de Murphy.
>
>Un gameplay "multitâche" qui renforce la pression, qui oblige à prioriser et à être méthodique.

>[!warning]-
>Si je devais choisir et être honnête, la résolution et la méthode "Black Hat" est la plus attrayante selon moi, puisque c'est elle qui m'est venue en tête en premier. J'ai poussé le scope largement et les ambitions, mais si on en gardait une, je pense que ça plus intéressant de garder cette version.
>
>Si c'est le cas, il faudra évidemment trouver des justifications, mais on peut toujours manipuler dans notre intérêt : adresse IP trouvée, connexion internet de l'immeuble isolée, et donc la seule possibilité de faire du ftp ou du P2P - quelque chose de local uniquement.
>
>Sinon, si on part sur ces deux options, il serait intéressant de trouver une justification de partir sur une méthode ou l'autre. On peut contrebalancer la morale d'accuser quelqu'un à tort, avec le fait que puisque le transfert de fichier est "local", dans un même bâtiment, c'est plus rapide. 

