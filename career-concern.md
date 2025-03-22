---
title: "Holmstrom 1999: Career Concern"
layout: post
permalink: /career-concern/
---

"Whoever thinks that principal-agent model is only about effort is incredibly naïve." -- *Bengt Holmstrom*

*The words above are quoted from Jin Li. The principal-agent model is only one representation of how the preference of the two are misaligned. It is quite possible that in the reality all the managers are workaholic, but they may have different goals from the shareholders.*

"Don't take the models too seriously. Think about how the reality differs from the model." -- *Jin Li*

About how a person's concern for future affects his current efforts. His productive abilities are revealed over time through observations of performance. There is no explicit contract, but each period the wage hinges on the expected output, which links today's payoff to future wages.

Congruence between the firm's financial concern and the individual's concern for human capital return may be low. Career concern may thus be beneficial or detrimental.

# Basic Model

Consider a manager operating in a competitive labor market. If there is no uncertainty in his characteristics, he has no incentive to work (competitive wage = cost).

Talent measurement $\eta$ with a normal prior. Mean $m_1$. Precision $h_1$ (the inverse of variance). The final product is determined by three components: ability, effort, and a noise.

$$ y_t = \eta + a_t + \varepsilon_t $$

Each period, the market observes the worker's history $y^{t-1}$ and posts a wage $w(y^{t-1})$ to her. Due to perfect competition, the wage should equal the worker's expected output.

$$ w_t(y^{t-1}) = \mathbb{E}[\eta \lvert y^{t-1}] + a_t^\ast $$

The market should use Bayes' rule to update the belief of $\eta$. Define $z_t\equiv \eta + \varepsilon_t + a_t - a_t^\ast = y_t - a_t^\ast$. Let $h_t$ denote the precision of $m_t\equiv \mathbb{E}[\eta\lvert y^{t-1}]$. It is easy to show that 

$$ \mathbb{E}[\eta \lvert y^{t}] = \frac{h_{t}\mathbb{E}[\eta\lvert y^{t-1}] + h_\varepsilon z_t}{h_{t} + h_\varepsilon}$$

$$ h_{t+1} = h_{t} + h_\varepsilon = h_1 + th_\varepsilon $$

Using the law of motion of $h_t$, we can get
$$ \mathbb{E}[\eta \lvert y^{t-1}] = \frac{h_1m_1 + h_\varepsilon \sum_1^{t-1} z_s}{h_1 + t h_\varepsilon} $$

Therefore, the expected wage in period $t$ is
$$ Ew_t(y^{t-1}) = \frac{h_1 m_1}{h_t} + \frac{h_\varepsilon}{h_t}\sum_{s=1}^{t-1} (m_1 + a_s - Ea_s^\ast(y^{s-1})) + Ea_t^\ast(y^{t-1}) $$

The marginal return of effort in one period is $h_\varepsilon/h_t$ for every period in the future. Therefore, the optimal effort is given by
$$ g'(a_t^\ast) = \sum_{s=t}^\infty \beta^{s-t} \frac{h_\varepsilon}{h_t} $$

It is obvious that as $t\to\infty$, the optimal effort is declining to zero. As the ability is more known to the market, the worker does not have the incentive to work.