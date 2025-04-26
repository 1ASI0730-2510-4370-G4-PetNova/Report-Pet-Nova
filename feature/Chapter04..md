
# **CAPÍTULO IV: PRODUCT DESIGN**
El objetivo principal de esta sección es definir el diseño funcional y visual de la plataforma, transformando los requerimientos en interfaces intuitivas y accesibles para veterinarios y dueños de mascotas. A través de flujos de usuario, wireframes y lineamientos visuales, se asegura una experiencia coherente y fluida, facilitando la gestión de historiales, productos y servicios. Este diseño mejora la eficiencia operativa, apoya la misión de mejorar la calidad de vida de las mascotas y sus dueños, y contribuye a la visión de convertir a la plataforma en la herramienta líder en gestión veterinaria, optimizando el cuidado de las mascotas y fortaleciendo la relación entre veterinarios y propietarios.

## 4.1. Style Guidelines.
Es una serie de normas que definen la identidad visual y la interacción estética de un producto.Funciona como una guía de estilo que asegura la coherencia visual en todos los componentes del diseño, incluyendo colores, tipografías, íconos e imágenes, manteniéndolos en sintonía con la identidad visual y la esencia de la marca. A continuación, se presentan las pautas de estilo definidas para nuestro proyecto.

## 4.1.1 General Style Guidelines

### Branding

La identidad visual de la marca **PETNOVA** representa el compromiso con el cuidado animal moderno e integral. El logotipo presenta la figura de un conejo dentro de un círculo, proyectando cercanía, agilidad y confianza. El nombre **PETNOVA** se muestra en una tipografía clara y moderna, lo que refuerza la imagen tecnológica y accesible de la plataforma.

![PETNOVA_LOGO.png](assets/Chapter04/PETNOVA_LOGO.png)

### Typography

Se utilizará la tipografía **Poppins**, ideal por su estilo limpio, amigable y altamente legible en distintos dispositivos. Se empleará en todos los niveles de texto: títulos, subtítulos, etiquetas e información dentro de formularios, garantizando una jerarquía visual clara y coherente.

### Colors

La paleta de colores está basada en tonos azules claros, los cuales transmiten confianza, tranquilidad y tecnología amigable. Estos colores permiten una navegación intuitiva, sin causar fatiga visual, y mantienen un entorno accesible tanto para veterinarios como para usuarios frecuentes.

![Paleta_colores.png](assets/Chapter04/Paleta_colores.png)

**Principal:**  
`#6ABFE3` – Celeste claro: Botones principales, títulos destacados y acciones clave.

**Secundario:**  
`#1E3A5F` – Azul profundo: Encabezados, fondo de navbar, pie de página o énfasis visual.

**Fondo:**  
- `#EAF7FC` – Celeste muy claro: Fondo de secciones, formularios, y contenedores suaves.  
- `#FFFFFF` – Blanco puro: Fondo base de pantallas, tarjetas, inputs y elementos limpios.

**Neutro:**  
`#A0AAB2` – Gris suave: Texto secundario, íconos, bordes, descripciones.

### Tone of Communication

- **Amigable:** Para mensajes generales y explicaciones dentro de la plataforma, buscando cercanía con los usuarios.
- **Profesional:** Aplicado en las descripciones de servicios, reportes médicos y perfiles de mascotas, manteniendo claridad y precisión.
- **Empático:** Para comunicar situaciones sensibles como alertas de salud o historial médico.
- **Informativo:** En mensajes de ayuda, tutoriales o recomendaciones veterinarias.
- **Motivador:** Para celebrar logros como revisiones completas o mejoras en la salud de las mascotas.
- **Formal:** En secciones legales como términos, condiciones y políticas de privacidad.
  
### 4.1.2. Web Style Guidelines

**Elementos Visuales:**
Se emplearán imágenes y videos con distintas finalidades. Las imágenes incluirán desde íconos hasta fotos de perfil, mientras que los videos formarán parte de la explicación del contenido, especialmente en la sección de características, facilitando el aprendizaje visual.
**Botones:**
Los botones permitirán al usuario ejecutar acciones como enviar formularios o navegar por la plataforma. Su diseño seguirá las pautas de estilo establecidas, destacándose claramente entre los demás elementos visuales para garantizar una interacción fluida.
**Formularios:**
Se implementarán formularios para usuarios que deseen registrarse ingresando sus datos personales. Su estructura estará pensada para facilitar la experiencia del usuario durante estos procesos clave.
**Interfaz Web Responsiva:**
La aplicación presentará un diseño adaptable a distintos dispositivos, gracias al uso de Flexbox y CSS Grid. Se prioriza la usabilidad mediante una interfaz clara e intuitiva, compatible con navegadores como Chrome, Firefox y Safari. Además, las imágenes estarán optimizadas para asegurar una carga rápida incluso con conexiones lentas.

