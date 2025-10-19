# clima-html-recurso
Una pequeña y elegante tarjeta con información del clima que muestra la temperatura actual, la ciudad y la fecha. Ideal para incluir en proyectos web como recurso reutilizable.

## Características

*   **Diseño moderno:** Tarjeta con fondo semitransparente, borde sutil y sombra para dar profundidad.
*   **Responsiva:** Se adapta bien a diferentes tamaños de pantalla.
*   **Interactiva:** Suaviza el efecto al pasar el mouse sobre la tarjeta.
*   **Datos de clima:** Muestra la temperatura, ciudad y fecha actual.
*   **Iconos:** Utiliza iconos de [Lucide](https://lucide.dev/) para representar condiciones climáticas.
*   **Ubicación automática:** Detecta la ubicación del usuario mediante su IP (fallback a Buenos Aires).
*   **Modo mock:** Funciona sin clave API de OpenWeatherMap, mostrando datos simulados.
*   **Fácil de usar:** Código limpio y comentado para facilitar su modificación.

## Cómo usar

1.  **Clonar o descargar:** Descarga este repositorio o copia el código HTML.
2.  **Personalización:**
    *   **API Key (opcional):** Si deseas datos reales del clima:
        *   Regístrate en [OpenWeatherMap](https://openweathermap.org/api).
        *   Obtén tu clave gratuita.
        *   Reemplaza el valor vacío de `OPENWEATHER_API_KEY` en el script con tu clave real.
    *   **Estilos:** Puedes modificar los colores, fuentes, tamaños y efectos directamente en el CSS (`<style>`).
    *   **Iconos:** El código usa emojis para representar condiciones climáticas. Puedes cambiar el mapeo en la función `iconFromKeyword`.
    *   **Fallback de ubicación:** Actualmente, si la detección por IP falla, se usa Buenos Aires. Puedes cambiar el objeto de fallback en `getLocationByIP`.
3.  **Incluir en tu proyecto:** Pega el código HTML en tu página web o intégralo como parte de tu estructura.

## Estructura del Proyecto
weather-capsule/
├── index.html     # Archivo principal con el código completo
└── README.md      # Este archivo


## Tecnologías Utilizadas

*   **HTML5:** Estructura básica.
*   **CSS3:** Estilos y animaciones.
*   **JavaScript (ES6+):** Lógica para obtener datos y manipular el DOM.
*   **[Lucide Icons](https://lucide.dev/):** Iconografía utilizada en el diseño.
*   **[OpenWeatherMap API](https://openweathermap.org/api):** Fuente de datos climáticos (opcional).
*   **[ipapi.co](https://ipapi.co/):** Servicio para detectar ubicación por IP.

## Autor

Facundo Gonzalez

*   Especialista en sucesiones, usucapión y juicios de escrituración.
*   Ofrece servicios comerciales de videos de drones.
*   Elabora cerveza artesanal bajo la marca 'Gualicho'.

*(Este proyecto refleja su interés en crear herramientas útiles y estéticas para su práctica profesional y otros intereses).*


## Licencia

Este proyecto es de uso libre y puede ser modificado y distribuido según tus necesidades. No se otorga ninguna garantía. El uso de servicios externos como OpenWeatherMap y ipapi.co está sujeto a sus respectivas licencias y términos de servicio.
