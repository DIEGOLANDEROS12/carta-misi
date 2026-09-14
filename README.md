# Carta para Misi 💌

Ya viene con tu carta completa y tus 5 fotos como collage alrededor.
Asegúrate de subir también la carpeta `fotos/` junto con `index.html` —
si solo subes el HTML, las fotos no van a aparecer.

## 1. Subirla a GitHub (repo nuevo)

```bash
git init
git add .
git commit -m "carta para Misi"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/NOMBRE-DEL-REPO.git
git push -u origin main
```

(Cambia `TU-USUARIO` y `NOMBRE-DEL-REPO` por los tuyos. Si el repo ya
existe, sáltate el `git remote add` y solo haz `git push`.)

## 2. Publicarla con GitHub Pages (para mandarle el link)

1. En GitHub, entra al repo → **Settings** → **Pages**.
2. En "Branch" selecciona `main` y la carpeta `/root`, luego **Save**.
3. Espera 1–2 minutos. Tu link quedará como:
   `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`

Ese es el link que le mandas a Misi.

## Notas

- La música empieza a sonar justo cuando ella toca "abrir mi corazón"
  (los navegadores no dejan reproducir audio automáticamente sin que
  la persona interactúe primero, así que quedó ligado al clic).
- Tocar el disco/nota musical de la esquina pausa o reanuda la canción.
- Si quieres cambiar la canción, reemplaza `Sek1vLw3s20` en `index.html`
  (línea del `videoId`) por el ID del video que quieras — es lo que va
  después de `youtu.be/` en el link.