## 4.2. Information Architecture

La arquitectura de la información es fundamental para organizar y estructurar el contenido de forma que sea fácil de entender y navegar. En este apartado, abordaremos cómo se han definido las categorías, las etiquetas, la optimización SEO, las metaetiquetas, y los sistemas de búsqueda y navegación que construyen la base de nuestro producto.


## 4.2.1. Organization Systems

El objetivo del sistema de organización de la página es definir una estructura visual clara que facilite tanto la presentación del contenido como la navegación del usuario. En el caso de **PetNova**, el diseño del contenido está segmentado en módulos y se centra en los siguientes elementos:

### Página principal (Homepage)

Esta se estructura en varias secciones, entre las que se encuentran:
- Home
- Why Choose Us?
- Contact
- Service Features
- Sign In
- Sign Up

![Home Page](assets/Chapter04/Home_page.png)

Los sistemas de organización desempeñan un papel fundamental en la presentación clara y coherente del contenido, ya que favorecen tanto la navegación como la comprensión. Para lograrlo, se aplican distintos métodos.


### 4.2.2. Labeling Systems

**Sistemas de Etiquetado**
Los sistemas de etiquetado cumplen un rol clave en la organización del contenido, ya que permiten mejorar la navegación y facilitar la búsqueda de información dentro del producto. Según el contexto y el tipo de usuario, se han definido diferentes enfoques de etiquetado:


- **Etiquetado Descriptivo:** Se utilizan términos claros y precisos que describen directamente el contenido, permitiendo que el usuario entienda rápidamente su propósito y lo localice fácilmente mediante el buscador.


    - Ejemplos antes de iniciar sesión: Inicio, Why choose us?, Contact, Service feature.


- **Etiquetado por Perfil de Usuario:** Las etiquetas se adaptan a las características o necesidades del usuario según su rol o nivel de acceso, mejorando así la relevancia de la información mostrada.


    - Ejemplos después de iniciar sesión: Mis mascotas, Citas, Historial de mascotas, Notificaciones de citas, Perfil, Cerrar sesión.


- **Etiquetado Basado en Relevancia:** Aquí, las etiquetas se asignan considerando la popularidad o utilidad del contenido. Esto puede basarse en estadísticas de uso o en la interacción de los usuarios, como clics, valoraciones o frecuencia de acceso.



### 4.2.3. SEO Tags and Meta Tags

En **PETNOVA**, los SEO Tags y Meta Tags forman parte de la estrategia para mejorar la visibilidad, el posicionamiento y la accesibilidad de la plataforma, tanto en la **Landing Page** como en la **Web Application**. A pesar de que el proyecto se encuentra en proceso de desarrollo, ya se ha definido su planificación SEO principal.

## Landing Page

- **Title:** Pet Nova | Gestión Veterinaria y Cuidado de Mascotas
- **Meta Description:** Plataforma integral que simplifica el acceso a historiales clínicos, productos y servicios veterinarios para mejorar la calidad de vida de las mascotas y sus dueños.
- **Meta Keywords:** gestión veterinaria, historial clínico de mascotas, servicios veterinarios, cuidado de mascotas, plataforma veterinaria digital
- **Meta Author:** Equipo de Pet Nova

## Web Application

- **Title:** Pet Nova | Portal de Gestión Clínica Veterinaria
- **Meta Description:** Plataforma web para la administración eficiente de historiales de salud, gestión de clientes, productos y servicios en clínicas veterinarias.
- **Meta Keywords:** aplicación veterinaria, historial médico de mascotas, servicios clínicos veterinarios, administración de clínicas veterinarias
- **Meta Author:** Equipo de Pet Nova

## Adicionalmente

- **Etiquetas de encabezado (Header Tags):** Se utilizarán etiquetas H1, H2 y H3 para organizar jerárquicamente el contenido, mejorando la estructura y navegación.
- **Etiqueta de idioma (Language Tag):** Se configurará la plataforma para soportar tanto español como inglés, optimizando la experiencia de usuarios locales e internacionales.
- **Metaetiqueta de robots (Meta Robots Tag):** Se permitirá la indexación de las páginas y el seguimiento de los enlaces relevantes por parte de los motores de búsqueda.

Estas configuraciones estarán integradas a nivel de código HTML y tienen como objetivo fortalecer la presencia digital de **Pet Nova** desde su lanzamiento.

### 4.2.4. Searching Systems

 **Sistemas de Búsqueda**


Contar con un sistema de búsqueda eficiente es clave para que los usuarios puedan acceder rápidamente a la información que necesitan. A continuación, se presentan los distintos métodos de búsqueda implementados:

- **Búsqueda por Términos Clave:** El usuario puede ingresar palabras específicas para localizar contenido relacionado. El sistema muestra los resultados más cercanos a esos términos.


