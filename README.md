# zTone

JavaScript Code Principles and Style Guide

There are many perfect guides and tutorials how to write clear and understandable code. Also our world has such outstanding tools to control clearness of JavaScript code as JSLint.
So I think that it's not necessary and even a bad idea to compose something in this sphere. Instead of reinventing the wheel I want to formulate some common principles and approaches for 
writing clear, well readable, self-explained, efficient JavaScript code. The ideas expressed here can use for creating own detailed style guides inside developer teams.

- Use well known acronyms and shorthands to make naming of auxiliary identifiers in your code (e.g. function parameters, counters etc.) more consistent and self-explained. I've collected a list (look at it below) of the most common and frequent cases which may appear in a code. They have optimal balance between brevity and intelligibility. You shouldn't go to extremes and use one-letter or even one-symbol identifiers like "_", "$" (despite their validity) except counters in loops like "i", "j", "k" etc.

SHORTHAND |FULL
----------|----------
ch, char  |character
ctx       |context
el, elem  |element
e, evt    |event
ex        |exception
fn, func  |function
idx       |index
init      |initial
pts       |points
pos       |position
res       |result
ret       |return
str       |string


## Versions

Actual version of zTone is 0.1.0-alpha.