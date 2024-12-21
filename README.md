# 🍋 Ejercicio 2: Layout Lemoncode

Múltiples temas usando Sass.

## Estructura del Proyecto

```
proyecto/
├── sass/
│   ├── _theme-a.scss    # Variables del tema A (rojo)
│   ├── _theme-b.scss    # Variables del tema B (azul)
│   └── mystyle.scss     # Estilos principales
└── index.html
```

## Cómo Cambiar de Tema

Para cambiar entre temas, simplemente modifica la primera línea en el archivo `sass/mystyle.scss`:

### Para usar el tema A (rojo):

```scss
@use "theme-a" as theme;
```

### Para usar el tema B (azul):

```scss
@use "theme-b" as theme;
```

## Características de los Temas

Cada tema modifica:

- Colores base
- Fuentes
- Border Radius
- Shadow Box

### Tema A (Rojo)

- Colores: Rojo, Rojo oscuro, Rosa claro
- Fuentes: Arial y Georgia
- Sin border radius
- Shadow box suave

### Tema B (Azul)

- Colores: Azul, Azul oscuro, Cyan
- Fuentes: Helvetica y Times New Roman
- Border radius de 10px
- Shadow box más pronunciado
