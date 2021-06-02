# GIT GUD

![Git Gud Meme](images/ca-git-gud.jpg)

## Você está aqui

```git
<<<<<<< HEAD
Essa branch é o exemplo de um conflito. Quando duas branches que realizam mudanças divergentes em um mesmo arquivo são mergeadas ou sofrem rebase, um conflito surge.
=======
Tags são ponteiros fixos/estáticos que mantém uma snapshot específica do código sempre referenciada. Elas podem ser criadas como o comando `git tag` e são normalmente usadas para releases, já que são ideias para guardar pontos estáveis no código e realizar operações de CD/CI. Mais detalhes: [Git Tag](https://git-scm.com/book/en/v2/Git-Basics-Tagging)

Você pode visualizar uma tag nesta branch através de seu log. Observe que no commit "explicação de tags" existe uma tag sinalizada.
>>>>>>> remote/tag
```

O conflito encontrado foi commitado nesse caso como uma demonstração, mas em um projeto real seria feita a resolução do conflito. Editores de texto, IDEs e até alguns programas específicos oferecem ferramentas para facilitar esse processo, porém, na prática, tudo que precisa ser feitos é remover as marcas do git e manter apenas o conteúdo desejado das informações conflitantes.

Por exemplo, nesta branch o desejado provavelmente seria manter a HEAD (Current Change) e remover o conteúdo da remote/tag (Incoming Change). Essa edição seria realizada no próprio commit de merge ou durante o rebase, e entraria assim no histórico. No caso desta branch, pode ver que este commit consta como um merge no log.
