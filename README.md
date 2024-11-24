# Aplicación de Gestión de Inventario con Kivy



Este proyecto implementa una aplicación sencilla de gestión de inventario utilizando Kivy para la interfaz gráfica y SQLite para la persistencia de datos. La aplicación permite a los usuarios agregar, visualizar, actualizar y eliminar productos de una base de datos local.



## Características principales



*   Interfaz de usuario intuitiva con botones para agregar, actualizar y eliminar productos.

*   Visualización clara de la lista de productos con ID, nombre y cantidad.

*   Popups para la entrada de datos y la confirmación de acciones.

*   Gestión eficiente de la base de datos SQLite para almacenar y recuperar datos.



## Tecnologías utilizadas



*   **Kivy:** Framework de Python para el desarrollo de interfaces gráficas multiplataforma.

*   **SQLite:** Base de datos ligera y embebida, ideal para aplicaciones móviles.

*   **Python:** Lenguaje de programación principal.



## Funciones implementadas



*   **Agregar producto:** Permite agregar un nuevo producto al inventario con su nombre y cantidad. Se utiliza un popup para la entrada de datos.

*   **Visualizar productos:** Muestra una lista de todos los productos en el inventario con su ID, nombre y cantidad. Se utiliza un `GridLayout` dentro de un `ScrollView` para mostrar la lista.

*   **Actualizar producto:** Permite modificar la cantidad de un producto existente en el inventario. Se utiliza un popup para ingresar la nueva cantidad.

*   **Eliminar producto:** Permite eliminar un producto del inventario. Se utiliza un popup para confirmar la eliminación.



## Pasos para ejecutar el proyecto



1.  **Instalar dependencias:** Asegúrate de tener instalado Python y Kivy. Puedes instalar Kivy con el siguiente comando:



    ```bash

    pip install kivy

    ```



2.  **Clonar el repositorio:** Clona este repositorio en tu máquina local.



3.  **Ejecutar la aplicación:** Abre una terminal en la carpeta del proyecto y ejecuta el archivo `main.py`:



    ```bash

    python main.py

    ```



## Estructura del proyecto



*   `main.py`: Archivo principal que contiene la lógica de la aplicación, la definición de la interfaz gráfica y las funciones para interactuar con la base de datos.



## Consideraciones


*   La aplicación utiliza una base de datos SQLite llamada `inventario.db` que se crea automáticamente al ejecutar la aplicación por primera vez.

*   Se implementan popups (`AgregarProductoPopup`, `EditarProductoPopup`, `EliminarProductoPopup`, `ActualizarProductoPopup`) para la interacción con el usuario al agregar, actualizar y eliminar productos.

*   Se utiliza `GridLayout` para mostrar la lista de productos dentro de un `ScrollView` para permitir el desplazamiento si la lista es larga.



## Capturas de pantalla

**Pantalla principal de la aplicación:**

