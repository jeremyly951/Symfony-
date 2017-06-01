  **Liste des répertoires**


apps/  	Contient les différentes applications du projet
cache/ 	Contient tous les fichiers de cache
config/ 	Fichiers de configuration du projet
lib/ 	Répertoire où sont stockés les librairies, classes PHP, les modèles...
log/ 	Traces et debug du framework
plugins/ Plugins installés dans le projet
test/ 	Répertoire contenant les tests unitaires / fonctionnels
web/ 	Le répertoire web sur lequel pointe notre domaine.

---------

**Le répertoire /app**

    Le répertoire /app contient tout ce qui concerne votre site Internet ,sauf son code source. 
    Elle permet de faire la logique de votre site, du reste.
    Et ce reste c'est : la configuration, le cache, les fichiers logs, etc. Ce sont des fichiers 
    qui concernent l'entièreté de votre site, contrairement aux fichiers de code source qui seront 
    découpés par fonctionnalité de votre site. Dans Symfony2, un projet de site Internet est une application, 
    simple question de vocabulaire. Le répertoire /app est donc le raccourci pour « application ».
---------

**Le répertoire /src**

    Le répertoire /src permet de mettre son code source. Nous organiserons notre code en bundles, 
    des briques de notre application.

----------
**Le répertoire /vendor**

    Ce répertoire contient toutes les bibliothèques externes à notre application. Dans ces bibliothèques externes, 
    Une bibliothèque est une sorte de boîte noire qui remplit une fonction bien précise, et dont on peut se servir
    dans notre code. Par exemple, la bibliothèque SwiftMailer permet d'envoyer des e-mails. On ne sait pas comment elle
    fonctionne (principe de la boîte noire), mais on sait comment s'en servir : on pourra donc envoyer des e-mails très facilement,
    juste en apprenant rapidement à utiliser la bibliothèque.
----------

**Le répertoire /web**

    Ce répertoire contient tous les fichiers destinés à vos visiteurs : images, fichiers CSS et JavaScript, etc.
    Il contient également le contrôleur frontal (app.php).
    En fait, c'est le seul répertoire qui devrait être accessible à vos visiteurs. Les autres répertoires ne sont 
    pas censés être accessibles (ce sont vos fichiers de code source, ils vous regardent vous, pas vos visiteurs), 
    c'est pourquoi vous y trouverez des fichiers .htaccess interdisant l'accès depuis l'extérieur. On utilisera donc
    toujours des URL du type http://localhost/Symfony/web/… au lieu de simplement http://localhost/Symfony/… .
    Nous pouvons configurer notre Apache pour que l'URL http://localhost/Symfony pointe directement sur 
    le répertoire /web..
    
--------
**À retenir**

Retenez donc que nous passerons la plupart de notre temps dans le répertoire /src, à travailler sur nos bundles.
On touchera également pas mal au répertoire /app pour configurer notre application. Et lorsque nous installerons 
des bundles téléchargés, nous le ferons dans le répertoire /vendor.
