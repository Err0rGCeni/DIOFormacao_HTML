# Trabalhando com Mídias

- `<img>`: Inserção de imagem no documento.
  - _src_: Endereço da imagem.
  - _title_: Mensagem exibida ao passar o mouse em cima,
  - _alt_: Texto a ser lido por ferramentas de acessibilidade.
- `<audio></audio>`: Inserção de aúdio no documento.
  - _src_ ou `<source />`: Endereço do aúdio.
  - _controls_: Exibe controles para a execução.
  - _autoplay_: Se especificado, o áudio iniciará automaticamente.
  - _loop_: Se especificado, o aúdio executará em loop.
- `<video>`: Inserção de vídeo no documento.
  - _src_ ou `<source />`: Endereço do vídeo.
    - Múltiplos source permitem carregar vídeos alternativos em caso de incompatibilidade.
  - _controls_: Exibe controles para a execução.
- `<track />`: Tag filha de `video` ou `audio` que permite que especificar faixas de texto temporizadas.
  - _src_: Endereço do arquivo (.vtt);
  - _kind_: Como o texto deve ser usado.
    - _subtitles_: Legendas de informações que podem não ser entendidas pelo usuário, e/ou informações extras.
    - _captions_: Transcrição e possivelmente uma tradução do áudio.
    - _descriptions_: Descrição textual do vídeo, útil para acessibilidade.
    - _chapters_: Navegação.
  - _srclang_: Idioma da legenda (track), selecionável.
- `<iframe />`: Incorpora páginas externas (ex: Youtube).

## Notas

- **JPEG**: O formato JPEG usa compactação com perdas, ou seja, alguns dados da imagem são excluídos permanentemente durante a redução.
- **PNG**: Os arquivos PNG se beneficiam da compactação sem perdas. Um recurso que os PNGs oferecem e os JPEGs não é a capacidade de lidar com gráficos que têm fundos transparentes.
