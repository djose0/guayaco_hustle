# 🏃‍♂️ GUAYACO HUSTLE: La Bahía Edition

> *"Plata o plomo? No, aquí es: Corre o te cae el tolete."*

# [🔴 >> HAZ CLICK AQUÍ PARA JUGAR AHORA << 🔴](https://djose0.github.io/guayaco_hustle/)

---

![Game Banner](https://via.placeholder.com/1200x400.png?text=GUAYACO+HUSTLE:+VOXEL+CHAOS)
*(Una experiencia de supervivencia urbana en Three.js)*

**Guayaco Hustle** es un *Endless Runner* de alta fidelidad desarrollado en un solo archivo con **Three.js**. Ambientado en el caótico corazón comercial de Guayaquil, Ecuador ("La Bahía"), el juego simula la adrenalina de una huida perpetua tras un "arranche" fallido.

## 🎮 De qué va esto

Empiezas robando un celular (mala idea) y la ciudad se vuelve tu enemiga. Tienes que esquivar Taxis que no respetan carriles, buses de la Metrovía y letreros publicitarios que te decapitarán si no te agachas.

Todo esto envuelto en una estética **Voxel Art** pulida, con iluminación dinámica de atardecer húmedo, niebla volumétrica y una economía interna inflacionaria.

## ✨ Características Técnicas

* **Motor Gráfico Puro:** Construido 100% en un solo archivo HTML (`index.html`). Sin dependencias complejas (`npm`), sin assets externos (ni imágenes ni mp3). Todo es geometría y audio generado por código.
* **Estética Voxel High-End:**
    * Iluminación ambiental (`HemisphereLight`) y sombras suaves (`PCFSoftShadowMap`).
    * Materiales `MeshStandardMaterial` que reaccionan a la luz del atardecer.
    * Sistema de partículas para impacto, monedas y polvo.
* **Narrativa Cinemática:**
    * **Intro:** Secuencia de robo con cámara dolly y animación de personajes.
    * **Game Over:** Secuencia de arresto detallada con animación de golpe (tolete) y traslado del detenido.
* **Economía "La Cachina":**
    * Sistema de tienda persistente (`localStorage`).
    * 5 Skins desbloqueables con modelos voxel únicos (El Brayan, UArtes, El Aniñado, El Ídolo, Alien).
* **Gameplay Dinámico:**
    * Curva de velocidad infinita.
    * Patrones de tráfico inteligentes (Embudo, Bloqueo Simple, Carril Seguro con monedas).

## 🕹️ Controles

| Acción | Teclado (PC) | Móvil (Touch) |
| :--- | :---: | :---: |
| **Moverse** | Flechas ⬅️ / ➡️ | Swipe Izquierda / Derecha |
| **Saltar** | Flecha ⬆️ | Swipe Arriba |
| **Agacharse** | Flecha ⬇️ | Swipe Abajo |

> **Nota:** Si ves un letrero alto, AGÁCHATE. Si ves una valla baja, SALTA. Si ves un Metropolitano... bueno, ya es tarde.

## 👽 Skins Disponibles

1.  **El Brayan (Default):** Camiseta azul eléctrica y gorra para atrás. Aerodinámico.
2.  **UArtes ($1,500):** Outfit *all-black*, lentes y tote bag. Corre con angustia existencial.
3.  **El Aniñado ($5,000):** Polo rosada y suéter en los hombros. No corre, se *desplaza*.
4.  **El Ídolo ($8,000):** La amarilla puesta. Ídolo del astillero.
5.  **Alien ($50,000):** Directamente del Área 51 a la Bahía. Piel emisiva.

## 📦 Instalación Local

Este proyecto es la definición de "Plug & Play".

1.  **Clona el repositorio:**
    ```bash
    git clone [https://github.com/djose0/guayaco_hustle.git](https://github.com/djose0/guayaco_hustle.git)
    ```
2.  **Ejecuta el juego:**
    * Simplemente abre el archivo `index.html` en cualquier navegador moderno.

---

<p align="center">
  Hecho con 💔, JavaScript y mucha humedad en Guayaquil.
  <br>
  <b>Larsen & ADNO Creative Labs</b>
</p>
