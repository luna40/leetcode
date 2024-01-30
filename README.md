# Example usage:

## code example

`code`

```javascript
// using the rest parameter (...) to allow a function to take any arguments
const f = createHelloWorld();
console.log(f({}, null, 42)); //hello word
```

### In this modification, the inner function uses the rest parameter...args to collect any arguments passed to it, but it doesn't use these arguments.

**Instead**, it always returns the string _"Hello World,"_ ensuring that the function behaves as expected regardless of the provided arguments.
