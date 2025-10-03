 
 explication de mes commande utilise 
 
 
mkdir -p projet_scolaire/maths projet_scolaire/sciences : je l’utilise pour créer en une seule commande l’arborescence avec deux dossiers maths et sciences dans projet_scolaire.

echo "x^2 + y^2 = z^2" > projet_scolaire/maths/equations.txt : je l’utilise pour créer un fichier equations.txt dans maths et y écrire la formule x^2 + y^2 = z^2.

echo "eau + huile = séparation" > projet_scolaire/sciences/experiences.txt : je l’utilise pour créer un fichier experiences.txt dans sciences et y écrire eau + huile = séparation.

mv projet_scolaire/maths/equations.txt projet_scolaire/maths/geometrie.txt : je l’utilise pour renommer le fichier equations.txt en geometrie.txt.

mv projet_scolaire/sciences/experiences.txt projet_scolaire/maths/ : je l’utilise pour déplacer le fichier experiences.txt dans le dossier maths.

rmdir projet_scolaire/sciences : je l’utilise pour supprimer le dossier sciences car il est maintenant vide.
