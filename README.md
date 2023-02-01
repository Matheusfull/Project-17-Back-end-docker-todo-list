# 👩🏼‍💻🕵🏼‍♂️🚛 Boas-vindas ao repositório do projeto de Docker todo list! 🚛🧾🚪

<!-- # Como ficou o projeto ?

# Link da Aplicação -->

# Habilidades necessárias

<details>
  <summary><strong>:memo: Habilidades</strong></summary><br />

  Neste projeto pude:

1. **_Conteinerizar_** aplicações;
2. Criar uma conexão entre elas;
3. Orquestrar seu funcionamento.

---

Pude criar as imagens para as aplicações e configura-lá com o `docker-compose`.

Para isto, utilizei uma série de comandos do `docker` com diferentes níveis de complexidade.

Cada comando foi escrito em seu próprio arquivo, a fim de que ficasse registrado.

Para isto, fiz os seguintes passos:

1. Li o requisito e criei um arquivo chamado `commandN.dc` no diretório `docker-commands`, onde `N` é o número do requisito. Por exemplo:

    ```text
    Requisito 1: ./docker/docker-commands/command01.dc
    Requisito 2: ./docker/docker-commands/command02.dc
    Requisito 3: ./docker/docker-commands/command03.dc
    ```
2. Escrevi neste arquivo o comando do CLI *(Interface de Linha de Comando)* do Docker que resolvesse o requisito. Um exemplo de como ficou o arquivo:

    ```dc
    docker network inspect bridge
    ```
</details>

# O que é a aplaicação ?

<details>
  <summary><strong>:convenience_store: Desenvolvimento </strong></summary><br />

  _Conteinerizei_ [uma aplicação full-stack](docker/todo-app) neste repositório: um **aplicativo de tarefas**! Esta aplicação precisa ser conteinerizada para funcionar. Com isso, desenvolvi os arquivos de configuração para cada frente específica: `Front-end`, `Back-end` e, no nosso caso, para um aplicativo de `teste` que valida se as aplicações estão se comunicando.

</details>

# Como rodar na sua máquina ? 

<details>
  <summary><strong>‼️ Teste em sua máquina</strong></summary><br />

  1. Clone o repositório

  - Use o comando: `git@github.com:Matheusfull/Project-17-Back-end-docker-todo-list.git`.
  - Entre na pasta do repositório que você acabou de clonar:
    - `Project-17-Back-end-docker-todo-list`

  2. Instale as dependências

  - `npm install`.

  3. Testando os Comandos :

  - `Vá até docker/docker-commands`.
  - `Para cada comando,basta rodá-lo no terminar a fim de criar um container específico ou uma modficação`

  </details>

<!-- Olá, Tryber!
Esse é apenas um arquivo inicial para o README do seu projeto no qual você pode customizar e reutilizar todas as vezes que for executar o trybe-publisher.

Para deixá-lo com a sua cara, basta alterar o seguinte arquivo da sua máquina: ~/.student-repo-publisher/custom/_NEW_README.md

É essencial que você preencha esse documento por conta própria, ok?
Não deixe de usar nossas dicas de escrita de README de projetos, e deixe sua criatividade brilhar!
:warning: IMPORTANTE: você precisa deixar nítido:
- quais arquivos/pastas foram desenvolvidos por você; 
- quais arquivos/pastas foram desenvolvidos por outra pessoa estudante;
- quais arquivos/pastas foram desenvolvidos pela Trybe.
-->

<!--
1 - Boas vindas
2 - imagem/gif da aplicação
3 - link do deploy
4 - Habilidades necessárias para realizar o projeto
5 - O que é aquele projeto
6 - Como baixar e rodar na máquina
-->