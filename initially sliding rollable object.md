A cylinder of mass $M$, radius $R$, and rotational inerta $I$ slides along a horizontal surface with negligible friction at velocity $v_0$, before entering a region where the coefficient of friction between it and the surface is $\mu_0$ at time $t_0$. Find the time $t_s$ at which it starts rolling without slipping.

This is worked out the same way as [[initially spinning rollable object]] but with the initial linear and angular velocities reversed.
We're finding the time at which the increasing velocity matches the decreasing angular speed such that $v=R\omega$.

$$v = v_0 - a t \text{ and } \omega = 0 + \alpha t$$
$$v_0 - a t = R\alpha t$$
$$v_0 - \mu g t = R \frac{\mu M g R}{I} t$$
$$v_0 - a t = \frac{\mu M g R^2}{I} t$$
$$-\mu g t + \frac{\mu M g R^2}{I} t= -v_0 $$
$$t(-\mu g + \frac{\mu M g R^2}{I}) = -v_0$$
$$t = \frac{-v_0}{-\mu g(1 + \frac{M R^2}{I})}=\frac{v_0}{\mu g(1 + \frac{M R^2}{I})}$$
Notice that $I$ is $MR^2$ if it is hollow and $\frac{1}{2}MR^2$ if it is solid, so this can be simplified further. If it is hollow we end up with $$t = \frac{v_0}{ 2\mu g}$$


#kata