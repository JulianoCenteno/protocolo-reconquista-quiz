# Protocolo de la Reconquista — Quiz Gamificado

Quiz en un único archivo (`index.html`), mobile-first, con XP, niveles, logros, sonido, diagnóstico personalizado, cofre de bonos y página de oferta.

## Editar
Todo lo editable está en el bloque `CONFIG` al inicio del `<script>`:
- `checkoutUrl`, `price`, `priceOld`
- `vslEmbed` (embed del vídeo) y `revealDelaySec` (segundos antes de mostrar la oferta; 0 = inmediato)
- rutas de imágenes (`logo`, `painImages`, `testimonialImages`, `bonusImages`, `expert.photo`)

## Imágenes
Poner los archivos en `images/` respetando las rutas del `CONFIG`.

## Pixels
Pegar los scripts de Facebook Pixel / UTMify en el `<head>` (hay un comentario marcando el lugar).
