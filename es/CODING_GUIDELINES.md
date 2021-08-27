# Guiá de codificación

- Puede validar que su código cumpla con estas reglas ejecutando `stuff / php-format.py validate`
- Tabuladores, sin espacios
- El final de la línea debe ser estilo Unix (`\n`), no estilo Windows (`\r\n`)
- Los corchetes de apertura van en la misma línea que la última declaración

```
    if (condición) {
        cosas;
    }
```

- Un espacio entre palabras clave y paréntesis para: `if`,` else`, `while`,` switch`, `catch`,` function`
- Las llamadas a funciones no tienen espacio antes del paréntesis.
- No se dejan espacios entre paréntesis
- Un espacio después de cada coma, pero sin espacio antes
- Todos los operadores binarios deben tener un espacio antes y otro después
- No debe haber más de una línea en blanco contigua
- No debe haber comentarios vacíos.
- No debe usar comentarios de bloque `/ * ... * /`, solo línea `// ...`
- Los cambios en la funcionalidad deben ir acompañados de sus respectivas nuevas/modificadas pruebas
- Se deben utilizar excepciones para informar estados erróneos. Se permite el uso de funciones que devuelven verdadero/falso cuando son valores esperados
- Utilizar [RAII](https://es.wikipedia.org/wiki/RAII) cuando corresponda, principalmente en la administración de recursos (archivos, etc ...)
