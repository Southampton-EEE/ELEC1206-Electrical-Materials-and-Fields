Damped SHM
==========

After a mass starts moving it’s amplitude gradually decreases with time
because of the resistive forces due to the air. The time period does not
change as the amplitude decreases, but the time period is larger then a
equivalent system with no resistive forces.

Hooke's Law: $F\_r = -kx$
Damping: $F\_d = -bv$ Newton II: $F = ma = \frac{md^2x}{dt^2}$

Equation of a damped SHM system:

$$ m\frac{d^2x}{dt^2}  + b\frac{dx}{dt} + kx = 0 $$

$$ Ae^{\frac{-bt}{2m}}\cos{(\omega't+\phi)} $$

$$ \omega' = \sqrt{\frac{k}{m} - \frac{b^2}{4m^2}} $$

So, therefore if $b = 0$ then $\omega = \omega'$, but if $b
\llless \sqrt{km}$ then $\omega' \approx \omega$.

The total mechanical energy of a damped system decreases as it does work
against resistive forces.

$$ U(t) = \frac{1}{2}lA^2e^{-\frac{bt}{m}}\cos^2{(\omega't+\phi)} $$
$$ K(t) \approx \frac{1}{2}lA^2e^{-\frac{bt}{m}}\sin^2{(\omega't+\phi)} $$
$$ E(t) = U(t) + K(t) \approx \frac{1}{2}kA^2e^{-\frac{bt}{m}} $$
