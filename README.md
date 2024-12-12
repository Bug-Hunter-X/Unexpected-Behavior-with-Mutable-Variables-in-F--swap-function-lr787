# F# Mutable Variable Swap Bug

This example demonstrates a common pitfall when working with mutable variables in F#.  Due to pass-by-reference semantics, attempting to swap the values of two mutable variables using a function can lead to unexpected results if not handled carefully. 

The `bug.fs` file contains code that illustrates the issue. The `bugSolution.fs` file shows how to correctly swap the variables.