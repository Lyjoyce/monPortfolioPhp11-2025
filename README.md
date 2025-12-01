lancer un serveur PHP intégré

Ouvre un terminal dans ton dossier du projet :

Dans VS Code → Terminal > Nouveau terminal
Puis va dans ton dossier, par exemple :

cd C:\Users\lahel\Documents\mon-projet-php


Ensuite lance :

php -S localhost:8000


Puis ouvre ton navigateur sur :

👉 http://localhost:8000

Ton code :

<h1>CC <?php echo 'toto'; ?></h1>


Va afficher :

CC toto
✅ Solution alternative : utiliser l’extension “PHP Server” (clic droit)

Puisque tu l’as installée, fais ça :

➤ Dans VS Code :

Clic droit sur ton fichier index.php

➡️ “PHP Server: Serve project”
ou
➡️ “PHP Server: Serve file”

L’extension va lancer un serveur et ouvrir une URL du style :

👉 http://localhost:3000/index.php

Cette URL exécutera bien le PHP.