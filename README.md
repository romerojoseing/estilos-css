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

	h1{									/* Selector */
		font-size: 10px;				/* Propiedad y Valor */
	}
```


<br>

## Selectores

```css
	div{                     			/* Selector de Etiqueta */
    background: #fff;
	}

	#div{                                /* Selector de Id */
    background: #fff;
	}

	.div{                                /* Selector de Clase */
    background: #fff;
	}
```

```css
	/* ---------------------- Atribitos y condiciones de las fuentes y otros ---------------------- */
h1{
    color: white;               /* Cambia el Color de tecto o icono */
    color: gray !important;     /* Darle importancia a esta regla sobre todo */
    background: gray;           /* Cambia color de Fondo */
    background-image: url(../img/bakbaner.png);
    background-position: -200px -200px;
    
    font-size: 18px;              /* Tamaño de Fuente */
    font-weight: 500;             /* Grosor de Fuente */
    font-family: sans-serif;      /* Familia de Fuente */
    font-style: normal;           /* Estilo de Fuente */

    text-align: center;           /* Alinear el texto */
    text-decoration: none;        /* Eliminar decoracion en texto (Enlaces) o usar el underline para agregar subrayado*/
    text-transform: uppercase;    /* Transformar fuente Minusculas o Mayusculas */
    text-shadow: 1px 1px 2px black;  /* Sombra en Texto X Y Grosor Color*/
    text-indent: 20px;            /* Generar un espacio antes de cada parrafo */
    word-spacing: 10px;           /* Generar espacio entre palabras*/
    letter-spacing: 5px;          /* Generar espacios entre letras*/ 
    line-height: 50px;            /* Ajustar el espacio entre lineas*/

    width: 300px;                 /* Tamaño Horizontal del elemento */
    min-width: 500px;             /* Tamaño Minimo de ancho */
    max-width: 1400px;            /* Tamaño Maximo de ancho */
    height: 200px;                /* Tamaño Vertical del elemento */
    min-height: 500px;            /* Tamaño Minimo de alto */
    max-height: 1400px;           /* Tamaño Maximo de alto */
    
    margin: 10px;                 /* Margen Externo del texto, imagen o lo que sea */
    margin: 10px auto;            /* Margen de 10px top y centrar */
    margin-top: 10px;
    margin-left: 10px;
    margin-bottom: 10px;
    margin-right: 10px;
    margin: 15px 15px 15px 15px;  /* Top Right Botton Left */

    padding: 10px;                /* Margen Interno del texto, imagen o lo que sea */
    padding-top: 10px;
    padding-left: 10px;
    padding-bottom: 10px;
    padding-right: 10px;
    padding: 15px 15px 15px 15px; /* Top Right Botton Left */

    border: 1px solid black;            /* Agregar borde Tamaño Tipo y Color */
    box-shadow: 0px 0px 15px black;     /* Sombras Horizontal Vertical Difuminado y Color*/
    border-radius: 30px 10px 4px 60px;    /* Sup iz, sup der, inf der, inf iz*/
    border-radius: 50%;
    border-radius: 30px;

    display: block;               /* Trabajar el elemnto como un bloque */
    float: left;                  /* Flotar las cajas para que se muevan en una direccion junstas */

    cursor: pointer;              /* Hacer efecto de cursor de mano en el puntero*/

    position: absolute;           /*Posicion absoluta que pasa por encima de cualquier elemento*/
    top: 10%;
    left: 0px;
    z-index: 1;                   /*Relevancia de elementos para saber cual va encima, mientras mas alto el indice va arriba del todo*/

    position: fixed;              /* Posicio fijada donde se sigue el scroll de la pagina*/
    top: 50%;
    left: 0px;
    z-index: 2;

    overflow: scroll;
    overflow-y: scroll;             /* scroll en casilla de texto*/
    overflow-x: hidden;
    overflow: hidden;               /* todo lo que se salga fuera del item no se ve */
    
}
```






| Longitudes |                 Valores                 | Descripción |
|:----------:|:---------------------------------------:|:-----------:|
|  Relativas |                 ```px```                | ayuda       |
|            | StartFragment```position``` EndFragment | dssf        |
|            | StartFragment```position``` EndFragment | dfdsf       |
|            | StartFragment```position``` EndFragment | fsdfsd      |

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