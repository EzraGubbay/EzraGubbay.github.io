---
title: "Understanding a Qubit"
date: 2025-11-08
---

A qubit is the fundamental unit of quantum information. Unlike a classical bit, which can be 0 or 1, a qubit's state can be a superposition of both.

We represent this state as a vector:

$$
|\psi\rangle = \alpha|0\rangle + \beta|1\rangle
$$

Here, $\alpha$ and $\beta$ are complex probability amplitudes. The probability of measuring the qubit as $|0\rangle$ is $|\alpha|^2$, and the probability of measuring $|1\rangle$ is $|\beta|^2$.

This leads to the normalization condition:

$$
|\alpha|^2 + |\beta|^2 = 1
$$