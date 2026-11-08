# smyldesign.ai

Sitio público de SMYL (landing, aviso de privacidad y términos), servido con GitHub Pages en `smyldesign.ai`.

La aplicación vive en `app.smyldesign.ai` (repositorio `camila`). Al cambiar el aviso de privacidad o los términos, actualizar ambos repositorios.

## Despliegue

- GitHub Pages: Settings → Pages → *Deploy from a branch* → `main` / root. El dominio viene de `CNAME`.
- DNS (Hostinger): registros **A** en `@` → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153;
  **CNAME** `www` → `rpartidaislas-cloud.github.io`. El CNAME de `app` pertenece al panel y no se toca.
- Tras propagar el DNS, marcar *Enforce HTTPS* en Pages.
