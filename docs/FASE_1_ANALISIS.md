# Fase 1: Análisis 

## 1) Análisis comparativo de perfiles de referencia

| Criterio | Perfil 1: Shawn Wang ([@sw-yx](https://github.com/sw-yx)) | Perfil 2: Kavish Hukmani ([@kavishhukmani](https://github.com/kavishhukmani)) | Perfil 3: Michael Hoffmann ([@Mokkapps](https://github.com/Mokkapps)) |
| :--- | :--- | :--- | :--- |
| **Primer impacto** *(Claridad del rol, propuesta de valor, tono profesional)* | Comunica de inmediato su filosofía de "Learn in Public" y liderazgo técnico. En menos de 5 segundos queda claro su enfoque en desarrollo web, creación de contenido técnico e inteligencia artificial, con un tono profesional, influyente y directo. | Gran impacto visual centrado en diseño de producto y desarrollo Full-Stack. Utiliza una estética moderna, encabezados limpios y una presentación que resalta su rol como creador y diseñador de interfaces de forma amigable y concisa. | Enfoque consultor y freelancer senior. Transmite seriedad corporativa, especialización técnica clara en frontend/cloud y disponibilidad para contratos profesionales y asesoría técnica especializada. |
| **Organización y navegación** *(Repositorios fijados, uso de enlaces, orden visual)* | Estructura vertical impecable. Enlaces directos a sus libros, charlas técnicas, podcasts y ensayos. Sus repositorios fijados priorizan recursos educativos masivos y herramientas de alto impacto comunitario. | Secciones compactas divididas visualmente con separadores sutiles. Muestra badges de tecnologías por categoría y enlaces destacados a demos interactivos de sus proyectos principales sin saturar la pantalla. | Organización orientada a métricas y proyectos de producción. Secciones bien delimitadas que enlazan a sus últimos artículos de blog, repositorios de código abierto con estrellas y componentes reutilizables. |
| **Calidad de la documentación** *(Estructura de README, capturas, contexto técnico)* | Excepcional. Sus repositorios destacados incluyen problemas resueltos, casos de uso reales, guías de contribución claras y documentación exhaustiva con ejemplos de código reproducibles. | Alta calidad gráfica. Emplea GIFs ligeros y mockups limpios en los repositorios fijados para mostrar de inmediato la interfaz de usuario antes de explicar los pasos de instalación local. | Muy estructurada y profesional. Documenta dependencias exactas, badges de CI/CD (GitHub Actions), pipelines de pruebas automatizadas y comandos de despliegue claros paso a paso. |
| **Contacto** *(Canales disponibles y su visibilidad)* | Múltiples canales visibles en la parte superior: enlaces directos a su newsletter, Twitter/X, podcast personal y formulario/correo para conferencias y colaboraciones. | Enlaces directos al final de la introducción con iconos minimalistas: correo electrónico personal, perfil verificado de LinkedIn y enlace a portafolio web interactivo. | Enlace a su sitio web de consultoría, perfil de LinkedIn, correo empresarial visible y enlace directo a su agenda para reuniones técnicas y mentorías. |
| **Accesibilidad y lectura en móvil** *(Texto alternativo, contraste, dependencia de imágenes externas)* | Excelente adaptabilidad. Prioriza texto Markdown semántico sobre imágenes decorativas pesadas; carga rápido en conexiones móviles y mantiene contraste óptimo en temas claro y oscuro. | Buen contraste y adaptabilidad responsiva. Las imágenes utilizadas cuentan con dimensiones controladas para no desbordar en resoluciones móviles, aunque depende parcialmente de badges externos. | Diseñado pensando en legibilidad limpia. Texto plano bien formateado, tablas legibles y mínimo uso de scripts dinámicos externos que puedan ralentizar la carga en teléfonos. |

## 2) Lista de verificación de proyectos

Criterios de calidad que debe cumplir cada proyecto destacado en el perfil y portafolio:

- [ ] **Nombre y descripción clara:** Título conciso del repositorio acompañado de una descripción de una sola línea indicando el problema que resuelve y las tecnologías clave.
- [ ] **Captura de pantalla o demostración visual:** Vista previa gráfica o GIF optimizado de la interfaz de usuario en funcionamiento.
- [ ] **Enlace a demo funcional:** URL directa desplegada en producción (GitHub Pages, Vercel, Netlify o similar).
- [ ] **Guía de instalación y configuración local:** Instrucciones paso a paso que incluyan prerrequisitos, clonación del repositorio (`git clone`), instalación de dependencias (`npm install`), configuración de variables de entorno (`.env.example`) y comandos de ejecución (`npm run dev`).
- [ ] **Explicación de la arquitectura y tecnologías:** Justificación técnica del stack utilizado (Frontend, Backend, Base de Datos, Autenticación).
- [ ] **Etiquetas de repositorio (*Topics*):** Al menos 4-5 tags relevantes asignados (ej. `react`, `typescript`, `vite`, `material-ui`, `rest-api`).
- [ ] **Licencia clara:** Archivo `LICENSE` visible en la raíz (ej. MIT).

## 3) Diagnóstico de mis repositorios


## 4) Requisitos Definidos
### Requisitos Funcionales (RF)
* **RF-01 (Sección de Presentación):** El perfil debe presentar una introducción técnica directa indicando nombre, rol (Ingeniero en Computación / Full-Stack Developer), tecnologías principales y disponibilidad profesional.
* **RF-02 (Showcase de Proyectos):** El perfil debe exhibir un catálogo de proyectos destacados con título, descripción del reto técnico resuelto, stack utilizado y enlaces directos tanto al código fuente como al demo en vivo.
* **RF-03 (Acceso a Canales de Contacto):** Debe incluir enlaces directos, funcionales y visibles hacia el correo electrónico profesional, perfil de LinkedIn y CV descargable.
* **RF-04 (Métricas y Habilidades Técnicas):** Debe clasificar las competencias tecnológicas por categorías (Frontend, Backend, Bases de Datos, Herramientas / DevOps) mediante badges SVG estandarizados y visualmente limpios.

### Requisitos No Funcionales (RNF)
* **RNF-01 (Responsividad y Accesibilidad):** Toda la maquetación del portafolio o README debe adaptarse correctamente a dispositivos móviles y respetar estándares básicos de contraste tanto en tema claro como en tema oscuro.
* **RNF-02 (Rendimiento de Carga):** Los recursos multimedia (imágenes, diagramas o badges) no deben superar los 500 KB en total para garantizar un tiempo de carga instantáneo.
* **RNF-03 (Mantenibilidad y Versionado):** El código y la documentación deben seguir una estructura modular estandarizada, con historial de commits semánticos (`feat:`, `fix:`, `docs:`) y ramas de trabajo independientes.
