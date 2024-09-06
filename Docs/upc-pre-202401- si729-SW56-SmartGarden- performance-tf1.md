# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
En este apartado, se mencionarán los distintos productos de software empleados por el equipo de desarrollo, para llevar acabo las actividades relacionadas con la elaboración del proyecto.
### 5.1.2. Source Code Management
### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration
## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1
| Sprint 1                         | Implementación de funcionalidades y diseño de la aplicación.                                                                                                                                              |
| -------------------------------- |-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Sprint Planning Background       |
| Date                             | 21/08/2024                                                                                                                                                                                                |
| Time                             | 18:00 horas (GMT-5)                                                                                                                                                                                       |
| Location                         | Reunión realizada mediante Discord                                                                                                                                                                        |
| Prepared By                      | De La Cruz Villarreal, Carlos Alejandro                                                                                                                                                                   |
| PAttendees (to planning meeting) | <li>De La Cruz Villarreal, Carlos Alejandro </li>	 <li>Jara Benites, Quique Vladimir </li> <li>Justo Yauricas, Alexander Poalo </li> <li>Conde Isla, Camila Alessandra </li> <li>Vera Nuñez, Nicolas Alejandro</li> |
|Sprint n -1 Review|
|Resumen| Se creará la organización de UPC-SmartGarden-SW56 en Github, se crea las ramas, se separa los trabajos a realizar como entrevistas, wireframe y mock-up                                                               |
|Sprint n -1 Retrospective|
|Resumen| Se implemento para el landing se ha realizado mediante html css y js.                                                                                                                                     |
| **Sprint Goal & User Stories**   |
| Sprint 1 Velocity                | 21 points                                                                                                                                                                                                 |
| Sum of Story Points              | 21 points                                                                                                                                                                                                 |

#### 5.2.1.2. Sprint Backlog 1
| id   | Title                 | Id  | Title                                                    | Description                                                                                                   | Estimations(Hours) | Assigned To        | Status(To-do /InProcess/ToReview/Done) |
| ---- |-----------------------| --- |----------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|--------------------|--------------------|---------------------------------------|
| GW01 | Apartado del Header   | G01 | Header responsive (Desarrollado en HTML y CSS).         | Desarrollo e implementación de los estilos que corresponden al encabezado (Header). Debe ser responsive.      | 3                  | Nicolas Vera      | Done                                  |
| GW02 | Apartado del Footer   | G02 | Footer responsive (Desarrollado en HTML y CSS).         | Desarrollo e implementación de los estilos que corresponden al pie de página (Footer). Debe ser responsive.   | 2                  | Nicolas Vera       | Done                                  |
| GW03 | Apartado del about us         | G03 | Sección "About us"(Desarrollado en HTML y CSS)                             | Desarrollo e implementación de los estilos que corresponden a la información acerca del startup. Debe ser responsive.           | 3                  | Alexander Justo       | Done                                  |
| GW04 | Apartado del about the team     | G04 | Información del equipo (Desarrollado en HTML y CSS)                             | Desarrollo e implementación de los estilos que corresponden a la información del equipo de desarrollo. Debe ser responsive.                  | 3                  | Carlos de la Cruz | Done                                  |
| GW05 | Apartado del Service     | G05 | Sección "Service"(Desarrollado en HTML y CSS)           | Desarrollo e implementación de los estilos que corresponden a la información del sobre el servicio. Debe ser responsive.    | 3                  | Quique Jara       | Done                                  |
| GW06 | Apartado del Subscription  | G06 | Sección "Subscription"(Desarrollado en HTML y CSS)      | Desarrollo e implementación de los estilos que corresponden a la información de las suscripciones. Debe ser responsive. | 3                  | Camila Conde      | Done                                  |

