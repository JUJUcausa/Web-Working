# Constructora Nova

Sitio web estático de 4 páginas para una empresa de servicios de construcción, con diseño moderno, responsive y listo para desplegarse en Netlify.

## Páginas
- `index.html` (Inicio)
- `servicios.html`
- `proyectos.html`
- `contacto.html` (formulario compatible con Netlify Forms)

## Desarrollo local
```bash
python3 -m http.server 4173
```

Abrir `http://localhost:4173`.

## Deploy en Netlify
El archivo `netlify.toml` ya está configurado para publicar la raíz del proyecto y ofrecer rutas limpias:
- `/`
- `/servicios`
- `/proyectos`
- `/contacto`
