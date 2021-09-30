##Import structure of base Hooks:

componentDidMount = initialized

    - only happens once, added to the UI

componentDidUpdate = state updated

    - reactice data is updated

componentWillUnmount = destroyed

    - removed from the UI

useEffect = update state

    - happens when mounted & when updates are needed

createContext = create variable accessible by children components

useContext = store/share data

    - share data without passing props

useRef = create a mutable object that will keep the same ref between renders

    - doesn't trigger a rerender

useReducer = redux pattern of updating state

    - [state, dispatch]

useMemo = optimize computation cost

    - use only when necessary, cache result of function

useCallback = memoize of function

    - good when function is used often in children