- **Búsqueda con Filtros:** Permite acotar los resultados aplicando criterios como categoría, fecha o tipo de contenido, lo que mejora la exactitud de lo que se busca.


- **Búsqueda Facetada:** Esta opción ayuda a refinar los resultados utilizando distintas propiedades del contenido, como ubicación, temática o tipo, ideal para manejar grandes volúmenes de datos.


- **Búsqueda por Relevancia:** Ordena los resultados según qué tan útiles o relacionados son con lo buscado, gracias a algoritmos que priorizan la información más pertinente.


### 4.2.5. Navigation Systems
En Pet Nova, la navegación en el Landing Page y las aplicaciones se ha diseñado cuidadosamente para guiar al usuario a través de una experiencia fluida y eficaz, asegurando que puedan cumplir sus metas sin complicaciones. A continuación, se detallan las principales acciones y técnicas que facilitarán el recorrido del contenido:

## Navegación Intuitiva:
La navegación en el Landing Page y en las aplicaciones está estructurada para ser clara y accesible, permitiendo que los usuarios encuentren lo que buscan sin esfuerzo. Se emplean menús desplegables en la parte superior de la página y enlaces fáciles de identificar en el pie de página. Estos menús están diseñados para dirigir al usuario a las áreas principales:

## Servicios
## Historial clínico
## Productos y servicios veterinarios
## Soporte

## Llamadas a la Acción (CTA):
Las llamadas a la acción están estratégicamente ubicadas para motivar a los usuarios a realizar tareas clave, como registrarse para crear una cuenta, consultar servicios veterinarios o agendar una cita. Los botones de CTA son visibles, con colores contrastantes para atraer la atención y facilitar la interacción.

## Navegación con Pestañas:
En la Web Application, se implementa un sistema de navegación por pestañas que permite a los usuarios moverse entre secciones clave sin necesidad de recargar la página. Esto incluye:

## Historial de Salud de las Mascotas
## Agenda de Citas
## Productos

Esto facilita una experiencia rápida y sin interrupciones, especialmente útil para los veterinarios que necesitan acceder a la información de manera eficiente.

## Desplazamiento Fluido:
El scroll infinito en las secciones de información o artículos dentro de la Web Application permite que los usuarios sigan explorando el contenido sin tener que hacer clic en varios enlaces. Esto es especialmente útil para las secciones de artículos educativos o productos relacionados, permitiendo que el contenido se cargue de manera continua conforme el usuario se desplaza hacia abajo.

## Visualización Clara de Información:
Los usuarios pueden visualizar el historial clínico de sus mascotas de manera sencilla. Cada sección está claramente dividida y etiquetada, lo que les permite encontrar rápidamente las estadísticas de salud y los detalles de sus visitas anteriores a la clínica. Los gráficos y resúmenes visuales permiten una comprensión más rápida y eficaz de la información.

## Adaptabilidad y Soporte Multilingüe:
La plataforma está adaptada para ofrecer una experiencia fluida tanto en español como en inglés, lo que permite que los usuarios, independientemente de su ubicación o idioma, puedan navegar y comprender fácilmente todas las funciones disponibles.

## Proceso de Registro Simplificado:
Para facilitar la creación de cuentas, hemos diseñado un proceso de registro rápido con formularios fáciles de completar. Los usuarios pueden empezar a interactuar con la plataforma sin tener que llenar formularios largos, simplificando su experiencia desde el primer momento.

## Asistencia al Usuario:
El soporte por correo electrónico estará disponible para los usuarios en todo momento. Además, se ofrecerán tutoriales dentro de la aplicación para guiar a los usuarios nuevos a través de las funciones clave de la plataforma.

## 4.3. Landing Page UI Design
La **Landing Page** cumple la función de atraer la atención del usuario y dirigirlo hacia una acción concreta, como completar un registro, adquirir un producto o explorar un servicio. 

En este apartado, se analizará el diseño de su interfaz, haciendo énfasis en los componentes esenciales que optimizan la experiencia del usuario y contribuyen a construir una página atractiva, funcional y fácil de usar.

### 4.3.1. Landing Page Wireframe
El **wireframe** de la landing page de **PetNova** representa la estructura base sobre la que se construirá el diseño final, permitiendo visualizar la disposición de cada sección y la experiencia del usuario de manera ordenada. La página estará compuesta por los siguientes bloques:

**Encabezado Principal:**  
Incluye el logo de PetNova, un menú de navegación simple, y una imagen principal donde se destaca el propósito de la marca: cuidar la salud y bienestar de las mascotas. Un breve mensaje de bienvenida y un botón de llamada a la acción (CTA) invitan a conocer más.

 ![](assets/Chapter04/WLPAGE_V1.png)

