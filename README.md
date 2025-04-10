## Ejercicio 1: Identificación de Tokens


### Instrucciones para los estudiantes:
- Analiza el fragmento de código proporcionado línea por línea
- Identifica cada token individual (la unidad más pequeña con significado)
- Clasifica cada token según su tipo
- Registra la posición exacta (línea y columna) donde aparece cada token

**Tipos de tokens comunes:**
- Palabras clave: Reservadas por el lenguaje (`if`, `while`, `int`, etc.)
- Identificadores: Nombres de variables o funciones
- Literales: Valores constantes (números, cadenas de texto)
- Operadores: Símbolos que realizan operaciones (`+`, `-`, `*`, `/`)
- Separadores: Delimitadores como paréntesis, llaves, punto y coma

**Ejemplo resuelto:**

```java
int suma = 10 + 5;
if (suma > 10) {
    print("El resultado es mayor que 10");
}
```

**Tabla de tokens resultante:**

| Token     | Tipo             | Línea | Columna |
|-----------|------------------|-------|---------|
| int       | Palabra clave    | 1     | 1       |
| suma      | Identificador    | 1     | 5       |
| =         | Operador         | 1     | 10      |
| 10        | Literal (entero) | 1     | 12      |
| completar |                  |       |         |

