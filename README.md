# 🎮 Entregable 1 - Programación de Videojuegos III
## Alumno: Matías Lorenzo
---
Todos los archivos que se utilizaron en blender y unity se encuntran dentro de la carpeta Assets/TP1, salvo excepción que se comentará luego.
Este proyecto consiste en la transformación de una escena de una entrega anterior, cumpliendo con los requisitos solicitados y que se detallarán a continuación:

---

## 📑 Índice

1. [Iluminación](#1-iluminación)
2. [Punto de vista en Primera Persona](#2-punto-de-vista-en-primera-persona)
3. [Implementación de objetos con LOD](#3-implementación-de-objetos-con-lod)
4. [Animación en loop e interacción](#4-animación-en-loop-e-interacción)

---

## 1. Iluminación:

La mayoría de los faroles de pared se configuraron como Baked, ya que son luces fijas. En cambio, se eligió uno en particular para tener un efecto de parpadeo aleatorio, tanto en intensidad como en duración, mediante un script, y ese se configuró como Mixed.

📸 *Capturas de luces*

![Iluminación](https://raw.githubusercontent.com/mateteCode/PROG3-TP1/refs/heads/main/Assets/TP1/Capturas/iluminacion.gif)

---

## 2. Punto de vista en Primera Persona

Para pasar a primera persona, se tuvo que agregar una camara cercana a su cara, modificar código original del PlayerController.cs para controlar el movimiento de la camara con el mouse, adaptarse el collider para que no atravesa paredes y columnas.

📸 *Captura de vista en primera persona:*

![Vista Primera Persona](https://raw.githubusercontent.com/mateteCode/PROG3-TP1/refs/heads/main/Assets/TP1/Capturas/player1.jpg)
![Vista Primera Persona](https://raw.githubusercontent.com/mateteCode/PROG3-TP1/refs/heads/main/Assets/TP1/Capturas/player2.jpg)

---

## 3. Implementación de objetos con LOD

Se incorporaron dos objetos con **niveles de detalle (LOD)** para optimizar el rendimiento gráfico Se encuentran dentro de "/Assets/TP1/Modelos LOD". Dependiendo de la distancia del jugador, los modelos cambian automáticamente su nivel de complejidad visual. Se remplazaron esos mismos objetos en todo el nivel.

- LOD0: Detalle completo (cerca)
- LOD1: Menor detalle (media distancia)
- LOD2: Silueta simple (lejos)

📸 *Visualización de transiciones LOD:*

![Objetos con LOD](https://raw.githubusercontent.com/mateteCode/PROG3-TP1/refs/heads/main/Assets/TP1/Capturas/obj1lod0.jpg)
![Objetos con LOD](https://raw.githubusercontent.com/mateteCode/PROG3-TP1/refs/heads/main/Assets/TP1/Capturas/obj1lod1.jpg)
![Objetos con LOD](https://raw.githubusercontent.com/mateteCode/PROG3-TP1/refs/heads/main/Assets/TP1/Capturas/obj1lod2.jpg)
![Objetos con LOD](https://raw.githubusercontent.com/mateteCode/PROG3-TP1/refs/heads/main/Assets/TP1/Capturas/obj2lod0.jpg)
![Objetos con LOD](https://raw.githubusercontent.com/mateteCode/PROG3-TP1/refs/heads/main/Assets/TP1/Capturas/obj2lod1.jpg)
![Objetos con LOD](https://raw.githubusercontent.com/mateteCode/PROG3-TP1/refs/heads/main/Assets/TP1/Capturas/obj2lod2.jpg)


---

## 4. Animación en loop e interacción

Se animaron dos objetos en blender para dar vida al entorno: una llave con un loop de moviendose necesaria para abrir una puerta (que también tiene una animación de abrirse). Se encuentran en "/Assets/TP1/Modelos Animados"

📸 *Animación en loop con interacción:*

![Animación e interacción](https://raw.githubusercontent.com/mateteCode/PROG3-TP1/refs/heads/main/Assets/TP1/Capturas/door1.jpg)
![Animación e interacción](https://raw.githubusercontent.com/mateteCode/PROG3-TP1/refs/heads/main/Assets/TP1/Capturas/door2.jpg)
![Animación e interacción](https://raw.githubusercontent.com/mateteCode/PROG3-TP1/refs/heads/main/Assets/TP1/Capturas/door3.jpg)

---

## 📌 Autor
*Matías Lorenzo*  
*Materia: Programación de Videojuegos III*  
*Profesor: Cristian Reynaga*  
*2025 1C*