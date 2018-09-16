### Quiz

Check your understanding so far. Make sure to play the part of *Engine* and have a "conversation" with the *Scope*:

```js
function foo(a) {
	var b = a;
	return a + b;
}

var c = foo( 2 );
```

1. Identify all the LHS look-ups (there are 3!).

2. Identify all the RHS look-ups (there are 4!).

### Answers

1.  - c will be found first 
    - then a = 2 because c has run 
    - then b because a now exists.

2.  - foo(2 will be found first
    - = a will then be found now that we know a
    - then a and b as the return fires.
