Does this work?

$\ket{x}$

When $a \ne 0$, there are two solutions to $(ax^2 + bx + c = 0)$ and they are 

$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$

\\[
\ket{a} + \ket{b} = \begin{pmatrix}
a_1 \cr
a_2 \cr
\vdots \cr
a_n
\end{pmatrix} + \begin{pmatrix}
b_1 \cr
b_2 \cr
\vdots \cr
b_n
\end{pmatrix} = \begin{pmatrix}
a_1 + b_1 \cr
a_2 + b_2 \cr
\vdots \cr
a_n + b_n \cr
\end{pmatrix}
\\]

More generally, a vector $\ket{v}$ can be defined as a linear combination of vectors $\ket{v_1}, \ket{v_2}, \ldots, \ket{v_n}$ given complex coefficients $\alpha_i$ like this:

\\[
\ket{v} = \alpha_1\ket{v_1} + \alpha_2\ket{v_2} + \cdots + \alpha_n\ket{v_n} = \sum_{i=1}^n \alpha_i\ket{v_i}
\\]

Note that in situations of interest in quantum computing, vectors need to have a norm of 1, which means that the linear combination also has to yield a vector whose norm is 1, which in turn means the coefficients must satisfy some conditions.
