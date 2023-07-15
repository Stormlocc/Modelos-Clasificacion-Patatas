# Modelos-Clasificacion-Patatas
Modelos de clasificación (machine learning) para clasificar 20 variedades de papas nativas
**Nombre del dataset:** Variaciones de papas en formato de píxeles

**Descripción:**
Este dataset contiene información de 20 variedades de papas. Cada variedad está nombrada por 2 surcos y cada surco contiene 10 entradas. Cada entrada corresponde a un promedio de 30 imágenes de la misma variedad de tubérculo de papa. La información de las imágenes se almacena en un archivo CSV que contiene los valores de los píxeles en escala de grises.

**Características del dataset:**
- Tamaño de las imágenes: Cada imagen tiene un tamaño de 300x300 píxeles.
- Variedades de papas: El dataset incluye un total de 20 variedades de papas diferentes.
- Estructura del archivo CSV: El archivo CSV tiene 9,001 columnas. Las primeras 9,000 columnas están etiquetadas desde 0 hasta 8,999 y representan los valores de los píxeles de las imágenes. Cada columna contiene un valor entero que representa la intensidad del brillo del píxel en escala de grises, variando entre 0 y 255. La última columna (columna 9,000) contiene la etiqueta de la variedad de papa que identifica el surco y la entrada a la que pertenece la imagen. La etiqueta sigue el formato "SurcoX-EntradaY", donde X es el número del surco (desde 3 hasta 4) y Y es el número de la entrada.
- Etiquetas de surcos y entradas: Cada fila del archivo CSV está etiquetada con el número de surco y entrada correspondiente.
- Total de imágenes: En cada entrada hay mas de 30 imágenes de un tubérculo de papa.
- Valores de los píxeles: Los valores en cada celda del archivo CSV representan la intensidad del brillo del píxel en escala de grises, donde 0 indica un píxel negro y 255 indica un píxel blanco.
> A continuacion un modelo del dataset en descripcion:
