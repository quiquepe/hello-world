# Sorteo de Instagram

App web para realizar sorteos transparentes con los comentarios de posteos de Instagram.

## Funcionalidades

- **Cargar participantes** de dos formas:
  - Pegar comentarios copiados directamente desde Instagram (detecta @usuarios automáticamente)
  - Usar la Instagram Graph API con un Access Token para cargar comentarios automáticamente
- **Filtros**: eliminar duplicados, excluir cuentas específicas, elegir cantidad de ganadores
- **Animación de sorteo** estilo ruleta/slot machine para grabar o compartir en vivo
- **Grabación de pantalla** integrada para capturar el sorteo y subirlo a redes
- **Link compartible**: generá un link con el resultado del sorteo para compartirlo
- **Selección criptográficamente aleatoria** usando `crypto.getRandomValues()`
- **Historial de sorteos** dentro de la sesión

## Cómo usar

1. Abrí `index.html` en un navegador (o desplegá en GitHub Pages)
2. Pegá los comentarios del posteo de Instagram o conectá la API
3. Revisá la lista de participantes y configurá las opciones
4. Hacé clic en "Iniciar sorteo" y grabá el resultado
5. Compartí el link del resultado

## Deploy en GitHub Pages

El archivo `index.html` es completamente autocontenido (HTML + CSS + JS). Para desplegarlo:

1. Activá GitHub Pages en Settings > Pages
2. Seleccioná la branch y carpeta raíz (`/`)
3. La app va a estar disponible en `https://tu-usuario.github.io/hello-world/`
