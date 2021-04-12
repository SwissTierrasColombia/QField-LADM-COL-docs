# Recolección de datos

## Flujo de captura para predios nuevos (Formación)

## Flujo de captura para predios existentes (Actualización)

## Formulario de puntos 

Los formularios de puntos se encuentran divididos en tres (3) clases, estas son: Lindero, Control y Levantamiento. Al interior de los formularios encontraremos que los siguientes atributos se encuentras en las tres (3) clases de puntos: 

- Posición interpolación 
- Punto tipo 
- Método de producción 

Además es importante resaltar, que cada una de estas clases facilita el levantamiento en campo de un tipo de información específica, el punto lindero es utilizado, como su nombre lo indica, para el levantamiento de la información de los linderos asociados al predio que se va a registrar, por otro lado los puntos de control, facilitan el levantamiento de puntos materializados o con un nivel de precisión de mayor calidad en el momento de captura de los linderos asociados al predio, por último se encuentran los puntos de levantamiento que facilitan la recolección de las unidades de construcción en el momento de captura. 

### Lindero 

Representación de la captura en campo de un punto lindero

<a class="" data-lightbox="Punto lindero" href="_static/recoleccion_datos/punto_lindero.gif" title="Punto lindero" data-title="Punto lindero"><img src="_static/recoleccion_datos/punto_lindero.gif" class="align-center" width="800px" height="500px" alt="Punto lindero">
</a>
### Control 

Representación de la captura en campo de un punto control

<a class="" data-lightbox="Punto control" href="_static/recoleccion_datos/punto_control.gif" title="Punto control" data-title="Punto control"><img src="_static/recoleccion_datos/punto_control.gif" class="align-center" width="800px" height="500px" alt="Punto control">
</a>
### Levantamiento

Representación de la captura en campo de un punto levantamiento

<a class="" data-lightbox="Punto levantamiento" href="_static/recoleccion_datos/punto_levantamiento.gif" title="Punto levantamiento" data-title="Punto levantamiento"><img src="_static/recoleccion_datos/punto_levantamiento.gif" class="align-center" width="800px" height="500px" alt="Punto levantamiento">
</a>
## Formulario de predio

El formulario de predio cuenta con una configuración basada en secciones para facilitar la captura de los diferentes componentes tanto alfanuméricos como geográficos. 

Este formulario se encuentra dividido en 8 secciones que se describirán a continuación.

### 1 - Información básica

Esta sección facilita la identificación de variables y características generales del predio como su localización e información del suelo, además es posible desde esta sección generar información geográfica asociada al predio, como lo son las direcciones del predio. 

<a class="" data-lightbox="Información Básica" href="_static/recoleccion_datos/Informacion_basica.png" title="Información Básica" data-title="Información Básica"><img src="_static/recoleccion_datos/Informacion_basica.png" class="align-center" width="800px" height="500px" alt="Información Básica">
</a>

### 2 - Información del predio

La sección de información del predio es una de las más largas del formulario y contempla el diligenciamiento de información alfanumérica relacionada a datos catastrales, datos registrales y la condición del predio. Dependiendo de cómo se diligencie este formulario, se habilitarán diferentes opciones relacionadas a los campos definidos anteriormente.

<a class="" data-lightbox="Información del predio" href="_static/recoleccion_datos/Info_predio.gif" title="Información del predio" data-title="Información del predio"><img src="_static/recoleccion_datos/Info_predio.gif" class="align-center" width="800px" height="500px" alt="Información del predio">
</a>

### 3 - Terreno

La tercera sección corresponde al formulario de terreno, esta tiene un componente geográfico, en donde se adquiere la geometría del terreno asociado al predio y se almacena la información asociada a ese terreno.

<a class="" data-lightbox="Terreno" href="_static/recoleccion_datos/Terreno.gif" title="Terreno" data-title="Terreno"><img src="_static/recoleccion_datos/Terreno.gif" class="align-center" width="800px" height="500px" alt="Terreno">
</a>

### 4 - Derechos

La cuarta sección corresponde a los derechos, en esta es posible adicionar uno o varios interesados o restricciones asociados al predio.

<a class="" data-lightbox="Derechos" href="_static/recoleccion_datos/Derechos.gif" title="Derechos" data-title="Derechos"><img src="_static/recoleccion_datos/Derechos.gif" class="align-center" width="800px" height="500px" alt="Derechos">
</a>

#### Interesados

Dentro del formulario de interesado, es posible agregar un nuevo interesado con su respectivo formulario o seleccionar uno ya existente dentro de la base de datos, también se agrega información asociada al derecho y una o varias fuentes.

##### Fuentes

Las fuentes permiten adicionar un adjunto a partir de la toma de una fotografía y el diligenciamiento de los diferentes atributos al interior del formulario. 
#### Restricciones del predio

El formulario de restricciones es bastante sencillo, ya que en este se agrega el tipo de servidumbre asociada al predio. 

<a class="" data-lightbox="Restricciones" href="_static/recoleccion_datos/Restricciones.gif" title="Restricciones" data-title="Restricciones"><img src="_static/recoleccion_datos/Restricciones.gif" class="align-center" width="800px" height="500px" alt="Restricciones">
</a>

### 5 - Construcciones

Esta sección facilita la creación de una o varias construcciones, el formulario está compuesto por dos pestañas, la primera que es información alfanumérica asociada a la construcción y la segunda permite la creación de una o varias unidades de construcción geográficas.
#### Unidades de construcción

El formulario de las unidades de construcción varía según las características que se seleccionen a lo largo del formulario, en este es posible agregar diferentes tipos de calificaciones de construcción, no convencionales y convencionales, siendo estas últimas las que tienen un formulario aparte para asociarlo a cada unidad de construcción.

### 6 - Ofertas de mercado inmobiliario

La sección de ofertas de mercado inmobiliario facilita agregar una o varias ofertas inmobiliarias asociadas al mismo predio, dentro de este formulario se solicitan la información del tipo de oferta, el valor pedido, el valor negociado, la fecha de captura de la oferta, el tiempo de la oferta en meses, el nombre del oferente y el teléfono de contacto del oferente, variables obligatorias para la captura de este formulario.

<a class="" data-lightbox="Ofertas de mercado inmobiliario" href="_static/recoleccion_datos/Ofertas_MI.gif" title="Ofertas de mercado inmobiliario" data-title="Ofertas de mercado inmobiliario"><img src="_static/recoleccion_datos/Ofertas_MI.gif" class="align-center" width="800px" height="500px" alt="Ofertas de mercado inmobiliario">
</a>

### 7 - Resultado de la visita 

En la sección de resultado visita, como su nombre lo indica, se recopila la información relacionada a la persona que atendió la visita y su relación con el predio.

### 8 - Observaciones

Esta es la última sección de la documentación y tiene por objetivo permitirle al reconocedor agregar las observaciones o novedades obtenidas en campo.

<a class="" data-lightbox="Observaciones" href="_static/recoleccion_datos/Observaciones.png" title="Observaciones" data-title="Observaciones"><img src="_static/recoleccion_datos/Observaciones.png" class="align-center" width="800px" height="500px" alt="Observaciones">
</a>