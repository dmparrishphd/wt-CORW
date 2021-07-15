normalize.weights
=================

Usage
-----

    normalize.weights(x)
    
| Argument | Description        |
| -------: | :----------------- |
|        x | a `numeric` vector |

Value
-----

A vector of the same "proportions" as `x` (within the tolerance of floating-point division).

Examples
--------

    normalize.weights(1:3)
    # [1] 0.1666667 0.3333333 0.5000000
