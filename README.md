# Páramo Omega · Travesía (scrollytelling)

Versión de **narrativa por scroll** de la experiencia *Páramo Omega*, inspirada en la mecánica de navegación de *The Boat* (SBS) — **no en su arte ni su código**, que son obra con derechos de SBS/Matt Huynh. Aquí se replica solo el **lenguaje de interacción**: entrada con gesto, la historia avanza al desplazarse, atmósfera inmersiva, audio ambiental por capítulo y controles discretos.

## Ambientación
Desierto + páramo superviviente: paleta cálida/árida (arena, óxido, ámbar, verde seco de frailejón). Atmósfera de **polvo y calor** (sin lluvia).

## Cómo funciona
- **Entrada**: "Pulsa para comenzar" (desbloquea el audio) → se reproduce `Intro.mp4` con sonido → fluye a la narrativa por scroll.
- **Scroll narrativo**: 8 capítulos a pantalla completa con parallax de las imágenes, texto que entra en secuencia y **audio ambiental que cruza-funde por capítulo**.
- **Controles**: SONIDO (silencia/activa), AUTO-SCROLL (avance lento que se detiene al interactuar), PANTALLA COMPLETA; indicador de capítulos (puntos) y barra de progreso.
- **Vigilia final**: el minijuego **"Guardián del Acuífero"** (arcade retro: recoge agua limpia, esquiva la ácida, gota dorada bonus, filtro-escudo, combo y niveles).
- Respeta `prefers-reduced-motion` (sin parallax/polvo; documento vertical legible) y funciona en móvil (scroll táctil).

## Medios (en la raíz del repo)
`Intro.mp4`, `Lamento de Piedra_2.mp3` (hub), `Tinta de Sal_2.mp3` (Refugio), `Binary Waltz_2.mp3` (Lyra), `Synthetic Waltz_2.mp3` (Cronos), `Cota Catorce_2.mp3` (equilibrio/finale).

## Publicación
Sitio estático; se sirve con GitHub Pages desde la rama `main` (carpeta raíz):
**https://zagrek-667.github.io/Paramo_scrollytelling/**

Créditos: Historia *Andronak Zagreirus* · Bogotá, Colombia · 2026 · Universidad Distrital Francisco José de Caldas · Facultad de Educación.
