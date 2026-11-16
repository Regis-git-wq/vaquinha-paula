# Site da vaquinha da Paula (paulaprotese-vaquinha.com.br)

Site estático de arrecadação para a prótese da Paula (R$ 280.000). Uma página única
`index.html` (HTML+CSS+JS juntos, sem build), pasta `img/` e `_headers` (segurança
Netlify). Criado no app Claude em nov/2026; contexto completo no doc
"claude/handoff-site-vaquinha.md" do projeto "Site Tia Paula" no claude.ai.

## Regras importantes
- NUNCA alterar chave PIX, titular ou dados bancários sem pedido explícito:
  PIX paulagalvaofortes@hotmail.com · Paula Fernanda Galvão Andrade Fortes · BB ag 44-2 c/c 270169-3 var 51.
- O gerador de Pix Copia e Cola (BR Code + CRC16, cidade TERESINA) foi validado
  contra o exemplo oficial do Banco Central; se mexer, revalidar e ler o QR de volta.
- `_headers` tem a CSP; precisa subir em todo deploy. Se adicionar origem externa
  nova, liberar na CSP.
- Barra de progresso lê CSV publicado da planilha Google (SHEET_CSV_URL no JS);
  só a aba "Site" é publicada, para não expor nomes de doadores. Fallback fixo FALLBACK.
- Não hospedar no GitHub (conta antiga suspensa); deploy é manual na Netlify:
  projeto paulaprotese-vaquinha → Deploys → arrastar a pasta.
- Design: DESIGN.md na raiz (areia #FBF7F1, teal #0F6B6B, laranja #C2541F só no
  progresso, Fraunces + Nunito Sans). Animações respeitam prefers-reduced-motion;
  topo e seção de doação ficam sem animação.
- Texto da história é relato da própria Paula: não reescrever nem inventar fatos.
