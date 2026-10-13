# Painel Ticket Manager — V45.3

Aplicação HTML estática e autocontida para demonstração e homologação do Painel Ticket Manager.

## Publicar pelo GitHub Pages

1. Envie `index.html`, `README.md` e `SECURITY.md` para a **raiz** do repositório (não envie este ZIP como substituto dos arquivos).
2. No GitHub, abra **Settings → Pages**.
3. Em **Build and deployment**, selecione **Deploy from a branch**.
4. Selecione a branch `main` e a pasta `/(root)` e clique em **Save**.
5. Aguarde a publicação. Para este repositório, o endereço esperado é https://leticiafolosino.github.io/pulse-360-dashboard/ .

## Escopo e limitações

- Este pacote é um único HTML, sem backend ou autenticação corporativa.
- Dados e preferências persistidos pelo navegador ficam no perfil/origem local de cada pessoa; não são compartilhados nem sincronizados entre usuários.
- Não é uma plataforma corporativa multiusuário e não deve receber chamados reais, dados pessoais, credenciais ou informações confidenciais. Use dados fictícios em demonstrações e testes.
- O repositório público deixa o código visível para qualquer pessoa. A publicação do site também é pública.
- A política de segurança do HTML bloqueia conexões de rede iniciadas pela aplicação (`connect-src 'none'`). Revise essa proteção antes de qualquer alteração.

## Release

- Versão: V45.3 — Inteligência com Cor
- HTML validado por hash SHA-256 do pacote de origem: `9d1def67e0099a6860e46045c620dcdcbd38aff5a4de82ac6f0fe67f75ace629`
- O hash confirma a integridade do arquivo em relação ao manifesto do pacote fornecido; não substitui testes funcionais no navegador.
- Nenhuma licença de redistribuição foi definida.
