# Swift Function Parameter Label Error

This example demonstrates a common error in Swift related to function parameters.  The `calculateArea` function is correctly defined, but it's called incorrectly in one instance.  Omitting the parameter label `width:` leads to a compiler error because Swift cannot determine which argument corresponds to which parameter.

This repository highlights the importance of using parameter labels consistently when calling functions in Swift to avoid ambiguity and ensure correct execution.