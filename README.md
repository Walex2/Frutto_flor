# Frutto Forastero — Generador de Radar de Cata

Herramienta interna para crear gráficos de perfil de cata en formato SVG, listos para insertar en las fichas de producto de la web (Odoo).

## Cómo usar

1. Abre la herramienta en el navegador
2. Elige la variante de color (Verde o Naranja)
3. Ajusta los 5 atributos de cata con los sliders (escala 6–10)
4. Introduce la puntuación total
5. Pulsa **"Generar código para Odoo"**
6. Copia el HTML y pégalo en un bloque HTML de la página del producto en Odoo

## Colores de marca

| Variante | Fondo | Pétalos |
|---|---|---|
| Verde | Green Coffee `#4F6045` | Sour `#D49C36` |
| Naranja | Sweet `#F4643F` | Spices `#6C1916` |

## Archivos

- `index.html` — la herramienta completa (no requiere servidor ni dependencias)

## Contexto técnico

Para la integración nativa en Odoo (campos editables desde el backend), ver el brief técnico en el repositorio del proyecto o contactar con el partner de desarrollo.
