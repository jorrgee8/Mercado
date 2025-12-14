# Mini Mercado 3D

Este proyecto es una aplicación 3D interactiva hecha con **A-Frame** que representa una tienda, un almacén y un pequeño minijuego. Todo funciona directamente en el navegador web.

---

## Tecnologías usadas

- HTML5  
- JavaScript  
- A-Frame  

---

## Archivos del proyecto

- `index.html` → Pantalla principal para elegir la escena  
- `escena-360.html` → Escena de la tienda  
- `escena-proceso.html` → Escena del almacén  
- `escena-resultado.html` → Minijuego de recoger un producto  

---

## Funcionamiento

- El usuario se mueve con las teclas **WASD**.
- El movimiento está limitado para no atravesar paredes.
- Cada escena tiene **botones 3D** para ir a las otras escenas.
- El minijuego consiste en acercarse a un producto y pulsar **ESPACIO** para recogerlo.

---

## Nota importante

Durante el desarrollo se intentó usar **modelos 3D (GLTF)** y **sonido**, pero al hacerlo la escena mostraba una pantalla azul y dejaba de funcionar correctamente.

Por este motivo, se decidió no usar recursos externos y trabajar solo con:
- Geometrías básicas de A-Frame
- Iluminación y objetos simples

Esto garantiza que el proyecto funcione correctamente en el navegador.

---

## Ejecución

El proyecto puede ejecutarse directamente desde GitHub Pages accediendo al enlace del repositorio.

---

## Objetivo del proyecto

Practicar el uso de:
- Escenas 3D en la web
- Interacción básica
- Navegación entre escenas
- Organización y publicación de un proyecto web
