# 00018824_practica1_secci-n1

## Sección de preguntas

### Ejercicio 2, pregunta 7: ¿Hay cambios en la visualización del sitio web? Si la respuesta es negativa, piense un momento ¿Para qué sirven las etiquetas meta? 

Las etiquetas <meta> generalmente no producen cambios visibles en la página web porque están diseñadas para proporcionar metadatos, no contenido visual.

### Ejercicio 3, pregunta 9: ¿Qué pasaría si la imagen esta guardada en la misma carpeta de la página web? ¿Y si está en una carpeta superior?

Si la imagen está guardada en la misma carpeta de la página web se tendría que cambiar la linea "<img src="imagenes/imagen.jpg" alt="Imagen">" a /*"<img src="imagen.jpg" alt="Imagen">"*/ ya que src hace referencia a un recurso dentro de la carpeta en la que se está trabajando, por lo que si el archivo está directamente en la misma carpeta solo se coloca el nombre del archivo, mientras que para adentrarse a carpetas dentro de carpetas se colocan las plecas, por ejemplo src=imagenes/UCALogos/BlancoNegro/logoUCA.jpg, mientras que, si está guardada en una carpeta superior se escribiría algo así: <img src="../imagen.jpg" alt="Imagen"> "../" significa subir de nivel en la estructura de carpetas.

### Ejercicio 3, pregunta 10: ¿Cómo se consigue que el último enlace se abra en una nueva ventana?

target="_blank" le dice al navegador que abra el enlace en una nueva pestaña/ventana.

### Ejercicio final, pregunta 6: ¿El resultado obtenido es similar al esquema HTML mostrado en la figura de la introducción teórica para elementos semánticos? ¿Por qué? Razónelo y/o consulte con su instructor.

La disposición de los elementos no es similar a la presentada en el apartado, al visualizar la página se ve todo apilado de manera vertical, esto es debido a que HTML proporciona la estructura semántica, pero CSS es responsable de la presentación visual (CSS que no ha sido aplicado en el ejercicio).