**¿Por qué elegirnos?:**  
Una sección de fondo sólido donde se resumen las principales razones para confiar en PetNova, apoyadas en imágenes pequeñas y texto breve que destaca nuestros valores y ventajas competitivas.

 ![](assets/Chapter04/WLPAGE_V2.png)

**Planes de Suscripción:**  
Mostramos tres opciones principales de servicios para mascotas, cada una presentada en una tarjeta visual, con nombre, imagen, descripción breve y un botón para más información o contratación.

 ![](assets/Chapter04/WLPAGE_V3.png)

**Nuestros Aliados:**  
Un bloque con los logos de marcas reconocidas en el sector veterinario, demostrando el respaldo y la calidad de los productos y servicios que ofrecemos.

 ![](assets/Chapter04/WLPAGE_V4.png)
 
**Testimonios de Clientes:**  
Sección de tres columnas donde mostramos experiencias reales de nuestros clientes, acompañadas de imágenes y citas cortas, reforzando la confianza de nuevos visitantes.

 ![](assets/Chapter04/WLPAGE_V5.png)

**Invitación para Veterinarios:**  
Una llamada especial para que veterinarios se unan a PetNova, con imagen destacada, texto motivador y un botón de contacto.

 ![](assets/Chapter04/WLPAGE_V6.png)

**Preguntas Frecuentes (FAQ):**  
Despejamos las dudas más comunes mediante una sección de preguntas y respuestas rápidas, haciendo que el usuario encuentre información relevante sin dificultad.
 ![](assets/Chapter04/WLPAGE_V7.png)

**Formulario de Contacto:**  
Un formulario sencillo y visible para que los usuarios puedan enviar sus consultas, suscribirse o solicitar información adicional de manera rápida y cómoda.

**Pie de Página:**  
Sección final con datos de contacto, accesos a redes sociales, mapa de navegación básico y un pequeño recordatorio de nuestra misión: “Comprometidos con la vida y felicidad de las mascotas”.

 ![](assets/Chapter04/WLPAGE_V8.png)
 
> **Nota:** También se incluye la versión **mobile** correspondiente para cada sección mostrada, siguiendo el mismo orden y adaptándose a las dimensiones y experiencia de uso en dispositivos móviles.  

Para una mejor visualización de los wireframes (versión desktop y mobile), se adjunta el siguiente enlace de Figma:  
https://www.figma.com/design/XjI2alaHmyFV0MPlaPpxzO/Web-design?node-id=401-8424&t=kuv2vsPlXaFzVYvk-0

### 4.3.2. Landing Page Mock-up

## PANTALLA 1
La primera pantalla presenta un encabezado claro con logo, menú de navegación y botón de acceso, demostrando una jerarquía visual efectiva y arquitectura de información bien estructurada. Justo debajo, la sección hero combina una imagen emocional de una veterinaria con una mascota y un mensaje directo que comunica el valor principal del servicio. El botón de llamada a la acción está destacado con un buen contraste, guiando al usuario sin fricción. El diseño es inclusivo al utilizar una imagen que representa diversidad y empatía, y se aplican principios como el alineamiento, proximidad y énfasis para dirigir la atención hacia el mensaje principal.

![](assets/Chapter04/MLPAGE_V1.png)

## PANTALLA 2
Esta sección comunica las ventajas del servicio mediante texto breve y tres tarjetas con íconos representativos. Se aplica proximidad para agrupar contenido relacionado y repetición para crear consistencia visual. Los íconos ayudan a la comprensión visual, especialmente útil para usuarios con dificultades de lectura o cognitivas, lo que evidencia un enfoque inclusivo. La arquitectura de la información es simple y clara, permitiendo captar rápidamente los beneficios sin sobrecargar al usuario.

![](assets/Chapter04/MLPAGE_V2.png)

## PANTALLA 3
Contiene tarjetas individuales para cada plan, con imágenes de mascotas, precios y características principales. La estructura visual facilita la comparación, usando jerarquía para resaltar precios y beneficios. El diseño es consistente y ordenado, lo que reduce la carga cognitiva. Las imágenes representan variedad de mascotas, promoviendo la inclusión y conexión emocional con diferentes tipos de usuarios.

![](assets/Chapter04/MLPAGE_V3.png)

## PANTALLA 4
Esta sección muestra los logotipos de empresas aliadas en un formato limpio y bien espaciado. El diseño es minimalista y utiliza espacio negativo de forma efectiva, lo que permite que cada logo se distinga claramente. Esta organización visual genera confianza mediante prueba social, y su presentación accesible permite que los usuarios identifiquen fácilmente a las marcas colaboradoras.

![](assets/Chapter04/MLPAGE_V4.png)

## PANTALLA 5
Aquí se muestran opiniones de usuarios reales junto con sus fotos, lo que añade autenticidad y credibilidad. La disposición en bloques aplica el principio de proximidad y alinea imágenes con texto para facilitar la lectura. Las imágenes muestran diversidad, aportando un enfoque inclusivo. Además, los textos son breves y fáciles de escanear, siguiendo buenas prácticas de arquitectura de información.

