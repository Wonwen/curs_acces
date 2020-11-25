# curs_acces
Exercici a realitzar:
1. Crea el teu primer repositori Git (línia de comandes):
a. Crea un nou repositori al teu GitHub.
b. Crea una nova carpeta al teu PC. (copia_proyecto_git).
c. Clona el repositori a aquesta carpeta del teu ordinador (git clone “url/to/repository”).
Exemple: git clone https://github.com/it-academyproject/Project.git
d. Crea un fitxer de text (.txt) en aquesta carpeta.
e. Afegeix el fitxer a un commit (git add nom_fitxer.txt)
Exemple: git add fitxer.txt
f. Fés un commit i push per a pujar els canvis al repositori remot de GitHub.
2. Treballar amb branques:
a. Crea una branca anomenada “branch1”
b. Modifica el text del fitxer des d’aquesta branca
c. Afegeix canvis “add” i realitza l’acció “Commit” i “Push” dels canvis. En aquest moment hauries de
veure dues branques al GitHub.
d. Torna a la branca “master”
e. Efectua qualsevol altre canvi al document i tot seguir realitzar l’acció “add” “commit” i “push”
f. Des d’aquesta fés “merge” dels canvis de la “branch1” a la teva branca “master”
3. Conflictes!
Com era d’esperar, el Git t’adverteix que hi ha canvis a les dues branques.
En aquest cas tenim 3 opcions:
a. Mine: selecciona que els canvis de la branca actual, “master” es la versió bona.
b. Their: selecciona que els canvis de l’altra branca “branch1” són els bons.
c. Resoldre el conflicte: Si accedeixes al fitxer veuràs que git ha afegit 3 línies de codi, esborra-les
i deixa les dues línies (una per cada branca).
Per a l’exercici has d’utilitzar l’opció c.
4. Un cop resolt el conflicte, s’ha de fer “add”, “commit” i “push” a la branca master.
Si tot ha anat correctament, hauries de visualitzar un flux com aquest, més o menys:
*Per veure aquest g
