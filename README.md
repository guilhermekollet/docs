# Monitora API - Documentação Oficial

Documentação completa e interativa da **Monitora API** - A plataforma definitiva para gerenciamento de grupos do WhatsApp, campanhas de marketing e monitoramento automatizado.

🔗 **[Acessar Documentação](https://docs.monitoragrupo.com)** | 🚀 **[Dashboard](https://dashboard.monitoragrupo.com)** | 💬 **[Suporte](mailto:support@monitoragrupo.com)**

---

## 🎯 Sobre o Projeto

A Monitora API oferece uma solução robusta para:

- **Gestão de Grupos WhatsApp**: Monitore capacidade, status e saúde de grupos em tempo real
- **SmartLinks**: Crie links inteligentes com rotação automática de grupos
- **Monitoramento 24/7**: Configure alertas e receba notificações instantâneas
- **Análise de Campanhas**: Acompanhe métricas, conversões e performance
- **Automação Completa**: Auto-rotação, validação de links e monitoramento em tempo real

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
- ✅ **Navegação Organizada**: API Reference com grupos por funcionalidade
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
- ✅ **Suporte a múltiplas linguagens**: Exemplos em JavaScript, Python, PHP, Ruby
- ✅ **Design profissional**: Seguindo best practices do Mintlify

## 🚀 Desenvolvimento Local

### Pré-requisitos

- Node.js 18+
- Mintlify CLI

### Instalação

```bash
npm i -g mintlify
```

### Executar localmente

```bash
mintlify dev
```

A documentação estará disponível em `http://localhost:3000`

## 📝 Validação

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
5. **Personalize o conteúdo** com informações específicas da sua API
6. **Implemente rate limiting** e lógica de retry

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
