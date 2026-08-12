# 🚀 Guía Paso a Paso: Cómo subir tu Portfolio a GitHub y Publicarlo Gratis

Esta guía contiene los comandos exactos que debes ejecutar en tu terminal para subir este proyecto a tu cuenta de GitHub y activar la web pública en **GitHub Pages**.

---

## 📋 Paso 1: Crear un nuevo repositorio en GitHub

1. Entra en tu cuenta de [GitHub](https://github.com/).
2. Haz clic en el botón **"+"** (arriba a la derecha) y selecciona **"New repository"**.
3. Rellena los datos:
   - **Repository name:** `PORTFOLIO` (o el nombre que prefieras).
   - **Description:** `Portfolio oficial de DJOKOBEATZ - Beats, Producción Musical & Desarrollo Web`.
   - **Public / Private:** Elige **Public** (para que se pueda ver en GitHub Pages).
   - **Initialize repository:** Deja desmarcadas las casillas de README, .gitignore y License (ya los hemos creado localmente).
4. Haz clic en **"Create repository"**.

---

## 💻 Paso 2: Ejecutar los comandos Git en tu terminal

Abre la terminal en la carpeta de este proyecto (`/Users/djokobeatz/CODE PROYECTS/PORTFOLIO`) y ejecuta las siguientes instrucciones una por una:

```bash
# 1. Inicializar el repositorio local
git init

# 2. Configurar tu identidad en Git
git config --global user.name "Pablo Sancho"
git config --global user.email "pablo96sancho@gmail.com"

# 3. Asegurar que la rama principal se llame main
git branch -M main

# 4. Añadir todos los archivos al seguimiento de git
git add .

# 5. Crear el primer commit
git commit -m "feat: versión inicial del portfolio web responsivo y documentación profesional"

# 6. Enlazar tu repositorio local con GitHub
git remote add origin https://github.com/Pablo96sancho/PORTFOLIO.git

# 7. Subir tus archivos a GitHub
git push -u origin main
```

---

## 🌐 Paso 3: Activar GitHub Pages (Tu web en internet)

Gracias al archivo `.github/workflows/deploy.yml` que hemos creado, la publicación es automática:

1. Entra a tu repositorio en GitHub.
2. Ve a la pestaña **Settings** (Configuración) > **Pages**.
3. En la sección **Build and deployment > Source**, cambia el desplegable a **GitHub Actions**.
4. En cuestión de 1-2 minutos, tu página web estará disponible públicamente en la URL:
   `https://Pablo96sancho.github.io/PORTFOLIO/`

---

## 🔄 Paso 4: Cómo actualizar tu portfolio en el futuro

Cada vez que hagas cambios en el código (por ejemplo, añadir un nuevo beat o modificar un texto):

```bash
git add .
git commit -m "update: descripción de los cambios realizados"
git push
```

¡GitHub Actions actualizará automáticamente tu web desplegada!
