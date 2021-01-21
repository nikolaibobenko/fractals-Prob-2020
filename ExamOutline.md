# Fractals Exam questions:

Please be advised that the questions mentioned here are just guidelines. The exam will be interactive and we will feel free to ask questions about both details and the big picture. In particular you should make sure you understand how some of these results apply to some of the examples we have considered in class and the exercise sessions.

1. State Frostman's lemma and outline its proof.
  - Mass distribution <--> Frostman
  - B-adic tree corresponding to K --> measure \mu on paths in tree --> Covers of $K$ correspond to cut sets of tree --> MaxFlow-MinCut Thm 
2. State Frostman's Theorem about the connection between capacity and Hausdorff measure and outline its proof.
  - Definitions
  - i) $H^\alpha(K) > 0$ --> Frostmann's lemma measure $\mu$ --> Check $\int \frac{d\mu(y)}{|x-y|^\beta} \leq M$ for $\beta < \alpha$.
  - ii) $\text{Cap}_\alpha(K) > 0$ --> take $\mu$ with $E_\alpha(\mu) < \infty$. Show that mass distribution gives $H^\alpha(K) = \infty$. 
3. Explain how to derive the dimension of the set $A_p$ defined by digit frequency $p$.
  - Definition $A_p$
  - SLLN + Billingsley's
  - dim(A_p) = dim(\mu_p) = h_2(p)
4. Let $\{f_1, \ldots, f_n\}$ be a collection of similitudes with contraction ratios $\{r_1,\ldots, r_n\}$. What is the attractor and what can we state about its dimension without the open set condition?
  - exists unique attractor for contractions: $F(C) = \bigcup f_i(C)$ contraction in $(\text{CPT}(X), d_H)$ --> Banach fixed point thm gives unique attactor.
  - $\alpha$ s.t. $\sum r_j^\alpha = 1$. Then $H^\alpha(K) = H^\alpha_\infty(K) < \infty$
  - $H^\alpha(f_i(K) \cap f_j(K)) = 0$
5. Explain the Open Set Condition. How does it allow us to calculate Hausdorff and Minkowski dimensions?
  - $K$ attractor of OSC similitudes with $\alpha$ the similarity dimension. Then $\implies \dim(K) = \alpha = \dim_M(K)$.
  - Argue existence of $\mu$ with $\mu = \sum \mu r_j^\alpha f_j^{-1}$. Check Mass distribution principle.
  - For equality of dimensions left to bound upper Minkowski dimension.
6. State Furstenberg's Lemma and explain its proof.
  - $\dim(K) = \dim_M(K)$ for $K$ compact + shift-invariant
  - $\alpha > dim(K)$ -> Covering of $K$ finite by compactness -> corresponds to cut set -> need to bound $\sum_{\tau \in \prod} b^{-\alpha |\tau|}$ 
  - Examples: Finite shift, Digit restriction
7. State Taylor's theorem about the dimension of the graph and path of Brownian motion and outline its proof.
  - Definitions of BM
  - Upper estimates: Lemma1: $f\in \text{H\"ol}_\alpha \implies \dim_M(G_f) \leq  2-\alpha$. Lemma2: $\dim_M(f([0,1])) \leq \frac{1}{\alpha}$.  
  - Lower estimate: $E_\alpha = \int \int\frac{d\nu d\nu}{|x-y|^\alpha}$, where $\nu(A) = \text{length}\{t: (t,W(t)) \in A\}$. --> Show: $\mathbb{E} E_\alpha < \infty$ via Gaussian calculations.
8. Define the Whitney decomposition of a set $K$ and prove the relation between the Whitney dimension and Minkowski dimension.