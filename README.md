# Blog Técnico — Grafos

Este repositorio contiene un pequeño blog técnico estático sobre la estructura de datos <strong>Grafos</strong>. La idea es publicar en GitHub Pages y entregar **el enlace** generado por GitHub Pages.

Archivos principales:
- `index.html` — Página principal.
- `css/styles.css` — Estilos con paleta verde/blanco (estilo "astrapto").
- `posts/post1.html` — Introducción a los grafos (nodos, aristas, tipos) con SVG.
- `posts/post2.html` — Representación: lista de adyacencia / matriz de adyacencia.
- `posts/post3.html` — Algoritmos BFS / DFS con pseudocódigo.

Publicar en GitHub Pages (pasos rápidos desde PowerShell):

1) Iniciar repo y commit localmente:

```powershell
cd "c:\Users\DAVID MEDINA\Videos\proyecto"
git init
git add .
git commit -m "Initial blog sobre grafos"
```

2) Crear repositorio en GitHub (puedes usar la web) y añadir remote, luego pushear a `main`:

```powershell
git branch -M main
git remote add origin https://github.com/<TU_USUARIO>/<TU_REPO>.git
git push -u origin main
```

3) En GitHub -> Settings -> Pages: seleccionar `main` branch y carpeta `/ (root)` o `/docs` según prefieras. Guardar. GitHub generará un enlace `https://<TU_USUARIO>.github.io/<TU_REPO>/`.

4) Copia ese enlace y súbelo a la actividad.

Notas:
- Los videos sugeridos están enlazados hacia búsquedas en YouTube para que puedas elegir el contenido preferido.
- Si quieres, puedo crear el repo por ti (necesitaría acceso por token) o guiarte en cada paso y validar que la página quedó publicada.
