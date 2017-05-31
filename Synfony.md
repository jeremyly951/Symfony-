# Qu'est-ce qu'un framework ?

  **L'objectif d'un framework**
  
L'objectif de ce chapitre n'est pas de vous fournir toutes les clés pour concevoir un framework, 
mais suffisamment pour pouvoir en utiliser un. On exposera rapidement l'intérêt, les avantages et 
les inconvénients de l'utilisation d'un tel outil.

  **Définition**
  
Le mot « framework » provient de l'anglais « frame » qui veut dire « cadre » en français, et « work » 
qui signifie « travail ». Littéralement, c'est donc un « cadre de travail ». Vous voilà bien avancés, 
hein ?  Concrètement, c'est un ensemble de composants qui sert à créer les fondations, l'architecture et 
les grandes lignes d'un logiciel. Il existe des centaines de frameworks couvrant la plupart des langages 
de programmation. Ils sont destinés au développement de sites web ou bien à la conception de logiciels.

Un framework est une boîte à outils conçue par un ou plusieurs développeurs à destination d'autres développeurs. 
Contrairement à certains scripts tels que WordPress, Dotclear ou autres, un framework n'est pas utilisable tel quel. 
Il n'est pas fait pour être utilisé par les utilisateurs finaux. Le développeur qui se sert d'un framework a encore 
du boulot à fournir, d'où ce cours !

**Objectif d'un framework**

L'objectif premier d'un framework est d'améliorer la productivité des développeurs qui l'utilisent. 
Plutôt sympa, non ? Souvent organisé en différents composants, un framework offre la possibilité au 
développeur final d'utiliser tel ou tel composant pour lui faciliter le développement, et lui permet 
ainsi de se concentrer sur le plus important.

Prenons un exemple concret. Il existe dans Symfony2 un composant qui gère les formulaires HTML : 
leur affichage, leur validation, etc. Le développeur qui l'utilise se concentre sur l'essentiel dans son application : 
chaque formulaire effectue une action, et c'est cette action qui est importante, pas les formulaires. 
Étendez ce principe à toute une application ou tout un site Internet, et vous comprenez l'intérêt d'un framework ! 
Autrement dit, le framework s'occupe de la forme et permet au développeur de se concentrer sur le fond.

Pesons le pour et le contre
Comme tout bon développeur, lorsqu'on veut utiliser un nouvel outil, on doit en peser le pour et le contre pour 
être sûr de faire le bon choix !

**Les pour**

L'avantage premier est donc, on vient de le voir, le gain en productivité. Mais il en existe bien d'autres !
On peut les classer en plusieurs catégories : le code, le travail et la communauté.
Tout d'abord, un framework va vous aider à réaliser un « bon code ». Par « bon code », j'entends qu'il vous incite,
de par sa propre architecture, à bien organiser votre code. Et un code bien organisé est un code facilement maintenable et évolutif
! De plus, un framework offre des briques prêtes à être utilisées (le composant Formulaire de Symfony2 par exemple), ce qui vous
évite de réinventer la roue, et surtout qui vous permet d'utiliser des briques puissantes et éprouvées. En effet, ces briques sont 
développées par des équipes de développeurs chevronnés, elles sont donc très flexibles et très robustes. Vous économisez ainsi des
heures de développement !
Ensuite, un framework améliore la façon dont vous travaillez. En effet, dans le cas d'un site Internet, vous travaillez
souvent avec d'autres développeurs PHP et un designer. Un framework vous aide doublement dans ce travail en équipe. D'une 
part, un framework utilise presque toujours l'architecture MVC ; on en reparlera, mais sachez pour le moment que c'est une
façon d'organiser son code qui sépare le code PHP du code HTML. Ainsi, votre designer peut travailler sur des fichiers 
différents des vôtres, fini les problèmes d'édition simultanée d'un même fichier ! D'autre part, un framework a une structure
et des conventions de code connues. Ainsi, vous pouvez facilement recruter un autre développeur : s'il connaît déjà le framework en 
question, il s'intégrera très rapidement au projet.
Enfin, le dernier avantage est la communauté soutenant chaque framework. C'est elle qui fournit les tutoriaux ou les cours 
(comme celui que vous lisez !), de l'aide sur les forums, et bien sûr les mises à jour du framework. Ces mises à jour sont
très importantes : imaginez que vous codiez vous-mêmes tout ce qui est connexion utilisateur, session, moteur de templates, etc.
Comme il est impossible de coder sans bugs, vous devriez logiquement corriger chaque bug déclaré sur votre code. Maintenant,
imaginez que toutes les briques de votre site, qui ne sont pas forcément votre tasse de thé, soient fournies par le framework.
À chaque fois que vous ou les milliers d'autres utilisateurs du framework trouverez un bug, les développeurs et la communauté s'
occuperont de le corriger, et vous n'aurez plus qu'à suivre les mises à jour. Un vrai paradis !


Il existe plein d'autres avantages que je ne vais pas vous détailler, mais un framework, c'est aussi :

* une communauté active qui utilise le framework et qui contribue en retour ;

* une documentation de qualité et régulièrement mise à jour ;

* un code source maintenu par des développeurs attitrés ;

* un code qui respecte les standards de programmation ;

* un support à long terme garanti et des mises à jour qui ne cassent pas la compatibilité ;

* etc.


**Les contre**

Vous vous en doutez, avec autant d'avantages il y a forcément des inconvénients. Et bien, figurez-vous qu'il n'y en a pas tant que ça !
S'il ne fallait en citer qu'un, cela serait évidemment la courbe d'apprentissage qui est plus élevée. En effet, pour
maîtriser un framework, il faut un temps d'apprentissage non négligeable. Chaque brique qui compose un framework a sa 
complexité propre qu'il vous faudra appréhender.
Notez également que pour les frameworks les plus récents, tels que Symfony2 justement, il faut également être 
au courant des dernières nouveautés de PHP. Je pense notamment à la programmation orientée objet (par Mathieu Nebra) 
et aux namespaces (par Victor Thuillier). De plus, connaître certaines bonnes pratiques telles que l'architecture MVC est un plus.
Mais rien de tout cela ne doit vous effrayer ! Voyez l'apprentissage d'un framework comme un investissement : il y a
un certain effort à fournir au début, mais les résultats se récoltent ensuite sur le long terme !
