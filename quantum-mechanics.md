## Mathematical Foundations

### Definitions

A **Vector Space** is a set of "vectors" which is closed under addition and scalar multiplication. That is, if \( \psi, \phi \in \mathbf V \), then \( a\phi + b \psi \in \mathbf V \). Note, that if the scalars are *real numbers*, we refer to the vector space as a *Real Vector Space*. If the scalars are complex, then it is a *Complex Vector Space*. In quantum mechanics, we'll mostly be dealing with complex vector spaces.

A set of vectors is **linearly dependent** if \[ \sum c_n \phi_n = 0 \] for some \( c_n \) not all zero. In other words, a set of vectors is linearly dependent if any one of them can be written as a linear combination of the others. If you cannot write \[ \sum c_n\phi_n = 0 \] for any non-trivial \( c_n \), then the set of vectors \( \phi_n \) is said to be **linearly independent**.

The **dimension** of a vector space is the maximum number of linearly independent vectors.