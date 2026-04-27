# 🔐 Política de Segurança

## Versões suportadas

Apenas a versão mais recente da branch `main` recebe correções de segurança.

## Reportando uma vulnerabilidade

Se você encontrar uma vulnerabilidade neste projeto, **não abra uma issue pública**. Em vez disso:

1. Envie um e-mail para **fluxodigitaltech@gmail.com** com:
   - Descrição do problema
   - Passos para reproduzir
   - Impacto potencial
   - (Opcional) Sugestão de correção

2. Aguarde confirmação em até **72 horas**.

3. Trabalharemos em uma correção em coordenação com você.

4. Após a correção, divulgaremos publicamente com créditos (se desejado).

## Boas práticas para colaboradores

- **Nunca** commite credenciais, tokens, chaves de API ou arquivos `.env`.
- Use `.env.example` para documentar variáveis de ambiente.
- Antes de cada push, revise o diff: `git diff --staged`.
- Configure pre-commit hooks (ex.: `gitleaks`, `detect-secrets`) sempre que possível.
- Mantenha dependências atualizadas (`npm audit`, `pip-audit`, Dependabot).

## Se uma credencial vazar

1. **Revogue imediatamente** a credencial no provedor (AWS, Google, GitHub, etc.).
2. **Gere uma nova credencial.**
3. Considere reescrever o histórico (`git filter-repo` / BFG) — apenas remover do último commit **não é suficiente**.
4. Se o repositório é público, considere torná-lo privado durante a limpeza.
5. Avise os usuários afetados, se aplicável.

---

© Fluxo Digital Tech
