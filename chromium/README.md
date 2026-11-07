# Parches de Chromium / ungoogled-chromium para CosmicOS

## Alcance (Secciones 9.3 y 11 de CosmicOS Spec v0.2.5)

- **Base oficial:** `ungoogled-chromium` con cadencia propia de actualizaciones.
- **Modo Wayland puro:** eliminación de capas X11 obsoletas.
- **Aislamiento de GPU:** listas blancas de `ioctl` permitidas para renderizadores de GPU libre (`freedreno` para Adreno, `panfrost`/`panthor` para Mali).
- **WebView del sistema (Etapa 2):** desacoplamiento de la integración de incrustación para proveer un único motor web seguro en espacio de usuario.
