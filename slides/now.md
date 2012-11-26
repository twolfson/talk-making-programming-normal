# The Present

```js
// Snippet of BDD -- vows preferred
```

// The above snippet is BDD in my favorite flavor

// It comes in other flavors which are probably more familiar

// TODO: Show side slide of mocha/jasmine syntax

// But let's get back to the vows test

// Each test can be read as a descriptive sentence

// Sentence are written in parts which describie what is occurring at each step of the algorithm

// e.g. `A banana` is a banana object and `that is peeled` gives performs the `peel` method on that banana

// As a result, any assertion that fails will quickly compose the sentence leading up to it

// e.g. `A banana that is peeled is soft (Expected: true, Actual: false)` quickly tells us that something is wrong in the `peel` method since the assertion for `A banana is hard` asserted properly.