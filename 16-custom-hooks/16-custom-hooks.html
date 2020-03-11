<body>
  <div id="root"></div>
  <script src="https://unpkg.com/react@16.12.0/umd/react.development.js"></script>
  <script src="https://unpkg.com/react-dom@16.12.0/umd/react-dom.development.js"></script>
  <script src="https://unpkg.com/@babel/standalone@7.8.3/babel.js"></script>
  <script type="text/babel">
    function useLocalStorageState(key, defaultValue = '') {
      const [state, setState] = React.useState(
        () => window.localStorage.getItem(key) || defaultValue,
      )

      React.useEffect(() => {
        window.localStorage.setItem(key, state)
      }, [key, state])

      return [state, setState]
    }

    function Greeting() {
      const [name, setName] = useLocalStorageState('name')

      const handleChange = event => setName(event.target.value)

      return (
        <div>
          <form>
            <label htmlFor="name">Name: </label>
            <input value={name} onChange={handleChange} id="name" />
          </form>
          {name ? <strong>Hello {name}</strong> : 'Please type your name'}
        </div>
      )
    }

    ReactDOM.render(<Greeting />, document.getElementById('root'))
  </script>
</body>
