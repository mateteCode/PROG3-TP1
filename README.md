# 🎮 Entregable 1 - Programación de Videojuegos III
## Alumno: Matías Lorenzo
---

Este proyecto consiste en la transformación de una escena de un proyecto final para la materia Programación de Videojuegos II, cumpliendo con los requisitos solicitados y que se detallarán a continuación:

---

## 📑 Índice

1. [Iluminación: Baked, Mixed y Real-Time](#1-iluminación-baked-mixed-y-real-time)
2. [Punto de vista en Primera Persona](#2-punto-de-vista-en-primera-persona)
3. [Implementación de objetos con LOD](#3-implementación-de-objetos-con-lod)
4. [Animación en loop e interacción](#4-animación-en-loop-e-interacción)

---

## 1. Iluminación: Baked, Mixed y Real-Time

En esta escena se aplicaron distintas técnicas de iluminación según el tipo de objeto y su interacción con el jugador:

- **Baked Lighting** se utilizó para objetos estáticos como paredes y suelos, mejorando el rendimiento al precalcular la iluminación.
- **Mixed Lighting** se aplicó en objetos que están en contacto con fuentes de luz dinámicas pero que no se mueven.
- **Real-Time Lighting** fue usado para luces en objetos que reaccionan al jugador o que se encienden/apagan durante la ejecución del juego.

📸 *Ejemplo visual de iluminación combinada:*

![Iluminación Baked, Mixed y Real-Time](ruta/a/imagen1.png)

---

## 2. Punto de vista en Primera Persona

Se reemplazó la cámara en tercera persona por un controlador en **primera persona**, utilizando como base el *First Person Controller* (Asset sugerido). Esto cambia completamente la percepción del jugador y la forma de interactuar con el entorno.

📸 *Captura de vista en primera persona:*

![First Person View](ruta/a/imagen2.png)

---

## 3. Implementación de objetos con LOD

Se incorporaron objetos con **niveles de detalle (LOD)** para optimizar el rendimiento gráfico. Dependiendo de la distancia del jugador, los modelos cambian automáticamente su nivel de complejidad visual.

- LOD0: Detalle completo (cerca)
- LOD1: Menor detalle (media distancia)
- LOD2: Silueta simple (lejos)

📸 *Visualización de transiciones LOD:*

![Objetos con LOD](ruta/a/imagen3.png)

---

## 4. Animación en loop e interacción

Se animaron ciertos objetos de forma continua (loop) para dar vida al entorno (ej: ventiladores, lámparas colgantes). Además, se incluyó una animación alternativa que se activa mediante interacción con el jugador (por ejemplo, abrir una puerta al acercarse).

📸 *Animación en loop con interacción:*

![Animación en loop e interacción](ruta/a/imagen4.png)

---

## 💾 Recomendación

> Este TP fue desarrollado a partir de una **copia del proyecto en tercera persona**, siguiendo la sugerencia de no modificar la estructura del proyecto original. Se trabajó sobre una sola escena para cumplir con la consigna.

---

## 🚀 Créditos y herramientas

- Unity 6  
- Standard Assets - First Person Controller  
- LOD Group Component  
- Animator Controller + Triggers  
- Sistema de iluminación Unity (Baked + Mixed + Real-Time)

---

## 📌 Autor
*Matías Lorenzo*  
*Materia: Programación de Videojuegos III*  
*Profesor: Cristian Reynaga*  
*2025 1C*