![](assets/Chapter04/MLPAGE_V5.png)

## PANTALLA 6
Esta sección invita a los profesionales a unirse a la plataforma, con una imagen amable y profesional acompañada de un mensaje claro y un botón de registro. La jerarquía visual destaca el llamado a la acción, y la imagen refuerza la empatía y profesionalismo. Se emplea diseño inclusivo mediante una representación positiva y cercana del personal veterinario.

![](assets/Chapter04/MLPAGE_V6.png)

## PANTALLA 7
Presenta preguntas comunes en un formato sencillo y organizado, lo que facilita el acceso a la información sin sobrecargar la vista. Se aplican principios de claridad y estructura predecible, usando bloques plegables para mantener la limpieza visual. El lenguaje utilizado es accesible, pensado para todo tipo de usuarios, y la disposición responde a una buena arquitectura de información que mejora la experiencia del usuario.

![](assets/Chapter04/MLPAGE_V7.png)

## PANTALLA 8

se integra el formulario de contacto "Get in Touch" junto con el pie de página en una misma sección. El formulario permite que los usuarios envíen su nombre, número de contacto y mensaje de manera rápida, mientras que el pie de página ofrece accesos a redes sociales, enlaces útiles y un recordatorio de la misión de Pet Nova. Esta combinación asegura que la experiencia de cierre del sitio sea funcional, accesible y coherente con el estilo visual general, facilitando tanto la comunicación como la navegación final.

![](assets/Chapter04/MLPAGE_V8.png)

> **Nota:** También se incluye la versión **mobile** correspondiente para cada sección mostrada, siguiendo el mismo orden y adaptándose a las dimensiones y experiencia de uso en dispositivos móviles.  

Para una mejor visualización de los mock ups (versión desktop y mobile), se adjunta el siguiente enlace de Figma:  
https://www.figma.com/design/XjI2alaHmyFV0MPlaPpxzO/Web-design?node-id=401-8424&t=kuv2vsPlXaFzVYvk-0

## 4.4. Web Applications UX/UI Design

Crear una experiencia de usuario efectiva en aplicaciones web requiere planificar cuidadosamente cada interacción del usuario. En esta sección se muestran los wireframes, flujos de navegación y mockups que aseguran una interfaz clara y fácil de usar.


### 4.4.1. Web Applications Wireframes


Listado de mascotas

![m_mascota_list.png](assets/Chapter04/m_mascota_list.png)

Busqueda de mascotas

![m_mascota_search.png](assets/Chapter04/m_mascota_search.png)

Registro de mascotas

![m_mascota_post.png](assets/Chapter04/m_mascota_post.png)

Edición del perfil de la mascota

![m_mascota_put.png](assets/Chapter04/m_mascota_put.png)

Eliminacion de mascota

![m_cliente_delete.png](assets/Chapter04/m_cliente_delete.png)

-------

Listado de clientes

![m_cliente_list.png](assets/Chapter04/m_cliente_list.png)

Busqueda de clientes

![m_cliente_search.png](assets/Chapter04/m_cliente_search.png)

Registro de clientes

![m_cliente_post.png](assets/Chapter04/m_cliente_post.png)

Edición del perfil del cliente

![m_cliente_put.png](assets/Chapter04/m_cliente_put.png)

Eliminacion de clientes

![m_mascota_delete.png](assets/Chapter04/m_mascota_delete.png)


--------------

notificaciones

![m_noti.png](assets/Chapter04/m_noti.png)

--------------

 **historial clinico**

Listado de historial clinico

![m_hist_list.png](assets/Chapter04/m_hist_list.png)

Registro de historial clinico

![m_hist_post.png](assets/Chapter04/m_hist_post.png)

Confirmacion de registro de historial clinico
  
![m_hist_confirm.png](assets/Chapter04/m_hist_confirm.png)

Descarga de historial clinico

![m_hist_download.png](assets/Chapter04/m_hist_download.png)


-------------

dashboard

![dashboard_wire.png](assets/Chapter04/dashboard_wire.png)

Registro de perfil

![perfil_edit_wire.png](assets/Chapter04/perfil_edit_wire.png)

Edición del perfil del perfil

![perfil_edit_wire.png](assets/Chapter04/perfil_edit_wire.png)

Eliminacion de perfil  

![perfil_delete_wire.png](assets/Chapter04/perfil_delete_wire  .png)


## movil:

Listado, búsqueda, registro, edición y eliminación de mascotas

![m_CRUD_clientes_mascotas_mo.png](assets/Chapter04/m_CRUD_clientes_mascotas_mo.png)

Dashboard del usuario

