# Rotacional de um campo

O rotacional é um vetor que mostra como um ponto em um campo vetorial gira gira alegria. 

Em geral, podemos dizer que:

$rot\vec{V} = \vec{\nabla}\times\vec{V}$

## Rotacional em um plano 2D

$rot\vec{V} = (-\frac{\partial v_x}{\partial y}+\frac{\partial v_y}{\partial x})\hat{k}$

No 2D, quando ele é positivo ele gira anti-horário, quando é negativo ele gira horário. Sei lá pq

## Rotacional em um plano 3D

$rot\vec{V} = (-\frac{\partial v_y}{\partial z}+\frac{\partial v_z}{\partial y})\hat{i} + (-\frac{\partial v_z}{\partial x}+\frac{\partial v_x}{\partial z})\hat{j}+(-\frac{\partial v_x}{\partial y}+\frac{\partial v_y}{\partial x})\hat{k}$

## Campo conservativo

Foi definido no começo do curso que um campo vetorial é conservativo quanto existe uma função escalar $\varphi(x,y,z)$ tal que $\vec{\nabla}\varphi=\vec{F}$, ou seja, o campo é conservativo se existe uma função escalar cujo gradiente é o próprio campo vetorial.

Se um campo é conservativo, então $rot\vec{F} = \vec{0}$

## Leis de Maxwell recap

$\oint \vec{E}\cdot \hat{n}dA=\frac{Q}{\varepsilon_0}$<br><br>
$\oint \vec{B}\cdot \hat{n}dA=0$<br><br>
$\oint \vec{E}\cdot d\vec{r}=\frac{d\int\vec{B}\cdot\hat{n}dA}{dt}$<br><br>
$\oint \vec{B}\cdot d\vec{r}=\mu_0(i+\varepsilon_0\cdot\frac{d\int\vec{E}\cdot\hat{n}dA}{dt})$<br><br>

## Leis de Maxwell em forma diferencial

As leis de Maxwell na forma diferencial descrevem o comportamento dos campos elétrico e magnético num ponto do espaço

$\vec{\nabla}\cdot\vec{E} = \frac{\rho}{\varepsilon_0}$<br><br>
$\vec{\nabla}\cdot\vec{B} = 0$<br><br>
$\vec{\nabla}\times\vec{E} = -\frac{d\vec{B}}{dt}$<br><br>
$\vec{\nabla}\times\vec{B} = \mu_0(\vec{J}+\frac{d\vec{E}}{dt}\varepsilon_0)$<br><br>

Onde $\vec{J}$ é o vetor densidade superficial de corrente