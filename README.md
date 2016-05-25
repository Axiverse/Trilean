# Trilean
A ternary logic primitive.


```

Unary ! ( Negate ), tri

- | +
0 | 0
+ | -


Unary ~ ( Valued ), bool

- | +
0 | -
+ | +

Unary + ( Lean Positive ), bool

- | -
0 | +
+ | +

Unary - ( Lean Negative ), bool

- | -
0 | -
+ | +

Binary | ( Max ), tri

l\r - 0 +
- | - - +
0 | - 0 +
+ | + + +

Binary & ( Min ), tri

l\r - 0 +
- | - - -
0 | - 0 +
+ | - + +

Binary + ( Add ), tri

l\r - 0 +
- | - - 0
0 | - 0 +
+ | 0 + +

Binary - ( Sub ), tri

l\r - 0 +
- | 0 - -
0 | + 0 -
+ | + + 0

Binary ^ ( Lean Right ), tri

l\r - 0 +
- | - - -
0 | - 0 +
+ | + + +

l\r - 0 +
- | - - 0
0 | - 0 +
+ | 0 + +

Binary * ( Mul ), tri

l\r - 0 +
- | + 0 -
0 | 0 0 0
+ | - 0 +









Rotate Left

l\r - 0 +
- | + - 0
0 | - 0 +
+ | 0 + +

Rotate Right

l\r - 0 +
- | - - 0
0 | - 0 +
+ | 0 + -

Loop

l\r - 0 +
- | + - 0
0 | - 0 +
+ | 0 + -

+1

l\r - 0 +
- | 0 + +
0 | + + +
+ | + + +

-1

l\r - 0 +
- | - - -
0 | - - -
+ | - - 0


Binary ( Lean Left ), tri

l\r - 0 +
- | - - +
0 | - 0 +
+ | - + +



l\r - 0 +
- | -
0 |
+ |

```