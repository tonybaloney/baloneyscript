# baloneyscript
An absurdly verbose script language.

This is primarily a demo of the ``lark`` parser module in Python

This package includes a Visual Studio Code plugin for syntax highlighting.

The compiler generates **statically linked standalone binaries**.

## Variable assignment

### Numberish

```baloney
my_variable is a number with a value of 1
```

### String-like

```baloney
my_string_variable is a string with a value of "hello"
```

## Numeric operations

### Increment/Decrement

```
increment my_variable
```

```
decrement my_variable
```

### Augmented operations

```
add 5 to the value of my_variable
```

```
subtract 5 to my_variable
```

## Printing

Print a string literal, only with double-quotes

```
print "hello world"
```

Or, print the value of a variable

```
print the value of my_variable
```
