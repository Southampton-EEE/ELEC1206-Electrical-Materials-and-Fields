# Coupled Oscillators

A coupled oscillator is where twi SHM systems are attached, for example, connecting two mass-sprint systems with another spring. 

Using Hooke's Law, $F = -kx$, and Newton II, $F = ma = m\frac{d^2x}{dt^2}$:

Dynamics of $m_1$:

$$ m\frac{\delta^2x_1}{\delta t^2} = -kx_1 - k(x_1 - x_2) = $$
$$ = -2kx_1 + kx_2 $$

Dynamics of $m_2$:

$$ m\frac{\delta^2x_2}{\delta t^2} = -kx_2 - k(x_2 - x_1) =$$
$$ = -2kx_2 + kx_1 $$

From which you can get:

$$ \frac{\delta^2(x_1 + x_2)}{\delta t^2} = -\frac{k}{m}(x_1+x_2)$$

So, further:

$$ x_1 + x_2 = x_{m1}\cos{(\omega t + \phi_1)} $$

$$ x_1 - x_2 = x_{m2}\cos{(\omega t + \phi_2)} $$

Even further:

$$ x_1(t) = \frac{1}{2}x_{m1}\cos(\omega_1 t +\phi_1) + \frac{1}{2}x_{m1}\cos(\omega_2 t +\phi_2) $$

$$ x_2(t) = \frac{1}{2}x_{m1}\cos(\omega_1 t +\phi_1) - \frac{1}{2}x_{m1}\cos(\omega_2 t +\phi_2) $$

# Forced Coupled Oscillators

Just as in normal forced SHM we apply a harmonic driving force, only to one of the two masses:

$$ F_e(t) = F_0\cos(\omega_d t) $$

Where $\omega_d$ can be the same or different as $\omega_1$ or $\omega_2$.

Using Newton II ($F=ma$) we can derive a differential equation for the two masses:

$$ x_1: \ \ m\frac{d^2x_1}{dt^2} = -kx_1 - k(x_1 - x_2) + F_0cos(\omega_d t) $$

$$ x_2: \ \ m\frac{d^2x_2}{dt^2} = -kx_1 - k(x_1 - x_2) $$

So, adding the two equations gives:

$$ m\frac{d^2(x_1 + x_2)}{dt^2} = -k(x_1 + x_2) + F_0\cos(\omega_d t) $$

and subtracting them

$$ m\frac{d^2(x_1 - x_2)}{dt^2} = F_0\cos(\omega_dt)-3k(x_1 - x_2) $$

and we know that

$$ x_m = \frac{\frac{F_0}{m}}{\omega^2 - \omega_d^2} $$

so 

$$ x_1 + x_2 = \frac{\frac{F_0}{m}}{\omega_1^2 - \omega_d^2} \cos(\omega_dt) $$

