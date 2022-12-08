---
layout: page
title: Hidden Markov Model
description: Hidden Markov Chain Model for Purchase Propensity
#img: assets/img/3.jpg
importance: 3
category: python
---

See the <a href="https://github.com/jsmatte/hmcb">github repo</a>.

This is a Python package I started working on during the <a href="http://crm.umontreal.ca/probindustrielsEn2021/index.php/coveo-eng/">11th Montreal Industrial Problem Solving Workshop (IPSW) Coveo Problem</a>. I used the opportunity to work on the cart-abandonment task: "given a session containing an add-to-cart event for a product X, a model is asked to predict whether the shopper will buy X or not in that session."

The package was developed based on the paper <a href="https://epubs.siam.org/doi/abs/10.1137/1.9781611972733.10">*Bertsimas, D., Mersereau, A., & Patel, N. (2003). Dynamic Classification of Online Customers*</a>.

I have been thinking about this problem a lot in the beginning of my PhD, and was happy I had the opportunity to try my hand at doing this short work. I have also been thinking of modelling/solving the purchase propensity problem using Dynamic Programming (where the value function updates the posterior probability of purchase). Although it could lead to neat theoretical findings, I think the DP approach is more limited in how it can be implemented in a "real-life" setting with a large amount of data.



<!--
...
-->
