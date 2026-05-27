# 🤝 Contributing to FinanceQuest

Obrigado por seu interesse em contribuir com FinanceQuest! Este documento fornece diretrizes para fazer contribuições significativas ao projeto.

## 📋 Código de Conduta

Todos os contribuidores devem seguir nosso Código de Conduta:
- Ser respeitoso e inclusivo
- Acolher críticas construtivas
- Focar no que é melhor para a comunidade
- Mostrar empatia com outros membros

## 🎯 Como Contribuir

### 1. Reportar Bugs
Se você encontrar um bug, abra uma **GitHub Issue** com:
- Título descritivo
- Descrição clara do problema
- Passos para reproduzir
- Comportamento esperado vs. comportamento atual
- Screenshots (se aplicável)
- Seu ambiente (OS, browser, versão)

### 2. Sugerir Features
Sugestões são bem-vindas! Abra uma **GitHub Issue** com:
- Motivo da feature
- Descrição detalhada
- Casos de uso
- Exemplos de como funcionaria

### 3. Pull Requests

#### Setup Inicial
```bash
# Fork o repositório
git clone https://github.com/SEU_USERNAME/FinanceQuest.git
cd FinanceQuest

# Crie uma branch
git checkout -b feature/sua-feature
```

#### Development
```bash
# Backend
cd backend
npm install
npm run dev

# Frontend (novo terminal)
cd frontend
npm install
npm start
```

#### Antes de Submeter
```bash
# Testes
npm test

# Lint
npm run lint

# Build
npm run build
```

#### Guidelines de Commits
- Use commits semânticos:
  - `feat:` - Nova feature
  - `fix:` - Bug fix
  - `docs:` - Documentação
  - `style:` - Formatação
  - `refactor:` - Refatoração
  - `test:` - Testes
  - `chore:` - Manutenção

Exemplos:
```
feat: add investment portfolio page
fix: resolve wallet balance calculation error
docs: update API documentation
```

#### Process do Pull Request
1. Crie um fork e uma branch
2. Faça suas mudanças
3. Escreva ou atualize testes
4. Atualize a documentação
5. Faça commit com mensagens claras
6. Push para sua fork
7. Abra um Pull Request

#### PR Template
```markdown
## 📝 Descrição
Descreva as mudanças que você fez.

## 🎯 Tipo de Mudança
- [ ] Bug fix
- [ ] Nova feature
- [ ] Mudança breaking
- [ ] Documentação

## ✅ Checklist
- [ ] Meu código segue o style guide
- [ ] Fiz self-review do meu código
- [ ] Comentei meu código, especialmente em partes complexas
- [ ] Atualizei a documentação
- [ ] Minhas mudanças não geram novos warnings
- [ ] Adicionei testes para minhas mudanças
- [ ] Testes novos e existentes passaram

## 🔗 Issues Relacionadas
Closes #(issue number)
```

## 📚 Estrutura do Projeto

```
FinanceQuest/
├── backend/              # Node.js + Express API
├── frontend/             # React 18 App
├── docs/                 # Documentação
├── docker-compose.yml    # Development environment
└── scripts/              # Utilitários
```

## 🧪 Testes

### Rodando Testes
```bash
# Todos os testes
npm test

# Com coverage
npm test -- --coverage

# Watch mode
npm test -- --watch
```

### Escrevendo Testes
- Use Jest para unit tests
- Use React Testing Library para component tests
- Aim for >80% coverage

## 📖 Documentação

Atualize a documentação quando:
- Adicionar nova API endpoint
- Mudar comportamento existente
- Adicionar configuração nova
- Criar novo componente importante

Locais para atualizar:
- `README.md` - Overview geral
- `docs/API_DOCS.md` - Endpoints
- `docs/GAME_DESIGN.md` - Regras do jogo
- `docs/ARCHITECTURE.md` - Arquitetura técnica

## 🔍 Code Review

- Leve e aprendizado com reviews
- Faça sugestões construtivas
- Elogie o trabalho bom
- Aceite críticas com graça

## 🐛 Debugging

### Backend Debugging
```bash
# Com debugger Node
node --inspect-brk dist/server.js

# No VS Code: attach ao debugger
```

### Frontend Debugging
- Use React DevTools extension
- Use Redux DevTools
- Use browser DevTools

## 📞 Precisa de Ajuda?

- Abra uma **Discussion** para perguntas
- Abra uma **Issue** para bugs/features
- Veja o **README** para setup
- Consulte **docs/** para documentação

## 🏆 Reconhecimento

Todos os contribuidores são reconhecidos em:
- Arquivo `CONTRIBUTORS.md`
- README.md
- GitHub insights

## 📜 Licença

Ao contribuir, você concorda que suas contribuições são licenciadas sob a MIT License.

---

**Obrigado por contribuir com FinanceQuest!** 🚀

Sua ajuda torna este projeto melhor para todos.
