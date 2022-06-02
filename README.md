# Práctica 1
## Creación básica de página web en WordPress

![Logo WordPress](https://github.com/AngelAlbertoCT/Creaci-n-b-sica-de-p-gina-web-en-WordPress/blob/main/Imagenes/WordPress_blue_logo.svg.png)

En esta práctica se aprende a crear una página Web utilizando WordPress. Se utilizarán las herramientas que nos proporciona Azure desde la página http://portal.azure.com/ .

Lo primero será ingresar al [portal de Azure](http://portal.azure.com/) con nuestro usuario y contraseña y lo primero que veremos será nuestra pantalla principal del portal. 

![Pantalla inicio](https://github.com/AngelAlbertoCT/Creaci-n-b-sica-de-p-gina-web-en-WordPress/blob/main/Imagenes/Imagen1.png)

Ahora tenemos que dirigirnos al **marketplace** y lo podemos hacer de dos maneras. La primera es buscarlo desde la barra de busqueda que se encuentra en la parte superior de nuestra página, o bien, seleccionar el icono que ya nos aparece en nuestra pantalla principal. 

![imgmktplc](https://github.com/AngelAlbertoCT/Creaci-n-b-sica-de-p-gina-web-en-WordPress/blob/main/Imagenes/Imagen2.png)
![imgmktplc](https://github.com/AngelAlbertoCT/Creaci-n-b-sica-de-p-gina-web-en-WordPress/blob/main/Imagenes/Imagen3.png)

Ya dentro, en la barra de busqueda del propio marketplace, vamos a buscar **WordPress** y nos apareceran variadas aplicaciones, pero para esta ocasión se utilizará la primera opción disponible.

![imgmktplc](https://github.com/AngelAlbertoCT/Creaci-n-b-sica-de-p-gina-web-en-WordPress/blob/main/Imagenes/Imagen4.png)

Después se va a seleccionar la opción **crear**

![imgmktplc](https://github.com/AngelAlbertoCT/Creaci-n-b-sica-de-p-gina-web-en-WordPress/blob/main/Imagenes/Imagen5.png)

Posteriormente tenemos que realizar la configuración correspondiente para poder terminar de crear la página inicial.

![imgmktplc](https://github.com/AngelAlbertoCT/Creaci-n-b-sica-de-p-gina-web-en-WordPress/blob/main/Imagenes/Imagen6.png)

Los requisitos mínimos que se necesitan para crear un recurso en Azure es:
* Una suscripción en Azure
* Un grupo de recursos
* Una región
* Un nombre para el recurso 

Sabiendo esto, podemos continuar con la creación de nuestra página web en la ventana **Creación de Wordpress en App Service**. Aquí es donde llenaremos los requisitos mínimos anteriormente mencionados. Para seleccionar la carpeta de recursos podemos seleccionar alguna (si ya está creada anteriormente) o crear un nuevo grupo desde la opción **Crear nuevo**. Ahí debemos de nombrar nuestro grupo de recursos. En este caso la nombraremos como **Practica_1**.

![imgmktplc](https://github.com/AngelAlbertoCT/Creaci-n-b-sica-de-p-gina-web-en-WordPress/blob/main/Imagenes/Imagen7.png)

Para el apartado **Región** es importante tener en consideración en que parte del mundo se van a encontrar nuestros usuarios. En este caso, lo más recomendable por la zona en la que nos encontramos (México), podemos seleccionar **South Central US** o **Central US**. Para esta práctica se seleccionará South Central US. 

Ahora en el apartado **Detalles de la instancia** colocaremos el nombre con el que se va a asociar la dirección web. Para esta práctica colocaremos **azure-practica-1**.

El formulario nos quedará algo similar a lo siguiente:

![imgmktplc](https://github.com/AngelAlbertoCT/Creaci-n-b-sica-de-p-gina-web-en-WordPress/blob/main/Imagenes/Imagen8.png)

Teniendo esto listo, pasamos a revisar el apartado de **Etiquetas**. Las etiquetas nos pueden servir para 3 cosas:
* Sacar reportes de costos
* Cumplir normativas de seguridad
* Para brindar más información a otros usuarios ajenos a Azure

Por ejemplo, podemos crear una etiqueta donde se indique que es importante que los procesos no se detengan bajo ninguna circunstancia. Para esto podemos darle un nombre a la etiqueta y una pequeña descripción o palabra clave para que se pueda entender mejor el motivo de la etiqueta. 

**Nota: las etiquetas pueden ser omitidas sin ningún inconveniente, pero para caso práctico se realizará la creación de una.**

En el apartado de **Nombre** colocaremos **Impact** y en **Valor** se colocará **Critical**. Nos quedará lo siguiente:

![imgmktplc](https://github.com/AngelAlbertoCT/Creaci-n-b-sica-de-p-gina-web-en-WordPress/blob/main/Imagenes/Imagen9.png)

Posteriormente, en la pestaña **Revisar y crear** se corroborará y se visualizará mayor información sobre nuestra página web. 

![imgmktplc](https://github.com/AngelAlbertoCT/Creaci-n-b-sica-de-p-gina-web-en-WordPress/blob/main/Imagenes/Imagen10.png)
![imgmktplc](https://github.com/AngelAlbertoCT/Creaci-n-b-sica-de-p-gina-web-en-WordPress/blob/main/Imagenes/Imagen11.png)

Para continuar y finalizar este apartado, presionamos el botón **Crear** y se realizará el proceso correspondiente. Esto puede demorar algunos minutos. Mientras se realizan estos procesos, nos aparecerá una pantalla como la siguiente:

![imgmktplc](https://github.com/AngelAlbertoCT/Creaci-n-b-sica-de-p-gina-web-en-WordPress/blob/main/Imagenes/Imagen12.png)

Cuando termine todo el proceso, aparecerá la siguiente ventana:

![imgmktplc](https://github.com/AngelAlbertoCT/Creaci-n-b-sica-de-p-gina-web-en-WordPress/blob/main/Imagenes/Imagen13.png)

Seleccionaremos el botón **Ir al recurso** y nos aparecerá la siguiente ventana:

![imgmktplc](https://github.com/AngelAlbertoCT/Creaci-n-b-sica-de-p-gina-web-en-WordPress/blob/main/Imagenes/Imagen14.png)

Para poder visualizar nuestra página ya creada, podemos dar click en el enlace que aparece en el apartado **URL** en la parte superior derecha de nuestra página.

Se nos mostrará la página de Wordpress donde se nos solicitará seleccionar un idioma. Para nuestro caso seleccionamos **Español de México**

![imgmktplc](https://github.com/AngelAlbertoCT/Creaci-n-b-sica-de-p-gina-web-en-WordPress/blob/main/Imagenes/Imagen15.png)

Posteriormente no aparecerá el siguiente formulario:

![imgmktplc](https://github.com/AngelAlbertoCT/Creaci-n-b-sica-de-p-gina-web-en-WordPress/blob/main/Imagenes/Imagen16.png)

Para el apartado de **Titulo del sitio** debemos colocarle el nombre correspondiente que queremos que nuestra página tenga.
En **Nombre de usuario** y **Contraseña** debemos colocar respectivamente aquellos que se utilizarán para que se pueda realizar la administración de la página. 
En la casilla **Visibilidad en los motores de búsqueda** es importante tener en cuenta que, si la casilla está desmarcada, el buscador realizará la busqueda correspondiente de nuestra página y pasará lo contrario si está marcada. Para nuestra práctica dejaremos la casilla marcada. Al concluir con el llenado del fórmulario, vamos a dar click en **Instalar WordPress**. 

Después nos aparecerá que WordPress quedó configurado correctamente y podemos acceder a nuestra página a traves del enlace que creamos. Para esta práctica el enlace es https://azure-practica-1.azurewebsites.net/. Se nos mostrará la siguiente pantalla:

![imgmktplc](https://github.com/AngelAlbertoCT/Creaci-n-b-sica-de-p-gina-web-en-WordPress/blob/main/Imagenes/Imagen17.png)

Para poder entrar a la configuración de la página debemos agregar **/wp-admin** al final de nuestro enlace que nos manda hacia la página. No direccionará a la siguiente pantalla:

![imgmktplc](https://github.com/AngelAlbertoCT/Creaci-n-b-sica-de-p-gina-web-en-WordPress/blob/main/Imagenes/Imagen18.png)

Aquí debemos ingresar el nombre de usuario o correo electrónico y la contraseña que se ingresó en los últimos pasos respectivamente. Al hacer esto ingresaremos a la pantalla donde podemos realizar todos los cambios y configuraciones correspondientes de nuestra recien creada página web. 

![imgmktplc](https://github.com/AngelAlbertoCT/Creaci-n-b-sica-de-p-gina-web-en-WordPress/blob/main/Imagenes/Imagen19.png)

Y así es como podemos apoyarnos de Azure para poder crear una página web utilizando WordPress. Como se pudo observar, son pasos sencillos los que se tienen que seguir y toma poco tiempo el proceso de creación.

