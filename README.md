# Ejercicio-cookies

Este proyecto es un ejercicio práctico de desarrollo web front-end que implementa un banner de consentimiento de cookies interactivo y un menú flotante de contacto con enlaces a diferentes redes sociales.

## 🚀 Características

* **Banner de Cookies Interactivo:** Un modal estilizado que informa al usuario sobre el uso de cookies en el sitio. Cuenta con opciones para "Solo Necesarias", "Personalizar" y "Aceptar Todas".
* **Lógica en JavaScript:** Al hacer clic en el botón principal ("Accept All Cookies"), un script sencillo de JavaScript oculta automáticamente el banner para mejorar la experiencia de usuario.
* **Menú Flotante de Contacto:** Incluye un botón fijo en la esquina inferior derecha. Al pasar el cursor por encima (efecto *hover*), se despliegan de forma animada varios íconos de contacto (Facebook, TikTok, WhatsApp y chat).
* **Estilos Modernos:** Uso de Flexbox para la maquetación, fondos con gradientes de color (`linear-gradient`) y transiciones suaves (`transition: all 1s ease`) para las interacciones.

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura de la página y los elementos del DOM.
* **CSS3:** Estilización, maquetación y animaciones hover.
* **JavaScript (Vanilla):** Manipulación básica del DOM para la interactividad del banner.
* **Font Awesome (v6.0.0):** Librería externa utilizada para la iconografía del menú de contacto y redes sociales.

## 📂 Estructura del Proyecto

El proyecto tiene la siguiente estructura de archivos:

```text
ejercicio-cookies/
│
├── css/
│   └── styles.css       # Hoja de estilos principal
├── images/
│   └── cookie.svg       # Ícono de galleta para el banner
├── index.html           # Estructura principal y script JS
└── README.md            # Documentación del proyecto
