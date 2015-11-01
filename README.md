# zTone

*JavaScript Code Principles and Style Guide*

There are many perfect guides and tutorials how to write clear and well understandable code. Also our world has such outstanding tools to control clearness of JavaScript code as JSLint. Instead of reinventing the wheel I want to formulate some common principles and approaches for writing clear, well readable, self-explained, efficient JavaScript code, certainly, from my point of view. The ideas expressed here can use for creating own detailed style guides and conventions inside developer teams. So...

- Use well known acronyms and shorthands to make naming of auxiliary identifiers in your code (e.g. function parameters, counters etc.) more consistent and self-explained. I've collected a list (look at it below) of the most common and frequent cases which may appear in a code. They have optimal balance between brevity and intelligibility. You shouldn't go to extremes and use one-letter or even one-symbol identifiers like "_", "$" (despite their validity) except counters in loops like "i", "j", "k" etc.

SHORTHAND |FULL
----------|----------
ch, char  |character
ctx       |context
el, elem  |element
evt** * **|event
ex        |exception
expr      |expression
fn, func  |function
idx       |index
init      |initial
pts       |points
pos       |position
res       |result
ret       |return
str       |string

* **evt** because **e** or **event** are not appropriate for this purpose. **e** could mean the mathematical constant and, generally, is too ambiguous and overall. On the other hand, **event** isn't suitable because in event model of old IE browser creates a property of the global object with this name `window.event` when some event occurs. So, if you're dealing with IE you should keep this fact in mind.

## Various style guides and code conventions

- [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript#airbnb-javascript-style-guide-)
- [Idiomatic.js](https://github.com/rwaldron/idiomatic.js#principles-of-writing-consistent-idiomatic-javascript)

## Versions

Actual version of zTone is 0.1.0-alpha.