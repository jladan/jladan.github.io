---
title: Experiments on the formation of icicle ripples
description: This my dissertation for a Ph.D. Physics at the University of Toronto
date: "2023-06-01T19:47:09+02:00"
jobDate: 2015-2023
work: [physics, ice, "pattern formation"]
techs: [Python, LabView, HDF5, skimage]
thumbnail: thesis/truncated-cylinder.png
projectUrl: https://hdl.handle.net/1807/127928
---

<!-- TODO new thumbnail image, which captures more of the research
    - water distribution
    - brine inclusions
    - crystal structure
    - plot of morphology
    -->

My research focus for my Physics Ph.D. was on the mechanisms of wet ice growth
using icicles as a case study. When icicles grow from water with a minute
concentration of impurities, ripples will form on the surface, and before my
research the causal mechanism was unknown.
The physics of water and ice is surprisingly complex for something that is so
ubiquitous, and produces many challenges in studying ice formation.

During this project I,
- created a machine to grow icicles in a controlled enviroment, and capture
  time-lapse photography of their growth;
- created and analyzed an analytical model of icicle ripple formation based on
  previous models that did not consider impurities;
- collected over 20 TB of data (mostly images) of over 120 lab-grown icicles
  with various concentrations and types of impurities;
- designed and automated a procedure to extract and measure the morphology of
  icicles from the images; and
- discovered how the concentration of impurities affects the distribution of
  water over the surface, using novel techiques.

## Thesis Abstract

Icicles are a common sight during winter, hanging from rooftops
and other structures from which water drips.
The long slender shape of an icicle develops through a highly
non-equilibrium process in which water flows down its surface,
partially freezing along the way. This is an example of ``wet ice growth.''

Many icicles exhibit rippled pattern along their length with a
near universal 9~mm wavelength. 
While measurements of icicle ripples date back to at least 1933, the
mechanism through which they form has eluded physicists.
The existence and amplitude of ripples was previously shown to depend on the
presence of impurities in the source water, 
but no existing model for icicle ripples includes impurities.
The problem of how icicles form in the presence of impurities
is the focus of this thesis.

A pre-existing model for the rippling instability was extended to include
physical effects of impurities. A linear stability analysis performed on
this model showed that it did not predict ripples. The stability of the
model is not sensitive to concentration, so 
such a model will likely never agree with experiment.

A set of 120 icicles were grown using various chemical species as the
impurity. The changes in morphology from impurities were only affected by
the molar concentration, showing that icicle ripples only depend on the
number of dissolved molecules.

One of the impurities used was a dye that only fluoresces when
dissolved in water. The liquid flowing down the surface of icicles was
observed directly using this dye. Contrary to previous models, we find that
the ice is incompletely and intermittently wetted by the liquid phase, 
and the concentration of impurities modifies the wetting properties of ice.

The location of impurities trapped inside of icicles was also observed. All
of the impurities were found inside small spherical inclusions.
The inclusions are organized into chevron patterns aligned with the peaks of
ripples, with a layered substructure, suggestive of cyclic wetting and
freezing.  

These observations must inform any successful model of an impurity-driven
rippling instability. Our results have general implications for the
evolution of many gravity-driven wet ice growth processes.
