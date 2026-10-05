# Géométrique

Outil web qui transforme une photo ou une vidéo en œuvre géométrique : contours, symboles, liens, contours lumineux, dither, pixel memory, grilles, chaînes de cercles, détection de personnes et réaction au son. Pensé pour les visuels et Reels Instagram du Bar du Crystal.

Tout est traité sur l'appareil : les photos, vidéos et sons ne sont envoyés nulle part.

## Ouvrir l'outil

https://joceleralouf.github.io/geometrique/

## Ce qui demande Internet

La détection de personnes et de visages charge les modèles MediaPipe de Google (environ 15 Mo) au premier usage. Le reste fonctionne même hors ligne une fois la page chargée.

## Limites

- Image : JPG, PNG, WEBP
- Vidéo : MP4, MOV, WEBM, 15 s et 100 Mo maximum
- Son : MP3, WAV, M4A, 3 min et 15 Mo maximum
- Export vidéo : 3, 5, 8 ou 10 s, 1080 px de large maximum, avec ou sans le son
