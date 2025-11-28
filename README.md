# FuturoRioja Argentina 2026

Sitio web oficial para la conferencia de desarrollo web "FuturoRioja" en La Rioja, Argentina.

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera para mantener un código limpio y profesional:

- **index.html**: Archivo principal del sitio. Contiene la estructura HTML.
- **css/**: Contiene los archivos de estilos.
  - `styles.css`: Estilos personalizados y animaciones.
- **js/**: Contiene la lógica y configuración de JavaScript.
  - `main.js`: Lógica principal (menú móvil, cuenta regresiva).
  - `tailwind-config.js`: Configuración personalizada para Tailwind CSS.
- **assets/**: Carpeta destinada a imágenes y otros recursos estáticos (actualmente las imágenes se cargan desde URLs externas).

## Tecnologías

- **HTML5**: Semántico y accesible.
- **Tailwind CSS**: Framework de utilidades para el diseño.
- **JavaScript (Vanilla)**: Para la interactividad sin dependencias pesadas.
- **Font Awesome**: Para los iconos.

## Cómo ejecutar

### Opción 1: Directa
Simplemente abre el archivo `index.html` en tu navegador web favorito.

### Opción 2: Servidor Local (Recomendado)
Para una mejor experiencia (y evitar problemas de CORS con algunos recursos), se recomienda usar un servidor local.

Si tienes Python instalado:
```bash
python3 -m http.server 8080
```
Luego abre [http://localhost:8080](http://localhost:8080) en tu navegador.

También puedes usar la extensión "Live Server" en VS Code.
