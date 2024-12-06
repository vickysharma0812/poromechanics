# Thermodynamics of Porous Media

<!-- markdownlint-disable MD041 MD013 MD033 MD012 -->

In this chapter we will learn about some important components of thermodynamics, and how thermodynamics equation looks for porous media. At this point, we are already aware of phases, species, and components. We will denote phases by greek letters $\alpha, \beta, \gamma$, and we will denote the species by lower case alphabets $a,b,c,\cdots$. So if $e$ is some intensive property, then $e$ of $i$th species in $\alpha$ phase will be denoted by $e^{i,\alpha}$.  In this way we can define following qualities.

| Description                                      | Symbol              |
| ------------------------------------------------ | ------------------- |
| Number of moles of $i$ species in $\alpha$ phase | $n^{i,\alpha}$      |
| Mass of $i$ species in $\alpha$ phase            | $m^{i,\alpha}$      |
| Mass fraction of $i$ species in $\alpha$ phase   | $\omega^{i,\alpha}$ |
| Mole fraction of $i$ species in $\alpha$ phase   | $X^{i,\alpha}$      |
|                                                  |                     |

Moles of $i$​ species inside $\alpha$​​ phase are given by following expression:

$$
n^{i,\alpha}:= \frac{m^{i,\alpha}}{M^{i}}
$$

where, $M^{i}$ is the molecular weight of $i$ species.

Let us denote the total mass of the phase by $m^{\alpha}$, which is given below.

$$
m^{\alpha} := \sum_{i=1}^{N}{m^{i,\alpha}}
$$

Also, we can define the total moles of $\alpha$ phase, which is denoted by $n^{\alpha}$, by following expression

$$
n^{\alpha} := \sum_{i=1}^{N}{n^{i,\alpha}}
$$

Now, it is straight forward to define the mass and mole fraction and mass fraction of $i$ species in $\alpha$ phase.

$$
\omega^{i,\alpha} = \frac{m^{i,\alpha}}{m^{\alpha}}
$$

$$
X^{i,\alpha} = \frac{n^{i,\alpha}}{n^{\alpha}}
$$


## Thermodynamic Equilibrium

Consider a fluid phase $\alpha$ inside the pore-space of porous media. We use the continuum description for this phase, which means that we are averaging (or looking at the average behaviour) of molecular behaviour of $\alpha$ phase. This averaging we can refer to as the averaging at the microscopic REV scale ($\mu$REV). Now, we upscale our observation area, and start looking at things which is significantly larger than the pore scale. We introduce what we called as the macroscopic REV. The continuum behaviour of $\alpha$ phase is averaged over the macroscopic REV to obtain the governing laws at the macroscopic level.

Thermodynamic equilibrium implies mechanical, chemical, thermal equilibrium. Thermal equilibrium requires uniformity of the temperature, and chemical equilibrium requires that all chemical potential should be equal (or, in balance).

*Local thermodynamic equilibrium signifies that when we are averaging the molecular behaviour of $\alpha$ phase with in $\mu$ REV, while isolating the REV from its surrounding, equilibrium among all the chemical species within that $\mu$ REV prevails.*

In this way, local thermodynamic equilibrium implies that at microscopic level mechanical, thermal, and chemical equilibria prevails. Further, local equilibrium ensures that the thermodynamic variables such as, thermodynamic pressure, temperature, density, entropy, internal energy, chemical potential, among others,  can be defined uniquely at every point in the phase continuum.

Now the main question is why local equilibrium is a valid assumption for flow through porous media? To understand this, note that we are interested in macroscopic phenomena such as flow of fluid inside the pore space. This phenomenon has its own time scale, let us denote it by $t_1$. What this time scale tells is that we have to wait for at least $t_1$ sec to see any measurable changes at the macroscopic scale. Now bring our attention to molecular level, where molecules of the fluid are colliding with each other. The average distance traveled by the a molecule before colliding with some other molecule is called **mean free path** of the molecule. Note that the size of $\mu$REV is significantly large so that we have large number of molecules inside that REV. In other words, size of the REV is much larger than the mean free path. Now consider the local effect at any point in $\mu$REV. The time scale at molecular level, which is approximately the ratio of mean free path and the RMS speed of the molecule is much smaller than $t_1$. This implies that within time $t_1$ molecules will undergo several collision, and we will observed an average value of physical quantities. In this way, it is safe to assume local thermal equilibrium at the microscopic level with in $\mu$ REV.

