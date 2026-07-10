# manual-rae

Manual de usuario web del sistema **RAE** (Registro de Actividades y Eventos) de la
UTP. El contenido se define en `seed-data.js` y el sitio se genera con
[`manual-generator`](https://github.com/afgrajaless/manual-generator).

## Estructura

```
manual-rae/
├─ seed-data.js     # contenido del manual (fuente)
├─ manual.xlsx      # libro generado desde seed-data.js
├─ styles.css       # sistema visual
├─ captures/        # capturas de pantalla (fuente)
├─ assets/          # logos + capturas optimizadas
└─ index.html + participante.html + coordinador.html   # sitio generado
```

## Uso

```bash
npm install          # instala manual-generator desde GitHub
npm run seed         # regenera manual.xlsx desde seed-data.js
npm run build        # construye el sitio (index.html + una página por manual)
```

Abre `index.html` en el navegador para ver el manual.
