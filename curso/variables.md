---
description: La base de las traducciones.
cover: ../.gitbook/assets/Arthur 02.png
coverY: 0
---

# Variables

Son comandos especiales en las hojas, unas más difíciles que otras, pero lo importante es que ninguna de estas debe ser alterada.



Todas las Variables son "invisibles" en la **Traducción del Parche**, por ende se debe cuidar como se colocan junto a los diálogos, de lo contrario podría dificultar la lectura de los mismos.



Existen variables de todo tipo, desde cambiar el color de un diálogo hasta hacer el texto más grande, por tal razón, los **Traductores** tienen prohibido:

* Modificarlas.
* Traducirlas.
* Ignorarlas.
* Colocarlas en los lugares equivocados.
* Escribirlas manualmente.

{% hint style="info" %}
Su única responsabilidad es copiarla y pegarla tal cual aparezca en el diálogo de NA.
{% endhint %}



**Ejemplo:**

* _<mark style="color:blue;">\[f large]</mark>...<mark style="color:blue;">\[messageShake 0.05 5 5 0.5]</mark>The hell is this!?_

{% hint style="success" %}
_<mark style="color:blue;">\[f large]</mark>...<mark style="color:blue;">\[messageShake 0.05 5 5 0.5]</mark>¿¡Qué demonios es esto!?_
{% endhint %}



Tal como ven, el diálogo inicia después de la variable "_<mark style="color:blue;">\[messageShake 0.05 5 5 0.5]</mark>_"**.**&#x20;



![](../.gitbook/assets/imagen\_2022-05-30\_185949847.png)

Lo más importante, como traductores, es respetar los (**espacios**, **puntos**, **comas** y **signos**) que aparezcan junto a la **Variable**. De igual forma, no pueden añadir ningún **signo** o **punto** antes o después de la Variable si no aparece en la versión NA.



**Ejemplo** (_extracto de <mark style="color:blue;">Oniland</mark>_):



* _It's time you found out what we managers<mark style="color:blue;">\[line 2]</mark>no, we Gold Servants<mark style="color:blue;">\[line 2]</mark>can really do!_

{% hint style="danger" %}
_Es hora de que descubran lo que los mánagers <mark style="color:blue;">\[line 2]</mark> no, los Gold Servants <mark style="color:blue;">\[line 2]</mark> ¡podemos hacer de verdad!_
{% endhint %}

{% hint style="success" %}
_Es hora de que descubran lo que los mánagers<mark style="color:blue;">\[line 2]</mark>no, los Gold Servants<mark style="color:blue;">\[line 2]</mark>¡podemos hacer de verdad!_
{% endhint %}



Aunque ambos diálogos están bien traducidos, el primer diálogo separo la variable "_<mark style="color:blue;">\[line 2]</mark>_" de los demás diálogos, eso se considera una falta a las Pautas, la forma correcta de dicho diálogo es la segunda, respetando el cómo la variable "_<mark style="color:blue;">\[line 2]</mark>_" se encuentra pegada a los diálogos.



![](../.gitbook/assets/imagen\_2022-05-30\_185949847.png)

Por supuesto, en la práctica, lo que encontraran en las hojas puede ser muy diferente, puede haber **comas**, **puntos** o signos de **exclamación** o **interrogación**.



**Más Ejemplos:**



* _<mark style="color:blue;">\[f large]</mark>Fresh! <mark style="color:blue;">\[wt 0.4]\[messageShake 0.01 3 3 0.2]</mark>Meat!_

{% hint style="danger" %}
_<mark style="color:blue;">\[f large]</mark>¡Carne!<mark style="color:blue;">\[wt 0.4]\[messageShake 0.01 3 3 0.2]</mark>¡Fresca!_
{% endhint %}

{% hint style="success" %}
_<mark style="color:blue;">\[f large]</mark>¡Carne! <mark style="color:blue;">\[wt 0.4]\[messageShake 0.01 3 3 0.2]</mark>¡Fresca!_
{% endhint %}

![](../.gitbook/assets/imagen\_2022-05-30\_185949847.png)

* _<mark style="color:blue;">\[line 3]</mark>. <mark style="color:blue;">\[line 6]</mark>. <mark style="color:blue;">\[line 3]</mark>Cha<mark style="color:blue;">\[line 3]</mark>dea.<mark style="color:blue;">\[wt 0.5]\[seVolume ad31 1.0 0.3]</mark>_

