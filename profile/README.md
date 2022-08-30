# Wasm-Code

Hello there 👋!

I created this org as a playground for trying to get low level languages into the web-development circle.
In the future, you will find bundler plugins, editor support, supporting packages and docs here (hopefully).

The plan is to include support for most languages with a LLVM frontend, so languages like C, Rust, and [V](https://github.com/vlang/v). They would then be converted into wasm modules by the bundler, and all imports and glue code would be added.

The vision is to be able to just:

```ts
import { fib } from './lib/math.v'

const fib_50 = fib(50)
console.log(typeof fib_50)  // number
```

<br>
<br>
*Walks like TypeScript, runs like native.*
