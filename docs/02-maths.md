# Maths in Markdown

## An example

- **The Cauchy-Schwarz Inequality**

$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$

---

## Basic maths

| Markdown Syntax | Math Expression |
|----------------|----------------|
| ``a + b`` | \( a + b \) (Plus) |
| ``a - b`` | \( a - b \) (Minus) |
| ``a \times b`` | \( a \times b \) (Multiplication) |
| ``a \cdot b`` | \( a \cdot b \) (Dot product) |
| ``\frac{a}{b}`` | \( \frac{a}{b} \) (Fraction) |
| ``a \div b`` | \( a \div b \) (Division) |
| ``a \pm b`` | \( a \pm b \) (Plus-minus) |
| ``a \mp b`` | \( a \mp b \) (Minus-plus) |
| ``a \ast b`` | \( a \ast b \) (Asterisk multiplication) |
| ``a \oplus b`` | \( a \oplus b \) (XOR / Direct sum) |
| ``a \otimes b`` | \( a \otimes b \) (Tensor product) |

---

## Parentheses

| Markdown Syntax | Math Expression |
|----------------|----------------|
| ``(a+b)`` | \( (a+b) \) |
| ``[a+b]`` | \( [a+b] \) |
| ``\{a+b\}`` | \( \{a+b\} \) |
| ``\langle a+b \rangle`` | \( \langle a+b \rangle \) |
| ``\lfloor a \rfloor`` | \( \lfloor a \rfloor \) (Floor function) |
| ``\lceil a \rceil`` | \( \lceil a \rceil \) (Ceiling function) |

For **scalable parentheses** (auto-sized based on content):

```latex
\left( \frac{a}{b} \right)
```

\[
\left( \frac{a}{b} \right)
\]

---

## Common math symbols

| Markdown Syntax | Math Expression |
|----------------|----------------|
| ``\sigma`` | \( \sigma \) |
| ``a^b`` | \( a^b \) |
| ``\sqrt{x}`` | \( \sqrt{x} \) |
| ``\log x`` | \( \log x \) |
| ``\log_{y} x`` | \( \log_{y} x \) |
| ``\ln x`` | \( \ln x \) |
| ``e^x`` | \( e^x \) |
| ``\pi`` | \( \pi \) |
| ``\int f(x) \,dx`` | \( \int f(x) \,dx \) |
| ``\frac{d}{dx} f(x)`` | \( \frac{d}{dx} f(x) \) |
| ``\frac{\partial f}{\partial x}`` | \( \frac{\partial f}{\partial x} \) |
| ``\iint f(x, y) \,dx\,dy`` | \( \iint f(x, y) \,dx\,dy \) |
| ``\iiint f(x, y, z) \,dx\,dy\,dz`` | \( \iiint f(x, y, z) \,dx\,dy\,dz \) |
| ``\oint f(x) \,dx`` | \( \oint f(x) \,dx \) |
| ``\sin x`` | \( \sin x \) |
| ``\cos x`` | \( \cos x \) |
| ``\tan x`` | \( \tan x \) |
| ``\sinh x`` | \( \sinh x \) |
| ``\cosh x`` | \( \cosh x \) |
| ``\tanh x`` | \( \tanh x \) |
| ``\Delta x`` | \( \Delta x \) |
| ``\lambda`` | \( \lambda \) |
| ``\sum_{i=1}^{n} x_i`` | \( \sum_{i=1}^{n} x_i \) |
| ``\prod_{i=1}^{n} x_i`` | \( \prod_{i=1}^{n} x_i \) |
| ``\lim_{x \to a} f(x)`` | \( \lim_{x \to a} f(x) \) |
| ``\approx`` | \( \approx \) |
| ``\neq`` | \( \neq \) |
| ``\geq`` | \( \geq \) |
| ``\leq`` | \( \leq \) |

---

## Matrix

Here’s how to write **rows, columns, and matrices** in LaTeX (Markdown math mode):

### 1. Row Vector

```latex
\begin{bmatrix} a & b & c \end{bmatrix}
```

$$
\begin{bmatrix} a & b & c \end{bmatrix}
$$

### 2. Column Vector

```latex
\begin{bmatrix} a \\ b \\ c \end{bmatrix}
```

\[
\begin{bmatrix} a \\ b \\ c \end{bmatrix}
\]

### 3. Matrix (General Form)

```latex
\begin{bmatrix} 
a & b \\ 
c & d 
\end{bmatrix}
```

\[
\begin{bmatrix}
a & b \\
c & d
\end{bmatrix}
\]

### 4. Identity Matrix (3×3 example)

```latex
\begin{bmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{bmatrix}
```

\[
\begin{bmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{bmatrix}
\]
