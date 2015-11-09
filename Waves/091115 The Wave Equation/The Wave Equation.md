# The Wave Equation

Waves on a stretched string can have different wave shapes, or wave forms, but they all have the same wave speed, for a string with a set tension - but what are some other features?

To find these features we can form a differential equation. If we assume that the amplitude of the wave is small, and take a small section of the string $l$, we can apply Newton's second law

$$ F = ma $$

and we know the linear density of the string $\mu$ and it's length $l$ so

$$m = \mu l$$

and, knowing the vertical acceleration $a_y$ we can find $F_y$

$$F_y = \mu l a_y$$

and we also know that 

$$ a_y = \frac{d^2y}{dt^2} $$

The string has two tensions on it, one pulling it left, $\vec{F_1}$, and one pulling it right, $\vec{F_2}$.

Using this we can find the resultant vertical force on $l$

$$ F_y = F_{2_y} - F_{1_y} $$

So, to find $F_{i_y}$ 

$$ \frac{F_{i_y}}{F_{i_x}} = S_i $$

$$ F_{i_y} = F_{i_x}S_i \approx \tau S_2 $$

So the total force

$$ F_y = \tau S_2 - \tau S_1 $$

Which we can then use to form the differential equation

$$ \frac{\tau S_2 - \tau S_1}{dx} = \frac{\mu}{\tau} \frac{d^2y}{dt^2} $$

Which we can then manipulate to give

$$ \frac{\delta^2y}{\delta x^2} = \frac{\mu}{\tau} \frac{\delta^2y}{\delta dt^2} $$

and, because we know that $v = \sqrt{\tau/\mu}$

$$ \frac{\delta^2y}{\delta x^2} = \frac{1}{v^2} \frac{\delta^2y}{\delta dt^2} $$

**Example:** Does the following equation for a periodic wave satisfy the wave equation?

$$ y(x, t) = y_m\sin(kx - \omega t) $$

So, substituting

$$ \frac{d^2}{dx^2}\big(y_m\sin(kx - \omega t)\big) = \frac{1}{v^2} \frac{d^2}{dt^2}\big(y_m\sin(kx - \omega t)\big) $$

Then differentiating

$$ -k^2y_m\sin(kx - \omega t) = - \frac{1}{v^2} y_m \omega^2 \sin(kx - \omega t)$$

Removing like terms

$$ k^2 = \frac{\omega^2}{v^2}$$

$$k = \frac{\omega}{v} $$

Which we know is true from previous lectures, therefore the wave satisfies the wave equation.

A general wave has the following form

$$ y(x, t) = h(kx \pm \omega t) $$

It is therefore possible to prove that any wave fits the wave formula.
