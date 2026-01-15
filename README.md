# Monorepo Chat Completion OpenAI

Monorepo contendo API NestJS e aplicação Web NextJS integrados com OpenAI.

## 📦 Estrutura

```
monorepo-chat-completion-openai/
├── apps/
│   ├── api/          # API NestJS com OpenAI
│   └── web/          # Aplicação NextJS
└── packages/         # Pacotes compartilhados
```

## 🚀 Comandos

### Desenvolvimento

```bash
pnpm dev              # Inicia todos os projetos em modo desenvolvimento
```

### Build

```bash
pnpm build            # Faz build de todos os projetos
```

### Produção

```bash
pnpm start            # Inicia todos os projetos em modo produção
```

### Outros

```bash
pnpm lint             # Executa lint em todos os projetos
pnpm test             # Executa testes em todos os projetos
pnpm format           # Formata código em todos os projetos
```

## 🛠️ Tecnologias

- **Turborepo**: Gerenciamento de monorepo
- **pnpm**: Gerenciador de pacotes
- **NestJS**: Framework backend
- **NextJS**: Framework frontend
- **OpenAI**: Integração com IA

## 📝 Apps

### API (@monorepo/api)

API RESTful construída com NestJS, oferecendo endpoints para integração com OpenAI.

### Web (@monorepo/web)

Aplicação web construída com NextJS para interface de chat completion.

## ⚙️ Configuração

1. Instale as dependências:

```bash
pnpm install
```

2. Configure as variáveis de ambiente em cada app (`.env`)

3. Execute em modo desenvolvimento:

```bash
pnpm dev
```
