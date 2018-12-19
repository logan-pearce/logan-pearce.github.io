---
layout: page
title: "Research"
bigimg:
  - "../img/img4_deathvalley.jpg" : "The Road from Panamint Springs, Death Valley NP"
  - "../img/img2_bigbend.jpg" : "Big Bend Big Sky, Big Bend NP"
  - "../img/img3_elcapitan.jpg" : "El Capitan, Guadalupe NP"
  - "../img/img1_vla.jpg" : "Very Large Array"
---
{% include mathjs %}

## Orbital Motion of Wide Planetary-Mass Companions to Low-Mass Stars
### Advisor: Adam Kraus
### Univ of Texas at Austin, 2017-2019

Planetary mass companions are large mass planets (on the order of 15 Mjup)  on wide orbits (100's of AU) from their host stars.  They exist in a parameter such that it is unclear if they represent the high end of planetary masses, the low end of brown dwarf masses, or if there is even is a dividing line in the substellar mass function at all.  There are a handful of these wide orbit companions that have been discovered through direct imaging surveys of young low mass stars.  Their wide orbits and young ages make them ideal for testing planet and star formation models, because they are young enough and wide enough that they can be studied relatively easily through high contrast imaging.

My work has focused on an orbital analysis of one particular wide orbit planetary mass companion, GSC 6214-210 b.  It is a 15 Mjup companion to a K5 dwarf star in the Upper Scorpious star-forming region.  GSC 6214-210 b has been observed with the NIRC2 camera on the Keck II telescope for 10 years, enough to measure the relative astrometry and test for orbital motion.  I developed my own PSF-fitting relative astrometry algorithm to observe orbital motion, then fit orbital parameters to my astrometry using a custom implementation of the Orbits for the Impatient algorithm (Blunt et. al. 2017).

| [![GSC 6214-210](GSC6214_2017_color1.eps){: class="image-100" }](GSC6214_2017_color1.eps) | [![Orbits](GSC6214_acceptedorbits_black.pdf){: class="image-100" }](GSC6214_acceptedorbits_black.pdf) |
|:---:|:---:|
| <sub><sup> NIRC2 image of GSC 6214-210, with its companion seen just to the south and east.  Inset: Relative motion of the companion found in this study.  Error bars to the left represent median error in individual image posteriors </sup></sub>| <sub><sup> 100 randomly selected orbits from the posterior of accepted orbital parameters from the OFTI algorithm. </sup></sub> |

We found that orbital element posteriors for GSC 6214-210 b, along with complementary lines of evidence,  make formation at close orbital radius, consistent with the core accretion model of planet formation, and subsequent dynamical scattering to its current wide radius is highly unlikely.  Star formation pathways such as gravitational instability are more likely to explain this object's current orbit.  Other orbital studies of other wide planetary-mass companions have made similar conclusions (see Bryan et. al. 2016).  This could indicate that dynamical scattering it not a dominant formation pathway for these objects.  This work can easily be repeated for other directly imaged wide companion systems.

Publication expected winter of 2018

<center>[GitHub repo for this project](https://github.com/logan-pearce)</center>

I am also a part of the orbitize! project -- an open-source object-oriented python package for fitting orbital parameters to directly-imaged planet astrometry.  Orbitize! allows users to select from multiple parameter fitting methodologies, including OFTI, that are statistically robust, and outputs fits and plots of the results.  Orbitize! version 1 is expected in September 2018.

<center>[Orbitize! Docs](https://orbitize.readthedocs.io/en/latest/)</center>

***




