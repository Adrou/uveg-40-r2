# Tokyo Night Palette - Despliegue de aplicación web

Este proyecto es en atención al R2 del módulo.

## Proceso de Optimización realizado
1. **Estructura de directorios**: Se separó la lógica en directorios estandarizados (`/css`, `/js`, `/img`).
2. **Minificación**: Se extrajo el bloque `<style>` del archivo original y se procesó hacia `css/style.min.css` reduciendo drásticamente su tamaño.
3. **Empaquetado**: Se generó el archivo `empaquetado_produccion.zip` listo para el paso a servidores de producción.
4. **Servidor Web**: Configurado utilizando MAMP PRO mediante un Virtual Host apuntando al directorio raíz.