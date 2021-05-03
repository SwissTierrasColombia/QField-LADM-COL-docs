# Interfaz
## Abrir el proyecto

La interfaz inicial de QField contiene dos elementos principales: *Abrir archivo local* y el listado de *Proyectos Recientes*.

<a class="" data-lightbox="Abrir proyecto" href="_static/interfaz/Abrir_proyecto.png" title="Abrir proyecto" data-title="Abrir proyecto"><img src="_static/interfaz/Abrir_proyecto.png" class="align-center" width="800px" height="500px" alt="Abrir proyecto">
</a>

### Abrir archivo local

Mediante este botón es posible acceder a los directorios de almacenamiento del dispositivo móvil, de manera que sea posible seleccionar el proyecto de QGIS a trabajar o el conjunto de datos que se quiere desplegar en QField.

Considerando lo anterior, sólo basta con navegar por la ruta de directorios que el usuario haya definido, y seleccionar el archivo que se desea abrir por medio de la aplicación.

### Proyectos Recientes

Consiste en un acceso rápido de los últimos proyectos de QGIS (.qgs ó .qgz)  o conjunto de datos (*dataset*) que el usuario haya desplegado por medio de la aplicación recientemente.
## Área de trabajo 

El área de trabajo de la aplicación QField se compone básicamente de seis (6) elementos: 

<a class="" data-lightbox="Area de trabajo" href="_static/interfaz/Area_trabajo.png" title="Area de trabajo" data-title="Area de trabajo"><img src="_static/interfaz/Area_trabajo.png" class="align-center" width="800px" height="500px" alt="Area de trabajo">
</a>

### 1. Lienzo

Hace referencia al espacio donde es posible visualizar e interactuar por medio de las herramientas de navegación con la información cargada por el usuario (mapas base, capas geográficas, imágenes, entre otros).

### 2. Botón de ubicación o posicionamiento ![Barra de búsqueda](_static/interfaz/2_ubicacion.png)

Corresponde a un botón que se encuentra en la esquina inferior derecha del lienzo, mediante el cual es posible habilitar o deshabilitar el acceso a la <u>Localización/Ubicación</u> del dispositivo móvil a la aplicación.

Al presionar este botón por al menos tres (3) segundos se despliega un menú que contiene: 

- Tipo de dispositivo (interno o externo) del cual la aplicación obtiene la información de localización.

- Casilla de verificación para habilitar o deshabilitar la opción de posicionamiento.

- Casilla de verificación para "Mostrar información de la posición". Si esta opción está activada, en la parte inferior del lienzo se despliega una ventana con:

  - Coordenada X
  - Coordenada Y
  - Información de Altitud
  - Velocidad
  - Precisión Horizontal
  - Precisión Vertical

  <div class="note">
  <p class="admonition-title">IMPORTANTE</p>
  <p>Estos datos están en función de la precisión del dispositivo del cual se extrae la información de posicionamiento.</p>
  </div>

  - Opción para acceder a la "Configuración de posicionamiento". Como su nombre lo dice, permite acceder a la configuración de QField en lo correspondiente con los ajustes de localización <span style="background:blue"><span style="color:white">ver pestaña configuración</span> </span>.
  - Opción para "Centrar en la posición actual", como herramienta de navegación permite que el lienzo se centre en la ubicación que provee el dispositivo.

### 3. Zoom out ![Barra de búsqueda](_static/interfaz/3_zoom_out.png)

Herramienta de navegación que permite que el usuario modifique la escala de visualización del lienzo reduciendo el detalle de información cargada en el proyecto.

### 4. Zoom in ![Barra de búsqueda](_static/interfaz/4_zoom_in.png)

Herramienta de navegación con la cual es posible que el usuario modifique la escala de visualización del lienzo ampliando el detalle de información que se despliega en la aplicación.  

### 5. Barra de búsqueda ![Barra de búsqueda](_static/interfaz/5_busqueda.png)

Con esta herramienta es posible realizar la búsqueda de registros y atributos sobre la información cargada por el usuario. Para hacer uso de esta función, se requiere previa definición de los campos y capas geográficas sobre las cuales se habilitará esta acción.

### 6. Menú ![Barra de búsqueda](_static/interfaz/6_menu.png)

Botón ubicado en la esquina superior izquierda del área de trabajo de la aplicación, mediante el cual se despliega una ventana con las siguientes opciones:

<a class="" data-lightbox="Menu" href="_static/interfaz/menu.png" title="Menú" data-title="Menú"><img src="_static/interfaz/menu.png" class="align-center" alt="Menú">
</a>

1. Botón incluir icono </span> </span> (Regresar)

   Se trata de la opción para cerrar la ventana que se despliega al hacer click en el botón de menú. 

2. Botón (Configuración)

   Al hacer click en este botón, se despliega un menú con las opciones:

   - Herramientas de medida
   - Imprimir a PDF
   - Abrir proyecto
   - Configuración
   - Message Log
   - Acerca de QField

3. Botón (Modos de trabajo)

   Corresponde al botón con el que el usuario selecciona el modo de trabajo a emplear, estos son: <span style="background:blue"><span style="color:white">Modo digitalización</span> </span> y <span style="background:blue"><span style="color:white">Modo exploración</span> </span>. 

4. Tema de mapa

   Desplegable que permite elegir entre los mapas base que el usuario haya definido previamente.

5. Contenido del proyecto

   Permite visualizar en un listado la información cargada por el usuario al proyecto:

   - Elementos individuales
     - Tablas
     - Capas geográficas
     - Imágenes ráster
   - Grupos

## Configuración

<a class="" data-lightbox="Configuracion" href="_static/interfaz/Configuracion.gif" title="Configuracion" data-title="Configuracion"><img src="_static/interfaz/Configuracion.gif" class="align-center" width="800px" height="500px" alt="Configuracion">
</a>

Esta opción permite acceder a los ajustes de:

- **General**: Corresponde a la configuración de acciones tales como: visualizar de la barra de escala, maximizar el formulario de atributos, navegar a escala fija, usar cámara nativa, activar modo de edición rápida, entre otras.
- **Posicionamiento**: En esta opción es posible configurar el dispositivo del cual se obtiene la información de ubicación, de manera que si se emplea un dispositivo externo, tal como una antena GNSS se puedan incluir variables como la altura de ésta para realizar la compensación correspondiente en la variable Z (altura). Así mismo, en este menú es posible habilitar indicadores asociados al posicionamiento en el área de trabajo.
- **Variables**: En este menú se encuentran definidas algunas variables del sistema, así mismo, allí se pueden añadir variables que el usuario haya definido para emplear en su proyecto.

## Modo visualización ![Modo visualización](_static/interfaz/modo_visualizacion.png)

En este modo es posible explorar la información cargada en el área de trabajo, sin que se modifique ningún tipo de atributo de la misma.

## Modo edición ![Modo edición](_static/interfaz/modo_edicion.png)

Esta opción permite que el usuario pueda crear, modificar o eliminar características -alfanuméricas y/o geográficas- de atributos asociados a la información (tablas y/o capas geográficas) cargada al proyecto.

## Opciones de capas geográficas