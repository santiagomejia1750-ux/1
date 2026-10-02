# Proyecto web — David Santiago Cortes Mejia

Proyecto web preparado para publicarse en **GitHub Pages**.

## 🚀 Publicar en GitHub Pages

1. Crea un repositorio **público** en GitHub.
2. Sube **todo el contenido de esta carpeta** al repositorio.
3. Haz el primer `commit` en la rama `main`.
4. Entra en **Settings → Pages**.
5. En **Build and deployment**, selecciona **GitHub Actions**.
6. GitHub ejecutará el flujo `.github/workflows/pages.yml`.
7. Cuando termine, en **Settings → Pages** aparecerá el enlace público del sitio.

También puedes usar **Deploy from a branch → main → / (root)** si prefieres la publicación directa de los archivos estáticos.

## 📁 Estructura importante

```text
.
├── index.html
├── README.md
├── .nojekyll
├── .github/
│   └── workflows/
│       └── pages.yml
└── demás archivos y carpetas del proyecto
```

`index.html` debe permanecer en la raíz del repositorio para que GitHub Pages lo encuentre como página principal.

## 💻 Uso local

Puedes abrir `index.html` directamente en el navegador. Si alguna función requiere un servidor local, ejecuta el proyecto mediante un servidor local desde esta carpeta.

## 👤 Autor

**David Santiago Cortes Mejia**  
**Universidad del Tolima**  
**Fecha de publicación:** 19 de septiembre de 2026

## 🛠️ Publicación automática

Cada vez que hagas `push` a la rama `main`, GitHub Actions volverá a publicar la versión actualizada del proyecto.
