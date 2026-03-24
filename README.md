# 📘 Barra de Accesibilidad para Web

Esta es una barra de accesibilidad flotante y arrastrable para sitios web. Permite a los usuarios ajustar el zoom, el contraste, invertir colores y aumentar el tamaño de fuente, mejorando la experiencia para personas con dificultades visuales.

## ⚡ Características

- Barra horizontal y flotante, visible en toda la página.
- Arrastrable (Drag & Drop) para colocarla en cualquier posición de la pantalla.
- Funcionalidades incluidas:
  - 🔍 Zoom In
  - 🔎 Zoom Out
  - 🧙‍♂️ Invertir colores
  - ⚫ Contraste alto
  - Aumentar fuente
  - ↺ Reset para volver a la configuración original
- Compatible con cualquier estructura de página HTML sencilla.
- Fácil de integrar: solo necesitas incluir el archivo JS y CSS.

## 🛠️ Instalación

1. Clona o descarga este repositorio.
2. Incluye los archivos en tu proyecto, por ejemplo:

```html
<link rel="stylesheet" href="https://github.com/Vito-Pulls/panel-accesibilidad/raw/main/estilo.css">
<script src="https://github.com/Vito-Pulls/panel-accesibilidad/raw/main/jocarsa-accesibilidad.js"
```

La barra se añadirá automáticamente al cargar la página (`window.onload`).

## 🖌️ Uso

- La barra se muestra por defecto en la parte superior derecha. Puedes:
  - Hacer clic en los iconos para activar las funciones.
  - Arrastrar la barra a cualquier parte de la pantalla manteniendo pulsado el cursor.
  - Resetear todas las modificaciones con el botón ↺.

## 📂 Estructura del proyecto

/proyecto-accesibilidad
│
├─ index.html # Página principal
├─ jocarsa-accesibilidad.js # Lógica de la barra de accesibilidad
├─ assets/
│ └─ css/
│ └─ estilo.css # Estilos de la página y barra

## 🔧 Personalización

- **Posición inicial:** Puedes cambiar la posición modificando el CSS `.jocarsa-accesibilidad` (top, right, left).
- **Colores y tamaño:** Ajusta `background`, `border-radius`, `padding`, `font-size` en CSS.
- **Funciones adicionales:** Se pueden añadir más botones con nuevas funcionalidades siguiendo el patrón del JS.

## 🌐 Compatibilidad

- Navegadores modernos: Chrome, Firefox, Edge, Safari
- Desktop y dispositivos táctiles (aunque el drag & drop puede necesitar ajustes para móviles)

## 📜 Licencia

MIT License – libre para uso y modificación.

```

```
