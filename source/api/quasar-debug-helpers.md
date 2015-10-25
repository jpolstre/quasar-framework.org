title: Quasar Debug Helpers
type: api
order: 3
---

The `quasar.debug` object has useful debugging methods.

## Javascript Stack
``` js
quasar.debug.printStack()
```
Useful when stuck somewhere in the code and you'd like to see the Javascript stack outputted to the console.

## Profiling

Sometimes you want to know how much time did something take to get executed. Example:
``` js
quasar.debug.profile('xyz');
//run some code... then to output results:
quasar.debug.profile('xyz');
```
You can have multiple profiles running at the same time.