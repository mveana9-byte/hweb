# Práctica 06 — Agregación de Links

## Contenido
- `glosario.html`: enlaces a fragmentos por letra y enlaces `Go up`.
- `masterchef/`: sitio de la práctica anterior con ejemplos de `target`.
- `autor/index.html`: página de autor con ejemplos de `mailto:` y `tel:`.

## Antes de entregar
1. Completa los campos entre corchetes en `autor/index.html`.
2. Agrega una fotografía llamada `foto.jpg` dentro de `autor/`, o cambia el valor de `src` para que coincida con el nombre de tu archivo.
3. Revisa todos los enlaces en el navegador.
4. Sube la carpeta `p06/` a un repositorio público de GitHub.

## Valores de `target`
- `_blank`: abre el enlace en una nueva pestaña o ventana.
- `_self`: abre el enlace en el contexto actual (valor predeterminado).
- `_parent`: abre el enlace en el contexto padre; si no hay marcos, suele comportarse como `_self`.
- `_top`: abre el enlace en el contexto superior completo; si no hay marcos, suele comportarse como `_self`.

## Notas sobre `mailto:` y `tel:`
- `mailto:` solicita al dispositivo abrir una aplicación compatible para redactar un correo; no garantiza que se envíe automáticamente.
- `tel:` solicita abrir una aplicación capaz de gestionar llamadas; en una computadora puede no haber una aplicación compatible.
- Ambos dependen de las aplicaciones configuradas en el dispositivo y de las políticas del navegador.
