# API Documentation

Documentação profissional e completa da API construída com [Mintlify](https://mintlify.com).

## 📚 Estrutura

```
docs/
├── introduction/           # Páginas de introdução
│   ├── overview.mdx       # Visão geral da API
│   └── getting-started.mdx # Primeiros passos
├── authentication/        # Documentação de autenticação
│   ├── overview.mdx      # Visão geral de autenticação
│   ├── api-keys.mdx      # Chaves de API
│   └── oauth.mdx         # OAuth 2.0
├── guides/               # Guias práticos
│   ├── quickstart.mdx    # Início rápido
│   ├── best-practices.mdx # Melhores práticas
│   └── rate-limits.mdx   # Limites de taxa
├── api-reference/        # Referência da API
│   └── overview.mdx      # Visão geral de endpoints
├── webhooks/             # Documentação de webhooks
│   └── overview.mdx      # Configuração e uso
├── errors/               # Tratamento de erros
│   └── overview.mdx      # Códigos de erro
├── getting-started/      # Endpoints específicos (migrar para api-reference)
│   ├── accounts.mdx
│   ├── campaings.mdx
│   ├── credits.mdx
│   ├── groups.mdx
│   ├── incidents.mdx
│   ├── monitors.mdx
│   ├── smartlinks.mdx
│   ├── subscription.mdx
│   └── common.mdx
├── changelog.mdx         # Histórico de mudanças
├── docs.json            # Configuração do Mintlify
└── openapi.json         # Especificação OpenAPI

```

## 🎨 Recursos

- ✅ **Navegação por Tabs**: Separação clara entre documentação e referência da API
- ✅ **Autenticação completa**: API Keys e OAuth 2.0 documentados
- ✅ **Guias práticos**: Quickstart, melhores práticas, limites de taxa
- ✅ **Webhooks**: Documentação completa de eventos em tempo real
- ✅ **Tratamento de erros**: Referência completa de códigos de erro
- ✅ **Changelog**: Rastreamento de versões e mudanças
- ✅ **Componentes interativos**: Cards, Accordions, Steps, Code Groups
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
