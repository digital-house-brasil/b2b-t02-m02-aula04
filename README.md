![](./assets/hd-header.png)

## Git e GitHub

<details>
    <summary>1. Trabalhando com GitLog</summary>

    > Git Log é utilizado para você revisita o histórico de versionamentos. Com ele você pode rever tudo o que ocorreu no repositório.

    > O git log podemos ver os commits e os ids vinculados a eles. Isso é importante, pois o utilizaremos em comandos como Reset.

</details>

<details>
    <summary>2. Como funciona Restore</summary>

    > O git restore é uma precisamos restaurar algum arquivo ou o projeto por completo. O git restore é especificamente para trabalhar com a restauração de arquivos ou projeto ao um ponto anterior

</details>

<details>
    <summary>3. Utilizando o Revert</summary>

    > Reverte é usado para reverter algumas alterações. É um comando como um CTRL+Z para  desfazer as alterações. Desfará o commit especificado. Geralmente, git revert é um commit.

</details>

<details>
    <summary>4. Utilizando Reset</summary>

    > O git reset é um comando muito importante dentro git e irá nos ajudar a eliminar algumas alterações tanto na área de staged como os commits já realizados.

</details>

<details>
    <summary>5. Utilizando o Rebase</summary>

    > No Git, o termo rebase é referido como o processo de mover ou combinar uma sequência de commits para um novo commit base. 

</details>

<details>
    <summary>6. Atividade em dupla</summary>

    - Integrante 1: 
        - Vai criar um repositório chamado `projeto-dark`, na criação do repositório, deve marcar a opção `Add a README file`
        - Realizar o clone do repositório
        - Criar uma branch chamada `develop` 
        - Depois realize o push para a branch `develop`
        - Depois criei uma branch chamada `feature/task1` e realize o checkout para ela
        - Adicionar o arquivo `task1.txt` e colocar o seguinte texto `Task 1`
        - Depois faça o push para a branch `feature/task1`  
        - Adicione o integrante 2 como colaborador
    - Integrante 2: 
        - Realize o clone do repositório
        - Crie uma branch chamada `feature/task2`
        - Adicionar o arquivo `task2.txt` e colocar o seguinte texto `Task 2`
        - Realize o pull da branch `develop`, para saber se existe alguma atualização
        - Se existir atualização, realize o merge da branch `develop` com a `feature/task2`
        - Depois faça o push para a branch `feature/task2`  
    - Integrante 1: 
        - Realize o pull request da branch `feature/task1` para `develop`
    - integrante 2:
        - Realize o pull request da branch `feature/task2` para `develop`
    - Integrante 1:
        - Realize o pull request da branch `develop` para a `main`
    - Integrante 1:
        - Faça o checkout para a branch `develop`
        - Realize o pull para atualizar as `branch`
    - Integrante 1:

</details>
