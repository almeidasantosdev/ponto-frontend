# Ponto Digital — frontend

Tela para o funcionário bater ponto e consultar o próprio histórico. Informa e-mail e senha, registra entrada ou saída e gera um relatório com tipo, data/hora e IP.

Feito em React, TypeScript e Vite. As chamadas vão para a API do repositório `ponto-backend` (`POST /punch` e `GET /report/:email`). A URL da API está fixa em `src/App.tsx` e precisa apontar para o backend publicado.

Versão publicada: https://pontofrontend.vercel.app

## Como rodar

```bash
npm install
npm run dev
```
