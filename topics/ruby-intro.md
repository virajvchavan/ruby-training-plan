<!-- Interns will be trying little things out in irb as we teach  -->

https://launchschool.com/books/ruby/read/

Intro:
  - It emphasizes the necessity for software to be understood by humans first and computers second.
  - a high level language
  - interpreted language
  - Ruby abstracts away (i.e. handles for you) most of the complex details of the machine
  - flexibility
  - performance (why it is slower)
  - everything is an object

Style guidelines:
  - indenting: 2 spaces for a tab
  - variable and method names: use snake_case
  - CONSTANT declarations
  - ClassName: CamelCase
  - single line and multiline blocks
  - string '' cs ""

Strings:
  - interpolation
  - escape chars

Symbols

Numbers:
  - int, float

Boolean

nil:
  - nothing

Operators:
  - + * / % == === < > && || !

Type conversion:
  to_i, to_s etc

Data Strictures:
  - Array
  - Hash

Variables:
  - assigninig values
  - CONSTANTS
  - $global_variables
  - scope of variables

Methods:
  - why?
  - how in ruby
  - params, arguments
  - default arguments
  - variable scope in methods
  - method chaining
  - methods as arguments?

Conditionals:
  - if else unless
  - ternary
  - switch case


----------------------------------------------------
Questions:
- Difference between "string" and "symbol" in ruby?
- What is "nil" in ruby, is it an object?
- Difference between "nil" and empty string ""?
- Difference between "==" and "==="
- Difference between single quote and double quote
- [
    a = "hi there"
    b = a
    a = "not here"
    puts b
  ]

  [
    a = "hi there"
    b = a
    a << ", Bob"
    puts b
  ]

  - what is the value of b printed in each of the above?
  - why?
