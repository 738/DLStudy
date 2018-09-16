# LEC 03

2018.09.16

## Simplified hypothesis

## What cost(W) looks like?

### W=1, cost(W)=?

## Gradient descent algorithm (경사하강법)

- Minimize cost function
- Gradient descent is used many minimization problems
- For a given cost function, cost (W, b), it will find W, b to minimize cost
- It can be applied to more general function: cost (w1, w2, ...)

### How it works?

How would you find the lowest point?

- Start with initial guesses
    - Start at 0,0 (or any other value)
    - Keeping changing W and b a little bit to try and reduce cost(W, b)
- Each time you change the parameters, you select the gradient which reduces cost(W, b) the most possible
- Repeat
- Do so until you converage to a local minimum
- Has an interesting property
    - Where you start can determine which minimum you end up

## Formal definition

## Convex function

Convex function인지 확인해야 Gradient descent algorithm을 적용할 수 있음