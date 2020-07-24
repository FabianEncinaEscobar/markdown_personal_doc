# Markdown

## Índice

**Índice**
1. [Primer apartado](#id1)
2. [Segundo apartado](#id2)
## Primer apartado<a name="id1"></a>
Texto del primer apartado
## Segundo apartado<a name="id2"></a>
Texto del segundo apartado


## Elementos de bloque

### Títulos
#### Títulos
##### Títulos

### Listas ordenadas
1. fila 1
    1. n1
    2. n2
2. fila 2
    1. t1
3. fila 3
4. fila 4

### Listas desordenadas
- fila 1
    - n1
    - n2
- fila 2
    - t1
- fila 3
- fila 4

### Listas checklist
**Listado de tareas 14-12-2019**

- [X] llevar los niños a natación
- [X] aprender markdown
- [ ] renovar mi suscripción del gimnasio

### Citas
> Esto sería una cita como la que acabas de ver.
> 
> > Dentro de ella puedes anidar otra cita.
> 
> La cita principal llegaría hasta aquí. 



### Códigos de bloque
~~~
Creando códigos de bloque.
Puedes añadir tantas líneas y párrafos como quieras.  
~~~

### Reglas horizontales
***
---
___

## Elementos de línea

### Énfasis (Negritas y cursivas)
- *cursiva*
- _cursiva_
- **negrita**
- __negrita__
- ***negrita y cursiva***
- ___negrita y cursiva___
- ~~palabra tachada~~
- ~~**palabra tachada**~~

### Links o enlaces
#### Enlace en linea:

[enlace en línea](http://www.limni.net)

#### Enlace como referencia:

Me llamo Javier Cristóbal y tengo un blog sobre [productividad mac][blog].

En dicha [web][blog] recopilo artículos sobre todo lo relacionado con automatización, gestión y eficiencia.

[blog]: http://limni.net/blog/

#### Links automáticos
<http://www.limni.net>

### Código
`Esto es una línea de código`

#### Esto es un conjunto de código
```html
<!DOCTYPE HTML>
<html>
  <head>
    <title>Ejemplo</title>
  </head>
  <body>

    <?php
     echo "¡Hola, mundo PHP!";
    ?>

  </body>
</html>
```

```JSON  
{"asd":"Aquí van el codigo en json"}
```

```Javascript
var = Aquí van el codigo en javascript
var = var + "yeahhh"
```


#### Resaltar código dentro de un texto
El comando para instalar LibreOffice es `sudo apt install libreoffice`.

### Imágenes
#### Desde una url de la web

![Texto alternativo](https://www.purina-latam.com/sites/g/files/auxxlc391/files/styles/kraken_generic_max_width_360/public/Que_debes_saber_antes_de_adoptar_un_gatito.jpg?itok=5_yubDf3)

#### Desde una imagen de tu pc
<img src="gatito.jpg"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />

### Videos

#### Poner una imagen de la web para redireccionar a la url del video a mostrar
[![texto_alternativo_imagen](https://www.purina-latam.com/sites/g/files/auxxlc391/files/styles/kraken_generic_max_width_360/public/Que_debes_saber_antes_de_adoptar_un_gatito.jpg?itok=5_yubDf3)](https://www.youtube.com/watch?v=ITn5Q6W9RQY)

### Tablas
| Mes | Facturación | Comercial |
| --- | ---: | :---: |
| Enero | 100.000 | Feli |
| Enero | 200.000 | Fran C. |
| Febrero | 400.000 | Feli |
| Febrero | 50.000 | Fran C. |

### Omitir caracteres markdown
Para omitir caracteres usados en markdown y mostrarlos por pantalla, se debe anteponer \ en el caracter.
Los caracteres son:
- \\  barra invertida
- \`  acento invertido
- \*  asterisco
- \_  guión bajo
- \{\} llaves
- \[\] corchetes
- \(\) paréntesis
- \#  almohadilla
- \+  símbolo de suma
- \-  guión
- \.  punto
- \!  exclamación

## Ecuaciones
En la misma linea: $A = \pi*r^{2}$ 

La *función Gamma* satisface $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ a través de la integral de Euler

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$


$$X_i$$

$$X_{i}$$

$$X_{i,j}$$

$$X_i,j$$

$$X^2_{i,j}$$

$$\sqrt{b^2 - 4ac}$$

$$\frac{4z^3}{16}$$

$$\sum_{i=1}^{n} X^3_i$$

$$\sum_{i=1}^{n}\left( \frac{X_i}{Y_i} \right)$$

$$\alpha, \beta,  \gamma, \Gamma$$

$$a \pm b$$

$$x \ge 15$$

$$a_i \ge 0~~~\forall i$$

$$\int_0^{2\pi} \sin x~dx$$

$$\begin{array}
{rrr}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{array}
$$

$$\mathbf{X} = \left[\begin{array}
{rrr}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{array}\right]
$$


