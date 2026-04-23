# Videos — Cerrajería Móvil Tijuana

Coloca aquí los archivos de video en formato MP4 (vertical, 9:16).

## Archivos esperados

| Archivo         | Descripción                                       |
|-----------------|---------------------------------------------------|
| `video1.mp4`    | Apertura de auto — servicio sin daño al vehículo  |
| `video2.mp4`    | Programación de llave con chip                    |
| `video3.mp4`    | Clonación de control de acceso                    |
| `video4.mp4`    | Llaves de proximidad                              |
| `comercial.mp4` | Comercial de Cerrajería Móvil Tijuana             |

## Recomendaciones técnicas

- **Formato:** MP4 (H.264 + AAC)
- **Resolución:** 1080 × 1920 px (9:16 vertical)
- **Peso máximo recomendado:** 15 MB por video (para carga rápida en móvil)
- **Comprimir con:** HandBrake o ffmpeg antes de subir

### Comprimir con ffmpeg (ejemplo)
```bash
ffmpeg -i entrada.mp4 -vcodec libx264 -crf 28 -preset fast -movflags +faststart salida.mp4
```

## Para agregar más videos

1. Agrega el archivo `.mp4` a esta carpeta.
2. Copia un bloque `<div class="vcard">` en `index.html` dentro de `#videoReelTrack` y actualiza el `src`.
