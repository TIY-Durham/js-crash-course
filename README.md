# JavaScript Crash Course

* What is HTML?
* What is CSS?
* What is JavaScript?
* What can I _do_ with them?

---

## What can I do with JavaScript?

### Basic Syntax

### Simple Types -- single, atomic values

* `null` -- Intentionally Empty
* `Boolean` -- Yes or No, there is no Maybe
* `Number` -- Everything has a decimal point, whether you want it or not.
  * integer math can be screwy
  * computers are bad at [fractional numbers](https://en.wikipedia.org/wiki/Fraction_(mathematics))
* `String` -- Any text, delimited by single- or double-quotes
  * can be "added" together via _concatenation_
  * modifying produces a _different_ value

### Container Types -- collections

* `Array` -- a numbered list of "elements" or "items"
  * all elements have a corresponding `Number` called an "index"
  * element numbering is automatic and starts with `0`
  * internally track the number of items: the "length" of the list
  * allows items to be added and removed via special action words: "methods"
  * allows access to each item via square brackets: `list[index]`
* `Object` -- a dictionary of "keys" mapped to "values"
  * every key is _always_ a `String` in JavaScript
  * allows access to each value via dot notation: `dictionary.key`

### It's Complicated...

* `Function` -- a snippet of code to run later
  * optionally accepts a list of inputs: "parameters" or "arguments"
  * _always_ provides an output via a `return` statement, `undefined` otherwise
  * optionally produces side-effects by altering its "scope"

