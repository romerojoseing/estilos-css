# Etiquetas de CSS

<br>

## ¿Qué es CSS? 🚀

_CSS son las hojas de estilos en cascada, es el lenguaje que se utiliza para diseñar la estetica visual de un sitio web, si lo ponemos de cierta forma las hojas de estilos serian la piel del cuerpo humano y donde el html serian los huesos, uno seria el estilo y el otro la estructura._

<br>

## Reglas Básicas de CSS 📋

Para el diseño de los estilos css vamos a tener que seguir algunas reglas importantes en cuanto a la composicion, tendremos un selector que servira como referencia al momento de asignar propiedades a selectores que pueden ser etiquetas, clases, id,... luego tendremos una propiedad que se le agregara a este selector y el valor correspondiente a esta propiedad.

```css
	selector{
		propiedad: valor;
	}

	h1{									
		font-size: 10px;	
	}
```

<br>

## Tipos de Selectores 👓

|  Selectores  |                                    Descripción                                   |
|:------------:|----------------------------------------------------------------------------------|
|   ```div```  | Selector de tipo etiqueta, este sirve para cualquier etiqueta declarada en HTML. |
| ```.class``` | Selector de clase asociada a una etiqueta en HTML.                               |
|   ```#id```  | Selector de id asociado a una etiqueta en HTML.                                  |

<br>

## Unidades de Medida 📏

|  Valores  | Descripción                                                                                        |
|:---------:|----------------------------------------------------------------------------------------------------|
|  ```px``` | Píxeles (relativo al dispositivo)                                                                  |
|  ```em``` | Relativo al tamaño de la fuente del elemento (2em significa 2 veces el tamaño de la fuente actual) |
| ```rem``` | Relativo al tamaño de la fuente Padre (2rem significa 2 veces el tamaño de la fuente del padre)    |
|  ```%```  | Porcentaje (relativo al elemento padre)                                                            |

<br>

## Color 🌈

|  Propiedad  |             Valores             | Descripción                          |
|:-----------:|:-------------------------------:|--------------------------------------|
| ```color``` |            ```red```            | Color de Texto en formato nombre     |
|             |          ```#ffffff```          | Colo de Texto en formato hexadecimal |
|             |    ```rgb(255, 255, 255);```    | Color de Texto en formato RGB        |
|             | ```rgba(255, 160, 122, 0.3);``` | Color de Texto en formato RGBA       |

<br>

## Fondos 🖼

|          Propiedad          |                       Valores                       | Descripción                     |
|:---------------------------:|:---------------------------------------------------:|---------------------------------|
|    ```background-color```   |        Aplican todos los valores de colores.        | Fondo con formato solo color.   |
|    ```background-image```   |                      url(...);                      | Fondo con formato de imagen.    |
|   ```background-repeat```   |    ```repeat , repeat-x , repeat-y , no-repeat```   | Repetir la imagen de fondo.     |
| ```background-attachment``` |                 ```scroll , fixed```                | Desplazamiento de la imagen.    |
|  ```background-position```  |  ```percentage , length , left , center , right```  | Posición de la imagen de fondo. |
|       ```background```      | Aplican todos los valores de las clases background  | Fondo compuesto                 |

<br>

## Fuentes 🔠

|      Propiedad     |                                                      Valores                                                      | Descripción                                            |
|:------------------:|:----------------------------------------------------------------------------:|--------------------------------------------------------|
|  ```font-family``` |                                     ```nombre-familia , arial , sans-serif```                                     | Familias de fuentes.                                   |
|  ```font-style```  |                                          ```normal , italic , oblique```                                          | Estilo de la fuente.                                   |
| ```font-variant``` |                                             ```normal , small-caps```                                             | Variante de fuente.|
|  ```font-weight``` |            ```normal , bold , bolder , lighter , 100 - 900```           | Anchura de los caracteres.                           |
|   ```font-size```  | ```small , medium , large , px , % , em , rem``` | Tamaño de la fuente.                                   |

<br>

## Textos 🔡

|       Propiedad       |                      Valores                     | Descripción                                   |
|:---------------------:|:------------------------------------------------:|-----------------------------------------------|
|   ```text-indent```   |              ```px , % , em , rem```             | Desplazamiento de la primera línea del texto. |
|    ```text-align```   |       ```left , right , center , justify```      | Alineamiento del texto.                       |
| ```text-decoration``` | ```none , underline , overline , line-through``` | Efectos de subrayado, tachado, parpadeo       |
|  ```letter-spacing``` |         ```normal , px , % , em , rem```         | Espacio entre caracteres.                     |
|   ```word-spacing```  |         ```normal , px , % , em , rem```         | Espacio entre palabras.                       |
|  ```text-transform``` |  ```capitalize , uppercase , lowercase , none``` | Transformación a mayúsculas / minúsculas.     |
|   ```line-height```   |         ```normal , px , % , em , rem```         | Tamaño del espacio entre líneas.              |

