
# Projeto Cotações

  

Esse projeto tem por finalidade treinar o uso do javascript para:

  

- Manipulação de DOM

- Manipulação de Eventos

- Consumo de API via fetch

- Uso do localStorage

  

Veja o projeto funcionando em [sergiomoura.github.io/cotacoes](https://sergiomoura.github.io/cotacoes/  "https://sergiomoura.github.io/cotacoes/")

  

# Instruções

  

Faça um fork desse projeto. Depois, clone o projeto para a sua máquina a partir do seu repositório.

Abra o seu editor na pasta do projeto e realize os passos descritos no Roadmap.

Observe que o arquivo index.js já possui uma constante chamada `cotacoes`. Ela que, inicialmente, irá conter as cotações de várias moedas em uma moeda base.

  

# Roadmap

  

- [ ] **Escreva uma função** `exibirCotacaoPrincipal`

> Essa função não deve receber parâmetros. Tudo que ela deve fazer é mostrar as informações da contante `cotacoes` exibi-la na parte da página destinada a exibir a cotação principal. Execute essa função ao final do script.

  

- [ ] **Escreva uma função** `exibirOutrasCotacoes`

> Essa função não deve receber nenhum parâmetro. O que ela deve fazer é exibir para cada cotação o símbolo da moeda seu respectivo valor com exatamente quatro casas decimais. Você pode usar o método `.toFixed()` do objeto Number para fazer isso. Saiba mais em [https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Number/toFixed](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Number/toFixed). Execute a função  `exibirOutrasCotacoes` ao final do script.

- [ ] **Escreva uma função** `carregaUltimasCotacoes()`
> Essa função deve fazer uma requisição com o método GET para a url https://api.exchangeratesapi.io/latest. A resposta a essa requisição deve ser um JSON com o formato análogo ao do objeto literal inicialmente guardado na constante `cotacoes`. Trate a resposta dessa requisição e faça com que os dados vindos nela sejam exibidos no documento utilizando as funções `exibirCotacaoPrincipal` e `exibirOutrasCotacoes`. Dica: altere o código inicial e faça com que a contante `cotacoes` passe a ser uma variável com o mesmo nome. Quando a resposta da requisição chegar, bastará atribuir o objeto retornado a essa variável `cotacoes` e chamar as funções `exibirCotacaoPrincipal` e `exibirOutrasCotacoes`. Execute essa função ao final do script.
