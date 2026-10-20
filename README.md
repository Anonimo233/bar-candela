# 🍷 Bar Candela — Web App de Hostelería & Reservas

Aplicación web progresiva de archivo único (*Single-File Web Application*) diseñada para **Bar Candela**, una vermutería y taberna tradicional. Incluye carta interactiva estilo pizarra, cálculo de horarios en tiempo real (con soporte para cierres de madrugada), sistema de reservas inteligente y panel de administración con criptografía en cliente.

🔗 **Demo en vivo:** [https://anonimo233.github.io/bar-candela/](https://anonimo233.github.io/bar-candela/)

---

## ✨ Características principales

* **🎨 Diseño Temático en CSS Puro:** Textura de pared de azulejos generada con gradientes CSS (0 imágenes externas, carga instantánea) y pizarra tradicional con soporte automático para **Modo Claro / Oscuro** (`prefers-color-scheme`).
* **🕒 Estado de Apertura en Tiempo Real:** Algoritmo que detecta automáticamente el día de la semana y la hora actual (incluyendo cierres posteriores a la medianoche) para indicar si el local está abierto o cuándo vuelve a abrir.
* **📅 Reservas con Filtro Inteligente:** Bloquea automáticamente los días de descanso del local y genera turnos de 30 minutos adaptados al horario de apertura del día seleccionado.
* **📲 Notificación Multicanal:** Envío automático de solicitudes en segundo plano al correo del propietario (`fetch` AJAX) y generación de enlaces directos a **WhatsApp** (`wa.me`).
* **🔐 Panel de Propietario Autónomo:** Autenticación mediante `Web Crypto API` (**PBKDF2** con 200.000 iteraciones y SHA-256) con bloqueo progresivo anti-fuerza bruta y generador integrado que exporta el nuevo `index.html` listo para producción al editar platos, precios u horarios.

## 🛠️ Tecnologías utilizadas

* **HTML5 Semántico** (`<dialog>`, atributos ARIA, metadatos Open Graph y Favicon SVG embebido).
* **CSS3 Moderno** (Custom Properties, CSS Grid, Flexbox, `clamp()`, `backdrop-filter`).
* **JavaScript ES6+ Vanilla** (Sin dependencias ni frameworks externos).

---
Desarrollado por **Alessandro Tineo** · Contacto: [tineoalessandro9@gmail.com](mailto:tineoalessandro9@gmail.com)
