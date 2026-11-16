# Espia só · protótipo

Protótipo funcional do Espia só, a plataforma de link na bio da Marketing Vision.

Tem página de vendas, cadastro, painel do cliente (editor, aparência, métricas e plano), página pública da bio e painel ADM.

## Como funciona fora do Claude

O site é um único arquivo `index.html`, sem build. Fora do Claude os dados ficam salvos no navegador de quem está usando (localStorage). Cada pessoa vê só os próprios cadastros, então o painel ADM mostra apenas o que foi criado naquele navegador.

## Publicação

Hospedado na Vercel a partir deste repositório. Cada push na branch `main` gera uma nova versão do site.
