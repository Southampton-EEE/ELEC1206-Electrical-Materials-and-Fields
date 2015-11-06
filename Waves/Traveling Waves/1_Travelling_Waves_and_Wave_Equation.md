# Travelling Waves and Wave Equation

## Introduction to Waves

*Reading: Sections 16.1 though 16.5*

At time t the displacement of y at position x is

$$ y(x, t) = y_m\sin(kx \pm \omega t) $$

So, for a wavelength of lambda you have a wave number of 

$$ k = \frac{2\pi}{\lambda} $$

Therefore, by fixing the position at $ x = 0 $ we observe the motion

$$ y(0,t) = -y_m\sin(\omega t) $$
$$ y(0,t) = y_m\cos\big(\omega t - \frac{\pi}{2}\big) $$

Which is the form of SHM.

We can get the speed of a travelling wave

$$ v = \frac{\omega}{k} = \lambda f $$

## Waves on a Stretched String 

*Reading: Sections 16.6-16.7*

An element $\Delta l$ os moving in the arc of a circle so it's acceleration is

$$ a = \frac{v^2}{r} $$

Using Newton II ($F = \Delta ma$) and considering the tension on the element

$$ F = 2(\tau\sin\theta) \approx 2\theta\tau \approx \tau\frac{\Delta l}{r}$$

The mass of the element

$$ \Delta m = \mu \Delta l $$

Then gives

$$ \tau\frac{\Delta l}{r} = (\mu\Delta l)\frac{v^2}{r} $$

So to find $v$

$$ v = \sqrt{\tau / \mu} $$

The power delivered to the string

$$ P = \vec{F}\ \vec{v}_{transverse} $$

So, you can then say that

$$ P = -\tau \frac{dy}{dt}\frac{dy}{dx} $$

Finally,

$$P = \mu v \omega^2 y^2_m \cos^2 (ks - \omega t)$$