<br>

## Listas 📃

|         Propiedad         |                                                                                                  Valores                                                                                                  | Descripción                                                           |
|:-------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|-----------------------------------------------------------------------|
|   ```list-style-type```   | ```disc ,  circle ,  square ,  decimal ,  decimal-leading-zero ,  lower-roman ,  upper-roman ,  lower-greek ,  lower-latin ,  upper-latin ,  armenian ,  georgian ,  lower-alpha ,  upper-alpha , none``` | Estilo aplicable a los marcadores.                                    |
|   ```list-style-image```  |                                                                                        ```url(“http://…”) , none```                                                                                       | Imagen aplicable a los elementos de las listas.                       |
| ```list-style-position``` |                                                                                           ```inside , outside```                                                                                          | Posición dentro de la lista de los elementos marcadores de las listas |
|      ```list-style```     |                                                                       ```list-style-type , list-style-position , list-style-image```                                                                      | Permite establecer el estilo de la lista, la imagen y/o la posición   |

<br>

## Cajas 📦

|         Propiedad         |                                          Valores                                         | Descripción                             |
|:-------------------------:|:----------------------------------------------------------------------------------------:|-----------------------------------------|
|        ```width```        |                              ```auto , px , % , em , rem```                              | Ancho de la caja.                       |
|      ```min-width```      |                              ```auto , px , % , em , rem```                              | Ancho mínimo de la caja.                |
|      ```max-width```      |                              ```auto , px , % , em , rem```                              | Ancho máximo de la caja.                |
|        ```height```       |                              ```auto , px , % , em , rem```                              | Alto de la caja.                        |
|      ```min-height```     |                              ```auto , px , % , em , rem```                              | Alto mínimo de la caja.                 |
|      ```max-height```     |                              ```auto , px , % , em , rem```                              | Alto máximo de la caja.                 |
|     ```padding-top```     |                                  ```px , % , em , rem```                                 | Margen superior interno de la caja.     |
|    ```padding-right```    |                                  ```px , % , em , rem```                                 | Margen derecho interno de la caja.      |
|    ```padding-bottom```   |                                  ```px , % , em , rem```                                 | Margen inferior interno de la caja.     |
|     ```padding-left```    |                                  ```px , % , em , rem```                                 | Margen izquierdo interno de la caja.    |
|       ```padding```       |                                  ```px , % , em , rem```                                 | Margen interno de la caja.              |
|      ```margin-top```     |                                  ```px , % , em , rem```                                 | Margen superior externo de la caja.     |
|     ```margin-right```    |                                  ```px , % , em , rem```                                 | Margen derecho externo de la caja.      |
|    ```margin-bottom```    |                                  ```px , % , em , rem```                                 | Margen inferior externo de la caja.     |
|     ```margin-left```     |                                  ```px , % , em , rem```                                 | Margen izquierdo externo de la caja.    |
|        ```margin```       |                                  ```px , % , em , rem```                                 | Margen externo de la caja.              |
|   ```border-top-width```  |                      ```thin , medium , thick , px , % , em , rem```                     | Anchura del borde superior de la caja.  |
|  ```border-right-width``` |                      ```thin , medium , thick , px , % , em , rem```                     | Anchura del borde derecho de la caja.   |
| ```border-bottom-width``` |                      ```thin , medium , thick , px , % , em , rem```                     | Anchura del borde inferior de la caja.  |
|  ```border-left-width```  |                      ```thin , medium , thick , px , % , em , rem```                     | Anchura del borde izquierdo de la caja. |
|     ```border-width```    |                      ```thin , medium , thick , px , % , em , rem```                     | Anchura del borde de la caja.           |
|   ```border-top-color```  |                                 ```color , transparent```                                | Color de borde superior de la caja.     |
|  ```border-right-color``` |                                 ```color , transparent```                                | Color de borde derecho de la caja.      |
| ```border-bottom-color``` |                                 ```color , transparent```                                | Color de borde inferior de la caja.     |
|  ```border-left-color```  |                                 ```color , transparent```                                | Color de borde izquierdo de la caja.    |
|     ```border-color```    |                                 ```color , transparent```                                | Color de borde de la caja.              |
|   ```border-top-style```  | ```none , hidden , dotted , dashed , solid , double , groove , ridge , inset , outset``` | Estilo de borde superior de la caja.    |
|  ```border-right-style``` | ```none , hidden , dotted , dashed , solid , double , groove , ridge , inset , outset``` | Estilo de borde derecho de la caja.     |
| ```border-bottom-style``` | ```none , hidden , dotted , dashed , solid , double , groove , ridge , inset , outset``` | Estilo de borde inferior de la caja.    |
|  ```border-left-style```  | ```none , hidden , dotted , dashed , solid , double , groove , ridge , inset , outset``` | Estilo de borde izquierdo de la caja.   |
|     ```border-style```    | ```none , hidden , dotted , dashed , solid , double , groove , ridge , inset , outset``` | Estilo de borde de la caja.             |
|      ```border-top```     |               ```border-top-width , border-top-style , border-top-color```               | Borde superior de la caja.              |
|     ```border-right```    |               ```border-top-width , border-top-style , border-top-color```               | Borde derecho de la caja.               |
|    ```border-bottom```    |               ```border-top-width , border-top-style , border-top-color```               | Borde inferior de la caja.              |
|     ```border-left```     |               ```border-top-width , border-top-style , border-top-color```               | Borde izquierdo de la caja.             |
|        ```border```       |               ```border-top-width , border-top-style , border-top-color```               | Borde de la caja.                       |
|    ```border-radius```    |                                  ```px , % , em , rem```                                 | Curvatura del borde                     |
|       ```position```      |                        ```static , relative , absolute , fixed```                        | Esquema de posicionamiento              |
|       ```display```       |                        ```inline , block , inline-block , none```                        | Comportamiento del contenedor           |
|         ```top```         |                              ```auto , px , % , em , rem```                              | Desplazamiento superior de la caja.     |
|        ```right```        |                              ```auto , px , % , em , rem```                              | Desplazamiento derecho de la caja.      |
|        ```bottom```       |                              ```auto , px , % , em , rem```                              | Desplazamiento inferior de la caja.     |
|         ```left```        |                              ```auto , px , % , em , rem```                              | Desplazamiento izquierda de la caja.    |
|        ```float```        |                                 ```left , right , none```                                | Posicionamiento flotante                |
|        ```clear```        |                             ```none , left , right , both```                             | Control de cajas adyacentes a las float |
|       ```z-index```       |                                ```auto , numero entero```                                | Nivel de la capa                        |

