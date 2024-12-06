# 𑗕 Enthalpy

While discussing the heat capacity at the constant volume, we have considered an isochoric process. For example, such processes occur in closed and rigid containers. In the isochoric process, the work done by the system is zero. Therefore, it is possible to use all heat energy to increase the system's internal energy.

Now, we will consider another situation where the system's pressure remains constant, for example, a reaction occurring under atmospheric pressure. In this situation, the system may perform some work, that is, $W \ne 0$. To understand this point, consider a closed system containing some gas. The top part of the container is movable and always kept at atmospheric pressure. A heating element is placed inside the container, providing heat to the system. However, the system cannot exchange heat with the surrounding (this assumption was made for simplicity). The gas will expand and perform work as the heat is supplied to the system. In this way, if the gas receives $Q$ amount of energy as heat, and it performs $W$ amount of work, then only $Q-W$ amount of the energy has been taken by the system. $W$ amount of the energy is returned by the system to the surrounding by performing work on the surroundings due to expansion. Mathematically,

$$
\Delta U = Q-W = Q_p - p_{ext}\Delta V
$$

!!! note ""
    Because pressure is constant we have used $W=\int_{V_1}^{V_2}p_{ext}dV=p_{ext}\Delta V$.

!!! note ""
    To indicate that the heat is supplied under isobaric condition we have used the subscript p in $Q_p$.

The above equation can also be written as:

$$
\label{eq:eq-2}
U_2 + p_2 V_2 = U_1 + p_1 V_1 + Q_p
$$

where $p_1=p_2=p_{ext}$.

It seems we can define a state function $H$ in the following manner.

$$
H=U+pV
$$

Then, we have the following equivalent of above Equation:

$$
\Delta H = Q_p
$$

The function $H$ is called the enthalpy of the system. It has following properties:

- $H$ is an extensive quantity
- $H$ is a state function, this is because $U$ is a state function and both $p$ and $V$ are state variables

The differential form of above equation is given by:

$$
dH = \delta Q_p, \quad \Delta H = \int{\delta Q_p}
$$

!!! warning ""
    $Q_p$ is energy provided as heat under isobaric conditions, and its value depend upon the path.

!!! example ""
    At constant pressure the amount of energy supplied to a system  as heat ($Q_p$) is equal to the change in the enthalpy of the system.

## Heat capacity at constant pressure

The energy supplied to a system as heat under isobaric conditions will increase the system's internal energy, which in turn increases the system's temperature. Therefore, like heat capacity at constant volume $C_V$, we can define heat capacity at constant pressure $C_P$ as follows:

$$
C_{P} = \left ( \frac{\partial H}{\partial T} \right )_{p}
$$

!!! note ""
    For solids and liquids, at nominal pressures, the value of internal energy is almost the same as the enthalpy. Therefore, $C_p$ and $C_V$ of solids are almost the same.

For gases, however, $C_p$ and $C_V$ differ significantly because gases have high molar volume than solids and liquids. For ideal gas following relationship holds

$$
H = U + pV = U + nRT
$$

In terms of the molar enthalpy and molar internal energy we get:

$$
\label{eq:eq-11}
h_m = u_m + pv_m = u_m + RT
$$

The molar internal energy ($u_m$) and molar heat capacity at constant volume $c_{V,m}$ of an ideal gas, from kinetic theory of gases are given by:

$$
u_m = \frac{f}{2} RT
$$

$$
c_{V,m} = \frac{f}{2}R
$$

By using these expressions we get:

$$
h_m = \frac{f}{2} RT + RT
$$

The molar heat capacity at constant pressure ($c_{p,m}$) can be obtained as follows.

$$
c_{p,m}=\frac{f}{2}R + R = c_{V,m} + R
$$

Therefore,

$$
c_{p,m} - c_{V,m} = R
$$

Or,

$$
C_p - C_{V} = nR
$$

Note that $C_{p} > C_{V}$: Heat supplied to a closed system at constant volume will cause more temperature increase than the case wherein heat is supplied at constant pressure. This is because, when heat is supplied at constant pressure, the system can return some energy as the work of expansion.

Heat capacity at constant pressure relates the change in enthalpy to a change in temperature:

$$
dH = C_p dT \text{ (at constant pressure) }
$$

If the heat capacity is constant from $T_1$ to $T_2$, then

$$
\Delta H = \int_{T_1}^{T_2} C_{p} dT = C_p \Delta T \text{ (at constant pressure) }
$$

## Modelling heat capacity at constant pressure

To approximate the variation of $C_p$ with $T$ following empirical expression can be employed.

