# task.io-api

## Configurando ambiente de desenvolvimento
- Realizar fork do repositório.
- Clonar o repositório.
    - `git clone https://github.com/SeuUsuarioDoGit/task.io-api`
- Rodar o seguinte comando para adicionar a upstream:
    - `git remote add upstream https://github.com/Task-io/task.io-api`
- Bloquear push para upstream:
    - `git remote set-url --push origin NO_PUSH`
- Atualizar repositório:
    - `git pull upstream main`
- Para enviar as alterações (Sempre deve ser enviado para sua origin):
    - `git push origin`
- Sempre que for implementar uma nova funcionalidade no projeto, deve ser criado uma nova branch:
    - `git checkout -b type-nome-da-branch`

## Configuração do Docker
- Criar o arquivo .env
    - Na raiz do projeto, crie um arquivo chamado .env.
    - Copie as variáveis de ambiente do arquivo de exemplo (.env.example) para o novo arquivo .env.
 - Configurar as variáveis de ambiente
    - Abra o arquivo .env que você acabou de criar.
    - Configure as variáveis de ambiente com os dados contidos na sessão environment do arquivo docker-compose.yml.
 - Iniciar os contêineres Docker
    - `docker-compose up -d`

## Building project
WIP
