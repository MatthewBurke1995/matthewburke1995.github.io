The first iteration I saw of this question required solving the problem without a calculator. The exact solution is easy with a bit of probability theory. The approximation requires a bit of intuition, and a much longer explanation.

The first iteration I saw of this question required solving the problem without a calculator. The exact solution is easy with a bit of probability theory. The approximation requires a bit of intuition, and a much longer explanation.

The general solution is
. The chance of each failure is , the chance of n consecutive failures is , take the complementary even by subtracting it from 1. In the above case and

. With a calculator the answer to two decimal places is 0.63.

When I first heard the question, my first method of approximating the answer was to use
and , with the expectation that having

a small p value and large n value would all be approximations of the same expression.

Let's introduce an approximation:

for very small values of p.

And the definition of

:

Given , let
and

.

.

Using the approximation for small x:

.

.

The expression is particularly nice when we assume

, but even without the assumption, we could still receive an answer in terms of e:

This shows that the cumulative probability of passing one interview is based on the value of only, with the caveat that the higher the value of the closer the solution is to the approximation that uses .