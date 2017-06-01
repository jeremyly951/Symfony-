
# Installation Symfony 


require https://getcomposer.org/download/

https://symfony.com/doc/current/setup.html

**1)Insérer le chemin sur PATH** 

* Clique droit sur "CePC"

* ensuite Propriété , 

* Paramètre Système Avancès ,

* Variables d'environnement ,

* Modifier PATH

* Ajouter "C:\wamp64\bin\php\php7.0.10\php.exe"

**2)Installer symfony**

Pour MacOS or linux 

    sudo mkdir -p /usr/local/bin
   
    sudo curl -LsS https://symfony.com/installer -o /usr/local/bin/symfony
   
    sudo chmod a+x /usr/local/bin/symfony

Pour windows

    php -r "readfile('https://symfony.com/installer');" > symfony

**3)Creation d'un projet symfony**
    
    symfony new nomduprojet


**Erreur rencontrer ( certificat )** 

* Creer un fichier cacert.pem dans le dossier wamp
* copier le code dans le fichier https://curl.haxx.se/ca/cacert.pem
* Mettre le code dans le fichier cacert.pem
* Modifier le fichier php.init dans C://wamp64/bin/php/php7.0.10 (openssl.cafile=C:/wamp64/cacert.pem) vers la fin du code 
* Fermer Wamp


https://www.youtube.com/watch?v=VxQndsw2re4
