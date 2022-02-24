---
id: SIMAjVOmviM5WfPErl8xL
title: Assignment 2
desc: ''
updated: 1645400224076
created: 1645158661283
---
#### Sean Clifford

* * *

#### Reccurence for Fibonacci Numbers

$$
\\
F_0 = 0
\\
F_1 = 1
\\
F_n = F_{n-1} + F_{n-2}
$$

$$
f(0;a,b) = a
\\
f(1;a,b) = b
\\
f(n;a,b) = f(n-1;b,a+b)
$$

```python
def fib(n, a=0, b=1):
    if n == 0: return a
    if n == 1: return b
    return fib(n - 1, b, a + b)
```

### Question 1.

It turns out that for any $n \in \N { ,\space } T_F(n) = F_{n+1} − 1$. Use limits together with theorem 3 to show that
$T_F(n) \in \Theta(\varphi^n).$

**Theorem 3**: $\text{For any } n \in \N, F_n = \frac{1}{5}(\varphi^n - \hat{\varphi^n}) \text{, where } \varphi = \frac{1+\sqrt{5}}{2} \text{ and } \hat{\varphi} = {1 - \sqrt{5} \above{1pt} {\ 2}}$

```
* Proof: By mathematical induction
* Observe that  L^0(a, b) = … = (f(0;a, b), f(1;a, b))
* Assume L^k(a, b) = (f(k;a, b), f(k+1;a, b)) // add hat to a, b
* L^k+1(a, b) = ________
* 		    = (f(k+1;a, b), f(k+2;a, b)) // no hat


L^n(a, b) = (L o L o L)(a, b)
		 = L(L(…L(a, b)))
```

Question 5.

$$


$$

