A cylinder of mass $M$, radius $R$, and rotational inertia $I$ spins at an initial angular velocity $\omega_0$ as it is lowered onto a horizontal surface where the coefficient of friction between it and the surface is $\mu$. Find the time $t$ from the moment it contacts the surface to when it starts rolling without slipping.

The net force is kinetic friction, so $\mu Mg=Ma$, so $a=\mu g$, accelerating the cylinder's center of mass from rest. Kinetic friction also exerts a net torque $\mu M g R$, so $\mu M g R = I \alpha$, such that $\alpha = \frac{\mu M g R}{I}$, decelerating the cylinder's angular speed. We're finding the time at which the increasing velocity matches the decreasing angular speed such that $v=R\omega$.

Since $a$ and $\alpha$ are both constant, we can use the kinematics equations for constant acceleration.

$$v = 0 + a t \text{ and } \omega = \omega_0 - \alpha t$$
$$a t = R(\omega_0 - \alpha t)$$
$$\mu g t = R(\omega_0 - \frac{\mu M g R}{I} t)$$
$$\mu g t = R\omega_0 - \frac{\mu M g R^2}{I} t$$
$$\mu g t + \frac{\mu M g R^2}{I} t= R\omega_0 $$
$$t(\mu g + \frac{\mu M g R^2}{I}) = R\omega_0$$
$$t = \frac{R\omega_0}{\mu g(1 + \frac{M R^2}{I})}$$.
Notice that $I$ is $MR^2$ if it is hollow and $\frac{1}{2}MR^2$ if it is solid, so this can be simplified further. If it is hollow we end up with $$t = \frac{R\omega_0}{ 2\mu g}$$. 

#kata