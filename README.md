# Planck-Curve-Sun-Earth

A LabView VI to illustrate, side-by-side, the Planck curves of a black-body Sun (at Earth's distance from Sun) and a black-body Earth.

## Description

The VI "Planck-Curve-Sun-Earth.vi" is the teaching application where instructors / students can change the black-body temperature of the Sun, the Temperature of Earth and explore how the spectra (Planck), the total emittance (Stefan-Boltzmann) and the maximum emittance (Wien's displacement law) of the two systems change, and bring them in equilibrium. 

Note that the Sun's Plack curve is scaled so it represents the curve at Earth's mean distance from Sun per average surface area of Earth (distributed over 4πR^2, while interception area is only πR^2).

The VI "Planck.vi" calculates for a given wavelength (in µm) and a given surface temperature (in K) the black-body spectral emittance (in W m-2 µm-1).
