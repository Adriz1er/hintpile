Le fait est que pour [[clarifier ses intrants pour passer à la réalité]] il faut séparer les intrants qui seront concrétisables de ceux qui ne le seront pas ^[[[saisir ce qui est nouveau dans une boite de reception avec GTD]]].
# ce qu'on *concrétise*
## l'agenda comme espace *inviolable*
Si une tâche est ***fixée*** à une date on doit la mettre sur l'**agenda** (éventuellement à une heure donnée). On doit considérer l'agenda comme un "espace inviolable où ne figurent que les engagements impératifs".
A noter que le fait est que la majorité des actions sur l'agenda sont à faire *au plus tôt*, (ce qui signifie qu'elles dépendent du contexte) ^[[[choisir ses actions avec GTD grâce à obsidian]]], et qu'il faut donc l'ajouter dans la section *lieu* de son calendrier.
### l'agenda sur obsidian
Il faut télécharger le plugin *Google Calendar*, de l'activer, et suivre ce [tutoriel](https://yukigasai.github.io/obsidian-google-calendar/#/Basics/Installation?id=setup-google-calendar-plugin) détaillé mais malheureusement un peu long ; si vous avez fermé la fenêtre pour votre id client et id client secret il faut cliquer sur l'icone tout à droite pour la réouvrir : ![[Pasted image 20230628111244.png]]. Après ça il faudra copier coller *Client ID* dans les paramètres du plugin, de même pour *Client Secret*.
A présent vous pourrez ajouter un évènement en ouvrant la *palette de commande* et en exécutant cette commande : ![[Pasted image 20230703140719.png|750]]Vous pourrez aussi ouvrir plusieurs vues de votre calendrier, je vous conseille de mettre la "*month view*" en haut dans le panneau de droite ![[Pasted image 20230703134255.png|500]], pour cela il faut ouvrir la *palette de commande* (avec *Ctrl+P*) et utiliser cette commande : ![[Pasted image 20230703134931.png|750]]. Vous pourrez ainsi voir rapidement vos différents évènements.  ^82adc2
## *structurer* ses *projet* doit passer par faire une liste de rappels
La plupart des tâches sont en fait des projets, car on ne fait pas beaucoup de choses sans qu'il y ait une action *future* qu'on puisse faire ensuite.

