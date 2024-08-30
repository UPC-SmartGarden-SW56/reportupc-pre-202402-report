# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping

Aquí se expone el análisis de los escenarios, organizando una tabla que detalla la situación que necesita ser optimizada para el segmento objetivo. Se examinan los pasos a seguir y se describe cómo se perciben.

**Segmento 1: Owner**

<img src="../assets/chapter-03/To-be-scenario/ToBe1.jpg" alt="Imagen To Be Mapping 1">

**Segmento 2: User**

<img src="../assets/chapter-03/To-be-scenario/ToBe2.jpg" alt="Imagen To Be Mapping 2">

## 3.2. User Stories

<table >
    <tr>
        <th>Epic / Story ID</th>
        <th>Título</th>
        <th>Descripción</th>
        <th>Criterios de Aceptación</th>
        <th>Relacionado con (Epic ID)</th>
    </tr>
    <tr>
        <td>EP01</td>
        <td>Landing page para la aplicacion Smart Garden</td>
        <td><b>Como</b> principiante/Experto de Smart Garden <b>Quiero</b> ingresar una landing page <b>Para</b> informarme sobre la aplicación y su equipo de desarrollo.</td>
        <td>No corresponde</td>
        <td>No corresponde</td>
    </tr>
    <tr>
        <td>EP02</td>
        <td>Gestión de cuenta de usuario</td>
        <td><b>Como</b> principiante/Experto de Smart Garden <b>Quiero</b> crear, visualizar, eliminar y editar mi cuenta <b>Para</b> tener mis datos actualizados y comenzar a hacer uso de la aplicación correctamente.</td>
        <td>No corresponde</td>
        <td>No corresponde</td>
    </tr>
    <tr>
        <td>EP03</td>
        <td>Gestión de cursos en venta</td>
        <td><b>Como</b> experto en Smart Garden <b>Quiero</b> agregar y gestionar mis cursos <b>Para</b> asegurarme que estén disponibles para la venta.</td>
        <td>No corresponde</td>
        <td>No corresponde</td>
    </tr>
    <tr>
        <td>EP04</td>
        <td>Gestión de compra de cursos</td>
        <td><b>Como</b> Principiante de Smart Garden <b>Quiero</b> gestionar mis cursos comprados <b>Para</b> planificar y controlar mi progreso. </td>
        <td>No corresponde</td>
        <td>No corresponde</td>
    </tr>
    <tr>
        <td>EP05</td>
        <td>Gestión de planes</td>
        <td><b>Cómo</b> Experto de Smart Garden <b>Quiero</b> tener una gestión y control de mi plan <b>Para</b> poder adquirirlo y cancelarlo cuando lo requiera</td>
        <td>No corresponde</td>
        <td>No corresponde</td>
    </tr>
    <tr>
        <td>US01</td>
        <td>Implementación de la sección Inicio de la Landing Page</td>
        <td><b>Como</b> visitante de la landing page
        <b>Quiero</b> visualizar la sección "Inicio"
        <b>Para</b> tener una primera vista del producto</td>
        <td>
            <b>Scenario 1: Visualizar sección Inicio</b> <br/>
            <b>Dado que</b> el visitante ingresa a la página<br/>
            <b>Cuando</b> la página cargue <br/>
            <b>Entonces</b> se muestra una sección llamativa que anime al usuario a usar la aplicación.<br/>
            <br>
            <b>Scenario 2: Error en el sistema </b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page<br/>
            <b>Cuando</b> ocurra algún problema con el sistema <br/>
            <b>Entonces</b> no se muestra la sección Home<br/>
            <b>Y</b> se muestra un mensaje de error.<br/>
        <td>EP01</td>
    </tr>
    <tr>
        <td>US02</td>
        <td>Implementación de la sección "Sobre Nosotros" de la Landing Page</td>
        <td><b>Como</b> visitante de la landing page
        <b>Quiero</b> visualizar la sección "Sobre Nosotros"
        <b>Para</b> tener información de la startup.</td>
        <td>
            <b>Scenario 1: Acceder a la sección "Sobre Nosotros"</b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page <br/>
            <b>Cuando</b> navegue hasta la sección “Sobre Nosotros” <br/>
            <b>Entonces</b> se muestra información importante sobre la startup. <br/>
            <br>
            <b>Scenario 2: Error en el sistema </b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page<br/>
            <b>Cuando</b> ocurra algún problema con el sistema <br/>
            <b>Entonces</b> no se muestra la sección Home<br/>
            <b>Y</b> se muestra un mensaje de error.<br/>
        <td>EP01</td>
    </tr>
