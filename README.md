# Vídeos de execução · AnabTech

Arquivos de vídeo dos exercícios usados pelo aplicativo da AnabTech.
Este repositório só guarda os vídeos; o aplicativo fica em `anabtech/anabtech.github.io`.

## O que há aqui

- `<exercício>.mp4`: vídeo de execução (1080×1920, H.264, sem áudio), gerado pelo estúdio 3D do app (`app/3d/estudio.html?lote=1`) e comprimido com x264 (`-preset medium -crf 26.5 -tune animation -movflags +faststart`).
- `<exercício>.jpg`: capa (540×960), o mesmo quadro que o estúdio usa como capa.
- `indice.json`: lista dos vídeos, com tamanho e duração, e a versão do 3D (`3d-v5`).

Endereço público: `https://anabtech.github.io/videos/<exercício>.mp4`.
