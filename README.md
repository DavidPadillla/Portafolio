# David Padilla — Portfolio

Portafolio estático bilingüe en HTML5, CSS3 y JavaScript ES Modules. No necesita compilación ni Node.js.

## Ejecutar

Desde esta carpeta: `python -m http.server 5500` y abrir `http://localhost:5500`. Evita abrir `index.html` mediante `file://`, porque los módulos ES requieren servidor HTTP. También sirve la extensión Live Server de VS Code.

## Publicar

Sube el contenido a un repositorio de GitHub. En GitHub Pages: Settings → Pages → Deploy from a branch → main / root. Alternativamente arrastra la carpeta a Netlify.

## Editar contenido

- Textos en español e inglés: `locales/es.js` y `locales/en.js`.
- Proyectos y enlaces: `data/projects.js`.
- Tecnologías: `js/main.js` (`skillGroups`).
- Colores y estilos: `css/style.css`.
- Fotografía: añade `assets/images/profile/david.jpg` y cambia `PHOTO_AVAILABLE` a `true` en `js/main.js`.
- CV: añade `assets/documents/CV-David-Padilla.pdf` y cambia `CV_AVAILABLE` a `true`.
- SEO: configura el dominio real en `index.html`, `robots.txt` y `sitemap.xml` al publicar.

## Contacto

El formulario valida campos y prepara un mensaje `mailto:`. **No envía mensajes por sí solo**: depende de una aplicación de correo configurada y requiere que la persona confirme el envío. Para recepción directa desde la web, integrar un proveedor real (Formspree, Netlify Forms u otro), configurar la cuenta y verificar errores y protección anti-spam. No se almacenan claves privadas.

## Limitaciones

Sin fotografía, CV, artículos, certificaciones ni enlaces no confirmados. Las composiciones de las tarjetas de proyectos son gráficas decorativas, no capturas. El despliegue de LECTIO en Render puede demorar al iniciarse. Las fechas de prácticas no se han inventado.
