# ASIX1_MP4UF1_apuntes_SergioCallejas

## **_GitHub_**

Comandos básicos de Git :

**git init** : inicializa un repositorio nuevo de Git y comienza a supervisar el directorio existente. Este agrega una subcarpeta oculta dentro del directorio existente que hospeda la estructura de datos interna que se requiere para el control de versiones.

**git clone** : crea una copia local de un proyecto que ya existe remotamente. El clon incluye todos los archivos, historial y ramas del proyecto.

**git add** : almacena provisionalmente un cambio. Git rastrea los cambios que se hacen a la base de código de un desarrollador, pero es necesario probarlos y tomar una captura de pantalla de ellos para incluirla en el historial del proyecto. Este comando realiza pruebas, la primera parte de este proceso consta de dos pasos. Cualquier cambio que se pruebe, se convertirá en parte de la siguiente captura de pantalla y también del historial del proyecto. Las pruebas y confirmaciones por separado otorgan a los desarrolladores el control completo sobre el historial y sobre el proyecto sin cambiar la forma en la que codifican y trabajan.

**git commit** : guarda la instantánea del historial del proyecto y completa el proceso de seguimiento de los cambios. En resumen, una confirmación funciona tal como el tomar una fotografía. Todo lo que se haya almacenado provisionalmente con git add pasará a formar parte de la instantánea con git commit.

**git status** : muestra el estado de los cambios como sin seguimiento, modificados o almacenados provisionalmente.

**git branch** : muestra las ramas en las que se trabaja localmente.

**git merge** : combina las líneas de desarrollo. Este comando habitualmente se utiliza para combinar los cambios que se realizan en dos ramas distintas. Por ejemplo, un desarrollador podría hacer una fusión cuando necesite combinar los cambios de una rama de característica en la rama de desarrollo principal.

**git pull** : actualiza la línea de desarrollo local con actualizaciones de sus contrapartes remotas. Los desarrolladores utilizan este comando si un compañero de equipo hizo confirmaciones en una rama en un repositorio remoto y quieren reflejarlas en su ambiente local.

**git push** : actualiza el repositorio remoto con las confirmaciones realizadas localmente en una rama.

**git branch** : -M main Asociamos la versión a la rama de desarrollo que queramos. La rama por defecto es “main”. 

**git push** : -u origin main Subimos los cambios al repositorio remoto y rama indicadas en los puntos anteriores.

**git clone** + URL* : clonar de GitHub a tu ordenador

___

## **_MarkDown_**

### ENCABEZADOS 

#→Es para poner encabezados. Máximo de encabezados 6#
Los encabezados se crean usando el carácter sostenido # delante de la oración que quieras que se formatee como un encabezado. Los encabezados pueden ser de diferentes niveles, organizándose jerárquicamente.


# Encabezado nivel 1

## Encabezado nivel 2

### Encabezado nivel 3

#### Encabezado nivel 4

##### Encabezado nivel 5

###### Encabezado nivel 6


También existe una sintaxis alternativa para los encabezados que consiste en agregar un número de caracteres = equivalente al número de caracteres del encabezado de la línea superior.

````
Encabezado nivel 1
==================

Encabezado nivel 2
------------------
````

### PALABRAS 

Para agregar texto resaltado en negrita tendrás que usar dos asteriscos ** o dos guiones bajos __ al principio y al final de lo oración que quieres resaltar. En caso de que quieras resaltar un texto que está en medio de una palabra, tedrás que agregar dos asteriscos ** o dos guiones bajos __, sin espacios, antes y después de las letras deseadas.

````
**palabra** __palabra__ → Negrita 
````

Para agregar texto en cursiva debes usar un solo asterisco * o un solo guión bajo _ tanto al inicio como al final de lo oración que quieres marcar como cursiva. Si quieres poner en cursiva ciertas letras que estén en la mitad de una palabra, deberás agregar un asterisco * o un guión bajo _, sin espacios, al comienzo y al final de las letras deseadas.

````
*palabra* _palabra_ → cursiva 
````

Para que en texto esté resaltado tanto en negrita como en cursiva al mismo tiempo debes agregar tres asteriscos *** o tres guiones bajos ___ antes y después de una palabra o de una frase. En caso de que el texto que quieres que esté en negrita y en cursiva esté en mitad de una palabra, deberás agregar también tres asteriscos *** o tres guiones bajos ___ sin espacios a ambos lados.


### TABLAS