#### 5.2.1.3. Development Evidence for Sprint Review
| Repository   | Branch               | Commit Id | Commit Message                         | Commit Message Body | Committed on (Date) |
|--------------|----------------------|-----------|----------------------------------------|---------------------|---------------------|
| Landing-Page | feature/about-team    | fc88ec6   | Add files via upload                   | -                   | 2/09/2024           |
| Landing-Page | feature/about-us      | fc88ec6   | Add files via upload                   | -                   | 2/09/2024           |
| Landing-Page | feature/about-team    | 25f080f   | Probando about team                    | -                   | 4/09/2024           |
| Landing-Page | feature/about-team    | 66449df   | About the team previous                | -                   | 4/09/2024           |
| Landing-Page | feature/about-team    | 888f544   | About the team last change             | -                   | 5/09/2024           |
| Landing-Page | feature/about-us      | 57a587f   | feat(header): add about us and images  | -                   | 5/09/2024           |
| Landing-Page | feature/about-us      | e4c30c8   | Merge remote-tracking branch 'origin/feature/about-us' into feature/a... | - | 5/09/2024 |
| Landing-Page | feature/header        | b7a0912   | feat(header): add header and background | -                   | 5/09/2024           |
| Landing-Page | feature/services      | b7a0912   | feat(header): add header and background | -                   | 5/09/2024           |
| Landing-Page | feature/subscription  | b7a0912   | feat(header): add header and background | -                   | 5/09/2024           |
| Landing-Page | feature/footer        | 14f4a07   | feat: add footer and info              | -                   | 5/09/2024           |
| Landing-Page | feature/footer        | fc74362   | feat: Add more stuff to the footer     | -                   | 6/09/2024           |

#### 5.2.1.4. Testing Suite Evidence for Sprint Review

En el proceso de desarrollo de la landing page, se aplicaron diversas estrategias de prueba para garantizar su correcto funcionamiento y adaptabilidad en diferentes entornos. A continuación se detallan las herramientas utilizadas y los enfoques adoptados

**1. Uso de Live Server de Microsoft Visual Studio Code**

Propósito:
- Live Server se implementó para facilitar el desarrollo y la prueba de la landing page de manera local.

Descripción:
- Esta herramienta permitió la visualización dinámica de la landing page en el navegador web, lo que agilizó el proceso de desarrollo al mostrar los cambios en tiempo real sin necesidad de recargar manualmente la página.


**2. Firefox Developer para Pruebas de Dimensiones Móviles**

Propósito:
- Firefox Developer fue empleado para verificar la compatibilidad y el aspecto visual de la landing page en dispositivos móviles.

Descripción:
- Esta herramienta proporcionó un entorno de desarrollo amigable para simular diferentes dimensiones de pantalla y validar el diseño responsivo de la landing page en dispositivos móviles.


**3. Aprovechamiento de las Propiedades del Navegador para Mejorar el Responsive**

Propósito:
- Se aprovecharon las características específicas del navegador para mejorar la compatibilidad con CSS Grid y el diseño responsivo.

Descripción:
- Se exploraron las capacidades de inspección de elementos del navegador para ajustar y optimizar el diseño de la landing page, especialmente en lo que respecta al uso de CSS Grid. Además, se utilizaron las herramientas de depuración del navegador para identificar y corregir cualquier problema de diseño responsivo.


Estas estrategias de prueba garantizaron la funcionalidad, la estética y la adaptabilidad de la landing page en diversos dispositivos y navegadores, contribuyendo así a una experiencia de usuario excepcional.

#### 5.2.1.5. Execution Evidence for Sprint Review
En el Sprint 1, se logró un avance parcial en la implementación y despliegue de la Landing Page. Esta muestra diversas secciones donde los usuarios pueden acceder a información clave sobre el producto y la startup. A continuación, se presentan algunas evidencias:

#### 5.2.1.6. Services Documentation Evidence for Sprint Review
En este primer Sprint, solo se trabajó en la implementación del Landing Page, por lo que no se requirieron servicios adicionales.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review
En el Sprint 1, se logró desarrollar y desplegar el Landing Page de SmartGarden, cuyo objetivo es atraer clientes y explicar los detalles de nuestra startup y su producto principal. Para el despliegue del Main del Landing Page, utilizamos Github Pages.

link:
#### 5.2.1.8. Team Collaboration Insights during Sprint
Durante los commits del primer Sprint, se utilizaron las herramientas Visual Studio Code, IntelliJ IDE y Git. Uno de los miembros realizó el primer commit para crear el repositorio, luego clonamos dicho repositorio utilizando Git. Posteriormente, los cambios se realizaron en Visual Studio Code/IntelliJ IDE, se crearon ramas (branches) para estos cambios, y finalmente se efectuaron los commits, los cuales fueron revisados en el repositorio de Github.

