### An implementaion of "OCaml with labeled and optional arguments" mini-language

This is a homework for functional programming course. For more information see [course repo](https://github.com/Kakadu/fp2022).

License: LGPL for implementation code + WTFPL for test examles in miniLanguage

Author: Denis Porsev, den.porsev@gmail.com

--- 

### Implementation features:

- Parser
- Interpreter
- Pretty-printing for ast types, values and errors
- Simple read-eval-print-loop
- Integration tests
- Type inference with polymorphism

--- 

### Language features:

#### Supported language features:
- Primitive types: booleans, integers, unit type, lists
- Binary operators: addition, multiplication, subtraction, division, comparisons, logical 'or' and logical 'and'
- Let expressions and definitions
- Functions: basic, anonymous, recursive, closures; partial application is available
- Labeled and optional arguments

You can see these features in use in [demos/demoSingle.t](demos/demoSingle.t)

#### Possible language extensions:
- Unary operators, pattern matching, option types
