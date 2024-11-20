# PROYECTO2 - Heladería Backend (Curso Backend con Python - Universidad de los Andes 2024-2)

Este repositorio corresponde al segundo proyecto del curso de Backend con Python, impartido por la Universidad de los Andes en el semestre 2024-2.

### Descripción general
Este proyecto implementa una aplicación web de gestión para una heladería utilizando Flask. El sistema permite manejar la creación de heladerías, sus productos y la venta de estos productos.

### Funcionalidades principales

1. **Creación de Heladería en la Base de Datos:**
   Al ejecutar `flask run`, se inicializa una heladería en la base de datos con productos e ingredientes predeterminados.

2. **Lista de Heladerías:**
   Accediendo a la URL [http://127.0.0.1:5000/](http://127.0.0.1:5000/), se muestra la lista de heladerías almacenadas en la base de datos (por defecto, habrá una heladería).

3. **Menú de la Heladería:**
   En la página de lista de heladerías, al seleccionar una heladería (por ejemplo, con ID `1`), el sistema redirige a [http://127.0.0.1:5000/parlor/1](http://127.0.0.1:5000/parlor/1), donde se muestra el menú de productos disponibles de esa heladería.

4. **Compra de Productos:**
   Al hacer clic en cualquier producto del menú, se realiza la compra de ese producto. La acción se ejecuta a través de la URL [http://127.0.0.1:5000/parlor/1/makeSale/Copa%20Vainilla](http://127.0.0.1:5000/parlor/1/makeSale/Copa%20Vainilla), y se muestra un mensaje de confirmación en la parte superior de la página.

5. **Mejor Producto:**
   En la URL [http://127.0.0.1:5000/parlor/1/bestProduct](http://127.0.0.1:5000/parlor/1/bestProduct), se muestra el nombre del mejor producto de la heladería con el ID especificado (por ejemplo, `1`).


