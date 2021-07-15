invert.weights
==============

Usage
-----

    invert.weights(x)
    
| Argument | Description        |
| -------: | :----------------- |
|        x | a `numeric` vector |

Value
-----

Provided that there are no zero-values in `x`, the numerical inverse of `x`;
Otherwise, a `vector` of ones and zeros, where `1` occurs at the same index as zero-values in `x`, and the other values are `0`.

Details
-------

Originally developed as part of an inverse distance weighting (IDW) scheme.
