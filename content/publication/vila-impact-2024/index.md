---
title: 'The Impact of Hardware Variability on Applications Packaged with Docker and
  Guix: a Case Study in Neuroimaging'
authors:
- Gaël Vila
- Emmanuel Medernach
- Inés Gonzalez
- Axel Bonnet
- Yohan Chatelain
- Michaël Sdika
- Tristan Glatard
- Sorina Camarasu-Pop
date: '2024-02-01'
publishDate: '2024-07-05T12:03:55.185225Z'
publication_types:
- manuscript
abstract: "The reproducibility of neuroimaging analyses across computational environments
  has gained significant attention over the last few years. While software containerization
  solutions such as Docker and Singularity have been deployed to mask the effects
  of softwareinduced variability, variations in hardware architectures still impact
  neuroimaging results in an unclear way. We study the effect of hardware variability
  on linear registration results produced by the FSL FLIRT application, a widely-used
  software component in neuroimaging data analyses. Using the Grid'5000 infrastructure,
  we study the effect of nine different CPU models using two software packaging systems
  (Docker and Guix), and we compare the resulting hardware variability to numerical
  variability measured with random rounding. Results show that hardware, software,
  and numerical variability lead to perturbations of similar magnitudes — albeit uncorrelated
  — suggesting that these three types of variability act as independent sources of
  numerical noise with similar magnitude. Therefore, random rounding is as a practical
  solution to measure the effect of numerical noise induced by hardware variability
  in this application. The effect of hardware perturbations on linear registration
  remains moderate, with average translation errors of 0.1 mm (maximum: 0.5 mm) and
  average rotation errors of 0.02 deg (maximum: 0.2 deg). Such variations might impact
  downstream analyses when linear registration is used as initialization step for
  other operations."
tags:
- CPU micro-architecture
- Neuroimaging
- Random rounding
- Reproducibility
- Software packaging
links:
- name: URL
  url: https://hal.science/hal-04480308
---
