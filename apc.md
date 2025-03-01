---
layout: post
title: Age, period, and cohort
permalink: /apc
---

# Fang and Qiu (2023)

I'm recently revisiting the paper by Fang and Qiu (2023) and finding it very interesting. Their method is simply the famous age-period-cohort method, which needs additional assumptions to be identified. In their paper, they use the following assumption, which is borrowed from LMPQS (2018): the experience growth at the end of one's career is stagnant.

Their illustration of a typical APC problem is classic. Imagine one's wage is determined by the price of human capital and his human capital.

$$W_{i,t} = P_{i,t} H_{i,t}$$

Take logarithm and denote variables with lower case letters.

$$w_{i,t} = p_{t} + h_{i,t}$$

But this is idiosyncratic. We need to separate out the mean.

$$w_{i,t} = p_{t} + h_{c(i),t} + \varepsilon_{i,t}$$

where $c(i)$ is the cohort of individual $i$ and $h_{c(i),t} = E[h_{i,t} \lvert c(i), t]$ is the mean human capital of cohort $c(i)$ at time $t$.

But the two components are not observable and cannot be identified. We further decompose the human capital into age and period effects.

$$ h_{c,t} = s_c + r_k^c$$

where $s_c$ is the baseline level of human capital and $r_k^c$ is the experience growth, $k = t-c$.

We assume each cohort has the same experience growth path.

$$w_{i,t} = p_{t} + s_{c(i)} + r_{k} + \varepsilon_{i,t}$$

But now the equation is still not identified. We can first derive some properties of the model.

# Golden ages

We can construct a cross-sectional age-earnings profile by averaging the earnings of people of the same age but different cohorts.

$$w(k;t) = E_i[w_{i,t} \lvert c(i) = t-k, t] = p(t) + s(t-k) + r(k)$$

Because of zero conditional mean, the random error is no longer in the equation.

The "golden age" in this cross-sectional profile is the age that maximizes this profile.

$$\frac{\partial}{\partial k} w(k;t) = s'(t-k) + r'(k) = 0$$

The profile is increasing when the life-cycle human capital growth is faster than the inter-cohort human capital growth.

As for the within-cohort profile,

$$\tilde{w}(k; c) = E_i[w_{i,t} \lvert c(i) = c, t = c+k] = p(c+k) + s(c) + r(k)$$

The "golden age" in this within-cohort profile is the age that maximizes this profile.

$$\frac{\partial}{\partial k} \tilde{w}(k; c) = p'(c+k) + r'(k) = 0$$

In general, the golden age is not the same in the cross-sectional and within-cohort profiles.

# Identification


