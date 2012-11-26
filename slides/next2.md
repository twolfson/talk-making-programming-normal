```js
// Easily combine commands into one command
// which *itself* could be tested
{
  'algorithm': ['algo1', 'algo2', 'algo3']
  // or in grunt world 'algo1, algo2, algo3'
}
```


```js
// Gotchas you might be curious about
{
  // Since names can be quite brittle, we can alias them to simpler forms
  // This is kind of frustrating if you want to tweak wording so I would love to hear suggestions
  'abc': 'xyz'
}