# Capítulo IV: Product Design
## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines
### 4.1.2. Web Style Guidelines

## 4.2. Information Architecture
### 4.2.1. Organization Systems

### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems

### 4.2.5. Navigation Systems
## 4.3 Landing Page UI Design
### 4.3.1 Landing Page Wireframe
En esta sección se mostrarán el diseño de baja fidelidad de nuestro landing page.
Link hacia los Wireframes creados en Figma: <a href="https://www.figma.com/design/r9kTUKu0IorsALAp1I9BoJ/Figma-basics?node-id=601-10&t=pnQcf5k1YsFhwerK-1">Figma</a>

<img src="../assets/chapter-04/Landing Page Wireframes/landing wireframe1.png" alt="Landing Page Home">
<img src="../assets/chapter-04/Landing Page Wireframes/landing wireframe2.png" alt="About Us">
<img src="../assets/chapter-04/Landing Page Wireframes/landing wireframe3.png" alt="Services">
<img src="../assets/chapter-04/Landing Page Wireframes/landing wireframe4.png" alt="Princing">
<img src="../assets/chapter-04/Landing Page Wireframes/landing wireframe5.png" alt="Team">

### 4.3.2 Landing Page Mock-Up
En esta sección se mostrarán el diseño de cómo sería nuestro landing page.
Link hacia los Mock-ups creados en Figma: <a href="https://www.figma.com/design/r9kTUKu0IorsALAp1I9BoJ/Figma-basics?node-id=601-10&t=pnQcf5k1YsFhwerK-1">Figma</a>

<img src="../assets/chapter-04/Landing Page Mockup/landing page mockup2.png" alt="Landing Page Home">
<img src="../assets/chapter-04/Landing Page Mockup/landing page mockup3.png" alt="About Us">
<img src="../assets/chapter-04/Landing Page Mockup/landing page mockup4.png" alt="Services">
<img src="../assets/chapter-04/Landing Page Mockup/landing page mockup5.png" alt="Pricing">
<img src="../assets/chapter-04/Landing Page Mockup/landing page mockup1.png" alt="Team">

## 4.4 Web Applications UX/UI Design
### 4.4.1 Web Applications Wireframes
En esta sección se presentarán el diseño de baja fidelidad para las funciones más importantes dentro del Web Application.
Link hacia los Wireframes creados en Figma: <a href="https://www.figma.com/design/r9kTUKu0IorsALAp1I9BoJ/Figma-basics?node-id=601-10&t=pnQcf5k1YsFhwerK-1">Figma</a>
<img src="../assets/chapter-04/Web Application Wireframes/Web Application Wireframe1.png" alt="Landing Page Home">
<img src="../assets/chapter-04/Web Application Wireframes/Web Application Wireframe2.png" alt="Courses">
<img src="../assets/chapter-04/Web Application Wireframes/Web Application Wireframe3.png" alt="Categorie">
<img src="../assets/chapter-04/Web Application Wireframes/Web Application Wireframe4.png" alt="Course Example">
<img src="../assets/chapter-04/Web Application Wireframes/Web Application Wireframe5.png" alt="Landing Page Home">
<img src="../assets/chapter-04/Web Application Wireframes/Web Application Wireframes6.png" alt="Landing Page Home">
<img src="../assets/chapter-04/Web Application Wireframes/Web Application Wireframe7.png" alt="Landing Page Home">

### 4.4.2 Web Application Wireflow Diagrams
Wireflow Diagram 1: Proceso de Registro para ambos segmentos.
<img src="../assets/chapter-04/Web Application Wireflow Diagrams/web wireflow1.png" alt="wireflow register">
Wireflow Diagram 2: Proceso de pago para acceder a un curso.
<img src="../assets/chapter-04/Web Application Wireflow Diagrams/web wireflow2.png" alt="wireflow pay course">
Wireflow Diagram 3: Proceso de creación de un curso.
<img src="../assets/chapter-04/Web Application Wireflow Diagrams/web wireflow3.png" alt="wireflow create a course">

### 4.4.3 Web Application Mock-Up
### 4.4.4 Web Applicatin Userflow Diagrams
### 4.6.2. Software Architecture Container Diagrams
### 4.6.3. Software Architecture Components Diagrams
## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
<img src="../assets/chapter-04/Diagrama_clases.png">

### 4.7.2. Class Dictionary

- Persona:
Esta es una clase principal que comparte atributos como nombre, apellido y otros datos pertinentes con sus clases derivadas. Además, funciona como la clase principal para dos clases adicionales. Su propósito es determinar el tipo de persona que está conectada al sistema.

- User:
Esta es una clase derivada que guarda toda la información relacionada con una persona cuando actúa como usuario en la plataforma. En esta clase se registran los datos sobre los comentarios realizados por el usuario y los cursos en los que está inscrito. Además, sirve de punto de conexión para que otras clases puedan interactuar con la información del usuario.

- Expert:
Esta clase derivada se encarga de almacenar la información de una persona cuando se desempeña como experto en la plataforma. Registra detalles relacionados con el experto y se conecta con otras clases que requieren acceso a esta información, como los cursos creados o los artículos escritos por el experto.

- Account:
Esta clase representa la cuenta de usuario registrada en el sistema. Administra funciones como el inicio de sesión y el registro, además de guardar el correo electrónico y la contraseña del usuario, ofreciendo también opciones para recuperar o modificar la información de acceso.

- Suscription:
Esta clase administra todo lo relacionado con las suscripciones de los usuarios. Aquí se almacenan los detalles de la cuenta asociada a la suscripción y se valida el tipo de persona a la que pertenece. También incluye métodos para definir el tipo de pago y el estado de la suscripción.

- Course:
La función principal de esta clase es gestionar los atributos relacionados con los cursos, como el nombre y la descripción, así como toda la información que compone el curso, incluidos videos y otros materiales.

- ExpertCourse:
Esta clase vincula la información entre expertos y cursos. Registra qué experto creó un curso específico y guarda todos los detalles del mismo. Además, permite rastrear qué usuario adquirió el curso y la calificación que recibió de los diferentes usuarios.

- Articles:
Esta clase se enfoca en los artículos informativos que los expertos publican en la plataforma. Aquí se almacena quién fue el autor del artículo y la fecha en que fue publicado.

- Comments:
Esta clase administra los comentarios que los usuarios pueden hacer en las publicaciones de los expertos. Almacena el contenido del comentario y el artículo al que está dirigido.

- Community:
Esta clase se encarga de gestionar las comunidades que los usuarios pueden formar dentro de la plataforma. Mantiene un registro de todos los usuarios que son parte de una comunidad y ofrece funciones para crear nuevas comunidades y facilitar la comunicación entre sus miembros.

- SuscriptionPrice:
Esta clase administra la información sobre los precios de las suscripciones y su frecuencia de pago. Está relacionada con la tabla de enumeración Frequency, que especifica si la suscripción es mensual o anual.
## 4.8. Database Design
### 4.8.1. Database Diagram
