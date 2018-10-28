# Awesome React Snippets

These snippets include all the different types of component structures you might want to use including the new [React.memo](https://reactjs.org/blog/2018/10/23/react-v-16-6.html#reactmemo) or "Memoized" React function component.

## Snippets

| Snippet | Renders                           |
| ------- | --------------------------------- |
| `rc`    | React Component                   |
| `rpc`   | React PureComponent               |
| `rfc`   | React Function Component          |
| `rfcm`  | React Function Component Memoized |
| `rp`    | React PropTypes                   |

## Full Expansions

### rc - React Component

```javascript
import React from 'react';

export default class | extends React.Component {
  render() {
    return ( | );
  }
}
```

### rpc - React PureComponent

```javascript
import React from 'react';

export default class | extends React.PureComponent {
  render() {
    return ( | );
  }
}
```

### rfc - React Function Component

```javascript
import React from 'react';

export default function |() {
  return ( | );
}
```

### rfcm - React Function Component Memoized

```javascript
import React from 'react';

export default React.memo(function |() {
  return ( | );
});
```

### rp - React PropTypes

```javascript
import PropTypes from 'prop-types';
```

## Commands

### React: class to className

Changes all occurences of `class` in JSX to `className`. This transform is safe
to run multiple times on any document. No text needs to be selected as the
command is executed on the entire document.

![React: class to className](https://i.imgur.com/i1ZwvOu.gif)
