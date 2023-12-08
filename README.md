# Guia básico de Git e GitHub

## Descrição

Repositório criado para colocar os ensinamentos de alguns cursos de Git e GitHub em prática.


## Comandos Git 

```bash
# Clonar um repositório
git clone https://github.com/usuario/repo.git

# Adicionar arquivos para o commit
git add arquivo.txt

# Realizar um commit
git commit -m "Mensagem do commit"

# Enviar para o repositório remoto
git push origin branch
```
**Visualizando o Status do Repositório:**
```markdown
```bash
# Verificar o status do repositório
git status

# Verificar diferenças entre os arquivos
git diff

```


### **Ramificações (Branches):**
```markdown
```bash
# Criar uma nova branch
git branch nova-branch

# Mudar para uma branch
git checkout nova-branch

# Mesclar branches
git merge outra-branch
```


### **Histórico de Commits:**
```markdown
```bash
# Visualizar o histórico de commits
git log

# Desfazer commits
git revert <hash_do_commit>

```

### **Trabalhando com Remotos:**
```markdown
```bash
# Adicionar um novo repositório remoto
git remote add upstream https://github.com/upstream/repo.git

# Obter alterações do repositório remoto
git pull upstream master

```
### **Sincronizar com Alterações Remotas**
Se outros colaboradores fizerem alterações no repositório, sincronize seu repositório local:
```bash
git pull origin [nome-do-seu-branch]
```
### **Criar um Novo Branch (Opcional)**
Se estiver trabalhando em uma funcionalidade específica ou correção de bug, crie um novo branch:
```bash
git checkout -b [nome-do-novo-branch]
```
### **Enviar um Pull Request**
Ao concluir suas alterações e garantir que tudo esteja funcionando corretamente, envie um Pull Request no GitHub.

### **Ignorar Arquivos/Dirs:**
Crie um arquivo .gitignore para listar os arquivos ou diretórios que você deseja ignorar no versionamento.

### **Logs e Status:**
Use git log para visualizar o histórico de commits e git status para ver o status atual do seu repositório.

### **Branches:**
Explore e use branches para desenvolver recursos isoladamente.

### **Links Úteis**
**[Documentação Oficial do Git](https://git-scm.com/doc)**

**[Documentação Oficial do GitHub](https://docs.github.com/pt)**

