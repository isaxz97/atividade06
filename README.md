# atividade06

O Git rastreia as alterações feitas nos arquivos de um projeto, permitindo gerenciar o histórico de forma local, sem depender da internet, são ferramentas essenciais e complementares no desenvolvimento de software, mas possuem funções distintas.
Como por exemplo: o Git é o sistema de controle de versão (local) e o GitHub é a plataforma de hospedagem (nuvem).
O  GITHUB funciona como uma rede social e repositório para programadores, permitindo armazenar, compartilhar e modificar códigos de qualquer lugar. Além disso, o GitHub facilita a colaboração em projetos de código aberto (open source), servindo como portfólio profissional para desenvolvedores.

Algumas das Principais Funções do GIT abaixo;
Rastreamento de Alterações: Registra modificações, adições e exclusões de arquivos ao longo do tempo.
Versionamento e "Snapshots": Cria "fotos" (commits) do estado do projeto, permitindo voltar a versões anteriores caso algo dê errado (reverter alterações).
Amificação (Branching): Permite criar ramificações (branches) para desenvolver novas funcionalidades de forma isolada, sem afetar o código principal (main ou master).
Fusão de Código (Merging): Junta as alterações de diferentes ramos (branches) de volta ao código principal.
Trabalho Offline: Como é local, não exige conexão com a internet para criar commits, diffs ou logs.

Principais Funções do GITHUB;
Hospedagem de Repositórios (Repositórios Remotos): Armazenamento online de projetos, permitindo guardar códigos, arquivos e o histórico de alterações (backups).
Controle de Versão com Git: Rastreia e gerencia mudanças no código ao longo do tempo, possibilitando reverter para versões anteriores e trabalhar com branches (ramificações) para desenvolver funcionalidades sem alterar o código principal.
Colaboração (Pull Requests): Permite que desenvolvedores proponham alterações em um repositório, revisem código de terceiros e discutam melhorias antes de integrar as mudanças.
Gestão de Projetos (Issues e Boards): Ferramentas para organizar tarefas, rastrear problemas (bugs) e acompanhar o progresso do desenvolvimento com boards no estilo Kanban.
GitHub Pages: Recurso para hospedar sites estáticos diretamente de um repositório, ideal para documentação ou portfólios.

Comandos para se utilizar a plataforma GIT:
Os passos necessários para se postar seu projeto online através do GIT e GITHUB é necessário organização e tempo, e seguir os comandos como, fazer login no GitHub, dar um nome ao projeto (ex: meu-projeto). Definir como Público (necessário para o GitHub Pages gratuito), Após isso realize esses comandos abaixo:

# 1. Inicia o Git na pasta
git init

# 2. Adiciona todos os arquivos para a área de stage
git add .

# 3. Faz o commit dos arquivos com uma mensagem
git commit -m "primeiro commit"

# 4. Renomeia a branch principal para 'main' (padrão atual do GitHub)
git branch -M main

# 5. Conecta seu projeto local ao repositório do GitHub (cole a URL)
git remote add origin https://github.com

# 6. Envia os arquivos para o GitHub (primeira vez)
git push -u origin main

Selecione a branch main e a pasta /root (ou /docs) e clique em Save, Configure e envie o Projeto, Aguarde alguns minutos e gerará um link.

Comandos para se utilizar a plataforma GITHUB:
Faça login no GitHub.No canto superior direito, clique no ícone + e selecione New repository.Dê um nome ao repositório, adicione uma descrição (opcional) e deixe-o como Public. Clique em Create repository e faça esse comando:

# 1. Inicia o repositório Git
git init

# 2. Adiciona todos os arquivos
git add .

# 3. Faz o commit (salva as alterações)
git commit -m "Meu primeiro projeto online"

# 4. Define a branch principal como 'main'
git branch -M main

# 5. Vincula seu repositório local ao do GitHub
# (Substitua pela URL do seu repositório)
git remote add origin https://github.com

# 6. Envia o código para o GitHub
git push -u origin main

Após isso  e ele gerará um link.

Resumo dos comandos principais:
git init
git add .
git commit -m "mensagem"
git remote add origin <URL>
git push -u origin main
