# GIT GUD

![Git Gud Meme](images/ca-git-gud.jpg)

## Você está aqui

Essa branch demonstra um merge. Se você olhar no `git log` dela, vai perceber que ela possui todos os commits da master até sua criação, com o commit da branch `basics/second-feature` intercalado na sua posição cronológica e um commit final gerado automaticamente do merge realizado (Merge branch 'basics/second-feature' into basics/feature-merge). No topo de todos esses estará o commit que atualiza este README novamente.

Um merge é exatamente o que o nome indica. Ele combina os commits de duas branches, em ordem cronológica, em uma nova branch e, caso existam alterações que diferem entre ambas as branches, cria um commit de merge no topo, que combina as mudanças. Mais detalhes: [Explicação da Atlassian](https://www.atlassian.com/br/git/tutorials/using-branches/git-merge).

A esse ponto, tente criar uma branch a partir dessa com a adição de um novo arquivo, e uma outra branch a partir dessa com a adição de outro arquivo. Faça o merge delas. (OBS: Lembre-se de usar o comando `git add` para adicionar o novo arquivo ao seu commit! Use os comandos dos tutoriais da atlassian e veja o que ocorre.)

Quando estiver satisfeito, pode seguir para a última branch básica: `basics/feature-rebase`.
