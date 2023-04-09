# Notes

## Get `build` command working

Set environment variable to use legacy Open SSL provider

```sh
export NODE_OPTIONS=--openssl-legacy-provider
```

Add to the top of `App.js`

```js
import React from 'react'
```

## Tips

- React components must return have a single top-level JSX element.
  - You can use "fragments", i.e. `<>` and `</>` for this purpose
- `useState`
  - params
    - initialValue
  - returns
    - current value
    - function to change the value
