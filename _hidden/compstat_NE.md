---
layout: post
title: "Comparative Statics of the NE"
permalink: /compstat_NE
---

# Settings

Imagine there is a principal and a manager, like in an Aghion-Tirole model. The utility of the principal is in general $ U_P = f(E,e) - (c_E/2)E^2 $, while the utility of the agent is $ U_M = g(E,e) - (c_e/2)e^2 $. The Nash equilibrium is the pair $(E,e)$ that is a mutual best response to each other. Best response functions defined by

$$ f_1(BR_P(e), e) = c_E BR_P(e) $$

$$ g_2(e, BR_M(E)) = c_e BR_M(E) $$

Now the question is how the NE utility of the principal changes when $c_e$ changes. (Give me the first order condition)

# Comparative Statics of Nash Equilibrium

To find how the Nash Equilibrium utility of the principal changes when $c_e$ changes, I'll derive the first order condition.

Let's denote the Nash Equilibrium as $(E^*, e^*)$. The principal's utility at this equilibrium is:

$$U_P(E^*, e^*) = f(E^*, e^*) - \frac{c_E}{2}(E^*)^2$$

To find how this changes with respect to $c_e$, we need to compute:

$$\frac{dU_P(E^*, e^*)}{dc_e}$$

Using the chain rule:

$$\frac{dU_P(E^*, e^*)}{dc_e} = \frac{\partial U_P}{\partial E^*}\frac{dE^*}{dc_e} + \frac{\partial U_P}{\partial e^*}\frac{de^*}{dc_e}$$

At the Nash Equilibrium, $E^*$ is the principal's best response, so $\frac{\partial U_P}{\partial E^*} = 0$ (first-order condition for the principal's optimization). This simplifies to:

$$\frac{dU_P(E^*, e^*)}{dc_e} = \frac{\partial U_P}{\partial e^*}\frac{de^*}{dc_e}$$

Substituting the principal's utility function:

$$\frac{dU_P(E^*, e^*)}{dc_e} = \frac{\partial f(E^*, e^*)}{\partial e^*}\frac{de^*}{dc_e}$$

Therefore, the first-order condition for how the principal's Nash Equilibrium utility changes with respect to $c_e$ is:

$$\frac{dU_P(E^*, e^*)}{dc_e} = f_2(E^*, e^*)\frac{de^*}{dc_e}$$

Where $f_2$ represents the partial derivative of $f$ with respect to its second argument (the agent's effort $e$).