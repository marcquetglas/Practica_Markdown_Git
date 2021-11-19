## Controladors de versions: Git i GitHub

</br>

### Que és un controlador de versions??

</br>

Un controlador de versions és un sistema que registra els canvis realitzats en un fitxer o conjunt d'aquests en tot moment, de manera que sempre puguis recuperar una copia del teu fitxer en la versió que desitjis. Això suposa una avantatje increible a l'hora de rectificar errors o tornar a un punt del projecte anterior.

</br>
</br>

### Llavors, quin paper té git dins el món dels controladors de versions??

</br>

Git és un sistema distribuït. Això vol dir que està dissenyat perque tot un equip treballi a l'hora sobre un repositori. La diferencia es que Git el que fa és crear una còpia del repositori grupal de treball al entorn de treball local que serà sobre el que els usuaris facin canvis. Mitjançant Git, els usuaris podràn copiar la informació del seu repositori individual al grupal.

Com hem dit el repositori local el genera Git, llavors, on es troba el repositori remot grupal compartit? Es troba a Github, la versió de Git en línia i on podrem penjar i emplear tots els nostres repositoris

</br>
</br>

### Com podem treballar amb Git i Github??

</br>

Per poder treballar amb Git i Github necessitarem el següent:

- Instalar Git al nostre dispositiu. Això ens permetrà crear el nostre repositori local i enllaçarlo al GitHub.
- Crear un compte a GitHub. En aquest compte és on tendrem tots els nostres repositoris al nigul.
- (opcional) Instalar VScode. Un editor de codi que podem conectar a GitHub mitjançant Git i ens permetrà editar el nostre repositori local.

</br>

A continuació hem de connectar el nostre VScode amb Github mitjançant Git. Per configurar git hem de llançar un parell de comandes. Obrim una consola i llancem:

`git config --global user.name "<Nom d'usuari>"`

Amb aquesta comanda configurem el nóm d'usuari amb el que realitzarem els canvis a GitHub.

`git config --global user.email "<email>"`

Amb aquesta comanda podem establir el correu amb els que ens autenticarem. Aquest ha d'estar autenticat a la configuració del teu compte de GitHub

`git config --list`

Podem emplear aquesta comanda per veure la configuració actual.

En el cas de que la autentificació del teu repositori es faci per http, llançant aquestes comandes i aceptant un popup a github on et demana la contrasenya del teu compte, ja estaràs autenticat i podràs pujar i baixar informació lliurement.

En el cas de que l'autentificació es dugui a terme per ssh, hauràs de crear una clau pública i un altre privada i introduir la pública a l'apartat keys del teu compte de GitHub.

</br>

Una vegada tenguem tot preparat, podem començar a treballar. Hi ha dues opcions, o bé crear un repositori local i pujarlo al GitHub, o bé copiar un repositori de GitHub i clonar-lo en local per fer feina sobre ell.

</br>

### Com creem un repositori local per treballar sobre ell