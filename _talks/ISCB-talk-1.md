---
title: "Talk 1 on "A unifying framework for flexible excess hazard modeling with applications in cancer epidemiology""
collection: talks
type: "Talk"
permalink: /talks/ISCB-talk-1
venue: "42nd Annual Conference of the International Society for Clinical Biostatisticians (ISCB)"
date: 2021-07-21
location: "Lyon, France"
---
I presented a joint work done with Prof. Giampiero Marra (UCL), Dr. Manuela Quaresma (LSHTM), Dr. Rosalba Radice (Business School, City, University of London) and Dr. Francisco Javier Rubio (UCL) entitled "A unifying framework for flexible excess hazard modeling with applications in cancer epidemiology". A brief abstract follows.

Excess hazard modeling has become the preferred tool in population-based cancer survival research as it overcomes drawbacks of both the traditional overall survival setting as well as of the cause-specific setting. This is achieved by assuming an additive decomposition of the overall hazard into two components: the excess hazard, e.g. due to the cancer of interest, and the population hazard due to all other causes of death.

Despite its widespread use, a unifying framework supporting virtually any application fully implemented in a ready to use package is not, to the best of our knowledge, available in the literature. We thus propose a solution which allows for excess hazard modeling in addition to traditional overall survival analysis and which uses a link-based additive model supporting many types of covariate effects, including time-dependent and spatial ones. Estimation is achieved using a carefully structured efficient and stable penalized likelihood algorithm.

Two practical applications in breast, colon and lung cancer epidemiology are presented and highlight the benefits of using this flexible framework. For instance, additional insight on socio-demographic inequality in cancer survival is found by including spatial effects. The proposed approach is readily available in the R package GJRM.
