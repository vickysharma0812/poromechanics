# Mathematical description of porous media

<!-- markdownlint-disable MD041 MD013 MD033 MD012 -->

In the previous chapter, we discussed the multiscale characteristics of porous media. Specifically, we identified the microscale, also known as the pore-scale, and the macroscale, which we will also refer to as the continuum scale. In this chapter we will learn how to describe the porous medium at these two-scales.

The goal of this chapter is to provide basic mathematical tools which is necessary to build a continuum description of the porous medium. Consider the REV shown in Figure 1.

```{figure}../figures/figure-1.svg
:label: rev
:align: center
Representative elementary volume of a porous medium
```

- $\Omega_{0}$ denotes the domain of REV, its measure is denoted by $V_{0}$
- $\Omega_{0}^{\alpha}$ denotes the domain of $\alpha$ phase, its measure is $V_{0}^{\alpha}$
- $\Omega_{0}^{v}$ denotes the domain of pore spaces, its measure is $V_{0}^{v}$
- $\textbf{x}_{0}$ is the center of REV
- $\mathbf{\xi}$ is the local coordinate of a point within the REV

For a considered porous medium, the size of the REV is selected such that the measured average value is independent of small variation in the size of the REV. In addition, the average value of the measure of  geometric characteristics of the void space should be independent of the size of the REV.

Let $l$ be the characteristic length of the REV, let $d$ be the characteristic length of the void space (viz., pore size, grain size, hydraulic radius of the void space). Then, $l \gt \gt d$, is a necessary condition which ensure that the average value of the measure of geometrical characteristics of the void space at any macroscopic point within a porous media is non-random. Now, let $l_{max}$ be the characteristic length beyond which the spatial distribution of the macroscopic coefficients deviates significantly. Then the REV size should satisfy $l \lt \lt l_{max}$. Finally, $l \lt \lt L$, where L is length scale of porous medium.

```{note}
It is noteworthy that the selected REV should be a valid REV for other void-space geometrical properties, 
such a specific surface area of pore space, hydraulic radius and tortuosity, as these are fundamental properties for determining the macroscopic coefficients.
```

```{note}
Estimating the size of the REV is important to determine the size of the monitoring devices.
```

## Characteristic function

We introduce a characteristic function of the void space $\gamma$. This function is called the indicator function, it is zero outside the porespace and 1 inside the pore space. As a result, it is a discrete function.

$$
\label{eq:char-func-void}
\gamma(\mathbf{x+\xi})=\left\{ \begin{array}{cc}
1 & \mathbf{x}+\xi\in\Omega_{0}^{v}\\
0 & \mathbf{x}+\xi\notin\Omega_{0}^{v}
\end{array}\right\}
$$

It is also possible to define a characteristic function for $\alpha$ phase.

$$
\label{eq:char-func-alpha}
\gamma^{\alpha}(\mathbf{x+\xi})=\left\{ \begin{array}{cc}
1 & \mathbf{x}+\xi\in\Omega_{0}^{\alpha}\\
0 & \mathbf{x}+\xi\notin\Omega_{0}^{\alpha}
\end{array}\right\}
$$

## Volume fraction

The porosity of REV at $\mathbf{x}_{0}$ is given by:

$$
\phi(\mathbf{x}_0) = \frac{V_{0}^{v}}{V_{0}}
$$

The volume fraction of $\alpha$ phase is given by:

$$
\theta^{\alpha}(\mathbf{x}_{0}) = \frac{V_{0}^{\alpha}}{V_{0}}
$$

Note that:

$$
\phi=\sum_{\alpha=1}^{N}\theta^{\alpha}
$$


## Volume Average

Volume averaging facilitates the migration from the microscopic scale to macroscopic scale.

Let $E$ be some extensive physical quantity, such as mass, momentum, energy, etc. Let $e$ be the volume density of the $E$, which is also an intensive physical quantity. Lets $e^{\alpha}$ denotes $e$ in phase tagged as $\alpha$.

The volume average of E is given as the ratio of total amount of E in $\Omega_{0}$ to the volume of the REV.

$$
\left\langle e\right\rangle := \left\langle e\right\rangle (\mathbf{x}) :=\frac{1}{V_{0}}\int_{\Omega_{0}}ed\Omega
$$

