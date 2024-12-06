# 𑗕 Thermodynamics of mixture

Definition of some keywords

**Binary mixture** is a mixture of two components.

## Partial molar volume

!!! note ""
    The partial molar volume of a substance A in a mixture is the change in volume of the mixture when one mole of A is added to a large volume of the mixture.

The partial molar volume of a component in the mixture depends upon the composition of the mixture. For example, the partial molar volume of pure water at 25 ${}^{\circ} C$ is 18 cm3/mol when the solvant is pure water. But, the partial molume of pure water at 25 degree C is 14 cm3/mol, when the solvant is pure ethanol.

Mathematically, the partial molar volume is given by the following expression.

$$
V_{J} = \left ( \frac{\partial V}{\partial n_{J}} \right )_{p,T,n}
$$

- [ ] TODO Describe the above equation.

For the sake of simplicity, let us focus on the binary mixture. There are two components A and B, which do not react with each other.

When the amount of A is changed by $\Delta n_{A}$ then the change in volume of the mixture is given by

$$
\Delta V_{A} = \text{\left(\frac{\partial V}{\partial n_{A}}\right)}_{p,T,n_{B}}\Delta n_{A}
$$

When the amount of B changes by $\Delta n_{B}$, then the change in volume of the mixture is given by

$$
\Delta V_{B}=\text{\left(\frac{\partial V}{\partial n_{B}}\right)}_{p,T,n_{A}}\Delta n_{B}
$$

Therefore, the total change in volume when A changes by $\Delta n_{A}$ and B changes by $\Delta n_{B}$ is given by

$$
\Delta V=\Delta V_{A}+\Delta V_{B}=\text{\left(\frac{\partial V}{\partial n_{A}}\right)}_{p,T,n_{B}}\Delta n_{A}+\text{\left(\frac{\partial V}{\partial n_{B}}\right)}_{p,T,n_{A}}\Delta n_{B}
$$

or

$$
\Delta V = V_{A} \Delta n_{A} + V_{B} \Delta n_{B}
$$

If we assume that the ratio of $n_A$ and $n_B$ remains constant, and the $V_{A}$ and $V_{B}$ are almost constant, then

$$
V = V_{A} n_{A} + V_{B} n_{B}
$$

!!! settings ""
    Molar volumes are always positive, but partial molar quantities can be negative.

## Partial molar Gibbs energies

Similar to the concept of partial molar volume, we can devise the concept of partial molar Gibbs energy of a component in the mixture. We just need to replace volume by Gibbs energy. Also, the partial molar Gibbs energy of a component in mixture is called the chemical potential of that component. Therefore,

$$
\mu_{J}=\text{\left(\frac{\partial G}{\partial n_{J}}\right)}_{p,T,n}
$$

Where, $n$ is the amount of all other components in the mixture. Note that the pressure, temperature, and $n$ remains constant.

In other words, $\mu_{J}$ is a measure of the change in Gibbs energy of the mixture when one mole of component $J$ is added to the large amount of the mixture.

For a pure substance, $\mu_{J}=G_{J,m}$, that is, molar Gibbs energy is same as the chemical potential of the substance.
