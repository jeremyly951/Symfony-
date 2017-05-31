**ArchitectureMVC**

MVC signifie « Modèle / Vue / Contrôleur ». C'est un découpage très répandu pour développer les sites Internet, 
car il sépare les couches selon leur logique propre :
_________________________

**Le Contrôleur (ou Controller) :** 

    Son rôle est de générer la réponse à la requête HTTP demandée par notre visiteur.
    Il est la couche qui se charge d'analyser et de traiter la requête de l'utilisateur. Le contrôleur contient la logique
    de notre site Internet et va se contenter « d'utiliser » les autres composants : les modèles et les vues. Concrètement, 
    un contrôleur va récupérer, par exemple, les informations sur l'utilisateur courant, vérifier qu'il a le droit de modifier 
    tel article, récupérer cet article et demander la page du formulaire d'édition de l'article.


**Le Modèle (ou Model) :**

    Son rôle est de gérer vos données et votre contenu. 
    Lorsque je dis « le contrôleur récupère l'article », il va en fait faire appel au modèle Article et lui dire :
    « donne-moi l'article portant l'id 5 ». C'est le modèle qui sait comment récupérer cet article, généralement via une requête 
    au serveur SQL, mais ce pourrait être depuis un fichier texte ou ce que vous voulez. Au final, il permet au contrôleur de manipuler 
    les articles, mais sans savoir comment les articles sont stockés, gérés, etc. C'est une couche d'abstraction.


**La Vue (ou View) :**

    Son rôle est d'afficher les pages. Ce n'est pas le contrôleur qui affiche le formulaire, 
    il ne fait qu'appeler la bonne vue. Si nous avons une vue Formulaire,
    les balises HTML du formulaire d'édition de l'article y seront et au final le contrôleur ne fera qu'afficher cette vue sans savoir 
    vraiment ce qu'il y a dedans. En pratique, c'est le designer d'un projet qui travaille sur les vues. Séparer vues et contrôleurs
    permet aux designers et développeurs PHP de travailler ensemble sans se marcher dessus.


Au final, si vous avez bien compris, le contrôleur ne contient que du code très simple,
car il se contente d'utiliser des modèles et des vues en leur attribuant des tâches précises. 
Il agit un peu comme un chef d'orchestre, qui n'agite qu'une baguette alors que ses musiciens jouent des instruments complexes.

__________________