| Encabezado 1 |  Encabezado 2  | Encabezado 3 | 
| ------------ |  :----------:  | -----------: |
| Item 1 |  Palo | 200 |
| Item 2 |  Piedra | 440 |
| Item 3 | Hoja | 202 |



### PARA CREAR LAS LINEAS HORIZONTALES

Con Markdown también podrás agregar líneas horizontales, que resultan útiles para separar el contenido o las secciones de un documento.
Para crear una línea horizontal basta con que agregues tres o más asteriscos seguidos, tres o más guiones seguidos o tres o más guiones bajos seguidos:

````
___: tres guiones bajos consecutivos
---: tres guiones consecutivos 
***: tres asteriscos consecutivos
````

### CÓDIGO EN LINEA

Para agregar código en línea en Markdown tendrás que usar comillas invertidas alrededor del texto que quieres que tengo formato de código

````
Usa el comando `cd`
``let str = `texto`;``
````

### LINKS

Para crear un enlace en Markdown debes situar entre corchetes el texto que quieres enlazar, también conocido como anchor. Seguidamente, debes usar paréntesis para definir la URL a la que debe enlazar en texto del enlace.
Al igual que en HTML, también podrás enlazar a puntos ancla de la página actual o de otras páginas postponiendo el carácter sostenido # y el id de la sección a enlazar.
Además, también puedes crear enlaces rápidamente a una URL usando únicamente un enlace, sin necesidad de definir un texto de enlace o anchor. Para ello deberás escribir un símbolo mayor > seguido del enlace y un símbolo menor <.

