# Recomendaciones para el uso de imágenes ráster

1. La información Raster en QField es unicamente de visualización y no de procesamiento.
2. Se sugiere 3 bandas es suficiente para la imagen ráster, máximo 4 en caso de incluir una banda alfa o de transparencia.
3. No se cuenta con un tamaño máximo de pixel, pero es necesario tener presente que este tamaño tiene un gran impacto en el tamaño de la imagen y la velocidad con la que la imagen carga en el dispositivo móvil.
4. Para renderizar, un requisito es crear los piramidales de la imagen para que no sea necesario leer el archivo completo por el dispositivo móvil, esto afectara el rendimiento del dispositivo y la batería. Por lo tanto, cualquier dato ráster debe venir con piramidales.
5. La compresión de archivos es deseable debido al almacenamiento limitado en los dispositivos. JPEG2K, JPEG o WEBP son buenas opciones. 
6. En caso de querer tener toda la configuración de compresión al interior de las imágenes, es posible usar la configuración COG, la cual ya viene con todos los requisitos necesarios para mejorar el funcionamiento de las imágenes en QField. 

   `gdal_translate.exe -of COG -co COMPRESS=WEBP source.tif destination.tif`