![m_dashboard_mo.png](assets/Chapter04/m_dashboard_mo.png)

Listado, registro, confirmación de registro y descarga de historial clínico

![m_medical_hist_mo.jpeg](assets/Chapter04/m_medical_hist_mo.jpeg)

Listado, búsqueda, registro, edición y eliminación de clientes

![m_CRUD_clientes_mascotas_mo.png](assets/Chapter04/m_CRUD_clientes_mascotas_mo.png)





### 4.4.2. Web Applications Wireflow Diagrams

Enlace Figma: https://www.figma.com/design/XjI2alaHmyFV0MPlaPpxzO/Web-design?node-id=435-460&t=FneTAGfdXkLo3c8Q-1 

User Goal: Registrar usuario

![User_Goal_1.jpeg](assets/Chapter04/User_Goal_1.jpeg)

User Goal: Gestionar perfil

![User_Goal_2.jpeg](assets/Chapter04/User_Goal_2.jpeg)

User Goal: Gestionar mascota

![User_Goal_3.jpeg](assets/Chapter04/User_Goal_3.jpeg)

User Goal: Gestionar citas

![User_Goal_4.jpeg](assets/Chapter04/User_Goal_4.jpeg)

User Goal: Gestionar Historial medico

![User_Goal_5.jpeg](assets/Chapter04/User_Goal_5.jpeg)




### 4.4.3. Web Applications Mock-ups

Listado de mascotas

![mascota_list.png](assets/Chapter04/mascota_list.png)

Busqueda de mascotas

![mascota_search.png](assets/Chapter04/mascota_search.png)

Registro de mascotas

![mascota_post.png](assets/Chapter04/mascota_post.png)

Edición del perfil de la mascota

![mascota_put.png](assets/Chapter04/mascota_put.png)

Eliminacion de mascota

![cliente_delete.png](assets/Chapter04/cliente_delete.png)

-------

Listado de clientes

![cliente_list.png](assets/Chapter04/cliente_list.png)

Busqueda de clientes

![cliente_search.png](assets/Chapter04/cliente_search.png)

Registro de clientes

![cliente_post.png](assets/Chapter04/cliente_post.png)

Edición del perfil del cliente

![cliente_put.png](assets/Chapter04/cliente_put.png)

Eliminacion de clientes

![mascota_delete.png](assets/Chapter04/mascota_delete.png)


--------------

notificaciones

![noti.png](assets/Chapter04/noti.png)

--------------

historial clinico

Listado de historial clinico

![hist_list.png](assets/Chapter04/hist_list.png)

Registro de historial clinico

![hist_post.png](assets/Chapter04/hist_post.png)

Confirmacion de registro de historial clinico
  
![hist_confirm.jpeg](assets/Chapter04/hist_confirm.jpeg)

Descarga de historial clinico

![hist_download.png](assets/Chapter04/hist_download.png)

-------------

Muestra de perfil

![perfil_list.png](assets/Chapter04/perfil_list.png)


Edición del perfil del perfil

![perfil_edit.png](assets/Chapter04/perfil_edit.png)

Eliminacion de perfil

![perfil_delete.png](assets/Chapter04/perfil_delete.png)

-----

Dashboard

![dashboard.png](assets/Chapter04/dashboard.png)

## Movil

Registro e inicio de sesion  

Listado, búsqueda, registro, edición y eliminación de clientes.

![CRUD_clientes_mo.jpeg](assets/Chapter04/CRUD_clientes_mo.jpeg)

Listado, búsqueda, registro, edición y eliminación de historial medico.

![medical_hist_mo.png](assets/Chapter04/medical_hist_mo.png)

notificaciones.

![noti_mo.png](assets/Chapter04/noti_mo.png)

Dashboard del usuario

![dashboard_mo.jpeg](assets/Chapter04/dashboard_mo.jpeg)

Listado, búsqueda, registro, edición y eliminación de mascotas.

![CRUD_mascota.png](assets/Chapter04/CRUD_mascota.png)



### 4.4.4. Web Applications User Flow Diagrams

## Interacción cuando un cliente gestiona su perfil

![User_Flow_Diagrams1.jpeg](assets/Chapter04/User_Flow_Diagrams2.jpeg)

## Interacción cuando un cliente se registra y procede a gestionar una cita

![User_Flow_Diagrams2.jpeg](assets/Chapter04/User_Flow_Diagrams2.jpeg)

## Interaccion cuando el cliente gestiona un historial de mascotas

![User_Flow_Diagrams3.jpeg](assets/Chapter04/User_Flow_Diagrams2.jpeg)

## Interaccion cuando el cliente gestiona una mascota

![User_Flow_Diagrams4.jpeg](assets/Chapter04/User_Flow_Diagrams4.jpeg)

## Interaccion cuando el usuario gestiona un cliente

