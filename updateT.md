##  Update T

#### primal problem:

${T}_k^{(l+1)}=\arg\sideset{}{_{{T}_k\in \Pi({\mu}_c^k,{\mu}_d^k)}}\min\langle-{P},{T}_k\rangle +
\frac{\rho}{2}\|{T}_k-{Z}_k^{(l)}+{U}_k^{(l)}\|_F^2,~\text{for}~k=1,...,K.$

#### Add a convex regularization

${OT_\Omega(u_c,u_d)}:= \mathop{\min}_{T \in \mathcal U(u_c,u_d)}\min\langle-{P},{T}_k\rangle +
\frac{\rho}{2}\|{T}_k-{Z}_k^{(l)}+{U}_k^{(l)}\|_F^2+\sum\limits_{j=1}^n \Omega(t_j)$

Group lasso: $\Omega(y)=\gamma(\frac{1}{2}||y||^2+\mu\sum\limits_{G\in\mathcal G}||y_G||)$

#### dual problem:

${OT(u_c,u_d)}:= \mathop{\max}_{\alpha,\beta \in \mathcal P(C)}\alpha^Tu_c+\beta^Tu_d-\sum\limits_{j=1}^n \delta_\Omega(\alpha+\beta_j{1_m}-{p_j}).$

$\delta_\Omega(x)=x^Ty^*-\Omega(y^*)$

$y^*=\nabla\delta_\Omega(x)=\left [1-\frac{\mu}{||x_G^+||} \right]x_G^+$



