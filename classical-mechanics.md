## Definitions

**Generalized Coordinates** characterize the state of a system (they don't necessarily have to be spatial coordinates!). They are generally denoted \( q_i(t) \) for some \( i = 1, 2, \ldots \).

**Action** is the integral between two times \( t_1 \) and \( t_2 \) of a function known as the **Lagrangian**. Thus, the action \( S(t_1, t_2) \) is given by 

\[ S(t_1, t_2) = \int_{t_1}^{t_2} L(q, \dot q, t) dt \]

**Hamilton's principle of least action** (sometimes called *Hamilton's principle* or the *principle of least action*, basically states that the behavior of a system is that which minimizes the action \( S(t_1, t_2) \). For example, we might ask a (general) question, "what path does some particle take between points \( q_1 \) and \( q_2 \)? The principle of least action tells us that the particle follows the path which minimizes \( S = \int_{t_1}^{t_2} L(q, \dot q t) dt \) for the appropriate Lagrangian \( L(q, \dot q, t) \).

## Calculus of variations

First, some definitions. A **functional** is a map from a vector space to its underlying scalar field. Specifically here, it maps functions to the set of Reals.

<table>
  <tr>
    <td>Functions</td><td>Functionals</td>
  </tr>
  <tr>
    <td>\( f(x) \) maps numbers to numbers</td><td>\( S[q(t)] \) maps functions to numbers</td>
  </tr>
  <tr>
    <td>Change of a function: \( x \rightarrow x \+ dx \); \( f(x) \rightarrow f(x \+ dx) \)</td><td>Change of a functional: \( q(t) \rightarrow q'(t) = q(t) \+ \delta q(t) \); \( S[q(t)] \rightarrow S[q(t) \+ \delta q(t)] \)</td>

  </tr>
</table>
