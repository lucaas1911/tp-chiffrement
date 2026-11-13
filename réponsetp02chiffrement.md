# tp-chiffrement

Ce problème de transmission pour éviter qu'un espion n'intercepte la clé sera résolu à la séance Diffie-Hellman.   


Partie 5 :
Quelle(s) propriété(s) DICP sont assurées ici ? La confidentialité.   
Qu'arrive-t-il si la clé est interceptée ? Un espion qui intercepte la clé pourrait lire le fichier, car c'est uniquement sans la bonne clé que la confidentialité est assurée et que le fichier reste illisible.   
Pourquoi utiliser un sel ? L'ajout d'un sel aléatoire fait en sorte que deux mots de passe identiques produisent des clés différentes.   
Pourquoi ne pas réutiliser la même clé + IV ? Permet de compliquer la tache à celui qui souhaite cracker le code 
