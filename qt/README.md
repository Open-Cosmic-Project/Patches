# Parches y Configuración de Qt6 / Qt WebEngine para CosmicOS

## Alcance (Secciones 9.1, 9.2 y 11 de CosmicOS Spec v0.2.5)

- **Podado por configuración:** exclusión de backends X11, Broadway, VNC y plataformas heredadas para minimizar superficie de código.
- **WebView del sistema (Etapa 1):** empaquetado centralizado de Qt WebEngine como componente inmutable del sistema base, evitando duplicación de navegadores embebidos por aplicación.
- **Integración Wayland:** adaptación completa a los protocolos móviles de CosmicOS y tema unificado con libadwaita/CreationDE.
