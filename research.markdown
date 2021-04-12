---
layout: page
title: Research
permalink: /research/
---
Stellar streams have been a promising tool to study the structures and accretion history of the Milky Way (MW).The progenitors of stellar streams are dwarf galaxies or globular clusters that fell into the potential well of the MW in the past, having their stars stripped out along their orbits. Interaction of a stream with a low-mass subhalo shows that it creates a discontinuity in the stream’s orbital energy distribution, which will later evolve into a gap or fluctuations in surface density of stars along the stream. These low-mass subhalos, which are otherwise dark, cannot be detected by direct observation. However, their existence is crucial in constraining the temperature of dark matter models. We study simulated streams in cosmological hydrodynamical simulations to model stream-subhalo interactions that will estimate the mass profile of interacting subhalos. We have done the following research in order to work towards that goal.

### **The Galaxy Progenitors of Stellar Streams around MW-mass Galaxies in the FIRE cosmological simulations**

We study and try to characterize progenitors of tidal streams in [FIRE-2 cosmological simulations](https://fire.northwestern.edu).

#### *how to pick out stellar streams*
![classification](/assets/stream_local_vel_dispersion.png)
We identify stream candidates by picking out objects that are bound between 2.7 to 6.5 Gyr ago and are within present day's virial radius of the host. Then, these candidates are classified into 3 catagories: satellite, phase-mixed object and stream. Satellites are ruled out by their compact sizes. We rule out phase-mixed objects by a criterion on the local velocity dispersion shown in the plot as a black dashed line where sample objects that were classified by eye as phase-mixed and stream are plotted in orange and blue, respectively.

#### *key results*
1. Present-day satellite galaxies are good proxies for stellar stream progenitors.
2. The order in which infall, quenching, and tidal disruption occur for progenitors of stellar streams varies with stellar mass.
3. The orientation of the galactic disk affects the orbital distributions of all surviving subhalos (luminious or dark), dwarf galaxies and stream progenitors
4. For streams that form more than 6--8 Gyr ago, the non-adiabatic evolution of the global potential during the early, chaotic phase of the formation of the host galaxy determines how quickly streams become phase-mixed with the host.
5. Orbital-phase-dependent fluctuations complicate using the velocity dispersion to estimate the mass of a stream progenitor.

### **Unwrapping Streams in Realistic MW Potential**
Canonical transformation allows us to be able to represent stellar streams in action-angle coordinates. Stream members are expected to cluster in action space (see Wu et al. including Panithanpaisal for the degree of clustering and how well we can recover streams in this dataset in action space). Moreover, we confirmed that these simulated streams also appear as line overdensities in angle space, eventhough these streams evolve under time-dependent, non-axisymmetric potential. Using this fact, we are able to disentangle streams that have multiple wraps to get exact phase for each star particle.
![angle_space](/assets/one_stream_hough_transform.png)
![unwrap](/assets/one_stream_unwrap_angle.png)
