<body>
  <div id="root"></div>
  <script src="https://unpkg.com/react@16.12.0/umd/react.development.js"></script>
  <script src="https://unpkg.com/react-dom@16.12.0/umd/react-dom.development.js"></script>
  <script src="https://unpkg.com/@babel/standalone@7.8.3/babel.js"></script>
  <script type="text/babel">
    function PokemonInfo({pokemonName}) {
      const [pokemon, setPokemon] = React.useState(null)

      React.useEffect(() => {
        if (!pokemonName) {
          return
        }
        fetchPokemon(pokemonName).then(pokemonData => {
          setPokemon(pokemonData)
        })
      }, [pokemonName])

      if (!pokemonName) {
        return 'Submit a pokemon'
      }

      if (!pokemon) {
        return '...'
      }

      return <pre>{JSON.stringify(pokemon, null, 2)}</pre>
    }

    function App() {
      const [pokemonName, setPokemonName] = React.useState('')

      function handleSubmit(event) {
        event.preventDefault()
        setPokemonName(event.target.elements.pokemonName.value)
      }

      return (
        <div>
          <form onSubmit={handleSubmit}>
            <label htmlFor="pokemonName">Pokemon Name</label>
            <div>
              <input id="pokemonName" />
              <button type="submit">Submit</button>
            </div>
          </form>
          <hr />
          <PokemonInfo pokemonName={pokemonName} />
        </div>
      )
    }

    function fetchPokemon(name) {
      const pokemonQuery = `
        query ($name: String) {
          pokemon(name: $name) {
            id
            number
            name
            attacks {
              special {
                name
                type
                damage
              }
            }
          }
        }
      `

      return window
        .fetch('https://graphql-pokemon.now.sh', {
          // learn more about this API here: https://graphql-pokemon.now.sh/
          method: 'POST',
          headers: {
            'content-type': 'application/json;charset=UTF-8',
          },
          body: JSON.stringify({
            query: pokemonQuery,
            variables: {name},
          }),
        })
        .then(r => r.json())
        .then(response => response.data.pokemon)
    }

    ReactDOM.render(<App />, document.getElementById('root'))
  </script>
</body>
