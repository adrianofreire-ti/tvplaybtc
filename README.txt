PAINEL TV PLAYER - NETLIFY + GOOGLE DRIVE

1) O projeto já está configurado com a pasta do Google Drive informada:
https://drive.google.com/drive/folders/1r7z7bovTB66ELvgUJlGWNCIw7bZDP2eD?usp=sharing

2) IMPORTANTE:
O Google Drive não oferece, de forma estável para site estático, uma listagem pública anônima pronta em JSON da pasta.
Por isso, o player usa o arquivo playlist.json.

3) COMO USAR:
- Abra a pasta do Drive.
- Entre em cada arquivo e copie o ID.
- Edite o arquivo playlist.json.
- Substitua os valores COLE_AQUI... pelos IDs reais.

Exemplo:
Link do arquivo:
https://drive.google.com/file/d/1AbCdEfGhIjKlMnOpQrStUvWxYz/view?usp=sharing

ID do arquivo:
1AbCdEfGhIjKlMnOpQrStUvWxYz

Link que vai na playlist:
https://drive.google.com/uc?export=download&id=1AbCdEfGhIjKlMnOpQrStUvWxYz

4) ARQUIVOS DO PROJETO:
- index.html   -> player em tela cheia
- config.json  -> configurações gerais e URL da pasta do Drive
- playlist.json -> ordem das mídias
- netlify.toml -> ajustes básicos do deploy

5) PUBLICAR NO NETLIFY:
- Entre no Netlify
- Escolha deploy manual ou via GitHub
- Publique esta pasta

6) OBSERVAÇÃO FRANCA:
- A pasta do Drive foi incluída no projeto como referência/configuração.
- A montagem automática da playlist direto da pasta exigiria Google Drive API com credenciais ou um intermediário como Apps Script.
- Para começar sem enrolação, a playlist manual é o caminho mais estável.


Primeira mídia já configurada na playlist:
https://drive.google.com/file/d/1uHw7g4e1I4S9GwbVElcFefnorD8rKgGE
