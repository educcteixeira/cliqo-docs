# Cliqo Docs

Documentação oficial da API Cliqo — hospedada em `docs.cliqo.io` via Mintlify.

## Como rodar localmente

```bash
npm install -g mintlify
mintlify dev
```

Acesse `http://localhost:3000`

## Deploy

1. Crie uma conta em [mintlify.com](https://mintlify.com)
2. Conecte este repositório GitHub
3. Configure o domínio customizado: `docs.cliqo.io`
4. No Cloudflare: adicione CNAME `docs` → valor fornecido pelo Mintlify

## Estrutura

```
├── mint.json              # Configuração do site
├── introduction.mdx       # Página inicial
├── quickstart.mdx         # Primeiros passos
├── authentication.mdx     # Autenticação
├── api-reference/
│   ├── contacts/          # CRUD de contatos
│   ├── campaigns/         # Envio de campanhas
│   ├── templates/         # Templates AMP
│   ├── events/            # Webhooks e eventos
│   └── pixel/             # Pixel de rastreamento
├── guides/
│   ├── pixel-installation.mdx
│   ├── webhooks.mdx
│   ├── loja-integrada.mdx
│   └── whatsapp-trigger.mdx
└── sdks/
    ├── nodejs.mdx
    └── python.mdx
```
