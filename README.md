# Erdős 1054

Lean formalization of [Jimmy/JIF’s divisor-prefix argument](https://github.com/jif-perso/erdos_1054).
Assuming `DusartBounds` and `HelfgottTailHypothesis`, every positive integer except
2 and 5 is the sum of an initial segment of some positive integer’s increasing divisors.

Statement: [Challenge.lean](Challenge.lean). Proof: [Solution.lean](Solution.lean).

```sh
lake exe cache get
lake build
```
