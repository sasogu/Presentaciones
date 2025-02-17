# Presentaciones con Reveal.js

Este repositorio contiene diversas presentaciones creadas con [Reveal.js](https://revealjs.com/), una biblioteca de código abierto para generar presentaciones en HTML.

## 🚀 Cómo usar

Para visualizar una presentación localmente, sigue estos pasos:

1. Clona el repositorio:
   ```sh
   git clone https://github.com/sasogu/Presentaciones.git
   cd Presentaciones
   ```

2. Abre una presentación en tu navegador. Si el archivo es `index.html`, simplemente haz doble clic sobre él o utiliza un servidor local como:

   ```sh
   python -m http.server 8000
   ```

   Luego accede en tu navegador a `http://localhost:8000`.

## 📂 Estructura del Repositorio

```
Presentaciones/
│── presentacion1/
│   ├── index.html
│   ├── style.css
│   ├── images/
│── presentacion2/
│   ├── index.html
│   ├── script.js
│   ├── assets/
│── README.md
│── reveal.js/  (opcional, si está incluido en el repo)
```

Cada carpeta contiene una presentación independiente con sus propios archivos de estilo, imágenes y scripts.

## ✨ Características

- Presentaciones interactivas en HTML, CSS y JavaScript.
- Soporte para Markdown y código en vivo.
- Temas y estilos personalizables.
- Posibilidad de añadir transiciones, fragmentos y animaciones.

## 📌 Dependencias

Si Reveal.js no está incluido en el repositorio, puedes instalarlo con:

```sh
git submodule update --init --recursive
```

O bien, enlazarlo desde un CDN:

```html
<script src="https://unpkg.com/reveal.js@4/dist/reveal.js"></script>
```

## 🎯 Contribuir

Si deseas añadir o mejorar una presentación:

1. Haz un fork del repositorio.
2. Crea una rama con los cambios.
3. Realiza un pull request explicando tus modificaciones.

## 📜 Licencia

Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

¡Disfruta creando y compartiendo presentaciones interactivas con Reveal.js! 🎤🚀
```

reveal.js is an open source HTML presentation framework. It enables anyone with a web browser to create beautiful presentations for free. Check out the live demo at [revealjs.com](https://revealjs.com/).

The framework comes with a powerful feature set including [nested slides](https://revealjs.com/vertical-slides/), [Markdown support](https://revealjs.com/markdown/), [Auto-Animate](https://revealjs.com/auto-animate/), [PDF export](https://revealjs.com/pdf-export/), [speaker notes](https://revealjs.com/speaker-view/), [LaTeX typesetting](https://revealjs.com/math/), [syntax highlighted code](https://revealjs.com/code/) and an [extensive API](https://revealjs.com/api/).


Want to create reveal.js presentation in a graphical editor? Try <https://slides.com>. It's made by the same people behind reveal.js.

 Getting started
- 🚀 [Install reveal.js](https://revealjs.com/installation)
- 👀 [View the demo presentation](https://revealjs.com/demo)
- 📖 [Read the documentation](https://revealjs.com/markup/)
- 🖌 [Try the visual editor for reveal.js at Slides.com](https://slides.com/)
- 🎬 [Watch the reveal.js video course (paid)](https://revealjs.com/course)
