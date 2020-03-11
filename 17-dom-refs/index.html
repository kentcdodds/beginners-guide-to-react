<body>
  <div id="root"></div>
  <script src="https://unpkg.com/react@16.12.0/umd/react.development.js"></script>
  <script src="https://unpkg.com/react-dom@16.12.0/umd/react-dom.development.js"></script>
  <script src="https://unpkg.com/@babel/standalone@7.8.3/babel.js"></script>
  <script src="https://unpkg.com/vanilla-tilt@1.7.0/dist/vanilla-tilt.min.js"></script>
  <style>
    /*
    Taken from the vanilla-tilt.js demo site:
    https://micku7zu.github.io/vanilla-tilt.js/index.html
    */
    .tilt-root {
      height: 150px;
      background-color: red;
      width: 200px;
      background-image: -webkit-linear-gradient(
        315deg,
        #ff00ba 0%,
        #fae713 100%
      );
      background-image: linear-gradient(135deg, #ff00ba 0%, #fae713 100%);
      transform-style: preserve-3d;
      will-change: transform;
      transform: perspective(1000px) rotateX(0deg) rotateY(0deg)
        scale3d(1, 1, 1);
    }
    .tilt-child {
      position: absolute;
      width: 50%;
      height: 50%;
      top: 50%;
      left: 50%;
      transform: translateZ(30px) translateX(-50%) translateY(-50%);
      box-shadow: 0 0 50px 0 rgba(51, 51, 51, 0.3);
      background-color: white;
    }
    .totally-centered {
      width: 100%;
      height: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
    }
  </style>
  <script type="text/babel">
    function Tilt({children}) {
      const tiltRef = React.useRef()

      React.useEffect(() => {
        const tiltNode = tiltRef.current
        const vanillaTiltOptions = {
          max: 25,
          speed: 400,
          glare: true,
          'max-glare': 0.5,
        }
        VanillaTilt.init(tiltNode, vanillaTiltOptions)
        return () => {
          tiltNode.vanillaTilt.destroy()
        }
      }, [])

      return (
        <div ref={tiltRef} className="tilt-root">
          <div className="tilt-child">{children}</div>
        </div>
      )
    }

    function App() {
      const [showTilt, setShowTilt] = React.useState(true)
      return (
        <div>
          <label>
            <input
              type="checkbox"
              checked={showTilt}
              onChange={e => setShowTilt(e.target.checked)}
            />{' '}
            show tilt
          </label>
          {showTilt ? (
            <Tilt>
              <div className="totally-centered">vanilla-tilt.js</div>
            </Tilt>
          ) : null}
        </div>
      )
    }

    ReactDOM.render(<App />, document.getElementById('root'))
  </script>
</body>
