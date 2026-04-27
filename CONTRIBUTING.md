# 🤝 Guia de Contribuição

Obrigado por contribuir com este projeto da **Fluxo Digital Tech**! Para manter o padrão, siga as diretrizes abaixo.

---

## 📝 Conventional Commits

Use sempre o padrão [Conventional Commits](https://www.conventionalcommits.org/):

| Tipo | Quando usar |
|------|-------------|
| `feat` | Nova funcionalidade |
| `fix` | Correção de bug |
| `docs` | Apenas documentação |
| `style` | Formatação, ponto e vírgula etc. (sem mudança de lógica) |
| `refactor` | Refatoração sem nova feature ou bugfix |
| `perf` | Melhoria de performance |
| `test` | Adição ou ajuste de testes |
| `build` | Mudanças no sistema de build/dependências |
| `ci` | Mudanças em CI/CD |
| `chore` | Tarefas de manutenção |
| `revert` | Reverter um commit |

**Exemplos:**

```
feat: adiciona integração com WhatsApp Cloud API
fix(auth): corrige expiração do token JWT
docs: atualiza README com novos endpoints
refactor: extrai service de envio de e-mail
chore: atualiza dependências
```

## 🌿 Branches

- `main` — produção, sempre estável
- `develop` — integração (opcional, para projetos maiores)
- `feat/<descricao-curta>` — novas features
- `fix/<descricao-curta>` — correções
- `hotfix/<descricao-curta>` — correções urgentes em produção
- `chore/<descricao-curta>` — manutenção

Use **kebab-case** no nome da branch.

## 🔁 Pull Requests

1. Crie a branch a partir de `main` (ou `develop`).
2. Faça commits pequenos e atômicos seguindo Conventional Commits.
3. Abra o PR usando o template (`.github/PULL_REQUEST_TEMPLATE.md`).
4. Descreva **o que** mudou e **por que**.
5. Marque o checklist de revisão.
6. Aguarde aprovação antes do merge.

## 📂 Padrões de código

- **Nomes de arquivos:** `kebab-case` (`meu-arquivo.js`, não `MeuArquivo.js`).
- **Variáveis e funções:** `camelCase`.
- **Classes e componentes:** `PascalCase`.
- **Constantes globais:** `UPPER_SNAKE_CASE`.
- Linhas até ~100 colunas (não obrigatório).
- Use linter/formatter do projeto (ESLint, Prettier, Ruff etc.).

## 🔐 Segurança

- **Nunca** commite credenciais, tokens, chaves ou `.env`.
- Use `.env.example` para documentar variáveis necessárias.
- Antes de fazer push, revise o diff (`git diff --staged`).
- Se vazar uma credencial, **revogue imediatamente** e abra issue.

## 🐛 Reportando bugs

Use o template de [bug report](.github/ISSUE_TEMPLATE/bug_report.md). Inclua passos para reproduzir, comportamento esperado e ambiente.

## 💡 Sugerindo features

Use o template de [feature request](.github/ISSUE_TEMPLATE/feature_request.md). Descreva o problema, a solução proposta e alternativas consideradas.

---

© Fluxo Digital Tech
