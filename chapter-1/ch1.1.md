# Introduction to porous medium

<!-- markdownlint-disable MD041 MD013 MD033 MD012 -->

In our surroudings there exists wide range of porous materials such as soil, rocks, sandstone, limestone, filters, bread, wood, concrete, tissues, bones, paper, among others. Every porous material contains solid particles and void space, which are distributed in the entire domain of porous media. The arrangement of solid and void phase significantly contribute to the overall strength of the porous media. In porous medium, some pores are interconnected or disconnected. The pore space of a porous medium can be occupied by several fluid phases. A fluid phase may contain several chemical species, which can react with other species present in the phase. Besides, these species can react with the solid phase, or the product of the reaction can accumulate on the solid phase. Further, when the fluid phase flows in the pore space, it can transport the extensive quantities (viz., mass, linear momentum, chemical species and energy). The movement, accumulation and transformation of extensive quantities within a porous media is what we refer to as the transport phenomena.

Application of the transport phenomena in porous media covers various field of science and engineering such as soil mechanics, groundwater hydrology, petroleum engineering, drainage and irrigation in agriculture engineering, reactors in chemical engineering, and geothermal engineering. For example, in civil and environmental engineering, it is used to investigate the movement of moisture through concrete walls, flow of water through and under the hydraulic structures. In recent years, the transport phenomena in porous medium has been employed to investigate the effect of heat and vapor transport in soils surrounding the thermoactive structures.

> A porous media is a spatial domain which always contains a solid domain and a void space. Also, it should be possible to find a REV of size such that wherever we place it within the domain, it will always contain both a solid matrix and void space.

## Continuum, phase, species and components

### Continuum

A spatial domain is regarded as a continuum with respect to an extensive property if a vaue of that property can be assigned to every point within that domain.

### Phases

A **Phase** is a portion of spatial domain which is separated from other such portions by a distinct physical boundary. As a result, two phases are immiscible. There can be only one gaseous phase in a system, because all gaseous phases are completely miscible and do not maintain a distinct interface between them.

### Species

- A chemical species is a chemical compound that participates in a chemical reaction that takes place within a phase.
- It is distinguishable by its chemical composition, and by the phase in which it is present.
- The same compound present in different fluid phases is regarded as different species.
- However, the same compound in solution, say in an aqueous liquid and as an absorbate on a solid are considered the same species.

### Components

- Under conditions of chemical equilibrium, we can completely describe the composition of a given phase by the minimum number of independent chemical species.
- The set of these minimum chemical species is called the chemical component or component.

## Continuum approach to porous media

Consider a porous media, in which pores are occupied by a fluid phase. We can state that the fluid phase forms a continuum of fluid particles. These fluid particles carry the extensive properties, and the transport phenonmena in this phase is described by the conservation laws of extensive properties. These laws can be cast in terms of the partial differential equations or integral forms. Each point in the fluid phase represents a scale which is significantly bigger than the atomistic scale of fluid molecules. This continuum scale is called microscopic scale. For fluid phase, it is possible to develop the mathematical equations of conservation of extensive quantities. It may be possible to prescribe the boundary conditions at the interface boundaries (include the fluid-solid boundary). However, it should be noted that the fluid phase has a very complex geometry, which is very difficult to determine. Therefore, even if we know the boundary conditions, it is difficult and impractical, if not impossible, to solve the balance equations at the microscopic level.

> In recent years, modeling of transport phenomena at the microscopic level has been made possible for domain of small sizes. For more details see [Blunt et al. 2013](https://www.sciencedirect.com/science/article/pii/S0309170812000528).

```{figure} https://ars.els-cdn.com/content/image/1-s2.0-S0309170812000528-gr2.jpg
:label: pore-image-carbonates
:width: 500px
:align: center
Pore-space images of three quarry carbonates. Reference: [Blunt et al. 2013](https://www.sciencedirect.com/science/article/pii/S0309170812000528)
```

To overcome the above-mentioned difficulties, upscaling procedures have been developed. The first step in these procedures is the selection of a Representative Elementary Volume (REV). Then averaging of miscroscopic description of the transport phenomena over an REV is performed. As a result, local variation of extensive properties inside the REV is averaged, and the resultant values are assigned to the center of the REV. These averaged properties are called macroscopic quantities and they form a upscaled continuum. The balance laws of these averaged quantities do not require information on the geometry of the microscopic interfaces. However, the upscaled version of the balance laws contains coefficient matrices (viz., porosity, hydraulic radius of void space, specific solid-void area, permeability, tortuosity, fluid saturation, etc.), which can only be determined through experiments. These coefficient matrices, however, depends upon the miscroscopic features (such as, unknown geometry of the solid-void interface, configuration of different fluid phases) and interaction among different phases. In this way, the microscopic details are encoded inside the coefficient matrices, and can be decoded only by conducting experiments.

![Figure REV](https://upload.wikimedia.org/wikipedia/commons/1/16/Schematic_illustration_of_idealized_fiber_arrays_and_their_corresponding_unit_cells.png)

Figure 3: Representative Element Volume. Reference: [Wikipedia](https://en.wikipedia.org/wiki/Representative_elementary_volume)

## Multiphase modeling of porous medium

For the sake of simplicity (but, without the loss of generality), let us consider a biphasic porous medium which is made of solid phase and fluid phase, for example, water-saturated soils. The continuum description of such porous medium can be obtained by using the so called "Theory of Porous Medium" (TPM) which can account for both solid-skeleton deformation and the pore-fluid flow. It is worth noting that at the macroscopic scale the information of pore-geometry and shape and size of individual grains are disregarded, and instead, the aggregates are assumed to be statistically distributed over a representative elementary volume (REV). By applying a homogenization process to the REV, an averaged continuum model is obtained, in which each spatial point is permanently occupied by all constituents in the sense of superimposed and interacting continua.

Biot's theory (BT) is another way to describe the flow of viscous fluids in deformable porous materials at macroscopic scale. This is a phenomenological approach which is derived by generalization of the theory of elasticity to multiphasic aggregates. In porous media dynamic BT introduces a critical frequency measure to distinguish between two types of dynamic responses:
- The first is low-frequency response, in which pore-fluid is described by the Poiseuille-type flow (for example, seismic waves in water-saturated soil). Poiseuille-type flow is characterized by the laminar flow of a viscous fluid through a long cylindrical tube of very small cross-section area. In such flow the pore-pressure gradient and the volume flux are linearly related to each other. For tube diameters or flow velocities above certain thresholds (e.g., due to a high frequency excitation and low-viscous fluid), the fluid flow is considered turbulent and the Poiseuille’s law is not valid.
- The second is high-frequency response, in which pore-fluid flow deviates from being laminar and there is strong fluid-solid inertia coupling at the micro-level.
- In this way, for the extremely high-frequency excitation, wavelengths can be of the same order as the micro-pore diameters, which makes the validity of the macroscopic modeling questionable.


## References

- deBoer, R.: Theory of Porous Media. Springer-Verlag, Berlin 2000, https://doi.org/10.1007/978-3-642-59637-7
- Trends in Continuum Mechanics of Porous Media, https://link-springer-com.kyoto-u.idm.oclc.org/book/10.1007/1-4020-3144-0
- de Boer, R., Ehlers, W. The development of the concept of effective stresses. _Acta Mechanica_ **83**, 77–92 (1990). https://doi-org.kyoto-u.idm.oclc.org/10.1007/BF01174734
- 
