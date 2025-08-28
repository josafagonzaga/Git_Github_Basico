# Git_Github_Basico

1 - Princiapais comandos 

    clonar um repositório do github ou outro local
        git clone linkDoRepositorio

            Exemplo:
                git clone QA-Proj-Cypress
                    (este link é encontrado e copiado através do code diretamente do github)
                        anexo a pasta um png para lembrar "Link Para Clone"

    verificar status de um repositório
        git status

    adicionar moidificações em um projeto
        git add .

    fazer o comentário anterior ao envio (obrigatório)
        git commit -m "mensagem que desejar anexar"

    fazer envio ao projeto
        git push

    fazer atualização do projeto
        git pull

2 - Fluxo de criação de repositório

    Github:
        Acessa github
        Cria repositório através da opção New
        Ao acessar a tela de configuração, dá um nome e clica na opção Add readme
        Escolhe se deseja deixar público ou privado
        Confirma
        Vai na opção code, e copia o link do repositório

    Computador:
        Botão direito do mouse, escolhe a opção git bash here
        digita git clone colaLinkCopiado, e aperta enter

        REPOSITÓRIO CLONADO

    VS-Code (Para enviar modificações)
        No link do git, poderá ver se há ou não modificações a serem enviadas
        Caso haja, clica no ícone
        Em "changes", insere a mensagem obrigatória (etapa do commit)
        Clica na setinha ao lado de "commit", e escolhe a opção commit and push