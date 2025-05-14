# Spike HTML y CSS
###### Realizado por: Diego Vallejo Z. 
###### Riwi - Clan Hopper a.m.
###### (14/05/2025)


### 1. Objetivo
- Conocer de manera general los principales conceptos y funcionamiento de HTML y CSS en la creación y funcionamiento de páginas web.

___

### 2. Contexto
El presente spike se realiza con el propósito de conocer los aspectos generales de html y css para su uso en el desarrollo web, teniendo en cuenta que son dos de las principales tres herramientas para este fin, las cuales en conjunto y sumadas a JavaScript permite tener sitios web funcionales, estéticos y dinámicos.

___
### 3. Alcance
El alcance del presente spike es poder adquirir los conocimientos básicos generales de que es y como funciona HTML y CSS en la creación de sitios y paginas web hoy en dia, para de esta manera poder abordar la temática del siguiente módulo - sprint de la mejor manera posible, teniendo una clara conceptualización de este tema. Para dicho propósito se hay propuesto un tiempo estimado de ocho horas para adelantar el proceso.

___
### 4. Preguntas por resolver

Las principales preguntas a resolver en el presente spike son:
- ¿Que es HTML?
- ¿Como es el funcionamiento general de HTML?
- ¿Para que sirve HTML?
- ¿Que es CSS?
- ¿Como es el funcionamiento general de CSS?
- ¿Para que sirve CSS?
- ¿Deberíamos usar estos dos tipos de archivos para la creación de paginas web?

___
### 5. Criterios de aceptacion
Los criterios de aceptacion se definen en:
- Cumplir el objetivo del presente spike.
- Cumplir con el alcance definido previamente.
- Dar respuesta a las preguntas planteadas.
- Presentar un documento escrito (este documento) con toda la información consultada y los hallazgos encontrados, de manera clara y resumida.
- Presentar las conclusiones de la investigación.
- Presentar las diversas fuentes de información consultada y usada en el documento.

___
### 6. Investigación y hallazgos
Durante la labor investigación y de revisión de información se encontró una gran cantidad de información relacionada, la cual se logró resumir exitosamente de la siguiente manera: 

### ¿Que es Html y Css?
#### 6.1 HTML
**HTML (Lenguaje de Marcado de Hipertexto, del inglés HyperText Markup Language)** es el componente más básico de la Web. Define el significado y la estructura del contenido web. Además de HTML, generalmente se utilizan otras tecnologías para describir la apariencia/presentación de una página web (CSS) o la funcionalidad/comportamiento (JavaScript). *(Developer Mozilla, s.f.)*

Es importante mencionar que HTML no es un lenguage de programación como tal, ya que este **se basa en el uso de etiquetas para el demarcado de texto** para ser mas facil de alcanzar por los diferentes buscadores de internet en la web. Es importante resaltar que todo documento debe poseer la extensión .html para que se un documento de este tipo.

En HTML existen una gran variedad de etiquetas las cuales se usan para diferentes clases de información, por ejemplo para el uso de encabezados (títulos) se usan las 'h' (de la h1 a la h6), para los párrafos se utiliza la etiqueta 'p', para las tablas la etiqueta 'table', etc.

A continuación se presentan algunas de las principales y mas usadas etiquetas en HTML:


|       ETIQUETA      |           TIPO          |        ¿QUE ES?       |
|:--------------------|:------------------------|:----------------------|
|html      | Documento html  | Estructura fundamental de todo documento html|
| head |   Documento html  | Encabezado del documento Html. No visible al usuario|
| body | Docuento html  | Cuerpo del html donde va todo el texto y etiquetas a usar |
| link | Documento html | Relaciona con documentos CSS para darle estilos al html |
|           p         | Etiquetas de texto HTML | Párrafo |
| h1 a h6   | Etiquetas de texto HTML | Títulos  |
| cite      | Etiquetas de texto HTML | Título de libros o trabajos web |
| q     | Etiquetas de texto HTML |     Cita online |
| code | Etiquetas de texto HTML | Visualizar una parte del código de programación |
| br    | Etiquetas de texto HTML  | Salto de línea sencillo   |
| div | Etiquetas de texto HTML  | División |
| a | Etiquetas de texto HTML | Etiquetas de anclaje de un enlace |
| img | Etiquetas de imagen y objeto | Imagen |
| map | Etiquetas HTML de imagen y objeto | Mapa de imagen |
| object | Etiquetas HTML de imagen y objeto | Insertar un objeto |
| ul   | 	Etiquetas de lista HTML | Lista desordenada |
| ol | 	Etiquetas de lista HTML | Lista ordenada |
| li | 	Etiquetas de lista HTML | Item de lista |
| dl | 	Etiquetas de lista HTML | Lista de descripciones |
| dt | 	Etiquetas de lista HTML | Término en la lista de descripciones |
| dd | 	Etiquetas de lista HTML | Definición/Descripción de un término en la lista de descripciones |

Si se desea conocer muchas mas etiquetas de HTML nos podemos redirigir al siguiente enlace: 
- https://www.mclibre.org/consultar/htmlcss/html/html-etiquetas.html


#### 6.2 CSS
Las siglas CSS **(Cascading Style Sheets) significan «Hojas de estilo en cascada»** y parten de un concepto simple pero muy potente: aplicar estilos (colores, formas, márgenes, etc...) a uno o varios documentos (generalmente documentos HTML, páginas webs) de forma automática y masiva.

