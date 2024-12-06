# 𑗕 Gibbs energy

## Introduction

Consider a system in thermal equilibrium with its surroundings, that is both system and surrounding are at uniform temperature $T$. Now, during a process, the system exchange energy with the surrounding in the form of heat, which will be denoted by $q,dq$. This process can be reversible or irreversible. According to Clausius inequality,

$$
ds \ge \frac{dq}{T}
$$

**Heating at constant volume**

Now consider a process, in which the system is heated at constant volume, and there is no additional work done on/by the system. Recall that the system and surrounding are in thermal equilibrium.

$$
dq_{V}=dU
$$

Hence,

$$
dS - \frac{dU}{T} \ge 0 \text{ volume=constant, no additional work}
$$

or,

$$
TdS - {dU} \ge 0 \text{ volume=constant, no additional work}
$$

Therefore, if $U$ remains constant during a process and $T>0$, then

$$
dS_{U,V}\ge0
$$

!!! settings ""
    In a system at constant volume and constant internal energy, the entropy increases in a spontaneous change.

**Heating at constant pressure**
Now consider a process, in which energy is transferred as heat at constant pressure. Also, other than the work done during the expansion, not additional work is done by/on the system. Therefore, $dq_{p}=dH$, and

$$
TdS-dH \ge 0 \text{ pressure=constant, no additional work}
$$

Also,

$$
dS_{H,p}\ge0
$$

!!! settings ""
    In a spontaneous process the entropy of the system at constant pressure must increase if its enthalpy remains constant.

Now the above-mentioned cases can be expressed by introducing the concept of the **Helmholz energy (A)** and  the **Gibbs energy (G)**

$$
A=U-TS
$$

$$
G=H-TS
$$

**At constant temperature** the change in A and G is given as follows.

$$
dA=dU-TdS \\
dG=dH-TdS
$$
At constant volume, we have following conditions for a spontaneous process

$$
TdS\ge dU \Rightarrow dA_{T,V} \le 0
$$

At constant pressure, we have following conditions for a spontaneous process

$$
TdS \ge dH \Rightarrow dG_{T,p}\le 0
$$

!!! note ""
    $dG_{T,p} \le 0$, is a vital criteria in the field of chemical thermodynamics.

!!! example ""
     In an **endothermic** reaction, $dH > 0$. Therefore, increase in the entropy will drive the endothermic process. The process will be spontaneous if there is sufficient increase in the entropy so that $T\Delta S > \Delta H$.

!!! example ""
    In an exothermic reaction $\Delta H < 0$. Therefore,  in general, the process is spontaneous. However, in situations where there is significant decrease in the entropy such that $T \Delta{S} < \Delta H$, the process becomes non spontaneous.

## Helmholtz energy and Maximum work

!!! success ""
    Change in Helmholtz energy is equal to the maximum work obtainable from a system at constant temperature.

The proof is given below

$$
dS \ge \frac{\delta q}{T}
$$

$$
dU=\delta q-\delta w_{sys} \Rightarrow dU \le TdS-\delta w_{sys}
$$

$$
-w_{sys} \ge dU-TdS \Rightarrow -w_{sys} \ge dA
$$

or

$$
\delta w_{sys} \le - dA
$$

Therefore, maximum amount of work done by the system is equal to the magnitude of the change in Helmholtz energy functional. Because of this fact, A is also called the work function.

Usually, the decrease in the internal energy of the system ($dU<0$) indicates the possibility that the system will do the work ($w_{sys}>0$). Now consider an isothermal process, so that $\Delta A = \Delta U - T \Delta S$. We have already seen that $w_{sys, max}=-\Delta A = -\Delta U + T \Delta S$. It means that depending upon the sign and value of $T \Delta S$, $w_{sys, max} \ne -\Delta U$.  Now let us say that $T\Delta S < 0$,that is, the system's entropy is decreasing. Then $w_{sys, max}$ will be less than $\Delta U$. Some of the internal energy escapes to the surrounding as heat. This is a natural process, because in this way, the entropy of the surrounding increases to overcome the reduction in entropy in the system. This makes the process spontaneous. Because of this reason, A is also called the *Helmholtz free energy*.

Work done by the system can be visualized as the energy that is transferred to the surrounding through the uniform motion of the atoms and molecules.  $T\Delta S$ can be considered as the energy associated with the random thermal motion of the atoms and molecules. This fraction of energy cannot be used for uniform motion of the surrounding. Therefore, $\Delta A = \Delta U - T \Delta S$ is the amount of energy that can be used in achieving uniform motion of the surrounding.

Case 2: $\Delta U < 0, T\Delta S > 0$.
In this case $w_{sys, max} \ge \Delta U$. How is this possible. Well, this is possible as $T\Delta S>0$, therefore, the surrounding can afford to decrease its entropy (only to an extent so that the change in total entropy is remain positive) by transferring some energy to the system as heat, which, in turn, can be used as the work.

## Gibbs energy and Maximum non-expansion work

At constant temperature and pressure, chemical reactions are spontaneous in the direction of decreasing Gibbs energy. Also, at constant temperature and pressure, the change in Gibbs energy is equal to the maximum additional (non-expansive) work. The proof is given below.

$$
H=U+pV
$$

$$
dU=\delta q + \delta w
$$

$w$ is work done on the system.

$$
dH = dU + d(pV) = \delta q + \delta w + d(pV)
$$

$$
G = H - TS
$$

$$
dG = dH - TdS - SdT
$$

$$
dG = \delta q - TdS + \delta w + d(pV) - SdT
$$

$$
dG = \delta q - TdS + \delta w + pdV + Vdp - SdT
$$

for an isothermal and isobaric processes, we get the following form

$$
dG = \delta q - TdS + \delta w + pdV
$$

$w$ is the net work done on the system, it includes the expansion work $-\int{pdV}$ and additional non-expansion work (such as work done by electricity), $w_{add}$, therefore,

$$
dG = \delta q - TdS -pdV + pdV + \delta w_{add}
$$

therefore,

$$
dG = \delta q - TdS + \delta w_{add}
$$

Now for a reversible processes, $\delta q_{rev} = TdS$, therefore,

$$
dG = \delta w_{rev,add}
$$

Therefore, at constant temperature and pressure, we can calculate the maximum value pf non-expansion work by calculating the total change in the Gibbs energy using $\Delta G = \Delta H - T \Delta S$

## Gibbs energy of formation

- The enthalpy of formation of $H^{+}$ in water is zero
- The absolute entropy of formation of $H^{+}$ in water is zero
- The standard Gibbs energy of formation of $H^{+}$ in water is zero
