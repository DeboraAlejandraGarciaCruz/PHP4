# Sistema de Pedidos para Bob's Auto hParts
Este proyecto es un sistema de pedidos para una tienda de autopartes, *Bob's Auto Parts*, desarrollado utilizando HTML y PHP.
El sistema permite a los usuarios realizar pedidos, visualizar los resultados y almacenar los pedidos realizados en un
archivo de texto para su posterior revisión.

## Estructura del Proyecto
El proyecto consta de los siguientes archivos:

*.DS_Store*: Archivo de sistema que se genera automáticamente en macOS (puede ser ignorado o eliminado si no es necesario).

*README.md*: Documento con la descripción del proyecto y detalles de uso.

*orderform.html*: Formulario que permite a los usuarios ingresar sus pedidos de productos.

*processorder.php*: Archivo PHP que procesa los pedidos, calcula el total y muestra un resumen de la orden realizada.

*vieworders.php*: Muestra el detalle de los pedidos realizados y almacenados en el archivo de texto para revisión.

## Funcionalidades

- *Realizar Pedido*: Los clientes pueden seleccionar productos como llantas, botellas de aceite y bujías, y hacer un pedido
   utilizando el formulario en orderform.html.

  - *Procesamiento de Pedido*: El archivo processorder.php maneja la lógica del pedido, calcula los totales y genera una
   respuesta con el resumen del pedido

   - *Visualización de Pedidos*: A través de vieworders.php, se pueden consultar todos los pedidos almacenados en el archivo.

- *Almacenamiento de Pedido*: Los pedidos realizados se almacenan en un archivo de texto ubicado en el servidor para su
  posterior revisión.

  ## Cómo Usar el Sistema
Descarga o clona el repositorio* en tu servidor local.

Asegúrate de tener configurado un entorno de servidor web con soporte para PHP (como XAMPP o WAMP).

Coloca los archivos del proyecto en la carpeta del servidor (usualmente htdocs para XAMPP).

Navega a orderform.html en tu navegador para realizar un pedido.

Completa el formulario con la cantidad de productos y la dirección de envío.

Al enviar el formulario, el archivo processorder.php procesará el pedido y lo guardará en un archivo de texto.

 Para ver todos los pedidos realizados, abre vieworders.php en el navegador.

 ## Requisitos

 *PHP*: El servidor debe tener PHP instalado y configurado.
