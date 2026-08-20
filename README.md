# Mesón O Recuncho — landing de demo

Landing page de demostración para **Mesón O Recuncho**, tapería gallega de marisco en la
Rúa Pastor Díaz, 55 — 27850 Viveiro (Lugo). El negocio no tiene web propia; esta demo se
construye para enseñarle cómo sería la suya.

- **Publicada en:** https://alvarodesigns34.github.io/web5/
- **Un solo archivo:** `index.html` con CSS y JS embebidos, sin dependencias ni build.
  Lo único externo son las tipografías de Google Fonts y el iframe del mapa.
- **Fotos:** `img/` — fotos reales del local y de los platos.

## Contenido

Todos los datos de la página (carta, precios, horario, teléfono, dirección, valoración y
citas de reseñas) salen de la carta real del mesón, de su ficha de Google Maps y de
Tripadvisor. No hay texto ni platos inventados.

## Detalles técnicos

- Responsive a 360 / 768 / 1280 px, con menú desplegable en móvil.
- Indicador de **abierto / cerrado en vivo**, calculado sobre la hora de `Europe/Madrid`.
- JSON-LD `Restaurant` con dirección, teléfono, horario, rango de precios y valoración.
- Reveals con `IntersectionObserver`, respetando `prefers-reduced-motion`.
