# Brawl Stars · Página de fans

Sitio web de varias páginas sobre **Brawl Stars**, hecho como proyecto escolar de tema libre. Está hecho con **HTML y Bootstrap**, sin JavaScript, para practicar componentes y enlaces entre páginas.

> **Aviso:** es un proyecto educativo y de fans, hecho con tono de parodia. No tiene relación con Supercell. Brawl Stars, sus personajes e imágenes pertenecen a Supercell.

🔗 **Ver en línea:** [pagina](https://rogelioprado-dev.github.io/Brawl-stars-fan-page/)

---

## Qué incluye

| Pagina | Archivo | Contenido |
|---|---|---|
| Inicio | `index.html` | Brawlers de la semana, información en acordeón y guía para principiantes |
| Brawlers | `1Brawlers.html` | Catálogo de brawlers organizado por rareza |
| ¿Qué es Brawl Stars? | `1QueEs.html` | Historia y desarrollo del juego |
| Brawl Talk | `1BrawlTalk.html` | Video, evento activo y novedades de la temporada(desactualizado) |
| Meta Brawl | `1Meta.html` | Brawlers del meta actual por categorías |
| FAQs | `1FAQs.html` | Preguntas frecuentes en acordeón |
| Contacto | `1ContactUs.html` | Formularios de registro y comentarios (simulación) |

## Tecnologías

- **HTML5**
- **Bootstrap 5.3.8** (cargado desde CDN, hace falta internet para ver los estilos)
- CSS propio mínimo (fondo oscuro y colores del tema solamente)

## Componentes de Bootstrap que practiqué

- Navbar responsive con menú desplegable
- Breadcrumbs
- Carruseles de imágenes
- Tarjetas (cards)
- Acordeones
- Tablas
- Formularios(sin funcionamiento)
- Sistema de rejilla
- Footer con enlaces a todas las páginas

## Cómo verlo

1. Descarga o clona el repositorio.
2. Abre `index.html` en tu navegador.

Mantén todos los archivos juntos en la misma carpeta (HTML, imágenes y el video), porque las rutas son relativas.

## Estructura

```
├── index.html
├── 1Brawlers.html
├── 1QueEs.html
├── 1BrawlTalk.html
├── 1Meta.html
├── 1FAQs.html
├── 1ContactUs.html
├── *.jpg          (imágenes del sitio)
└── videobrawl.mp4 (video de Brawl Talk)
```

## Limitaciones conocidas

Esto es un proyecto de práctica, y algunas cosas no funcionan o son mejorables. Las dejé documentadas a propósito:

- **El buscador del navbar no funciona**, porque el proyecto no usa JavaScript.
- **Los formularios no envían información.** Son solo una simulación visual y no guardan ningún dato.
- Algunos botones y enlaces son decorativos (por ejemplo "Disabled").
- Hay errores menores en el HTML (etiquetas sin cerrar, clases mal escritas, textos alternativos genéricos en imágenes). Los dejé como registro de mi progreso .
- El contenido del juego (eventos, fechas, datos) corresponde a octubre de 2026 y puede estar desactualizado.

## Lo que aprendí

- A estructurar un sitio de varias páginas con enlaces entre ellas y una navegación consistente.
- A usar los componentes y la rejilla de Bootstrap para diseños responsive.
- A organizar contenido largo con acordeones, tarjetas y tablas.
- A depurar errores de HTML y a distinguir cuáles afectan la página y cuáles no.
- Que repetir el mismo navbar y footer en cada página es incómodo de mantener mas si deseas cambiar o añadir direcciones.
- Subir este proyecto a GitHub aprendí del entorno de GitHub, subir proyectos, estructurar un readme, etc.

## Próximos pasos

- Corregir los errores de HTML restantes y validarlo con el validador de W3C
- Mejorar los textos alternativos (`alt`) de las imágenes
- Añadir un buscador funcional con JavaScript
- Reutilizar navbar y footer con `include` de PHP
- Añadir paginas secundarias de cada brawler con su información del mismo

## Créditos y fuentes

- Juego, nombres, personajes e imágenes: © Supercell. Proyecto no oficial.
- Información de referencia: [Brawl Stars Wiki en Fandom](https://brawlstars.fandom.com/wiki/Brawl_Stars_Wiki)
- Framework: [Bootstrap](https://getbootstrap.com/).

## Autor

José Rogelio Prado Cosio · Estudiante de [CBTIS62 / 3er Semestre] · [GitHub](https://github.com/rogelioprado-dev)
