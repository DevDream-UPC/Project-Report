# Capítulo IV: Product Design
## 4.1. Style Guidelines. 
A continuacion se planteara los estilos y herramientas que se estaran utilizando como guias para el desarrollo de la aplicacion web.

### 4.1.1. General Style Guidelines.

### Historia de la marca
En esta sección se mostrara de manera organizada los Branding, Typography, Colors y Spacing que se usara para diseñar nuestra solucion.

* __Brand Overview.-__ La necesidad del monitoreo de los animales por parte de los productores agropecuarios y veterinarios.

* __Brand Name.-__ El nombre de nuestro aplicacion web es FarmGuard. La creacion de este nombre se debe al juntar palabras relacionadas con la idea de nuestra solucion, siendo estas **Farm**  (Traducido es granja) y **Guard** (Traducido es guardia ). Palabras que creemos que expresan nuestro objetivo de la aplicacion. 

![Logo](/Assets/img/ChapterIV/DALL·E%202024-08-31%2001.58.29%20-%20A%20minimalist%20logo%20for%20an%20app%20called%20'FarmGuard.'%20The%20logo%20should%20feature%20a%20simple,%20clean%20design%20with%20modern%20lines.%20The%20central%20element%20could%20be%20a%20shie.webp)

* __Fonts.-__ El tipo de tipografia de letra elegido fue Roboto debido a su legibilidad, claridad, versatilidad y integracion facil gracias a Google Fonts. A continuacion se mostrara los tamaños de letras que se usara en los diferentes tipos de etiquetas que contenga texto.

![Fuente](/Assets/img/ChapterIV/Section%201%20(1).png)

* __Colores.-__ El color escogido fue el verde __#4ADE80__ debidom a que queremos expresar salud, cuidado, bienestar a nuestros usuarios que monitorean a sus animales.

![](/Assets/img/ChapterIV/image%202.png)

* __Tonos de comunicacion.-__ El tipo de lenguaje a emplear sera serio y formal.


### 4.1.2. Web Style Guidelines.
La aplicacion web se adaptara a todo tipos de dispositivos tecnologicos usados por nuestros segmentos objetivos, garantizando la usabilidad se mantenga en todo momento. Esto ofrecera una experiencia de usuario satisfactoria y coherente, independientemente del dispositivo que use el usuario en ese momento.

![Paginas Web Responsive](/Assets/img/ChapterIV/responsibe.jpeg)

Se utilizara un patron Z para el diseño de nuestro landing page, dado que queremos que el usuario mire primero nuestro logo para luego proceder con las opciones del navbar, donde luego vea el contenido de cada seccion y termine con el texto que contiene cada una de las secciones.

![Patron Z](/Assets/img/ChapterIV/OIP.jpeg)

Para la aplicacion web pensamos usar el patron F por que queremos que el usuario vea las opciones disponibles para navegar para luego proceder con sus respectivas busquedas y usos en la aplicacion web.

![Patron F](/Assets/img/ChapterIV/lectura-contenido-página-web-patrón-3.png)

## 4.2. Information Architecture.
En esta seccion, estableceremos la estructura de las secciones de nuestro software que incluye el landing page y la aplicacion Web para cada segmento objetivo.
<hr>

### 4.2.1. Organization System.

En este punto indicaremos en que secciones se aplicara el tipo de estructuras jerarquicas, secuenciales o matriarcales en el landing page y aplicacion web.

* __Landing Page__

Para el landing page usaremos un sistema jerarquico visual puesto que este tipo de organizacion es ideal para paginas con secciones e identificar informacion mas importante en el citio.

![Imaqgen del sistema jerarquico](/Assets/img/ChapterIV/jerarquico.jpg)

