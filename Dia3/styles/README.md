## Explicación archivo CSS

Lo primero que se utilizó en el archivo fue la modificación del tag "body" para ajustar de mejor manera como se visualizaría el archivo:
    
"body {
display: flex;
justify-content: center;
align-items: center;
}"

En este caso el display: flex lo que hizo fue que el cuerpo del archivo html se distribuyera de mejor forma y gracias a eso se le pudo dar un mejor manejo, el justifý-content y align-items sirvieron para alinear el contenido horizontalmente y verticalmente respectivamente al centro como índica la orden.

Despues al nombre de la división que se creó en el archivo html se utilizó para la creación de bordes junto a los pixeles máximo que se podría expandir en la parte horizontal.

En el tag "table" se asignó la clase cuerpo que se utilizó para darle una margen de 20 pixeles y que no esté pegada a los bordes.

En el caso de "td" se asignó un padding de 20 pixeles y se declaró que la información dentro de las tablas se alineará a la parte de arriba de estas mismas.

Para la columna 1 al ser la única que utilizó imágenes se creó la clase "izquierda" la cúal me alinea los objetos al centro con la función justify-content y align items.

Los estilos para las clases medio, derecha e izquierda1 son los mismos, se añaden bordes y se centra el contenido.
    "border: 5px solid black;
    text-align: center;"

En el caso de los estilos para imágenes se utilizaron dos en lugar de uno porque una imágen debe ser circular, entonces si utilizara el mismo estilo para ambas las dos me quedarian circular y eso no se quiere, por eso se utilizaron dos, la única diferencia entre los dos estilos es la siguiente:
    "border-radius: 50%;"

Y por último en los estilos para los párrafos nuevamente utilicé dos, en este caso porque necesitaba que algunos párrafos me quedaran en formato justificado en lugar de formato centrado, por ese motivo se realizaron dos clases en lugar de una, la principal diferencia es la siguiente:
    "1. text-align: cener;"
    "2. text-align: justify;"