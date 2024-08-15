# Pokedex

# Introdução ao Projeto

O Projeto a seguir é uma Pokedex criada com o objetivo de usar uma API para mostrar todos os pokemon e suas evoluções baseado na animação japonesa de sucesso "Pokemon"

![transferir-removebg-preview](https://github.com/user-attachments/assets/351c98d3-1052-4bdb-8163-6168552d37ce)

# Tecnologias Utilizadas

Javascript: Linguagem de Programação Interpretada Estruturada


Html: Linguagem de Marcação


CSS: Linguagem de Estilização 


Api's: para conseguirmos pegar os pokemon e seus dados

# Importações Necessárias
* Usamos este import para poder utilizar uma font que encaixe mais com o contexto do projeto
```py
* /* Importa a fonte 'Oxanium' do Google Fonts */
* @import url("https://fonts.googleapis.com/css?family=Oxanium:wgh@300;400;500;600;700;800&display=swap");
```

* utilizamos esta Const para chamar a API que utilizaremos em nossa pokedex para mostrar os dados e imagem dos pokemon
```py
 // Faz uma requisição à API do Pokémon
  const APIResponse = await fetch(`https://pokeapi.co/api/v2/pokemon/${pokemon}`);
```

# Funcionalidade
* este form serve para que possamos alocar o numero ou nome do pokemon desejado
```py
<form class="form">
      <input type="search" class="input__search" placeholder="Encontrar Pokémon" required>
      </label>
    </form>
```
* ja essas classes que serão estilizados para ficar dentro dos parametros da imagem servem para mostrar o Numero, Nome, Peso e Altura do pokemon antes escolhido
```py
<h1 class="pokemon__data">
      <span class="pokemon__number"></span>
      <span class="pokemon__name"></span>
    </h1>

    <h1 class="pokemon__infos">
      <span class="pokemon__height"></span>
      <span class="pokemon__weight"></span>
    </h1>
```