* __Aplicacion Web (Veterinarios y ganaderos)__

    * Jerarquica <br>
        __Lista de Animales:__ El usuario puede ver todos los animales que tiene a su cargo. Al hacer clic en un animal específico, se despliega su perfil completo, que incluye información detallada como su historial médico, peso, edad, etc.

        __Lista de Vacunas:__ El usuario puede acceder a una lista de todas las vacunas administradas a cada animal. Desde esta lista, puede seleccionar una vacuna específica para ver detalles adicionales, como la fecha de administración y el veterinario responsable.

        __Lista de estados de los animlaes:__ El usuario puede consultar el estado de salud actual de cada animal, con la posibilidad de filtrar por estado (saludable, enfermo, en tratamiento) y acceder a registros específicos para cada caso.

    
    * Secuencial <br>
        __Agregar un animal:__ Un proceso paso a paso donde el usuario introduce los datos del nuevo animal, como su especie, raza, edad,etc.

        __Agregar una vacuna:__ Un proceso guiado para registrar una nueva vacuna. El usuario selecciona el animal, el tipo de vacuna, la fecha de administración, y otros detalles pertinentes. Este proceso asegura que todos los campos requeridos sean completados en orden.

    * Matriarcal <br>
        __Mostrar Caracteristicas de los animales:__ En esta sección, el usuario puede comparar diferentes animales en función de características como especie, edad, peso, y estado de salud. Las comparaciones se muestran en una tabla donde se pueden seleccionar varios animales y ver sus atributos lado a lado.


### 4.2.2. Labeling System.

A continuacion se presentara el etiquetado  que tendra las diferentes secciones del landing y aplicacion web .

* __Landing Page__ <br>

__Inicio/Home:__ Sección que mostrará un banner con una frase representativa, de igual manera brindará una idea principal y a su vez un botón con el cual el usuario podrá entrar a la aplicación.

__Beneficios/Benefits:__ Sección dividida por cada segmento en donde se le mostrarán los beneficios que tendrá cada uno a la hora de usar la aplicación.

__Planes/Plans:__ Se mostraran los precios que tendrá cada uno de los planes con una descripcion breve y su respectivo precio.

__Contactanos/Contact Us:__ Se mostrarán nuestros canales de comunicación, a la vez que un formulario en donde pueda enviar sus comentarios o enviar informacion para contactarlo.

__Nosotros/ About Us:__ Esta sección el visitante podrá ver la información del equipo que trabajo que trabajo en el proyecto.

* __Aplicacion Web (Veterinarios y ganaderos)__ <br>

__Inicio/Home:__ Se mostrara las notificaciones, graficos que mostraran estadisticas de los animales respecto a su estado de salud y una barra que mostrara la cantidad de animales registrados.

__Animales/Animals:__ Se mostrara los animales registrados en la aplicacion con sus datos respectivos. Ademas de permitir agregar otros animales.

__Alertas/Alerts:__  Se mostrara mas detalles de las notificaciones.

__Vacunas/Vaccines:__ Se mostrara las vacunas disponibles ademas de recomendar para que tipo de animal le puede beneficiar.



<br>



### 4.2.3. SEO Tags and Meta Tags.

En esta seccion, se presentaran las etiquetas a usar para el landing page y app web. Gracias a estas, podremos destacar en los motores de busquedas.
.

### Para la landing page.

* __Title (Seo tag):__ FarmGuard | Landing Page 

* __Description (Meta tag):__ FarmGuard Oficial Landing Page.

* __Keywords (Meta tag):__ Animals, Farm, Guard, Vaccines, Control, monitoring, information, plans.

### Para la App Web.

* __Authors (Meta tag):__ DevDream

* __Title (Seo tag):__ FarmGuard | App Web 

* __Description (Meta tag):__ FarmGuard Oficial app web.

* __Keywords (Meta tag):__ Animals, Farm, Guard, Vaccines, Control, monitoring, information, plans.

* __Authors (Meta tag):__ DevDream

### 4.2.4. Searching Systems.

En esta seccion, se presentara el sistema de busqueda que implementaremos en la aplicacion. Para que los usuarios puedan buscar la informacion que desean.

Para la busqueda de nuestra aplicacion usaremos (Patron Search Filters). Por el motivo que permite hacer busquedas por filtros sobre un respectivo contenido.

