# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management.
.A continuacion , presentaremos los programas de software que hemos usado en el transcurso del desarrollo de nuestro proyecto

## 5.1.1. Configuración del Entorno de Desarrollo de Software

A continuación, detallamos las herramientas de software que utilizamos durante el desarrollo de nuestro proyecto.

### Gestión de Proyectos
- **WhatsApp**: [https://web.whatsapp.com/](https://web.whatsapp.com/)  
Utilizamos WhatsApp para coordinar las tareas del equipo y facilitar el intercambio de ideas y apoyo durante todo el proceso.

### Diseño UX/UI del Producto
- **Miro**: [https://miro.com/es/](https://miro.com/es/)  
Miro fue empleado para la creación del Lean UX Canvas.
- **Uxpressia**: [https://uxpressia.com/](https://uxpressia.com/)  
Uxpressia nos permitió diseñar User Personas, Mapas de Empatía y Journey Maps.
- **Figma**: [https://www.figma.com](https://www.figma.com)  
Utilizamos Figma como herramienta principal para la creación de wireframes, wireflows, maquetas de la landing page y para los prototipos de las aplicaciones web.
- **LucidChart**: [https://www.lucidchart.com/pages/](https://www.lucidchart.com/pages/)  
Con LucidChart generamos los Impact Maps necesarios para el proyecto.

### Desarrollo de Software
- **Landing Page**: La página de inicio fue desarrollada utilizando HTML5, CSS y JavaScript.

### Pruebas de Software
- Realizamos las pruebas del landing page y la aplicación web empleando las herramientas de desarrollo integradas en navegadores como **Google Chrome** y **Brave**.

### Entornos de Desarrollo (IDE)
- **WebStorm**: [https://www.jetbrains.com/webstorm/](https://www.jetbrains.com/webstorm/)  
WebStorm fue nuestro IDE preferido para el desarrollo frontend, gracias a sus potentes herramientas que optimizan el flujo de trabajo.

### Despliegue de Software
- **GitHub Pages**: [https://pages.github.com/](https://pages.github.com/)  
Desplegamos la landing page usando GitHub Pages, conectando el repositorio para automatizar el proceso de despliegue.

### Documentación de Software
- **Google Docs**: [https://docs.google.com/document/u/0/](https://docs.google.com/document/u/0/)  
Usamos Google Docs para el seguimiento del progreso de las tareas asignadas y para compartir los informes semanales entre los miembros del equipo.
- **GitHub**: [https://github.com/](https://github.com/)  
GitHub fue empleado para la documentación del proyecto, permitiendo colaboración en el desarrollo y registro de los commits de cada miembro.
- **Visual Paradigm**: Utilizamos Visual Paradigm para generar los diagramas C4 del proyecto.
- **Vertabelo**: [https://vertabelo.com/](https://vertabelo.com/)  
Vertabelo nos sirvió para diseñar la estructura de la base de datos de manera colaborativa.


### 5.1.2. Source Code Management.

La administración y estructuración de las múltiples modificaciones se realizaron mediante la creación de un repositorio en GitHub para el proyecto. Nuestra organización se estructuró de la siguiente manera:

### Organización:
- **Repositorio en GitHub**: [https://github.com/DevDream-UPC](https://github.com/DevDream-UPC)
- **Landing Page**: [https://github.com/DevDream-UPC/FarmGuard-LandingPage](https://github.com/DevDream-UPC/FarmGuard-LandingPage)

### Ramas Principales:
- **Rama `main`**: En esta rama se almacenan las versiones oficiales de nuestro repositorio para pasarlas a producción.
- **Rama `develop`**: Esta rama se utiliza como punto de integración para las ramas de `feature`. Una vez que el equipo lo considere listo para el lanzamiento.

### Ramas Auxiliares:

- **Rama `Refactor/structure`**: En estas ramas se desarrollan las funcionalidades generales que se integrarán en la rama `develop`. Estas funcionalidades son aquellas solicitadas por los usuarios, tanto en la página de inicio como en la aplicación web. Por ejemplo, la rama `feature/navbar`.


### 5.1.3. Source Code Style Guide & Conventions.

Para asegurar la consistencia y calidad en el desarrollo de nuestra Landing Page y la aplicación web, implementaremos una serie de convenciones específicas para los distintos lenguajes y tecnologías que utilizamos:

### HTML
- **Tipo de Documento**: Cada archivo HTML comenzará con `<!DOCTYPE html>` para asegurar la correcta interpretación del documento.
- **Uso de Minúsculas**: Todas las etiquetas y atributos en HTML estarán en minúsculas, como `<body>` y `<p>`.
- **Cierre de Etiquetas**: Todas las etiquetas se cerrarán adecuadamente para mantener la estructura limpia.
- **Atributos con Comillas**: Los valores de los atributos siempre estarán entre comillas, por ejemplo, `<a href="https://example.com">`.
- **Especificaciones de Imágenes**: Se incluirán los atributos `alt`, `width` y `height` en las imágenes para mejorar la accesibilidad y el diseño responsivo.
- **Atributos sin Espacios**: No habrá espacios alrededor del signo igual en los atributos, por ejemplo, `<link rel="stylesheet" href="styles.css">`.
- **Elemento `<title>`**: No omitiremos el elemento `<title>` ya que es esencial para SEO y la accesibilidad del sitio.
- **Idioma y Codificación**: Usaremos el atributo `lang` para definir el idioma del documento y `<meta charset="UTF-8">` para la codificación de caracteres.

### CSS
- **Uso de HTTPS**: Todos los recursos externos, como fuentes y multimedia, se cargarán a través de HTTPS para garantizar la seguridad, por ejemplo: `@import 'https://fonts.googleapis.com/css?family=Open+Sans';`.
- **Nombres en Minúsculas**: Todos los nombres de elementos, atributos y valores estarán en minúsculas para mantener la coherencia, por ejemplo, `color: #e5e5e5;`.
- **Clases Descriptivas**: Las clases CSS tendrán nombres que describan claramente su propósito, separadas por guiones, por ejemplo: `.barra-navegacion`, `.autor-articulo`.
- **Propiedades Abreviadas**: Se usarán propiedades abreviadas cuando sea posible, para reducir el tamaño del código y mejorar la legibilidad, por ejemplo: `border-top: 0;`.
- **Colores Hexadecimales Reducidos**: Se utilizarán colores en formato hexadecimal de tres caracteres cuando sea aplicable, por ejemplo: `color: #ebc;`.
- **Orden Alfabético**: Las propiedades CSS dentro de un bloque estarán organizadas en orden alfabético para facilitar el mantenimiento.
- **Uso de Punto y Coma**: Cada declaración CSS terminará con un punto y coma para evitar errores de interpretación, por ejemplo: `display: block;`.
- **Espaciado Consistente**: Habrá un espacio después de los dos puntos en las declaraciones y entre las llaves que abren un bloque, por ejemplo: `font-weight: bold;`.
- **Comillas Simples en Atributos**: Los valores de atributos en CSS estarán entre comillas simples, por ejemplo: `font-family: 'Open Sans', Arial, sans-serif;`.

### C# y .NET
- **Uso de PascalCase**: Las clases, métodos y propiedades en C# seguirán la convención PascalCase, por ejemplo: `public class UserAccount { }`.
- **Uso de camelCase**: Las variables y parámetros se escribirán en camelCase, por ejemplo: `int userId = 0;`.
- **Espaciado y Sangría**: Se usará una sangría de 4 espacios y se incluirá un espacio entre las palabras clave y los paréntesis, por ejemplo: `if (condition)`.
- **Uso de `var`**: Se utilizará `var` cuando el tipo de la variable sea evidente, pero se preferirá el tipo explícito en casos no tan claros.
- **Comentarios XML**: Se documentarán los métodos públicos y las clases con comentarios XML, por ejemplo: `/// <summary>Descripción del método</summary>`.

### RESTful APIs
- **Rutas Descriptivas**: Se utilizarán rutas claras y descriptivas siguiendo los principios RESTful, por ejemplo: `GET /api/users`.
- **Métodos HTTP Apropiados**: Se garantizará el uso correcto de los métodos HTTP, como `GET`, `POST`, `PUT` y `DELETE`.
- **Códigos de Estado HTTP Correctos**: Las respuestas incluirán los códigos de estado HTTP adecuados, como `200 OK`, `404 Not Found` y `500 Internal Server Error`.
- **Formato JSON**: Tanto las solicitudes como las respuestas estarán estructuradas en JSON, manteniendo un formato consistente en las claves.

### Vue.js
- **Componentes Separados**: Cada componente Vue se almacenará en su propio archivo `.vue` para mantener una estructura modular.
- **camelCase en Métodos**: Los métodos y variables dentro de Vue seguirán la convención camelCase, por ejemplo: `computedProperty()`.
- **Sangría y Espaciado**: Se utilizarán 2 espacios para la sangría en los archivos `.vue`.
- **Uso Consistente de Directivas**: Se emplearán directivas de Vue como `v-bind`, `v-if` y `v-for` según las mejores prácticas oficiales.
- **Separación de Secciones**: Las plantillas, scripts y estilos dentro de los componentes `.vue` estarán claramente separados para un código más ordenado y mantenible.



### 5.1.4. Software Deployment Configuration.

Creamos un repositorio en la organización de nuestro equipo en GitHub, donde subimos los archivos necesarios para desplegar la landing page. El despliegue se realizó mediante GitHub Pages.

1. Subimos los archivos requeridos al repositorio correspondiente.
   
3. Luego, accedemos a **Settings** y localizamos la opción **Pages**. En el apartado de **Branch**, seleccionamos la rama `main` y guardamos los cambios.
   
5. Tras unos minutos, GitHub genera el enlace de acceso a nuestra página web.




## 5.2. Landing Page, Services & Applications Implementation.
<hr>

### 5.2.1. Sprint 1

### 5.2.1.1. Sprint Planning 1

<table>
     <tr> 
        <th>  Sprint #  </th>
        <th> Sprint 1 </th>
     </tr>
     <tr> 
        <td style="font-weight: bold;" colspan="7"> Sprint Planing Background</td>
     </tr>
     <tr>
       <td style="font-weight: bold;"> Date </td>
       <td> -- </td>
     </tr>
     <tr>
       <td style="font-weight: bold;"> Time </td>
       <td> -- horas (GMT-5) </td>
     </tr>
     <tr>
       <td style="font-weight: bold;"> Location </td>
       <td> Modalidad remota a través de la plataforma Discord <td>
     </tr>
      <tr>
        <td style="font-weight: bold;"> Prepared By </td>
        <td>  <td>
     </tr>
        <tr>
        <td style="font-weight: bold;"> Attendees (to planning meeting) </td>
        <td> 
        <br>
          . 
           <br>
         .
          <br>
           .
          <br>
        . 
              <br>
         .
         <td>
     </tr>
     <tr>
        <td style="font-weight: bold;"> Sprint 0 Review Summary </td>
        <td> Dado que es nuestro primer sprint de desarrollo, no existe 
        un review summary del sprint <td>
     </tr>
     <tr>
        <td style="font-weight: bold;"> Sprint 0 Retrospective Summary </td>
        <td> Dado a que nos encontramos en nuestro primer sprint, aun no identifcamos planes de mejora.<td>
     </tr>
     <tr> 
        <td style="font-weight: bold;" colspan="7"> Sprint Goal & User Stories</td>
     </tr>
       <tr>
          <td style="font-weight: bold;"> Sprint 1 Goal</td>
          <td>  . <td>
      </tr>
       <tr>
          <td style="font-weight: bold;"> Sprint 1 Velocity </td>
          <td>  . <td>
      </tr>
      <tr>
          <td style="font-weight: bold;"> Sum of Story Points </td>
          <td> . <td>
      </tr>


  </table>


### 5.2.1.2. Sprint backlog 1

.

Link de Trello:


<table style="width:800px; height:300px;"> 
   <tr>
      <th colspan="4"> Sprint # </th>
      <th colspan="7"> Sprint 1 </th>
   </tr>
   <tr >
     <th colspan="4"> User Story </th>
     <th colspan="7"> Work-Item /Task</th>
   </tr>
   <tr>
     <th > Id </th>
     <th colspan="3"> Title </th>
     <th> Id </th>
     <th > Title </th>
     <th> Description </th>
     <th> Estimation (Hours) </th>
     <th> Assigned To </th> 
     <th> Status (To-do / In-Process / To- Review / Done) </th>
   </tr>
     <tr>
      <th> EP1-US01 </th>
     <th colspan="3"> . </th>
      <th> W01  </th>
     <th> . </th>
     <th> .</th>
     <th> </th>
     <th> . </th> 
     <th> . </th>
   </tr>
    <tr>
      <th> EP1-US01 </th>
     <th colspan="3">  .  </th>
      <th> W02  </th>
     <th> . </th>
     <th> . </th>
     <th> . </th>
     <th> . </th> 
     <th> . </th>
   </tr>
    <tr>
      <th> EP1-US02 </th>
     <th colspan="3"> .</th>
      <th> W03  </th>
     <th> . </th>
     <th> . </th>
     <th> . </th>
     <th> . </th> 
     <th> . </th>
   </tr>




</table>


### 5.2.1.3. Development Evidence for Sprint Review.


### 5.2.1.5 Execution Evidence for Sprint Review.



### 5.2.1.6 Services Documentation Evidence for Sprint Review.


#### Anexo: flujo de trabajo entre las ramas


#### Anexo: tablas de commits en el periodo de 1 mes


#### Anexo: Flujo de trabajo en el periodo de 1 mes



#### Anexo: Colaboration Insights en el periodo de 1 mes

 

 
