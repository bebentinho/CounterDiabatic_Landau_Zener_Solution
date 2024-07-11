Codes used for solving the Landau-Zener model with and without the counter-diabatic drive.

To calculate the evolution operator $\hat{U}(t)$, the Schrödinger Equation was solved:

$$ i \partial_t\hat{U}(t) = \hat{H}(t)\hat{U}(t) $$

The procedure was done according to:

Ya-Feng Cao, Lian-Fu Wei, Bang-Pin Hou,
Exact solutions to Landau–Zener problems by evolution operator method,
Physics Letters A,
Volume 374, Issue 22,
2010,
Pages 2281-2285,
ISSN 0375-9601,
<https://doi.org/10.1016/j.physleta.2010.03.034.>

But with the hamiltonian

$$

$$ \hat{H}_{CD}(t) = \hat{H}_{0}(t) + \hat{H}_{aux}(t) $$

And

$$ \hat{H}_{aux}(t) = - i \frac{\Delta \dot{g}(t)}{2(\Delta^2 + g^2(t))} \sigma_y $$

That way, the differential system solved numerically was:

$$ \dot{\alpha}(t) = -A(t) cos(2 \alpha) tan (2 \beta) - C(t) sin (2 \alpha) tan(2 \beta) - B(t) $$

$$ \dot{\beta}(t) = A(t) sin(2 \alpha) - C(t) cos(2 \alpha) $$

$$ \dot{\gamma}(t) = -A(t) \frac{cos(2 \alpha)}{cos(2\beta)} - C(t) \frac{sin(2 \alpha)}{cos(2 \beta)} $$

With:

$$ A(t) = g(t) $$

$$ B(t) = \Delta $$

$$ C(t) = - \frac{\Delta \dot{g}(t)}{2(\Delta^2 + g^2(t))} $$
