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

* Equilibrium conditions (deterministic):

  $\forall_{a \in A} q_a * (u_a - U*_a) = 0 $

* Travel time, BPR deterministic model:

  $t_a(q_a) = t^0_a (1 + (q_a / Q_a)^2)$

* Exponential smoothing (learning):

  $E(t_{i,a,\tau})=\alpha  \hat{t} + (1-\alpha) E(t_{i,a,\tau})$ 

**Notation**:

  * $i$ - agent, traveller, human
  * $I$ - set of all agents
  * $a$ - action, or choice, or arc chosen by traveller
  * $A$ - choice-set, action-space, set of available routes
  * $c_{i,a}$ - cost of using arc/route/alternative $a$ by traveller $i$
  * $t_{i,a}$ - travel time of arc $a$ perceived by traveller $i$
  * $U$ - utility
  * $q_a$ - is the flow (number of vehicles using arc)
* $t^0_a$ - is the free flow speed (with no other vehicles)
* $Q_a$ - is the capacity (maximal number of vehices)
* $E(t_{i,a,\tau}$ - expected time at arc a at day $\tau$ by traveller $i$
* $\hat{t}$ - latest experienced travel time

----

## Paper notes:

In [Mehmet Yildirimoglu](https://doi.org/10.1371/journal.pone.0196997) they observe the flow on the network to verify hypothesis on the stable point equilibrium:

<img width="887" alt="image" src="https://github.com/COeXISTENCE-PROJECT/references/assets/20555451/bebc1807-9d8d-4499-8a9a-2f8acd34036d">

