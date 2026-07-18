# Modelo 01 — Eventos Direto com Opções, Vídeo e Fade

Mantém o mesmo visual simples aprovado, com apenas duas mudanças:

- fade suave ao abrir e fechar a tela de opções;
- vídeo opcional por equipamento.

## Demonstração
A Plataforma 360 possui um vídeo local demonstrativo.
Os demais equipamentos não mostram área de vídeo.

## Como cadastrar vídeo
No objeto `PRODUCTS`, em `script.js`, adicione:

```js
video: "assets/videos/nome-do-video.mp4",
```

Quando a propriedade `video` não existir, o botão e a área de vídeo não aparecem.

## WhatsApp
Altere `TEMPLATE_CONFIG.whatsapp` no início de `script.js`.


## Publicação
Este pacote foi gerado pelo LA Generator 4.4. Envie TODO o conteúdo desta pasta para a raiz do repositório do GitHub Pages. O arquivo index.html já está na raiz.
