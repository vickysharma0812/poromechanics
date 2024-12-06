# 𑗕 Changes in enthalpy

The enthalpy of a system is given by

$$
H = U + pV
$$

$H$ is a state dependent function.  Let $p,T$ be the independent state variables, then

$$
H:=H(p,T)
$$

The total change in $H$ is given by

$$
dH = \left( \frac{\partial H}{\partial p} \right)_T dp + \left( \frac{\partial H}{\partial T} \right)_p dT
$$

By using the definition of heat capacity at constant pressure, the above equation becomes.

$$
dH = \left( \frac{\partial H}{\partial p} \right)_T dp + C_p dT
$$

Now consider *isenthalpic* curves in $T,P$ space, where $H(P,T)$ remains constant. Along these curves we have $dH=0$.

$$
\left( \frac{\partial H}{\partial p} \right)_T dp + C_p dT = 0
$$

Which leads to the following expression

$$
\left( \frac{\partial H}{\partial p} \right)_T = -C_{p} \mu
$$

Where $\mu$ is the Joule-Thomson Coefficient of the gas, and it is given as the slope of an isenthalpic curve.

$$
\mu = \left( \frac{\partial T}{\partial P} \right)_H
$$

Therefore,

$$
dH = C_p dT - C_{p} \mu dp
$$

or,

$$
\Delta H = \int_{T_1}^{T_2} C_p dT - \int_{p1}^{p2} C_p \mu dp
$$
