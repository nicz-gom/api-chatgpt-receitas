passa a passo para subir

- criar .env e pegar a key na api do gpt
- npm install
- npm run dev
como testar (via terminal):
Invoke-RestMethod -Method Post -Uri http://localhost:3001/api/receitas/perguntar -ContentType "application/json" -Body '{"pergunta":"frango"}'
