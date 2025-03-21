# Día 9

Aquí verás la explicación de el ejercicio realizado para el día número 4 basado en HTML/CSS

## Instalación

Baja los archivos del respositorio con el comando git clone o git pull en la carpeta seleccionada, seguido de esto abre tu editor de código de preferencia y abre la carpeta con los archivos en tu editor de código.

## Explicación archivo HTML

Antes de empezar con la página se utiliza el comando "!" para tener la documentación de html 5, esta documentación también se puede obtener escribiendo "html:5".

Para poder aplicar los estilos de css se utilizó el tag "link" para vincular el archivo css mediante su ruta al archivo index.html, por ejemplo: "link rel="stylesheet" href="./styles/styles.css"".

Dentro del cuerpo principal se utilizó una división con una clase llamada "cuerpo", así la distribución del archivo sería más sencilla al momento de aplicarle los estilos.

Al momento de inesrtar todo el contenido de la página se utilizaron tags "img" cada uno con su respectiva clase y ubicación de la imágen correspondiente.

En el caso de los textos un simple tag "p" que indica parrafos fue suficiente, claramente con su respectiva clase, además de que las lineas separadoras se hicieron con el tag "hr" y las tablas de cada cafe con divisiones "div".

## Explicación archivo CSS

Para la aplicación de los estilos se eligió el color del fondo para el cuerpo de la página con "background-color: black", además de que se aplicaron estilos a cada imágen tales como la distancia entre la imágen y la parte más alta de la página, la distancia desde la izquierda, la altura de la imágen y el ancho de la imágen, todo se uso mediante la clase declarada en el index.html de cada imágen.

Para la letra se insertaron 3 estilos de fuente con el comando "@font-face" en css y así poder dar mejor manejo a la letra de la página.

Para los estilos de los textos se modificó el tamaño de letra y la fuente personalizada que insertamos con el comando "@font-face".

En la parte de las "tablas" (div) se modificó el ancho, largo, posición y borde con los estilos de css.