##PHP

![alt tag](http://scr.sad.supinfo.com/articles/resources/203968/2651/0.png)

##L'utilisation du PHP :

PHP est principalement conçu pour servir de langage de script coté serveur, ce qui fait qu'il est capable de réaliser tout ce qu'un script <strong>CGI*1</strong> quelconque peut faire, comme collecter des données de formulaire, générer du contenu dynamique, ou gérer des cookies. Mais PHP peut en faire bien plus.

<strong>*1 Script CGI :

Un script CGI (Common Gateway Interface, traduisez interface de passerelle commune) est un programme exécuté par le serveur web (on dit généralement « côté serveur »), permettant d'envoyer au navigateur de l'internaute un code HTML créé automatiquement par le serveur (basé par exemple sur une autre application, telle qu'un système de gestion de base de données, d'où le nom de passerelle).</strong>

<h3>Il y a trois domaines différents où PHP peut s'illustrer :</h3>

- Langage de script coté serveur. C'est l'utilisation la plus traditionnelle, et aussi le principal objet de PHP. Vous aurez besoin de trois composants pour l'exploiter : un analyseur PHP (CGI ou module serveur), un serveur web et un navigateur web.  Vous devez exécuter le serveur web en corrélation avec PHP. Vous pouvez accéder au programme PHP avec l'aide du navigateur web. Tout ceci peut fonctionner sur votre propre machine si vous êtes juste expérimenté dans la programmation en PHP.

- Langage de programmation en ligne de commande. Vous pouvez écrire des scripts PHP et l'exécuter en ligne de commande, sans l'aide du serveur web et d'un navigateur. Il vous suffit de disposer de l'exécutable PHP. Cette utilisation est idéale pour les scripts qui sont exécutés régulièrement (avec un <strong>cron*2</strong> sous Unix ou Linux), ou un gestionnaire de tâches (sous Windows). Ces scripts peuvent aussi être utilisés pour réaliser des opérations sur des fichiers texte.

<strong>*2 cron :

cron est un programme qui permet aux utilisateurs des systèmes Unix d’exécuter automatiquement des scripts, des commandes ou des logiciels à une date et une heure spécifiées à l’avance, ou selon un cycle défini à l’avance. (Signifie : Table de planification)</strong>

- Ecrire des applications clientes graphiques. PHP n'est probablement pas le meilleur langage pour écrire des applications clientes graphiques, mais si vous connaissez bien PHP et que vous souhaitez exploiter des fonctionnalités avancées dans vos applications clientes, vous pouvez utiliser <strong>PHP-GTK*3</strong> pour écrire de tels programmes. Vous avez aussi la possibilité d'écrire des applications très portables avec ce langage. PHP-GTK est une extension de PHP, qui n'est pas fournie dans la distribution de base.

<strong>*3 PJP-GTK :

PHP-GTK est une extension libre de PHP qui utilise la bibliothèque <strong>GTK+*4</strong> pour créer des applications graphiques.</strong>

<strong>*4 GTK+ :

GTK+ (The GIMP Toolkit) est un ensemble de bibliothèques logicielles, c'est-à-dire un ensemble de fonctions permettant de réaliser des interfaces graphiques. Cette bibliothèque a été développée originellement pour les besoins du logiciel de traitement d'images GIMP.</strong>

Avec PHP vous avez le choix de votre système d'exploitation et de votre serveur web. De plus, vous avez aussi le choix d'utiliser la programmation procédurale ou objet <strong>(OOP)*5</strong>, ou encore un mélange des deux.

<strong>*5 OOP :

La programmation orientée objet (POO), ou programmation par objet.</strong>

Avec PHP, vous n'êtes pas limité à la production de code HTML. Les capacités de PHP lui permettent de générer aussi bien des images, des fichiers PDF, des animations Flash (avec l'aide des bibliothèques libswf et Ming) à la volée. Vous pouvez aussi générer facilement du texte, du code XML ou XHTML. PHP génère tous ces fichiers et les sauve dans le système de fichiers, ou bien les envoie directement au navigateur web.

Une des forces les plus significatives de PHP est qu'il supporte énormément de bases de données. Écrire une page web faisant appel à une base de données devient terriblement simple, en utilisant une des extensions spécifiques aux bases de données (i.e., pour mysql), ou utilisant une classe d'abstraction comme PDO, ou une connexion à n'importe quelle base de données supportant la connexion standard ouvert via l'extension ODBC. Les autres bases de données peuvent utiliser l'extension cURL ou sockets comme CouchDB.

