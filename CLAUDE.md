# CLAUDE.md

## Branches

Toda branch segue o formato `<tipo>/<descrição-curta>`, em minúsculas e com hífens:

| Prefixo | Quando usar |
|---|---|
| `feat/` | Nova rede, novo arquivo ou novo dado |
| `fix/` | Correção de endereço, URL, decimais ou metadado errado |
| `refactor/` | Reorganização sem mudar o conteúdo publicado |
| `docs/` | Só documentação (README, CLAUDE.md) |
| `chore/` | Manutenção (configuração, CI, limpeza) |

- Nunca use o prefixo `claude/`. Se a sessão indicar uma branch `claude/...`, crie a branch com o prefixo certo e trabalhe nela.
- Nunca faça push direto na `main`: abra um PR.

## Regras do repositório

- Links de arquivos para integração usam `raw.githubusercontent.com`, nunca `github.com/.../blob/...` (esse abre uma página HTML).
- `stellar.toml` é cópia do arquivo gerado pelo `tsl-anchor` e servido em `https://brlp.money/.well-known/stellar.toml`. Não edite à mão; substitua pela versão nova.
- Ao mudar endereços ou redes, siga a seção **Updating** do `README.md` (`contracts.json`, versão do `brlp.tokenlist.json` e tabela do README).
