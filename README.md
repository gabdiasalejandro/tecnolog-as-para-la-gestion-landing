# Tecnologías de Gestión — Landing

Página web interactiva que sirve de apoyo a la presentación de un **proyecto escolar**
(materia Tecnologías de Gestión, UVM · Laureate): *Emprendimiento e Impacto Ambiental*
y el *Asistente Virtual EnergyCo*.

> **Nota de autoría:** el contenido del proyecto escolar **no es mío**. Yo solo
> desarrollé esta página web **por encargo**; el trabajo académico pertenece a sus autores.

## Demo

https://gabdiasalejandro.github.io/tecnolog-as-para-la-gestion-landing/

## Uso local

```bash
python3 -m http.server 8000
# abrir http://localhost:8000
```

O simplemente abrir `index.html` en el navegador.

## Estructura

- `index.html` — página principal
- `quiz.html` — quiz interactivo de estimación
- `assets/styles.css` — estilos compartidos
- `assets/img/` — imágenes (WebP) y QR

## Stack

HTML + CSS + JavaScript, sin dependencias ni build. Funciona offline.
