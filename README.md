# Bola 22 Mágica — PWA + Capacitor

Esta rama contiene una versión mínima lista para PWA y para compilar con Capacitor.

Probar en el navegador (rápido):
1. Abre `www/index.html` en tu navegador o usa RawGit/RawGithack si el repo es público:
   https://raw.githack.com/oteodavid22-beep/Bola-22-m-gica2/main/www/index.html

Habilitar GitHub Pages (recomendado para probar PWA):
- Repo → Settings → Pages → Source → branch: `main` folder: `/ (root)` → Save.

Compilar en Android (requiere PC):
1. Instalar dependencias: `npm install @capacitor/core @capacitor/cli`
2. Inicializar (si no lo has hecho): `npx cap init "Bola22" com.oteodavid22.bola22`
3. Añadir Android: `npx cap add android`
4. Copiar web assets: `npx cap copy`
5. Abrir Android Studio: `npx cap open android` y compilar/run.

Si quieres, puedo
- activar Pages por ti (si me das permiso),
- o crear una rama para añadir cambios y pruebas.
