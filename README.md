# Playtime Co. · Fábrica de Mates

Un juego educativo interactivo de matemáticas diseñado para alumnos de **2º de Primaria (7-8 años)**, ambientado de manera inocente e ilustrativa en la temática de *Poppy Playtime*.

---

## 🎮 Descripción del Juego

**Fábrica de Mates** ayuda a los estudiantes a practicar y dominar operaciones de suma y resta con llevadas/préstamos mediante minijuegos progresivos y visuales.

### 🌟 Características Principales

- **Soporte Visual de Llevadas:** Operaciones presentadas en formato vertical tradicional (centenas, decenas y unidades) con casillas superiores interactivas para anotar las llevadas o préstamos.
- **Sistema de Perfiles:** Permite crear y gestionar múltiples jugadores con nombre y avatar personalizado.
- **Niveles Progresivos:** 5 subniveles de dificultad creciente por cada modo de juego.
- **Sistema de Recompensas:** Ganancia de Monedas Playtime y Estrellas (★) al resolver ejercicios.
- **Tienda Playtime:** Desbloqueo de accesorios para el GrabPack (manos doradas, guantes de neón) y pegatinas de personajes (Huggy Wuggy, Kissy Missy, Poppy, Mommy Long Legs).
- **PWA (Progressive Web App):** Funciona sin conexión gracias al Service Worker y manifest configurados.

---

## 🕹️ Modos de Juego

1. **Nivel 1: El GrabPack de las Sumas (Reparación de Puertas)**
   - **Mecánica:** Sumas verticales con llevada de 2 y 3 cifras. El jugador pulsa el cable o botón con el resultado correcto usando el GrabPack.
   - **Objetivo:** Resolver sumas correctamente para restaurar la energía de la fábrica.

2. **Nivel 2: La Cinta Transportadora de Restas (Escape de Huggy)**
   - **Mecánica:** Restas verticales con préstamos. Las respuestas se mueven en cajas a través de una cinta transportadora.
   - **Objetivo:** Seleccionar la caja correcta antes de que llegue al final de la cinta.

3. **Nivel 3: El Puzle Final de Poppy (Operaciones Combinadas)**
   - **Mecánica:** Combinación de sumas y restas, incluyendo operaciones con término faltante (número escondido `?`).
   - **Objetivo:** Resolver los puzles para abrir el candado final y liberar a Poppy.

---

## 🛠️ Estructura del Proyecto

```text
fabrica-de-mates/
├── index.html                       # Aplicación principal Web (HTML5, CSS3, JavaScript)
├── Playtime-fabrica-de-mates.html   # Copia/fichero fuente del juego
├── manifest.json                    # Manifiesto Web App para PWA
├── sw.js                            # Service Worker para soporte offline
├── prompt.md                        # Especificaciones y prompt original de diseño
└── README.md                        # Documentación del proyecto
```

---

## 🚀 Cómo Ejecutar el Proyecto

1. Clona o descarga este repositorio.
2. Abre el archivo `index.html` en cualquier navegador web moderno (Chrome, Firefox, Edge, Safari).
3. ¡Comienza a jugar! No requiere instalación ni servidor backend.

---

## 🧰 Tecnologías Utilizadas

- **HTML5 & CSS3:** Diseño responsive adaptable a móviles, tablets y ordenadores con variables CSS y Flexbox/Grid.
- **JavaScript (ES6+):** Lógica del juego, generación dinámica de ejercicios y persistencia de datos en `localStorage`.
- **Web App Manifest & Service Worker:** Soporte PWA para instalación como aplicación web nativa y uso offline.
- **Google Fonts:** Tipografía *Baloo 2* para una experiencia visual infantil y legible.