<br>

## Pseudo-clases 🎬

|  Pseudo-clase  | Descripción                                                     |
|:--------------:|-----------------------------------------------------------------|
|   ```:link```  | No visitado por el usuario                                      |
| ```:visited``` | Visitado por el usuario                                         |
|  ```:hover```  | Modifica el estilo cuando un elemento apuntador pasa por encima |
|  ```:active``` | Se activa cuando el usuario pulsa el elemento                   |
|  ```:focus```  | Se activa cuando tiene el foco sobre el elemento                |


<br><br>

## Construido con 🛠️

_Para el desarrollo de este proyecto se utilizaron las siguientes tecnologías:_

* [CSS 3](https://es.wikipedia.org/wiki/Hoja_de_estilos_en_cascada) - Diseño de estilos.

<br>

## Autor ✒️

_Si te gusta lo que hago, visita mi web y comparte mi contenido, también puedes seguirme en mis redes para estar al tanto de nuevas publicaciones y proyectos interesantes que estaré desarrollando._

Diseñado con ❤️ por [Romero José](https://romerojose.com/)

### Redes Sociales

* **GitHub** - *Repositorios de mis últimos proyectos* - [romerojoseing](https://github.com/romerojoseing)
* **CodePen** - *Mini proyectos y pruebas interesantes* - [romerojoseing](https://codepen.io/romerojoseing)
* **LinkedIn** - *Perfil desarrollador profesional* - [romerojoseing](https://www.linkedin.com/in/romerojoseing/)
* **Instagram** - *Documentando mi viaje* - [romerojoseing](https://www.instagram.com/romerojoseing/)
* **Facebook** - *Publicaciones y contenido promocional* - [romerojoseing](https://www.facebook.com/romerojoseing)
* **Twitter** - *Comentarios random y más* - [romerojoseing](https://twitter.com/romerojoseing)