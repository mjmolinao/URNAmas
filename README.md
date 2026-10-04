# URNA+

Plataforma de alfabetización política para jóvenes de 18 a 35 años en Guatemala. Test político tipo juego, top 3 de temas, radar de aspirantes 2027, calendario electoral y diccionario de bolsillo.

## Publicar en GitHub Pages

1. Subí `index.html` (y este README) a la raíz del repositorio.
2. En el repo: **Settings → Pages**.
3. En *Source* elegí **Deploy from a branch**, rama `main`, carpeta `/ (root)`. Guardá.
4. En uno o dos minutos la web queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Notas

- Todo vive en un solo archivo: HTML, CSS y JavaScript. No necesita instalar nada.
- El acta del test se guarda en el navegador de cada persona (localStorage). No se envía a ningún servidor.
- **Mapa de intereses:** en esta versión aparece como "se enciende pronto". Para activarlo en la web pública hay que conectar una base de datos (por ejemplo Supabase o Firebase).
- Para cambiar el color principal, editá la variable `--pink` al inicio del `<style>`.
- Datos de aspirantes: Infobae (28/07/2026). Calendario: cronograma preliminar del TSE (junio 2026). Revisar y actualizar antes de cada publicación.
