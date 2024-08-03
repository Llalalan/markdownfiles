Note that

$$
\begin{aligned}
 18 &= 2 \cdot 3^2 \\
 180 &= 2^2 \cdot 3^2 \cdot 5 \\
 45 &= 3^2 \cdot 5 \\
 15 &= 3 \cdot 5
\end{aligned}
$$

Let $n = 2^a \cdot 3^b \cdot 5^c$. It follows that:

1. From the least common multiple condition, we have

$$
\begin{aligned}
 \operatorname{lcm}(n,18) &= \operatorname{lcm}(2^a \cdot 3^b \cdot 5^c, 2 \cdot 3^2) \\
 &= 2^{\max(a,1)} \cdot 3^{\max(b,2)} \cdot 5^{\max(c,0)} \\
 &= 2^2 \cdot 3^2 \cdot 5
\end{aligned}
$$

from which $a=2, b\in\{0,1,2\},$ and $c=1$.

From the greatest common divisor condition, we have

$$
\begin{aligned}
 \gcd(n,45) &= \gcd(2^2 \cdot 3^b \cdot 5, 3^2 \cdot 5) \\
 &= 2^{\min(2,0)} \cdot 3^{\min(b,2)} \cdot 5^{\min(1,1)} \\
 &= 3 \cdot 5
\end{aligned}
$$

from which $b=1.$

Together, we conclude that $n=2^2 \cdot 3 \cdot 5 = 60.$ The sum of its digits is $6+0=\boxed{\textbf{(B) } 6}.$
