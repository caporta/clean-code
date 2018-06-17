Ch 1. - Clean Code
------------------
- LeBlanc's law: _"Later equals never."_

Ch 2. - Meaningful Names
------------------------
- The length of a name should correspond to the size of its scope
- Don't be cute
- Pick one word per concept
- Default to _solution_ domain names, then to _problem_ domain names
  - i.e. programmers read your code, so speak to them
- Don't add gratuitous context

Ch 3. - Functions
-----------------
- They should be small
- They should _do one thing_
  - If a function does only those steps one level of abstraction
    below the stated name of the function, it is doing one thing
  - A function is doing more than one thing if you can extract
    another function from it with a name that isn't merely a
    restatement of its implementation
  - Using a _**TO**_ paragraph can be a useful measure of this
  - Annotated "sections" are a smell
- One level of abstraction per function
