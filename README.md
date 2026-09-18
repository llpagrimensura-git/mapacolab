# Mapa #Encuentro · Santa Fe

Mapa colaborativo para el #Encuentro: la gente toca un punto en el mapa, cuenta qué pasa ahí y el aporte se guarda en una planilla de Google Sheets. Después se puede ver todo en un mapa en vivo, en una tabla cruda o en gráficos.

🔗 **Demo:** https://mapacolab.netlify.app/

---

## ✨ Qué hace

- 🗺️ **Mapa interactivo** (Leaflet + OpenStreetMap) centrado en Santa Fe.
- 📍 **Carga de puntos** con temática, ícono, texto (280 caracteres) y autor opcional o anónimo.
- ❤️ **Apoyos** por punto, con animación.
- 🏷️ **Filtros por temática** (Ciudad, Nutrición, Educación, Salud, Juventud, Obras, Otro).
- 📋 **Vista Planilla** para ver todos los aportes y descargarlos como CSV.
- 📊 **Vista Datos** con contador animado, dona por temática, línea por día y ranking de barras.
- 📱 **Responsive** con panel colapsable y popup adaptado a mobile.
- 🔄 **Sincronización automática** cada 60 s con reintento de escrituras si se cae la red.
- 💾 **Guardado local** (localStorage) si no hay conexión; se sube cuando vuelve.
- 🔗 **Compartir** por WhatsApp o copiar link.

---

## 🛠️ Stack

- **Frontend:** HTML + CSS + JS puro. Sin build step.
- **Mapa:** [Leaflet 1.9](https://leafletjs.com/) + tiles de OpenStreetMap.
- **Gráficos:** [Chart.js 4.4](https://www.chartjs.org/).
- **Backend:** Google Apps Script como Web App (recibe POST y GET, escribe en Google Sheets).
- **Deploy:** Netlify (o cualquier host estático: Vercel, GitHub Pages, etc.).
