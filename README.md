# Mi Parque

Juego de gestión de parques de atracciones en 3D que se juega directamente en el navegador (celular o computadora). Construye caminos, atracciones y montañas rusas; investiga, enfrenta el clima y supera escenarios.

- Jugar: abre la página del repositorio en GitHub Pages.
- La partida se guarda sola en tu navegador. En el menú (☰ → Parque) puedes exportar e importar una copia de seguridad.
- Es un sitio estático: `index.html` + `three.min.js` (three.js r128, licencia MIT).

## Probar en local

    python3 -m http.server 8000

Y abre http://localhost:8000

## Novedades

- **Montaña rusa en modo simple.** El editor abre con pocos botones: Recta, Subida (con cadena automática), Bajada, Izquierda y Derecha. El botón ✨ arma o termina el circuito por ti, lo prueba y abre la atracción. Las piezas avanzadas siguen en «Más piezas y opciones».
- **Ayuda integrada** (botón «?»): explica cómo cerrar el circuito y qué significan emoción, intensidad y náuseas. Se muestra sola la primera vez.
- **Sin zoom accidental** al tocar rápido los botones del menú en el celular.
