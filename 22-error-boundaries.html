<body>
  <div id="root"></div>
  <script src="https://unpkg.com/react@16.12.0/umd/react.development.js"></script>
  <script src="https://unpkg.com/react-dom@16.12.0/umd/react-dom.development.js"></script>
  <script src="https://unpkg.com/@babel/standalone@7.8.3/babel.js"></script>
  <script src="https://unpkg.com/react-error-boundary@1.2.5/dist/umd/react-error-boundary.js"></script>
  <script type="text/babel">
    const ErrorBoundary = ReactErrorBoundary.ErrorBoundary
    // class ErrorBoundary extends React.Component {
    //   state = {error: null}
    //   static getDerivedStateFromError(error) {
    //     return {error}
    //   }
    //   render() {
    //     const {error} = this.state
    //     if (error) {
    //       return <this.props.FallbackComponent error={error} />
    //     }

    //     return this.props.children
    //   }
    // }

    function ErrorFallback({error}) {
      return (
        <div>
          <p>Something went wrong:</p>
          <pre>{error.message}</pre>
        </div>
      )
    }

    function Bomb() {
      throw new Error('💥 CABOOM 💥')
    }

    function App() {
      const [explode, setExplode] = React.useState(false)
      return (
        <div>
          <div>
            <button onClick={() => setExplode(true)}>💣</button>
          </div>
          <div>
            <ErrorBoundary FallbackComponent={ErrorFallback}>
              {explode ? <Bomb /> : 'Push the button Max!'}
            </ErrorBoundary>
          </div>
        </div>
      )
    }
    ReactDOM.render(<App />, document.getElementById('root'))
  </script>
</body>
