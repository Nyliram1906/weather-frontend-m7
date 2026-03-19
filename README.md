# 🌫️ El Tiempo en Scadrial — Módulo 6 (SPA con Vue.js)

Recreación de la App de Clima como una **aplicación de una sola página (SPA)** utilizando Vue.js.
Mantiene la temática del universo **Mistborn** de Brandon Sanderson y los datos de clima de los módulos anteriores.

---

## 🗺️ Vistas principales

| Vista       | Ruta           | Descripción                                              |
|-------------|----------------|----------------------------------------------------------|
| Home        | `/`            | Listado de las 10 ciudades de Scadrial con clima actual  |
| Detalle     | `/lugar/:id`   | Pronóstico, estadísticas y alertas de una ciudad         |

---

## 🧭 Rutas configuradas (Vue Router)

```javascript
{ path: '/',          component: HomeView }
{ path: '/lugar/:id', component: DetalleView }
```

La navegación entre vistas se realiza sin recargar la página gracias a Vue Router.

---

## ✨ Interacción incluida

- Búsqueda de lugares por nombre con `v-model`

---

## 🛠️ Tecnologías utilizadas

- **Vue.js 3**
- **Vue Router**
- **Bootstrap 5.3** + Bootstrap Icons
- **Vite**
- **API Open-Meteo** (gratuita, sin API key)

---

## ⚙️ Cómo ejecutar el proyecto

```bash
npm install
npm run dev
```

---

## 🔗 Repositorio

[GitHub — El Tiempo en Scadrial M6](https://github.com/Nyliram1906/weather-frontend-m6)

---

## 👩‍💻 Autora

**Marilyn Villalobos** — Desarrolladora Frontend  
Proyecto académico — Módulo 6: SPA con Vue.js  
© 2025 Mistborn Edition

