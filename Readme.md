Os principais comandos do Git para o controle de versão e trabalho em projetos estão organizados abaixo por categorias essenciais. Você pode consultar a documentação completa no Git Documentation.

Configuração Inicial

• git config --global user.name "Seu Nome": define o nome de usuário global.
• git config --global user.email "seu@email.com": define o e-mail global.

Criação e Clonagem de Repositórios

• git init: cria um novo repositório Git em uma pasta local.
• git clone [url]: baixa uma cópia de um repositório remoto existente para sua máquina.

Fluxo de Trabalho Básico

• git status: exibe o estado atual dos arquivos (modificados, preparados ou não rastreados).
• git add . ou git add [arquivo]: adiciona as alterações à área de preparação (staging area).
• git commit -m "mensagem": salva as alterações preparadas no histórico local com uma mensagem descritiva.
• git diff: mostra as diferenças detalhadas entre arquivos ou commits.
• git log: exibe o histórico de commits do repositório.

Ramos (Branches) e Mesclagem

• git branch: lista, cria ou exclui ramos.
• git checkout [branch] ou git switch [branch]: alterna entre ramos diferentes.
• git checkout -b [nome] ou git switch -c [nome]: cria um novo ramo e muda para ele imediatamente.
• git merge [branch]: une as alterações de outro ramo ao ramo atual.

Sincronização com Repositório Remoto

• git remote -v: lista os repositórios remotos vinculados.
• git fetch: baixa as atualizações do repositório remoto sem aplicá-las automaticamente no código.
• git pull: baixa e mescla as alterações do repositório remoto para o ramo atual.
• git push: envia os seus commits locais para o repositório remoto.

Desfazendo Alterações

• git reset --soft ou git reset --hard: retorna o repositório para um estado ou commit anterior.
• git revert [hash]: cria um novo commit que desfaz as alterações feitas em um commit passado.
• git stash: guarda temporariamente alterações não finalizadas para usar depois.
Você gostaria de um exemplo prático de como criar e enviar seu primeiro projeto para o GitHub ou de como resolver conflitos de merge?
• 
GitHub
Comandos Git - Aprenda Git do básico ao avançado
* Config: git config --global user.name/email * Init/Clone: git init, git clone [url] * Basic: git add, status, diff, commit -m, r...
• 
somostera.com
15 comandos git que vão te ajudar a programar - Tera | Lidere a mudança e transforme sua carreira
Git: Sistema de controle de versão para gerenciar ramificações, rastrear alterações e manter histórico de códigos. Comandos essenc...
• 
DataCamp
Os 20 principais comandos do Git com exemplos: Um guia prático
Comandos básicos do Git. As etapas básicas do trabalho com o Git incluem a criação de um repositório, a cópia de um repositório ex...
Mostrar tudo
    
As respostas da IA podem conter erros.        