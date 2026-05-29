# Tipografía — Prime Gym

## Estado

> El texto del logo está **completamente vectorizado** (convertido a paths SVG), por lo que no se puede extraer directamente el nombre de la fuente del archivo SVG. Las recomendaciones siguientes están basadas en el estilo visual deportivo premium identificado.

---

## Análisis del Estilo Tipográfico

A partir de la estructura visual del logo y el contexto de marca deportiva-wellness urbana, el estilo tipográfico de Prime Gym responde a:

- **Mayúsculas predominantes** (ALL CAPS en el logo)
- **Trazos limpios y geométricos** — sin serifa o con serifa mínima
- **Peso bold/black** para el nombre de marca
- **Alta legibilidad** en contextos digitales y deportivos

---

## Fuentes Recomendadas (para Claude Design)

> Para reconstruir la identidad tipográfica, se recomiendan las siguientes opciones compatibles con el estilo detectado:

### Opción A — Fuentes Geométricas Sans-Serif (estilo principal)
| Uso | Fuente | Variante |
|---|---|---|
| Wordmark / Títulos hero | **Bebas Neue** | Regular (solo mayúsculas) |
| Subtítulos | **Montserrat** | Bold / ExtraBold |
| Cuerpo / Párrafos | **Montserrat** | Regular / Medium |
| Etiquetas / UI | **Montserrat** | SemiBold |

### Opción B — Fuentes más Premium/Deportivas
| Uso | Fuente | Variante |
|---|---|---|
| Wordmark / Títulos hero | **Barlow Condensed** | ExtraBold / Black |
| Subtítulos | **Barlow** | Bold |
| Cuerpo / Párrafos | **Barlow** | Regular |

---

## Jerarquía Tipográfica Sugerida

```
H1 — Hero / Nombre de sección principal
  Fuente: Bebas Neue o Barlow Condensed ExtraBold
  Tamaño: 48–96px
  Color: #FFFFFF o gradiente aplicado como fill
  Transform: UPPERCASE

H2 — Subtítulos de sección
  Fuente: Montserrat Bold
  Tamaño: 32–48px
  Color: #FFFFFF

H3 — Titulillos de card / servicio
  Fuente: Montserrat SemiBold
  Tamaño: 20–28px
  Color: #FFFFFF o #3BFF28

Body — Párrafos descriptivos
  Fuente: Montserrat Regular
  Tamaño: 14–18px
  Color: #FFFFFF con 80% opacidad

Label / Tag — Etiquetas, horarios, precios
  Fuente: Montserrat SemiBold
  Tamaño: 12–14px
  Color: #7D00D6 o gradiente
  Transform: UPPERCASE con letter-spacing amplio
```

---

## Escala y Espaciado

```
Line-height recomendado:
  Títulos: 1.1–1.2
  Subtítulos: 1.3
  Cuerpo: 1.6–1.8

Letter-spacing:
  Títulos ALL CAPS: 0.05em–0.15em
  Labels: 0.1em–0.2em
  Cuerpo: normal (0)
```

---

## Google Fonts (para implementación web)

```html
<!-- Importar en el <head> -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Montserrat:wght@400;600;700;800&display=swap" rel="stylesheet">
```

```css
:root {
  --font-display: 'Bebas Neue', sans-serif;
  --font-body: 'Montserrat', sans-serif;
}
```
