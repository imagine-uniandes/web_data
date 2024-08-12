# IMAGINE y COLIVRI Web Data

Este repositorio contiene los datos y recursos utilizados por los sitios web de IMAGINE y COLIVRI de la Universidad de los Andes.

## Descripción

Este repositorio almacena:
1. Información estructurada en formato JSON para el contenido de los sitios web.
2. Imágenes y otros recursos visuales utilizados en los sitios.

## Estructura del Repositorio
```
├───data
│       groups.json
│       papers.json
│       people.json
│       projects.json
│       seminars.json
│
├───img
│   ├───events
│   ├───groups
│   ├───people
│   └───projects
│
└───v2
│   └───data
|       projects.json
```
### Descripción de las carpetas

- `data/`: Contiene archivos JSON con información estructurada para diferentes secciones del sitio.
- `img/`: Almacena todas las imágenes utilizadas en los sitios web.
  - `events/`: Imágenes relacionadas con eventos.
  - `groups/`: Imágenes de los grupos de investigación.
  - `people/`: Fotos de los miembros del equipo.
  - `projects/`: Imágenes relacionadas con proyectos.
- `v2/`: Versión actualizada, con mejor estructura (actualmente solo contiene projects.json).

## Uso

Este repositorio es utilizado por el sistema de gestión de contenidos (CMS) personalizado de IMAGINE para actualizar la información y los recursos visuales en los sitios web.

### Actualización de Contenido

1. Para datos JSON:
   - Navega hasta el archivo JSON correspondiente en la carpeta `data/`.
   - Edita el contenido siguiendo la estructura existente del JSON.

2. Para imágenes:
   - Añade o reemplaza imágenes en la subcarpeta correspondiente dentro de `img/`.
   - Utiliza nombres de archivo descriptivos y en minúsculas.

3. Haz commit de tus cambios con un mensaje descriptivo.
4. Realiza un push al repositorio.

## Directrices de Contribución

- Mantén la estructura existente de los archivos JSON y las carpetas de imágenes.
- Utiliza nombres de archivo descriptivos y en minúsculas para todos los recursos.
- Asegúrate de que el JSON sea válido antes de hacer commit.
- Optimiza las imágenes antes de subirlas para mejorar el rendimiento del sitio web.
- No incluyas información sensible o privada en este repositorio público.

## Imágenes y Recursos Visuales

- Formatos aceptados: JPG, PNG, SVG, WEBP, ETC.
- Coloca las imágenes en las subcarpetas correspondientes según su uso (events, groups, people, projects).
- Nombra las imágenes de manera descriptiva (ej. `foto_juanPerez.jpg`).

## Seguridad

Aunque este es un repositorio público, ten en cuenta que la información y las imágenes aquí contenidas se reflejarán en los sitios web públicos de IMAGINE y COLIVRI. No incluyas datos sensibles, información personal que no deba ser de dominio público, o imágenes con derechos de autor sin permiso.
.
