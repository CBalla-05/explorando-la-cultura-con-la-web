# Proyecto 02: Explorando la cultura con la web — Biblioteca de las Artes

**Materia:** Desarrollo de aplicaciones web y móviles  
**Estudiantes:** César Balladares y Fátima Torres 

---

## Análisis

### 1. Elección y justificación de la actividad
La actividad seleccionada es la participación ciudadana en los espacios de lectura y encuentro cultural dentro de la **Biblioteca de las Artes en Guayaquil**. Esta actividad involucra a un público sumamente variado: desde niños y familias en la Sala Ría, hasta estudiantes universitarios, investigadores y artistas locales que utilizan el espacio para la lectura, el debate y la apreciación de exposiciones artísticas. 

Resulta de gran relevancia porque esta biblioteca no es solo un repositorio de libros, sino un núcleo de dinamización cultural y social en el centro de la ciudad. Realizaremos el levantamiento de datos mediante encuestas y observaciones en el sitio para documentar cómo las personas interactúan con los recursos físicos y tecnológicos del lugar. Los testimonios, estadísticas de uso y registros multimedia recopilados servirán como insumo fundamental para desarrollar un sitio web interactivo que comunique, a través del *storytelling* visual, el impacto de este espacio en el fomento cultural y la vida comunitaria de la ciudad.

---

## Planificación

Se estableció un cronograma de trabajo estructurado bajo metodologías ágiles divididas en Sprints. Para la interacción con la comunidad y el levantamiento de datos en la Biblioteca de las Artes, el equipo aplicó un protocolo ético y seguro centrado en las siguientes pautas:

- **Seguridad personal y respeto al espacio:** Las visitas de campo se programaron en horarios permitidos y zonas de libre acceso, cumpliendo con las normas de la institución y respetando la tranquilidad de los lectores.
- **Consentimiento informado y anonimización:** Se informó a los participantes el propósito estrictamente académico del proyecto antes de cada entrevista. Se garantizó el anonimato de las personas mediante identificadores (ej. *Participante 01*, *Madre de familia 01*) para proteger sus datos personales.
- **Protección de menores de edad:** En las interacciones asociadas a la Sala Ría y el cine infantil de los sábados, se aplicaron encuestas y diálogos directos con sus padres o tutores legales, sin registrar fotografías ni datos identificables de los niños.
- **Uso ético e integridad de la información:** Los datos y testimonios se mantuvieron fieles a la realidad observada, utilizándose de forma agregada únicamente para los fines de diseño y desarrollo web del proyecto.

---

## Diseño

### 1. Pauta de entrevistas y encuestas
En esta fase se diseñó la pauta de entrevistas y encuestas aplicadas a los visitantes, estudiantes, personal administrativo y madres de familia en las instalaciones de la biblioteca. Las preguntas combinaron aspectos cualitativos y cuantitativos para evaluar la accesibilidad, el impacto de los talleres, el uso de recursos tecnológicos (como el ciber gratuito y el préstamo de equipos) y las expectativas digitales de los usuarios.

* **Preguntas Clave Aplicadas:**
  * *¿Cómo describirías tu experiencia en la Biblioteca de las Artes y con qué frecuencia la visitas?* (Abierta)
  * *¿Qué servicios utilizas con mayor frecuencia (préstamo de libros, ciber, Sala Ría, cine, talleres)?* (Cerrada / Abierta)
  * *¿Consideras que el espacio fomenta la participación comunitaria y reduce el uso excesivo de pantallas en los jóvenes y niños?* (Cerrada)
  * *¿Qué te gustaría encontrar en un sitio web interactivo de la biblioteca?* (Abierta)

### 2. Organización del contenido (Sprint 1)
A partir de la información recopilada en las entrevistas de campo, se estructuraron las secciones definitivas para la landing page:

