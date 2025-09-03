# Tutorial: GitHub + VS Code
---

## Requisitos
- VS Code instalado.  
- Git instalado (instale pelo site https://git-scm.com — isto é instalação, **não** exige usar linha de comando).  
- Conta no GitHub.

---

## 1) Configurar **nome** e **e‑mail**

> Esses dados aparecem como autor dos commits. Peça aos alunos para usar **o mesmo e‑mail** cadastrado no GitHub para vincular os commits à conta.
`
git config --global user.name "NOME"
git config --global user.email "EMAIL"
`
---

## 2) Inicializar o repositório no VS Code (se ainda não tiver sido feito)
1. Abra a pasta do projeto no VS Code (**File → Open Folder...**).  
2. Clique em **Source Control** (ícone de raminho à esquerda).  
3. Se o projeto não for um repositório git, você verá um botão **Initialize Repository** — clique nele.  
4. Agora o Source Control passa a mostrar os arquivos modificados (unstaged).

---

## 3) Fazer o primeiro commit (pela interface do VS Code)
1. Crie/edite arquivos (por exemplo `README.md`). **Salvar** o arquivo.  
2. No painel **Source Control**, para cada arquivo modificado clique no **+** ao lado do arquivo para **Stage** (preparar para commit), ou clique em **Stage All Changes**.  
3. No topo do painel Source Control escreva a **mensagem do commit** (ex: `Primeiro commit`) no campo de mensagem.  
4. Clique no ícone de **check (✓)** para **commit**. O commit será gravado localmente com o nome/e‑mail configurados.  

---

## 4) Conectar e publicar no GitHub
1. No canto inferior esquerdo do VS Code existe o ícone de **Contas** — clique e faça **Sign in / Sign in to GitHub** (isso abrirá o navegador para autenticar).  
2. Após entrar, volte ao VS Code.  
3. No painel **Source Control** aparecerá o botão **Publish Branch** ou **Publish to GitHub** (ou no topo da janela de status). Clique nele.  
4. Na janela que abrir escolha o nome do repositório e se vai ser **public** ou **private**. Confirme.  
5. O VS Code criará o repositório no GitHub e fará o **push** dos commits iniciais automaticamente.  

---

## 5) Fluxo diário
1. **Editar arquivos** no editor → salvar.  
2. **Stage** dos arquivos: clique no **+** (ou Stage All).  
3. Escrever a mensagem de commit no campo do Source Control → clicar no **✓** (commit).  
4. **Enviar para o GitHub (push)**: depois do commit clique no ícone de **Sincronizar / Setas circulares** no canto inferior esquerdo ou no botão **… (More Actions)** do painel Source Control → escolha **Push** ou **Sync**.  
5. **Baixar atualizações (pull)**: botão **… → Pull** ou **Sync** (o VS Code sugere sincronizar se houver mudanças remotas).  

---

## 6) Branches (criar/usar sem terminal)
1. Clique no **nome da branch** no canto inferior esquerdo (ex.: `main`).  
2. Escolha **Create new branch** → digite o nome (ex.: `feature1`) → o VS Code muda para a nova branch.  
3. Faça commits normalmente. Para enviar a nova branch ao GitHub clique em **Publish Branch** (aparecerá um botão para publicar a branch).

---

## 7) Resolver conflitos (pela interface)
1. Se houver conflito ao puxar/puxar e mesclar, abra o arquivo com conflito — o editor mostrará botões nas regiões de conflito: **Accept Current Change**, **Accept Incoming Change**, **Accept Both Changes**, ou **Compare Changes**.  
2. Use os botões para escolher a versão correta.  
3. Depois de resolver, **stage** o arquivo e faça o **commit**.  

---

## 8) Dicas e observações finais
- Use o **mesmo e‑mail do GitHub** para vincular commits à conta do GitHub. (Se usar outro e‑mail, os commits podem não aparecer como seus no site.)  
- Se o VS Code reclamar que **user.name** e **user.email** não estão configurados, siga o passo 1 (Git Graph ou editar `.gitconfig`) e reinicie o VS Code.  
- Para ensino médio: peça aos alunos que façam cada etapa em pares — um cria o commit, outro publica — para praticar as telas do VS Code.  

---



---

## ATIVIDADES
1 - Crie um repositório pelo VSCODE
2 - Adicione arquivos.py dentro do repositório
3 - Sincronize outros projetos pelo VSCode


