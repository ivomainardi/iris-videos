# iris-videos

Vídeos das lições do **Aprender o Iris** (treinamento em níveis do Iris, visualizador IFC).

- `aprender/<lição>.mp4`: a lição rodando no Iris, com narração, capítulos e legenda embutida
- `aprender/<lição>.vtt` e `.srt`: legenda
- `aprender/videos.json`: lista das lições com vídeo (o Iris lê esta lista)

Publicado pelo GitHub Pages em https://ivomainardi.github.io/iris-videos/aprender/ — é daí que o Iris web e desktop abrem os vídeos.
Os vídeos são gerados por `tools/gerar_videos.py` no repositório do Iris; vídeo novo ou refeito: copiar `videos/aprender/` para `aprender/` aqui.
