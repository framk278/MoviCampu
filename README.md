# MoviCampus Valledupar

Aplicación web académica para explorar y planificar desplazamientos en Valledupar. Es un prototipo independiente y complementario: **no es una aplicación oficial de SIVA**, no contiene datos oficiales validados y no ofrece información en tiempo real.

## Requisitos

- Node.js 18 o posterior
- npm

## Instalación y ejecución

```bash
npm.cmd install
npm.cmd run dev
```

Abre la URL local que indique Vite. Para generar la versión de producción: `npm.cmd run build`; para previsualizarla: `npm.cmd run preview`.

## Acceso de demostración

- Usuario: `admin`
- Contraseña: `demo123`

El acceso solo ilustra el flujo de administración. La sesión y los datos se guardan en LocalStorage; esto **no es seguridad de producción**. No reutilices estas credenciales ni guardes información sensible.

## Funcionalidades

- Inicio con acceso a rutas, paraderos, horarios y planificador.
- Búsqueda de rutas por código y nombre, filtros y detalle con mapa Leaflet/OpenStreetMap.
- Planificador que encuentra coincidencias exactas de origen y destino en la lista de paraderos de una ruta. No estima tiempos ni inventa transbordos.
- Consulta de paraderos y disponibilidad de horarios. Los horarios vacíos se muestran como no disponibles.
- Panel administrativo con creación, edición y eliminación de rutas y paraderos, administración de horarios y confirmación antes de borrar.
- Persistencia local y restablecimiento de los datos de muestra.
- Diseño responsive.

## Datos de demostración

Las rutas, paraderos, coordenadas y trazados iniciales son **ficticios e ilustrativos**. Las coordenadas solamente permiten demostrar la visualización del mapa. No representan recorridos publicados por SIVA ni deben usarse para viajar. El prototipo no carga horarios oficiales. Los cambios locales pueden marcarse como verificados desde el panel; hágase solo al contar con una fuente validada.

## Tecnologías

React, Vite, JavaScript, Tailwind CSS, React Router, Lucide React, Leaflet, React-Leaflet y OpenStreetMap.


