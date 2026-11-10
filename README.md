# Consultorio Dental Sonrisa Clara

Página de una sola pantalla para agendar, confirmar o reprogramar citas por WhatsApp.

- Sitio estático: un solo archivo `index.html`, sin dependencias ni paso de compilación.
- No guarda datos. Los formularios solo abren un enlace `wa.me` con el mensaje redactado.
- Para cambiar el número de WhatsApp, edita la constante `PHONE` al final de `index.html`.

## Publicar en Vercel
1. Sube esta carpeta a un repositorio de GitHub.
2. En Vercel: Add New → Project → importa el repositorio.
3. Framework Preset: **Other**. Deja vacíos Build Command y Output Directory.
4. Deploy.
