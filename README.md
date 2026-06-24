# Agente de Atendimento n8n

Workflow n8n para atendimento automatizado via WhatsApp, com qualificacao de leads, consulta/registro em Google Sheets e uso de modelos OpenAI.

## Conteudo

- `Agente de Atendimento especialiizado.json`: export sanitizado do workflow n8n.
- `.env.example`: lista dos valores que precisam ser configurados no ambiente/n8n.

## Antes de importar

Este repositorio nao contem credenciais reais. Os valores sensiveis foram substituidos por placeholders:

- `REPLACE_WITH_ZAPI_INSTANCE_ID`
- `REPLACE_WITH_ZAPI_TOKEN`
- `REPLACE_WITH_GOOGLE_SHEET_ID`
- `REPLACE_WITH_OPENAI_CREDENTIAL_ID`
- `REPLACE_WITH_GOOGLE_SHEETS_CREDENTIAL_ID`
- `REPLACE_WITH_N8N_WEBHOOK_ID`
- `REPLACE_WITH_SELLER_WHATSAPP_NUMBER`
- `REPLACE_WITH_N8N_INSTANCE_ID`

Depois de importar o workflow no n8n, recrie ou selecione as credenciais reais dentro do proprio n8n.

## Seguranca

Nao publique tokens, chaves de API, arquivos `.env`, exports com credenciais reais ou URLs contendo tokens.

Antes de publicar alteracoes, rode uma busca por termos sensiveis como `token`, `secret`, `password`, `senha`, `authorization` e `api_key`.
