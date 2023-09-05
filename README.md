##Bienvenido al repositorio para ejecutar el proyecto final del alumno Pablo Emmanuel Pichardo Román de MTI/UPEMOR

#### Introducción

El proyecto está implementado en el framework de desarrollo web de código abierto Django, que es escrito en Python y se basa en el modelo vista-controlador.

Este proyecto final consiste en  desplegar una página web que brinda servicios especializados en el sector energía y su característica principal; **La venta de productos online.**

El sistema cuenta con una sección de "carrito de compras", que tiene la capacidad de agregar, restar y eliminar elementos. Los Productos están segmentados por categorías, mismas que se pueden editar en el panel de administración con el que cuenta django. Al contar con un sistema ordenado de pedidos, el usuario puede almacenar su carrito de compras en cada inicio de sesión. Al terminar de seleccionar sus compras, la confirmación del pedido se envía directamente al correo electrónico registrado por el usuario.

Adicionalmente, el carrito de compras solo está habilitado para usuarios logeados. Aquellos usuarios que no estén autenticados no podrán hacer ningún proceso de compra.

El sistema cuenta también con un bloque de "Blog", el cuál despliega las noticias por categorías que el administrador desea mostrar a los usuarios. En este caso, la intención es agregar las ctaegorías correspondientes a las **"Energías Renovables"**.

Es un sistema muy completo de despliegue de servicios/noticias y para hacer compras online.

**Instalación:**

-  Crear una carpeta en el ordenador en la ubicación en donde se desee instalar el proyecto

- Dentro de la carpeta, inicializaremos el Git Bash.

- Introducir el siguiente comando para clonar el proyecto de GitHub:

**git clone https://github.com/Pichardozion/Proyecto_final.git**

- Para instalar las librerías necesarias basta con ejecutar el siguiente comando:

**pip  install -r requirements.txt **

- Se deben realizar las migraciones:

**python manage.py makemigrations
python manage.py migrate**

- Por último basta con arrancar el proyecto:

**python manage.py runserver**