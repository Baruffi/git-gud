# GIT GUD

![Git Gud Meme](images/ca-git-gud.jpg)

## Você está aqui

Essa branch demonstra um merge. Se você olhar no `git log` dela, vai perceber que ela possui todos os commits da master até sua criação, com o commit da branch `basics/second-feature` intercalado na sua posição cronológica. Note que não há nenhum commit final gerado automaticamente. No topo de todos esses estará o commit que atualiza este README novamente.

Antes de explicar o rebase, é importante que seja conhecida a diferença entre repositórios locais e remotos. Ao realizar mudanças em um repositório local, essas mudanças não estão sendo publicadas para lugar nenhum. Para interagir com a origem, ou seja, a versão remota do repositório, são utilizados os comandos `git pull` e `git push` (para obter mudanças e publicar mudanças, respectivamente). Mais detalhes: [Atlassian Pull](https://www.atlassian.com/br/git/tutorials/syncing/git-pull), [Atlassian Push](https://www.atlassian.com/br/git/tutorials/syncing/git-push).

Essa separação é útil, pois permite que várias pessoas façam mudanças no mesmo código simultaneamente sem interferir no repositório remoto. É possível realizar mudanças locais sem a necessidade de publicá-las, com acesso a todos os comandos do git sem interferências externas. Mais detalhes: [Atlassian Syncing](https://www.atlassian.com/br/git/tutorials/syncing).

Isso tudo é relevante, pois a principal coisa que o git está tentando preservar é o histórico de mudanças realizadas no repositório. E o rebase é o primeiro comando desta sequência que reescreve esse histórico.

Isto é, ele combina os commits de duas branches, em ordem cronológica, porém, ele aplica suas mudanças passo a passo, ou, commit a commit. Dessa forma, o resultado final já é a combinação dos commits aplicados, sem necessidade de merge. Mas fazer isso não é completamente gratuito: Observe que as hashes dos commits (as linhas de texto aparentemente aleatório de cada commit visto no git log) mudam completamente no rebase. Ele precisa reescrever todo o histórico para aplicar as alterações uma a uma, o que significa que essas mudanças vão divergir do repositório remoto se a branch tiver sido publicada. Isso não afeta o desenvolvimento local, mas pode gerar problemas ao tentar publicar a branch com o rebase realizado. Mais detalhes: [Explicação da Atlassian](https://www.atlassian.com/br/git/tutorials/rewriting-history/git-rebase).

A esse ponto, tente criar uma branch a partir dessa com a adição de um novo arquivo, e uma outra branch a partir dessa com a adição de outro arquivo. Faça o rebase delas. (OBS: Lembre-se de usar o comando `git add` para adicionar o novo arquivo ao seu commit! Use os comandos dos tutoriais da atlassian e veja o que ocorre.)

Quando estiver satisfeito, pode explorar os demais grupos de branches do repositório!
