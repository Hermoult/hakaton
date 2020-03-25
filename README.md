# hackaton1

Création d'un interface d'accueil d'un nouveau système de validation quadri-partie de transaction sur borne pour une banque national avec une page d'accueil contenant 4 liens permettant aux 4 protagonistes d'accéder a leur formulaire de transaction.

Les protagonistes: 
Mr Schylowski 
Mme Orlando
Mr Petrov
Mme Julien.

Infos bdd: 
identifiant_num       name       validation_key

1123454526         schylowski       bdmGh27*

1123456789           orlando         vcnH3*

1123456668           pietrov         dctQ3*

1123452537           julien          tntZ9*


Validation des transactions -> mène success.php
                               (quand transaction validé, la manoeuvre doit être sauvegardé dans un cookie et quand celui-ci possède 4 sauvegardes, index.php doit rediriger les utilisateurs vers succes.php)


Formulaires -> 3 champs: identifiant numérique (entier de 10 chiffres)
                         nom (chaîne de caractères)
                         mot de passe (chaîne de caractères)


Identification erronée -> controller redirige vers index-php avec un message d'erreur envoyé par GET : Votre mot de passe et/ou votre identifiant sont erronées. 

Identification fonctionne -> controller redirige vers index.php avec un message de succès envoyé par GET et sauvegarde la manipulation dans un cookie : Identification correcte. Transaction validée.

si les 4 ont validé la transaction dans $_COOKIE



Les critères:

- respect de l’expression des besoins clients
- indentation, commentaires du code
- Participation de chaque membre à l’élaboration du projet (code)
- Qualité des interfaces proposées (design et expérience utilisateur)
- Fonctionnement global du projet

