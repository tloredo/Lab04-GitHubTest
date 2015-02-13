Here is *Bayes's theorem*:
\[
p(H_i|D) = \frac{p(H_i) p(D|H_i)}{p(D)} \qquad ||~I.
\]
And, of course, the all-import LTP, where \(\{B_j\}\) is a *suite*:
\[
p(H_i) = \sum_j p(H_i,B_j) = \sum_j p(B_j) p(H_i|B_j) \qquad ||~I.
\]
And since it's so important, let's write the LTP with alignment:
\[
\begin{align}
p(H_i)
  &= \sum_j p(H_i,B_j)\\
  &= \sum_j p(B_j) p(H_i|B_j) \qquad ||~I.
\end{align}
\]
And here's the *generalized beta integral*, from the lecture on categorical/multinomial inference:
\[
\int_0^\infty d\alpha_1 \cdots \int_0^\infty d\alpha_K\;
  \alpha_1^{\kappa_1-1}\cdots\alpha_K^{\kappa_K-1} \delta\left(a-\sum_k\alpha_k\right)\\
  = \frac{\Gamma(\kappa_1)\cdots\Gamma(\kappa_K)}{\Gamma(\kappa_0)}\; a^{\kappa-1}
\]
where \(\kappa_0 = \sum_{k=1}^K \kappa_k\).
