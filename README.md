# Planck-Curve-Sun-Earth

A LabView VI to illustrate, side-by-side, the Planck curves of a black-body Sun (at Earth's distance from Sun) and a black-body Earth.

![](assets/img/example_front_panel.png)

## Description

The VI "Planck-Curve-Sun-Earth.vi" is the teaching application where instructors / students can change the black-body temperatures of the Sun and Earth and explore how the spectra (Planck curves), the total emittance (Stefan-Boltzmann) and the maximum emittance (Wien's displacement law) of the two systems change, and bring them in equilibrium. 

Note that the Sun's Plack curve is scaled by a factor R_sun^2 / (4 D^2), so it represents the curve at Earth's mean distance from Sun per average surface area of Earth. D is the mean distance Sun-Earth, R_sun is the radius of the Sun, and the factor 4 is introduced to distribute the solar irradiance over 4πR_Earth^2, the whole surface area of the planet -- while the interception area for solar radiation is πR_Earth^2. R_Earth being the radius of Earth.

The VI "Planck.vi" calculates for a given wavelength (in µm) and a given surface temperature (in K) the black-body spectral emittance (in W m-2 µm-1).
