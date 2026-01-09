# Monitora API - Documentação Oficial

<p align="center">
  <img src="https://img.shields.io/badge/Mintlify-Powered-mint?style=for-the-badge" alt="Mintlify">
  <img src="https://img.shields.io/badge/API-v1.0-blue?style=for-the-badge" alt="API Version">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/Status-Production-success?style=for-the-badge" alt="Status">
</p>

Documentação completa e interativa da **Monitora API** - A plataforma definitiva para gerenciamento de grupos do WhatsApp, campanhas de marketing e monitoramento automatizado.

🔗 **[Acessar Documentação](https://docs.monitoragrupo.com)** | 🚀 **[Dashboard](https://dashboard.monitoragrupo.com)** | 💬 **[Suporte](mailto:support@monitoragrupo.com)**

---

## 🎯 Sobre o Projeto

A Monitora API oferece uma solução robusta para:

- **Gestão de Grupos WhatsApp**: Monitore capacidade, status e saúde de grupos em tempo real
- **SmartLinks**: Crie links inteligentes com rotação automática de grupos
- **Monitoramento 24/7**: Configure alertas e receba notificações instantâneas
- **Análise de Campanhas**: Acompanhe métricas, conversões e performance
- **Automação Completa**: Webhooks, auto-rotação, validação de links e mais

## 📚 Estrutura da Documentação

```
docs/
├── 📖 introduction/              # Introdução e Getting Started
│   ├── overview.mdx             # Visão geral da plataforma
│   └── getting-started.mdx      # Primeiros passos e setup inicial
│
├── 🔐 authentication/            # Autenticação e Segurança
│   ├── overview.mdx             # Métodos de autenticação
│   ├── api-keys.mdx             # Gerenciamento de API Keys
│   └── oauth.mdx                # Fluxo OAuth 2.0
│
├── 📘 guides/                    # Guias Práticos
│   ├── quickstart.mdx           # Início rápido em 5 minutos
│   ├── best-practices.mdx       # Melhores práticas e otimização
│   ├── rate-limits.mdx          # Limites e quotas
│   └── code-examples.mdx        # Exemplos de código completos
│
├── 🔌 webhooks/                  # Webhooks e Eventos
│   └── overview.mdx             # Configuração e exemplos
│
├── ⚠️ errors/                     # Tratamento de Erros
│   └── overview.mdx             # Códigos HTTP e troubleshooting
│
├── 🚀 api-reference/             # Referência Completa da API
│   ├── overview.mdx             # Visão geral de todos endpoints
│   │
│   ├── 🔑 auth/                  # Autenticação (4 endpoints)
│   │   ├── overview.mdx         # Resumo de autenticação
│   │   ├── login.mdx            # POST /auth/login
│   │   ├── logout.mdx           # POST /auth/logout
│   │   ├── refresh.mdx          # POST /auth/refresh
│   │   └── me.mdx               # GET /auth/me
│   │
│   ├── 👤 accounts/              # Contas (3 endpoints)
│   │   ├── overview.mdx         # Resumo de contas
│   │   ├── usage.mdx            # GET /accounts/usage
│   │   ├── list-adaccounts.mdx  # GET /accounts/adaccounts
│   │   └── create-facebook.mdx  # POST /accounts/facebook
│   │
│   ├── 📊 campaigns/             # Campanhas (1 endpoint)
│   │   ├── overview.mdx         # Resumo de campanhas
│   │   └── list-groups.mdx      # GET /campaigns/{id}/groups
│   │
│   ├── 👥 groups/                # Grupos (1 endpoint)
│   │   ├── overview.mdx         # Resumo de grupos
│   │   └── update-image.mdx     # PUT /groups/{id}/image
│   │
│   ├── 📡 monitors/              # Monitores (5 endpoints)
│   │   ├── overview.mdx         # Resumo de monitoramento
│   │   ├── list.mdx             # GET /monitors
│   │   ├── create.mdx           # POST /monitors
│   │   ├── update.mdx           # PUT /monitors/{id}
│   │   ├── delete.mdx           # DELETE /monitors/{id}
│   │   └── insights.mdx         # GET /monitors/{id}/insights
│   │
│   ├── 🔗 smartlinks/            # SmartLinks (5 páginas)
│   │   ├── overview.mdx         # Resumo de SmartLinks
│   │   ├── validate.mdx         # POST /smartlinks/validate
│   │   ├── get-campaign.mdx     # GET /smartlinks
│   │   ├── update-details.mdx   # PUT /smartlinks/{code}/details
│   │   └── activities.mdx       # GET /smartlinks/campaign/{id}/activities
│   │
│   ├── 💰 credits/               # Créditos (2 endpoints)
│   │   ├── overview.mdx         # Resumo de créditos
│   │   ├── history.mdx          # GET /credits/history
│   │   └── breakdown.mdx        # GET /credits/breakdown
│   │
│   ├── 🚨 incidents/             # Incidentes (4 endpoints)
│   │   ├── overview.mdx         # Resumo de incidentes
│   │   ├── monitors.mdx         # GET /incidents/monitors
│   │   ├── monitors-stats.mdx   # GET /incidents/monitors/stats
│   │   ├── links.mdx            # GET /incidents/links
│   │   └── links-stats.mdx      # GET /incidents/links/stats
│   │
│   └── 💳 subscriptions/         # Assinaturas (3 endpoints)
│       ├── overview.mdx         # Resumo de planos
│       ├── status.mdx           # GET /subscriptions/status
│       ├── checkout.mdx         # POST /subscriptions/checkout
│       └── portal.mdx           # POST /subscriptions/portal
│
├── 📝 changelog.mdx              # Histórico de versões
├── ⚙️ docs.json                  # Configuração Mintlify
└── 📄 openapi.json               # Especificação OpenAPI (futuro)
```

## ✨ Recursos Principais

### 📖 Documentação Completa
- ✅ **40+ Páginas** de documentação detalhada
- ✅ **8 Grupos de Endpoints** organizados por funcionalidade
- ✅ **Playground Interativo** em todos os endpoints (testável na própria documentação)
- ✅ **Exemplos de Código** em 4 linguagens: JavaScript, Python, PHP, cURL

### 🎨 Interface Moderna
- ✅ **Navegação por Tabs**: API Reference, Guides, Webhooks
- ✅ **Busca Inteligente**: Pesquisa em toda documentação
- ✅ **Modo Dark/Light**: Temas customizáveis
- ✅ **Componentes Interativos**: CardGroup, Accordion, Steps, CodeGroup

### 🚀 Funcionalidades Avançadas
- ✅ **API Playground**: Teste requisições diretamente na documentação
- ✅ **Autenticação Configurada**: Bearer Token e API Key
- ✅ **Feedback System**: Thumbs up/down e sugestões de edição
- ✅ **Analytics Integrado**: Google Analytics 4
- ✅ **SEO Otimizado**: Indexação e meta tags configuradas

### 📊 Casos de Uso Reais
Cada endpoint inclui:
- 💡 **Casos de uso práticos** com código funcional
- 📈 **Dashboards e análises** prontas para uso
- 🔧 **Sistema de automação** completos
- ⚠️ **Tratamento de erros** e edge cases
- 🎯 **Melhores práticas** e otimizações

## 🚀 Desenvolvimento Local

### Pré-requisitos

- **Node.js** 18+ ([Download](https://nodejs.org))
- **Mintlify CLI** (instalado globalmente)

### Instalação

```bash
# Instalar Mintlify CLI globalmente
npm i -g mintlify
```

### Executar Localmente

```bash
# Navegar até a pasta da documentação
cd docs

# Iniciar servidor de desenvolvimento
mintlify dev
```

A documentação estará disponível em **http://localhost:3000**

### Hot Reload

O Mintlify possui hot reload automático. Qualquer alteração em arquivos `.mdx` ou `docs.json` será refletida instantaneamente no navegador.

## 🛠️ Comandos Úteis

```bash
# Validar configuração
mintlify validate

# Verificar links quebrados
mintlify broken-links

# Build para produção
mintlify build

# Instalar dependências
npm install

# Limpar cache
mintlify clean
```

## 📝 Como Contribuir

### Estrutura de Arquivos MDX

Cada página MDX segue este padrão:

```mdx
---
title: 'Título da Página'
description: 'Descrição breve para SEO'
api: 'POST /endpoint'  # Opcional: para endpoints de API
---

## Seção Principal

Conteúdo da documentação...

<Tip>
  Dica útil para o usuário
</Tip>

<Warning>
  Aviso importante
</Warning>

## Exemplos de Código

<CodeGroup>
```javascript JavaScript
// Código JavaScript
```

```python Python
# Código Python
```
</CodeGroup>
```

### Componentes Disponíveis

| Componente | Uso |
|------------|-----|
| `<Card>` | Cards clicáveis com ícones |
| `<CardGroup>` | Grupo de cards em grid |
| `<Accordion>` | Conteúdo expansível |
| `<AccordionGroup>` | Múltiplos accordions |
| `<Steps>` | Lista numerada de passos |
| `<Tabs>` | Navegação por abas |
| `<CodeGroup>` | Múltiplas linguagens de código |
| `<ParamField>` | Documentação de parâmetros de API |
| `<ResponseField>` | Campos de resposta da API |
| `<Tip>`, `<Note>`, `<Warning>` | Caixas de destaque |
| `<Expandable>` | Seção expansível |

### Adicionar Nova Página

1. **Criar arquivo MDX** na pasta apropriada
2. **Adicionar ao docs.json** na seção `navigation`:

```json
{
  "group": "Nome do Grupo",
  "pages": [
    "pasta/novo-arquivo"
  ]
}
```

3. **Testar localmente** com `mintlify dev`

### Adicionar Novo Endpoint

1. **Criar arquivo MDX** em `api-reference/grupo/endpoint.mdx`
2. **Configurar frontmatter**:

```mdx
---
title: 'Nome do Endpoint'
api: 'METHOD /path'
description: 'O que este endpoint faz'
---
```

3. **Documentar parâmetros** com `<ParamField>`
4. **Documentar resposta** com `<ResponseField>`
5. **Adicionar exemplos** em múltiplas linguagens

## 📦 Deploy

### Deploy Automático (Mintlify Cloud)

1. Conecte seu repositório GitHub ao Mintlify
2. Cada push para `main` faz deploy automático
3. Prévia de PRs disponível automaticamente

### Deploy Manual

```bash
# Build da documentação
mintlify build

# Deploy para produção (configurar em docs.json)
mintlify deploy
```

## 🔧 Configuração

### docs.json

Arquivo principal de configuração:

```json
{
  "$schema": "https://mintlify.com/docs.json",
  "name": "Monitora API",
  "theme": "mint",
  "logo": {
    "dark": "/logo/dark.svg",
    "light": "/logo/light.svg"
  },
  "api": {
    "baseUrl": "https://api.monitoragrupo.com/v1",
    "mdx": {
      "server": "https://api.monitoragrupo.com/v1",
      "auth": {
        "method": "bearer",
        "name": "Authorization"
      }
    }
  }
}
```

**Configurações importantes:**
- `baseUrl`: URL base da API
- `api.mdx.server`: Servidor para playground de MDX
- `api.mdx.auth`: Método de autenticação (bearer, key, basic)
- `navigation`: Estrutura de navegação
- `tabs`: Abas principais

## 📊 Analytics

Analytics configurado em `docs.json`:

```json
{
  "analytics": {
    "ga4": {
      "measurementId": "G-XXXXXXXXXX"
    }
  }
}
```

Eventos rastreados automaticamente:
- Visualizações de página
- Buscas
- Cliques em links
- Testes no API playground
- Feedback (thumbs up/down)

## 🎨 Customização

### Cores

Cores definidas em `docs.json`:

```json
{
  "colors": {
    "primary": "#0D9373",
    "light": "#07C983",
    "dark": "#0D9373"
  }
}
```

### Logos

Adicione logos em `/logo/`:
- `dark.svg` - Logo para tema escuro
- `light.svg` - Logo para tema claro

### Favicon

Adicione `favicon.png` na raiz do projeto.

## 🔍 SEO

Cada página MDX deve incluir:

```mdx
---
title: 'Título da Página (50-60 caracteres)'
description: 'Descrição meta para SEO (150-160 caracteres)'
---
```

Configuração global de SEO em `docs.json`:

```json
{
  "seo": {
    "indexing": "navigable"
  }
}
```

## 📚 Recursos Adicionais

### Documentação do Mintlify
- 📖 [Documentação Oficial](https://mintlify.com/docs)
- 🎨 [Showcase de Componentes](https://mintlify.com/showcase)
- 💬 [Community Discord](https://discord.gg/mintlify)

### Exemplos de Referência
- [Stripe Docs](https://stripe.com/docs/api)
- [Twilio Docs](https://www.twilio.com/docs)
- [Clerk Docs](https://clerk.com/docs)

### Ferramentas Úteis
- [OpenAPI Validator](https://apitools.dev/swagger-parser/online/)
- [Mintlify Scraper](https://mintlify.com/docs/api-playground/scraping) - Gera docs a partir de OpenAPI
- [MDX Editor](https://mdxeditor.dev/) - Editor visual para MDX

## 🐛 Troubleshooting

### Erro: "Missing required fields to send a playground request"

**Solução**: Verificar configuração `api.mdx` em `docs.json`:

```json
{
  "api": {
    "mdx": {
      "server": "https://sua-api.com",
      "auth": {
        "method": "bearer",
        "name": "Authorization"
      }
    }
  }
}
```

### Erro: "Failed to load navigation"

**Solução**: Validar sintaxe do `docs.json`:

```bash
mintlify validate
```

### Página não aparece na navegação

**Solução**: Verificar se o caminho em `docs.json` corresponde ao arquivo:

```json
{
  "pages": [
    "api-reference/auth/login"  // Arquivo: api-reference/auth/login.mdx
  ]
}
```

### Hot reload não funciona

**Solução**:
1. Parar servidor: `Ctrl+C`
2. Limpar cache: `mintlify clean`
3. Reiniciar: `mintlify dev`

## 📞 Suporte

- 💬 **Email**: support@monitoragrupo.com
- 🐛 **Issues**: [GitHub Issues](https://github.com/monitoragrupo/docs/issues)
- 📖 **Docs**: [docs.monitoragrupo.com](https://docs.monitoragrupo.com)
- 🚀 **Dashboard**: [dashboard.monitoragrupo.com](https://dashboard.monitoragrupo.com)

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<p align="center">
  Feito com ❤️ pela equipe Monitora Grupo | Powered by <a href="https://mintlify.com">Mintlify</a>
</p>

### Validar OpenAPI

```bash
mintlify openapi-check ./openapi.json
```

### Validar docs.json

O arquivo `docs.json` usa o schema do Mintlify para validação automática em editores compatíveis.

## 🔗 Integração OpenAPI

Para integrar sua especificação OpenAPI:

1. **Adicione sua spec OpenAPI** em `openapi.json` ou mantenha-a hospedada
2. **Configure no docs.json**:

```json
{
  "navigation": {
    "groups": [
      {
        "group": "API Reference",
        "openapi": "openapi.json",
        "pages": [
          "api-reference/overview",
          "GET /accounts",
          "POST /accounts"
        ]
      }
    ]
  }
}
```

## 📦 Deploy

### Mintlify Cloud

```bash
mintlify deploy
```

### Vercel

```bash
vercel
```

### Netlify

```bash
netlify deploy
```

## 🎯 Próximos Passos

1. **Preencha openapi.json** com sua especificação OpenAPI real
2. **Customize as cores** em `docs.json` para combinar com sua marca
3. **Adicione logos** em `/logo/` (dark.svg e light.svg)
4. **Configure analytics** (Google Analytics, Mixpanel, etc.)
5. **Adicione exemplos** de código reais nos endpoints
6. **Configure webhooks** com eventos reais do seu sistema
7. **Personalize o conteúdo** com informações específicas da sua API

## 📖 Documentação do Mintlify

- [Guias](https://mintlify.com/docs/guides)
- [Componentes](https://mintlify.com/docs/components)
- [Navegação](https://mintlify.com/docs/organize/navigation)
- [OpenAPI Setup](https://mintlify.com/docs/api-playground/openapi-setup)

## 🤝 Contribuindo

1. Fork o repositório
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT.

## 💬 Suporte

- Email: support@example.com
- Discord: [discord.gg/example](https://discord.gg/example)
- Status: [status.example.com](https://status.example.com)
