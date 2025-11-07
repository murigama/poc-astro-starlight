---
title: Teste de Vídeo
description: Exemplo de como incorporar vídeos na documentação
---

Este é um exemplo de página de teste para demonstrar como incorporar vídeos na documentação.

## Vídeo Local

Para vídeos armazenados localmente, você pode usar a tag HTML `<video>`:

<video controls width="100%">
  <source src="../../assets/exemplo.mp4" type="video/mp4">
  Seu navegador não suporta o elemento de vídeo.
</video>

## Vídeo do YouTube

Para incorporar vídeos do YouTube, você pode usar um iframe:

<iframe 
  width="100%" 
  height="400" 
  src="https://www.youtube.com/embed/dQw4w9WgXcQ" 
  title="YouTube video player" 
  frameborder="0" 
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
  allowfullscreen>
</iframe>

## Vídeo do Vimeo

Para incorporar vídeos do Vimeo:

<iframe 
  src="https://player.vimeo.com/video/148751763" 
  width="100%" 
  height="400" 
  frameborder="0" 
  allow="autoplay; fullscreen; picture-in-picture" 
  allowfullscreen>
</iframe>

## Notas

- Vídeos locais devem ser colocados na pasta `src/assets/` ou `public/`
- Para vídeos do YouTube/Vimeo, use o código de incorporação fornecido por essas plataformas
- Ajuste a altura (`height`) conforme necessário para melhor visualização
