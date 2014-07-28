# Unorthodox Performance
#### John-David Dalton @jdalton

- jsperf.com
- github.com/lodash/lodash

- Optimize for common case
- Interesting - modifying function arguments immediately disqualifies function from browser optimization
  - so does try/catch
  - as does size of function (too big, not optimized)

- Native functions are not always fast
- ES6 set, what is it?

### Underscore has a method to tell if a function is native or not
- i.e. not shimmed ala old versions of prototype
- It checks the function's toString and sees if there's a "native"

- Interesting - lodash does curry/bind by using only 1 function + metadata!
