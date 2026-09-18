# Sushi Fuku — sitio web

## Estructura
- `index.html` — el sitio completo (una sola página)
- `images/` — fotos reales del negocio, referenciadas por nombre en el HTML

## Para agregar o cambiar una foto de un platillo
1. Nombra el archivo nuevo de forma clara, ej. `fuku-hero.jpg`, `arrachera.jpg`
2. Ponlo dentro de la carpeta `images/`
3. En `index.html`, busca el bloque del platillo (Ctrl+F con el nombre del platillo) y donde dice
   `<div class="w-16 h-16 ... text-2xl shrink-0">🍣</div>` (el emoji placeholder),
   cámbialo por: `<img class="w-16 h-16 rounded-lg object-cover shrink-0" src="images/nombre-del-archivo.jpg" alt="nombre del platillo">`

## Fotos ya incluidas
fuku-hero.jpg · charola-sushi.jpg · charola-alitas.jpg · camanroll.jpg ·
toxica-burger.jpg · toro-horneado.jpg · alitas.jpg · charola-surtida.jpg

Los demás 39 platillos de la carta todavía usan un emoji como marcador de foto —
se van reemplazando igual, uno por uno, según lleguen las fotos.
