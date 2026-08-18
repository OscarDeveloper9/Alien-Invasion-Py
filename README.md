# 👾 Alien Invasion

<img width="1362" height="762" alt="Inicio" src="https://github.com/user-attachments/assets/9fcbb569-2a8e-40de-bd26-91dc731a77be" />


Juego arcade estilo *Space Invaders* desarrollado en **Python** con la librería **Pygame**. Proyecto creado como práctica de programación orientada a objetos (POO), manejo de eventos, colisiones y estructura de proyectos en Python.

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)
![Pygame](https://img.shields.io/badge/Pygame-2.x-green?logo=pygame&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

## 🎮 Descripción

**Alien Invasion** es un juego arcade en el que controlás una nave espacial que debe defenderse de una flota de alienígenas que avanza en formación. El jugador dispara balas para destruir a los enemigos, suma puntos, sube de nivel y compite por el puntaje más alto.

El objetivo del proyecto fue aplicar conceptos fundamentales de desarrollo de software:

- Programación orientada a objetos (clases y herencia)
- Gestión de estados del juego (activo, pausa, game over)
- Detección de colisiones
- Manejo de eventos de teclado
- Persistencia del puntaje más alto (high score)
- Organización modular del código

---

## 📸 Capturas de pantalla

<p align="center">
  <img src="docs/screenshots/inicio.png" width="500" alt="Pantalla de inicio"><br>
  <em>Pantalla de inicio</em>
</p>

<p align="center">
  <img src="docs/screenshots/gameplay.png" width="500" alt="Partida en curso"><br>
  <em>Partida en curso</em>
</p>

---

## 🕹️ Cómo jugar

| Tecla | Acción |
|---|---|
| `←` `→` | Mover la nave |
| `Espacio` | Disparar |
| `P` | Pausar / Reanudar |
| `Q` | Salir |

---

## 📂 Estructura del proyecto

```
alien-invasion/
├── src/
│   ├── alien.py           # Clase Alien: comportamiento y renderizado de enemigos
│   ├── alien_invasion.py  # Clase principal: bucle del juego y lógica central
│   ├── bullet.py          # Clase Bullet: disparos del jugador
│   ├── button.py          # Botón de inicio (Play)
│   ├── game_stats.py       # Estadísticas del juego (vidas, nivel, puntaje)
│   ├── scoreboard.py       # Marcador en pantalla (score, nivel, high score)
│   ├── settings.py         # Configuración global (velocidad, colores, tamaños)
│   └── ship.py             # Clase Ship: la nave del jugador
├── assets/
│   └── images/              # Sprites e imágenes del juego
├── docs/
│   └── screenshots/          # Capturas para el README
├── requirements.txt
├── .gitignore
└── README.md
```

---

## ⚙️ Instalación

**Requisitos previos:** tener instalado [Python 3.10+](https://www.python.org/downloads/)

1. Cloná el repositorio:

```bash
git clone https://github.com/OscarDeveloper9/alien-invasion.git
cd alien-invasion
```

2. Creá un entorno virtual (recomendado):

```bash
python -m venv venv
venv\Scripts\activate      # Windows
source venv/bin/activate   # Mac/Linux
```

3. Instalá las dependencias:

```bash
pip install -r requirements.txt
```

4. Ejecutá el juego:

```bash
python src/alien_invasion.py
```

---

## 🧠 Qué aprendí con este proyecto

- Diseñar un juego completo aplicando **clases y herencia** en Python.
- Estructurar un proyecto de forma modular, separando responsabilidades por archivo.
- Manejar el **bucle principal de un juego** (game loop) y la actualización de estados en tiempo real.
- Implementar **detección de colisiones** entre balas, nave y alienígenas.
- Gestionar **niveles de dificultad progresivos** y persistencia del high score.
- Buenas prácticas de organización de repositorios para proyectos personales.

---

## 🚀 Posibles mejoras futuras

- [ ] Agregar sonido y música de fondo
- [ ] Sistema de power-ups
- [ ] Menú de configuración (dificultad, controles)
- [ ] Versión ejecutable (.exe) con PyInstaller
- [ ] Guardado de puntajes en archivo JSON o base de datos

---

## 👤 Autor

**Oscar** — Full Stack Developer en formación | Fisioterapeuta
- GitHub: [@OscarDeveloper9](https://github.com/OscarDeveloper9)
- LinkedIn: _agregá el link a tu perfil_

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Podés usarlo libremente con fines educativos.
