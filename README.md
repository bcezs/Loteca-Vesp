# Projeto Lotecaria
Simulator de loteria que o usuarios que escolhe seis números e o programa sorteia outos seis números e após isso verifica a quantidade de acertos!

## Tecnologia Utilizadas
- **HTML:** _Estrutura do SITE_
- **CSS:** Estilo do SITE
- **JS:** Funções do SITE
- ~~BootStrap~~: Não foi utilizada

### Melhorias Possiveis
1. [x] Subir no github pages

2. [ ] Trocar Alert pro mensagens mais amigaveis

3. [ ] Realizar testes pra descobir bugs 🐱‍👤

### Disponivel em:
[GitHubPage](https://bcezs.github.io/Loteca-Vesp/)

### Prints da Tela do WebApp

| Tela Inicial | Primeiro Test   |
|--------------|-----------------|
| ![tela inicial do site](/img/tela 1.png)     | Imagem 2        |



### codigo principal
```js:
function verificaAcertos() {
    let cont = 0;
    numDig.forEach(function (valor, index) {
        if (numSort.includes(valor)) {
            cont = cont + 1;

        }

    });
    document.getElementById("total").innerText = cont;
}
```
