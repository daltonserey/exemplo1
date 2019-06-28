> **DISCLAIMER** Este repositório é apenas um exemplo criado em sala de aula como 
> demonstração de uso do git e do github por linha de comando. Há muito
> material sobre git e github excelente na rede. Use este material
> apenas para relembrar o que fizemos em sala de aula.

> Sugestão: leia _o livro_ sobre Git. É código aberto e é excelente para
> aprender sobre o git. Sugestão 2: foque mais no git que no github. O github
> é construído sobre o git. Entender bem o git facilitará seu entendimento
> do GitHub.

# Exemplo de projeto no GitHub


Este arquivo é exibido na página do projeto.

- exemplo
- de
- bullets


## Comandos básicos de Git

- `init` para criar um repo local
- `status` para exibir o estado do repositório local e do _stage_
- `log` para listar os commits
  - use `log --oneline` para listar commits em uma única linha
  - use `log --graph` para listar commits como grafo
  - combine os keywords acima
- `checkout` para visualizar um commit ou branch 
  - você não deve comitar sobre um commit existente
  - se é o que você quer, crie uma nova _branch_
- `add` para adicionar um arquivo ao stage
- `diff` para comparar um arquivo mudado ao que está no último
  commit
- `difftool` para fazer o mesmo via `vimdiff` (ou equivalente)
- `commit` para fazer o commit dos arquivos no _stage_
- `push` para enviar os commits ao github (ou outro repo)