Se le denomina estilos en cascada porque se lee, procesa y aplica el código desde arriba hacia abajo (siguiendo patrones como herencia o cascada que trataremos más adelante) y en el caso de existir ambigüedad (código que se contradice), se siguen una serie de normas para resolver dicha ambigüedad.

Para el uso de CSS es impresindible contar con un archivo html para aplicarle los estilos. El archivo CSS debe poseer la extensión .css para que sea un documento válido para este tipo de estilos. Aunque los estilos de una página se puede realizar de manera integrada en el mismo código html, esto se considera una mala práctica ya que mezcla dos códigos en algo llamado "código spaguetti" el cual no es tan facil de interpretar, espor ello que se suele crear otro archivo a parte llamado estilos.css para manejar todos los estilos de la página web.

Para realizar la conexión entre los dos archivos, se usa la etiqueta "link" en el código del head del html tendiendo presente de realizar la siguiente configuración en el 'rel:' para que el archivo css en cuestión sea leido como un archivo de estilos:   ***link rel="stylesheet" href="/estilos.css"***

Para saber a que le estamos aplicando los diferentes estilos, CSS se basa en las etiquetas del HTML (h1, p, a, table, ul, etc), en las cuales debimos haber creado las diferentes clases *("class')* e identificadores *('id')*. **En CSS utilizaremos los siguientes caracteres al inicio de las llaves antes de darle un estilo a una etiqueta, dependiendo si queremos referirnos a una class = "." o un "#" si lo haremos con base en un id.**

Para tener esto mas claro se usa de la siguiente manera:

**Aplicar el color "blue" a todas las clases llamadas "texto":**

    .texto{
        color: blue;
    }
Recordar hacer el uno del punto '.' al inicio para difinir que se trabajará sobre una clase.

**Aplicar el color "red" al id llamado "importante":**

    #importante{
        color: red;
    }
Recordar hacer uso de '#' para denotar que se trabajará sobre un id en específico.

___
### 7. Recomendaciones / conclusiones

#### 7.1 Recomendaciones
- Dentro de las recomendaciones a tener en cuenta se encuentran:
- Usar las correctas etiquetas en el documento .html para denotar cada uno de los diferentes textos del documento, teniendo claridad en la diferenciación de los diferentes elementos del mismo.
- Aplicar los estilos en un documento .css separado del .html.
- Usar los correctos id's y classes en el html para aplicar los estilos deseados desde el .css.
- Hoy en dia existen muchos estilos creados por terceros en formato de plantillas y uso de bootstrap.



#### 7.2 Conclusiones
- Hoy en día prácticamente toda la web se basa en el estandar de HTML5.
- HTML se basa en el uso de etiquetas para denotar y buscar información en la web.
- HTML se combina con el uso de CSS para la creación de sitios web.
- El uso de HTML se fundamenta en la estructuración de una página web, lo cual se asemejaría al esqueleto en el cuerpo humano.
- El uso de CSS se combina con HTML para lograr conseguir resultados estéticos para una mejor presentación de la pagina web. Haciendo el simil con el cuerpo humano, este haría las veces de nuestra piel y la ropa que vestimos.
- Los estilos de CSS se basan en las class e id's asignados en el Html para identificar a que etiquetas debe asignarles que estilos.
- El uso del punto "." en CSS se reserva exclusivamente para referirnos al estilo a asignar a una clase.
- El uso de numeral - almohadilla "#" está reservado para referir se a los id's del html.
- Tener presente que ni html ni css son lenguajes de programación, para las diferentes funcionalidades que tendrá una página web se utiliza una herramienta presente en casi todo web site, la cual es JavaScript (JS), el cual si es un lenguaje de programación.


___
### 8. Referencias
* Developer Mozilla. HTML: Lenguaje de etiquetas de hipertexto. *(s.f.).* https://developer.mozilla.org/es/docs/Web/HTML
* Varangouli E. Lista de tags HTML: hoja de trucos HTML. ¿Qué son y para qué sirven? *(2023).* Recuperado de: https://es.semrush.com/blog/lista-de-html-tags/ 
* Roman J. ¿Que es CSS?. *(s.f.).* Recuperado de: https://lenguajecss.com/css/introduccion/que-es-css/
* Schürmann N. Aprende HTML ahora! curso completo GRATIS desde cero. *(2021).* Recuperado de: https://www.youtube.com/watch?v=MJkdaVFHrto
* Schürmann N. Aprende CSS ahora! curso completo GRATIS desde cero. *(2021).* Recuperado de: https://www.youtube.com/watch?v=wZniZEbPAzk
___
### 9. Tiempo estimado / invertido
El **tiempo invertido para la realización del presente spike fue de aproximadamente 8 horas**, las cuales incluyeron la combinación de teoría junto con la parte práctica para poder dominar los principales conceptos de HTML, entendidos estos desde como es la estructuracion de un documento html (html, head, body, footer, )así como las principales etiquetas para realizar encabezados (h1 a h6), parrafos (p), tablas (table, thead [tr, th], tbody [tr, td]), listas ordenadas (ol [li]) y no ordenadas (ul [li]), hipervínculos (a), inserción de imágenes (img), colocación de negrita (b), letra cursiva (i), linea horizontal (hr), salto de línea (br), pies de pagina (footer).

Enlaces interés:
- Tutorial de HTML:
https://www.youtube.com/watch?v=MJkdaVFHrto
- Tutorial de CSS:
https://www.youtube.com/watch?v=wZniZEbPAzk

___