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
λ = \frac{2π v_p}{ω} = \frac{2π v_p}{2πf} = \frac{v_p}{f} = \frac{c}{\sqrt{ϵ}_r f}
$$

## About: the reflection coefficient at different points of a lossless TL

* The reflection coefficient in any lossless transmission line remains constant
  in magnitude.
* Any movement in the TL implies a rotation of $Γ(z)$ in the $|Γ_L|$ circle.

## Concept of Matching

* Matching in a TL: $Γ_L = \frac{Z_L-Z_0}{Z_L+Z_0}$ ⟹ Standing wave
* Conjugate matching

## Smith Chart

**Definition**: A calculus chart that directly represents reflection
coefficients rising in a transmission line in a polar pattern

> "The Smith Chart is much more than a graphic representation, since all CAD
> tools incorporate it in their representation."
>
> – Daniel Segovia Vargas

$$
\begin{align}
    Γ(l) = \frac{V^- e^{-jΒl}}{V^+ e^{jβl}}
        = Γ(0) e^{-j2βl}
        = |Γ_L| e^{jϕ_L} e^{-j2βl}
\end{align}
$$

Starting from the polar representation of $Γ_L$, when moving towards the
generator (away from the load), expression (1) will have increasing values for
l, which implies:

1. The value will stay in the circle of constant radius $|Γ_L|$ (as always)
2. The rotation will be given by $2βl$ in the **clockwise** direction.

### Representing impedances

If we want to represent an impedance

$$
Z(l) = Z₀ \frac{1+Γ(l)}{1-Γ(l)}
$$

In order to have a general expression, we need to **normalize** the magnitude,
which means we must divide by the characteristic magnitude:

$$
\bar{z}_L = \frac{Z_L}{Z₀} \\
\bar{y}_L = \frac{Y_L}{Y₀} \\
\bar{z}(l) = \frac{1 + Γ(l)}{1 - Γ(l)}
$$ 

In order to **de-normalize**, we will multiply the normalized magnitude by the
characteristic magnitude:

$$
Z_L = \bar{z}_L Z₀ \\
Y_L = \bar{y}_L Y₀
$$
