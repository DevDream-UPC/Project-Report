# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.

El To-Be Scenario Mapping es una técnica utilizada para visualizar cómo será la experiencia futura de los usuarios al interactuar con un producto o servicio, después de implementar mejoras o cambios. A diferencia del As-Is Scenario Mapping, que refleja el estado actual, el To-Be muestra el escenario deseado, donde se optimizan los procesos, se eliminan obstáculos y se mejoran las emociones y percepciones de los usuarios.

En el caso del segmento de veterinarias, el To-Be Scenario Mapping describe cómo será su interacción con FarmGuard, desde la identificación del problema hasta el registro en la aplicación, destacando los beneficios y mejoras en su experiencia. Este método permite a las veterinarias administrar las historias clínicas de sus pacientes de manera más eficiente, lo que reduce los errores y ayuda a optimizar las operaciones.

**Cuidadores de animales en terrenos de productores agropecuarios:**

<img src="Assent/img/to-be1.PNG" alt="TO-BE1">

**Veterinarias:**

<img src="Assent/img/to-be2.PNG" alt="TO-BE2">

[Enlace de Miro](https://miro.com/app/board/uXjVKiLniSg=/?share_link_id=58992610792)

## 3.2. User Stories

En la sección de historias de usuarios, detallaremos las diversas necesidades y requerimientos de nuestros usuarios y veterinarios. Cada historia de usuario representará un escenario o una función que la plataforma debe proporcionar para cumplir con nuestro objetivo principal: ofrecer una solución completa para la gestión de la salud animal.

Proporcionar a los usuarios herramientas efectivas para el monitoreo, registro y análisis de la salud de los animales en granjas y clínicas veterinarias es el objetivo principal. Esto permitirá a los dueños de granjas y veterinarios tomar decisiones informadas y reducir los riesgos asociados con la salud animal. Al detallar estas historias de usuario, podremos comprender mejor cómo la plataforma satisfará las necesidades de ambos grupos y ofrecer una solución completa y eficiente para la administración de la salud de los animales.


<table>
<colgroup>
<col style="width: 11%" />
<col style="width: 15%" />
<col style="width: 21%" />
<col style="width: 39%" />
<col style="width: 11%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Epic / Story ID</td>
<td>Título</td>
<td>Descripción</td>
<td>Criterios de Aceptación</td>
<td>Relación Epic ID</td>
</tr>
<tr class="even">
    <td>E1-US01</td>
    <td>Gestión digital de la granja</td>
    <td>
        <p><strong>Como</strong> productor agropecuario familiarizado con la tecnología,</p>
        <p><strong>Quiero</strong> digitalizar la gestión de mis animales </p>
        <p><strong>Para</strong> poder acceder a toda la información desde cualquier dispositivo y agilizar mis operaciones. </p>
    </td>
    <td>
        <p>Escenario 1: Acceso a la plataforma desde múltiples dispositivos</p>
        <p><strong>Dado</strong> que el usuario esta familiarizado con dispositivos tecnologicos,</p>
        <p><strong>Cuando</strong> accede a la plataforma desde su movil o computadora,</p>
        <p><strong>Entonces</strong> podrá visualizar, aregar y actualizar la informacion de los animales de su granja de manera remota.</p>
        <p>Escenario 2: Actualización automática en tiempo real
        <p><strong>Dado</strong> que el usuario ha actualizado los datos de su granja,</p>
        <p><strong>Cuando</strong> ingresa nuevas entradas en la plataforma</p>
        <p><strong>Entonces</strong> los cambios se sincronizarán automaticamente en todos sus dispositivos</p>
    </td>
    <td>1</td>
</tr>
<tr class="odd">
<td>E1-US02</td>
<td>Monitoreo de indicadores clave</td>
<td>
<p><strong>Como</strong> productor agropecuario con expriencia tecnológica,</p>
<p><strong>Quiero</strong> monitorear indicadores clave de salud de los animales en tiempo real </p>
<p><strong>Para</strong> tomar decisiones más informadas y mejorar la productividad de mi granja.</p>
</td>
<td>
<p>Escenario 1: Indicadores en tiempo real</p>
<p><strong>Dado</strong> que el usuario tiene acceso a sensores de la granja.</p>
<p><strong>Cuando</strong> abre la plataforma </p>
<p><strong>Entonces</strong> podrá ver los indicadores de salud actualizados de los animales, como tempertura, peso, y frecuencia cardíaca </p>
<p>Escenario 2: Actualización automática en tiempo real</p>
<p><strong>Dado</strong> que el usuario ha actualizado los datos de su granja,</p>
<p><strong>Cuando</strong> ingresa nuevas entradas en la plataforma</p>
<p><strong>Entonces</strong> los cambios se sincronizaran automaticamente en todos sus dispositivos</p>
</td>
<td>1</td>
</tr>
<tr class="even">
<td>E1-US03</td>
<td>Integración con Equipos y Sensores</td>
<td>
<p><strong>Como</strong> productor agropecuario interesado en la innovación,</p>
<p><strong>Quiero</strong> integrar la plataforma con sensores y dispositivos en mi granja</p>
<p><strong>Para</strong> automatizar el monitoreo de la salud de los animales y reducir la intervención manual</p>
</td>
<td>
<p>Escenario 1: Conexión de dispositivos</p>
<p><strong>Dado</strong> que el usuario cuenta con sensores instalados</p>
<p><strong>Cuando</strong> los dispositivos se conecten a la plataforma, </p>
<p><strong>Entonces</strong> la información se actualizará automáticamente en la aplicación sin intervención manual. </p>
<p>Escenario 2: Automatización de tareas repetitivas</p>
<p><strong>Dado</strong> que el usuario ha integrado sus dispositivos,</p>
<p><strong>Cuando</strong> un animal cumpla con ciertos criterios predeterminados, </p>
<p><strong>Entonces</strong> la plataforma ejecutará acciones automáticas, como registrar una vacuna aplicada</p>
</td>
<td>1</td>
</tr>
<tr class="odd">
<td>E2-US01</td>
<td>Herramientas de Aprendizaje</td>
<td>
<p><strong>Como</strong> productor agropecuario con poca capacitación, </p>
<p><strong>Quiero</strong> acceder a recursos educativos dentro de la plataforma</p>
<p><strong>Para</strong> aprender más sobre la gestión efectiva de mi granja y mejorar el bienestar de mis animales</p>
</td>
<td>
<p>Escenario 1: Acceso a material educativo</p>
<p><strong>Dado</strong> que el usuario tiene poca experiencia en la gestión de granjas,</p>
<p><strong>Cuando</strong> accede a la plataforma, </p>
<p><strong>Entonces</strong> podrá visualizar tutoriales y guías que le enseñen buenas prácticas para la gestión de la salud animal. </p>
<p>Escenario 2: Retroalimentación educativa</p>
<p><strong>Dado</strong> que el usuario está completando un tutorial,</p>
<p><strong>Cuando</strong> finaliza una lección, </p>
<p><strong>Entonces</strong> recibirá retroalimentación automática sobre su progreso y recomendaciones adicionales.</p>
</td>
<td>2</td>
</tr>
<tr class="even">
<td>E2-US02</td>
<td>Simplificación de tareas</td>
<td>
<p><strong>Como</strong> productor agropecuario sin experiencia tecnológica,</p>
<p><strong>Quiero</strong> que la aplicación tenga una interfaz sencilla y fácil de usar</p>
<p><strong>Para</strong> poder gestionar mi granja sin necesidad de conocimientos avanzados en tecnología</p>
</td>
<td>
<p>Escenario 1: Interfaz de usuario simplificada</p>
<p><strong>Dado</strong> que el usuario no está familiarizado con aplicaciones complejas</p>
<p><strong>Cuando</strong> accede a la plataforma, </p>
<p><strong>Entonces</strong> verá una interfaz amigable y simplificada con iconos y pasos claros para realizar tareas básicas</p>
<p>Escenario 2: Guías de usuario</p>
<p><strong>Dado</strong> que el usuario está usando la paltaforma por primera vez,</p>
<p><strong>Cuando</strong> se enfrente a una nueva funcionalidad,</p>
<p><strong>Entonces</strong> se le proporcionará una guía paso a paso para completar la tarea.</p>
</td>
<td>2</td>
</tr>
<tr class="odd">
<td>E2-US03</td>
<td>Guia Paso a Paso</td>
<td>
<p><strong>Como</strong> productor agropecuario que no ha recibido capacitacion,</p>
<p><strong>Quiero</strong> seguir un proceso guiado paso a paso</p>
<p><strong>Para</strong> registrar el estado de mis animales y recibir recomendaciones automáticas sobre sus cuidados, sin necesidad de entender términos complejos</p>
</td>
<td>
<p>Escenario 1: Registro guiado de animales</p>
<p><strong>Dado</strong> que el usuario está registrando un nuevo animal,</p>
<p><strong>Cuando</strong> complete cada paso del registro, </p>
<p><strong>Entonces</strong> la plataforma le proporcionará instrucciones claras y sencillas para llenar los campos correctamente.</p>
<p>Escenario 2: Recomendaciones personalizadas</p>
<p><strong>Dado</strong> que el usuario ha completado el registro de un animal,</p>
<p><strong>Cuando</strong> se detecten necesidades específicas de ese animal,</p>
<p><strong>Entonces</strong> la plataforma le proporcionará recomendaciones automáticas sobre cuidados o tratamientos necesarios.</p>
</td>
<td>2</td>
</tr>
<tr class="even">
<td>E3-US01</td>
<td>Predicción de necesidades alimenticias</td>
<td>
<p><strong>Como</strong> productor agropecuario interesado en en mejorar productividad y la salud del ganado,</p>
<p><strong>Quiero</strong> que la plataforma ofresca predicciones de necesidades alimenticias basandose en las características del animal </p>
<p><strong>Para</strong> poder optimizar el uso de los recursos disponibles y asegurar la salud de los animales. </p>
</td>
<td>
<p>Escenario 1: Recomendaciones de dieta</p>
<p><strong>Dado</strong> que los animales tienen sus datos actualizados,</p>
<p><strong>Cuando</strong> el usuario consulte las necesidades alimenticias,</p>
<p><strong>Entonces</strong> la plataforma le mostrará dietas racomendadas para cada animal.</p>
<p>Escenario 2: Ajuste de cantidad de alimentos
<p><strong>Dado</strong> que el peso y edad de los animales ha cambiado,</p>
<p><strong>Cuando</strong> el sistema analice los nuevos datos</p>
<p><strong>Entonces</strong> se reajustará las recomendaciones de dietas de acuerdo a las nuevas características de los animales</p>
</td>
<td>3</td>
</tr>
<tr class="odd">
<td>E3-US02</td>
<td>Alertas de emergencia por salud animal</td>
<td>
<p><strong>Como</strong> productor agropecuario interesado en la salud de mis animales,</p>
<p><strong>Quiero</strong> recibir alertas caundo alguno de mis animales presente anomalías en su salud</p>
<p><strong>Para</strong> poder tomar las acciones necesarias en la salud de mis animales</p>
</td>
<td>
<p>Escenario 1: Deteccion de anomalias en la salud del animal</p>
<p><strong>Dado</strong> que los animales estan conectado a sensores que monitorean su salud,</p>
<p><strong>Cuando</strong> se detecten datos fuera de lo normal, </p>
<p><strong>Entonces</strong> la plataforma enviara una alerta al dispositivo vinculado con detalles de la salud del animal.</p>
<p>Escenario 2: Planes de acción</p>
<p><strong>Dado</strong> que el sistema ha emitido una alerta del estado de salud del animal,</p>
<p><strong>Cuando</strong> el usuario habra la alerta en su dispositivo,</p>
<p><strong>Entonces</strong> la plataforma le proporcionará tratamientos e instrucciones para atender cualquier emergencia.</p>
</td>
<td>3</td>
</tr>
<tr class="even">
<td>E4-US01</td>
<td>Gestión de inventarios de insumos</td>
<td>
<p><strong>Como</strong> productor agropecuario que desea tener control preciso de los insumos de la granja,</p>
<p><strong>Quiero</strong> gestionar el inventario de los insumos (alimentos, medicinas, etc) dentro de la plataforma </p>
<p><strong>Para</strong> poder tener un mejor manejo de los recursos disponibles y evitar desabastecimiento. </p>
</td>
<td>
<p>Escenario 1: Registro automatico de insumos</p>
<p><strong>Dado</strong> que el usuario ingresa los nuevos insumos al almacén,</p>
<p><strong>Cuando</strong> se registre las entradas de nuevos insumos,</p>
<p><strong>Entonces</strong> la plataforma  actualizara automaticamente el inventario disponible e informara si hace falta algun insumo.</p>
<p>Escenario 2: Generación de informes de insumos
<p><strong>Dado</strong> que el usuario desea analizar el uso de insumos,</p>
<p><strong>Cuando</strong> el sistema genere un reporte de inventario</p>
<p><strong>Entonces</strong> la plataforma mostrara el historial de ingreso y uso de insumos</p>
</td>
<td>4</td>
</tr>
<tr class="odd">
<td>E4-US02</td>
<td>Planificacion de actividades agricolas</td>
<td>
<p><strong>Como</strong> productor agropecuario con actividades programadas,</p>
<p><strong>Quiero</strong> planificar las actividades diarias de mi granja (limpieza, alimentacion, vacunacion, etc.) dentro de la plataforma</p>
<p><strong>Para</strong> poder garantizar un mejor manejo del tiempo para realizar exitosamente todas las actividades diarias</p>
</td>
<td>
<p>Escenario 1: Calendario de actividades</p>
<p><strong>Dado</strong> que el usuario desea tener planificado las actividades diarias</p>
<p><strong>Cuando</strong> se cree un plan en la plataforma, </p>
<p><strong>Entonces</strong> se podra visualizar un cronograma con las tareas hechas y por hacer, ademas recibir notificaciones de recordatorio.</p>
<p>Escenario 2: Asignacion de tareas</p>
<p><strong>Dado</strong> que exiten multiples tareas diarias,</p>
<p><strong>Cuando</strong> el usuario planifique las actividades diarias,</p>
<p><strong>Entonces</strong> se podra asignar tareas a empleados especificos, y ellos recibiran una notificacion con las tareas que se les fueron asignadas.</p>
</td>
<td>4</td>
</tr>
<tr class="even">
    <td>E5-US011 </td>
    <td>Sección sobre los planes del Landing Page de FarmGuard</td>
    <td>
        <p><strong>Como</strong> visitante del sitio estatico,</p>
        <p><strong>Quiero</strong> tener informacion sobre los planes disponibles de la app web. </p>
        <p><strong>Para</strong> poder considerar la adquisicion de uno de estos. </p>
    </td>
    <td>
        <p>Escenario 1: Buscar los planes disponibles.</p>
        <p><strong>Dado</strong> que el visitante esta interesado en los planes disponibles,</p>
        <p><strong>Cuando</strong> accede al landing page a la seccion de planes,</p>
        <p><strong>Entonces</strong> podrá visualizar, los diferentes planes disponibles y leer la informacion clara y precisa.</p>
        <p>Escenario 2: No encuentra los planes disponibles.
        <p><strong>Dado</strong> que el visitante esta interesado en los planes disponibles,</p>
        <p><strong>Cuando</strong>accede al landing page a la seccion de planes,</p>
        <p><strong>Entonces</strong> la seccion de planes no aparece correctamente y no carga la informacion importante.</p>
    </td>
    <td>5</td>
</tr>
<tr class="odd">
    <td>E5-US12</td>
    <td>Sección sobre los beneficios del Landing Page de FarmGuard</td>
    <td>
        <p><strong>Como</strong> visitante del sitio estatico,</p>
        <p><strong>Quiero</strong> tener informacion sobre los beneficios que me brinda la app web. </p>
        <p><strong>Para</strong> poder considerar el uso de esta misma.</p>
    </td>
    <td>
        <p>Escenario 1: Buscar la seccion de beneficios</p>
        <p><strong>Dado</strong> que el visitante esta interesado en los beneficios de la app web,</p>
        <p><strong>Cuando</strong> cuando presione en el boton de Beneficios en el navbar, </p>
        <p><strong>Entonces</strong> se podra visualizar la seccion de los beneficios con sus respectivas imagenes con tiempos de carga cortos.</p>
        <p>Escenario 2: No se encuentra la seccion de beneficios.</p>
        <p><strong>Dado</strong> que el visitante esta interesado en los beneficios de la app web,</p>
        <p><strong>Cuando</strong> cuando presione en el boton de Beneficios en el navbar,</p>
        <p><strong>Entonces</strong> la pagina no lo redirrecciona a la seccion respectiva.</p>
    </td>
    <td>5</td>
</tr>
<tr class="even">
    <td>E5-US013 </td>
    <td>Sección de contactanos del Landing Page de FarmGuard</td>
    <td>
        <p><strong>Como</strong> visitante del sitio estatico,</p>
        <p><strong>Quiero</strong> tener la opcion de poder de contactar con el equipo de desarrollo </p>
        <p><strong>Para</strong> poder tener mas informacion.</p>
    </td>
    <td>
        <p>Escenario 1: Buscar el formulario para contactar al equipo.</p>
        <p><strong>Dado</strong> que el visitante esta interesado contactar con el equipo de desarrollo,</p>
        <p><strong>Cuando</strong> accede al landing page a la seccion de contactanos,</p>
        <p><strong>Entonces</strong> el visitante navega hasta esa seccion para poder llenar su informacion y enviar sus datos para la consulta.</p>
    </td>
    <td>5</td>
</tr>
<tr class="odd">
    <td>E5-US14</td>
    <td>Sección sobre los integrantes del Landing Page de FarmGuard</td>
    <td>
        <p><strong>Como</strong> visitante del sitio estatico,</p>
        <p><strong>Quiero</strong> tener informacion sobre los creadores de la app web. </p>
        <p><strong>Para</strong> poder saber mas sobre el equipo detras de la app web.</p>
    </td>
    <td>
        <p>Escenario 1: Buscar la seccion de Nosotros</p>
        <p><strong>Dado</strong> que el visitante esta interesado en saber del equipo detras de la app web,</p>
        <p><strong>Cuando</strong>presione en el boton de Nosotros en el navbar, </p>
        <p><strong>Entonces</strong> se podra visualizar la seccion Nosotros con sus respectivas imagenes con tiempos de carga cortos y descripciones de cada miembro.</p>
        <p>Escenario 2: No carga la seccion nosotros.</p>
        <p><strong>Dado</strong> que el visitante esta interesado en conocer los desarrolladores de la app web,</p>
        <p><strong>Cuando</strong> presione en el boton de Nosotros en el navbar,</p>
        <p><strong>Entonces</strong> la pagina no lo redirrecciona a la seccion respectiva y no carga la informacion.</p>
    </td>
    <td>5</td>
</tr>
<tr class="even">
    <td>E5-US015 </td>
    <td>Boton de accion del Landing Page a FarmGuard</td>
    <td>
        <p><strong>Como</strong> visitante del sitio estatico,</p>
        <p><strong>Quiero</strong> tener la opcion de poder dirigirme a la app web  </p>
        <p><strong>Para</strong> para poder usarla.</p>
    </td>
    <td>
        <p>Escenario 1: Presiona un boton para dirigirse al app web.</p>
        <p><strong>Dado</strong> que el visitante esta buscando ir a la app web,</p>
        <p><strong>Cuando</strong> presiona el boton de accion,</p>
        <p><strong>Entonces</strong> este le redirige a la app web.</p>
        <p>Escenario 2: Presiona un boton para dirigirse al app web y no pasa nada.</p>
        <p><strong>Dado</strong> que el visitante esta buscando ir a la app web,</p>
        <p><strong>Cuando</strong> presiona el boton de accion,</p>
        <p><strong>Entonces</strong> el boton no realiza ninguna accion.</p>
    </td>
    <td>5</td>
</tr>
</tbody>
</table>
<hr>

## 3.3. Impact Mapping.

La sección de Impact Mapping analizará las consecuencias más amplias y los objetivos estratégicos que buscamos lograr con la implementación de esta aplicación. En lugar de concentrarnos en detalles técnicos o funcionalidades específicas, el Impact Mapping nos ayudará a comprender cómo funciona.

Nuestro proyecto ayudará a lograr objetivos más grandes y cómo tendrá un impacto positivo en varios grupos de interés. Este Impact Mapping nos ayudará a identificar cómo las características de la aplicación se relacionan con los resultados deseados, lo que nos permitirá tomar decisiones informadas sobre qué aspectos priorizar y cómo medir el éxito a largo plazo.


![Impact Mapping](/Assent/img/Impact_Mapping.png)

## 3.4. Product Backlog.
<table>
<colgroup>
<col style="width: 13%" />
<col style="width: 12%" />
<col style="width: 18%" />
<col style="width: 28%" />
<col style="width: 14%" />
<col style="width: 12%" />
</colgroup>
<thead>
<tr class="header">
<th>#Orden</th>
<th>User Story ID</th>
<th>Titulo</th>
<th>Descripcion</th>
<th>Prioridad</th>
<th>Story Points</th>
</tr>
</thead>
<tbody>

<tr class="odd">
<td>1</td>
<td>E1-US01</td>
<td>Gestión digital de la granja</td>
<td><p><strong>Como</strong> productor agropecuario familiarizado con la tecnología,</p>
<p><strong>quiero</strong> digitalizar la gestión de mis animales</p>
<p><strong>para</strong> poder acceder a toda la información desde cualquier dispositivo y agilizar mis operaciones.</p></td>
<td>Alta</td>
<td>8</td>
</tr>
<tr class="even">
<td>2</td>
<td>E1-US02	</td>
<td>Monitoreo de indicadores clave</td>
<td><p><strong>Como</strong> productor agropecuario con expriencia tecnológica,</p>
<p><strong>quiero</strong> monitorear indicadores clave de salud de los animales en tiempo real.</p>
<p><strong>para</strong> tomar decisiones más informadas y mejorar la productividad de mi granja.</p></td>
<td>Alta</td>
<td>8</td>
</tr>
<tr class="odd">
<td>3</td>
<td>E1-US03	</td>
<td>Integración con Equipos y Sensores</td>
<td><p><strong>Como</strong> productor agropecuario interesado en la innovación,</p>
<p><strong>quiero</strong> integrar la plataforma con sensores y dispositivos en mi granja</p>
<p><strong>para</strong> automatizar el monitoreo de la salud de los animales y reducir la intervención manual.</p></td>
<td>Alta</td>
<td>13</td>
</tr>


<tr class="even">
<td>4</td>
<td>E2-US01</td>
<td>Herramientas de aprendizaje</td>
<td><p><strong>Como</strong> productor agropecuario con poca capacitación,</p>
<p><strong>quiero</strong> acceder a recursos educativos dentro de la plataforma</p>
<p><strong>para</strong> aprender más sobre la gestión efectiva de mi granja y mejorar el bienestar de mis animales.</p></td>
<td>Media</td>
<td>5</td>
</tr>

<tr class="odd">
<td>5</td>
<td>E2-US02</td>
<td>Simplificación de tareas</td>
<td><p><strong>Como</strong> productor agropecuario sin experiencia tecnológica,</p>
<p><strong>quiero</strong> que la aplicación tenga una interfaz sencilla y fácil de usar</p>
<p><strong>para</strong> poder gestionar mi granja sin necesidad de conocimientos avanzados en tecnología.</p></td>
<td>Media</td>
<td>5</td>
</tr>

<tr class="even">
<td>6</td>
<td>E2-US03</td>
<td>Guia Paso a Paso</td>
<td><p><strong>Como</strong> productor agropecuario que no ha recibido capacitacion,</p>
<p><strong>quiero</strong> seguir un proceso guiado paso a paso</p>
<p><strong>para</strong> registrar el estado de mis animales y recibir recomendaciones automáticas sobre sus cuidados, sin necesidad de entender términos complejos.</p></td>
<td>Media</td>
<td>5</td>
</tr>

<tr class="odd">
<td>7</td>
<td>E3-US01</td>
<td>Predicción de necesidades alimenticias</td>
<td><p><strong>Como</strong> productor agropecuario interesado en en mejorar productividad y la salud del ganado,</p>
<p><strong>quiero</strong> que la plataforma ofresca predicciones de necesidades alimenticias basandose en las características del animal</p>
<p><strong>para</strong> poder optimizar el uso de los recursos disponibles y asegurar la salud de los animales.</p></td>
<td>Media</td>
<td>5</td>
</tr>

<tr class="even">
<td>8</td>
<td>E3-US02</td>
<td>Alertas de emergencia por salud animal</td>
<td><p><strong>Como</strong> productor agropecuario interesado en la salud de mis animales,</p>
<p><strong>quiero</strong> recibir alertas caundo alguno de mis animales presente anomalías en su salud</p>
<p><strong>para</strong> poder tomar las acciones necesarias en la salud de mis animales.</p></td>
<td>Alta</td>
<td>13</td>
</tr>


<tr class="odd">
<td>9</td>
<td>E4-US01</td>
<td>Gestión de inventarios de insumos</td>
<td><p><strong>Como</strong> productor agropecuario que desea tener control preciso de los insumos de la granja,</p>
<p><strong>quiero</strong> gestionar el inventario de los insumos (alimentos, medicinas, etc) dentro de la plataforma</p>
<p><strong>para</strong> poder tener un mejor manejo de los recursos disponibles y evitar desabastecimiento.</p></td>
<td>Alta</td>
<td>8</td>
</tr>

<tr class="even">
<td>10</td>
<td>E4-US02</td>
<td>Planificacion de actividades agricolas</td>
<td><p><strong>Como</strong> productor agropecuario con actividades programadas,</p>
<p><strong>quiero</strong> planificar las actividades diarias de mi granja (limpieza, alimentacion, vacunacion, etc.) dentro de la plataforma</p>
<p><strong>para</strong> poder garantizar un mejor manejo del tiempo para realizar exitosamente todas las actividades diarias.</p></td>
<td>Media</td>
<td>5</td>
</tr>
