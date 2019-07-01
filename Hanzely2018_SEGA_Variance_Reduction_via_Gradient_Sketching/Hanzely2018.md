Basic idea is given sketches, how to do gradient descent. Let's say sketches are $S^\intercal \nabla f(x)$. The gradients are computed via:

$ h^{k+1} = \arg\min \|h-h^k\| \\ st. S^\intercal h =S^\intercal \nabla f(x) $

It is a nice idea and theory suggest good convergence for the case of convex functions.