It is noteworthy that the $\left\langle e\right\rangle$ is a macroscopic parameter, meaning it is a function of macroscopic coordinate for water-saturated soils, this is approximately the case in undrained $\mathbf{x}$, and independent of microscopic coordinate $\xi$.

Using the above definition of volume average we can define the volume average of $\gamma$.

$$
\left\langle \gamma\right\rangle (\mathbf{x})=\frac{1}{V_{0}}\int_{\Omega_{0}}\gamma(\mathbf{x+\xi})d\Omega=\frac{V_{0}^{v}}{V_{0}}=\phi(\mathbf{x})
$$

The deviation of $\gamma$ from the mean value is denoted by $\mathring{\gamma}$

$$
\mathring{\gamma}(\mathbf{x}+\xi)=\gamma(\mathbf{x}+\xi)-\left\langle \gamma\right\rangle
$$

It can be shown that $\left\langle \mathring{\gamma}\right\rangle =0$.

### Phase volume average

The Phase volume average of $e^{\alpha}$, which is denoted by $<e^{\alpha }>$ is the ratio of the total amount of $E$ present in phase $\alpha$ to the volume of the REV as shown below.

$$
\label{eq:phase-vol-avg}
<e^{\alpha}>=\frac{1}{V_{0}^{}}\int_{\Omega_{0}^{\alpha}}e^{\alpha}d\Omega=\frac{1}{V_{0}^{}}\int_{\Omega_{0}}\gamma^{\alpha}e^{\alpha}d\Omega
$$

### Intrinsic phase volume average

The intrinsic phase volume average is denoted by $<e^{\alpha}>^{\alpha}$, and given by Eq. \ref{eq:int-phase-vol-avg}. It can be noted that it is the ratio of the total amount of $E$ in $\alpha$ phase to the volume of the $\alpha$ phase.

$$
\label{eq:int-phase-vol-avg}
<e^{\alpha}>^{\alpha}=\frac{1}{V_{0}^{\alpha}}\int_{\Omega_{0}^{\alpha}}e^{\alpha}d\Omega=\frac{1}{V_{0}^{\alpha}}\int_{\Omega_{0}}\gamma^{\alpha}e^{\alpha}d\Omega
$$

The relationship between phase volume average and intrinsic phase volume average is given by Eq. \ref{eq:int-vs-phase-vol-avg}.

$$
\label{eq:int-vs-phase-vol-avg}
<e^{\alpha}>= \theta^{\alpha} <e^{\alpha}>^{\alpha}
$$

Intrinsic phase volume average is often used to define the deviation of $e^{\alpha}$ about its average. This deviation is denoted by $\mathring{e}^{\alpha}$, and it is given below.

$$
\mathring{e}^{\alpha}=e^{\alpha}-<e^{\alpha}>^{\alpha}
$$

It can be noted that the phase volume average and intrinsic phase volume average of $\mathring{e}^{\alpha}$ is zero.

$$
\left\langle \mathring{e}^{\alpha}\right\rangle ^{\alpha}=0=\left\langle \mathring{e}^{\alpha}\right\rangle
$$

## Intrinsic mass average

Let $e^{\alpha}$ be the specific density of the extensive quantity $E$, which is the ratio of amount of $E$ present in $\alpha$ phase to the total mass of $\alpha$ phase. Then, the intrinsic mass average of $e^{\alpha}$ is given by:

$$
\widetilde{\left\langle e^{\alpha}\right\rangle }^{\alpha}=\frac{\int_{\Omega_{0}^{\alpha}}e^{\alpha}\rho^{\alpha}d\Omega}{\int_{\Omega_{0}^{\alpha}}\rho^{\alpha}}=\frac{1}{\left\langle \rho^{\alpha}\right\rangle ^{\alpha}}\left\langle \rho^{\alpha}e^{\alpha}\right\rangle ^{\alpha}
$$

where, $\rho^{\alpha}$ is the mass density of the $\alpha$ phase, and $\left\langle \rho^{\alpha}\right\rangle ^{\alpha}$ is the intrinsic mass average of the mass density.

The relationship between intrinsic mass average and intrinsic volume avergae is given by following expression.