![User_Flow_Diagrams5.jpeg](assets/Chapter04/User_Flow_Diagrams5.jpeg)


## 4.5. Web Applications Prototyping

En esta sección se realizó la navegación para mostrar los user flows de nuestra aplicación web

Para el diseño de los prototipos de la interfaz de usuario para Desktop y Mobile Web Browser, se tomaron en cuenta varios principios clave:

1. Claridad y Simplicidad: Se buscó que la navegación fuera fácil e intuitiva, permitiendo a los usuarios comprender rápidamente las funcionalidades, como el registro de procesos y la visualización de informes estadísticos.

2. Diseño Responsivo: Se garantizó que la aplicación web fuera adaptable a diferentes tamaños de pantalla, permitiendo su acceso sin restricciones, sin importar el dispositivo utilizado.

3. Prioridad a la Información Relevante: El diseño se centró en mostrar la información más importante para los usuarios del segmento objetivo, evitando saturar la interfaz con detalles innecesarios

![Prototype_1.jpeg](assets/Chapter04/Prototype_1.jpeg)
![Prototype_1.jpeg](assets/Chapter04/Prototype_1.jpeg)


Video del prototipo:

vista del cliente(web) : https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a301_upc_edu_pe/EfkZIPN2ofNDjrD7A87eLEkBuNByQ2ch0yCCBfZO8ltJbA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=rOoOMm

vista del cliente(movil) : https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a301_upc_edu_pe/EeDRJ_qML11Pj1LgtFxWWB4Bq6-FcuSXI5B5pINQFmyHDA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=lmtqeh

vista del veterinario(web) : https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a301_upc_edu_pe/ESvd9FR5FlBIuWgdgzCsYJcBNI_lB7ZKoH6Mys5_BWZNVg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=iqlyrA

vista del veterinario(movil) : https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a301_upc_edu_pe/ESQ9b9kkwK5LkdbKRjqc9L8BXTVrulFa2-_bTqO49Ndbgw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=rQAXj4

Enlace del prototipo (vista del cliente) : https://www.figma.com/design/XjI2alaHmyFV0MPlaPpxzO/Web-design?node-id=300-149&t=aGzgk6GCBuWJqZho-1

Enlace del prototipo (vista del veterinario) : https://www.figma.com/design/XjI2alaHmyFV0MPlaPpxzO/Web-design?node-id=325-1279&t=FneTAGfdXkLo3c8Q-1


## 4.6. Domain-Driven Software Architecture

Este enfoque resalta la importancia de comprender profundamente el dominio del negocio para el cual se desarrolla el software. Su objetivo es diseñar soluciones alineadas de manera precisa con las necesidades y particularidades del negocio, garantizando que el sistema aporte verdadero valor y responda eficazmente a sus requerimientos.

### 4.6.1. Software Architecture Context Diagram 

El esquema de contexto es una herramienta clave de análisis que permite visualizar y entender cómo Pet Nova se relaciona con su entorno. Esta representación facilita la identificación de oportunidades de integración, colaboración y mejora en los distintos procesos que componen la experiencia del usuario. Al mapear los elementos internos y externos que interactúan con la plataforma, se obtienen valiosas perspectivas para optimizar su funcionamiento y adaptarse de manera estratégica a las necesidades del sector veterinario.

![](assets/Chapter04/System.png)

### 4.6.2. Software Architecture Container Diagrams

El diagrama de contenedores es una herramienta esencial para visualizar la arquitectura de Pet Nova a alto nivel. Permite identificar cómo se organizan los principales componentes del sistema y cómo interactúan entre sí. Esta representación facilita la detección de posibles cuellos de botella, dependencias innecesarias o áreas que podrían optimizarse, proporcionando una base sólida para tomar decisiones técnicas informadas y mejorar el rendimiento general de la plataforma.

![](assets/Chapter04/Container.png)
   
### 4.6.3. Software Architecture Components Diagrams

Los diagramas de componentes proporcionan una vista detallada de la arquitectura del software, mostrando cómo se descompone en módulos funcionales y cómo estos se relacionan entre sí para formar un sistema cohesivo y eficiente. Esta representación es fundamental para entender la estructura interna de Pet Nova, facilitando el análisis, mantenimiento y escalabilidad de la plataforma a lo largo del tiempo.

### Veterinarians Bounded Context

![](assets/Chapter04/Component_1.png)  

### Pet Owners Bounded Context

![](assets/Chapter04/Component_2.png)
## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams


![class_diagram.jpeg](assets/Chapter04/class_diagram.jpeg)

### 4.7.2. Class Dictionary


## Pet

Representa a las mascotas registradas por los clientes o veterinarios.

