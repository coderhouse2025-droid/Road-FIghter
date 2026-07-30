<img width="1147" height="1372" alt="banner RF" src="https://github.com/user-attachments/assets/f1af2649-6cd7-4943-9399-1f13c17b650c" />

# 🏁 Road Fighter — Versión La Matanza

> 🐾 Un homenaje arcade al clásico **Road Fighter** (Konami, 1984), reversionado con identidad propia: **Isis**, una gata gris atigrada con el número **31**, corre en un Fórmula 1 rosa a través de cinco barrios del partido de **La Matanza, Buenos Aires**.

![Estado](https://img.shields.io/badge/estado-jugable-brightgreen)
![Plataforma](https://img.shields.io/badge/plataforma-navegador-blue)
![Tecnología](https://img.shields.io/badge/tech-HTML5%20%7C%20Canvas%20%7C%20JS-yellow)
![Licencia](https://img.shields.io/badge/licencia-MIT-lightgrey)

<img width="1688" height="1125" alt="image" src="https://github.com/user-attachments/assets/e66ae9cf-4878-4844-a089-30630c271e61" />

---

## 🎮 Sobre el juego

Subite en la butaca del Fórmula 1 rosa manejado por Isis y cruzá cinco barrios esquivando tráfico, motos y manchas de aceite. Juntá combustible para reparar la carrocería y llegá entera hasta Gregorio de Laferrere. Cada barrio sube la apuesta: más velocidad, más carriles cerrados y más tránsito.

El juego es un archivo **HTML único y autocontenido** (sin dependencias externas, sin instalación): todo el código, los gráficos, la música y los efectos de sonido están embebidos en `index.html`. Basta con abrirlo en un navegador para jugar.

## 🐱 Los cinco barrios

| # | Barrio | Dificultad |
|---|--------|:---:|
| 1️⃣ | Ramos Mejía | 🟢 |
| 2️⃣ | San Justo | 🟢🟡 |
| 3️⃣ | Lomas del Mirador | 🟡 |
| 4️⃣ | Isidro Casanova | 🟠 |
| 5️⃣ | Gregorio de Laferrere | 🔴 |

Cada tramo aumenta la velocidad base, reduce los carriles disponibles y acelera el consumo de combustible, exigiendo reflejos cada vez más finos.

## 🕹️ Controles

| Acción | Teclado | Pantalla táctil |
|---|---|---|
| ⬆️ Acelerar / ⬇️ Frenar | Flechas arriba / abajo | Botones en pantalla |
| ⬅️➡️ Cambiar de carril | Flechas izquierda / derecha | Botones en pantalla |

El juego detecta automáticamente dispositivos móviles y muestra controles táctiles superpuestos.

## ⚙️ Mecánicas principales

- 🐾 **3 vidas**: cada choque cuesta una vida; sin vidas, se acaba la carrera.
- ⛽ **Combustible**: se agota con la velocidad y la distancia recorrida; recolectá los tambores de combustible en la pista para reponerlo.
- 🐾**Huellas de gato**: el logo de las huellas de gato, la marca registrada de Isis repara los daños en la carrocería del auto.
- 🚌🏍️ **Tráfico variable**: colectivos, motos y manchas de aceite con patrones distintos por barrio.
- 🏆 **Puntuación y récord**: el mejor puntaje se guarda automáticamente en el navegador (`localStorage`) y persiste entre partidas.
- 🎉 **Final épico**: al completar los cinco barrios, Isis levanta la Copa Road Fighter con música de victoria y una pantalla de cierre animada.

## 🚀 Cómo jugar

No requiere instalación ni servidor:

1. Descargá o cloná este repositorio.
2. Abrí el archivo `index.html` con cualquier navegador moderno (Chrome, Firefox, Edge, Safari).
3. ¡A correr por La Matanza! 🏎️💨

```bash
git clone https://github.com/tu-usuario/road-fighter-la-matanza.git
cd road-fighter-la-matanza
# Abrí index.html directamente en el navegador
```

## 🧱 Tecnología

- **HTML5 Canvas** para el renderizado del juego (auto, tráfico, pista y HUD).
- **JavaScript vanilla**, sin frameworks ni librerías externas.
- **Web Audio API** para efectos de sonido y música sintetizados en tiempo real.
- Imágenes embebidas en **Base64** dentro del propio HTML: un solo archivo, cero dependencias.
- Diseño **responsive**, con soporte para escritorio y dispositivos móviles (controles táctiles).

## 📁 Estructura del repositorio

```
.
├── index.html   # Juego completo: HTML, CSS, JS, audio e imágenes embebidos
└── README.md    # Este archivo
```

## 🙌 Créditos

- 🎮 Inspirado en **Road Fighter** (Konami, 1984).
- 🐾 Protagonista y ambientación: creación original con identidad de **La Matanza, Buenos Aires**.

## 📄 Licencia

Este proyecto se distribuye bajo licencia [MIT](https://opensource.org/licenses/MIT). El nombre "Road Fighter" y la obra original pertenecen a Konami; este es un proyecto de fan sin fines comerciales.

---

<p align="center">Hecho con 🐾 y muchos <img width="512" height="512" alt="te-de-mate" src="https://github.com/user-attachments/assets/09cced83-5026-4718-b2f0-d4ef6b319aeb" />
 en La Matanza</p>
