# Squawk 🎵

¡Bienvenido a **Squawk**! Un reproductor de música local para Android diseñado desde cero para ofrecerte un control total sobre tu biblioteca musical, con una interfaz moderna, limpia e intuitiva.

## 🌟 Características Principales

* **Interfaz Moderna y Fluida**: Construida íntegramente con Jetpack Compose (Material 3), ofreciendo animaciones suaves, diseño responsivo y compatibilidad con el modo claro/oscuro del sistema.
* **Organización Total**: Navega por tu música a través de pestañas dedicadas:
  * Todas las canciones
  * Carpetas
  * Artistas
  * Álbumes
  * Géneros
  * Sentimientos (Moods)
  * Playlists personalizadas
* **Editor de Metadatos Integrado**: ¡Personaliza tu biblioteca! Mantén pulsada cualquier canción y selecciona "Editar" para modificar el título, artista, álbum, género, letras o la **portada del álbum**.
* **Sentimientos (Etiquetas Múltiples)**: Categoriza tu música según tu estado de ánimo. Al editar una canción, puedes añadir múltiples sentimientos separados por comas (Ej: `Feliz, Ejercicio, Lluvia`). La canción aparecerá automáticamente en las listas de todos esos sentimientos.
* **Aleatorio Inteligente (Smart Shuffle)**: ¿No sabes qué escuchar? Usa el Aleatorio Inteligente para mezclar de manera dinámica toda tu biblioteca ("Todas"), o limítalo a una Carpeta, Artista, Álbum, Género o Sentimiento específico.
* **Cola de Reproducción Interactiva**: Dentro del reproductor a pantalla completa, despliega la pestaña flotante de "Cola" para ver el orden exacto de las próximas canciones (incluso si están en aleatorio) y salta directamente a la que prefieras.
* **Lector de Letras (Lyrics)**: Añade letras sincronizadas o en texto plano a tus canciones desde el editor y disfrútalas en pantalla completa mientras se reproduce la música.
* **Navegación Inteligente (Smart Back)**: El botón "Atrás" de tu teléfono funciona de manera jerárquica: minimizará el reproductor, cancelará selecciones o volverá a la pantalla principal antes de salir (requiriendo un doble toque para evitar cierres accidentales).
* **Auto-Actualizador (GitHub Integrado)**: Squawk busca automáticamente nuevas versiones de la aplicación desde GitHub al iniciarse. Si hay una nueva versión disponible, te mostrará un botón permanente en la pantalla principal para descargar e instalar el nuevo APK con un solo toque.

## 🚀 Instalación y Uso

1. Descarga la última versión (`Sqwak.apk`) desde la sección de **Releases**.
2. Instala el APK en tu dispositivo Android (requiere Android 7.0 / API 24 o superior).
3. Concede los permisos de lectura de almacenamiento para que Squawk escanee tus archivos locales.
4. ¡Disfruta de tu música!


## 🛠️ Tecnologías

- **Kotlin** & **Jetpack Compose**
- **Media3 (ExoPlayer)** para el motor de audio y servicios en segundo plano.
- **Room Database** para almacenar metadatos personalizados y listas de reproducción locales.
- **Coil** para la carga asíncrona de portadas.
- **OkHttp / Kotlinx Serialization** para el actualizador integrado con la API de GitHub.
