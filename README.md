Taller Integrador Individual — Parte A
Bernal De la peña Juan Angel
Auditoría y corrección de la página "Calculadora de Promedio de Notas", siguiendo el flujo de trabajo con ramas, commits convencionales y Pull Requests visto en clase.

Tabla de hallazgos de la auditoría

Defecto encontrado | Por qué era un problema | Cómo lo corregí |

Nombres de archivo | "Mi Pagina De Notas.HTML" y "Estilos Del Sitio.CSS" usan espacios y mayúsculas mezcladas. No siguen ninguna convención de nombres de archivo. | Renombrados a `index.html` y `estilos.css`. |
Variable `x` | Número mágico sin nombre descriptivo; no indicaba que representaba la cantidad de notas, y nunca cambiaba de valor. | Renombrada a `cantidadNotas` y declarada con `const`. |
Variable `TempValue2` | Nombre no descriptivo, mezclaba "Temp" con Pascal Case y un sufijo numérico sin significado. | Renombrada a `promedio`. |
Variable `data1` sin usar | Se declaraba `let data1 = []` pero nunca se utilizaba; código muerto. | Eliminada por completo. |
Variables `a`, `b`, `c` | Nombres de una sola letra que no indicaban qué almacenaban. | Renombradas a `nota1`, `nota2` y `nota3`. |
Nombre de la función `calc()` | Nombre demasiado corto y ambiguo. | Renombrada a `calcularPromedio()`. |
Identificadores HTML `n1`, `n2`, `n3` | No describían su contenido. | Renombrados a `notaUno`, `notaDos` y `notaTres`. |
Identificadores HTML `r` y `r2` | Nombres ambiguos que no indicaban qué mostraban. | Renombrados a `resultadoPromedio` y `resultadoEstado`. |
Título de la pestaña del navegador | El `<title>` era simplemente "pagina". | Cambiado a "Calculadora de Promedio de Notas". |
Líneas de código sin función | Quedaba una función comentada (`calcularAntiguo`) y varios `console.log` de depuración. | Eliminados todos. |
Evento `onclick` embebido en el HTML | Mezclaba estructura (HTML) con comportamiento (JavaScript). | Se quitó del HTML y se asoció el evento desde JavaScript con `addEventListener`. |

Sitio publicado
