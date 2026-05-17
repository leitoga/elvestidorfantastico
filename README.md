# El Vestidor Fantástico

Sitio landing de **El Vestidor Fantástico** — cosplays, disfraces e indumentaria.

## Estructura

```
.
├── index.html              # Landing page (todas las secciones)
├── css/
│   └── style.css           # Estilos
├── assets/                 # Imágenes, logo y separadores SVG
└── README.md
```

## Desarrollo local

Es un sitio estático: no hace falta build. Para verlo localmente alcanza con abrir `index.html` en el navegador, o servirlo con cualquier servidor estático:

```bash
# con Python 3
python3 -m http.server 8080

# o con Node
npx serve .
```

Después abrir <http://localhost:8080>.

## Publicar en GitHub Pages

1. Subir este repo a GitHub.
2. Settings → Pages → Branch: `main` / root → Save.
3. El sitio queda en `https://<usuario>.github.io/<repo>/`.

## Secciones

- Inicio
- Cosplays
- Disfraces
- Indumentaria
- Nuestros trabajos
- Envíos
- Contacto

## Notas

- La página principal es responsive, con menú hamburguesa overlay en mobile.
- Las secciones violetas tienen fondo cósmico tileado con parallax al scroll.
- Las divisiones entre secciones usan SVG con pinceladas como CSS mask.
