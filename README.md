# jsj-minigame
#### Mais informações do projeto consultar a Wiki.
##  ----------Tutorial Git----------
### Primeiramente é necessário fazer o "Fork" do projeto principal
- Fork:
    - Basicamente o Fork é uma cópia do repositório central , para um repositório remoto(Um repositório seu).
- Git Clone
    - Esse comando serve para clonar o repositório remoto para sua máquina;
        - Lembrando que após a clonagem é nesssário informar ao git o que é repositório de fork e o que é repositório central, com os comandos:
            -   `$git remote set-url origin https://github.com/{username}/{projeto}`
            -   `$git remote add upstream https://github.com/serc-ntic/{projeto}`

######  Depois da realização desses passos o programador já pode iniciar seu fluxo de programação.
**Lembrando que uma boa prática é a utilização de branchs(ramos), para mais informações acessar o link (https://github.com/InfoJr/git/blob/master/pages/workflow.md).**

### Fluxo de programação
- Sempre ao executar `git commit`:
    - Puxar atualizações. (`git pull`)
    - Verificar mensagem de retorno no terminal.
    - Se o git acusar conflito:
        - Resolver conflito
        - Dica: Observe as linhas em que o git acusa conflito ou através da comparação feita pelo Visual Studio Code.
        - Executar `git push`.
- **Todos os passos acima estão realacionados ao seu Fork.**

### Pull Request
- Um pull request é uma solicitação de alteração no repositório central.Após executar o git push, é necessário criar um pull request para que seu código seja mesclado com o principal.

### Para mais informações acessar os links de consulta, que são eles:
    (https://github.com/InfoJr/git/blob/master/pages/workflow.md)
    (https://git-scm.com/docs)

### Guia de Estilo
    Baseado no guia de estilo do Node.JS. Artigo em: (https://medium.com/swlh/node-js-coding-style-guidelines-74a20d00c40b)
