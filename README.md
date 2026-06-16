# Área de Membros — Valentes na Fé

Mini site estático pronto para publicar no GitHub e conectar na Vercel.

## Arquivos

- `index.html` — página principal da área de membros.
- `README.md` — instruções de publicação e edição.

## Como configurar os links de download

Abra o arquivo `index.html` e procure por este trecho:

```js
const DOWNLOAD_LINKS = {
  album: "COLE_AQUI_O_LINK_DO_ALBUM_PDF",
  figurinhas: "COLE_AQUI_O_LINK_DAS_FIGURINHAS",
  memoria: "COLE_AQUI_O_LINK_DO_JOGO_DA_MEMORIA",
  desafio: "COLE_AQUI_O_LINK_DO_DESAFIO_7_DIAS",
  colorir: "COLE_AQUI_O_LINK_DOS_VERSICULOS_PARA_COLORIR",
  suporte: "https://wa.me/55SEUNUMEROAQUI"
};
```

Substitua cada texto pelo link real do arquivo no Google Drive, Dropbox ou outra hospedagem.

## Dica para usar Google Drive

1. Suba os PDFs no Google Drive.
2. Clique com o botão direito no arquivo.
3. Escolha **Compartilhar**.
4. Altere para **Qualquer pessoa com o link**.
5. Copie o link e cole no `index.html`.

## Como publicar no GitHub

1. Crie um repositório novo.
2. Envie `index.html` e `README.md` para a raiz do repositório.
3. Faça o commit.

## Como publicar na Vercel

1. Acesse a Vercel.
2. Clique em **Add New Project**.
3. Importe o repositório do GitHub.
4. Selecione **Other** ou **Static HTML**.
5. Publique.

## Observação

As imagens principais já estão embutidas no `index.html`, então não precisa subir uma pasta de imagens separada.
