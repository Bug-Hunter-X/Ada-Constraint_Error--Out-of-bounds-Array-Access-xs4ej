# Ada Constraint_Error: Out-of-bounds Array Access

This example demonstrates a common error in Ada: accessing an array element outside of its defined index range.  Ada's strong typing system helps catch this at runtime, raising a `Constraint_Error` exception.  The solution involves carefully checking array indices before accessing elements to prevent this runtime error. The files `bug.ada` and `bugSolution.ada` demonstrate the problem and its correction.