| Nombre de la Sección | Propósito | Datos que se presentarán |
| :--- | :--- | :--- |
| **Header / Hero Section** | Captar la atención del visitante de inmediato y transmitir la identidad cultural del espacio. | Título principal, subtítulo enfocado en artes y humanidades, imagen de fondo representativa y botones de acceso rápido. |
| **Sobre el Espacio** | Explicar la propuesta de valor de la biblioteca como núcleo de dinamización social en Guayaquil. | Descripción del enfoque en artes y humanidades, gratuidad y accesibilidad universal. |
| **Zonas y Servicios** | Detallar los espacios físicos y tecnológicos disponibles para la comunidad. | - Sala Ría (espacio infantil).<br>- Préstamo de libros y equipos.<br>- Zonas de estudio e investigación. |
| **Agenda Cultural y Talleres** | Mostrar las actividades de mayor aforo y alta demanda ciudadana. | - Cine abierto de los sábados.<br>- Talleres gratuitos de dibujo y pintura.<br>- Enlaces a canales oficiales (WhatsApp e Instagram). |
| **Voces de la Comunidad** | Transmitir empatía y validación real mediante *storytelling* visual. | Testimonios resumidos de estudiantes, diseñadores y madres de familia sobre el impacto positivo del lugar. |
| **Contacto y Ubicación** | Proveer información práctica para fomentar la visita presencial. | Horarios, ubicación en el centro de Guayaquil, enlaces a redes sociales y créditos de desarrollo. |

