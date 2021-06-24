# GIT GUD

![Git Gud Meme](images/ca-git-gud.jpg)

## Você está aqui

Nesta branch será adicionado e comitado um arquivo super secreto e privado por acidente! Esse arquivo será depois adicionado ao gitignore e será necessário o comando `git rm -r --cached .` para limpar o cache e realizar o push da mudança. Porém isso não irá corrigir o histórico! Como esse caso é bem simples poderia ser feita a remoção ou edição dos commits que envolvem o arquivo através de reset, amend, ou de forma mais completa com um rebase. Porém, para demonstrar o que seria feito em um caso com muitos commits importantes incluindo o arquivo, o arquivo será removido através do poderoso comando `git filter-branch`. Veja como os commits envolvendo o arquivo se tornaram commits completamente vazios, o que normalmente não é possível. Lembrando novamente que esta alteração é de último caso e que o próprio git recomenda o uso de outras ferramentas para fazer isso. Para mais detalhes: [Git Filter Branch](https://git-scm.com/docs/git-filter-branch).
