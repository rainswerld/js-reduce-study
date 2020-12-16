# Reduce Study

## Processing all array elements with an accumulator

The
[reduce](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce)
method returns a single value from operating on all the values in the array. It
"reduces" many values to one value. The original array does not change.

Take your time and methodically walk-through the "How reduce works" section at
the above link. Then, try running the following snippets (taken from the link
above) in the `node` repl environment:

```js
[0, 1, 2, 3, 4].reduce(function(accumulator, currentValue, currentIndex, array) {
  return accumulator + currentValue
})

[0, 1, 2, 3, 4].reduce((accumulator, currentValue, currentIndex, array) => {
    return accumulator + currentValue
}, 10)
```

Play around with the examples above, then walk through the steps in `bin/reduce.js`
 to use see what else reduce can do.

## Additional Resources

- [A Guide To The Reduce Method In Javascript​](https://medium.freecodecamp.org/reduce-f47a7da511a9)
