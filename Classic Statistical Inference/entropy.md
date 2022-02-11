# Entropy
The **entropy** of a random variable is the average level of "information", "uncertainity" or "surprise", inherent to the variable's posible outcomes.
The uncertainity of an outcome is related inversely with the probability of the same:

$$\text{uncertainity}(x) = \log_2{\frac{1}{p(x)}}$$

## Formal definition

Given a discrete random variable $X$ with possible outcomes $x_1, x_2, ..., x_n$, which occur with probabilities $P(x_1), P(x_2), ..., P(x_n)$ is defined as:

$$ \begin{align*}
    H(X) &= \sum_{i=1}^n P(x_i)\cdot\log_2\left(\frac{1}{P(x_i)}\right) \\
        &= -\sum_{i=1}^n P(x_i)\cdot\log_2(P(x_i))
    \end{align*} $$

Used to measure the **difference** or **similarity** between any two states of a system.

A high entropy means less uncertainity in the outcomes of a rangom variable, while a low entropy represent the prescence of outcomes with more uncertainity.