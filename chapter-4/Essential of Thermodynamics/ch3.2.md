# 𑗕 Entropy

The concept of entropy is vital in physics and chemistry because it provides explaination about why certain processes  are spontaneous, and others. are not. As a result, entropy can tell us the direction of spontaneous change. It will be shown that this direction is determine by the way in which energy and matter are dispersed in the space.  Further, in this chapter, it will be demonstrated that the change in entropy of a system can be calculated from the heat transferred to it reversibly.

## Distribution of mass and energy

Consider a ball, which is bouncing on a ground. Each time the ball collides with the floor, it attains lesser height in the air. Let us consider the ball when it is in the air. Its total energy consists gravitational potential energy and the kinetic energy. The sum of these two energies remains constant before and after the collision (here, we are neglecting the frictional losses due to the atmosphere and surface of the bottom wall). Our observation (that the ball attains lesser height every time it collides with the ground) suggest that the total energy of the ball decreases after the collision.

The first law of thermodynamics states that the total energy of system and surrounding remains constant in a process. Therefore, the decrease in total energy of the ball (system) implies that the energy has been transferred to the ground (the surrounding). The energy received by the ground causes thermal motion of the atoms of the ground. Moreover, this energy in the ground disperse away from the point of contact between the ball and the ground. Therefore, there is no way this dispersed energy is going to concentrated on a point on the ground, and then to the ball. Beside, we know that this dispersed energy is not going to transfer back towards the surface of the ground. As a result, the ball looses all its energy and eventually sits on the ground.

So can we say that the spontaneous process occurs in the direction of change that leads to the dissipation (dispersion) of energy?

Now let us consider the distribution of mass. Take an example of expansion of gas or collapse of a sand column. In these cases, the natural tendency of the system is to distribute the mass in the space.

!!! note "Lord Kelvin's statement"
    No process is possible in which the sole result is the absorption of heat from a reservoir and its complete conversion into work.

In other words, it is not possible to construct a heat engine in which heat drawn from a hot reservoir completely gets transferred to the work.

Another statement of Second law is given by [[Rudolf Clausius]]

!!! success ""
    Heat does not flow spontaneously from a cooler object to a hotter object.

 Let $S$ be the entropy of the system of interest, and $S_{sur}$ be the entropy of the surrounding, then $S_{tot}:=S+S_{sur}$ will be the total entropy of the overall isolated system (the *universe*), then Second law of thermodynamics states that

!!! settings ""
    The entropy of an isolated system increases in the couse of a spontaneous change, that is $\Delta S_{tot}>0$.

Although, we have defined the Second law, we have not defined the measure of Entropy. In what follows definition of Entropy will be provided so that we can measure the change in entropy in a thermodynamic process.

## Thermodynamic Definition of Entropy

We have discussed earlier that heat is related to the random motion of atoms whereas work is related to the uniform motion of atoms. Therefore, we can accept that the change in entropy, that is the extent to which energy is dispersed in a disorderly way, depends on how much energy is transferred as heat, not as work.

The thermodynamic definition of entropy is based on the expression

$$
\label{eq:thermo-def-entropy}
ds=\frac{\delta q_{rev}}{T}
$$

Alternatively, we can write

$$
\label{eq:thermo-def-entropy-change}
\Delta{s}=\int_{s1}^{s2}\frac{\delta q_{rev}}{T}
$$

Here $q_{rev}$ is the energy transfer as heat reversibly to the system at the absolute temperature $T$.

!!! example ""
    To calculate the change in entropy between two states of a system, at first, one needs to identify a reversible path which connectes these two states. Then, one needs to integrate the energy supplied as heat at each stage of the path divided by the temperature at which that heat is transferred. Note that the actual process may be different from the reversible path that we have selected.

**Entropy of the surrounding**: To calculate entropy of the surrounding, we will assume that, during a process, the surrounding remains at constant volume. Therefore, the heat entering the surrounding as heat would be equal to the change in the internal energy of the surrounding. Noting that internal energy is a state function, we can say that the energy entering in the surrounding as heat is independent of the nature of the process (irreversible or reversible) followed by the system. Therefore,

$$
\delta {S}_{sur}=\frac{\delta q_{sur}}{T_{sur}}
$$

!!! note "Heat flows from hotter to cooler objects"
    Why heat flow from hotter to colder object is a sponteneous process? Let $q$ be the amount of heat. Then entropy of hotte body will decrease because heat is leaving it $\Delta {S}_{hot}=-q/T_{hot}$. The entropy of colder object will increase $\Delta {S}_{cool}=-q/T_{cool}$. But, $T_{hot}>T_{cool}$, therefore, the total entropy change is positive. This explains why heat flow from hotter to colder object is a spontenous process.

## Clausius inequality

To derive an expression of Clausius inequality we should make a note of following.

!!! note ""
    Work done by a system during a reversible process is more than the work done during an irereversible system.

!!! note ""
    Internal energy is a state function.

Therefore,

$$
dU = \delta q - \delta W = \delta q_{rev} - \delta W_{rev}
$$

or

$$
\delta q_{rev} - \delta q = \delta W_{rev} - \delta W \ge 0
$$

Then Clausius inequality can be given by,

$$
dS \ge \frac{\delta q}{T}
$$

According to the Clausius inequality, for a system isolated from its surroundings (i.e., $\delta q=0$),

$$
dS \ge 0
$$

!!! warning ""
    In an isolated system the entropy cannot decrease when a spontaneous change occurs.

!!! example ""
    Clausius inequality also implies that spontaneous processes are also necessararily irreversible processes. A reversible process, for which $dS_{tot}=0$, is spontaneous in neither direction: it is at equilibrium.

## Summary

Entropy change of a system

$$
\Delta S = \int \frac{\delta q_{rev}}{T} \ge \int \frac{\delta q}{T}
$$

$$
\Delta S_{sur} = \frac{q_{sur}}{T_{sur}}
$$

$$
\Delta S_{tot} = \Delta S + \Delta S_{sur}
$$
