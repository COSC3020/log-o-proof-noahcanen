# Asymptotic Equivalences

In the lectures, we said that logarithms with different bases don't affect the
asymptotic complexity of an algorithm. Prove that $O(\log_{2} n)$ is the same as
$O(\log_{5} n)$. Use the mathematical definition of $O$ -- do a formal proof,
not just the intuition.

I have started with the formal definition of $O$ below. Add your answer to this
markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$T(n) \in O(f(n)) \iff \exists c, n_0: T(n) \leq c \cdot f(n) \forall n \geq n_0$

$f(n)\in O(g(n)) \iff \exists c>0, \exists n_0, \forall n\ge n_0: f(n) <= c g(n)$

$O(\log_{2} n)$ \in $O(\log_{5} n)$

$\log_{5} n \in O(\log_{2} n)$

$f(n) \in \log_{5} n $

$g(n) \in \log_{2} n$

so $\exists c>0, \exists n_0, \forall n\ge n_0: \log_{5} n <=  c \log_{2} n$ is true
then \log_{5} \in O(\log_{2}) is true

$\log_{2} n \in O(\log_{5} n)$

$f(n) \in \log_{2} n $

$g(n) \in \log_{5} n$

so $\exists c>0, \exists n_0, \forall n\ge n_0: \log_{2} n <=  c \log_{5} n$ is true
then \log_{2} \in O(\log_{5}) is true

so $O(\log_{2} n)$ = $O(\log_{5} n)$ is true

For this assignment, I was able to do it entirely on my own with help on the distinct parts of the proof I needed to tackle from the TA.

"I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice."


