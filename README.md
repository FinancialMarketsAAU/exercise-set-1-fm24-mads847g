# Exercise Set 1 for the Financial Markets Course

Commit with your solutions.

1)  
i. $\prec$ is both irreflexive and transitive

Proof 1: If x $\succ$ x then x $\succsim$ x but also $\neg$ x $\succsim$ x, which is simply impossible.

Proof 2: Let x $\prec$ y and y $\prec$ z and x $\neq$ z. Then x $\precsim$ y and y $\precsim$ z and thus x $\precsim$ z. Since x $\neq$ z then x $\prec$ z and transitivity has been proven.

ii. $\sim$ is reflexive, transitive and symmetric

Proof 1: Let's consider x $\succsim$ x and x $\precsim$ x and since $\succsim$ is rational, then it yields x $\sim$ x $\forall$x $\in$ X. 

Proof 2: Let x $\sim$ y and y $\sim$ z. Since it's known that x $\precsim$ y and y $\precsim$ z $\Rightarrow$ x $\precsim$ z and thus x $\sim$ z.

Proof 3: Let x $\sim$ y. It's known that if x $\succsim$ y and x $\precsim$ y then x $\sim$ y. Thus y $\sim$ x. 

iii. if x $\succ$ y $\succsim$ z, then x $\succ$ z. 

Proof 1: Let x $\succ$ y $\succsim$ z. Since $\succsim$ is transitive, it's known that x $\succsim$ y $\succsim$ z, but since x $\succ$ y, x $\succ$ z!

2)
i. Show that $\succsim$ is transitive

Proof: Let $(x_1,x_2)\precsim (y_1,y_2)$ and $(y_1,y_2)\precsim (z_1,z_2)$. Since $(x_1,x_2)\precsim (y_1,y_2)$ then $x_1 > y_1$ or $x_1 = y_1$ and $x_2 \geq y_2$. 
Since $(y_1,y_2)\precsim (z_1,z_2)$ then $y_1 > z_1$ or $y_1 = z_1$ and $y_2 \geq z_2$. Thus $x_1 > z_1$ or $x_1 = z_1$ and $x_2 \geq z_2$ and thus $(x_1,x_2)\precsim (z_1,z_2)$!

ii. Show that $\succsim$ is not continuous

Proof: In order to solve the task, let's consider the sequence $(x_1^n,x_2^n)=(1-\frac{1}{n},1)$ and $(y_1,y_2)=(1,0)$. Let's observe the sequence $(x_1^n,x_2^n)$ as $n$ goes to infinity: $\lim_{n\rightarrow\infty}1-\frac{1}{n}=0$. Thus for any arbitrary n the relation is $(y_1,y_2) \succsim (x_1^n,x_2^n)$ but at the limit, $(y_1,y_2) \precsim (x_1^n,x_2^n)$

3)
i. Show that when $\rho=1$, indifference curves become linear.

Proof: In order to show that $\U$ is linear, we have to show the following conditions are satisfied:

- $U(x+y)=U(x)+U(y)$

- $U(cx)=cU(x)$

$U(x+y)=\alpha_1(x_1+y_1)+\alpha_2(x_2+y_2)=\alpha_1x_1+\alpha_2x_2+\alpha_1y_1+\alpha_2y_2=U(x)+U(y)$, so first condition is satisfied!

$U(cx)=(c\alpha_1x_1+c\alpha_2x_2)=c(\alpha_1x_1+\alpha_2x_2)=cU(x)$, so second condition is satisfied!

ii)
$U(x)=(\alpha_1x_1^{\rho}+\alpha_2x_2^{\rho})^{1/{\rho}}$,
$ln(U)=\lim_{\rho \to \infty}(\frac{ln(\alpha_1x_1^p+\alpha_2x_2^p)}{\rho})$
$=\frac{\alpha_1x_1^{\rho}ln(x_1)+\alpha_2x_2^{\rho}ln(x_2)}{\alpha_1x_1^{\rho}+\alpha_2x_2^{\rho}}$
$=\frac{ln(x_1^{\alpha_1}x_2^{\alpha_2})}{\alpha_1+\alpha_2}$
taken the inverse of ln, we get $x_1^{\alpha_1}x_2^{\alpha_2}$. 
It means that the utility function U(x) represent the same preferences as the generalized Cobb-Douglas function.


  

