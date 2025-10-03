# Part 1 : Ordinary Differential Equations

${toc}

# Chapter 1: First Order Ordinary Differential Equations

## 1.1 Basic Concepts

__Ordinary differential equation (ODE):__ an equation that contains one or
several derivatives of an unknown function. An ODE is said to be of order $n$ if
the $n^{th}$ derivative of the unknown function $y$ is the highest derivative of
$y$ in the equation.

First order ODE's can be written as the implicit form $F(x,y.{y'})=0$ or in the explicit form of ${y'}=f(x,y)$

Example:

$$
x^{-3}{y'}-4y^2=0\ (implicit\ form)\ \qquad {y'}=\frac{4y^2}{x^{-3}}=4y^2x^3\ (explicit\ form)\
$$

__Concept of Solutions:__
$y=h(x)$ is called a solution of a given ODE for an open interval $a < x < b$ if $h(x)$ is differentiable and defined through the interval such that the equation becomes an identity if $y$ and $y'$ are replaced with $h$ and $h'$ respectively.

Example: Verify that $y=c/x$ (with c being an arbitrary constant) is a solution of the ODE $x{y'}=-y$ for all $x \neq 0$.

__Solution:__

$$
\begin{align}
&y=c/x \\
&{y'}=-c/x^2 \\
&x{y'}=-c/x \qquad ,\ since\ y=c/x \\
&\boxed{x{y'}=-y}
\end{align}
$$

From the above example, we observed that the solution contains an arbitrary
constant $c$. Such solutions can be recalled as the __General Solution__ of
an ODE. The opposite of this is a __Particular Solution__ of an ODE.

__Initial Value Problem__

__Initial Condition:__ a condition given in the form of $y(x_o)=y_o$ with a given $(x_o,y_o)$ used to find the arbitrary value $c$.
An initial value problem is an ODE together with an initial condition.

__Example__: Solve the initial value for the problem ${y'}=\frac{dy}{dx}=3y$, $\quad y(0)=5.7$

__Solution:__

$$
\begin{align}
&{y'}=\frac{dy}{dx}=3y \\
&dy=3y \cdot dx \\
&\frac{dy}{y}=3 \cdot dx \\
&\int{\frac{1}{y}}{dy}= \int{3}{dx} \\
&ln \left| y \right| = 3x+c \\
&y=e^{3x+c}=e^{3x}\cdot e^{c} \qquad let\ C_1=e^{c} \\
&y=C_1e^{3x} \\
&y(0)=C_1e^{3\cdot0}=C_1=5.7 \\
&\boxed{y(x)=5.7e^{3x}}
\end{align}
$$

Therefore, the initial value of ${y'}=\frac{dy}{dx}=3y$ is $\boxed{y(x)=5.7e^{3x}}$

## 1.2 Separable ODEs

__Separable ODEs:__ are ODEs whose $x$ and $y$ parts can be separated into the two separate sides of the equation.

This is done by integrating both sides of the equation and expressing  the equation in terms of $y$.

__Example:__ Separate the ODE ${y'}=1+y^2$

__Solution:__

$$
\begin{align}
&{y'}=1+y^2 \qquad \qquad \qquad write\ {y'}\ interms\ of\ \frac{dy}{dx}  \\
&\frac{dy}{dx}=1+y^2 \qquad \qquad \qquad separate\ the\ y\ and\ x\ terms\ \\
&\frac{dy}{1+y^2}=dx  \qquad \qquad \qquad integrate\ both\ sides\  \\
&\int{\frac{dy}{1+y^2}}=\int{1}{dx} \\
&{tan^{-1}(y)= x + C} \\
&\boxed{y=tan(x+C)} \\
\end{align}
$$

$$
Therefore, the ODE ${y'}=1+y^2$ can be separated and written as $\boxed{y=tan(x+C)}$
