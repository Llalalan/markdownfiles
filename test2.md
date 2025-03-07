Note that 
$$
18 = 2\cdot3^2 
$$
$$180 = 2^2\cdot3^2\cdot5$$ 
$$45 = 3^2\cdot5 $$
$$ 15 = 3\cdot5$$. 
Let $n = 2^a\cdot3^b\cdot5^c.$ It follows that:

$$
       \frac{1}{(\sqrt{\phi \sqrt{5}}-\phi) e^{\frac25 \pi}} =
         1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {1+\frac{e^{-6\pi}}
          {1+\frac{e^{-8\pi}} {1+\ldots} } } }
$$

$$

    \left( \sum_{k=1}^n a_k b_k \right)^{\!\!2} \leq
     \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
$$

From the least common multiple condition, we have\[\operatorname{lcm}(n,18) = \operatorname{lcm}(2^a\cdot3^b\cdot5^c,2\cdot3^2) = 2^{\max(a,1)}\cdot3^{\max(b,2)}\cdot5^{\max(c,0)} = 2^2\cdot3^2\cdot5,\]from which $a=2, b\in\{0,1,2\},$ and $c=1.$
From the greatest common divisor condition, we have\[\gcd(n,45) = \gcd(2^2\cdot3^b\cdot5,3^2\cdot5) = 2^{\min(2,0)}\cdot3^{\min(b,2)}\cdot5^{\min(1,1)} = 3\cdot5,\]from which $b=1.$
Together, we conclude that $n=2^2\cdot3\cdot5=60.$ The sum of its digits is $6+0=\boxed{\textbf{(B) } 6}.$
