## I. Why bother performing analysis on real numbers?

Lets start by understanding what analysis is? 

Lets say we have an object and we want to analyse it. What we simply do is study its behaviour. After doing this, we can manipulate these said objects in some ways to achieve particular goals since we know how they behave. I will assume knowledge of Natural Numbers, Integers, Rational numbers and Basic Set Theory for the upcoming sections.

Why do we perform Real Analysis as opposed to Rational Analysis? 

Simply stated, rational numbers are too thin. Taking a limit leads to convergence to irrational numbers(each of these terms will be defined but this would make sense to the reader intuitively). 

**Euclid’s Proof by Contradiction that √2 is Irrational:**
 
Assume √2 is rational. Then there exist integers p and q with q ≠ 0 such that

    √2 = p/q.

We may assume that p/q is in lowest terms (i.e., gcd(p, q) = 1).

Squaring both sides:

    2 = p² / q²   ⇒   p² = 2q².

Thus p² is even, which implies p is even. Let p = 2k. Substituting back:

    (2k)² = 2q²   ⇒   4k² = 2q²   ⇒   q² = 2k².

Hence q² is even, so q is also even.

Therefore, both p and q are divisible by 2, contradicting the assumption that p/q was in lowest terms.

This contradiction shows that √2 is irrational. 

So our goal is to simply fill this gaps and everything will be okay. But one may ask how we are so sure these gaps can be filled?

Here is the philosophy regarding this. An initial assumption is always needed. Through Peano axioms, we assume that Natural Numbers exist. From that point on, we just create objects out of our convenience and make sure that they follow consistent properties. (Recall that integers are just a pair of natural numbers - 
[3-5:=-2]). There is no proof and none is required. 

So now there are two ways to construct the set **R** from **Q**:  

**A) Cauchy Completion:**

Before we go on to do this, we need 4 very simple definitions.
**1. Definition: Infinite Rational Sequence**

Let m be an integer. An infinite rational sequence is a sequence such that

![formula](https://quicklatex.com/cache3/b3/ql_b3fa9ed52370e04cb4a0053fcad312b3_l3.png) 


**2. Definition: Cauchy Sequence of Rational Numbers**

The following two statements are equivalent:

a. ![formula](https://quicklatex.com/cache3/12/ql_02d40111a53c40cef2d540e04ff18812_l3.png) 

b. ![formula](https://quicklatex.com/cache3/3d/ql_4f384c8cfac5cbcc4035ab021693953d_l3.png) 







b) Dedekind Cuts