$$
C_{p} = a + bT + c/T^2
$$

- For liquid water:  $a=75.29$ J/mol/K, $b=c=0$
- For CO2: $a=44.22$ , $b=8.79\times 10^{-3}$, $c=-8.62 \times 10^5$

## Standard enthalpy changes

Changes in enthalpy are usually reported for processes which are occurring under standard conditions. The standard state of a substance at a given temperature is its pure form at 1 bar. Therefore, the standard enthalpy change $\Delta H^{\star} $ is the change in enthalpy for a process in which the initial and final substances are in their standard states. Further, $\Delta H^{\star}$ for a process is the difference in enthalpy between the products in their standard states and the reactants in their standard states, all at the same given temperature.

**Standard enthalpy of vaporisation**

$$
H_2 O(l) \rightarrow H_2 O(g), \quad \Delta_{vap} H^{*}(373K) = 40.66 \text{ kJ/mol }
$$

**Standard enthalpy of fusion**

$$
H_2 O(s) \rightarrow H_2 O(l), \quad \Delta_{fus} H^{\star}(273K) = 6.01 \text{ kJ/mol }
$$

|    **Substance**     | **Formula** |             **ΔH(fusion) / kJ mol-1**             | **Melting Point / K** |          **ΔH(vaporization) / kJ mol-1**           | **Boiling Point / K** | **(ΔHv/Tb) / JK-1 mol-1** |
|:--------------------:|:-----------:|:-------------------------------------------------:|:---------------------:|:--------------------------------------------------:|:---------------------:|:-------------------------:|
|         Neon         |     Ne      |                       0.33                        |          24           |                        1.80                        |          27           |            67             |
|        Oxygen        |     O2      |                       0.44                        |          54           |                        6.82                        |         90.2          |            76             |
|       Methane        |     CH4     |                       0.94                        |         90.7          |                        8.18                        |          112          |            73             |
|        Ethane        |    C2H6     |                       2.85                        |         90.0          |                       14.72                        |          184          |            80             |
|       Chlorine       |     Cl2     |                       6.40                        |         172.2         |                       20.41                        |          239          |            85             |
| Carbon tetrachloride |    CCl4     |                       2.67                        |         250.0         |                       30.00                        |          350          |            86             |
|        Water*        |     H2O     | 6.00678 at 0°C, 101kPa 6.354 at 81.6 °C, 2.50 MPa |         273.1         | 40.657 at 100 °C, 45.051 at 0 °C, 46.567 at -33 °C |         373.1         |            109            |
|      *n*-Nonane      |    C9H20    |                       19.3                        |          353          |                        40.5                        |          491          |            82             |
|       Mercury        |     Hg      |                       2.30                        |          234          |                        58.6                        |          630          |            91             |
|        Sodium        |     Na      |                       2.60                        |          371          |                         98                         |         1158          |            85             |
|       Aluminum       |     Al      |                       10.9                        |          933          |                        284                         |         2600          |            109            |
|         Lead         |     Pb      |                       4.77                        |          601          |                        178                         |         2022          |            88             |

Source: <https://chem.libretexts.org/Bookshelves/General_Chemistry/Book%3A_ChemPRIME_(Moore_et_al.)/10%3A_Solids_Liquids_and_Solutions/10.10%3A_Enthalpy_of_Fusion_and_Enthalpy_of_Vaporization>

- The enthalpy of vaporization of a substance is always higher than its enthalpy of fusion. This is because, when a solid melts, the molecules are not separated from each other to nearly the same extent as when a liquid boils.
- There is a close correlation between the enthalpy of vaporization and the boiling point measured on the thermodynamic scale of temperature. The trends in boiling point closely follow the trends in heat of vaporization. If we divide the one by the other, we find that the result is often in the range of 75 to 90 J/mol/K.
- To a first approximation therefore the *enthalpy of vaporization of a liquid is proportional to the thermodynamic temperature at which the liquid boils*. This interesting result is called **Trouton’s rule**.

## Standard Enthalpy of Reaction

Consider a reaction

$$
aA+bB = cC + dD
$$

where, $A, B, C, D$ are the formulae of the reactants and products, and $a,b,c,d$ are the stoichiometric coefficients. Then, the standard enthalpy of reaction is given by:

$$
\Delta_{r} H ^{\star} = cH_{m,C}^{\star}+dH_{m,D}^{\star} - aH_{m,A}^{\star} - bH_{m,B}^{\star}
$$

Here, $H_{m,A}^{\star}$ is the molar standard enthalpy of A.

In this way, we can define the standard enthalpy of combustion.
