<h1 align="center">HOTEL ALURA</h1>

<p> Se trata de una aplicación de escritorio que se conecta a una base de datos que permite registrar huéspedes, realizar reservas, buscar la información de huéspedes y/o reservas y actualizar o eliminar la información de la base de datos. </p>

<p>La aplicación se realizó con java, en la base de datos se trabajó con MySQL</p>

<h2>Funcionamiento del programa</h2>

<p>Al ingresar en el menú principal está la opción de iniciar sesión. Por defecto hay 2 usuarios, que son almacenados en una base de datos, los username son "0" y "admin" y la contraseña es "admin".</p>

<p>Una vez dentro del sistema, el usuario puede realizar una reserva o la búsqueda de las reservas previamente realizadas. Si decide realizar una nueva reserva, aparece una ventana emergente donde se solicitan los datos para registrar al huesped. Una vez registrado vuelve al menú de de búsqueda y reserva.</p>

<p>En el menú de búsqueda existen 3 métodos, al dejar en blanco se seleccionan todos los registros de las tablas de huespedes y de reservas. Al ingresar un valor numérico se buscará el número de reserva que coincida y el tercer método es ingresar el apellido (String) del huésped.</p>

<p>En el campo de búsqueda se pueden realizar operaciones de edición y de eliminación de registros. Para modificar un registro se selecciona sobre la tabla, se modifica al valor deseado y se oprime el botón modificar. Para eliminar un registro, se selecciona la fila correspondiente y se oprime el botón eliminar.</p>

<h2>Acceso al proyecto</h2>

<p>Para este proyecto se utilizó IDE Eclipse, para descargar el proyecto se puede realizar fetch en Github y abrirlo en un servidor local, o se puede descargar el proyecto en formato zip. Es necesario importar la librería JCalendar, para esto vamos a Eclipse

<ul>Clic derecho en el proyecto</ul>
<ul>Build path</ul>
<ul>Configure build path</ul>
<ul>Pestaña libraries</ul>
<ul>Add libraries</ul>
<ul>Buscar el archivo .jar de instalación de la librería</ul>
<ul>Aplicar y cerrar</ul>
</p>

<h2>Tecnologías utilizadas</h2>

<p>Para este proyecto se utilizó el lenguaje de programación Java, la interfaz JDBC, el IDE utilizado fue Eclipse. Los ejemplos de bases de datos se crearon en MySQL. Además de la librería estándar de Java se usó la librería JCalendar para mejorar la selección de fechas</p>

<p>Se utilizaron patrones de diseño MVC (Model-View-Controller), adicionalmente se  DAO (Data Access Object) y FactoryMethod</p>

<h2>Autores</h2>

<ul>El view fue desarrollado por el equipo de Alura, quien además suministró la estructura general del programa.</ul>
<ul>La parte back-end, lógica de las funciones y conexión a base de datos, fue realizada por Nestor Daniel Bayona Espitia.</ul>





