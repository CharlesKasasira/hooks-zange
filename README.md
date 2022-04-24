# my-hooks

A collection of npm packages

Install
```bash
npm install --save hooks-zange
```

useMediaQuery

```js
import { useMediaQuery } from "hooks-zange"

export default function MyComponent(){
    const matches = useMediaQuery('(min-width: 800px)')

    return (
        //...
    )
}

```
