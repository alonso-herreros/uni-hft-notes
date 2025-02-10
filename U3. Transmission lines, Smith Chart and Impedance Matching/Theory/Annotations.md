## High Frequency Technologies <!-- omit in toc -->

# Unit 2 annotations

*Academic year 2024-2025*  
*Telematics Engineering Department - Universidad Carlos III de Madrid*

---

## About: propagation equations in a transmission line

*Transmission Lines And Smith Chart - Slide 9*

* Inductance has been defined in static conditions. If this were not so, the
  skin effect would have to be taken into account.
* Radiation losses have not been considered, this is always valid whenever
  the electrical spacing between is much smaller than $d$.
* The solution of the wave equation would be as follows:

$$
V(z) = F_1 (t - \frac{z}{v_p})  + F_2 (t + \frac{z}{v_p})
$$

Where:

* $F_1$ is a progressive wave: if $t$ increases, $z$ must increase in order to
  keep the argument constant.
* $F_2$ is a regressive wave: if $t$ increases, $z$ must decrease in order to
  keep the argument constant.

Both solutions ($F_1$ and $F_2$) exist whenever the ending condition of the
transmission line.

## Expressions of lambda

$$
λ = \frac{2π v_p}{ω} = \frac{2π v_p}{2πf} = \frac{v_p}{f} = \frac{c}{ϵ_r f}
$$

## About: the reflection coefficient at different points of a lossless TL

* The reflection coefficient in any lossless transmission line remains constant
  in magnitude.
* Any movement in the TL implies a rotation of $Γ(z)$ in the $|Γ_L|$ circle.
