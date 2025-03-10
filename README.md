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


$T(n) \in O(\log_{2} n)$ then 

$\exists c, n_0: T(n) \leq c \cdot \log_{2} n \forall n \geq n_0$

change-of-base formula for $\log_{2} n = \log_{5} n / \log_{5} 2$

$c = \log_{5} 2$

$\exists c, n_0: T(n) \leq \log_{5} 2 \cdot \log_{5} n / \log_{5} 2 \forall n \geq n_0$


$\exists c, n_0: T(n) \leq \log_{5} n \forall n \geq n_0$ so

$T(n) \in O(\log_{5} n)$  is true 


$T(n) \in O(\log_{5} n)$ then 

$\exists c, n_0: T(n) \leq c \cdot \log_{5} n \forall n \geq n_0$

change-of-base formula for $\log_{5} n = \log_{2} n / \log_{2} 5$

$c = \log_{2} 5$

$\exists c, n_0: T(n) \leq \log_{2} 5 \cdot \log_{2} n / \log_{2} 5 \forall n \geq n_0$


$\exists c, n_0: T(n) \leq \log_{2} n \forall n \geq n_0$ so

$T(n) \in O(\log_{2} n)$  is true 

 $T(n) \in O(\log_{2} n) \iff T(n) \in O(\log_{5} n)$ is true 





For this assignment, I was able to do it entirely on my own with help on the distinct parts of the proof I needed to tackle from the TA and change-of-base formula from https://study.com/academy/lesson/change-of-base-formula-logarithms-proof-quiz.html#:~:text=An%20important%20algebraic%20property%20of,1%20is%20the%20chosen%20base.

"I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice."