<tr>
        <td>US03</td>
        <td>Implementación de la sección "Servicios" de la Landing Page</td>
        <td><b>Como</b> visitante de la landing page
        <b>Quiero</b> visualizar la sección "Servicios"
        <b>Para</b> tener información de los servicios ofrecidos por la aplicación</td>
        <td>
            <b>Scenario 1: Acceder a la sección "Servicios"</b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page<br/>
            <b>Cuando</b> navegue hasta la sección “Servicios” <br/>
            <b>Entonces</b> se muestra información sobre los servicios que ofrece Smart Garden<br/>
            <br>
            <b>Scenario 2: Error en el sistema </b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page<br/>
            <b>Cuando</b> ocurra algún problema con el sistema <br/>
            <b>Entonces</b> no se muestra la sección Home<br/>
            <b>Y</b> se muestra un mensaje de error.<br/>
        <td>EP01</td>
    </tr>
 <tr>
        <td>US04</td>
        <td>Implementación de la sección "Planes" de la Landing Page</td>
        <td><b>Como</b> visitante de la landing page
        <b>Quiero</b> visualizar la sección "Planes"
        <b>Para</b> tener información de las membresías de la aplicación</td>
        <td>
            <b>Scenario 1: Acceder a la sección "Planes"</b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page<br/>
            <b>Cuando</b> navegue hasta la sección “Planes” <br/>
            <b>Entonces</b> se muestra la información relacionada a los planes de pago que se ofrecen y cuáles son los beneficios de cada uno de estos.<br/>
            <br>
            <b>Scenario 2: Error en el sistema </b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page<br/>
            <b>Cuando</b> ocurra algún problema con el sistema <br/>
            <b>Entonces</b> no se muestra la sección Home<br/>
            <b>Y</b> se muestra un mensaje de error.<br/>
        <td>EP01</td>
    </tr>
 <tr>
        <td>US05</td>
        <td>Implementación de la sección "About the Team" de la Landing Page</td>
        <td><b>Como</b> visitante de la landing page
        <b>Quiero</b> visualizar la sección "About the Team"
        <b>Para</b> tener información de los miembros que conforman la startup.</td>
        <td>
            <b>Scenario 1: Conocer al equipo en "About the Team"</b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page <br/>
            <b>Cuando</b> navegue hasta la sección “About the Team”<br/>
            <b>Entonces</b> se muestra la información correspondiente a los videos about the project y about the team, además de la información de cada uno de los miembros.<br/>
            <br>
            <b>Scenario 2: Error en el sistema </b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page<br/>
            <b>Cuando</b> ocurra algún problema con el sistema <br/>
            <b>Entonces</b> no se muestra la sección Home<br/>
            <b>Y</b> se muestra un mensaje de error.<br/>
        <td>EP01</td>
    </tr>
 <tr>
        <td>US06</td>
        <td> Landing Page Responsiva a diferentes tamaños de pantalla </td>
        <td><b>Cómo</b> visitante interesado 
        <b>Quiero</b> que la landing page tenga un diseño responsivo
        <b>Para</b> acceder a ella desde cualquier dispositivo.</td>
        <td>
            <b>Scenario 1: Acceder a la landing page desde un ordenador</b> <br/>
            <b>Dado que</b> el visitante se encuentre usando un ordenador de escritorio <br/>
            <b>Cuando</b> ingrese a la landing page <br/>
            <b>Entonces</b> se muestra la landing page adaptada correctamente a la pantalla del ordenador. <br/>
            <br>
            <b>Scenario 2: Acceder a la landing page desde un dispositivo móvil</b> <br/>
            <b>Dado que</b> el visitante se encuentre usando un dispositivo móvil <br/>
            <b>Cuando</b> ingrese a la landing page <br/>
            <b>Entonces</b> se muestra la landing page adaptada correctamente a la pantalla del dispositivo móvil. <br/>
        <td>EP01</td>
    </tr>
 <tr>
        <td>US07</td>
        <td>Acceder a la aplicación desde la landing page </td>
        <td><b>Cómo</b> visitante de la landing page 
        <b>Quiero</b> poder acceder a la aplicación Smart Garden desde la landing page
        <b>Para</b> comenzar a utilizar las funcionalidades ofrecidas</td>
        <td>
            <b>Scenario 1: Usuario ingresa a aplicación</b> <br/>
            <b>Dado que</b> el visitante se encuentra en la landing page <br/>
            <b>Cuando</b> seleccione la opción que permite el acceso al software elaborado<br/>
            <b>Entonces</b> es redirigido a la aplicación desplegada<br/>
            <br>
            <b>Scenario 2: Fallo en el acceso a la aplicación</b> <br/>
            <b>Dado que</b> el visitante se encuentre en la landing page <br/>
            <b>Cuando</b> seleccione la opción que permite el acceso al software elaborado y ocurra un error en el proceso de redirección<br/>
            <b>Entonces</b> el usuario obtiene un mensaje de error.<br/>
        <td>EP01</td>
    </tr>
    <tr>
        <td>US08</td>
        <td>Registrar usuario</td>
        <td><b>Cómo</b> visitante de la aplicación web de Smart Garden
        <b>Quiero</b> poder crear una cuenta personal
        <b>Para</b> comenzar a hacer uso de la aplicación como Principiante/Experto.</td>
        <td>
            <b>Scenario 1: Usuario ingresa credenciales válidas.</b> <br/>
            <b>Dado que</b> el visitante desee crear una cuenta personal en la aplicación Smart Garden <br/>
            <b>Cuando</b> ingrese las credenciales de una cuenta inexistente en la base de datos Smart Garden, una contraseña que cumple con todos los requisitos de seguridad y acepte los términos y condiciones de uso <br/>
            <b>Entonces</b> se creará la cuenta de usuario.<br/>
            <br>
            <b>Scenario 2: Usuario ingresa credenciales incorrectas.</b> <br/>
            <b>Dado que</b> Usuario ingresa credenciales incorrectas. <br/>
            <b>Cuando</b> ingrese una dirección de correo electrónico o contraseña que no cumplen con los requisitos especificados<br/>
            <b>Entonces</b> se le denegará la operación<br/>
        <td>EP02</td>
    </tr>
    <tr>
        <td>US09</td>
        <td>Iniciar sesión</td>
        <td><b>Cómo</b> Principiante/Experto de Smart Garden 
        <b>Quiero</b> iniciar sesión
        <b>Para</b> acceder a los beneficios que ofrece la aplicación.</td>
        <td>
            <b>Scenario 1: Usuario ingresa credenciales válidas </b> <br/>
            <b>Dado que</b> el usuario posee una cuenta en la aplicación Smart Garden <br><b>Y</b> desee iniciar sesión <br/>
            <b>Cuando</b> ingrese las credenciales necesarias correctamente<br/>
            <b>Entonces</b> el sistema permitirá el acceso a la aplicación<br/>
            <br>
            <b>Scenario 2: Usuario ingresa credenciales incorrectas</b> <br/>
            <b>Dado que</b> el usuario posee una cuenta en la aplicación Smart Garden <br><b>Y</b> desea iniciar sesión <br/>
            <b>Cuando</b> ingrese alguna credencial de manera incorrecta <br/>
            <b>Entonces</b> el sistema denegará la solicitud<br/>
        <td>EP02</td>
    </tr>
    <tr>
        <td>US10</td>
        <td>Visualizar perfil de usuario</td>
        <td><b>Cómo</b> Principiante/Experto de Smart Garden 
        <b>Quiero</b> visualizar mi perfil personal 
        <b>Para</b> visualizar mis datos actuales</td>
        <td>
            <b>Scenario 1: Acceder al perfil personal</b> <br/>
            <b>Dado que</b> el usuario desee visualizar su información personal <br/>
            <b>Cuando</b>  ingrese a su perfil <br/>
            <b>Entonces</b> obtendrá toda la información que registró previamente<br/>
            <br>
            <b>Scenario 2: Problema al acceder al perfil personal </b> <br/>
            <b>Dado que</b> el usuario desee visualizar su información personal  <br/>
            <b>Cuando</b> intente ingresar a su perfil <br><b>Y</b> experimente un error de conexión o de servidor <br/>
            <b>Entonces</b> no se visualizarán los datos del perfil <br/>
        <td>EP02</td>
    </tr>
    <tr>
        <td>US11</td>
        <td>Cambiar datos personales </td>
        <td><b>Cómo</b> Principiante/Experto de Smart Garden 
        <b>Quiero</b> cambiar los datos asociados a mi perfil
        <b>Para</b> actualizar la información</td>
        <td>
            <b>Scenario 1: Cambiar contraseña</b> <br/>
            <b>Dado que</b> el usuario quiera cambiar su contraseña <br/>
            <b>Cuando</b> ingrese la nueva contraseña, esta sea validada por el sistema <br><b>Y</b> el usuario confirme su intención de proceder con el cambio<br/>
            <b>Entonces</b> la nueva clave será guardada y la información actualizada.<br/>
            <br>
            <b>Scenario 2: Cambiar nombre</b> <br/>
            <b>Dado que</b> el usuario quiera cambiar su nombre<br/>
            <b>Cuando</b> ingrese el nuevo nombre, esta sea validada por el usuario <br><b>Y</b> confirme su intención de proceder con el cambio <br/>
            <b>Entonces</b> el nuevo nombre será guardado y la información actualizada<br/>
            <br>
            <b>Scenario 3: Cambiar foto</b> <br/>
            <b>Dado que</b> el usuario quiera cambiar su foto <br/>
            <b>Cuando</b> ingrese la nueva foto, esta sea validada por el usuario <br><b>Y</b> confirme su intención de proceder con el cambio<br/>
            <b>Entonces</b> la nueva foto será guardada y la información actualizada<br/>
            <br>
            <b>Scenario 4: Cambiar número de celular</b> <br/>
            <b>Dado que</b> el usuario quiera cambiar su número de celular <br/>
            <b>Cuando</b> ingrese el nuevo número, esta sea validada por el sistema <br><b>Y</b> el usuario confirme su intención de proceder con el cambio <br/>
            <b>Entonces</b> el nuevo número será guardado y la información actualizada<br/>
            <br>
            <b>Scenario 5: Ingreso de datos inválidos</b> <br/>
            <b>Dado que</b> el usuario quiera cambiar su información <br/>
            <b>Cuando</b> ingrese datos inválidos<br/>
            <b>Entonces</b> se mostrará un mensaje de dato no válido<br/>
            <br>
            <b>Scenario 6: No cambiar información</b> <br/>
            <b>Dado que</b> el usuario no quiera cambiar su información <br/>
            <b>Cuando</b> aparezca el pop up para confirmar el cambio <br><b>Y</b> seleccione la opción para cancelar cambio<br/>
            <b>Entonces</b> el pop up desaparecerá y el cambio no se realizará<br/>
        <td>EP02</td>
    </tr>
    <tr>
        <td>US12</td>
        <td>Eliminar cuenta de usuario</td>
        <td><b>Cómo</b> Principiante/Experto de Smart Garden 
        <b>Quiero</b> eliminar mi cuenta de usuario
        <b>Para</b> dejar de usar los servicios de la aplicación</td>
        <td>
            <b>Scenario 1: Principiante/Experto elimina cuenta de usuario </b> <br/>
            <b>Dado que</b> el Principiante/Experto desee eliminar su cuenta de usuario <br/>
            <b>Cuando</b> seleccione la opción de eliminar cuenta en su perfil <br><b>Y</b> confirme su intención para proceder con la operación<br/>
            <b>Entonces</b> el sistema eliminará la cuenta y todos los datos almacenados. <br/>
            <br>
            <b>Scenario 2: Principiante/Experto no elimina cuenta de usuario</b> <br/>
            <b>Dado que</b> el Principiante/Experto desee eliminar su cuenta de usuario <br/>
            <b>Cuando</b> niegue su intención para proceder con la operación<br/>
            <b>Entonces</b> el sistema regresará a la vista de su cuenta sin eliminar los datos.<br/>
        <td>EP02</td>
    </tr>
    <tr>
        <td>US13</td>
        <td>Publicar curso</td>
        <td><b>Cómo</b> Experto en hidroponia  
        <b>Quiero</b> crear publicaciones con sobre como crear un huerto hidropónico de un tipo específico
        <b>Para</b> que pueda ser comprado por un Principiante</td>
        <td>
            <b>Scenario 1: Experto publica su curso en Smart Garden </b> <br/>
            <b>Dado que</b> el Experto cuente con una cuenta en nuestra aplicación <br><b>Y</b> se encuentre el la opción de “Publicar curso” <br/>
            <b>Cuando</b> llene todas las casillas obligatorias para publicar su curso <br><b>Y</b> le de al botón “Publicar”<br/>
            <b>Entonces</b> el sistema le muestra un aviso de que su curso ha sido publicado. <br/>
            <br>
           <b>Scenario 2: Experto cancela la publicación de su curso</b> <br/>
            <b>Dado que</b> el Experto cuente con una cuenta en nuestra aplicación <br><b>Y</b> se encuentre el la opción de “Publicar curso”  <br/>
            <b>Cuando</b> le de al botón de “Cancelar”<br/>
            <b>Entonces</b> el sistema le muestra un aviso de que se ha cancelado la publicación.<br/>
            <br>
           <b>Scenario 3: Experto no publica su scooter </b> <br/>
            <b>Dado que</b> el Experto cuente con una cuenta en nuestra aplicación <br><b>Y</b> se encuentre el la opción de “Publicar curso” <br/>
            <b>Cuando</b> no llene todas las casillas obligatorias para publicar su curso <br><b>Y</b> le de al botón “Publicar”<br/>
            <b>Entonces</b> el sistema le muestra un aviso de que se no ha completado la información requerida <br><b>Y</b> no se publica su curso<br/>
        <td>EP03</td>
    </tr>
    <tr>
        <td>US14</td>
        <td>Visualizar cursos publicados</td>
        <td><b>Cómo</b> Experto  
        <b>Quiero</b> visualizar mis publicaciones con la información y especificaciones de mis cursos
        <b>Para</b> verificar que toda la información ingresada es correcta y actualizada.</td>
        <td>
            <b>Scenario 1: Experto visualiza su curso en Smart Garden </b> <br/>
            <b>Dado que</b> el Experto se encuentre en la aplicación de Smart Garden <br/>
            <b>Cuando</b> se dirija a la opción de “Ver mis cursos”<br/>
            <b>Entonces</b> el sistema le mostrará la información de los cursos publicados.<br/>
            <br>
            <b>Scenario 2: Experto cancela la visualización de cursos en Smart Garden </b> <br/>
            <b>Dado que</b> el Owner se encuentre en la aplicación de Smart Garden<br/>
            <b>Cuando</b> se dirija a la opción de “Ver mis cursos” <br><b>Y</b> le de al botón de “Salir” <br/>
            <b>Entonces</b> el sistema lo sacará de la ventana de “Ver mis cursos”<br/>
        <td>EP03</td>
    </tr>
    <tr>
        <td>US15</td>
        <td>Editar curso</td>
        <td><b>Cómo</b> Experto de un scooter eléctrico 
        <b>Quiero</b> editar la publicación un curso
        <b>Para</b> que la información proporcionada a los clientes esté siempre actualizada.</td>
        <td>
            <b>Scenario 1: Experto edita la publicación de su curso en Smart Garden</b> <br/>
            <b>Dado que</b> el Experto se encuentra en el apartado de “Mis cursos” <br><b>Y</b> le de al botón “Editar” de una publicación. <br/>
            <b>Cuando</b> actualice correctamente la información<br/>
            <b>Entonces</b> el sistema le muestra un aviso de que su curso ha sido actualizado<br/>
            <br>
            <b>Scenario 2: Experto cancela la edición de la publicación de su scooter en Smart Garden</b> <br/>
            <b>Dado que</b> el Owner se encuentra en el apartado de “Mis cursos” <br><b>Y</b> le de al botón “Editar” de una publicación. <br/>
            <b>Cuando</b> le de al botón de “Cancelar”<br/>
            <b>Entonces</b> el sistema cierra la ventana de edición de publicación<br/>
            <br>
            <b>Scenario 3: Owner no edita la publicación de su scooter en Smart Garden</b> <br/>
            <b>Dado que</b> el Owner se encuentra en el apartado de “Mis cursos” <br><b>Y</b> le de al botón “Editar” de una publicación. <br/>
            <b>Cuando</b> ingrese incorrectamente la información <br><b>Y</b> le de al botón de “Aceptar”<br/>
            <b>Entonces</b> el sistema le muestra un aviso de que su scooter no ha sido actualizado.<br/>
        <td>EP03</td>
    </tr>
</table>

