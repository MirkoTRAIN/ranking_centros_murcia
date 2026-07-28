# Ranking de vacantes docentes · Región de Murcia

Web estática (un único archivo `index.html`, sin backend) con el ranking de las 539 vacantes docentes puntuadas según el baremo: calidad educativa, % de extranjeros, calidad de vida y precio del alquiler.

## Publicarla con GitHub Pages (gratis)

1. Ve a [github.com/new](https://github.com/new) y crea un repositorio nuevo (puede llamarse, por ejemplo, `ranking-vacantes-murcia`). Debe ser **público** para que Pages sea gratuito.
2. Sube el archivo `index.html` de esta carpeta a la raíz del repositorio (arrastrándolo desde la web de GitHub con "Add file → Upload files", o con `git push` si usas línea de comandos).
3. En el repositorio, ve a **Settings → Pages**.
4. En "Build and deployment", elige **Source: Deploy from a branch**, rama **main** (o `master`), carpeta **/ (root)**, y pulsa **Save**.
5. Espera 1-2 minutos. La web quedará publicada en:
   `https://TU-USUARIO.github.io/ranking-vacantes-murcia/`

## Actualizar la web más adelante

Si cambian los datos, solo tienes que volver a subir el `index.html` actualizado al repositorio (sobrescribiendo el anterior) y GitHub Pages lo republica solo.

## Archivos de esta carpeta

- `index.html` — la web (esta es la que sube a GitHub, GitHub Pages la sirve automáticamente por llamarse `index.html`).
- `ranking_vacantes_murcia.html` — copia idéntica, útil para abrir localmente por su nombre descriptivo.
