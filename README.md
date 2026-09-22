# Taller integrador — Auditoría y corrección de sitio web

**Nombre completo:** Jorge Andres Sanchez Cuadrado

## Sitio publicado
[COMPLETA CON EL LINK DE NETLIFY]

## Tabla de hallazgos

| Defecto encontrado | Por qué era un problema | Cómo lo corregí |
|---|---|---|
| Nombres de archivo con espacios y extensión en mayúscula | Los espacios y las mayúsculas pueden causar errores al referenciarlo desde el código | Se renombraron a `index.html` y `styles.css` |
| Variables `a`, `b`, `c` | No se sabe qué representa cada una sin ir a revisar dónde se usan | Se renombraron a `nota1`, `nota2`, `nota3` |
| Variable `x` | Al tener una variable `x`, es imposible saber para qué se usa sin antes revisar el código | Se reemplazó por la constante `CANTIDAD_NOTAS` |
| Variable `TempValue2` | El nombre no tiene sentido ya que realmente no hay un "TempValue1" y puede llegar a confundir | Se renombró a `promedio` |
| Variable `data1` sin usar | Hace pensar que la variable se usa en algún momento, pero es código muerto que no cumple ningún propósito | Se eliminó |
| Función `calc()` | El nombre no dice de inmediato qué es lo que calcula; hay que entrar a leer el código para adivinar qué hace | Se renombró a `calcularPromedio()` |
| IDs `n1`, `n2`, `n3`, `r`, `r2` | No describen el contenido del elemento | Se renombraron a `nota1`, `nota2`, `nota3`, `resultadoPromedio`, `resultadoEstado` |
| Título de pestaña `pagina` | No describe el contenido del sitio | Se cambió a `Calculadora de Promedio` |
| Función comentada `calcularAntiguo` | Es código desactualizado que puede confundir al lector | Se eliminó |
| `console.log` de depuración | El hecho de que salga información que solo le interesa al programador puede molestar al lector | Se eliminaron |
| Número mágico `3.0` | No queda claro qué representa ese valor sin contexto | Se reemplazó por la constante `NOTA_MINIMA_APROBACION` |
| Clase CSS `.cont1` | El nombre no describe para qué se usa ni qué contiene; es un nombre genérico | Se renombró a `.tarjeta-calculadora` |
