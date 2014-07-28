# Ricky Bobby's World (Performance)
#### Brian Lonsdorf

- Javascript w/out the this (article, look up)
- SuperAgent

## Declarative Coding (vs imperative)

### Loop fusion

compose(map(g1, map(f1))) == map(compose(g of f))

### Shortcut Fusion

- Fusing folds (map + sum -> one iteration)
- "deforestation"

### Memoization

- Future (like promise, but tell to run). Pure. ~look it up
- monet.js

### Parallel code

- f(f(x,y),z) = f(x, f(y, z))

- River trial, web workers

- liftA3(fn, A1, A2, A3)

- **"Can run js in parallel"**

### Compile while you compose

- **lazy.js**

- **rephrase.js** (@puffnfresh)

- Declarative
  - write once, run everywhere

- **Try to write the stuff you want to write**

- **As app developers (not library developers), should focus on writing declarative, higher level code**
