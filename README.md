# Creando un Web Service SOAP con C# en Visual Studio
En este documento explicaremos paso a paso como realizar la creación de un servicio web con C# en Visual Studio para saber como crearlos, implementarlos y utilizarlos en futuros proyectos para Integracion de Plataformas.
## Para crear un Servicio Web Soap sigue los siguientes pasos:

### 1. Crear un nuevo proyecto en Visual Studio
Para comenzar, abre Visual Studio y selecciona "Crear un nuevo proyecto". En la ventana que aparece, busca `"Aplicación web ASP.NET (.NET Framework)"` y haz clic en "Crear".

### 2. Seleccionar el tipo de plantilla
En la siguiente ventana, selecciona la plantilla `Vacío` y asegúrate de que esté marcada la casilla "Configurar para HTTPS" en la lista de opciones en Avanzado y haz clic en "Crear".

### 3. Agregar un servicio web
Una vez que hayas creado el proyecto, haz clic derecho en la carpeta del proyecto y selecciona `Agregar` > `Nuevo elemento`. En la ventana que aparece, ubica el buscador y busca `"Servicio web"`.

### 4. Configurar el servicio web
Entre las opciones, selecciona `"Servicio web ASMX"`, luego, asigna un nombre al servicio web y haz clic en "Agregar".

### 5. Escribir el código
Abre el archivo del servicio web que acabas de crear y escribe el código que necesitas para el servicio. Implementa la lógica para cada método en tu clase.

### 6. Probar el servicio
Para probar el servicio, ejecuta tu proyecto y dirígete a la dirección URL de tu proyecto en tu navegador web.

### 7. Implementar el servicio
Finalmente, para implementar o consumir tu web service desde otra aplicación, simplemente utiliza la dirección URL de tu web service y llama al método que deseas utilizar con los parámetros necesarios.