$$
\left\langle \rho^{\alpha}\right\rangle ^{\alpha}\widetilde{\left\langle e^{\alpha}\right\rangle }^{\alpha}=\left\langle \rho^{\alpha}e^{\alpha}\right\rangle ^{\alpha}
$$

Also, the relationship between the intrinsic mass average and the phase volume average is given by following expression. Here, note that on the LHS we have phase average of mass density of $\alpha$ phase.

$$
\left\langle \rho^{\alpha}\right\rangle \widetilde{\left\langle e^{\alpha}\right\rangle }^{\alpha}=\left\langle \rho^{\alpha}e^{\alpha}\right\rangle
$$

## Which average value to use?


## Geometrical characterization of REV


## Characteristics of porous media

### Specific surface area

### Heterogeneity

Homogeneous or heterogeneous porous medium are defined with respect to some property which is defined over the domain. If the value of the propery remains constant through the spatial domain then the medium is homogeneous with respect to that property, otherwise it is heterogeneous.

In this way, in heterogeneous porous medium, the property changes with spatial coordinates. Now we can introduce the concept of scale of heterogeneity, which is the length over which the property can change significantly. At the microscopic scale this length is in comparison with the pore/ grain size. Determination of the exact expression of heterogenity at the macroscopic scale is difficult. There are several computation strategy to overcome this issue. Stochastic modeling is one of such strategy.

### Anisotropy

In an anisotropic porous medium, the value of the property of porous medium at a point with in the domain changes with the direction. On the other hand, in an isotropic porous medium, the value of the property does not change with the direction. The geometry of the pore space and the solid matrix are the main factors which determine whether a porous medium will be isotropic or anisotropic.

### Shape of grains


## Fractured porous domain

A fractured porous domain contains a network of fractures and a solid matrix. Many geological formations belong to the class of fractured porous medium. These naturally occuring fracture porous domain are of interest to a wide spectrum of applications, including ground water hydrology, petroleum engineering, and geothermal engineering. The share of fractured rock reservoirs in the world’s hydrocarbon reserves is more than 20%.

![fractured-1](https://image.shutterstock.com/image-photo/large-rock-fractured-cracks-forming-260nw-1536738020.jpg)

![fractured-2](https://image.shutterstock.com/image-photo/tone-texture-closeup-background-600w-77414101.jpg)

![fractured-3](https://image.shutterstock.com/image-photo/fault-lines-colorful-layers-sandstone-600w-321094349.jpg)

Fractures can be formed for several reasons including the excessive local mechanical and thermal stresses. The distance between the opposite faces of a fracture is called its aperture.

The term fractured rock is referred to indicate the solid matrix surrounding the fracture has micro and nano pores. In this way the solid portion does not contribute to the fluid flow.

The term fractured porous media indicates that the surrounding solid is a porous media.

Fractured porous/ rock media can be modelled as four overlapping continuum.

- void space in the entire domain
- the solid matrix distributed in the entire domain
- the fracture distributed in the entire domain
- the void space in the porous block

It is important to note that most of the fluid happens through the fractures and most of the fluid is stored in the solid blocks. However, there can be exchange of mass between the fluid in the fractures and the fluid in the solids.

## Approaches to describe the fractured medium

### ECM: Equivalent continuum model

- In ECM, there is not distinction between the pores of porous blocks and the void space in the fractures
- A single pore space continuum is used to define fractures and voids of porous blocks
- This description is suitable for modeling flow through large domains
- If the domain is smaller than this description is unable to capture the different flow characteristics in the fractures and porous blocks

### Dual porosity model

- In DPM, there are two types of porosity.
- Primary porosity, which is also known as the matrix porosity, defines the interconnected pore space of porous blocks
- Secondary porosity, which is also known as fracture porosity, deals with the void space of fractures and joints
These two continuum overlap with each other
- Flow takes place in these two continuum, there is also an exchange of flow between fracture and surrounding porous blocks
- However, there is no direct flow between two blocks separated by a fracture

### Dual permeability model

- It is an extension of dual-porosity model
- There are two overlapping continua; fracture and block
- This model permits flow through
  - fractures
  - blocks
  - between blocks and fractures
  - between block and blocks
