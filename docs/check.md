## A1

```
--paso-menos-1: clamp(0.8333rem, 0.8111rem + 0.099vw, 0.9rem);
```

Según la documentación el tamaño mínimo es 16px y el máximo es 18px.
El termino rem es obligatorio porque un tamaño solo en vw no crece ampliando el texto e incumple la

```
color: var(--color-acento);
```
Este trozo de código estable el tema para el color del elemento con los valores primitivos establecidos en el _token.scss:

```
"acento": ("acento-700", "acento-400"),
```

## A2
Para trabajar en una empresa con un equipo me planteria el uso de Figma como alternativa ya que una de sus ventajas es que te permite trabajar en simultaneo con tus compañeros. Por otro lado hay gente que prefiere trabajar directamente con el codigo lo que supone una desventaja ya que no dispone de algo similar


## A3

--color-acento

1. Este token pasa por _tokens.scss, _index.scss.
2. Porque Stylelint marca @import como error y será eliminado en la versión 3 por lo que hace que el código no sea escalable.
3. Falso, porque Chrome solo lee estilos.css

## A4

1. Se llegará desde el menú principal mediante un elemento <a> dentro del <header>
2. Se vuelve a través del menú principal
3. Cabecera -> Menú: Incidencias -> incidencias.html .
4. Debe ir ya que comprobando en diferentes pantallas gracias a chrome vemos que aún tenemos espacio suficiente para hacerlo responsive.
