# 🌿 Visualización de Datos del Manglar

Este proyecto permite visualizar datos ambientales obtenidos de sensores ubicados en un manglar. Los datos son cargados desde una hoja de cálculo de Google Sheets y se presentan en dos formatos:

- **Tabla interactiva**
- **Gráfico dinámico por variable**

El objetivo principal es facilitar el análisis de variables como pH, temperatura, TDS, oxígeno disuelto, entre otras, para monitorear la salud del ecosistema.

---

## 📦 Tecnologías Utilizadas

- **HTML5** – Estructura de la página
- **CSS3** – Estilos visuales
- **JavaScript** – Lógica e interactividad
- **[Chart.js](https://www.chartjs.org/)** – Gráficos interactivos
- **Google Sheets (CSV)** – Fuente de datos en la nube

---

## 🔍 Funcionalidades

| Función                   | Descripción                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| Visualización en tabla   | Muestra todos los datos en una tabla ordenada                              |
| Visualización gráfica    | Permite graficar variables seleccionadas sobre el tiempo                   |
| Selector de variables    | Despliega una lista de variables disponibles para graficar                 |
| Zoom y Pan en gráfico    | El usuario puede acercar, alejar y mover el gráfico                        |
| Exportar gráfico         | Opción para descargar el gráfico como imagen PNG                           |
| Actualizar datos         | Recarga los datos desde la hoja de cálculo                                 |
| Navegación con pestañas  | Cambia entre vista de tabla y gráfica                                       |

---

## 📄 Estructura del Proyecto

```bash
📁 proyecto/
├── index.html         # Página principal
├── styles.css         # Estilos personalizados
└── script.js          # Lógica para cargar datos y renderizar gráficos
```

---

## 🔗 Fuente de Datos

Los datos se cargan desde la siguiente hoja de Google Sheets publicada como CSV:

```
https://docs.google.com/spreadsheets/d/e/2PACX-1vQZcYp6CmGzPbeIfLHtGbQ4V2A1sLbSsLJZIts_ksK9cy51xrhpeLyx7X9Q2mHYbfvAp8Fhr3186Y9k/pub?output=csv
```

> ⚠️ Asegúrate de que la hoja esté publicada y con permisos de visualización pública si vas a desplegar esta aplicación.

---

## 💡 Mejoras Futuras

- Filtros por fecha o por variable
- Visualización de múltiples variables en un mismo gráfico
- Modo oscuro
- Adaptabilidad total a dispositivos móviles
- Almacenamiento de preferencias (última pestaña o variable usada)

---

## 👥 Público Objetivo

- Estudiantes e investigadores ambientales
- Comunidades locales interesadas en la salud de los manglares
- Docentes y ciudadanos comprometidos con el monitoreo ambiental

---

## 📜 Licencia

Este proyecto es de uso libre para fines educativos, académicos y científicos. Si lo utilizas, considera referenciar al equipo de desarrollo original.

---

## 🙌 Créditos

Desarrollado por Juan D. Villa ( https://github.com/danielvillam ) - _Desarrollador_., como parte de un sistema de monitoreo ambiental de bajo costo para manglares en la zona de Perlaza, seleccionada por su nivel de afectación, seguridad, uso colectivo del territorio y ausencia de sensores previamente instalados.