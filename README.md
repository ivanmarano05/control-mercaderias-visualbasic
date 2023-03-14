# control-mercaderias-visualbasic
Programa destinado al control de mercaderías realizado en Visual Basic a través de Visual Studio.

El mismo controlará movimientos de artículos que estarán asociados a agrupaciones y podrán ser parte de diferentes tipos (compra, venta, etc).

DISEÑO

El programa está compuesto de los siguientes formularios:

- Principal: Será el principal del programa, desde el cual se podrá acceder a los distintos formularios ya sea por los botones de la pantalla o por la barra de navegación.
- Agrupaciones: Se podrá agregar, modificar o eliminar cualquier agrupación completando con su nombre. Si existe alguna agrupación con un artículo asociado, la misma no se podrá eliminar.
- Artículos: Se podrá agregar, modificar o eliminar cualquier artículo completando con su nombre, agrupación y precio.
- Tipos de Movimientos: Se podrá agregar, modificar o eliminar cualquier tipo de movimiento completando con su nombre y su tipo (entrada o salida).
- Búsqueda Agrupaciones: Muestra todas las agrupaciones existentes además de un cuadro de texto que servirá para búsqueda. Este formulario es únicamente accesible desde el formulario "Agrupaciones".
- Búsqueda Artículos: Muestra todos los artículos existentes además de un cuadro de texto que servirá para búsqueda. Este formulario es únicamente accesible desde el formulario "Artículos".
- Búsqueda Tipo de Movimientos: Muestra todos los tipos de movimientos existentes además de un cuadro de texto que servirá para búsqueda. Este formulario es únicamente accesible desde el formulario "Tipos de Movimientos".
- Movimientos de Cantidades: Se podrá agregar un movimiento de cantidad completando con el tipo de movimiento, el artículo (el cual mostrará su precio), la fecha, la cantidad y una observación.
- Búsqueda Movimientos de Cantidades: Muestra todos los movimientos de cantidades existentes además de un cuadro de texto que servirá para búsqueda y un botón para ver la observación de los mismos. Este formulario es únicamente accesible desde el formulario "Movimientos de Cantidades".
- Informes: Muestra los informes de los distintos artículos (fecha, tipo de movimiento, cantidad de entrada, cantidad de salida, saldo) además de un botón para ver la observación de los mismos.
- Observación: Muestra las observaciones del artículo seleccionado mediante el botón "Ver Observacion" de los formularios "Búsqueda Movimientos de Cantidades" e "Informes".

FUNCIONALIDAD

La conexión con la base de datos se realiza mediante un módulo con variables SQLConnection y un servidor propio.

En aquel módulo se realizaron todos los métodos relacionados con las funciones que ofrecen los diferentes formularios.
