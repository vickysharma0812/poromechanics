# 𑗕 Changes in Internal energy

The internal energy of an ideal gas depends only on the temperature of the gas because intermolecular forces and the corresponding potential energy are negligible in an ideal gas. Therefore, internal energy only depends upon the kinetic energy of molecules, which in turn depends upon the temperature. Therefore, the internal energy of an ideal gas is given by

$$
U_{ideal}=\frac{f}{2}RT
$$

where, $f$ is the total number of degree of freedom of gas molecule.

In case of real gas, intermolecular forces play an important role. Therefore, the internal energy is given as sum of the kinetic energy  and potential energy of the molecule. Note that the potential energy of a molecule depends upon the forces acting on it due to other molecules. As a result, intermolecular distances control the potential energy. In other words, internal energy depends upon volume of the gas as well as the temperature of the gas. Therefore,

$$
U:=U(V,T)
$$

We can also relate the pressure, volume and temperature by using the equation of state. In this way, we can express internal energy in terms of any two state variables out of $P,V,T$.

Another important point to note is that internal energy is a state function, it means its value only depends upon the state variables (i.e., variable that define state of the system). Therefore, the change in internal energy of a system, only depends upon the initial and final state of the system, that is, it does not depend upon the path of the process.

The total change in $U$ is caused by the change in $T$ and $V$ , which is expressed as follows.

$$
dU = \left( \frac{\partial U}{\partial V} \right)_T dV + \left( \frac{\partial U}{\partial T} \right)_V dT
$$

By using the definition of heat capacity at constant volume, we can obtain the following relationship.

$$
dU = \left( \frac{\partial U}{\partial V} \right)_T dV + C_{V} dT
$$

Further, the partial derivative $\left( \frac{\partial U}{\partial V} \right)_T$ denotes the rate of change in internal energy with the change in volume (ie compression or expansion of gas) at constant temperature. This term has dimension of pressure, and it is called internal pressure of system which is denoted by $\pi_{T}$ . This term denotes the influence of intermolecular forces on the internal energy of the system, and for an ideal gas it is equal to zero.

$$
\pi_{T} =\left( \frac{\partial U}{\partial V} \right)_T
$$

Therefore, for any substance we can denote the change in internal energy as

$$
dU = \pi_{T} dV + C_{V} dT
$$

## Change in $U$ at constant pressure

In above discussion we employ $U=U(V,T)$, i.e., $V,T$ are the primary independent state variables, and pressure $P$ is a secondary variable.

$$
p := p(V,T)
$$

Therefore, $p=\text{constant}$  defines a surface in $V,T$ space. Now we are interested in determining the change in $U$ over this surface. Note that on this surface $V,T$ are changing such that $p$ remains constant.

$$
\left( \frac{\partial U}{\partial T} \right)_{p} = \pi_T \left( \frac{\partial V}{\partial T} \right)_{p} + C_{V}
$$

$\left( \frac{\partial V}{\partial T} \right)_{p}$ defines the change in $V$ with temperature at constant pressure, it is used in defining the thermal expansion coefficient of a material $\alpha$ as shown below.

$$
\alpha =\frac{1}{V} \left( \frac{\partial V}{\partial T} \right)_{p}
$$

Therefore, change in $U$ at constant pressure is given by

$$
\left( \frac{\partial U}{\partial T} \right)_{p} = \pi_T \alpha V + C_{V}
$$
