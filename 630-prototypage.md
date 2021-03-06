---
layout: page
title: Prototypage
permalink: /outils/prototypage/
---

Prototypage, maquettage, wireframing
===

Les outils graphiques utilisés pour créer des maquettes de sites web sont aujourd'hui très variés. Ces outils sont souvent utilisés aussi bien pour les maquettes de sites que d'applications, ces deux domaines étant confrontés aux mêmes problématiques (multiplicité des écrans et méthodes d'interaction). 

Dans un livre publié en 2008?, (Prototyping, par Todd Zaki Warfel), l'auteur indique: 

> There isn't a dedicated prototyping tool for non-coders that can create rapid prototypes with little effort and produce reusable source code. 

Son livre fait référence aux logiciels suivants: PowerPoint, Keynote, Visio, Fireworks, Axure, et... HTML et JavaScript.

Depuis quelques années, la pertinence des outils de design classiques dans l'environnement du web a fait l'objet de vifs débats: 

- Article de Brad Frost: “[The Post-PSD Era](http://bradfrost.com/blog/post/the-post-psd-era/)” (2013) - "Are we entering the Post-PSD Era of web design?" - L'auteur relève des faiblesses de Photoshop pour la réalisation de maquettes web: supports de taille et résolution variable. Eléments interactifs tels que les liens. 
- Article de Emelyn Baker: “[2014 - The Year of Interaction Design Tools](https://medium.com/@extremelyn/2014-the-year-of-design-tools-3c449d771e62#.542hf0q21)”
- Khoi Vinh, mai 2015: “[The State of Design Tools: An Unscientific Survey](https://www.subtraction.com/2015/05/07/the-state-of-design-tools/)” - L'auteur indique: 

> “Prototyping is the Wild West. Every team we met with uses a variety of prototyping tools, whether Pixate, Marvel, InVision, Flinto or others.”

![Catégories établies par Khoi Vinh dans son sondage](/cours-divers/img/categories-outils.png)

On peut distinguer différentes classes d'outil, répondant à ces modes de travail multiples, et dans une certaine mesure à différentes étapes du processus de création:

- Outils classiques de graphisme (*Photoshop, Illustrator, InDesign, Keynote, Powerpoint*...)
- Outils de wireframing: *UXPin, Balsamiq, Axure, Proto.io* ...
- Outils de design d'interface: *Sketch, Figma, Adobe XD* ...
- Outils de prototypage: *Just in Mind, Axure, Flinto, Origami* ...
- Outils d'animation: *After Effects, Principle, Framer* ...

#### Outils de Wireframing

*UXPin*, *Balsamiq*, *Axure*, *Proto.io* 

Ces outils servent à produire des "wireframes", càd des représentatons centrées sur la navigation et la répartition de blocs de contenus, sans interférer avec le design graphique. Il est possible de faire cela avec un outil de dessin vectoriel (p.ex. Illustrator), mais il existe des outils spécifiquement dédiés. Il est aussi courant de produire des wireframes sur papier, dans un carnet de notes...

#### Outils de prototypage

*Axure*, *Just in Mind*, *Flinto*...

À la différence des "wireframes", ces outils servent à produire des maquettes visuelles proches de l'expérience finale, l'écriture de code en moins. On distingue le prototype de la maquette (*mockup*, créé dans un outil comme Photoshop): le prototype vise à simuler non seulement le graphisme, mais aussi le *comportement* du produit final. Un outil de prototypage permettra de définir les *interactions* et les *transitions* entre les différents écrans du site (ou de l'application).

Certains outils proposent d'inclure tout cela dans une application.

Une autre approche consiste à créer les visuels dans un outil de design (Photoshop, Illustrator, Sketch...), puis de définir les interactions et construire un prototype avec des outils comme *InVision* ou *Marvel* (voir ci-dessous).

<h4>Outils de dessin vectoriel orientés design d'interfaces</h4>

*Sketch*, publié en 2010 par Bohemian Software, est une application de design d’interface très populaire actuellement. Sketch est développé uniquement pour Mac OSX, par une petite équipe de développement basée aux Pays-Bas. Bohemian Software propose également une application pour iOS, *Sketch Mirror*, visant à prévisualiser les créations sur iPhone ou iPad.

![Sketch avec prévisualistion iOS](/cours-outils/img/sketch-mirror.jpg)

La situation des outils de design d'interface est assez particulière: Adobe a stoppé en 2010 le développement de *Fireworks*, utilisé par de nombreux webdesigners pour la création de visuels. En 2011, Adobe lance la suite de logiciels *Edge* (*Edge Animate, Edge Inspect, Edge Reflow, Edge Code*), afin de mieux répondre aux besoins des webdesigners (lire à ce sujet [cet article de Aaron Shekey](https://www.aaronshekey.com/work/adobe/)). 

![Palmarès des outils de design d'interface, sondage effectué par Khoi Vinh en 2015](/cours-outils/img/interface-design-tools.png)

Le développement de la suite Adobe Edge est stoppé en 2015, certains développements étant intégrés dans *Dreamweaver* et *Muse*. En 2016, Adobe dévoile un nouveau logiciel: *Adobe Experience Design* (Adobe XD). C'est visiblement une tentative de contrer le succès de Sketch, et l'accueil des designers UX est [relativement](http://outsmartlabs.com/blog/sketch-v-s-adobe-xd/) [mitigé](http://scottjensen.design/2016/04/what-i-think-of-adobe-xd/).

![Interface de Adobe XD](/cours-outils/img/adobeXD.png)

#### Outils de présentation et communication

Ce nouveau type outils permet de construire une maquette interactive avec simulation de navigation, en combinant des images et en définissant des zones cliquables qui permettent de naviguer d'un écran à l'autre. Le travail de design se fait dans une autre application — le plus souvent *Photoshop*, *Illustrator* ou *Sketch*. Les fichiers graphiques sont synchronisés, afin de permettre un processus de travail fluide. Ces outils visent également à faciliter la collaboration et la discussion, via leurs fonctions de partage, de commentaires et annotations. 

**InVision** - InVision est une entreprise basée à New York. "Launched in 2011, the company has since raised around $80M in four fundraising rounds." En novembre 2014, InVision annonce [le support du format Sketch](http://blog.invisionapp.com/sketch-meet-rapid-hi-fi-prototyping/), et va même développer "Craft", une série d'extensions apportant de nouvelles fonctionalités à Sketch.

**Marvel** - Marvel est lancé en 2013. C'est une petite startup basée à Londres, comptant en 2016 une vingtaine d'employés. Construit initialement autour de DropBox, Marvel ajoute en 2015 le support des fichiers Sketch.

**Particularités:**

Ces deux applications permettent la synchronisation d'images (PNG ou JPEG) depuis DropBox (ou GoogleDrive).

Les deux applications proposent également un excellent support pour les fichiers **Sketch**:

- **Marvel** propose un plugin pour Sketch, qui permet de synchroniser des *artboards* depuis l'application.
- **InVision** peut synchroniser les fichiers Sketch depuis DropBox, et va créer un écran pour chaque *artboard*.

Tous deux proposent des **applications mobiles**:

- **InVision** propose une application iOS pour iPhone et iPad ([InVision Viewer](https://itunes.apple.com/ch/app/invision-viewer/id990700027?mt=8)), qui permet de naviguer dans les projets, et de les consulter hors-ligne.
- **Marvel** propose une [application iOS](https://itunes.apple.com/ch/app/marvel-design-apps-on-your/id765801658?mt=8) ainsi qu'une [application Android](https://play.google.com/store/apps/details?id=com.marvelapp&hl=en), qui permettent non seulement de visionner les projets (même hors-ligne) mais aussi de [créer et modifier des prototypes](https://blog.marvelapp.com/marvel-for-ios-the-prototyping-tool-for-the-mobile-generation/).

#### Autres approches du Prototypage:

Applications de prototypage utilisant un principe de "patches" (*node based design*):

- *[Origami](http://origami.design/)* - outil développé par Facebook, permet de visualiser sur iOS (avec une application, *Origami Live*).
- *[Avocado](https://github.com/ideo/avocado/)* - "an open source interaction design toolbox, built on top of Facebook's Origami framework". C'est un outil créé par la fameuse agence [IDEO](https://www.ideo.com/eu). Ne semble plus maintenu depuis 2015.

![Interface d'Origami Studio](/cours-outils/img/Origami-Interface.jpg)

Autre logiciel atypique: *[Framer](https://framer.com/)* - logiciel créé par [Koen Bok](http://koenbok.com/), fondateur de l'agence néerlandaise Sofa, acquise par Facebook en 2011.

D'autres logiciels apparus récemment, qui mettent l'accent sur l'animation, sont [Principle](http://principleformac.com/) (sorti en 2015) et [Kite Compositor](https://kiteapp.co/) (2017).

<h3>Un paysage en mouvement</h3>

La profession du design web étant en rapide évolution, le marché des outils de design et de prototypage est particulièrement instable. Les nouveaux outils sont souvent lancés en mode "startup", avec un financement initial modeste et un modèle économique incertain. Par conséquent, il n'est pas rare que ces entreprises disparaissent, en se faisant racheter par l'un des "géants": 

**Pixelapse** (2011)

- Permet de comparer visuellement des changements de design.
- Racheté par Dropbox.

**Form** 

- Outil de prototypage créé par une startup de 6 personnes, RelativeWave.
- Achat par Google en 2014.

**Pixate** (2012)

- Slogan: “the most powerful prototyping platform”
- [Campagne Kickstarter](https://www.kickstarter.com/projects/pixate/beautiful-native-mobile-apps/description) en 2012 qui a levé $61,274.
- Achat par Google en 2015. Annonce la fin du développement en 2016.
- En 2016, Google annonce une nouvelle application, *Stage*: "Stage is being brought to you by the teams behind Pixate and Form."

![Pixate](/cours-outils/img/pixate.png)

**Macaw** (2014)

- Slogan: “the code-savvy Web design tool”  
- Campagne [Kickstarter](https://www.kickstarter.com/projects/macaw/macaw-the-code-savvy-web-design-tool) en 2013 qui a levé $275,929.
- Achat par InVision en 2016, le développement s'achève.

![Aperçu de Macaw Scarlet, qui ne sera jamais publié...](/cours-outils/img/macaw-scarlet.png)

<h3>Le design selon Google...</h3>

Google a commencé à investir d'importantes ressources dans le domaine du design, avec notamment le système "Material Design" annoncé en 2014, la plateforme [Google Design](https://design.google.com/), les [conférences SPAN consacrées au design](https://design.google.com/events/span/), le site de référence [material.io](https://material.io/), et [l'annonce en 2016](https://design.google.com/articles/design-is-never-done/) d'une série d'outils: [Stage](https://material.io/stage/) ("define dynamic interfaces with interactive motion") et [Gallery](https://material.io/gallery/) ("design collaboration, simplified").

![Stage et Gallery, deux outils de design annoncés par Google en 2016](/cours-outils/img/google-design-tools-wide.jpg)