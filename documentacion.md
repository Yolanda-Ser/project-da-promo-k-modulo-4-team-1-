# Documentación de los Archivos CSV

## Contexto de la Empresa

La empresa "DataTech Solutions" es una compañía líder en el sector de la tecnología y el comercio electrónico. Se dedica a la venta de una amplia gama de productos que incluyen electrónica, ropa, libros, artículos para el hogar y cocina, así como productos deportivos y para actividades al aire libre. Con una base de clientes diversa y en constante crecimiento, DataTech Solutions se esfuerza por ofrecer productos de alta calidad y un excelente servicio al cliente.

Para mejorar sus estrategias de ventas y marketing, la empresa ha recopilado una gran cantidad de datos sobre sus productos, clientes y transacciones de ventas. Estos datos son fundamentales para analizar el comportamiento de los clientes, identificar tendencias de ventas y optimizar el inventario.

## Descripción de los Archivos CSV

### Archivo: `productos.csv`

Este archivo contiene información sobre los productos. Las columnas incluidas son:

- **id_producto**: Identificador único para cada producto (por ejemplo, `P0001`, `P0002`, ...).
- **precio**: Precio del producto, expresado en euros (por ejemplo, `37.80 €`).
- **categoria**: Categoría del producto. Puede ser una de las siguientes: `Electronics`, `Clothing`, `Books`, `Home & Kitchen`, `Sports & Outdoors`.
- **descripcion**: Descripción breve del producto.

### Archivo: `clientes.csv`

Este archivo contiene información sobre los clientes. Las columnas incluidas son:

- **id_cliente**: Identificador único para cada cliente (por ejemplo, `C0001`, `C0002`, ...).
- **nombre**: Nombre del cliente.
- **apellido**: Apellido del cliente.
- **ciudad**: Ciudad y país de residencia del cliente (por ejemplo, `Madrid, España`).

### Archivo: `ventas.csv`

Este archivo contiene información sobre las ventas. Las columnas incluidas son:

- **id_venta**: Identificador de la venta (por ejemplo, `V000001`, `V000002`, ...).
- **id_producto**: Identificador del producto vendido.
- **cantidad**: Cantidad del producto vendido en esa transacción.
- **fecha**: Fecha en la que se realizó la venta.
- **id_cliente**: Identificador del cliente que realizó la compra.


## Uso de los Archivos

Estos archivos están diseñados para ejercicios de análisis y limpieza de datos en Python. Se pueden utilizar para:

- Practicar la carga y manipulación de datos con bibliotecas como `pandas`.
- Realizar análisis de ventas, productos y clientes.
- Limpiar y transformar datos para análisis más profundos.
- Desarrollar modelos de datos para ventas y marketing.


