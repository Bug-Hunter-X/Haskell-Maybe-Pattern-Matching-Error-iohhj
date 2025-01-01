# Haskell Maybe Pattern Matching Error
This repository demonstrates a common error in Haskell programming involving pattern matching on Maybe values.  The `bug.hs` file contains code that fails to handle the `Nothing` case, resulting in a runtime error.  The solution is shown in `bugSolution.hs`. 

**Bug Description:** The provided Haskell function `myFunction` uses pattern matching to handle `Just` values but omits handling for `Nothing`.  When called with `Nothing`, it throws an error rather than gracefully handling the absence of a value.

**Solution:** The `Nothing` case must be explicitly handled to prevent runtime errors.  Proper handling usually involves returning a default value or performing alternative actions.