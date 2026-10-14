# Profesor IA Matemáticas — sitio web oficial

Sitio estático (HTML y CSS, sin frameworks ni dependencias) del complemento **Profesor IA Matemáticas**, desarrollado por William Jiménez. Se publica con GitHub Pages desde la rama `main`, carpeta raíz.

## Páginas

| Archivo | Uso en OpenAI Platform | URL pública |
| --- | --- | --- |
| `index.html` | Website URL | https://williamajg80.github.io/profesor-ia-matematicas-web/ |
| `soporte.html` | Support URL | https://williamajg80.github.io/profesor-ia-matematicas-web/soporte.html |
| `privacidad.html` | Privacy policy URL | https://williamajg80.github.io/profesor-ia-matematicas-web/privacidad.html |
| `terminos.html` | Terms of service URL | https://williamajg80.github.io/profesor-ia-matematicas-web/terminos.html |

Otros archivos:

- `estilos.css`: hoja de estilos común.
- `favicon.svg`: icono del sitio.
- `404.html`: página de error.
- `LICENSE`: licencia CC BY 4.0.
- `.nojekyll`: indica a GitHub Pages que publique los archivos tal cual.

## Cómo editar

1. Abra el archivo en GitHub y pulse el icono del lápiz («Edit this file»).
2. Haga el cambio y pulse **Commit changes**.
3. GitHub Pages publica la nueva versión en uno o dos minutos.

El encabezado y el pie de página se repiten en las cuatro páginas. Si cambia un enlace del menú, cámbielo en todas.

## Mantenimiento

- **Cambios en el complemento:** si se habilita la compilación de PDF o se añaden herramientas al servidor MCP, actualice `index.html`, `soporte.html`, `privacidad.html` y `terminos.html`.
- **Textos legales:** al modificar la política de privacidad o los términos, actualice la fecha «Última actualización» y la versión al inicio del documento.
- **Rutas relativas:** use enlaces del tipo `soporte.html` y `estilos.css`, sin barra inicial, para que el sitio funcione dentro de `/profesor-ia-matematicas-web/`.
- **Privacidad del sitio:** no añada analítica, cookies, formularios, tipografías externas ni scripts de terceros sin actualizar antes la política de privacidad.
- **Seguridad:** no suba claves, credenciales ni código o documentación interna del servidor MCP. El repositorio del servidor es privado e independiente.
- **Soporte:** las incidencias se gestionan en la pestaña **Issues** de este repositorio, que debe permanecer habilitada.

## Publicación con GitHub Pages

Settings → Pages → Build and deployment → Source: **Deploy from a branch** → Branch: `main` / `(root)` → Save.

## Licencia

Los textos y el diseño de este sitio se publican bajo la licencia [Creative Commons Atribución 4.0 Internacional (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.es). Puede reutilizarlos citando a William Jiménez como autor. El texto completo está en `LICENSE`.