![Patron](https://ui-patterns.com/patterns/LiveFilter/examples/773)



### 4.2.5. Navigation Systems.

A continuacion, presentaremos el sistema de navegacion con el que contara FarmGuard que permititra al usuario navegar en el landing page y app web.

En este caso usaremos un solo sistema de navegacion, siendo este Navigation Tabs puesto que permite tener una vista rapida de las opciones de la aplicacion para interactuar tanto para el landing page y app web, como ejemplo la imagen que hay debajo siendo esta un sidebar con las diversas partes de los sistemas

![navigation tabs](https://ui-patterns.com/uploads/image/file/8/best_old_3.jpg)

## 4.3. Landing Page UI Design.
<hr>

### 4.3.1. Landing Page Wireframe.

En esta seccion se mostrara los diferrentes wireframes desarrollados en software de figma para el landing page.

![Inicio](/Assets/img/ChapterIV/Wireframes%20LP/W-Inicio.png)

![Inicio](/Assets/img/ChapterIV/Wireframes%20LP/W-Beneficios.png)

![Inicio](/Assets/img/ChapterIV/Wireframes%20LP/W-Planes.png)

![Inicio](/Assets/img/ChapterIV/Wireframes%20LP/W-Nosotros.png)

![Inicio](/Assets/img/ChapterIV/Wireframes%20LP/W-Contactanos.png)

![Inicio](/Assets/img/ChapterIV/Wireframes%20LP/W-Footer.png)

Link para ver los wireframes en figma [https://www.figma.com/design/DUUA7IzOUkyUtHMm9hOo5Z/Untitled?node-id=0-1&t=nZEpVk0KewGNnMTo-1](https://www.figma.com/design/DUUA7IzOUkyUtHMm9hOo5Z/Untitled?node-id=0-1&t=nZEpVk0KewGNnMTo-1)


### 4.3.2. Landing Page Mockup.

En esta seccion mostraremos los mockups realizados para el landing page con los respectivos estilos establecidos en los puntos anteriores.

![Inicio](/Assets/img/ChapterIV/Landing%20Page%20Mockup/Inicio.png)

En este mockup del inicio del landing page se aprecia el inicio de aplicativo con una frase haciendo referencia al negocio asi como las imagenes respectivas. Ademas de un boton de accion que permitira al usuario redirigirlo a la aplicacion web.

![Inicio](/Assets/img/ChapterIV/Landing%20Page%20Mockup/Beneficios.png)

En este mockup de los beneficios mostrara los beneficios al usar el aplicativos con imagenes dentro de cards que tendran animaciones haciendo mas agradable la interaccion del usuario.

![Inicio](/Assets/img/ChapterIV/Landing%20Page%20Mockup/Planes.png)

En este mockup de los planes se muestra cards con los diferentes planes que tendra la aplicacion web.

![Inicio](/Assets/img/ChapterIV/Landing%20Page%20Mockup/Nosotros.png)

En esta seccion mostraremos al equipo detras del desarrollo del aplicativo web.

![Inicio](/Assets/img/ChapterIV/Landing%20Page%20Mockup/Contactanos.png)

En este mockup mostraremos un formulario para poder contactar con el equipo de desarrollo de FarmGuard.

![Inicio](/Assets/img/ChapterIV/Landing%20Page%20Mockup/Footer.png)

En este mockup se puede ver el footer donde tendra una pequeña descripcion con nuestras respectivas redes.

Enlace a la mockup de la Landing Page en Figma: [https://www.figma.com/design/DUUA7IzOUkyUtHMm9hOo5Z/Untitled?node-id=0-1&t=nZEpVk0KewGNnMTo-1](https://www.figma.com/design/DUUA7IzOUkyUtHMm9hOo5Z/Untitled?node-id=0-1&t=nZEpVk0KewGNnMTo-1)


## 4.4. Web Applications UX/UI Design
En esta seccion mostrara los wireframes y mockups de la aplicacion web.

### 4.4.1. Web Applications Wireframes

A continuacion mostraremos los wireframes del app web con su respectiva descripcion.

![**](/Assets/img/ChapterIV/Web%20app%20wireframes/W-Iniciar%20sesin.png)

En esta pantalla se muestra el inicio de sesion con el respectivo formulario para poder iniciar en el aplicativo web.

![**](/Assets/img/ChapterIV/Web%20app%20wireframes/W-Iniciar%20sesin-1.png)

En esta pantalla se mostrara el formulario para poder crear una cuenta en la aplicacion web con la posibilidad de agregar una imagen en la cuenta.

![**](/Assets/img/ChapterIV/Web%20app%20wireframes/W-Perfil%20App.png)

En esta pantalla se mostrara la informacion del perfil donde el usuario podra editar sus datos y su imagen del perfil.

![**](/Assets/img/ChapterIV/Web%20app%20wireframes/W-Inicio%20App.png)

En esta pantalla es el inicio de la aplicacion donde mostara las notificaciones, graficos, y una barra que mostarra la cantidad de animales registrados.

![**](/Assets/img/ChapterIV/Web%20app%20wireframes/W-Animales%20App.png)

En esta pantalla se mostrara los animales registrados ademas de permitir registrar mas animales.

![**](/Assets/img/ChapterIV/Web%20app%20wireframes/W-Animales%20App-1.png)

En esta pantalla se mostrara la informacion del animal con datos mas detallados ademas de poder actualizar la informacion del animal.

![**](/Assets/img/ChapterIV/Web%20app%20wireframes/W-Animales%20App-2.png)

En esta pantalla se mostrara las vacunas que tiene el animal seleccionado.

![**](/Assets/img/ChapterIV/Web%20app%20wireframes/W-Animales%20App-3.png)

En esta pantalla se podra agregar la vacuna que tenemos registradas en la base de datos.

![**](/Assets/img/ChapterIV/Web%20app%20wireframes/W-++Animales%20App.png)

En esta pantalla se muestra un formulario para agregar un nuevo animal

![**](/Assets/img/ChapterIV/Web%20app%20wireframes/W-Vacunas.png)

Pantalla paraver recomendaciones sobre las vacunas.

### 4.4.2. Web Applications Wireflow Diagrams

Enlace a traves de la herramienta LucidChart:

.

### 4.4.3. Web Applications Mock-ups

A continuacion mostraremos los wireframes del app web con su respectiva descripcion.

![**](/Assets/img/ChapterIV/Web%20app%20mockups/Iniciar%20sesin.png)

En esta pantalla se muestra el inicio de sesion con el respectivo formulario para poder iniciar en el aplicativo web.

![**](/Assets/img/ChapterIV/Web%20app%20mockups/Iniciar%20sesin-1.png)

En esta pantalla se mostrara el formulario para poder crear una cuenta en la aplicacion web con la posibilidad de agregar una imagen en la cuenta.

![**](/Assets/img/ChapterIV/Web%20app%20mockups/Perfil%20App.png)

En esta pantalla se mostrara la informacion del perfil donde el usuario podra editar sus datos y su imagen del perfil.

![**](/Assets/img/ChapterIV/Web%20app%20mockups/Inicio%20App.png)

En esta pantalla es el inicio de la aplicacion donde mostara las notificaciones, graficos, y una barra que mostarra la cantidad de animales registrados.

![**](/Assets/img/ChapterIV/Web%20app%20mockups/Animales%20App.png)

En esta pantalla se mostrara los animales registrados ademas de permitir registrar mas animales.

![**](/Assets/img/ChapterIV/Web%20app%20mockups/Animales%20App-1.png)

En esta pantalla se mostrara la informacion del animal con datos mas detallados ademas de poder actualizar la informacion del animal.

![**](/Assets/img/ChapterIV/Web%20app%20mockups/Animales%20App-2.png)

En esta pantalla se mostrara las vacunas que tiene el animal seleccionado.

![**](/Assets/img/ChapterIV/Web%20app%20mockups/Animales%20App-3.png)

En esta pantalla se podra agregar la vacuna que tenemos registradas en la base de datos.

![**](/Assets/img/ChapterIV/Web%20app%20mockups/++Animales%20App.png)

En esta pantalla se muestra un formulario para agregar un nuevo animal

![**](/Assets/img/ChapterIV/Web%20app%20mockups/Vacunas.png)

Pantalla paraver recomendaciones sobre las vacunas.


Enlace a la mockup de la App Web en Figma: [https://www.figma.com/design/DUUA7IzOUkyUtHMm9hOo5Z/Untitled?node-id=0-1&t=nZEpVk0KewGNnMTo-1](https://www.figma.com/design/DUUA7IzOUkyUtHMm9hOo5Z/Untitled?node-id=0-1&t=nZEpVk0KewGNnMTo-1)

### 4.4.4 Web Applications User Flow Diagrams.
En esta seccion se muestra el daigram de uso de la aplicacion respecto a nuestro usuario desde el registro hasta agregar animales, vacunas, ver recomendaciones de vacunas para administrar a sus animales, etc.

![user flow diagram](/Assets/img/ChapterIV/User%20diagram%20flow.png)

Enlace de los User Flow Diagrams en LucidChart: [https://lucid.app/lucidchart/c5066ad5-1553-4741-8503-0beb31c75bff/edit?viewport_loc=-7249%2C-868%2C16168%2C7220%2C0_0&invitationId=inv_4b7d3152-0a03-4625-b055-bc4660b58dfe](https://lucid.app/lucidchart/c5066ad5-1553-4741-8503-0beb31c75bff/edit?viewport_loc=-7249%2C-868%2C16168%2C7220%2C0_0&invitationId=inv_4b7d3152-0a03-4625-b055-bc4660b58dfe)


## 4.5. Web Applications Prototyping.
<hr>

En esta seccion se mostrara el prototipo de nuestra aplicacion web realizado en figma.

![prototipo](/Assets/img/ChapterIV/prototipo.png)

[https://www.figma.com/proto/DUUA7IzOUkyUtHMm9hOo5Z/Untitled?node-id=65-242&node-type=CANVAS&t=oGQqXPyqH22KfISJ-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=150%3A357](https://www.figma.com/proto/DUUA7IzOUkyUtHMm9hOo5Z/Untitled?node-id=65-242&node-type=CANVAS&t=oGQqXPyqH22KfISJ-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=150%3A357)


## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Software Architecture Context Diagram.
![Diagrama de contexto](/Assets/img/ChapterIV/structurizr-SystemContext-001.png)
### 4.6.2. Software Architecture Container Diagrams
![Diagrama de contendedores](/Assets/img/ChapterIV/structurizr-Container-001.png)
### 4.6.3. Software Architecture Component Diagram.
![Diagrama de componente](/Assets/img/ChapterIV/structurizr-Componente.png)

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
En esta seccion planteamos nuestro diagrama de clases para poder conllevar el desarrollo de la backend con sus respectivas metodos que contienen la logica del negocio.
![diagrama de clases](/Assets/img/ChapterIV/FarmGuard%20Class%20Diagram.png)


Enlace del class diagrams en LucidChart: [https://lucid.app/lucidchart/ee9979a8-233e-46e8-b8aa-baf5ac02537c/edit?viewport_loc=-1846%2C-507%2C3360%2C1501%2C0_0&invitationId=inv_db63e70b-6b1e-49d0-a407-75ad39294d40](https://lucid.app/lucidchart/ee9979a8-233e-46e8-b8aa-baf5ac02537c/edit?viewport_loc=-1846%2C-507%2C3360%2C1501%2C0_0&invitationId=inv_db63e70b-6b1e-49d0-a407-75ad39294d40)

### 4.7.2. Class Dictionary
<hr>

* __Profile:__ Clase que representa la informacion de un perfil . 
* __User:__ Clase que representa a un usuario teniendo como atributos el rol, la contraseña y nick teniendo la inforamcion sensible de este.
* __Role:__ Clase que representa los roles disponibles en la aplicacion, esta siendo nuestros dos segmentos objetivos.
* __Email:__ Clase que representa el email de un perfil.
* __PersonName:__ Clase que representa los nombre y apellidos de una persona.
* __Membership:__  Clase que representa los planes disponibles en la aplicacion.
* __Inventory:__ Clase que representa el inventario de los animales en la aplicacion.
* __Notification:__ Clase que representa una notificacion en la aplicacion.
* __Vaccine:__ Clase que representa una vacuna que puede tener un animal o puede ser recomendaciones de un animal.
* __Animal:__  Clase que representa un animal que puede ser guardado en el inventario.

<br>

## 4.8. Database Design
En esat seccion se mostrara el diseño de la base de datos teniendo de base nuestro diagrama de clase. Usando el software de Vertabelo.
### 4.8.1. Database Diagram
![diagrama de clases](/Assets/img/ChapterIV/FarmGuard-2024-09-05_00-20.png)

Enlace de Database Diagram: [https://my.vertabelo.com/doc/ctoANnzcmfn49HenpcIjKUxFyyq0drUW](https://my.vertabelo.com/doc/ctoANnzcmfn49HenpcIjKUxFyyq0drUW)

# Anexo

* __Anexo 1__

Codigo realizado en structurizer para la realizacion del diagrama c4.

workspace {
    model {
        user = person "Veterinarian"
        user2 = person "Animal breeder"
        
        softwareSystem = softwareSystem "FarmGuard" "Application for veterinarians and animal breeders who want to monitor" {
             
            webapp = container "Single-Page Application" {
        
            }

            database = container "DB" "DataBase" "MySql Schema" "MySql"
            
            api = container "Api Aplication" {
                
                ComandServiceInventory = component "ComandServiceInventory" "" ".net" "Componente"
                QueryServiceInventory = component "QueryServiceInventory" "" ".net" "Componente"
                ControllerInventory = component "ControllerInventory" "" ".net" "Componente"
                
                ComandServiceUser = component "ComandServiceUser" "" ".net" "Componente"
                QueryServiceUser = component "QueryServiceUser" "" ".net" "Componente"
                ControllerUser = component "ControllerUser" "" ".net" "Componente"
                
                ComandServiceAnimal = component "ComandServiceAnimal" "" ".net" "Componente"
                QueryServiceAnimal = component "QueryServiceAnimal" "" ".net" "Componente"
                ControllerAnimal = component "ControllerAnimal" "" ".net" "Componente"
                
                ComandServiceProfile = component "ComandServiceProfile" "" ".net" "Componente"
                QueryServiceProfile = component "QueryServiceProfile" "" ".net" "Componente"
                ControllerProfile = component "ControllerProfile" "" ".net" "Componente"
                
                ComandServiceVaccine = component "ComandServiceVaccine" "" ".net" "Componente"
                QueryServiceVaccine = component "QueryServiceVaccine" "" ".net" "Componente"
                ControllerVaccine = component "ControllerVaccine" "" ".net" "Componente"
                
                ComandServiceNotification = component "ComandServiceNotification" "" ".net" "Componente"
                QueryServiceNotification = component "QueryServiceNotification" "" ".net" "Componente"
                ControllerNotification = component "ControllerNotification" "" ".net" "Componente"
                
                





                
                Domain = component "DomainAplication"
                
            }
            landingpage = container "LandingPage" 
                
            
        }
        
        #Conexiones User{
        user -> webapp "Try using the farmGuard project"
        user2 -> webapp "Try using the farmGuard project"
        

       
       # Conexiones api
        api -> database "Make queries to the database"
        database -> api "send the answers"
        api -> webapp "receive response"
        webapp -> api "send http request"
        
        #Conexiones landing Page
        user2 -> landingpage "user visit our landing page"
        user -> landingpage "user visit our landing page"
        landingpage -> webapp "user directed to website"
       
       #Conexiones de SinglePage
       /*
       webapp -> securityC "Makes API calls to" "JSON/HTTPS"
       
       webapp -> proyectManagement "Makes API calls to" "JSON/HTTPS"
       webapp -> requests "Makes API calls to" "JSON/HTTPS"
       webapp -> librery "Makes API calls to" "JSON/HTTPS"
       webapp -> file "Makes API calls to" "JSON/HTTPS"
       webapp -> notification "Makes API calls to" "JSON/HTTPS"
       webapp -> profilecontroller "Makes API calls to" "JSON/HTTPS"
       *//*
       proyectManagement -> database "Perform query or command in the database"
       requests -> database "Perform query or command in the database"
       librery -> database "Perform query or command in the database"
       file -> database "Perform query or command in the database"
       notification -> database "Perform query or command in the database"
       profilecontroller -> database "Perform query or command in the database"*/
       
       #Conexiones a nivel componente
       
        #Otros servicio

        ComandServiceInventory -> ControllerInventory
        QueryServiceInventory -> ControllerInventory
        
        ComandServiceInventory -> database
        QueryServiceInventory -> database
        
        database -> QueryServiceInventory
        
        ControllerInventory -> webapp
        webapp -> ControllerInventory
       
        Domain -> ComandServiceInventory
        Domain -> QueryServiceInventory
        Domain -> ComandServiceUser
        Domain -> QueryServiceUser
        
        #Otros servicios
        
        ComandServiceUser -> ControllerUser
        QueryServiceUser -> ControllerUser
        
        QueryServiceUser -> database
        ComandServiceUser -> database
        
        database -> QueryServiceUser
        
        ControllerUser -> webapp
        webapp -> ControllerUser
        
        #Otro servicio
        
        ComandServiceAnimal -> ControllerAnimal
        QueryServiceAnimal -> ControllerAnimal
        
        ComandServiceAnimal -> database
        QueryServiceAnimal -> database
        
        database -> QueryServiceAnimal
        
        ControllerAnimal -> webapp
        webapp -> ControllerAnimal
        
        Domain -> ComandServiceAnimal
        Domain -> QueryServiceAnimal
        
        #Otro servicio
        
        ComandServiceProfile -> ControllerProfile
        QueryServiceProfile -> ControllerProfile
        
        ComandServiceProfile -> database
        QueryServiceProfile -> database
        
        database -> QueryServiceProfile
        
        ControllerProfile -> webapp
        webapp -> ControllerProfile
        
        Domain -> ComandServiceProfile
        Domain -> QueryServiceProfile
        
        
        #Otro servicio
        ComandServiceVaccine -> ControllerVaccine
        QueryServiceVaccine -> ControllerVaccine
        
        ComandServiceVaccine -> database
        QueryServiceVaccine -> database
        
        database -> QueryServiceVaccine
        
        ControllerVaccine -> webapp
        webapp -> ControllerVaccine
        
        Domain -> ComandServiceVaccine
        Domain -> QueryServiceVaccine

        
        #Otro servicio
        
        ComandServiceNotification -> ControllerNotification
        QueryServiceNotification -> ControllerNotification
        
        ComandServiceNotification -> database
        QueryServiceNotification -> database
        
        database -> QueryServiceNotification
        
        ControllerNotification -> webapp
        webapp -> ControllerNotification
        
        Domain -> ComandServiceNotification
        Domain -> QueryServiceNotification

        
        
        

        
        
        #Otro servicio



    }

    views {
        systemContext softwareSystem {
            include *
            autolayout lr
        }
        
        container softwareSystem {
            include *
            autolayout lr
        }
        
        component  api "Componente" {
            include *
            autolayout lr
            
        }
        

        
     
   
    




      
        styles {
            element "MySql" {
                shape "Cylinder" 
            
            }
            

        }
    
        theme default
    }
}