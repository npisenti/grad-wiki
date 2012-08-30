## Important techniques

* **Asymptotic methods** -- ie, approximation methods

## Important Theorems

**Gauss' Theorem** states that the divergence of a vector field, integrated over some volume \( V \), is equivalent to the integral of that vector field over the surface \( S \) bounding \( V \). In other words, 

\[ \int_{\mathbf V} \left( \vec \nabla \cdot \vec A \right) d^3 x  = \int_{\mathbf S}  \vec A \cdot \vec{ds}\]

**Stoke's Theorem** states that the curl of a vector field \( \vec A \) integrated over some surface \( S \) is equivalent to the path-integral of \( \vec A \) around the edge bounding the surface \( S \). That is, 

\[ \int_{\mathbf S} \left( \vec \nabla \times \vec A \right) \cdot \vec{ds} = \oint_{\mathbf C} \vec A \cdot \vec{dl} \]

## Complex Analysis

Generally speaking, *complex analysis* follows the progression of (functional) *real analysis* by first defining functions \( f(x) \), then their derivatives and anti-derivatives, Taylor Series, differential equations, etc. The program for complex analysis in this class will do the same, but for complex numbers \( z = x + iy \).

**Define a function** \( f(z) \), where \( z = x + iy \), as

\[ f(z) = u(x, y) + i v(x,y) \]

Note, however, that the functions \( u(x,y) \) and \( v(x,y) \) are related by the [Cauchy-Reimann criteria](http://en.wikipedia.org/wiki/Cauchy%E2%80%93Riemann_equations) if the function \( f(z) \) is **analytic** (loosely, if \( f(z) \) is *differentiable*). In complex analysis, a complex function will always be analytic if it can be written as \( f(z) \) as opposed to \( f(z, z^* ) \).

The **Cauchy-Riemann equations** relating \( u(x,y) \) and \( v(x,y) \) for analytic functions are

\[ \frac{\partial u}{\partial x} = \frac{\partial v}{\partial y} \]

and

\[ \frac{\partial u}{\partial y} = - \frac{\partial v}{\partial x}  \]