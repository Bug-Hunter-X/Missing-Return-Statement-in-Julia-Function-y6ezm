# Julia Function Bug: Missing Return Statement

This repository demonstrates a common error in Julia functions: a missing return statement when neither condition in an `if-else` block is met. This leads to unexpected errors during function execution.

The `bug.jl` file contains the erroneous code, illustrating the problem.

The solution in `bugSolution.jl` shows how to correct the function by adding a return statement to handle the case when the conditions are not met.  This also showcases the need for explicit return statements. 

This example highlights the importance of writing robust and complete functions in Julia to avoid runtime errors.