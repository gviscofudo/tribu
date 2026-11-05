# tribu

App social gastronómica: lista de antojos por tribu, salidas grupales con cupo, reseñas con sliders y ranking mensual.

## Archivos

| Archivo | Para qué |
|---|---|
| `index.html` | La app completa |
| `icon.svg` | Favicon e ícono vectorial |
| `icon-192.png`, `icon-512.png` | Íconos para Android y para compartir |
| `apple-touch-icon.png` | Ícono al agregar la app a la pantalla de inicio del iPhone |
| `logo.svg` | Isologotipo (cardón verde + "ribu") para usar fuera de la app |

Subí todos los archivos juntos a la raíz del repositorio.

## Publicar en GitHub Pages

1. Subí los archivos a la raíz del repo.
2. **Settings → Pages → Source: Deploy from a branch**, rama `main`, carpeta `/ (root)`.
3. En uno o dos minutos queda online en `https://<usuario>.github.io/<repo>/`.

## Identidad

- Verde cardón `#2F7D4A` (en modo oscuro `#5FAE77`), negro `#111111`, fondo `#FAFAF7`.
- Tipografía: Barlow 800 para la marca, Barlow 400–700 para la interfaz.

## Modo de datos

En GitHub Pages la app funciona en modo demo: los datos se guardan solo en el dispositivo de cada persona y arranca con tribus y locales de Palermo y Villa Crespo precargados. Para que sea multiusuario hace falta conectar un backend (por ejemplo, Supabase).
