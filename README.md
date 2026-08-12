# 🌎 Maestro de Banderas - Juego de Banderas del Mundo 

![Vista Previa del Juego](./Preview.png)

**Maestro de Banderas** es un juego interactivo de geografía web desarrollado con HTML5, CSS3 y JavaScript Vanilla. Pon a prueba tus conocimientos adivinando las banderas de diferentes continentes o del mundo entero, con sistema de tiempos, mejores récords personales y tolerancia inteligente a la escritura.

---

## 🚀 Características Principales

- **🌎 Modos por Continente y Mundo:**
  - 🌎 **América** (35 banderas)
  - 🌍 **Europa** (46 banderas)
  - 🌏 **Asia** (49 banderas)
  - 🌍 **África** (54 banderas)
  - 🌏 **Oceanía** (14 banderas)
  - 🎲 **Mundo** (50 banderas seleccionadas aleatoriamente)
- **⚡ 100% Offline:** Carga las imágenes localmente desde la carpeta `banderas/`, sin depender de APIs externas ni conexión a internet.
- **🔤 Entrada Inteligente de Texto:**
  - **Insensible a acentos y mayúsculas:** Puedes escribir `méxico`, `Mexico` o `MEXICO` y será reconocido como correcto.
  - **Múltiples respuestas válidas:** Reconoce sinónimos, nombres cortos y siglas populares (ej: *EEUU*, *USA*, *Estados Unidos*; *Holanda*, *Países Bajos*; *Gran Bretaña*, *Reino Unido*).
- **⏱️ Sistema de Récords y Cronómetro:**
  - Cronometra el tiempo total de tu partida.
  - Guarda tu **mejor tiempo** por continente en `localStorage`.
  - *Condición de récord:* Solo se guarda un nuevo récord si logras el 100% de aciertos a la primera.
- **🎨 Interfaz Moderna en Modo Oscuro:**
  - Diseño limpio, centrado y adaptado para dispositivos móviles y de escritorio.
  - Animación visual de sacudida (*shake effect*) al cometer un error.
- **💡 Opción "No me la sé":** Muestra el nombre correcto del país para aprenderlo y continuar el juego.
- **🗑️ Gestión de Récords:** Permite borrar y reiniciar tus tiempos guardados cuando lo desees.

---

## 📁 Estructura del Repositorio

```text
FlagsGame/
│
├── banderas/            # Carpeta local con las banderas en formato .png por código de país
├── index.html           # Código principal del juego (HTML, CSS y JavaScript integrados)
├── Preview.png          # Imagen de vista previa utilizada en este README
└── README.md            # Documentación del proyecto
