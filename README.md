# 🎮 Juegos Samuel Digital

Juegos y actividades de Informática para la primaria, creados por **Samuel Tocaimaza** (Samuel Digital) para usar en el aula y en casa.

🌐 **https://juegos.samueldigital.com.ar**

## Actividades por grado

Paso a paso de proyectos de ScratchJr y Scratch, con los bloques dibujados en español:

| Grado | Actividades |
|---|---|
| 2° | El gato va a buscar la manzana (ScratchJr) |
| 3° | Primeros pasos en Scratch |
| 4°, 5° y 6° | El gato y la manzana: nivel 2 · **El penal ⚽** |

Cada grado del mismo proyecto suma algo nuevo: 4° variables y si/si no, 5° velocidad y dos finales, 6° números al azar y tres finales.

Funcionan en cualquier navegador, sin instalar nada, sin cuentas y sin sonido (pensados para salas de informática sin parlantes).

## Juegos

| Juego | Qué se aprende | Grados |
|---|---|---|
| ⚽ Penales Mundialistas | Apuntar, medir la fuerza, contar goles, saber ganar y perder | Todos |
| 🌳 Laberinto | Orientación espacial, izquierda/derecha, secuencias de pasos | 1° y 2° |
| 🎨 Pintá Píxeles | Píxeles, cuadrícula, colores, copiar un modelo | 1° y 2° |
| ✏️ Boceto Libre | Expresión con el dibujo, manejo del mouse | 1° |
| 🃏 Memotest | Memoria, atención, igual y diferente | 1° y 2° |
| 🎈 Globos para Contar | Números, cantidades, contar | 1° |
| 🧺 Atrapá la Letra | Letras, vocales, mayúsculas y minúsculas | 1° y 2° |
| 🤖 Vestí al Robotito | Arrastrar y soltar, partes del cuerpo | 1° |
| 🧩 Rompecabezas | Observación, partes y todo, arrastrar | 1° y 2° |
| 🔁 Seguí la Secuencia | Patrones de colores y figuras | 1° y 2° |

Cada juego tiene:

- **El robotito**, la mascota, que explica cómo jugar con pictogramas (para chicos que todavía no leen).
- **📘 ¿Qué aprendemos?**: un panel para chicos y familias con lo que se aprende, palabras nuevas, un dato curioso, preguntas para charlar y un juego para hacer en casa.

## Cómo está hecho

HTML, CSS y JavaScript puro, un archivo por juego. No necesita compilación: se publica tal cual en cualquier hosting estático (Vercel, GitHub Pages, Netlify).

```
index.html            → portada con actividades y juegos
actividades/          → actividades por grado (grado-N.html y cada paso a paso)
actividades/img/      → capturas, ilustraciones y bloques de Scratch
<juego>.html          → cada juego
favicon.svg           → ícono del sitio
```

Para probarlo en la compu, alcanza con abrir `index.html` en el navegador.

---

Hecho con 💛 por Samuel Digital.