Under the condition of microscopic thermodynamic equilibrium, we obtain a single value of chemical potential for every chemical species present in the REV, and a single temperature within the REV. Besides, under such local equilibrium inside a phase domain in a REV, there exists no net transport of mass of chemical species, of energy, and of linear momentum within that phase domain.

In the absence of gravity and surface forces, the pressure within any phase must be uniform, and at the interface between two phases Laplace formula describe the condition of jump in pressure across the interface. Under these conditions, the value of pressure at the macroscopic scale will be the same as its microscopic counterpart.

## WORK

In mechanics work, $W$​, done by a force $\mathbf{F}$ on a body $\mathfrak{B}$​ is defined as the dot product between the force and the displacement at the point of application of the force.

$$
dW:= \mathbf{F} \cdot d\mathbf{u}
$$

From above definition of work, it should be noted that, for the force to perform work, the point of application should move in the line of action of the force. The work done by a force is always positive when the displacement of the point of action is in the direction of the force, and it is negative when the displacement is in opposite direction of the force.

It is important to note that, in the case of a rigid body, the work done by a force actually displaces the centre of the mass of the body. In this way, the boundary of the body simply performs rigid body motion.

In the case of a deformable body, the force can also deform the body such that its volume changes. Whenever, the volume of a deformable body changes its boundary must move to accommodate the new volume. It is possible that a deformable body undergoes rigid body motion, in which case the boundary also performs rigid body motion.

