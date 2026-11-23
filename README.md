# LaCoru · datos

Datos abiertos que usa [LaCoru](https://lacoru.pages.dev), la app cívica y gratuita de A Coruña y su área: buses, farmacias, tiempo, mar, planes…

- **Rama `datos`:** los ficheros que lee la app (servidos por GitHub Pages). Se regeneran cada ~30 minutos (la tarea está programada cada 10, pero GitHub casi no la lanza y la relanza la pasarela).
- **Rama `catalogo`:** paradas, calles y sitios, regenerados cada madrugada.
- **Cada semana** se rehacen los grafos de calles con los que el móvil calcula las rutas, y **cada mes** las teselas del mapa (`tiles/`, con `tiles/tiles.json`).
- **Avisos (Issues):** la tarea «Salud» abre uno si algo deja de funcionar (y lo cierra sola cuando vuelve) y «Fuentes que cambian» avisa si cambia un documento oficial que la app transcribió a mano, como la ordenanza de la ORA.

Las fuentes y sus licencias están en la app: Ajustes → Privacidad y fuentes. Aquí no hay ningún dato de personas.

El código de la app no es público. © Santiago Delgado Ferreiro. Todos los derechos reservados sobre el código y el diseño de LaCoru; los datos de cada fuente conservan su licencia.
