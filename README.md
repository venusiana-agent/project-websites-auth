# Venusiana App — site de conformidade OAuth

Site estático para `https://venusiana-app.soberania.cloud`.

## Rotas

- `/` — homepage institucional
- `/privacy` — política de privacidade
- `/terms` — termos de serviço

## Publicação

Publique o conteúdo desta pasta em uma hospedagem HTTPS e configure o DNS do subdomínio. As rotas `/privacy` e `/terms` possuem `index.html` próprio para funcionar em hospedagem estática sem regras especiais.

No Google Cloud:

1. Verifique `soberania.cloud` (ou o subdomínio) no Google Search Console.
2. Cadastre o domínio em **Authorized domains**.
3. Use exatamente estas URLs no Google Auth Platform → Branding:
   - `https://venusiana-app.soberania.cloud/`
   - `https://venusiana-app.soberania.cloud/privacy`
   - `https://venusiana-app.soberania.cloud/terms`
4. Confirme que os serviços e escopos solicitados pelo app correspondem ao texto publicado.

## Revisão obrigatória antes de produção

- Confirmar a identificação jurídica do operador do app na política.
- Confirmar os serviços Google/escopos realmente usados.
- Confirmar que `jarbas@agents.soberania.cloud` é monitorado para suporte e solicitações de privacidade.
- Revisar o conteúdo jurídico com o responsável da Venusiana.
