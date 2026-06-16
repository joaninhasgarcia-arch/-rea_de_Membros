# Área de Membros — Valentes na Fé

Arquivos incluídos:
- `index.html`: página final da área de membros.
- `README.md`: instruções rápidas.

## O que foi ajustado

- Removido o modelo de página dentro de celular.
- Removidas as áreas de suporte e “Bem-vindo ao material”.
- Mantido o topo “Área de Membros Exclusiva” e o selo “Acesso liberado”.
- Mantidas as instruções em 3 passos.
- Álbum e figurinhas ficaram juntos em um único card: “Álbum Valentes na Fé + Figurinhas”.
- Cada bônus recebeu a capa correta, sem imagens repetidas.

## Como colocar os links dos arquivos

Abra o arquivo `index.html` e procure esta parte:

```js
const DOWNLOAD_LINKS = {
  album: "COLE_AQUI_O_LINK_DO_ALBUM_E_FIGURINHAS",
  memoria: "COLE_AQUI_O_LINK_DO_JOGO_DA_MEMORIA",
  desafio: "COLE_AQUI_O_LINK_DO_DESAFIO_7_DIAS",
  colorir: "COLE_AQUI_O_LINK_DOS_VERSICULOS_PARA_COLORIR"
};
```

Troque cada texto pelo link real do Google Drive, Dropbox ou outra hospedagem.

Depois disso, envie o `index.html` para sua hospedagem ou construtor de página.
