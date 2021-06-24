# GIT GUD

![Git Gud Meme](images/ca-git-gud.jpg)

## Você está aqui

Nesta branch será adicionado e comitado um arquivo super secreto e privado por acidente! Esse arquivo será depois adicionado ao gitignore e será necessário o comando `git rm -r --cached .` para limpar o cache e realizar o push da mudança. Porém isso não irá corrigir o histórico! Como esse caso é bem simples poderia ser feita a remoção ou edição dos commits que envolvem o arquivo através de reset, amend, ou de forma mais completa com um rebase. Porém, para demonstrar o que seria feito em um caso com muitos commits importantes incluindo o arquivo, o arquivo será removido através do poderoso comando `git filter-branch`. Será feito um push antes para realizar um merge que preservará as duas versões do histórico para comparação; mas na prática isso seria feito em uma nova branch, e a branch original posteriormente deletada (ou por meio de um push --force, que é mais arriscado).
