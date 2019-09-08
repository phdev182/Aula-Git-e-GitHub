# Guia basico de Git e GitHub Rocketseat

Guia prático para iniciantes

### Instalação

https://git-scm.com/download

# SCENES

- [x] Você deseja criar pontos na historia da produção do seu projeto.

- [x] Você deseja verificar mudanças feitas no seu projeto.

- [x] Você começa uma nova funcionabilidade no seu projeto, sem estragar oque já foi feito.

- [x] Você adiciona as novas funcionabilidades no seu projeto em produção.

- [x] Você quer deletar a branch da nova funcionabilidade, depois de aplicar ao seu projeto.

- [x] Você quer colocar seu projeto na nuvem.

- [x] Você vai pegar um projeto já iniciado, para trabalhar com o time

- [x] Você precisa resolver um conflito.

- [x] Antes de enviar a resolução, precisamos atualizar o projeto local.

- [x] Você precisa voltar um arquivo para um determinado momento da linha do tempo.

- [x] Você precisa recuperar algo deletado.

- `git init` // inicia a linha do tempo
- `git add` // adiciona ou atualiza mudanças para irem para a linha do tempo
- `git add .` // adiciona ou atualiza mudanças para irem para a linha do tempo em diferentes arquivos.
- `git commit` // adiciona um ponto na linha do tempo
- `git commit -am ""` // não necessita do git add
- `git log` // visualiza os pontos na linha do tempo / commit
- `git status` // informa o estado das alterações do nosso projeto
- `git show` // apresenta determinado ponto na história
- `git branch` // gerenciar novas linhas do tempo
- `git branch checkout master` // muda para a branch master
- `git branch` -d // deleta uma branch
- `git checkout` // manipula as linhas do tempo
- `git checkout "ponto da historia" --"nome do arquivo"` // volta na linha do tempo
- `git merge` // unir linhas do tempo
- `git remote -v` // ver os repositorios remotos
- `git push` // envia alterações locais para o repositório remoto
- `git config credential.helper store` // evita solicitação de login e senha sempre que for salvar alguma coisa na nuvem
- `git clone` // clonar um projeto / repositório
- `git pull` // puxa do repositório remoto da nuvem para o repositorio local 