# White space layout:
- essentially kernel style, with indentation provided by tabs (default = 8):
  - [kernel
layout](https://www.kernel.org/doc/html/latest/process/coding-style.html)
  - [Stroustrup layout
style](http://www.stroustrup.com/bs_faq2.html#layout-style)
- implemented in KDevelop editor as:
  Settings -> Source Formatter => C++ -> Stroustrup .

# Code:
- http://www.stroustrup.com/bs_faq2.html#Hungarian
- http://www.stroustrup.com/bs_faq2.html#constplacement

## Comments:
- doxygen compatible
- all classes, methods, structs, and variables to be commented

## File names:
- header files: <>.hpp
- source code files: <>.cpp

## Names
Names should be usefully descriptive and succinct.

###### Name spaces:
- all lower case

###### Collections:
- plural
- PascalCase
- format: NounDescription

###### Structs:
- singular
- PascalCase
- format: NounDescription

###### Classes:
- singular
- PascalCase
- format: NounDescription

###### Class methods:
- singular
- camelCase
- format: verbDescription

###### Variables:
- singular
- lower case
- underscore separated word(s)
- block local can be much shorter (e.g. 'i' as a loop counter)
