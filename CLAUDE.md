# josorogic.github.io — instrucciones para agentes

Sitio de desarrollador de LCN en GitHub Pages. Es infraestructura, no un producto.

## Regla crítica

⚠️ **`app-ads.txt` es la verificación de AdMob para las apps de LCN (Calculadora de crédito, Nekruba). Romperlo, moverlo o borrarlo corta la monetización por ads.** Cualquier cambio a ese archivo debe ser explícitamente pedido por Joso, y tras editarlo hay que recordarle que AdMob puede tardar en re-verificar (hasta 24h+).

## Protocolo

- Inicio: verifica qué hay realmente desplegado (el sitio público) antes de asumir el estado local.
- Cierre: si cambiaste algo, confirma que el deploy de GitHub Pages salió (el push a `main` publica).
- Jerarquía de verdad: **sitio publicado > repo local**.

## Contexto

- Contenido: `index.html` (página del estudio) + `app-ads.txt` (AdMob).
- Los IDs de publisher de AdMob que deben figurar en `app-ads.txt` se gestionan desde la cuenta AdMob de LCN.
