---
cover: ../.gitbook/assets/Shiki 01.png
coverY: 61.33919843597263
---

# Variables Regulares

Algunas variables que conseguirán regularmente son las siguientes, dejaremos una pequeña descripción de cada una:



* <mark style="color:blue;">**\[line 2]**</mark>

Representa un diálogo cortado a la fuerza, dicho de otra manera, alguien interrumpiendo a la fuerza a otra persona, en el parche aparecerá como un **Guion**:

{% hint style="success" %}
_**Persona 1**: Ella estaba aquí, la dejé justo en este lug<mark style="color:blue;">\[line 2]</mark>_

_**Persona 2**: ¡La dejaste sola!_
{% endhint %}



También se presenta en casos de que una persona quiera corregir lo que estaba a punto de decir:

{% hint style="success" %}
_Luego de este terremoto, tal vez deberí<mark style="color:blue;">\[line 2]</mark>pensándolo bien, ¿qué fue lo que ocasiono el terremoto?_
{% endhint %}



El **Traductor** tiene libertad en decidir donde <mark style="color:blue;">**cortar**</mark> la palabra, lo importante es respetar el diálogo en cuestión y nunca perder el contexto de la situación.

![](<../.gitbook/assets/Line2 (8).png>)

* <mark style="color:blue;">**\[f large]**</mark> / <mark style="color:blue;">**\[f small]**</mark>

Es una modificación al texto, dependiendo de la variable, hará que el texto después de ella sea grande o pequeño. Tiene otras versiones donde el diálogo es incluso más grandes de lo esperado.



Esta variable no puede recibir ninguna **Traducción** o signo detrás de ella:

{% hint style="danger" %}
_¡¡¡<mark style="color:blue;">\[f large]</mark>No escaparán de mí!!!_
{% endhint %}

{% hint style="success" %}
_<mark style="color:blue;">\[f large]</mark>¡¡¡No escaparán de mí!!!_
{% endhint %}

Dado que la intención de la variable es hacer grande o pequeño el diálogo después de ella, no tiene sentido que algo detrás de ella tenga un carácter neutro en ese sentido.



Por supuesto, dependerá de la clase de diálogo si se presenta o no:

{% hint style="info" %}
_Tal vez, pero si noso<mark style="color:blue;">\[line2]\[f large]</mark>¿¡Qué demonios!?_
{% endhint %}

![](<../.gitbook/assets/Line2 (8).png>)

* <mark style="color:blue;">**\[messageShake 0.01 3 3 0.2]**</mark>

Es una variable de movimiento, que hace "**temblar**" el diálogo, generalmente se usa cuando hay un grito.

Esta variable suele repetirse más de una vez en diálogos, pero absolutamente **TODAS** las que se repitan son especialmente diferente.

El código **numeral** dentro de la variable suele cambiar, y por tal razón, deben copiar cada una de las repetidas que salgan en el diálogo.



1. _Y<mark style="color:blue;">\[messageShake 0.02 3 3 0.4]</mark>ou will not escape from me! I s<mark style="color:blue;">\[messageShake 0.02 3 3 0.3]</mark>wear I'll find you! A<mark style="color:blue;">\[messageShake 0.02 3 3 0.6]</mark>nd I'll kill you in the most merciless way possible!_

{% hint style="danger" %}
_¡N<mark style="color:blue;">\[messageShake 0.02 3 3 0.4]</mark>o escaparás de mí! ¡J<mark style="color:blue;">\[messageShake 0.02 3 3 0.4]</mark>uro que te encontraré! ¡Y t<mark style="color:blue;">\[messageShake 0.02 3 3 0.4]</mark>e mataré de la forma más despiadada posible!_
{% endhint %}

{% hint style="success" %}
_¡N<mark style="color:blue;">\[messageShake 0.02 3 3 0.4]</mark>o escaparás de mí! ¡J<mark style="color:blue;">\[messageShake 0.02 3 3 0.3]</mark>uro que te encontraré! ¡Y t<mark style="color:blue;">\[messageShake 0.02 3 3 0.6]</mark>e mataré de la forma más despiadada posible!_
{% endhint %}

El primer ejemplo repitió la primera variable "_<mark style="color:blue;">\[messageShake 0.02 3 3 0.4]</mark>_" en las 3 ocasiones, por ende, está mal.



{% hint style="info" %}
Respecto a "_**¿dónde colocar esta variable?**_", tengan en cuenta que usualmente es colocada justo al inicio del diálogo o entre la **1ra** y **2da** letra de la palabra, tienen la libertad de colocarla como deseen cuando hagan la **Traducción**, respetando ese hecho.
{% endhint %}

![](<../.gitbook/assets/Line2 (8).png>)

* <mark style="color:blue;">**\[wt 0.4]**</mark>

Es una variable de ralentización o aceleración de diálogo. Básicamente, hará que vaya o más lento o más rápido.

Esta variable suele ir acompañada de otra más, puede ser una combinación con las antes mencionadas, pero no deben separarse de esta sin importar que:

{% hint style="danger" %}
_<mark style="color:blue;">\[wt 0.6] \[charaFace F 4]</mark>_
{% endhint %}

{% hint style="success" %}
_<mark style="color:blue;">\[wt 0.6]\[charaFace F 4]</mark>_
{% endhint %}



{% hint style="info" %}
Al igual que la anterior, tiene un **número** dentro de ella, así que deben copiarla tal cual y no alterar dicho **número**.
{% endhint %}

## Recordatorio



* **Modificar**, **alterar**, o **traducir** las variables está **Prohibido**.
* El uso de Signos de **Interrogación** y **Exclamación** antes o después de las variables debe ser consultado en caso de dudas.
* Existen una gran cantidad de variables en este <mark style="color:blue;">**Proyecto**</mark>, en caso de dudas, se debe consultar.



{% hint style="warning" %}
En caso de tener dudas con alguna variable, es obligatorio pedir ayuda en el <mark style="color:blue;">**Chat del Proyecto**</mark>, cuando un Líder esté disponible, responderá la duda.
{% endhint %}

{% hint style="danger" %}
<mark style="color:blue;">**Tagear**</mark> constantemente a los **Líderes** no se tolerará y se le hará un llamado de atención.
{% endhint %}

![](<../.gitbook/assets/Line2 (8).png>)

![](<../.gitbook/assets/Saito 02 (2).png>)
