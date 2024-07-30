# Induced EMF and Current

**Question:** 

A magnetic field \( B \) is directed outward perpendicular to the plane of a circular coil of radius \( r = 0.8m \). The field is cylindrically symmetrical with respect to the center of the coil, and its magnitude decays exponentially according to \( B = 2.5e^{-5t} \) where \( B \) is in Teslas and \( t \) is in seconds.

(a) Calculate the emf induced in the coil at the times ( $t_1 = 0s$ ), ( $t_2 = 3 \times 10^{-2}s$ ), and ( $t_3 = 2s$ ).
.

(b) Determine the current in the coil at these times if the resistance is \( 20Ω \).

### Solution:

#### (a) Calculate the emf:

The magnetic flux \( \Phi \) through the coil is:

$$
\Phi = B \cdot A = B \cdot \pi r^2 = B \cdot \pi (0.8m)^2 = B \cdot 2.01m^2
$$

The induced emf \( E \) is:

$$
E = -\frac{d\Phi}{dt} = -2.01 \frac{dB}{dt}
$$

Given \( B = 2.5e^{-5t} \):

$$
\frac{dB}{dt} = -5 \cdot 2.5e^{-5t} = -12.5e^{-5t}
$$

Therefore:

$$
E = 2.01 \cdot 12.5e^{-5t} = 25.125e^{-5t}
$$

At \( t_1 = 0s \):

$$
E = 25.125 \cdot e^0 = 25.125V
$$

At \( t_2 = 3 \times 10^{-2}s \):

$$
E = 25.125 \cdot e^{-0.15} \approx 25.125 \cdot 0.861 = 21.63V
$$

At \( t_3 = 2s \):

$$
E = 25.125 \cdot e^{-10} \approx 25.125 \cdot 4.54 \times 10^{-5} = 1.14 \times 10^{-3}V
$$

#### (b) Determine the current in the coil at these times if the resistance is \( 20Ω \):

Current in the coil \( I = \frac{E}{R} \):

At \( t_1 = 0s \):

$$
I = \frac{25.125V}{20Ω} = 1.256A
$$

At \( t_2 = 3 \times 10^{-2}s \):

$$
I = \frac{21.63V}{20Ω} = 1.081A
$$

At \( t_3 = 2s \):

$$
I = \frac{1.14 \times 10^{-3}V}{20Ω} = 5.7 \times 10^{-5}A
$$
