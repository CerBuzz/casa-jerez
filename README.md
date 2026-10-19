# Casa Jerez — alquiler temporal

Dashboard para decidir un alquiler en Jerez de la Frontera (1 nov 2026 – 1 ene 2027).

**URL prevista:** https://cerbuzz.github.io/casa-jerez/

## Uso
1. Abrir la URL en el móvil.
2. Escribir los dos nombres y elegir **¿Quién eres?**
3. Votar / comentar: se sincroniza sola cada ~20 s (MantleDB). Sin login.

## Activar GitHub Pages (una sola vez)
Si el sitio aún no carga, en GitHub:
1. Abrir https://github.com/CerBuzz/casa-jerez/settings/pages
2. En **Build and deployment → Source** elegir **GitHub Actions**
3. Ir a Actions → *Deploy GitHub Pages* → **Run workflow**

## Privacidad
El HTML incluye una clave de escritura que **solo** permite leer/escribir el documento de votos en MantleDB (namespace `casa-jerez-…`). No hay tokens de GitHub ni de Google.
