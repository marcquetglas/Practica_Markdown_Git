## ***Guia Introductoria al Markdown***

</br>
</br>

### En aquesta guia veuràs una guia bàsica introductoria per poder crear documents en Markdown

</br>

**Per començar, per insertar títols de distints tamanys empleem (#), quantes més possis davant un text, més petit serà **:

# Hola Món

## Hola Món

### Hola Món

#### Hola Món

##### Hola Món

</br>
</br>

### Markdown també ens dona la possibilitat de ficar un text seguit de (=) i (-) per crear els títols:

</br>

Hola Món
=
Hola Món
-

</br>
</br>

### Com a editor de text, podem modificar el tipus de lletra molt fàcilment. Els tipus de lletra que podem emplear són:

</br>

En Markdown per fer una cursiva escrivim el text entre (*)

*cursiva* 

Per fer text en negreta l'escrivim entre(**)

**negreta**

Per fer text en negreta i cursiva l'escrivim entre (***)

***Text en cursiva i negreta***

Si volem escriure un text ratllat l'escrivim entre (~~)

~~Aquest text esta ratllat~~

</br>
</br>

### Per crear text en format de cita, hem d'emplear (>) abans del text per fer sangria

</br>

>Aquest fragment és una ***cita***

> // com també comença amb (>) continua 

>Aquesta és un altre ***cita***

Com no comença amb (>) xapem la cita

</br>
</br>

### Per crear una llista podem emplear tant el signe més (+), guions (-) com asteriscs (*) (el resultat serà el mateix)

</br>

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

</br>
</br>

### Per introduir una línia de codi la possem entre (``), si el text té qualcún caracter amb aquest accent, en podem possar dos per ignorar-lo:

</br>

`Això és codi`

``tot això és `codi` ``

Si volem introduir un bloc sencer de codi, podem possar tres accents en començar i acabar (```)

```
Aquí comença el codi.
    Aquí segueix el codi pero més tabulat.
Aquí segueix el codi.
```

Inclús podem indicar el llenguatge que empleem al principi i Markdown aplicarà els colors predefints d'aquest

```js
Aquí comença el codi.
    Aquí segueix el codi pero més tabulat.
Aquí segueix el codi.
```

</br>
</br>

### Com podem crear hipervincles o imatges enllaçades a aquestos? Anem-ho a veure:

</br>

Per introduir un link empleem el format `[Nom](https://exemple.com/)`. En aquest cas em anat a twitch.tv


[Twitch](https://www.twitch.tv/  "link a twitch" )


Si vols que es vegi la direcció, pots introduir l'URL directament entre (<>)


<https://www.twitch.tv/>


També podem afegir imatges mitjançant el format:  

**(![Descripció](URL imatge))**


![Descripció](https://estaticos.muyinteresante.es/media/cache/1140x_thumb/uploads/images/gallery/5d9208eb5cafe81a0f3c986a/delfin0_0.jpg)  


Inclús podem combinar imatges amb hipérvincles de manera que clickant damunt la imatge ens dugui al vincle indicat empleant el format:  

**[![Descripció](URL imatge)](URL web)**


[![Descripció](https://estaticos.muyinteresante.es/media/cache/1140x_thumb/uploads/images/gallery/5d9208eb5cafe81a0f3c986a/delfin0_0.jpg)](https://www.salvemosalosdelfines.org/)


</br>
</br>