| Atributo     | Tipo          | Descripción                       |
|--------------|---------------|-----------------------------------|
| id           | long int      | Identificador de la mascota       |
| name         | string        | Nombre de la mascota              |
| lastname     | string        | Apellido de la mascota            |
| age          | short int     | Edad de la mascota                |
| client       | Client        | Propietario de la mascota         |
| medicalHistory | List<MedicalHistory> | Lista de historiales médicos   |
| currentStatus | PetStatus    | Estado actual de salud de la mascota |

## MedicalHistory

Representa el historial médico de una mascota.

| Atributo     | Tipo          | Descripción                       |
|--------------|---------------|-----------------------------------|
| id           | long int      | Identificador del historial médico|
| id_mascota   | string        | ID de referencia a la mascota    |
| genero       | string        | Género de la mascota              |
| raza         | string        | Raza de la mascota                |
| fecha_nac    | date          | Fecha de nacimiento               |
| description  | text          | Descripción médica                |
| veterinarian | Veterinarian  | Veterinario asignado              |
| tratamiento  | List<Treatment> | Lista de tratamientos            |
| vacunas      | List<Vaccines>  | Lista de vacunas                  |

## Treatment

Representa el tratamiento brindado de una mascota.

| Atributo     | Tipo          | Descripción                       |
|--------------|---------------|-----------------------------------|
| id           | long int      | Identificador del tratamiento     |
| name         | string        | Nombre del tratamiento            |
| duration     | string        | Duración del tratamiento          |
| medicalHistory | MedicalHistory | Historial médico relacionado    |
| description  | text          | Detalles del tratamiento          |

## Vaccines

Representa las vacunas brindado de una mascota.

| Atributo     | Tipo          | Descripción                       |
|--------------|---------------|-----------------------------------|
| id           | long int      | Identificador de la vacuna        |
| name         | string        | Nombre de la vacuna               |
| duration     | string        | Duración de la protección         |
| medicalHistory | MedicalHistory | Historial médico relacionado    |
| description  | text          | Detalles de la vacuna             |

## Horario

Representa el horario de un veterinario.

| Atributo     | Tipo          | Descripción                       |
|--------------|---------------|-----------------------------------|
| id           | long int      | Identificador del horario         |
| dia_semana   | DiaSemana     | Día de la semana                  |
| servicio     | string        | Servicio proporcionado            |
| h_inicio     | time          | Hora de inicio del servicio       |
| h_fin        | time          | Hora de fin del servicio          |

## Client

Representa a los clientes del sistema que poseen mascotas.

| Atributo     | Tipo          | Descripción                       |
|--------------|---------------|-----------------------------------|
| id           | long int      | Identificador del cliente         |
| firstname    | string        | Nombre del cliente                |
| lastname     | string        | Apellido del cliente              |
| email        | string        | Correo electrónico                |
| password     | string        | Contraseña del cliente            |

## Veterinarian

Representa a los veterinarios en el sistema.


| Atributo     | Tipo          | Descripción                       |
|--------------|---------------|-----------------------------------|
| speciality   | string        | Especialidad médica               |
| appointments | List<Appointment> | Lista de citas asignadas         |

## Appointment

Representa las citas entre un veterinario y una mascota.

| Atributo             | Tipo          | Descripción                       |
|----------------------|---------------|-----------------------------------|
| id                   | long int      | Identificador de la cita          |
| DNI                  | string        | DNI del cliente                   |
| date                 | datetime      | Fecha y hora de la cita           |
| service              | string        | Servicio solicitado               |
| recordatorio_enviado | bool          | Estado del recordatorio enviado  |
| notificacion_enviada | bool          | Estado de la notificación enviada |

## StatusAppointment

Representa el estado en el que se encuentra la citas 

| Atributo     | Tipo          | Descripción                       |
|--------------|---------------|-----------------------------------|
| id           | long int      | Identificador del estado de la cita |
| descripcion  | string        | Descripción del estado            |

## User

Representa a los usuarios del sistema, ya sea veterinarios o clientes.

| Atributo     | Tipo          | Descripción                       |
|--------------|---------------|-----------------------------------|
| id           | long int      | Identificador del usuario         |
| firstname    | string        | Nombre del usuario                |
| lastname     | string        | Apellido del usuario              |
| email        | string        | Correo electrónico                |
| password     | string        | Contraseña del usuario            |

## 4.8. Database Design
### 4.8.1. Database Diagram 
Para el diseño y gestión de la base de datos de Pet Nova, se optó por utilizar MySQL como sistema gestor, administrado mediante MySQL Workbench. Esta elección responde tanto a la experiencia previa del equipo con el lenguaje SQL, como a la solidez, escalabilidad y eficiencia que ofrece la herramienta para satisfacer los requerimientos funcionales y estructurales del proyecto. Además, su interfaz visual facilita la planificación, modelado y mantenimiento de una base de datos clara y coherente.

![](assets/Chapter04/data_base.png)

###

###

###

###

###