[![PANTALLA-PRINCIPAL-DE-LA-APLICACION.jpg](https://i.postimg.cc/LsTVQ1mK/PANTALLA-PRINCIPAL-DE-LA-APLICACION.jpg)](https://postimg.cc/xkXHcqkt)

En esta captura podemos observar la pantalla principal de la aplicación al iniciar. Se muestra el título "Inventario de Productos" y los encabezados de las columnas para la lista de productos (ID PRODUCTO, NOM PRODUCTO, CANT PRODUCTO). En la parte inferior se encuentran los botones para "Agregar Producto", "Actualizar Producto" y "Eliminar Producto".

**Popup para agregar un producto:**

[![CAPTURA-DOS-AGREGAR-PNG.jpg](https://i.postimg.cc/1tkWFNSk/CAPTURA-DOS-AGREGAR-PNG.jpg)](https://postimg.cc/G8jJwtHK)

Esta captura muestra el popup que aparece al presionar el botón "Agregar Producto". Permite al usuario ingresar el nombre y la cantidad del nuevo producto a través de campos de texto. En este ejemplo, se está agregando el producto "Golf GTI 2024" con una cantidad de 5.

**Mensaje de confirmación al agregar un producto:**

[![TERCERA-CAPTURA-DE-PROGRAMA.jpg](https://i.postimg.cc/XvqPRCg5/TERCERA-CAPTURA-DE-PROGRAMA.jpg)](https://postimg.cc/67szRTg6)

Esta captura muestra el mensaje de confirmación que aparece después de agregar un producto correctamente. En este caso, se confirma que el producto "Golf GTI 2024" se ha agregado al inventario.

**Visualización del producto en la lista:**

[![CUARTA-IMAGEN.jpg](https://i.postimg.cc/kGyQfTLd/CUARTA-IMAGEN.jpg)](https://postimg.cc/MfvfGmWs)

En esta captura se observa que el producto "Golf GTI 2024" se ha agregado correctamente a la lista del inventario con su ID (1) y la cantidad especificada (5).

**Popup para actualizar la cantidad de un producto:**

[![QUINTA-IMAGEN.jpg](https://i.postimg.cc/6p1pCCjb/QUINTA-IMAGEN.jpg)](https://postimg.cc/mPC4s1G7)

Esta captura muestra el popup que se utiliza para actualizar la cantidad de un producto existente. El usuario debe ingresar el ID del producto y la nueva cantidad. En este ejemplo, se está actualizando la cantidad de 5 a 3 del producto con ID 1.

**Mensaje de confirmación al actualizar la cantidad:**

[![SEXTA-IMAGEN.jpg](https://i.postimg.cc/LXp4SPHx/SEXTA-IMAGEN.jpg)](https://postimg.cc/WD5c6hqZ)

Esta captura muestra el mensaje de confirmación que aparece después de actualizar correctamente la cantidad de un producto. Se indica que el producto con ID 1 se ha actualizado correctamente.

**Visualización de la cantidad actualizada en la lista:**

[![SEPTIMA-IMAGEN.jpg](https://i.postimg.cc/25jCZ1JG/SEPTIMA-IMAGEN.jpg)](https://postimg.cc/G4N00mbT)

Esta captura muestra la lista de productos después de actualizar la cantidad del producto con ID 1. Se puede observar que la cantidad se ha actualizado correctamente a 3.

**Popup para eliminar un producto:**

[![OCATAVA-IMAGEN.jpg](https://i.postimg.cc/jSs7zcMr/OCATAVA-IMAGEN.jpg)](https://postimg.cc/jLF2THV8)

Esta captura muestra el popup que se utiliza para eliminar un producto del inventario. Se solicita al usuario que ingrese el ID del producto que desea eliminar. En este ejemplo, se está eliminando el producto con ID 1.

**Confirmación de eliminación:**

[![NOVENA-IMAGEN.jpg](https://i.postimg.cc/sDsMfgmj/NOVENA-IMAGEN.jpg)](https://postimg.cc/9zgmJVsK)

Esta captura muestra el mensaje de confirmación que aparece antes de eliminar un producto. Se pregunta al usuario si está seguro de que quiere eliminar el producto con el ID especificado. Esto ayuda a prevenir eliminaciones accidentales.

**Lista de productos vacía después de la eliminación:**

[![DECIMA-IMAGEN.jpg](https://i.postimg.cc/Hnfp8H8t/DECIMA-IMAGEN.jpg)](https://postimg.cc/zHFm4sjL)

Esta captura muestra la lista de productos después de eliminar el producto con ID 1. Se puede observar que la lista está vacía, lo que indica que el producto se ha eliminado correctamente.


## Video demostrativo




[https://youtu.be/Y3DecVVpc9M](https://youtu.be/Y3DecVVpc9M)



## Autor



Josue Rolando Galvez Corona 



## Licencia



[MIT License](LICENSE)
