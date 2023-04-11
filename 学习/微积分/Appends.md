# Appends

## 一些公式

$\begin{cases}
    1 + 2 + \cdots + n = \displaystyle \frac{n(n+1)}{2} \\
    1^{2} + 2^{2} + \cdots + n^{2} = \displaystyle \frac{n(n+1)(n+2)}{6} \\
    1^{3} + 2^{3} + \cdots + n^{3} = \displaystyle [ \frac{n(n+1)}{2} ]^{2}
\end{cases}$

$\begin{cases}
    a^{n} - b^{n} = (a-b)(a^{n-1} + a^{n-2}b + \cdots + b^{n-1}) \\
    a^{n} + b^{n} = (a+b)(a^{n-1} - a^{n-2}b + \cdots +- \quad  b^{n-1}) \\
\end{cases}$

$\begin{cases}
    \arcsin x + \arccos x = \displaystyle \frac{\pi}{2} \\
    \arcsin (-x) = -\arcsin x \\
    \arccos (-x) = \pi - \arccos x \\
    \arctan (-x) = -\arctan x \\
\end{cases}$

$\begin{cases}
    \arctan x + arccot x = \displaystyle \frac{\pi}{2} \\
    arccot (-x) = -arccot x
\end{cases}$

---

## 一些缩放

1. $\displaystyle \sum \frac{1}{n}$
由 $\displaystyle \frac{1}{x} < \ln \frac{x}{x-1} < \frac{1}{x-1}$

可得 $\displaystyle \frac{1}{2} + \frac{1}{3} + \cdots + \frac{1}{n} < \ln \frac{2}{1} + \ln \frac{3}{2} +\cdots + \ln  \frac{n}{n-1} < 1 + \frac{1}{2} + \cdots + \frac{1}{n-1}$

即 $\displaystyle \frac{1}{2} + \cdots + \frac{1}{n} < \ln n < \frac{1}{2} + \cdots + \frac{1}{n} + 1 - \frac{1}{n}$

则 $\displaystyle \ln n + \frac{1}{n} < \sum \frac{1}{n} < \ln n + 1$

2. $\displaystyle \sum \sqrt{\frac{1}{n}}$

$\displaystyle \sqrt{n} < \sqrt{n+1} \implies 1 + \sqrt{\frac{n}{n+1}} < 2 \implies \sqrt{\frac{1}{n+1}} < 2(\sqrt{n+1} - \sqrt{n}) \implies \sum \sqrt{\frac{1}{n}} < 2(\sqrt{n}-1)$

3. $\displaystyle 2\ln n < n- \frac{1}{n}$
