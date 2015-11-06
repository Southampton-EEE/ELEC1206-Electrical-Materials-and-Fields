# Forced Oscillation

*Reading: Section 15.*

The driving force is harmonic:

$$ F_e(t) = F_0\cos{(\omega_dt)} $$

$\omega_d$ is the angular frequency of the driving force.

Using Newton II ($F = ma$) we can form a differential equation for a force harmonic motion:

$$ m\frac{d^2x}{dt^2} + b\frac{dt}{dt} + kx = F_0\cos{(\omega_dt)} $$

The steady state solution:

$$ x(t) = x_m\cos{(\omega_dt+\phi)} $$

where

$$ x_m = \frac{F_0}{\sqrt{m^2(\omega_d^2-\omega^2)^2+b^2\omega_d^2}} $$

So, to find $x_m$ we calculate the maximum of $\omega^2$:

$$ \omega_{max}^2 = \omega - \frac{1}{2}\frac{b^2}{m^2} $$

