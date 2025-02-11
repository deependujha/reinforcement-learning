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
| ``\inf`` | \( \inf \) |
| ``\infty`` | \( \infty \) |
| ``\max`` | \( \max \) |
| ``\min`` | \( \min \) |
| ``\arg \max`` | \( \arg \max \) |
| ``\arg \min`` | \( \arg \min \) |

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

---

## Probability

Here’s a table of **probability-related symbols** in Markdown (LaTeX math mode):  

| Markdown Syntax | Math Expression |
|----------------|----------------|
| ``P(A)`` | \( P(A) \) (Probability of event A) |
| ``\mathbb{P}(A)`` | \( \mathbb{P}(A) \) (Alternative notation for probability) |
| ``P(A \cap B)`` | \( P(A \cap B) \) (Probability of A and B) |
| ``P(A \cup B)`` | \( P(A \cup B) \) (Probability of A or B) |
| ``P(A \vert B)`` | \( P(A \vert B) \) (Conditional probability) |
| ``P(A \mid B)`` | \( P(A \mid B) \) (Alternative conditional probability notation) |
| ``\mathbb{E}[X]`` | \( \mathbb{E}[X] \) (Expected value of X) |
| ``\operatorname{Var}(X)`` | \( \operatorname{Var}(X) \) (Variance of X) |
| ``\operatorname{Cov}(X, Y)`` | \( \operatorname{Cov}(X, Y) \) (Covariance of X and Y) |
| ``X \sim \mathcal{N}(\mu, \sigma^2)`` | \( X \sim \mathcal{N}(\mu, \sigma^2) \) (X follows a normal distribution) |
| ``X \sim \text{Bern}(p)`` | \( X \sim \text{Bern}(p) \) (X follows a Bernoulli distribution) |
| ``X \sim \text{Bin}(n, p)`` | \( X \sim \text{Bin}(n, p) \) (X follows a Binomial distribution) |
| ``X \sim \text{Poisson}(\lambda)`` | \( X \sim \text{Poisson}(\lambda) \) (X follows a Poisson distribution) |
| ``H(X) = -\sum p(x) \log p(x)`` | \( H(X) = -\sum p(x) \log p(x) \) (Entropy formula) |

---

## Greek Letters

| Markdown Syntax | Math Expression |
|----------------|----------------|
| ``\alpha`` | \( \alpha \) |
| ``\beta`` | \( \beta \) |
| ``\gamma`` | \( \gamma \) |
| ``\delta`` | \( \delta \) |
| ``\epsilon`` | \( \epsilon \) |
| ``\zeta`` | \( \zeta \) |
| ``\eta`` | \( \eta \) |
| ``\theta`` | \( \theta \) |
| ``\iota`` | \( \iota \) |
| ``\kappa`` | \( \kappa \) |
| ``\lambda`` | \( \lambda \) |
| ``\mu`` | \( \mu \) |
| ``\nu`` | \( \nu \) |
| ``\xi`` | \( \xi \) |
| ``\pi`` | \( \pi \) |
| ``\rho`` | \( \rho \) |
| ``\sigma`` | \( \sigma \) |
| ``\tau`` | \( \tau \) |
| ``\upsilon`` | \( \upsilon \) |
| ``\phi`` | \( \phi \) |
| ``\chi`` | \( \chi \) |
| ``\psi`` | \( \psi \) |
| ``\omega`` | \( \omega \) |

!!! note "Capital Greek letters"
    For uppercase versions, just capitalize the first letter, e.g., ``\Delta`` → \( \Delta \), ``\Gamma`` → \( \Gamma \).  

---

## Calculus

| Markdown Syntax | Math Expression |
|----------------|----------------|
| ``\frac{a}{b}`` | \( \frac{a}{b} \) (Fraction) |
| ``\sum_{i=1}^{n} x_i`` | \( \sum_{i=1}^{n} x_i \) (Summation) |
| ``\prod_{i=1}^{n} x_i`` | \( \prod_{i=1}^{n} x_i \) (Product notation) |
| ``\int_a^b f(x) \,dx`` | \( \int_a^b f(x) \,dx \) (Definite Integral) |
| ``\int f(x) \,dx`` | \( \int f(x) \,dx \) (Indefinite Integral) |
| ``\iint f(x, y) \,dx \,dy`` | \( \iint f(x, y) \,dx \,dy \) (Double Integral) |
| ``\iiint f(x, y, z) \,dx \,dy \,dz`` | \( \iiint f(x, y, z) \,dx \,dy \,dz \) (Triple Integral) |
| ``\oint f(x) \,dx`` | \( \oint f(x) \,dx \) (Contour Integral) |
| ``\frac{d}{dx} f(x)`` | \( \frac{d}{dx} f(x) \) (Derivative) |
| ``\frac{\partial}{\partial x} f(x,y)`` | \( \frac{\partial}{\partial x} f(x,y) \) (Partial Derivative) |
| ``\nabla f`` | \( \nabla f \) (Gradient) |
| ``\lim_{x \to a} f(x)`` | \( \lim_{x \to a} f(x) \) (Limit) |

---

## Some more symbols

Here are some **more symbols** like the cap, hat, overline, and similar:  

### 1. Overhead Symbols

| Markdown Syntax | Rendered Output | Usage |
|----------------|----------------|-------|
| ```\hat{x}``` | \( \hat{x} \) | Estimators, unit vectors |
| ```\widehat{xyz}``` | \( \widehat{xyz} \) | Longer expressions |
| ```\bar{x}``` | \( \bar{x} \) | Mean, averages |
| ```\overline{ABC}``` | \( \overline{ABC} \) | Complex conjugates, closures |
| ```\tilde{x}``` | \( \tilde{x} \) | Approximation, modified variables |
| ```\widetilde{XYZ}``` | \( \widetilde{XYZ} \) | Extended tilde notation |

### 2. Set and Logic Symbols

| Markdown Syntax | Rendered Output | Usage |
|----------------|----------------|-------|
| ```A \cup B``` | \( A \cup B \) | Union of sets |
| ```A \cap B``` | \( A \cap B \) | Intersection of sets |
| ```A \subset B``` | \( A \subset B \) | Subset |
| ```A \supset B``` | \( A \supset B \) | Superset |
| ```A \subseteq B``` | \( A \subseteq B \) | Subset or equal |
| ```A \supseteq B``` | \( A \supseteq B \) | Superset or equal |

### 3. Special Notation

| Markdown Syntax | Rendered Output | Usage |
|----------------|----------------|-------|
| ```\vee``` | \( \vee \) | Logical OR |
| ```\wedge``` | \( \wedge \) | Logical AND |
| ```\neg P``` | \( \neg P \) | Logical NOT |
| ```\forall x``` | \( \forall x \) | "For all" (universal quantifier) |
| ```\exists y``` | \( \exists y \) | "There exists" (existential quantifier) |
| ```\nexists z``` | \( \nexists z \) | "There does not exist" |
| ```\Rightarrow``` | \( \Rightarrow \) | Implies |
| ```\Leftrightarrow``` | \( \Leftrightarrow \) | If and only if |