La majorité des tâches nécessitent plus d'une étape, car on ne fait pas beaucoup de choses sans le fait que une [[gestion de l'action suivante doit se faire par la clarté]]. 
Il faut donc déterminer les deux points suivants : 
1. Quels sont les **projets** dont vous vous occupez et quels sont les *résultats* auxquels vous vous êtes engagé ?
2. Quelle(s) est la (ou les) ***prochaine***(s) ***action***(s) à exécuter ? ^[[[gestion de l'action suivante doit se faire par la clarté]]]

Un **projet** n'est pas un *projet* si on a pas des choses à faire, on doit ainsi **identifier** l'action *suivante* qui fera avancer le projet. 
Ce qui signifie que la majorité des "***tâches***" sont des **projets** (autant que chaque "*grand*" projet puisqu'elles hébergent elles aussi tous les éléments qui leurs sont associées). 
 #👤/David_Allen préconise donc une liste de projets (à noter que "la plupart des gens préfèrent une liste *unique*").
 
 > [!quote]
> Il y a trois domaines susceptibles de cacher des projets :  
> vos activités courantes ; 
> vos intérêts et engagements à des horizons plus élevés ; 
> vos problèmes et opportunités en cours.

### les projets sur obsidian
Lorsqu'il projet est dans les tags c'est qu'il est listé dans la liste de projet

Pour écrire une *action suivante* sur obsidian rien de plus simple que d'écrire `- [ ]` en allant à la ligne ce qui créera une case que l'on peut cocher comme ça (sans #noté) : 
- [ ] #noté

Noté correspond à une tache qui n'est juste noté qui ne sous entend aucunes actions

Quelque chose peut être plus ou moins *prioritaire* ou encore doit être fait avant une certaine date *etc...*, c'est pourquoi il est nécessaire d'installer le *module complémentaire* **Task** (et de l'activer). 

Maintenant à chaque fois que vous créerez une tâche un *petit* menu déroulant va s'afficher pour que vous puissiez indiquer par exemple la priorité etc... Mais pour mieux comprendre vous devriez ouvrir la *palette de commande* (Ctrl+P), sélectionnez la deuxième commande en cherchant Tasks ![[Pasted image 20230627185523.png]], ce qui vous permettra de créer une tâche avec les informations que vous souhaitez ajouter.

Pour indiquer une date d'échéance il suffit de cliquer dans ajouter une propriété et de sélectionner *due* (déjà pré rentré) et rentrer la date à laquelle le projet doit être fait. Si cette date d'échéance correspond à un élément en particulier alors il faut écrire quelque chose comme ça : 
`- [ ] l'action suivante 📅2023-09-17`
Et ce sera affiché sur le panneau de droite. ^95ae19
### les sous projets
Les sous-projets sont un peu comme des sous-concepts au niveau de la gestion, je m'explique pas d'inquiétude : lorsque l'on écrit un sous-concept on écrit un sous-titre ^[[[la prise de notes organique]]] , ce qui donne quelque chose de ce type : ![[Screenshot_20230827-095859~2.png|1000]]
Le fait est qu'il se passe exactement la même chose avec les projets et les sous-projets, mais le fait est qu'un élément (autre qu'une action suivante) sous-entend généralement autre chose qu'il faudra noter par une indentation ^[[[les listes de vérifications sont des rappels créatifs et constructifs#^59e024]]].
### tâche en fonction de l'appareil
Si vous avez besoin de votre ordinateur pour faire quelque chose et que vous tenez à garder une *exhaustivité*, il est nécessaire d'installer le plugin Checklist (et de l'activer). Puis dans ces options de spécifier l'appareil sur lequel vous êtes actuellement dans la section ci-dessous, par exemple mes options sur pc sont : ![[Pasted image 20230627191134.png]], et si ce n'est pas déjà fait de grouper par page, afin de voir à quel projet l'action fait référence : ![[Pasted image 20230627191217.png]]
# ce qu'on ne *concrétise* pas
donnent lieux à trois possibilités :
1. C’est obsolète ou inutile : *poubelle* ! : ![[Pasted image 20230627191332.png]] ![[Pasted image 20230627191412.png|200]]
2. Rien à faire maintenant, mais plus tard peut-être… (*incubation*^[[[effet d'incubation]]]) 
3. C’est une information potentiellement intéressante qui pourrait s’avérer utile un jour de **retrouver** (si trouvable dans un moteur de recherche alors il n'est pas nécessaire d'encombrer ça boite de référence). (*référence*). Donc une référence peut être une archive d'un ==projet==, pour faire en sorte qu'un projet ne soit plus actif il faut que le plugin task ne le détecte et donc mettre le tag #noté à chaque élément qui est **juste** noté ^2b0b18

Cela crée des catégories que l'on va pouvoir gérer : 
2. L'*échéancier* donne *souvent* une liste *un jour peut-être*^[[[effet d'incubation]]] (et éventuellement des sous catégories pour **accumuler** les éléments) que l'on peut se remémorer ***hebdomadairement*** ^[[[révision périodique hebdomadaire est essentielle dans la méthode GTD]]]. Parfois il vaut mieux se **donner des dates** ce qui constitue *agenda perpétuel*, et qu'il est très efficace car il permet de prendre des décisions en un *instant* ^[[[saisir ce qui est nouveau dans une boite de reception avec GTD]]].
Sur obsidian, il suffit de faire d'utiliser l'intégration à todoist ^[[[assumer efficacement ses engagements internes avec GTD#intégration à todoist]]].

A noter que cette catégorie peut potentiellement être partagée, mais il faudra que la personne ait "déjà au moins l’ébauche d’un système analogue". ^4c7598
>Cette catégorie sert à **réévaluer ses projets en cours**, comme **catalyseur de décisions**, ou pour se **rappeler de l'activation d'un projet**. 

> [!quote]
> Bref, l’échéancier n’exige de modifier son comportement qu’une seconde par jour pour être fonctionnel, et on en tire des fruits exponentiels par rapport à l’investissement en temps.

3. Les *références* nécessite d'être ==stockés== par thème et domaines (notamment avec [[la prise de notes organique]] ; qui permet de considérer les projets comme des notes que l'on peut accumuler), ou par des fichiers *généraux*  si c'est impossible. Cela permet de les avoir *sous la main* ; deux critères pour vérifier que la boite à références fonctionne bien :
	- référence accessible en moins de 60 secondes
	- agréable à utiliser

On peut aussi joindre les références à la liste d'incubation, sur l'agenda, sur l'échéancier, notamment dans un projet ou *autre part* ^[[[saisir ce qui est nouveau dans une boite de reception avec GTD]]].
### les tâches terminées comme  référence
Le plugin Task hider permet de masquer les tâches terminées à l'aide d'une commande, ou du bouton dans la barre latérale. 

Il affiche *Showing Completed Tasks* (quelque soit la visibilité des taches achevées).
## l'incubation sur obsidian
Sachez que si vous ne vous y attendiez pas, on devra encore télécharger un nouveau module. Celui-ci s'appelle _Google Tasks_, et il faudra suivre le même tutoriel que pour _Google Calendar_ que je remets [ici](https://yukigasai.github.io/obsidian-google-calendar/#/Basics/Installation?id=setup-google-calendar-plugin), à quelques exceptions près ^[[[clarifier ses intrants pour passer à la réalité#^82adc2]]] : - il faut activer [Google task Api](https://console.cloud.google.com/marketplace/product/google/tasks.googleapis.com?q=search&referrer=search&project=iron-core-327018), que vous pourrez ensuite retrouver comme ci-dessous en violet ![[Pasted image 20230628110042.png|450]] - avoir juste ça (pas de deuxième _URI_) : ![[Pasted image 20230628110847.png|400]] - le plugin vers lequel on copie les identifiants n'est pas le même

Il existe notamment une commande pour créer un nouvel élément à revoir _non_ concrétisable : ![[Pasted image 20230703142527.png]] Grace à ce plugin vous allez avoir un nouveau panneau (avec une _commande_) : ![[Pasted image 20230703133510.png|600]]
Pour mettre la connexion sur mobile il suffit d'exécuter la commande qui copie dans le presse papier et coller le token dans la page d'accueil pour mobile