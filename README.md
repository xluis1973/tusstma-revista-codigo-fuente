# Revista interactiva TUSSTMA

HTML, CSS y JavaScript sin dependencias. Incluye las 25 materias, 10 enlaces de presentación, ilustraciones vectoriales y correlatividades según RR 11080003-ULP-2024.

## Publicar en GitHub y Vercel

Descomprimir y subir el contenido a un repositorio, conservando dist y vercel.json en la raíz.
En Vercel: Framework Other, sin comando de compilación, Output Directory dist.

## Abrir localmente

Abrir dist/index.html o ejecutar: python -m http.server 8000 --directory dist

## Contenido

- dist/index.html: HTML, CSS, datos de materias y JavaScript de navegación.
- dist/materias.json: copia de consulta de los datos. La revista usa la constante subjects de index.html; actualizar esa constante para modificar la revista.
- dist/documentos/: plan original y modificación de correlatividades.

El régimen de 2024 ubica Estadística en 2.º año, 2.º cuatrimestre, y Capacitación de Personal en 3.º año, 1.º cuatrimestre. Se conserva la notación numérica original de las correlatividades para evitar reinterpretar guiones o rangos.

Higiene Laboral I y II usan el mismo enlace suministrado: V_IwXaJ7EBM. Sustituir el identificador correspondiente si se desea diferenciar las presentaciones.

Las ilustraciones están incluidas como SVG dentro del HTML. El cambio de hojas utiliza animación CSS/JavaScript y respeta la preferencia de reducir movimiento. Los videos requieren Internet y permisos de inserción en YouTube. El sitio no incluye autenticación propia.
