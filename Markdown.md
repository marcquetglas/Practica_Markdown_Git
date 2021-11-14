En aquest document veurem una guia bàsica per aprendre a fer Markdown

Per començar, per ficar títols de distints tamanys podem emplear (#), quantes més possis davant un text, més petit serà (fins un límit de 5):

# Hola Món

## Hola Món

### Hola Món

#### Hola Món

##### Hola Món

També podem ficar un text seguit de (=) i (-) 

Hola Món
=
Hola Món
-

Els tipus de lletra que podem emplear són:

En Markdown per fer una cursiva escrivim el text entre (*)

*cursiva* 

Per fer text en negreta l'escrivim entre(**)

**negreta**

Per fer text en negreta i cursiva l'escrivim entre (***)

***Text en cursiva i negreta***

Si volem escriure un text ratllat l'escrivim entre (~~)

~~Aquest text esta ratllat~~

Per ficar text en format de cita, podem emplear (>) abans del text per fer sangria

>Aquest fragment és una ***cita***

> // com també comença amb (>) continua 

>Aquesta és un altre ***cita***

Com no comença amb (>) xapem la cita

Per crear una llista podem emplear tant el signe més (+), guions (-) com asteriscs (*) (el resultat serà el mateix)

+ Element 
+ Element 2
+ Element 3

Si volem que estigui ordenada simplement hem de possar un número seguit d'un punt (x.)

1. Element 
2. Element 2
3. Element 3

També podem crear llistes amb caselles marcables mitjançant ([ ] text). Si entre [] possem una "X" marcarà la casella

+ [x] A
+ [ ] B
+ [x] C

Per marcar que una línia és codi la possem entre (``), si el text té qualcún caracter amb aquest accent, en podem possar dos per ignorar-lo

`Això és codi`

``tot això és `codi` ``

Si volem introduir un bloc sencer de codi, podem possar tres accents en començar i acabar (```)

```
Aquí comença el codi.
    Aquí segueix el codi pero més tabulat.
Aquí segueix el codi.
```
```js
Aquí comença el codi.
    Aquí segueix el codi pero més tabulat.
Aquí segueix el codi.
```