### 3. Análisis comparativo de plantillas (Sprint 1)
Se evaluaron tres alternativas gratuitas de [HTML5 UP](https://html5up.net/):
1. **Twenty:** Orientada a blogs o sitios corporativos con un flujo lineal. Su navegación limita la integración modular de bloques dinámicos y llamadas a la acción enriquecidas.(https://html5up.net/twenty)
2. **Helios:** Diseñada como portafolio o galería en cuadrícula. Su estructura rígida dificulta la lectura fluida de textos largos y testimonios narrativos. (https://html5up.net/helios)
3. **Landed:** Plantilla moderna de una sola página (*single-page scrolling*), altamente responsiva, estructurada en bloques verticales limpios con efectos visuales (*parallax*), secciones de características por iconos y áreas ideales para testimonios.(https://html5up.net/landed)

### 4. Selección y justificación de la plantilla
* **Plantilla Seleccionada:** [Landed](https://html5up.net/landed)
* **Justificación:** Se selecciona *Landed* porque su diseño modular se alinea perfectamente con las necesidades del evento (*comunicar la interacción de la comunidad con la Biblioteca de las Artes mediante storytelling visual*). Permite estructurar de forma jerárquica las secciones informativas, integrar galerías de imágenes de los talleres y la Sala Ría, y mantener una adaptabilidad (*responsive design*) impecable y una gran facilidad de personalización para visualizarse correctamente en computadoras y dispositivos móviles.

---

## Implementación

Se transformó la plantilla *Landed* en el sitio de la Biblioteca de las Artes y la Sala Ría. Se eliminó todo el contenido de demostración (textos *lorem ipsum*, `elements.html` e imágenes de la plantilla).

### 1. Estructura del sitio

| Página | Contenido | Aplicación de la plantilla |
| :--- | :--- | :--- |
| `index.html` | Portada: banner con logo, quiénes somos, 3 categorías de actividades, Sala Ría y encuesta de participación | Landing |
| `left-sidebar.html` | **Talleres, música y teatro**: 9 talleres con descripción, público y lugar | Barra lateral izquierda con índice de la página |
| `right-sidebar.html` | **Cine, lectura y charlas**: CineClub Guayacine, Cine Kids, Baúl Literario, Exploradores de Cuentos y charla magistral | Barra lateral derecha con índice y enlaces a redes |
| `no-sidebar.html` | **Nosotros**: la biblioteca, Sala Ría, servicios, ubicación y contacto | Sin barra lateral |

### 2. Cambios por archivo

| Archivo | Qué se cambió o agregó |
| :--- | :--- |
| `index.html` | Se reescribió con `<main>`, `<section>`, `<article>`, `<header>`, `<nav>` y `<footer>`; un solo `<h1>`; menú con enlaces que existen; encuesta con `<label>`; `lang="es"`, `meta description` y favicon; enlace «Saltar al contenido». |
| `left-sidebar.html`, `right-sidebar.html`, `no-sidebar.html` | Se reemplazó el contenido de demostración por información real; se agregaron `<aside>` y `<nav>` con índice, `<article>` por actividad, imágenes con `alt` y `loading="lazy"`. |
| `assets/css/main.css` | Variables de color del logo, tipografías, banner amarillo, secciones, tarjetas, estilos de foco visible y utilidades de accesibilidad. |
| `images/` | Se eliminaron imágenes de la plantilla; se agregaron fotos y afiches propios; se optimizó el logo (de 652 KB a 96 KB). |
| `elements.html` | Eliminado (página de demostración de la plantilla). |

### 3. Identidad visual

* **Colores (tomados del logo):** amarillo `#F7BF01`, rojo coral `#ED4A52`, coral oscuro `#C93440` para botones con texto blanco, y tinta `#1F2421` para texto.
* **Tipografías:** *Barlow Condensed* (títulos, parecida a las letras del logo) y *Nunito* (texto, redondeada y amable para público infantil), vía Google Fonts.
* **Contraste calculado (WCAG):** texto oscuro sobre amarillo 9.3:1, texto blanco sobre coral oscuro 5.2:1, texto blanco sobre fondo oscuro 15.8:1. Los tres superan el mínimo AA (4.5:1); el coral claro `#ED4A52` se usa solo en bordes y detalles, no para texto.

### 4. Ajustes respecto al plan del Sprint 1

* La sección *Voces de la Comunidad* no se publicó, porque los testimonios se recogieron con anonimato y todavía no se redactaron para el sitio.
* *Contacto y ubicación* y *Zonas y servicios* se integraron en la página **Nosotros**.
* La encuesta de la portada es demostrativa: el formulario aún no envía datos a ningún servidor.

### 5. Control de versiones

| N.º | Autor | Mensaje del commit |
| :-: | :--- | :--- |
| 1 | César | `style: aplica paleta del logo, tipografías y estilos de tarjetas, banner y accesibilidad` |
| 2 | Fátima | `chore: elimina elements.html e imágenes de plantilla y agrega imágenes de la biblioteca` |
| 3 | César | `feat: reestructura index.html con estructura semántica, navegación y actividades reales` |
| 4 | Fátima | `feat: convierte left-sidebar.html en talleres, música y teatro con información real` |
| 5 | César | `feat: convierte right-sidebar.html en cine, lectura y charlas con información real` |
| 6 | Fátima | `feat: convierte no-sidebar.html en página Nosotros con ubicación y contacto` |
| 7 | César | `docs: completa implementación del README con cambios, identidad visual y commits` |
| 8 | Fátima | `docs: registra verificación del despliegue en GitHub Pages y URLs finales` |

### 6. Verificaciones realizadas

| Verificación | Resultado |
| :--- | :---: |
| Los enlaces internos y anclas del menú llevan a secciones existentes | ☐ |
| Todas las imágenes cargan (sin íconos rotos) | ☐ |
| Cada página tiene un solo `<h1>` y encabezados en orden | ☐ |
| Se puede navegar con teclado y se ve el foco | ☐ |
| Vista correcta en celular (ancho de 375 px) | ☐ |
| Los enlaces a Instagram, WhatsApp y Linktree abren | ☐ |
git push origin main
---

## Despliegue

(Sección reservada para la verificación del funcionamiento del sitio publicado mediante GitHub Pages y sus enlaces correspondientes).

---

## Bibliografía

* HTML5 UP. *Landed Template*. Disponible en: [https://html5up.net/landed](https://html5up.net/landed)
* Biblioteca de las Artes. Perfil oficial de Instagram: [@bibliouartes](https://www.instagram.com/bibliouartes)
* Biblioteca de las Artes. Canal oficial de WhatsApp para difusión de talleres y agenda cultural.(https://whatsapp.com/channel/0029VarUfghHltYImKMChr0y)