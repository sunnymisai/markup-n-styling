1. O Fluxo Principal (Salvar alterações)
git status — Vê o que mudou no teu código.

git add . — Prepara todas as alterações para o commit.

git commit -m "Mensagem" — Grava as alterações localmente com uma mensagem descritiva.

git push origin main — Envia os teus commits para o GitHub/servidor remoto.

2. Ver o Histórico
git log --oneline — Mostra a lista de commits passados de forma curta (uma linha por commit).

3. Corrigir Erros Comuns
git commit --amend -m "Nova mensagem" — Corrige a mensagem do último commit que acabaste de fazer.

git reset HEAD nome-do-arquivo — Tira um arquivo da área de preparação (desfaz o git add).

git reset --soft HEAD~1 — Desfaz o último commit, mas mantém o teu código intacto para poderes alterá-lo.