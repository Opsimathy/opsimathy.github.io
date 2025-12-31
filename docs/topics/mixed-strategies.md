# Mixed strategies

A **mixed strategy** randomizes over pure strategies.

## Definition
If player \(i\) has pure strategies \(S_i\), a mixed strategy is a probability distribution \(\sigma_i\) over \(S_i\).
Write \(\Delta(S_i)\) for the set of all such distributions.

A mixed-strategy profile is \(\sigma = (\sigma_1,\dots,\sigma_n)\).

## Expected payoff
Payoffs become expectations under \(\sigma\):
$$
\mathbb{E}[u_i(\sigma)] = \sum_{s \in S_1 \times \cdots \times S_n}
\left( \prod_{j=1}^n \sigma_j(s_j) \right) u_i(s).
$$

## Support + indifference condition (key trick)
In a mixed-strategy equilibrium, any pure strategy in the support of \(\sigma_i\) must yield the same expected payoff (otherwise you'd shift probability mass).
This is often how you *solve* for equilibrium mixing probabilities.

## Why it matters
Some games have no pure Nash equilibrium, but do have a mixed equilibrium (finite games always have at least one mixed Nash equilibrium).

## Links
- See also: [[glossary]]
