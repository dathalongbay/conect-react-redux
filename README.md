# conect-react-redux
5 cách connect Redux Actions trong ReactJS
# https://viblo.asia/p/5-cach-connect-redux-actions-trong-reactjs-07LKXBAplV4

# https://react-redux.js.org/using-react-redux/connect-mapdispatch
```
import { increment, decrement, reset } from './counterActions'

const actionCreators = {
  increment,
  decrement,
  reset,
}

export default connect(mapState, actionCreators)(Counter)

// or
export default connect(mapState, { increment, decrement, reset })(Counter)
```
### https://react-redux.js.org/api/hooks
