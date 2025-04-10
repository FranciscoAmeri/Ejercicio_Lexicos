

## Ejercicio 2: Diseño de Expresiones Regulares

**Objetivo:** Aprender a definir patrones formales para identificar diferentes tipos de tokens mediante expresiones regulares.

### Conceptos clave:
- **Caracteres literales:** Coinciden consigo mismos (a, b, 1, 2...)
- **Clases de caracteres:** `[a-z]`, `[A-Z]`, `[0-9]`
- **Cuantificadores:** `*`, `+`, `?`, `{n}`, `{n,m}`
- **Alternativas:** `|` (OR lógico)
- **Agrupación:** `( )`
- **Caracteres especiales:** `\d`, `\w`, `\s`

### Ejemplos de expresiones regulares:
- **Identificadores en Java:** `[a-zA-Z_][a-zA-Z0-9_]*`
- **Números enteros:** `[0-9]+`
- **Punto flotante:** `[0-9]+\.[0-9]+`
- **Notación científica:** `[0-9]+(\.[0-9]+)?[eE][+-]?[0-9]+`
- **Cadenas:** `"[^"]*"` o `"(\\.|[^"\\])*"`
- **Comentarios:** `//.*` y `/\*[\s\S]*?\*/`

### Actividad práctica:
- Probar las expresiones en https://regex101.com/
- Validar casos positivos y negativos
- Refinar expresiones
