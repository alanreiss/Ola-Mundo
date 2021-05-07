# Branch ou Ramificação

Primeiro commit é feito na master/main. 
O branch é uma ramificação criada inicialmente da master/main.

Sempre que for desenvolver uma nova feature para o software, site ou projeto é interessante a criação de uma nova branch pra essa feature especifica. Assim alterações podem ser feitas a partir dela sem comprometer o branch principal/ branch main.

Quando a feature branch tiver sido finalizada e ou aprovada você pode realizar um **merge(junção)** entre a **branch secundária** (branch da feature) com a **branch principal** (branch main). Ou se a decisão for apagar, você pode deletar essa branch sem alterar a branch main.

O **merge** é feito a partir da branch main(principal).

**Conflito:** Ocorre quando duas branch alteram a mesma linha de código.
ex: se em uma branch o tittle estiver como "Título a preencher" e em outra estiver escrito "Titulo Preenchido", haverá um conflito.
No GitHub Desktop aparece uma mensagem de erro assim que for realizar o merge e da como sugestão abrir o **vscode** e escolher entre as linhas de código conflitante.