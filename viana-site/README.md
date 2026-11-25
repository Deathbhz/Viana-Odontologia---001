# Viana Odontologia — Site institucional

Site de uma página (`index.html`) pronto para publicar no GitHub Pages.

## Como publicar no GitHub Pages
1. Crie um repositório novo no GitHub (ex: `viana-odontologia`).
2. Suba todos os arquivos desta pasta (`index.html` e a pasta `assets/`) para o repositório.
3. No repositório, vá em **Settings → Pages**.
4. Em "Branch", selecione `main` (ou `master`) e a pasta `/root`, depois salve.
5. Em alguns minutos o site estará disponível em `https://SEU-USUARIO.github.io/viana-odontologia/`.

## O que personalizar depois
- **CRO e CNPJ**: no rodapé, troque `CRO-[UF] [00000]` pelos dados reais da responsável técnica.
- **Depoimentos**: a seção "Depoimentos" usa textos de exemplo — substitua por relatos reais de pacientes, sempre com autorização por escrito.
- **WhatsApp**: os links já usam o número (31) 98829-2839. Se mudar o número, atualize todos os `https://wa.me/55...` no arquivo `index.html`.
- **Fotos**: estão em `assets/img/`. Para trocar, basta substituir o arquivo mantendo o mesmo nome, ou editar o `src` no HTML.

## Estrutura
```
index.html
assets/
  img/
    dentista-foto.png      → foto da Dra. Fê Viana (hero)
    botox-post.png         → card "Botox na odontologia"
    fio-dental-post.png    → card "Dicas da Tia Fê" (fio dental infantil)
    logo-viana.png         → logo completa (ícone + nome)
    logo-icon-transparent.png → apenas o ícone, fundo transparente (usado no header/rodapé)
```
