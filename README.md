# Raid · Angel & Maicol

Calculadora de raid de Rust para raidear en dúo. Añades lo que hay entre vosotros y el loot y te dice qué explosivos usar, cuánto azufre hay que farmear y qué lleva cada uno: Angel los explosivos y Maicol las balas explosivas con el rifle.

**Abrir la app:** https://crr4zzy.github.io/raid-angel-maicol/

## Instalarla en el iPhone

1. Abre el enlace en **Safari**.
2. Pulsa **Compartir** y luego **Añadir a pantalla de inicio**.
3. Ábrela desde el icono. Funciona también sin cobertura y se actualiza sola cuando hay internet.

## Qué hace

- **Objetivos:** muros, suelos, puertas, ventanas, externos y defensas, con filtro por categoría y buscador (sin importar tildes). En cada pieza puedes indicar si la rompéis **desde dentro** y cuánta **vida le queda**.
- **Modos:** el más barato en azufre (combina C4, satchels, balas y lo que tengáis), o solo C4, cohetes, satchels, balas o granadas 40mm.
- **Inventario:** lo que ya tenéis se gasta primero y solo pide craftear el resto.
- **Plan:** qué lleva cada uno con margen (satchels +25 %, balas y 40mm +10 %, cohetes +1 cada 10, C4 sin margen), materiales para craftear repartidos entre Angel y Maicol, y el desglose pieza por pieza.
- **En directo:** durante el raid vais tachando cada pieza y os dice qué explosivos os quedan.
- **Raids guardados:** varios raids con nombre (la base del vecino, la vuestra...).
- **Compartir:** manda el plan y un enlace que abre la app con el mismo raid cargado.
- **Deshacer** al vaciar, cargar una base de ejemplo o borrar un raid.

## Datos

- Vida, protecciones y daño de cada explosivo: [GameServerKings](https://www.gameserverkings.com/knowledge-base/rust/rust-raid-chart/), sacados de los archivos del servidor de Rust (septiembre de 2026).
- Tronera vertical, barricada metálica, torreta y aerogenerador: recuentos publicados por Supercraft.
- Recetas y azufre por explosivo: C4 2.200, cohete 1.400, satchel 480, bala explosiva 25, granada 40mm 85.
- Las piezas sin cifras fiables (ventana blindada, escaparates, SAM, bancos de trabajo...) aparecen aparte y no suman.

Los valores son del Rust vanilla y pueden cambiar un poco con cada parche mensual.

## Archivos

- `index.html`: toda la app (HTML, CSS y JavaScript en un solo archivo).
- `sw.js`: guarda la app para usarla sin conexión.
- `manifest.json` e `icon.png`: icono y nombre al instalarla.
