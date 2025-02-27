---
layout: post
title: "Legros and Newman 2013 A price theory of vertical and lateral integration"
permalink: /legros_newman_2013
---

*A model about integration and coordination in a market equilibrium.*
# Settings
**Production:**
There is one consumer good, the production of with requires two parties, $A$ and $B$. Denote the decision of $A$ as $a\in [0,1]$ and similarly for $B$. The identity of the decision maker will be determined by the ownership structure. The final output is $1$ with a probability $1-(a-b)^2$.
The managers of the two parties have a private cost of making decisions. What is easy for one is hard for the other. Specifically, manager $A$'s utility is $y^A - (1-a)^2$, and $y^B - b^2$ for $B$.

***Assumption:*** limited liability $y^i \geq 0$. No any means of side payments (enter the scene with zero cash endowments). This is to make the ownership structure dependent on supplier market conditions.

**Integration**: the $HQ$ will make the decision without private costs. Utility $y^H$

**Contract**: Under non-integration, $A$ gets $s$ share of the revenue and $B$ gets $1-s$. Under integration, $HQ$ buys the assets of $A,B$ for prices of $\pi_A$ and $\pi_B$ in exchange for a share structure $\mathbf{s} = (s_A,s_B,s_H)$ where the sum of the three is $1$.

**Coalitions (enterprises)**:** Coalitions consisting of $A$ and $B$ vs. Coalitions consisting of $A$ and $B$ and $HQ$.


**Define an equilibrium**:
- *Feasibility*. The payoffs paid to the agents must be feasible within the coalition under the equilibrium price $P$.
- *Stability*. No coalition can form and find feasible payoff for its members that are strictly greater than their equilibrium payoffs.
- *Market clearing*. $S(P) = D(P)$.

# Analysis
## Non-integration
The unique Nash equilibrium will be
$$a = 1- s \frac{P}{1+P},\quad b=(1-s)\frac{P}{1-P}$$
The expected resulted output
$$Q^N(P)\equiv 1- \frac{1}{(1+P)^2}$$
The Pareto frontier is obtained by changing $s$

$$U^N(s,P)\equiv Q^N(P)P- (s^2+ (1-s)^2)\left(\frac{P}{1+P}\right)^2$$

which is maximized at $s=\frac{1}{2}$ and minimized at $s=0$ or $1$.
## Integration
Under integration, the $HQ$, if she has a positive stake in the enterprise, can choose to maximize the probability $(a=b)$ minimize the private costs of the managers $a=b=1/2$. So the Pareto frontier must be $u_B = P-1/2-u_A$. Notice that this is NOT first best because the $HQ$ does not fully consider the welfare of the managers.

In general, the supplier market equilibrium, which determines the distribution of surplus and $s$ (?), as well as the product market equilibrium, which determines $P$, will jointly affect integration decision.

The linear frontier of integration will intersect with the non-linear frontier of non-integration. The loci are given by $\lvert u_A - u_B \rvert = \frac{P}{1+P}$.

**Proposition 1**
a. Integration is chosen when product price $P > 1$ and 
   $\lvert u_A - u_B \rvert > \frac{P}{1+P}$.

b. Nonintegration is chosen when $P < 1$ or 
   $\lvert u_A - u_B \rvert < \frac{P}{1+P}$.

c. Either ownership structure may be chosen when $P \geq 1$ 
   and $\lvert u_A - u_B \rvert = \frac{P}{1+P}$.


![pareto frontier](https://github.com/HubertYHZhang/HubertYHZhang.github.io/raw/main/images/SCR-20250227-qiac.png)
