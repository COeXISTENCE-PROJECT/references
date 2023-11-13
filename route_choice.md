# Route-choice in traffic


**Assumptions**:

* Homogeneity:

   $\forall_{i \in I } U_{i,a} = const$
* Utility:

   $U_{i,a} = \beta_{i,a} + \beta_c c_a + \beta_t t_a + \varepsilon $
* Rational utility maximization:

  $p_{i,a} = Pr(U_{i,a} = max_{a' \in A} U_{a',i})$

* Logit choice model (if $\varepsilon \sim$ Gumbel :
 
    $p_{i,a} = exp( \mu U_{i,a}) / \sum_{a' \in A} U_{a,i}$

* Equilibrium (deterministic):

  $\forall_{a \in A} q_a * (u_a - U*_a) = 0 $

  **Notation**:

  * $i$ - agent, traveller, human
  * $I$ - set of all agents
  * $a$ - action, or choice, or arc chosen by traveller
  * $A$ - choice-set, action-space, set of available routes
  * $c_{i,a}$ - cost of using arc  
