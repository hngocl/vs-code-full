# VS Code React Native Snippets Full


This extension provides you JavaScript and React/Redux snippets in ES7 with Babel plugin features for [VS Code](https://code.visualstudio.com/)

## Installation

### Visual Studio Marketplace

Launch _Quick Open_:

- [_Linux_](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf): `Ctrl+P`
- [_macOS_](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf): `⌘P`
- [_Windows_](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf): `Ctrl+P`

Paste the following command and press `Enter`:

```shell
ext install hngocl.react-native-snippets-full
```

### GitHub Repository Clone

Change to your `.vscode/extensions` [VS Code extensions directory](https://code.visualstudio.com/docs/extensions/install-extension#_side-loading).
Depending on your platform it is located in the following folders:

- _Linux_: `~/.vscode/extensions`
- _macOS_: `~/.vscode/extensions`
- _Windows_: `%USERPROFILE%\.vscode\extensions`

Clone the Material Theme repository as `hngocl.react-native-snippets-full`:

```shell
git clone https://github.com/hngocl/vs-code-full.git
```

## Search command

You can search through snippets with `ES7 snippet search` command which can be run with `CMD + Shift + P` or just use `CMD + Shift + R` (`CTRL + ALT + R` for Windows & Linux) keybinding.

Here is direct link to marketplace [React Native Snippets Full](https://marketplace.visualstudio.com/items?itemName=hngocl.react-native-snippets-full)

## Supported languages (file extensions)

- JavaScript (.js)
- JavaScript React (.jsx)
- TypeScript (.ts)
- TypeScript React (.tsx)

## Snippets info

Every space inside `{ }` and `( )` means that this is pushed into next line :)
`$` represent each step after `tab`.

## Basic Methods

|  Prefix | Method                                              |
| ------: | --------------------------------------------------- |
|  `imp→` | `import moduleName from 'module'`                   |
|  `imn→` | `import 'module'`                                   |
|  `imd→` | `import { destructuredModule } from 'module'`       |
|  `ime→` | `import * as alias from 'module'`                   |
|  `ima→` | `import { originalName as aliasName} from 'module'` |
|  `exp→` | `export default moduleName`                         |
|  `exd→` | `export { destructuredModule } from 'module'`       |
|  `exa→` | `export { originalName as aliasName} from 'module'` |
|  `enf→` | `export const functionName = (params) => { }`       |
|  `edf→` | `export default (params) => { }`                    |
|  `fre→` | `arrayName.forEach(element => { }`                  |
|  `fof→` | `for(let itemName of objectName { }`                |
|  `fin→` | `for(let itemName in objectName { }`                |
| `anfn→` | `(params) => { }`                                   |
|  `nfn→` | `const functionName = (params) => { }`              |
|  `dob→` | `const {propName} = objectToDescruct`               |
|  `dar→` | `const [propName] = arrayToDescruct`                |
|  `sti→` | `setInterval(() => { }, intervalTime`               |
|  `sto→` | `setTimeout(() => { }, delayTime`                   |

## React

|      Prefix | Method                                                                              |
| ----------: | ----------------------------------------------------------------------------------- |
|      `imr→` | `import React from 'react'`                                                         |
|     `imrc→` | `import React, { Component } from 'react'`                                          |
|    `imrpc→` | `import React, { PureComponent } from 'react'`                                      |
|     `imrm→` | `import React, { memo } from 'react'`                                               |
|    `redux→` | `import { connect } from 'react-redux'`                                             |
|   `rconst→` | `constructor(props) with this.state`                                                |
|      `cwm→` | `componentWillMount = () => { }` DEPRECATED!!!                                      |
|      `cdm→` | `componentDidMount = () => { }`                                                     |
|      `cwr→` | `componentWillReceiveProps = (nextProps) => { }` DEPRECATED!!!                      |
|      `scu→` | `shouldComponentUpdate = (nextProps, nextState) => { }`                             |
|     `cwup→` | `componentWillUpdate = (nextProps, nextState) => { }` DEPRECATED!!!                 |
|     `cdup→` | `componentDidUpdate = (prevProps, prevState) => { }`                                |
|     `cwun→` | `componentWillUnmount = () => { }`                                                  |
|      `sst→` | `this.setState({ })`                                                                |
|      `ssf→` | `this.setState((state, props) => return { })`                                       |
|    `props→` | `this.props.propName`                                                               |
|    `state→` | `this.state.stateName`                                                              |

## React Hooks

- All hooks from [official docs](https://reactjs.org/docs/hooks-reference.html) are added with hook name prefix.

## React Native

|     Prefix | Method                                 |
| ---------: | -------------------------------------- |
|    `imrn→` | `import { $1 } from 'react-native'`    |

## Redux

|       Prefix | Method                    |
| -----------: | ------------------------- |
|  `rxaction→` | `redux action template`   |
|   `rxconst→` | `export const $1 = '$1'`  |
| `rxreducer→` | `redux reducer template`  |


## Console

| Prefix | Method                              |
| -----: | ----------------------------------- |
| `clg→` | `console.log(object)`               |
| `clo→` | `console.log("object", object)`     |
| `ctm→` | `console.time("timeId")`            |
| `cte→` | `console.timeEnd("timeId")`         |
| `cas→` | `console.assert(expression,object)` |
| `ccl→` | `console.clear()`                   |
| `cco→` | `console.count(label)`              |
| `cdi→` | `console.dir`                       |
| `cer→` | `console.error(object)`             |
| `cgr→` | `console.group(label)`              |
| `cge→` | `console.groupEnd()`                |
| `ctr→` | `console.trace(object)`             |
| `cwa→` | `console.warn`                      |
| `cin→` | `console.info`                      |

## React Native Components

### `rnhm`

```javascript
import React, { memo } from 'react'
import { View, Text } from 'react-native'

const FileNameComponent = () => {
    return (
        <View>
            <Text></Text>
        </View>
    )
}

export default FileName = memo(FileNameComponent,isEqual)
```

### `rnhms`

```javascript
import React, { memo } from 'react'
import { View, Text } from 'react-native'

const styles = StyleSheet.create({

});

const FileNameComponent = () => {
    return (
        <View>
            <Text></Text>
        </View>
    )
}

export default FileName = memo(FileNameComponent,isEqual)
```

### `rthm`

```typescript
import React, { memo } from 'react'
import { View, Text } from 'react-native'

interface FileNameProps {

}

const indexComponent = ({}:FileNameProps) => {
    return (
        <View>
            <Text></Text>
        </View>
    )
}

export default FileName = memo(FileNameComponent,isEqual)
```

### `rthms`

```typescript
import React, { memo } from 'react'
import { View, Text } from 'react-native'

const styles = StyleSheet.create({

});

interface FileNameProps {

}

const FileNameComponent = ({}:FileNameProps) => {
    return (
        <View>
            <Text></Text>
        </View>
    )
}

export default FileName = memo(FileNameComponent,isEqual)
```

### `timreducer`

```typescript
import { produce } from 'immer'
import * as Action from '';

export interface FileNameState {

}
const initialState: FileNameState = {

};
interface ActionProps {
    type: keyof typeof Action;
    payload: any;
}
export default
    produce((draftState: FileNameState, { type, payload }: ActionProps) => {
        switch (type) {
            default:
                break;
        }
    }, initialState)
```

### `rni`

```typescript
interface index {

}
```

### `erni`

```typescript
export interface index {

}
```

### `tsuseSelector`

```typescript
const {state} = useSelector<any>(x => x.state);
```

### `tsuseRef`

```typescript
const ref = useRef<any>(initialValue)
```

### `rxsaga`

```typescript
export function* functionName() {

}
```

### `useDispatch`

```typescript
const dispatch = useDispatch();
```

### `srtest`

```javascript
import React from 'react'
import renderer from 'react-test-renderer'
import { Provider } from 'react-redux'

import store from 'src/store'
import { ${1:ComponentName} } from '../${1:ComponentName}'

describe('<${1:ComponentName} />', () => {
  const defaultProps = {}
  const wrapper = renderer.create(
    <Provider store={store}>
      <${1:${TM_FILENAME_BASE}} {...defaultProps} />)
    </Provider>,
  )

  test('render', () => {
    expect(wrapper).toMatchSnapshot()
  })
})
```

### `sntest`

```javascript
import 'react-native'
import React from 'react'
import renderer from 'react-test-renderer'

import ${1:ComponentName} from '../${1:ComponentName}'

describe('<${1:ComponentName} />', () => {
  const defaultProps = {

  }

  const wrapper = renderer.create(<${1:ComponentName} {...defaultProps} />)

  test('render', () => {
    expect(wrapper).toMatchSnapshot()
  })
})
```

### `snrtest`

```javascript
import 'react-native'
import React from 'react'
import renderer from 'react-test-renderer'
import { Provider } from 'react-redux'

import store from 'src/store/configureStore'
import ${1:ComponentName} from '../${1:ComponentName}'

describe('<${1:ComponentName} />', () => {
  const defaultProps = {}
  const wrapper = renderer.create(
    <Provider store={store}>
      <${1:ComponentName} {...defaultProps} />
    </Provider>,
  )

  test('render', () => {
    expect(wrapper).toMatchSnapshot()
  })
})
```