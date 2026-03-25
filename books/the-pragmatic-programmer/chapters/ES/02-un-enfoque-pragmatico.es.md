[← Volver al libro](../../README.es.md) | [↑ Volver al índice](../../../../README.es.md) | [🌐 Cambiar idioma](../EN/02-a-pragmatic-approach.md)

# 02 - Un enfoque pragmático

> Navegación rápida: [Idea central](#idea-central) · [Conceptos clave](#conceptos-clave) · [Acciones](#acciones) · [Notas relacionadas](#notas-relacionadas)

## Idea central

La ortogonalidad reduce fricción: cuando los componentes están bien aislados, puedes cambiar uno sin romper los demás mientras mantengas su interfaz. Lo contrario (sistemas no ortogonales) vuelve el cambio caro y riesgoso, porque todo choca con todo.

## Conceptos clave

- **Beneficio de la ortogonalidad:** mejora control, mantenibilidad y velocidad de cambio.
- **Costo del acoplamiento:** en sistemas no ortogonales, una decisión local impacta múltiples partes.
- **Ejemplo del helicóptero:** aunque parezca simple por cantidad de controles, cada ajuste afecta otros parámetros y exige compensaciones constantes.
- **Aislamiento por interfaces:** si no cambian las interfaces externas, se puede evolucionar un componente con menos riesgo.
- **Dependencias de terceros:** cada herramienta o biblioteca puede introducir acoplamientos ocultos; hay que elegir con criterio.
- **Código desacoplado como disciplina:** evitar datos globales, duplicación funcional y funciones demasiado parecidas.
- **Pruebas como señal de diseño:** si una prueba unitaria necesita importar gran parte del sistema, hay falta de desacople.
- **Reversibilidad:** asumir que nada es permanente; diseñar decisiones que puedan cambiar cuando el contexto cambie.

## Citas (solo breves)

- "Nada es más peligroso que una idea si es la única que tienes."
- "En vez de grabar decisiones en piedra, escríbelas en la arena de la playa."

## Mi interpretación

Este capítulo me aterriza dos hábitos: diseñar para evitar efectos colaterales y decidir sabiendo que el futuro cambia. La ortogonalidad no es un lujo de arquitectura; es una forma práctica de reducir incidentes y de mantener capacidad de evolución.

## Lecciones prácticas

- Cada línea de código puede subir o bajar el acoplamiento: hay que revisar ese impacto de forma intencional.
- Si una prueba unitaria requiere medio sistema para correr, la modularidad está fallando.
- Introducir tecnología por moda suele encarecer cambios futuros.
- Diseñar reversibilidad permite corregir rumbo sin rehacer todo.

## Preguntas

- ¿Qué partes de mi sistema cambian juntas por diseño deficiente y no por necesidad real?
- ¿Qué bibliotecas de terceros están imponiendo decisiones difíciles de revertir?
- ¿Cuántos futuros posibles soporta hoy mi arquitectura?
- ¿Qué tan costoso sería cambiar una decisión crítica en seis meses?

## Acciones

- [ ] Revisar un módulo actual e identificar acoplamientos innecesarios entre componentes.
- [ ] Eliminar al menos una dependencia global (estado global o acceso compartido) en la próxima iteración.
- [ ] Crear o ajustar una prueba unitaria para que ejecute con dependencias mínimas.
- [ ] Documentar una decisión técnica importante con su plan de reversión.
- [ ] Continuar completando las notas pendientes del resto del capítulo 2.

## Notas relacionadas

- Capítulo 1: [01 - Una filosofía pragmática](01-una-filosofia-pragmatica.es.md)
- Prefacio: [00 - Prefacio (primera edición)](00-prefacio.es.md)
- Revisión de código: [09 - Revisión de código](../../../software-engineering-at-google/chapters/ES/09-revision-de-codigo.es.md)
- Índice del libro: [The Pragmatic Programmer - README.es](../../README.es.md)

## Ver también

- Plantilla de capítulo: [chapter-template.es.md](../../../../templates/chapter-template.es.md)
- Índice del repositorio: [README.es.md](../../../../README.es.md)

---

**Navegación**

- Capítulo anterior: [01 - Una filosofía pragmática](01-una-filosofia-pragmatica.es.md)
- Capítulo siguiente: Pendiente
- Notas relacionadas: [README del libro](../../README.es.md), [Versión en inglés](../EN/02-a-pragmatic-approach.md)

## Aviso legal

- Estas notas son interpretaciones personales y material de aprendizaje.
- Cualquier contenido citado pertenece a sus autores y editoriales originales.
- Las citas son breves, se atribuyen cuando es posible y se usan con fines educativos.
- Este repositorio no republica capítulos completos ni extractos sustanciales con copyright.
