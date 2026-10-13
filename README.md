# BoxesMedia360 — Catálogo de referencias visuales

Catálogo para revisar referencias visuales facilitadas a BoxesMedia360. Incluye copias sin modificación de 12 artes de referencia, capturas de cuatro proyectos web (incluida una tarjeta de contacto) y cinco fotogramas de muestra de cada uno de dos videos. Contiene anotaciones provisionales para análisis interno y **no** declara aprobada, reutilizable ni lista para producción ninguna pieza.

## Uso local

Abre `index.html` en un navegador moderno. No requiere dependencias externas. La selección de referencias usa `localStorage` del navegador actual: no se envía al servidor ni se sincroniza con GitHub. GitHub Pages, si llegara a activarse manualmente, es alojamiento estático público y no sincroniza `localStorage` entre visitantes.

## Contenido

- `asset_01.jpg` … `asset_12.png`: copias byte por byte de los archivos gráficos inventariados. Consulta `assets.json` para tamaño, formato, modo de color y hashes de origen.
- `web_*.png`: capturas de revisión de los sitios suministrados.
- `Grand_Opening_video/` y `Menu_Los_Cuates_3/`: cinco fotogramas de cada MP4, no los videos originales.
- `feedback.json`: etiquetas de selección por referencia y limitación de alcance; no contiene el transcript o la atribución de autorización de chat.
- `MEMORIA_VISUAL.md`: síntesis general no sensible de pautas de QC, separando observaciones de aprobación.

## Límites y licencias

Las capturas web reflejan la vista superior observada, no una prueba funcional integral. Los fotogramas no validan secuencia, movimiento, audio o sincronía. El `.kra` original no se publica aquí. La composición/etiquetas describen material suministrado; pueden existir logos, contactos, precios o anuncios propiedad de clientes/terceros. **La autorización del director no reemplaza licencias o permisos que sean necesarios para redistribuir públicamente activos de terceros.** Repositorio público previsto sólo bajo la responsabilidad y permiso de BoxesMedia360; no publicar secretos ni archivos fuente privados.

No es un paquete de producción ni está listo para imprenta.


## Portfolio público · actualización del 12 de octubre de 2026

El autor confirma que los trabajos son suyos y que cuenta con autorización de los involucrados para usar logos y nombres en su portfolio. Esta confirmación se refiere a su presentación como trabajo del estudio; las notas técnicas de revisión anteriores se conservan como registro.

- Incorporada [La Jaiba Brava — tarjeta de contacto](https://la-jaiba-brava-menu.netlify.app/), proyecto independiente del muestrario orbital, con captura real `web_la_jaiba_contacto.png` (1264 × 1486).
- `portfolio-publico.json` selecciona 16 fichas: 12 piezas gráficas y cuatro proyectos web. Contiene solo títulos, categorías, rutas de imágenes y enlaces públicos; excluye notas internas.
- El portal de BoxesMedia360 consume esta selección al ejecutar `npm run sync:portfolio` en el proyecto portal. Modificar este JSON permite incorporar o editar fichas en la siguiente sincronización. No hay despliegue automático conectado.
- El nuevo sitio se inspeccionó visualmente; no se enviaron mensajes, iniciaron llamadas ni realizó una auditoría funcional completa.

