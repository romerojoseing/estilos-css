<p align="center"><img src="https://github.com/romerojoseing/archivos/blob/master/img/logov.png?raw=true" width="150"></p>

<p align="center">
Te doy la bienvenida a mi repositorio, puedes usar este contenido con total libertad, siempre teniendo el mayor respeto por los autores que desarrollaron el proyecto.
</p>

<br>

# Etiquetas de CSS

<br>

## ¿Qué es CSS?

CSS son las hojas de estilos en cascada, es el lenguaje que se utiliza para diseñar la estetica visual de un sitio web, si lo ponemos de cierta forma las hojas de estilos serian la piel del cuerpo humano y donde el html serian los huesos, uno seria el estilo y el otro la estructura. 

<br>

## Reglas Básicas de CSS

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

## Tipos de Selectores

|  Selectores  |                                    Descripción                                   |
|:------------:|----------------------------------------------------------------------------------|
|   ```div```  | Selector de tipo etiqueta, este sirve para cualquier etiqueta declarada en HTML. |
| ```.class``` | Selector de clase asociada a una etiqueta en HTML.                               |
|   ```#id```  | Selector de id asociado a una etiqueta en HTML.                                  |

<br>

## Unidades de Medida

|  Valores  | Descripción                                                                                        |
|:---------:|----------------------------------------------------------------------------------------------------|
|  ```px``` | Píxeles (relativo al dispositivo)                                                                  |
|  ```em``` | Relativo al tamaño de la fuente del elemento (2em significa 2 veces el tamaño de la fuente actual) |
| ```rem``` | Relativo al tamaño de la fuente Padre (2rem significa 2 veces el tamaño de la fuente del padre)    |
|  ```%```  | Porcentaje (relativo al elemento padre)                                                            |

<br>

## Color

|  Propiedad  |             Valores             | Descripción                          |
|:-----------:|:-------------------------------:|--------------------------------------|
| ```color``` |            ```red```            | Color de Texto en formato nombre     |
|             |          ```#ffffff```          | Colo de Texto en formato hexadecimal |
|             |    ```rgb(255, 255, 255);```    | Color de Texto en formato RGB        |
|             | ```rgba(255, 160, 122, 0.3);``` | Color de Texto en formato RGBA       |

<br>

## Fondos

|          Propiedad          |                       Valores                       | Descripción                     |
|:---------------------------:|:---------------------------------------------------:|---------------------------------|
|    ```background-color```   |        Aplican todos los valores de colores.        | Fondo con formato solo color.   |
|    ```background-image```   |                      url(...);                      | Fondo con formato de imagen.    |
|   ```background-repeat```   |    ```repeat , repeat-x , repeat-y , no-repeat```   | Repetir la imagen de fondo.     |
| ```background-attachment``` |                 ```scroll , fixed```                | Desplazamiento de la imagen.    |
|  ```background-position```  |  ```percentage , length , left , center , right```  | Posición de la imagen de fondo. |
|       ```background```      | Aplican todos los valores de las clases background  | Fondo compuesto                 |

<br>

## Fuentes

|      Propiedad     |                                                      Valores                                                      | Descripción                                            |
|:------------------:|:----------------------------------------------------------------------------:|--------------------------------------------------------|
|  ```font-family``` |                                     ```nombre-familia , arial , sans-serif```                                     | Familias de fuentes.                                   |
|  ```font-style```  |                                          ```normal , italic , oblique```                                          | Estilo de la fuente.                                   |
| ```font-variant``` |                                             ```normal , small-caps```                                             | Variante de fuente.|
|  ```font-weight``` |            ```normal , bold , bolder , lighter , 100 - 900```           | Anchura de los caracteres.                           |
|   ```font-size```  | ```small , medium , large , px , % , em , rem``` | Tamaño de la fuente.                                   |

<br>

## Textos

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

## Listas

|         Propiedad         |                                                                                                  Valores                                                                                                  | Descripción                                                           |
|:-------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|-----------------------------------------------------------------------|
|   ```list-style-type```   | ```disc ,  circle ,  square ,  decimal ,  decimal-leading-zero ,  lower-roman ,  upper-roman ,  lower-greek ,  lower-latin ,  upper-latin ,  armenian ,  georgian ,  lower-alpha ,  upper-alpha , none``` | Estilo aplicable a los marcadores.                                    |
|   ```list-style-image```  |                                                                                        ```url(“http://…”) , none```                                                                                       | Imagen aplicable a los elementos de las listas.                       |
| ```list-style-position``` |                                                                                           ```inside , outside```                                                                                          | Posición dentro de la lista de los elementos marcadores de las listas |
|      ```list-style```     |                                                                       ```list-style-type , list-style-position , list-style-image```                                                                      | Permite establecer el estilo de la lista, la imagen y/o la posición   |

<br><br>

## Tecnologías Usadas

- CSS3

<br><br>

## Autor

<p align="center"><img src="https://github.com/romerojoseing/archivos/blob/master/img/logoh.png?raw=true" width="200"></p>

<p align="center">
  Si te gusto el proyecto sígueme y dame apoyo para seguir creando más contenido.
</p>

<p align="center">
  <a target="_blank" href="https://romerojose.com/"><img src="https://github.com/romerojoseing/archivos/blob/master/img/web.png?raw=true" height="20"></a> - 
  <a target="_blank" href="https://www.linkedin.com/in/romerojoseing/"><img src="https://github.com/romerojoseing/archivos/blob/master/img/linkedin.png?raw=true" height="20"></a> - 
  <a target="_blank" href="https://github.com/romerojoseing"><img src="https://github.com/romerojoseing/archivos/blob/master/img/github.png?raw=true" height="20"></a> - 
  <a target="_blank" href="https://www.instagram.com/romerojoseing/"><img src="https://github.com/romerojoseing/archivos/blob/master/img/instagram.png?raw=true" height="20"></a> - 
  <a target="_blank" href="https://www.facebook.com/romerojoseing"><img src="https://github.com/romerojoseing/archivos/blob/master/img/facebook.png?raw=true" height="20"></a> - 
  <a target="_blank" href="https://twitter.com/romerojoseing"><img src="https://github.com/romerojoseing/archivos/blob/master/img/twitter.png?raw=true" height="20"></a>
</p>