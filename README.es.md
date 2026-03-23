# Dev Notes

Una base de conocimiento bilingue (con espanol como idioma principal) para notas personales de libros de ingenieria de software.

## Por que existe este repositorio

Este repositorio existe para convertir notas de lectura en un manual practico de ingenieria:

- Capturar reflexiones personales, aprendizajes e ideas accionables.
- Mantener los conceptos faciles de encontrar por libro, capitulo y tema.
- Compartir notas publicamente con una traduccion profesional al ingles.
- Construir una referencia de largo plazo que siga siendo util con el tiempo.

## Politica de idioma

- El espanol es la fuente de verdad.
- El ingles es una traduccion limpia y profesional.
- Cada archivo usa un solo idioma.

## Indice de libros

- `software-engineering-at-google`
  - Ingles: [`books/software-engineering-at-google/README.md`](books/software-engineering-at-google/README.md)
  - Espanol: [`books/software-engineering-at-google/README.es.md`](books/software-engineering-at-google/README.es.md)

## Como se organizan las notas

Las notas se organizan en tres niveles:

1. Indice del repositorio (`README.md`, `README.es.md`)
2. Indice por libro (`books/<book-name>/README*.md`)
3. Notas por capitulo (`books/<book-name>/chapters/*.md`)

Cada capitulo incluye navegacion superior e inferior, cambio de idioma y enlaces cruzados.

## Estructura del repositorio

```text
.
├── LICENSE
├── README.es.md
├── README.md
├── books/
│   └── software-engineering-at-google/
│       ├── README.es.md
│       ├── README.md
│       └── chapters/
│           ├── 01-introduction.es.md
│           └── 01-introduction.md
└── templates/
    ├── book-template.es.md
    ├── book-template.md
    ├── chapter-template.es.md
    └── chapter-template.md
```

## Como navegar

Usa esta ruta para navegar rapido:

1. Empieza desde el indice de libros en este archivo.
2. Abre el README de un libro para ver la tabla de contenidos por capitulos.
3. Abre un capitulo y usa:
   - `← Volver al libro`
   - `↑ Volver al indice`
   - `🌐 Cambiar idioma`
4. Muevete entre capitulos desde la navegacion inferior:
   - `Capitulo anterior`
   - `Capitulo siguiente`
   - `Notas relacionadas`

## Como usar este repositorio

- Usa las plantillas en `templates/` para agregar libros y capitulos.
- Actualiza primero los archivos en espanol y despues traduce al ingles.
- Agrega citas breves y acciones practicas.
- Mantener enlaces cruzados entre conceptos relacionados.

## Licencia

Este proyecto esta licenciado bajo Creative Commons Attribution 4.0 International (CC BY 4.0).

Consulta [`LICENSE`](LICENSE).

## Aviso legal

- Estas notas son interpretaciones personales y material de aprendizaje.
- Cualquier contenido citado pertenece a sus autores y editoriales originales.
- Las citas son breves y se incluyen con fines educativos.
