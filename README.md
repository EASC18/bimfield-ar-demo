# BIMFIELD AR 0.2.1 — diagnóstico de seguimiento

## Instalación
1. Descomprimir el ZIP.
2. En Netlify, abrir el proyecto existente y arrastrar la carpeta BIMFIELD_AR_v0.2.1 en Deploys para publicar actualización. No subas modelos GLB ni RVT al hosting.
3. En Chrome Android recarga la página; si aparece versión anterior, cierra pestaña y vuelve a abrirla.
4. Toca Ver DEMO HVAC, START AR. Apunta a una superficie con textura y espera que aparezca un aro verde en el suelo. Toca una sola vez para anclar. Un marcador vertical verde marca el punto de anclaje: gira la cámara 90 grados y vuelve al mismo lugar.

## Importante
Esto usa un punto fijo en el espacio de referencia local de WebXR; no ofrece calibración QR, anclaje persistente, detección de interferencias ni precisión validada. Un anclaje del renderer no es necesariamente un anclaje ARCore persistente. No utilizar para medidas ni perforaciones. El modelo DEMO es ficticio y grande, sus elementos pueden quedar fuera de campo visual.

## Seguridad
La aplicación carga Three.js de jsDelivr. No cargar planos sensibles hasta realizar revisión de seguridad y despliegue privado.