![Deformation of different bodies](https://dm2302files.storage.live.com/y4moFC67kmKtL5br8VIKU7xq9_pt29vYl8otDTAzk94EbQVtJGCB7de7iqXJZggz_9z4EzLz-0tdMcbtIEjWXYd8p188wlahDQJXUzrl0UxMachEbvrtaDozfWDMMkfUs9qsWB8lmFgDPx8zK5XdQKwH8isRfHZrc18ulQ0DxObzycxCGUkCTiVT-toqqh7fbH3?width=660&height=660&cropmode=none)

Figure 1: Representation of  deformation of different bodies

Note that

Usually, the force on a body is exerted by its surrounding. Therefore, we can say that the surrounding is working on the system. If the system is working on the surrounding then then the work done by the system will be considered as positive. The positive work done by the system means, the system is giving some of its energy to its surroundings. The work done by the surrounding on the system will be taken as negative. In this way, the negative work done on the system implies that the system is taking energy from its surrounding. The most important thing to note is that work done on a system or by a system represent some sort of energy exchange between the system and its surrounding.

Let $\mathbf{F}$​  be the force exerted by the surrounding on the system or the body at some point on the surface of the body. Let us denote the displacement of this point by $d\mathbf{u}$​. Then, the work done by the force on the body is given by $\mathbf{F}\cdot d\mathbf{u}$​​, however, the work done by the surrounding on the system will be negative of this work done, and it will given by following equation.

$$
W_{surr \rightarrow sys}:=-\int \mathbf{F} \cdot d\mathbf{u}
$$

If you are wondering why the negative sign, then let me explain. The work done by the force is always positive when the displacement of the point of application is in the direction of the application of the force. In this case, the force provides energy to the body. But we know that when the energy is supplied to the system then we use negative sign to represent it. This is why we have used negative sign in above equation. In this way, when the work done by the force is negative, means the displacement of the point of application is in opposite direction of direction of force, the surrounding will be extracting energy from the system, and we present it extraction of energy from the system by denoting work as positive.

The amount of work done by a force on a body depends upon the path taken (trajectory) during the motion.


## First law of thermodynamics

Now consider a system (or a body), the work done by the system on its surrounding will be denoted by $W$​, and the heat entering the system will be denoted by $Q$​. Then, first law of thermodynamics state that $Q-W$​, which is the sum of the energy entering the system as heat and the work done on the system, only depends upon the state of the system (i.e., $Q-W$​ is independent of the path).  The change in the state of the system results in the change in the internal energy, which we will denote by $\Delta U$​. Mathematically, the first law of thermodynamics state that

$$
\Delta U = Q-W
$$

or

$$
dU = dQ - dW
$$

In the case of an adiabatic process, $Q=0$​​, that is, the system is not allowed to exchange heat with its surrounding. The work done during an adiabatic process is called *adiabatic work*, which is independent of the path taken by the process to change the state of the system. In other words, the adiabatic work only depends upon the state of the system. In such case, the first law of thermodynamics state that

$$
\Delta U = -W_{adia}
$$

In this way, the first law of thermodynamics defines energy of a system. Internal energy of the system is just a form of energy like the potential energy and kinetic energy. We know that potential energy can be converted into kinetic energy , and  vice-versa. Similarly, internal energy can be converted to PE or KE. Like PE, internal energy can be stored in the system.  However, note that the work and heat cannot be stored or conserved independently because they depend on the process (i.e., on the path).

What this video which explains the first law of thermodynamics.

<iframe width="560" height="315" src="https://www.youtube.com/embed/1OFlW8OXN64" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Internal energy

The concept of internal energy is very important and interesting. Consider a close system or body $\mathfrak{B}$. By close system we mean that the mass cannot be exchanged between the body and its surroundings. Also, you can imagine that you cannot see what is going inside the body (i.e., the body is not transparent). Now the question is how do we measure the internal energy of the system? This is where the first law of thermodynamics comes into picture.

The first law of thermodynamics state that we can provide energy to a close system by means of performing work on it. Remember that positive work done by the surrounding implies energy is being supplied to the body. We can also provide energy to the body by putting it in the contact with another object which has  higher temperature. In this way, heat will transfer from high temperature to the lower temperature regime. We can also extract the heat from the body by putting it in contact with an object of lower temperature. These process are explained in Figure 1. In this way, first law of thermodynamics state that the change in internal energy of the system will be $Q-W$,  and there is no need to go inside the  body and see it.  In other words, we can change the state of the system  either by mechanically working on it (through its boundary) and by providing heat to it (again, through its boundary). Then, $\Delta U$ is a measure of the change in the state of the system.

![figure](https://dm2302files.storage.live.com/y4mtrEa8QsLJtjyOyjUzhxfCXjyYByf16cXlFQzMdlv_jdB9wpBFgPyfD3magXBCfQ26Ttm7I1NeyXtb8E3XSIv86dII5i91O9Rl0m9R_DcQQQxa0LFmz-0G0CRkOhFYYPV99UETpw5L6Z7KSvD0kqYMfRE5ASnaaOMUgTtNWu02KjarOKp96CKo4zRr9SxCWXj?width=660&height=660&cropmode=none)


Professor Atkins in the following video lecture provides a beautiful metaphor for the internal energy. You can think internal energy as the currency, and the body as the bank, also you can consider work as USD and heat as JPY. Then you can withdraw or deposit currency in the bank through USD or JPY.

<iframe width="560" height="315" src="https://www.youtube.com/embed/kSuXS_zqRec" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## Second law of thermodynamics

In the first law of thermodynamics we have seen that the energy of an isolated system is conserved. Now we want to understand the reason why certain processes in nature occur in a certain ways. For example, heat transfers from high temperature to low temperature regime. Gases always try to expand. In technical terms, we are interested in spontaneous processes. What phenomenon drives them?

## Web references

<iframe width="560" height="315" src="https://www.youtube.com/embed/mGDJO2M7RBg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/mg0hueOyoAw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
