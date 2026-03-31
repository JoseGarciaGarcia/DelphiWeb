# DelphiWeb
Ficheros Curso Iniciación Programación Web en Delphi

## Vídeo: 11-Creación de Página Web con Consulta a InterBase
- Creación de una aplicación Web que utiliza el servidor web WebBroker
- Crear acciones dentro del WebModule
- Conexión a una tabla InterBase
- Consulta a la base de datos mediante código Delphi, obteniendo un conjunto de datos en JSON
- Visualización de los datos en una página web mediante etiquetas HTML

Ficheros: 
- **WebModuleUnit1.txt**
- **EMPLOYEE.GDB**

## Vídeo: 12-Creación de Página Web con Mantenimiento de Tabla
- Sacar el HTML del Response y llevarlo al fichero inicio.html
- Incluir el código para crear el mantenimiento de la tabla: código Delphi en el WebModule, y HTML y JavaScript en la página.

Ficheros: 
- **WebModuleUnit1-B.txt**
- **inicio.html**

## Vídeo: 13-HTMX
- Introducción a HTMX
- Dejar solo una página raíz. Costruir un Enrutador.
- Simplificar inicio.html

Documentación:
Antonio Zapater: 
- Demos: https://github.com/Embarcadero/WebStencilsDemos
- Libro WebStencils castellano: https://www.danysoft.com/htmx-y-webstencils-desarrollo-web-rapido-con-rad-studio/ 
- Nueva versión WebStencils (inglés), y otros: https://delphi-books.com/en/Antonio-Zapater.html

Danysoft Vídeos, con Antonio Zapater, Emilio Pérez (MVP), Jorge Cangas (MVP): https://www.youtube.com/@Danysoft/ 

Ficheros: 
- **WebModuleUnit1-C.txt**
- **inicio-B.html**. Renombrar dentro del wwwroot a incio.html.

## Vídeo: 14-HTMX + Bootstrap
- Añadimos Bootstrap para crear de forma sencilla un diseño más profesional
- Eliminamos todas las acciones del WebModule y simplificamos el código
- Creamos un mini-framework con WebBroker con tres capas:
	- Vista: RenderProjectList devuelve HTML
	- Controlador: WebModuleBeforeDispatch
  - Modelo: FireDAC query sobre tabla PROJECT

 ## Vídeo: 15-WebFileDispatcher + FDQuery
- Añadimos TWebFileDispatcher
	- Permite servir contenido estático (HTML, JS, CSS, imágenes) directamente desde una carpeta (wwwroot) sin necesidad de escribir código en el WebModule. Simplifica la arquitectura, evita errores de codificación, organiza los recursos y mantiene el WebModule dedicado exclusivamente a lógica de negocio.
- Añadimos TFDQuery
	- Centraliza el acceso a datos. Se reutiliza el mismo query dentro de cada petición del WebModule, reduciendo duplicación de SQL y simplificando operaciones CRUD. Más robustez, menos código, más claridad y mejor seguridad gracias al uso de parámetros.
 - Añadimos Bootstrap Icons
	- Activa el sistema de iconos usado por el HTML. Mejora la experiencia del usuario, clarifica las acciones de los botones y hace la interfaz considerablemente más moderna sin esfuerzo adicional.

Ficheros: 
- **TWebFileDispatcher.zip**

## Vídeo: 16-WebStencils
- Introducción y caracterísitcas principales de WebStencils
- Demos y documentación de Antonio Zapater, en la página de Github de Embarcadero
- Explicación de una Demo con WebBroker, FireDAC y WebStencils.

Documentación.

Antonio Zapater: 
- Demos: https://github.com/Embarcadero/WebStencilsDemos
- Libro WebStencils castellano: https://www.danysoft.com/htmx-y-webstencils-desarrollo-web-rapido-con-rad-studio/ 
- Nueva versión WebStencils (inglés), y otros: https://delphi-books.com/en/Antonio-Zapater.html

Danysoft:
- Vídeos, con Antonio Zapater, Emilio Pérez (MVP), Jorge Cangas (MVP): https://www.youtube.com/@Danysoft/ 
