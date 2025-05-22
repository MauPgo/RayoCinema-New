1. Título: RayoCinema, Descripción: Es un sitio de peliculas y series que contiene los títulos de todas tus plataformas favoritas, Objetivo: Implementación de la BD en el hub de entretenimiento y la implementación del lazyloading.

2. Pedro Mauricio Godinez Ortiz

3. Screenshots:
<img width="1438" alt="principal" src="https://github.com/user-attachments/assets/9a2ab380-f8e6-42b3-9f9b-df8b30c979f8" />
<img width="1438" alt="login" src="https://github.com/user-attachments/assets/03a69902-21e4-4b86-92d7-b50c1df294af" />
<img width="1438" alt="home" src="https://github.com/user-attachments/assets/69f29e66-68d6-45a4-92d6-75330504cdc7" />
<img width="1438" alt="detalle" src="https://github.com/user-attachments/assets/4b7b7b2b-8f5c-4a9e-91a7-5ed04d70deb0" />
<img width="1438" alt="favoritos" src="https://github.com/user-attachments/assets/4345df0e-5145-4b34-a888-f61c0f5d3ceb" />

4. Como utilizar el sitio: una vez descargado el repositorio deberas ingresar a la carpeta del proyecto mediante la terminal, ingresar a la carpeta de frontend y después deberás iniciar el servidor de desarrollo local con el comendo ng serve para que te permita ver el proyecto, una vez ejecutado el comando se deberá desplegar el url que te arroja la terminal (ejemplo: http://localhost:4200/), una vez que ya te cargó el proyecto te mostrará el archivo principal.html ahí te mostrará un vistazo previo al sitio, para ingresar deberás dar click en iniciar sesión para dirigirte al login, en el login introducirás tus datos, solo hay un usuario registrado así que si pones otros datos te dará error si deseas ingresar al sitio para pruebas puedes introducir el correo (mau@gmail.com) y la contraseña (mau) al dar click en iniciar sesión te redigirá a la pantalla principal dónde estan todos los títulos disponibles, si das click en ver te despliegará a una página donde te mostrará una algunos detalles del título, en la pestaña de favoritos se muestran los títulos que marcaste como favoritos, en la pestaña de series se muestran solo las series disponibles así como en la pestaña de películas y en cada pestaña encontrarás un botón para cerrar sesión que te redirigirá al login, eso es para levantar el frontend y para el back te diriges a la carpeta de backend y corres el comando dotnet run para levantar el servidor (no deberías tener problema si utilizas windows ya que utiliza autenticación integrada de Windows pero si usas mac deberas modificar el appsettings.json y añadir el server, user y password para poder realizar la conexión)y abrir http://localhost:5250/swagger/index.html para visualizar el API y conectar el frontend con el backend.

5. Mockup:
<img width="555" alt="Mockup" src="https://github.com/user-attachments/assets/2f8af2c0-1c3e-4683-a8e1-9697b95163fc" />


6.Dependencias o bibliotecas utilizadas: @angular/animations	18.2.13, @angular/common	18.2.13, @angular/compiler	18.2.13, @angular/core	18.2.13, @angular/forms	18.2.13, @angular/platform-browser	18.2.13, @angular/platform-browser-dynamic	18.2.13, @angular/router	18.2.13, @fortawesome/fontawesome-free	^6.7.2, bootstrap	^5.3.6, rxjs	^7.5.7, tslib	^2.6.2, zone.js	~0.14.10, @angular-devkit/build-angular	18.2.7, @angular/cli	18.2.7, @angular/compiler-cli	18.2.13, typescript	5.4.5

7. Como lo hice: Una vez terminado de revisar y corregir código procedí a definir que tablas podría implementar por ahora, posteriormente realicé el diagrama e hice las instalaciones necesarias para levantar mi servidor y crear la BD con sus tablas y relación para posteriormente conectar la BD con mi login e implementar el lazy loading en las routes.
   
8. Reporte de Code Coverage y reporte de testing:
<img width="1440" alt="test coverage" src="https://github.com/user-attachments/assets/fd5916ad-b5bc-48e2-b6bb-717ca7f3aba6" />
<img width="1440" alt="reporte de test" src="https://github.com/user-attachments/assets/a4abccd0-fb5b-40ca-aff0-06d8cc281e66" />

9. Diagrama BD:
<img width="516" alt="diagrama BD" src="https://github.com/user-attachments/assets/0baae6b6-d242-411a-a453-020817f1550a" />

10. Problemas conocidos: Al usar mac me enfrente al problema de la compatibilidad de programas, por lo cual tuve que comenzar a utilizar docker y azure data studio para poder hacer mi BD y mi server, al igual que la incompatibilidad de versiones de algunas librerias en mi proyecto lo cual me llevo algo de tiempo para corregir y que todo estuviera bien y lograr que se comunicaran mi BD y el login.
 
11. Retrospectiva: Que hice bien? Definir bien mis pasos a seguir durante el sprint y planificar mejor las tareas durante él mismo. Que hice mal? No contemplar la compatibilidad entre sistemas operativos, no revisar que las versiones de mis bibliotecas y dependencias fueran congruentes. Que puedo hacer diferente? Seguir mejorando en cada sprint como organizar las tareas a desarrollar y así generar experiencia, tener en cuenta como debe ser la correcta implementación del proyecto para evita problemas futuros.
   

