# Projeto Cotações

Esse projeto tem por finalidade treinar o uso do javascript para:

 - Manipulação de DOM
 - Manipulação de Eventos
 - Consumo de API via fetch
 - Uso do localStorage

Veja o projeto funcionando em [sergiomoura.github.io/cotacoes](https://sergiomoura.github.io/cotacoes/ "https://sergiomoura.github.io/cotacoes/")

# Instruções

Faça um fork desse projeto. Depois, clone o projeto para a sua máquina a partir do seu repositório.
Abra o seu editor na pasta do projeto e realize os passos descritos no Roadmap.
Observe que o arquivo index.js já possui uma constante chamada `cotacoes`.  Ela que, inicialmente, irá conter as cotações de várias moedas em uma moeda base.

# Roadmap

 - [ ] **Escreva uma função **`exibirCotacaoPrincipal`**:**
 Essa função não deve receber parâmetros. Tudo que ela deve fazer é mostrar as informações da contante `cotacoes` exibi-la na parte da página destinada a exibir a cotação principal.

 - [ ] **Escreva uma função **`exibirOutrasCotacoes`**:**
 Essa função não deve receber nenhum parâmetro. O que ela deve fazer é exibir para cada cotação o símbolo da moeda seu respectivo valor com exatamente quatro casas decimais. Você pode usar o método `.toFixed()` do objeto Number para fazer isso. [https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Number/toFixed](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Number/toFixed)