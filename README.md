# Sabor sin Culpa — página web

Este paquete contiene una copia estática e independiente de la página. Incluye `index.html` y la carpeta `assets/` con las imágenes, la portada del libro y el logotipo. No necesita Manus, un servidor propio ni instalar dependencias: GitHub Pages puede publicar estos archivos tal como están.

## Publicarla desde tu cuenta de GitHub

1. Descarga y descomprime el ZIP. Dentro de la carpeta `sabor-sin-culpa-web` verás `index.html`, este README y `assets/`.
2. Entra a [GitHub](https://github.com), inicia sesión y crea un repositorio nuevo para la página, por ejemplo `sabor-sin-culpa`. Si tu cuenta usa el plan Free, usa un repositorio público para publicarlo con GitHub Pages; la publicación desde repositorios privados depende del plan.
3. En el repositorio, elige **Add file → Upload files** y arrastra `index.html`, `README.md` y la carpeta `assets/` desde la carpeta descomprimida. Deja `index.html` directamente en la raíz del repositorio y conserva `assets/` como carpeta al mismo nivel. Escribe un mensaje como `Agregar página Sabor sin Culpa` y pulsa **Commit changes**.
4. En el repositorio, abre **Settings → Pages**. En **Build and deployment**, elige **Deploy from a branch**, selecciona la rama `main` y la carpeta `/(root)`, y pulsa **Save**. GitHub publicará los archivos de esa rama y carpeta.
5. Vuelve a **Settings → Pages** para copiar la dirección que GitHub asigna a tu sitio. El primer despliegue puede tardar unos minutos.

La página conserva los botones de compra conectados al checkout actual de Hotmart. Los archivos y la configuración del repositorio quedarán en tu cuenta; podrás editarlos o retirarlos desde allí.

## Usar un dominio propio (opcional)

Necesitas registrar o tener ya un dominio. En **Settings → Pages**, escribe tu dominio personalizado y guarda primero ese cambio. Después configura el DNS en el sitio donde administras el dominio. Para un subdominio como `www.tudominio.com`, crea un registro `CNAME` que apunte a `TU-USUARIO.github.io` (sin el nombre del repositorio). Para un dominio raíz como `tudominio.com`, GitHub indica los registros `A` correspondientes. Cuando GitHub valide el dominio, puedes activar **Enforce HTTPS**. La propagación de DNS puede tardar hasta 24 horas.

Consulta las instrucciones oficiales antes de cambiar los DNS:

- [Publicar GitHub Pages desde una rama](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
- [Configurar un dominio personalizado en GitHub Pages](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site)
- [Subir archivos o carpetas desde la web de GitHub](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)