````
[Enlace](https://linux.com)

[Encabezados](#encabezados)

<https://linux.com>

<me@email.com>
````

### LISTAS ORDENADAS

Para agregar listas ordenadas en Markdown debes agregar un número seguido de un punto, un espacio y el elemento de la lista. La lista no debe estar ordenada numéricamente, pero debe comenzar por el número

````
 1. + espacio → Lista Ordenada 

.. Num de lista → Sublista dentro de la lista 

Si ponemos * →  Lista de puntos 
````
  
1. Primer elemento
2. Segundo elemento
3. Tercer elemento
 
 
1. Primer elemento
8. Segundo elemento
1. Tercer elemento
 
 
### LISTAS NO ORDENADAS
 
* Primer elemento
* Segundo elemento
 
+ Primer elemento
+ Segundo elemento
 
- Primer elemento
- Segundo elemento
 
 
### IMAGENES 

Para agregar imágenes con Markdown debes agregar un signo de exclamación ! seguido del texto alternativo o alt de la imagen entre corchetes y de la URL de la imagen entre paréntesis.

![Súbdito](http://octodex.github.com/images/minion.png)

___

## HTML

HTML són les sigles de Hyper Text Markup Language. HTML és un llenguatge de marques per descriure documents web (pàgines web) més usat actualment en el món web.

**html** : Element arrel del document.

**head** : Capçalera, espai destinat a contenir informació del document. 

**title** : Títol descriptiu de la pàgina web. Normalment apareix a la barra del navegador, també és el text que s’emmagatzema en els marcadors del navegador (llista d’adreces d’interès). 

**body** : Cos o contingut del document. 


!DOCTYPE html — el tipo de documento. 
Es un preámbulo requerido. Anteriormente, cuando HTML era joven (cerca de 1991/2), los tipos de documento actuaban como vínculos a un conjunto de reglas que el código HTML de la página debía seguir para ser considerado bueno, lo que podía significar la verificación automática de errores y algunas otras cosas de utilidad. Sin embargo, hoy día es simplemente un artefacto antiguo que a nadie le importa, pero que debe ser incluido para que todo funcione correctamente. Por ahora, eso es todo lo que necesitas saber.
 
html/html — el elemento HTML. Este elemento encierra todo el contenido de la página entera y, a veces, se le conoce como el elemento raíz (root element).
 
head/head — el elemento HEAD. Este elemento actúa como un contenedor de todo aquello que quieres incluir en la página HTML que no es contenido visible por los visitantes de la página. Incluye cosas como palabras clave (keywords), una descripción de la página que quieres que aparezca en resultados de búsquedas, código CSS para dar estilo al contenido, declaraciones del juego de caracteres, etc.
 

title/title — el elemento TITLE establece el título de tu página, que es el título que aparece en la pestaña o en la barra de título del navegador cuando la página es cargada, y se usa para describir la página cuando es añadida a los marcadores o como favorita.
 
body/body — el elemento BODY. Encierra todo el contenido que deseas mostrar a los usuarios web que visiten tu página, ya sea texto, imágenes, videos, juegos, pistas de audio reproducibles, y demás.

Una capçalera mínima seria la següent: 
 
````
Exemple d’un fitxer index.html

<!DOCTYPE html >
<html>
   <head>
<meta charset="utf-8"/>
  	<title>La meva pàgina web</title>
   </head>
   <body>
<!-- Contingut de la web -->
   </body>
</html>
````

 
### Encapçalaments

El número denota el nivell de l’encapçalament, és a dir h1 és l’encapçalament de primer nivell i h6 l’encapçalament d’últim nivell.

![image](https://user-images.githubusercontent.com/113420594/197594387-0ba0db09-aa75-42bc-b6ec-2b122e77f7a6.png)

### ELEMENTOS DE LINEA

**p** : Paràgraf. 
 
**br/** : Salt de línia. 
 
**hr/** : Línia separadora. 
 
**blockquote** : Citació de tipus bloc. 
 
**pre** : Text preformatat. 

**div** : Capa. Es tracta d’una etiqueta de tipus bloc sense significat semàntic que ens servirà per agrupar text i/o d’altres elements. 

### ETIQUETAS CORRESPONDIENTES A ELEMENTOS DE LINEA

A continuació es detalla un resum de les etiquetes de text corresponents a elements de línia, més importants: 

**em** : Text amb èmfasi/cursivai. 

**strong** : Text amb molt èmfasi. 

**q** : Citació de tipus línia. 

**cite** : Font de la citació. 

**acronym** : Acrònim. 

**abbr** : Abreviació. 

**code** : Codi de programació. 

IMAGENES

L’etiqueta que ens serveix per inserir una imatge és l’etiqueta <img>. Es tracta d’un element de línia que no té etiqueta de tancament: es tanca en ella mateixa. 

![image](https://user-images.githubusercontent.com/75097605/197519518-e7e205b1-0f2e-4b6b-822d-57af5dc4cc29.png)

___

### INTRODUCCION A CSS


### 1. _Maquetación básica_


**width** : Ancho de un elemento.

**height** : Alto de un elemento.

**vertical-align** : Alineamiento vertical dentro de un elemento.

**margin** : Espacio que se añade entre el elemento y sus vecinos. Se puede diferencia por lado (arriba, abajo, izquierda, derecha).

**padding** : Relleno interior que se añade en los bordes del A diferencia de margin, cuenta para el tamaño del elemento.

**float** : Mueve el elemento todo lo posible hacia el lado indicado. Esta propiedad se usa en el posicionamiento flotante de CSS. El tema del posicionamiento en CSS no es trivial y conviene estudiar cómo funciona antes de usar esta propiedad.

![image](https://user-images.githubusercontent.com/113420594/208419431-358000de-2d05-4a67-9a08-dee2b80b9002.png)



### 2. _Fuentes y texto_


**font-family** : Tipo de letra

**font-size** : Tamaño de letra

**font-weight** : Peso (normal, negrita, …)

**font-style** : Estilo (normal, cursiva, …)

**text-decoration** : “Decoraciones” como subrayado, tachado, etc.

**text-align** : Alineación del texto (izquierda, derecha, etc.)

En [https://fonts.google.com/](https://fonts.google.com/) localizamos la familia de fuentes que queremos añadir y la seleccionamos. Esto nos permitira ver el codigo necesario para ponerlo en "head" en el archivo HTML y las reglas necesarias para añadirla a la hoja de estilos CSS.


### 3. _Color y fondos_


**color** : Color del elemento. Se puede especificar en diferentes formatos como palabras predefinidas (red, green, etc.) RGB o como valor hexadecimal.

**background-color** : Color del fondo del elemento.

**background-image** : Permite especificar una imagen de fondo.

**background-repeat** : Permite usar una imagen a modo de mosaico en diferentes modalidades.

**box-shadow** : Crear un efecto de sombra para un elemento.


### 4. _Listas_


**list-style-image** : Usar la imagen especificada como viñeta para la lista.

**list-style-type** : Diferentes estilos de viñetas y estilos de numeración para elementos de lista.


### 5. _Bordes_


**border** : Añade un borde a un elemento y establece algunas propiedades (grosor, estilo de línea, etc.)
**border-color** : Color del borde.
**border-style** : Diferentes estilos para el borde (sólido, puntos, etc.)
**border-radius** : Permite crear esquinas redondeadas para un elemento.






