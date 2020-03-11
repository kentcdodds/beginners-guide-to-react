<body>
  <div id="root"></div>
  <script src="https://unpkg.com/react@16.12.0/umd/react.development.js"></script>
  <script src="https://unpkg.com/react-dom@16.12.0/umd/react-dom.development.js"></script>
  <script src="https://unpkg.com/@babel/standalone@7.8.3/babel.js"></script>
  <script type="text/babel">
    const allItems = [
      {id: 'a', value: 'apple'},
      {id: 'o', value: 'orange'},
      {id: 'g', value: 'grape'},
      {id: 'p', value: 'pear'},
    ]

    function App() {
      const [items, setItems] = React.useState(allItems)

      function addItem() {
        setItems([...items, allItems.find(i => !items.includes(i))])
      }

      function removeItem(item) {
        setItems(items.filter(i => i !== item))
      }

      return (
        <div>
          <button disabled={items.length >= allItems.length} onClick={addItem}>
            add item
          </button>
          <ul style={{listStyle: 'none', paddingLeft: 0}}>
            {items.map(item => (
              <li>
                <button onClick={() => removeItem(item)}>remove</button>{' '}
                <label htmlFor={`${item.value}-input`}>{item.value}</label>{' '}
                <input id={`${item.value}-input`} defaultValue={item.value} />
              </li>
            ))}
          </ul>
        </div>
      )
    }

    ReactDOM.render(<App />, document.getElementById('root'))
  </script>

  <script type="text/babel">
    function FocusDemo() {
      const [items, setItems] = React.useState([
        {id: 'a', value: 'apple'},
        {id: 'o', value: 'orange'},
        {id: 'g', value: 'grape'},
        {id: 'p', value: 'pear'},
      ])

      React.useEffect(() => {
        const interval = setInterval(() => {
          setItems(shuffle(items))
        }, 1000)
        return () => clearInterval(interval)
      }, [])

      return (
        <div>
          <div>
            <h1>Without Key</h1>
            {items.map(item => (
              <input value={item.value} />
            ))}
          </div>
          <div>
            <h1>With Key as Index</h1>
            {items.map((item, index) => (
              <input key={index} value={item.value} />
            ))}
          </div>
          <div>
            <h1>With Key</h1>
            {items.map(item => (
              <input key={item.id} value={item.value} />
            ))}
          </div>
        </div>
      )
    }

    function shuffle(originalArray) {
      const array = [...originalArray]
      let currentIndex = array.length
      let temporaryValue
      let randomIndex
      // While there remain elements to shuffle...
      while (0 !== currentIndex) {
        // Pick a remaining element...
        randomIndex = Math.floor(Math.random() * currentIndex)
        currentIndex -= 1
        // And swap it with the current element.
        temporaryValue = array[currentIndex]
        array[currentIndex] = array[randomIndex]
        array[randomIndex] = temporaryValue
      }
      return array
    }
    // uncomment this line to demo:
    // ReactDOM.render(<FocusDemo />, document.getElementById('root'))
  </script>
</body>
