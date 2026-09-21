# Álbum UIB — APK Android personal

Proyecto Android muy sencillo que envuelve el HTML del álbum en un WebView.

## Qué hace
- Usa el `index.html` del álbum como pantalla principal.
- Mantiene JavaScript y `localStorage`.
- Permite seleccionar fotografías desde el móvil.
- Necesita Internet para cargar Tailwind y las fuentes externas que utiliza el HTML original.
- Genera un APK Debug instalable en un móvil Android. No está preparado para publicación en Google Play.

## Generación desde GitHub
El workflow `.github/workflows/build-apk.yml` genera `app-debug.apk` en GitHub Actions y lo guarda como Artifact.