{% hint style="danger" %}
_<mark style="color:blue;">\[line 3]</mark> . <mark style="color:blue;">\[line 6]</mark> . <mark style="color:blue;">\[line 3]</mark> Cha<mark style="color:blue;">\[line 3]</mark> dea. <mark style="color:blue;">\[wt 0.5]\[seVolume ad31 1.0 0.3]</mark>._
{% endhint %}

{% hint style="success" %}
_<mark style="color:blue;">\[line 3]</mark>. <mark style="color:blue;">\[line 6]</mark>. <mark style="color:blue;">\[line 3]</mark>Cha<mark style="color:blue;">\[line 3]</mark>dea.<mark style="color:blue;">\[wt 0.5]\[seVolume ad31 1.0 0.3]</mark>_
{% endhint %}

![](../.gitbook/assets/imagen\_2022-05-30\_185949847.png)

* _One... Two... <mark style="color:blue;">\[wt 0.4]</mark>T<mark style="color:blue;">\[messageShake 0.02 3 3 0.3]</mark>hree!_

{% hint style="danger" %}
_Uno... Dos... ¡<mark style="color:blue;">\[wt 0.4]</mark>T <mark style="color:blue;">\[messageShake 0.02 3 3 0.3]</mark> res!_
{% endhint %}

{% hint style="success" %}
_Uno... Dos... <mark style="color:blue;">\[wt 0.4]</mark>¡T<mark style="color:blue;">\[messageShake 0.02 3 3 0.3]</mark>res!_
{% endhint %}

![](../.gitbook/assets/imagen\_2022-05-30\_185949847.png)

* _<mark style="color:blue;">\[f large]</mark>A<mark style="color:blue;">\[messageShake 0.05 3 3 0.4]</mark>ll of you, move out!_

{% hint style="danger" %}
_¡<mark style="color:blue;">\[f large]</mark> To<mark style="color:blue;">\[messageShake 0.05 3 3 0.4]</mark> dos ustedes, muévanse!_
{% endhint %}

{% hint style="success" %}
_<mark style="color:blue;">\[f large]</mark>¡To<mark style="color:blue;">\[messageShake 0.05 3 3 0.4]</mark>dos ustedes, muévanse!_
{% endhint %}

![](../.gitbook/assets/imagen\_2022-05-30\_185949847.png)

{% hint style="warning" %}
En caso de tener dudas con alguna variable, es obligatorio pedir ayuda en el <mark style="color:blue;">**Chat del Proyecto**</mark>, cuando un Líder esté disponible, responderá la duda.
{% endhint %}

{% hint style="danger" %}
<mark style="color:blue;">**Tagear**</mark> constantemente a los **Líderes** no se tolerará y se le hará un llamado de atención.
{% endhint %}

## Nota Adicional



El uso del signo de <mark style="color:blue;">**%**</mark> en las **Traducciones** está totalmente **Prohibido**.



No pueden escribir ningún diálogo numeral que contenga el signo de <mark style="color:blue;">**%**</mark>. El **Parche** trabaja con innumerables signos, uno de ellos es el <mark style="color:blue;">**%**</mark> y es de los más importantes dado que el **Parche** mismo lo detecta como **Variable**.



**Ejemplos:**

{% hint style="danger" %}
_50_<mark style="color:blue;">**%**</mark>.
{% endhint %}

{% hint style="success" %}
_Cincuenta <mark style="color:blue;">porciento</mark>._
{% endhint %}

![](../.gitbook/assets/imagen\_2022-05-30\_185949847.png)

{% hint style="danger" %}
_¡El rendimiento del Ortinax es del 90<mark style="color:blue;">%</mark>! ¡Mash Kyrielight, lista para el combate!_
{% endhint %}

{% hint style="success" %}
_¡El rendimiento del Ortinax es del noventa <mark style="color:blue;">porciento</mark>! ¡Mash Kyrielight, lista para el combate!_
{% endhint %}





{% hint style="info" %}
_El uso de números para fechas o épocas está bien, pero el signo de <mark style="color:blue;">**%**</mark> no debe ser utilizado. En caso de hallarlo en una traducción durante la_ corrección_, se le hará un recordatorio al **Traductor**._
{% endhint %}

![](../.gitbook/assets/imagen\_2022-05-30\_185949847.png)

![](<../.gitbook/assets/Jalter 05.png>)
