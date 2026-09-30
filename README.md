# CuscoPlan 🏔️

App web para los huéspedes de un hostal en Cusco. Proyecto del curso de Gestión de Proyectos.

**Problema:** los viajeros llegan sin plan y no saben cómo aclimatarse a la altura.

## Funciones

- El viajero elige cuántos días se queda (2 a 7) y sus intereses.
- Genera un itinerario día por día. El día 1 siempre es tranquilo.
- Botón "Reservar con el hostal" que abre WhatsApp con el mensaje listo (incluye el itinerario).
- Consejos rápidos: altura, qué llevar, clima y seguridad.
- Extras: cambiar actividades con 🔄, gráfico de esfuerzo por día y lista de mochila.
- Selector de idioma español / inglés. Sin precios. Pensado para celular.

## Cómo usarlo

Es un solo archivo, sin dependencias: abre `index.html` en el navegador.

## Personalizar para tu hostal

En el `<script>` de `index.html` cambia:

- `HOSTEL_NAME`: nombre del hostal.
- `HOSTEL_PHONE`: WhatsApp del hostal, con código de país y sin `+` (ejemplo: `51999999999`).

## Sistema de diseño

Tokens de color, tipografía, espaciado, radios, sombras y movimiento al inicio del `<style>`. Componentes: `.btn` (primary, accent, success), `.card`, `.tile`, `.seg`.

## Publicar en GitHub Pages

Settings → Pages → Branch `main` / carpeta `/root` → Save.
