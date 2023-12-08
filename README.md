# Guia básico de Git e GitHub

## Descrição

Repositório criado para colocar os ensinamentos de alguns cursos de Git e GitHub em prática.


## Comandos Git 

1.  Adicionar e Commitar Alterações

git add .
git commit -m "Breve mensagem explicativa sobre suas alterações"

2.  Enviar Alterações para o GitHub

git push origin [nome do seu branch]

3. Sincronizar com Alterações Remotas
Se outros colaboradores fizerem alterações no repositório, sincronize seu repositório local:

git pull origin [nome-do-seu-branch]

4. Criar um Novo Branch (Opcional)
Se estiver trabalhando em uma funcionalidade específica ou correção de bug, crie um novo branch:

git checkout -b [nome-do-novo-branch]

5. Enviar um Pull Request
Ao concluir suas alterações e garantir que tudo esteja funcionando corretamente, envie um Pull Request no GitHub.

Ignorar Arquivos/Dirs:
Crie um arquivo .gitignore para listar os arquivos ou diretórios que você deseja ignorar no versionamento.

Logs e Status:
Use git log para visualizar o histórico de commits e git status para ver o status atual do seu repositório.

Branches:
Explore e use branches para desenvolver recursos isoladamente.

Links Úteis
Documentação Oficial do Git
Documentação Oficial do GitHub