# TP1 - Landing Page: Hidromiel Artesanal

Descripción del proyecto
------------------------
Nuestro proyecto es una página web estática que muestra qué es la hidromiel, sus ingredientes y los pasos básicos para aprender a elaborarla. 

Decidimos armarlo a partir de la charla que tuvimos la primera clase cuando el profesor Matías dio las consignas. Ahí fue cuando surgió el tema de la hidromiel, ya que uno de los integrantes tenía la experiencia cercana de haberla hecho. Elegimos hacer una web que muestre el proyecto ya que no hay mucha información que enseñe a fabricarla de forma casera.

Tecnologías
-----------
- HTML: Se utilizó para armar toda la estructura del sitio. Incluye un encabezado (`header`) con el menú de navegación, una sección de bienvenida (`hero`) con título, descripción y botón, secciones ordenadas con identificadores específicos (`que-es`, `ingredientes`, `pasos`, `tipos`), y tarjetas (`.cards` y `.card`) para organizar visualmente los ingredientes y las variedades de hidromiel.
- CSS: Se aplicó para controlar la apariencia completa de la web. Usamos un color de fondo principal crema (`#f5e6c8`), encabezado y pie de página en marrón oscuro (`#5c3b1e`), una imagen de fondo en la sección de bienvenida, estilos de tarjetas con fondo blanco, sombras y bordes redondeados, y un botón destacado en color dorado.

Integrantes y roles
-------------------
- Martín Ortiz — Colaborador (rama: `mejoras_martin`).
- Facundo Sotelo — Propietario.

Pasos para ejecutar el proyecto
-------------------------------
1. Clonar el repositorio:
   git clone [https://github.com/escfacundosotelo2024-wq/hidromiel-artesanal-gestion-de-proyectos.git](https://github.com/escfacundosotelo2024-wq/hidromiel-artesanal-gestion-de-proyectos.git)
Entrar a la carpeta del proyecto:
cd hidromiel-artesanal-gestion-de-proyectos
Abrir la página:
Se puede hacer doble clic directamente sobre el archivo index.html o levantar un servidor local desde la terminal con Python de la siguiente forma:
python -m http.server 8000
Y luego, abrir en el navegador la dirección: http://localhost:8000
Flujo de trabajo realizado
Crear una rama nueva para trabajar los cambios sin romper nada: git checkout -b nombre_rama.
Guardar los cambios locales: git add . y luego git commit -m "mensaje explicativo".
Subir la rama creada a GitHub: git push origin nombre_rama.
Abrir un Pull Request hacia la rama principal (main) y esperar la revisión de los compañeros antes de unir el código.
Mantener la buena práctica de no subir cambios directamente a la rama main.
© 2026 Martín Ortiz & Facundo Sotelo. Proyecto desarrollado con fines educativos para la materia Gestión de Proyectos. Se permite su uso, copia y modificación.