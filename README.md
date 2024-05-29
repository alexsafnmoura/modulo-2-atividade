# Modulo 2 atividade

# Trabalhando com Repositórios do GitHub

Este documento fornece um guia básico sobre como trabalhar com repositórios no GitHub. Ele cobre desde a criação de um novo repositório até a clonagem, envio de alterações (push), e criação de pull requests.

## Índice

1. [Introdução ao GitHub](#introdução-ao-github)
2. [Criando um Novo Repositório](#criando-um-novo-repositório)
3. [Clonando um Repositório](#clonando-um-repositório)
4. [Fazendo Alterações e Enviando (Push)](#fazendo-alterações-e-enviando-push)
5. [Criando Pull Requests](#criando-pull-requests)
6. [Conclusão](#conclusão)

## Introdução ao GitHub

GitHub é uma plataforma de hospedagem de código que permite colaboração e controle de versão usando Git. Ele é amplamente utilizado para desenvolvimento de software, permitindo que desenvolvedores colaborem em projetos de qualquer lugar do mundo.

## Criando um Novo Repositório

Para criar um novo repositório no GitHub:

1. Faça login na sua conta do GitHub.
2. No canto superior direito, clique no ícone `+` e selecione "New repository".
3. Preencha os detalhes do repositório:
    - Nome do repositório
    - Descrição (opcional)
    - Escolha a visibilidade (público ou privado)
4. Clique em "Create repository".

## Clonando um Repositório

Para clonar um repositório para o seu computador:

1. Vá até a página do repositório no GitHub.
2. Clique no botão `Code` e copie a URL do repositório.
3. Abra o terminal ou prompt de comando no seu computador.
4. Execute o comando:

    ```bash
    git clone [URL_DO_REPOSITÓRIO]
    ```

    Substitua `[URL_DO_REPOSITÓRIO]` pela URL que você copiou.

## Fazendo Alterações e Enviando (Push)

Para fazer alterações e enviá-las para o GitHub:

1. Navegue até a pasta do repositório clonado:

    ```bash
    cd [NOME_DO_REPOSITÓRIO]
    ```

2. Faça as alterações necessárias nos arquivos.
3. Adicione as alterações ao stage:

    ```bash
    git add .
    ```

4. Faça um commit das alterações:

    ```bash
    git commit -m "Descrição das alterações"
    ```

5. Envie as alterações para o repositório no GitHub:

    ```bash
    git push origin main
    ```

    Substitua `main` pelo nome da branch, se necessário.

## Criando Pull Requests

Para criar uma pull request (PR):

1. Faça login na sua conta do GitHub.
2. Navegue até o repositório onde você deseja enviar a PR.
3. Clique na aba `Pull requests`.
4. Clique no botão `New pull request`.
5. Selecione a branch de origem e a branch de destino para a PR.
6. Adicione um título e uma descrição para a PR.
7. Clique em `Create pull request`.

## Conclusão

Este guia básico cobre as operações fundamentais ao trabalhar com repositórios no GitHub.
