## I. Why bother performing analysis on real numbers?

Lets start by understanding what analysis is? 
Lets say we have an object and we want to analyse it. What we simply do is study its behaviour. After doing this, we can manipulate these said objects in some ways to achieve particular goals since we know how they behave. I will assume knowledge of Natural Numbers, Integers and Rational numbers for the upcoming sections.

Why do we perform Real Analysis as opposed to Rational Analysis? 
Simply stated, rational numbers are too thin. Taking a limit leads to convergence to irrational numbers(each of these terms will be defined but this would make sense to the reader intuitively). 

# Euclid’s Proof that √2 is Irrational

**Theorem.** √2 is not a rational number.

**Proof (by contradiction).**  
Assume √2 is rational. Then there exist integers \(p\) and \(q\) with \(q \neq 0\) such that

\[
\sqrt{2} = \frac{p}{q}.
\]

We may assume that \(\frac{p}{q}\) is in lowest terms (i.e., \(\gcd(p,q) = 1\)).

Squaring both sides:

\[
2 = \frac{p^2}{q^2} \quad \Longrightarrow \quad p^2 = 2q^2.
\]

Thus \(p^2\) is even, which implies \(p\) is even. Let \(p = 2k\). Substituting back:

\[
(2k)^2 = 2q^2 \quad \Longrightarrow \quad 4k^2 = 2q^2 \quad \Longrightarrow \quad q^2 = 2k^2.
\]

Hence \(q^2\) is even, so \(q\) is also even.

Therefore, both \(p\) and \(q\) are divisible by 2, contradicting the assumption that \(\frac{p}{q}\) was in lowest terms.

This contradiction shows that √2 is irrational. 
