# Lua Web IDE [BETA]

Un entorno de desarrollo interactivo (IDE) avanzado, ligero y moderno diseñado para escribir, autocompletar y compilar scripts de **Lua** directamente desde el navegador web. Desarrollado con el motor real de Visual Studio Code para ofrecer una experiencia de escritorio portátil.

---

## ✨ Características Principales

### 💎 Experiencia Visual Studio Code (Monaco Engine)
* **IntelliSense Nativo:** Burbuja flotante predictiva que autocompleta palabras clave (`local`, `function`, `print`) y variables creadas por ti al presionar `Enter` o `Tab`.
* **Cierres Automáticos:** Inserción inteligente de paréntesis, llaves y comillas de cierre de forma automática mientras escribes.
* **Maquetación Profesional:** Numeración de líneas a la izquierda, resaltado de línea actual y salto automático de línea (*word wrap*) optimizado para pantallas táctiles de celulares.

### 💻 Consola de Ejecución Real Dividida
* **Pestaña Terminal:** Atrapa y muestra los outputs reales de la función `print()` de tus scripts en vivo.
* **Pestaña Output:** Registra los reportes técnicos del compilador y marcas de tiempo del sistema de ejecución.
* **Fengari VM:** Incorpora una máquina virtual nativa de Lua corriendo al 100% sobre JavaScript para una ejecución instantánea sin servidores externos.

### 📱 Optimización Celular y PC
* Interfaz con esquema de colores **Dark Modern (Dracula Contrast)** de alta fidelidad que no fatiga la vista.
* Diseño responsivo que adapta el espacio del editor de código automáticamente al levantar el teclado táctil en teléfonos iOS y Android.
* Favicon personalizado integrado (Ícono de la **S Azul Marino**) visible en el historial y barra de navegación.

---

## 🛠️ Arquitectura Tecnológica

* **Editor Core:** Monaco Editor ESM (Microsoft Open Source Component).
* **Lua Runtime VM:** Fengari Web Core Lua Compiler.
* **Cargador de Módulos:** Asynchronous Blinded Loader (Estructura antirrecortes de URLs para despliegues de hosting estáticos).
* **Hosting / Despliegue:** GitHub Pages enlazado a dominio personalizado con cifrado HTTPS forzado.

---

## 📄 Licencia

Este ecosistema web de desarrollo se distribuye libremente bajo los términos y condiciones de la **Licencia Open Source MIT**. Puedes revisar el archivo `LICENSE` adjunto en la raíz para más información.

---

*Desarrollado con dedicación para la comunidad de programadores en Lua. 🦪*

