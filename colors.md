# Paleta de Colores — Prime Gym

## Colores Primarios (Gradiente del Logo)

El sello visual de Prime Gym es un **gradiente dinámico** que corre de verde lima a azul eléctrico, transmitiendo energía, movimiento y progreso.

| Rol | Color | Hex | RGB | Uso |
|---|---|---|---|---|
| Inicio gradiente | Verde Lima | `#3BFF28` | rgb(59, 255, 40) | Acento energético, CTAs primarios |
| Punto medio | Cian/Aqua | `#00FFFF` | rgb(0, 255, 255) | Transición, highlights |
| Fin gradiente | Azul Eléctrico | `#2F6BFF` | rgb(47, 107, 255) | Confianza, elementos secundarios |

### CSS del Gradiente Principal
```css
background: linear-gradient(90deg, #3BFF28 0%, #00FFFF 50%, #2F6BFF 100%);
```

---

## Colores Secundarios

| Rol | Color | Hex | RGB | Uso |
|---|---|---|---|---|
| Acento Púrpura | Magenta/Violeta | `#7D00D6` | rgb(125, 0, 214) | Elementos destacados, badges, iconos de apoyo |
| Blanco Puro | Blanco | `#FFFFFF` | rgb(255, 255, 255) | Texto principal, elementos sobre fondos oscuros |

---

## Colores Neutros / Fondos

> Inferidos del estilo visual deportivo/premium de la marca. Verificar con el equipo de diseño.

| Rol | Color | Hex | Uso sugerido |
|---|---|---|---|
| Fondo Oscuro | Negro Profundo | `#0A0A0A` | Background principal (dark mode) |
| Fondo Medio | Gris Oscuro | `#1A1A1A` | Cards, secciones alternadas |
| Fondo Suave | Gris Antracita | `#2A2A2A` | Bordes, separadores |

---

## Uso del Color

### Reglas de aplicación
- El **gradiente verde→azul** es el elemento de mayor identidad. Usarlo en: barras decorativas, botones CTA, iconos activos, títulos hero.
- El **púrpura `#7D00D6`** aparece en gráficos de apoyo y recursos secundarios. No competir con el gradiente principal.
- El **blanco `#FFFFFF`** es el color de texto por defecto sobre fondos oscuros.
- Mantener siempre **alto contraste** (paleta dark): la marca tiene ADN nocturno/energético.

### Combinaciones válidas
| Fondo | Texto | Acento |
|---|---|---|
| `#0A0A0A` | `#FFFFFF` | gradiente `#3BFF28→#2F6BFF` |
| `#1A1A1A` | `#FFFFFF` | `#7D00D6` |
| gradiente | `#0A0A0A` o `#FFFFFF` | — |

---

## Moodboard de Color

```
┌─────────────────────────────────────────────────────┐
│  #3BFF28   ████  Verde Lima    — Energía / Arranque │
│  #00FFFF   ████  Cian          — Frescura / Flujo   │
│  #2F6BFF   ████  Azul Eléc.   — Confianza / Meta    │
│  #7D00D6   ████  Púrpura      — Premium / Exclusivo │
│  #FFFFFF   ░░░░  Blanco        — Claridad / Limpieza │
│  #0A0A0A   ████  Negro         — Base / Sofisticación│
└─────────────────────────────────────────────────────┘
```
