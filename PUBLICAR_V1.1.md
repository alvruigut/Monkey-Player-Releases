# Publicar Monkey Player v1.1

## 1. Contenido que sí debe quedar en el repositorio

Sube/commitea a la rama `main` del repositorio público:

- `README.md`

La carpeta `release-assets/` se entrega aquí como área de preparación. No es necesario mantener estos binarios dentro del historial Git.

## 2. Crear la Release

En GitHub:

1. Abre `alvruigut/Monkey-Player-Releases`.
2. Entra en **Releases**.
3. Pulsa **Draft a new release**.
4. Crea el tag `v1.1` apuntando a `main`.
5. Título: `Monkey Player v1.1`.
6. Usa como descripción el contenido de `release-assets/v1.1/RELEASE_NOTES.md`.
7. Adjunta estos cinco archivos de `release-assets/v1.1/`:
   - `Monkey-Player-Windows.exe`
   - `Monkey-Player-Android.apk`
   - `Monkey-Player-FireTV.apk`
   - `checksums.txt`
   - `release-manifest.json`
8. Publica la Release como estable, no prerelease.

## 3. URLs que usará el actualizador

La API pública de la última Release será:

`https://api.github.com/repos/alvruigut/Monkey-Player-Releases/releases/latest`

Los binarios de v1.1 tendrán URLs estables con este patrón:

- `https://github.com/alvruigut/Monkey-Player-Releases/releases/download/v1.1/Monkey-Player-Windows.exe`
- `https://github.com/alvruigut/Monkey-Player-Releases/releases/download/v1.1/Monkey-Player-Android.apk`
- `https://github.com/alvruigut/Monkey-Player-Releases/releases/download/v1.1/Monkey-Player-FireTV.apk`

No cambies estos nombres de archivo en futuras Releases; el actualizador podrá seleccionar el binario por nombre y plataforma.
