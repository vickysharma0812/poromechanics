# 𑗕 Fundamental equation of Thermodynamics

## Internal energy

For a reversible process in a close system with no additional work than expansive work, the first law of thermodynamics states that,

$$
dU=\delta q - pdV
$$

The second law of thermodynamics states that

$$
\delta q_{rev} = TdS
$$

By combining the first and the second law, we can obtain the fundamental equation, which is given below.

$$
dU = T dS - p dV
$$

!!! note ""
    In this way, we can apply the above equation to any change (reversible or irreversible) of closed system that does no additional (non-expansion) work. This is because $dU$ is exact differential, and its value is independent of the process as $U$ is a state-variable.

The fundamental equation suggests that $U=U(S,V)$, and

$$
dU = \left( \frac{\partial U}{\partial S} \right )_{V} dS + \left (\frac{\partial U}{\partial V} \right )_{S} dV
$$

By comparing above equation with the fundamental equation, one can derive the thermodynamic definition of temperature and pressure.

$$
T=\left( \frac{\partial U}{\partial S} \right )_{V}
$$

and,

$$
p = - \left (\frac{\partial U}{\partial V} \right )_{S}
$$

We can also derive following relationship while noting that $dU$ is extact differential.

$$
\left( \frac{\partial T}{\partial V} \right )_{S} = -\left( \frac{\partial V}{\partial S} \right )_{V}
$$

## Internal pressure

Internal pressure $\pi_{T}$, denotes the change in internal energy with change in the volume during an isothermal process.

$$
\pi_{T} = \left ( \frac{\partial U}{\partial V} \right )_{T}
$$

To derive an expression for $\pi_{T}$ we start from the fundamental equation,

$$
dU = TdS - p dV
$$

$$
\pi_{T} = T \left ( \frac{\partial S}{\partial V} \right )_{T} - p
$$

Noting that

$$
\left ( \frac{\partial S}{\partial V} \right )_{T} = \left ( \frac{\partial p}{\partial T} \right )_{V}
$$

we obtain

$$
\pi_{T} = T  \left ( \frac{\partial p}{\partial T} \right )_{V} - p
$$

## Enthalpy

$$
H=U+pV
$$

$$
dH = dU + d(pV)
$$

$$
dH = TdS + Vdp
$$

$$
T=\left( \frac{\partial H}{\partial S} \right )_{p}
$$

$$
V=\left( \frac{\partial H}{\partial p} \right )_{S}
$$

Also,

$$
\left( \frac{\partial T}{\partial p} \right )_{S} = \left( \frac{\partial V}{\partial S} \right )_{p}
$$

## Helmholtz energy

$$
A = U - TS
$$

## Gibbs energy

Gibbs energy functional is given by

$$
G = H - TS
$$

The differential form is given by

$$
dG = dH - T dS - S dT
$$

Noting $dH$ as given above, we can obtain the fundamental equation of chemical thermodynamics.

$$
dG = TdS + Vdp - T dS - S dT
$$

$$
dG = Vdp - S dT
$$

> $G$ is a state variable, and $dG$ is exact differential. $G$ can be regarded as a function of $p$ and $T$.

$$
V = \left ( \frac{\partial G}{\partial p} \right )_{T}
$$

$$
S = -\left ( \frac{\partial G}{\partial T} \right )_{p}
$$

!!! note ""
    As $S>0$ for all the substance, G always decreases with increase in the temperature for a closed system at constant pressure.

!!! note ""
    As $V>0$ for al the substance, G always increases with the pressure at constant temperature.

!!! success ""
    As $S$ increases, $\left ( \frac{\partial G}{\partial T} \right )_{p}$ becomes more negative. This means that G will decrease sharply with temperature when the entropy of the system is large. Due to this, G of a gaseous phase is more sensitive to T than its liquid or solid phase.

!!! success ""
    As $V$ increases, $\left ( \frac{\partial G}{\partial p} \right )_{T}$ becomes more positive. This means that G will increase sharply with pressure when the volume of the system is large. Due to this reason, G of a gaseous phase is more sensitive to p than its liquid or solid phase.
