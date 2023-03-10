<head>
    <!-- <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script> -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML" type="text/javascript"></script>
    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
            tex2jax: {
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
            inlineMath: [ ['$','$'], ["\\(","\\)"] ],
            displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
            }
        });
    </script>
</head>

# $\LaTeX$ Formula

References:

- https://hackmd.io/@CynthiaChuang/Basic-LaTeX-Commands
- https://www.scijournal.org/articles/dots-symbols-in-latex

## Elementary arithmetic

$$
2x - 5y = 8\\
3x + 9y= -12\\
7x \times 2y \neq 3z
$$

## Exponential function

$$
x^3 + x^9 + x^y
$$

## Square root

$$
\sqrt{3x - 1} + \sqrt[5]{2y^5 - 4}
$$

## Trigonometric functions

$$
\cos(2\theta) = \cos^2 \theta - \sin^2 \theta
$$

## Fraction

$$
\frac{x}{2y} + \frac{x - y}{x + y}
$$

## Progression

$$
\sum_{i = 1}^\infty \frac{1}{i^2} \quad and \quad
\prod_{i = 1}^n \frac{1}{i^2} \quad and \quad
\bigcup_{i = 1}^{2} R
$$

## Limit

$$
\lim_{x \to \infty} \exp(-x) = 0
$$

## Factorial function

$$
\frac{n!}{k!(n - k)!} = \binom{n}{k}
$$

## Matrix

$$
\begin{bmatrix}
    1 & 2 & 3 \\
    4 & 5 & 6 \\
    7 & 8 & 9
\end{bmatrix}
$$

## Piecewise function

$$
X(m,n) =
\begin{cases}
    x(n) \\
    x(n - 1) \\
    x(n + 1) \\
\end{cases}
$$

## Calculus

{% raw %}
$$
\left. \frac{{\rm d}u}{{\rm d}x} \right|_{x = 0} \quad and \quad
\int_0^1 (x^2) \,{\rm d}x \quad and \quad
\frac{\partial x}{\partial y}
$$
{% endraw %}

## Align

$$
\begin{align}
    \sqrt{37} & = \sqrt{\frac{73^2 - 1}{12^2}} \\
    & = \sqrt{\frac{73^2}{12^2} \cdot \frac{73^2 - 1}{73^2}} \\
    & = \frac{73}{12} \sqrt{1 - \frac{1}{73^2}} \\
    & \approx \frac{73}{12} (1 - \frac{1}{2 \cdot 73^2})
\end{align}
$$
