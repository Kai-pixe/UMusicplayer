# Vinilo — reproductor de música personal

Reproductor PWA instalable en Android, Chromebook e iPhone. Subes tus propias canciones y quedan guardadas en tu dispositivo.

## Privacidad

Sin backend, sin servidor propio. Las canciones se guardan con **IndexedDB directamente en el dispositivo** de quien instale la app. Nadie más tiene acceso a esas canciones — ni siquiera quien publicó el repo.

## Estructura del repo (todo suelto, sin carpetas)

```
index.html
manifest.json
sw.js
README.md
icon-192.png
icon-512.png
icon-512-maskable.png
```

## Publicar en GitHub Pages

1. Sube estos 7 archivos a un repo nuevo, todos en la raíz (sin carpetas).
2. Settings → Pages → Source: **Deploy from a branch** → Branch: **main** → **/ (root)** → Save.
3. Espera 1-2 minutos y abre el link que te da GitHub.

## Uso

- Toca **"Insertar canciones"** para subir tus archivos (mp3, m4a, wav, ogg, aac, flac).
- Toca cualquier canción de la lista para reproducirla.
- El lápiz permite renombrarla; el bote de basura la elimina.
- Todo queda guardado offline: cierra la app y al volver a abrirla tu colección sigue ahí.

## Notas

- Si algún día quieres borrar todo y empezar de cero, borra los datos del sitio desde los ajustes del navegador (Chrome: ícono junto a la URL → Permisos → Borrar datos).
- El almacenamiento tiene un límite que depende del dispositivo (normalmente varios GB), no es infinito.
