
Iniciar e Configurar

• git init: Inicializa um novo repositório Git local na pasta atual.
• git clone [url]: Baixa um repositório existente da internet para a sua máquina.
• git config --global user.name "[nome]": Define o nome que será associado aos seus commits.
• git config --global user.email "[email]": Define o e-mail que será associado aos seus commits.

Fluxo Diário de Trabalho

• git status: Mostra o estado atual dos seus arquivos (quais foram modificados, deletados ou criados).
• git add [arquivo]: Salva as alterações de um arquivo específico na área de preparação (staging area).
• git add .: Adiciona todas as modificações da pasta atual para a área de preparação.
• git commit -m "[mensagem]": Grava permanentemente as alterações salvas na área de preparação no histórico local.
• git commit --amend: Altera a mensagem do último commit realizado (caso ainda não tenha enviado para o servidor).

Sincronização com Repositório Remoto

• git remote add origin [url]: Conecta o seu repositório local a um servidor remoto (como GitHub ou GitLab) pela primeira vez.
• git push origin [branch]: Envia as suas alterações locais para o servidor remoto.
• git pull: Baixa e mescla as alterações mais recentes do servidor remoto diretamente no seu projeto atual.
• git fetch: Baixa o histórico do servidor remoto para o seu computador, mas sem misturar com o seu código atual.

Gerenciamento de Branches (Ramificações)

• git branch: Lista todas as branches locais do seu projeto.
• git branch [nome-da-branch]: Cria uma nova ramificação com o nome escolhido.
• git checkout [nome-da-branch]: Muda o seu ambiente de trabalho para a branch informada.
• git checkout -b [nome-da-branch]: Cria uma nova branch e muda para ela imediatamente.
• git merge [nome-da-branch]: Junta as alterações da branch informada com a sua branch atual.
• git branch -d [nome-da-branch]: Apaga a branch indicada de forma segura.

Histórico e Desfazer Alterações

• git log: Exibe o histórico de todos os commits realizados no projeto.
• git log --oneline: Mostra o histórico simplificado, exibindo apenas uma linha por commit.
• git checkout -- [arquivo]: Descarta as modificações não salvas de um arquivo específico, voltando ao último commit.
• git reset [arquivo]: Remove o arquivo da área de preparação, mantendo as alterações feitas nele.
• git stash: Guarda temporariamente as alterações atuais sem fazer commit, limpando a mesa de trabalho para trocar de branch.
• git stash pop: Recupera as alterações guardadas temporariamente de volta para o código.
