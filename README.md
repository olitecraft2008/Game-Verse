# Tanques 1v1

Juego web de tanques en HTML, CSS y JavaScript. No necesita un proceso de compilación: GitHub Pages puede servirlo directamente.

## Publicarlo con GitHub Pages

1. Entra en GitHub y crea un repositorio nuevo, por ejemplo `tanques-1v1`.
2. Sube `index.html`, `.nojekyll` y `README.md` a la raíz del repositorio. También puedes subir el ZIP preparado y extraerlo antes de publicar; Pages debe tener `index.html` en la raíz.
3. En el repositorio, abre **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/(root)`, y pulsa **Save**.
6. Espera a que termine la publicación. La dirección aparecerá en esa misma página, normalmente con el formato `https://TU-USUARIO.github.io/tanques-1v1/`.

## Notas

- El archivo carga PeerJS desde un CDN y usa Google Fonts, por lo que necesita conexión a Internet.
- GitHub Pages aloja los archivos del juego, pero no proporciona por sí mismo un servidor de partidas. El modo multijugador depende del servicio de señalización/conexión configurado por PeerJS y de la conectividad de los navegadores.
- Si actualizas el juego, vuelve a subir el `index.html` y espera a que GitHub Pages publique los cambios.
