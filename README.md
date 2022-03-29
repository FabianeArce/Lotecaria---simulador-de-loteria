# Projeto Lotecaria---simulador-de-loteria
Um simulador de loteria que o usuário escolhe seis numeros
e o programa sorteia outros seis numeros e após isso
verifica a quantidade de acertos!!!

## Tecnologias utilizadas
- **HTML:** _Estrutura do SITE_
- **CSS:** _Estilo do SITE_
- **JS:** *Funções do SITE*
- ~~BootStrap:~~ Não foi utilizado


### Melhorias Possiveis
1. [X] Subir no github pages
2. [ ] Trocar o alerte por mensagems mais amigaveis 
3. [ ] Realizar teste para descobrir bugs 🕷🤨


### Disponivel em:
[GitHubPage](https://fabianearce.github.io/Lotecaria---simulador-de-loteria/)

### Prints da Tela do WebApp

| Tela inicial | Primeira Rodada |
|--------------|-----------------|
| ![tela inicial do site](/img/tela1.png)      | ![tela preenchida do site](https://raw.githubusercontent.com/FabianeArce/Lotecaria---simulador-de-loteria/master/img/tela2.png)        | 


### Código Principal
```js:
function verificaAcertos() {
    let cont = 0
    numDig.forEach(function (valor, index) {
        if (numSort.includes(valor)) {
            cont = cont + 1
        }
    })
    document.getElementById("total").innerText = cont
}
```
