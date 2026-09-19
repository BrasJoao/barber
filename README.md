# Borges Barber

Site estático pronto para publicação em Vercel ou Netlify.

## Estrutura
- `index.html` — página principal
- `style.css` — estilos
- `assets/` — coloque aqui as fotos

## Fotos
Use estes nomes para substituir os placeholders:
- `hero.jpg`
- `corte-1.jpg` até `corte-6.jpg`
- `barbearia-1.jpg`

Para ativar as fotos, basta trocar os blocos `.image-placeholder` do HTML por:
`<img src="assets/nome-da-foto.jpg" alt="Descrição">`

## Publicação
### Vercel
1. Crie um repositório no GitHub e envie os arquivos.
2. Entre na Vercel e importe o repositório.
3. Framework Preset: **Other**.
4. Build Command: deixe vazio.
5. Output Directory: `.`
6. Deploy.

### Netlify
1. Crie um repositório no GitHub e envie os arquivos.
2. No Netlify, escolha **Add new site > Import an existing project**.
3. Selecione o repositório.
4. Build command: deixe vazio.
5. Publish directory: `.`
6. Deploy.

Não há backend ou banco de dados: o agendamento é feito diretamente pelo WhatsApp.
