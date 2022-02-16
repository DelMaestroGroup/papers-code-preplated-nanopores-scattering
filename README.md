<!--[![Paper](https://img.shields.io/badge/paper-arXiv%3AXXXX.YYYYY-B31B1B.svg)](https://arxiv.org/abs/XXXX.YYYYY) -->
[![DOI](https://zenodo.org/badge/214220909.svg)](https://zenodo.org/badge/latestdoi/214220909)

# Experimental Realization of One Dimensional Helium
Adrian Del Maestro, Nathan S. Nichols, Timothy R. Prisk, Garfield Warren, Paul E. Sokol

<!-- [arXiv:XXXX.YYYYY](https://arxiv.org/abs/XXXX.YYYYY) -->

### Abstract
The realization of experimental platforms exhibiting one-dimensional (1D) quantum phenomena has been elusive, due to their inherent lack of stability, with a few notable exceptions including spin chains, carbon nanotubes  and ultracold low-density gasses. The difficulty of such systems in exhibiting long range order is integral to their effective description in terms of the Tomonaga-Luttinger liquid theory.  Recently, it has been proposed that that the bosonic superfluid <sup>4</sup>He could realize a 1D quantum system beyond the Luttinger liquid paradigm.  Here we describe an experimental observation of this behavior using nanoengineering by preplating a porous material with a noble gas to enhance dimensional reduction. The resulting excitations of the confined <sup>4</sup>He are qualitatively different than 3D and 2D superfluid helium, and can be analyzed in terms of a mobile impurity in a Luttinger liquid allowing for the characterization of the emergent quantum liquid. The confined helium system offers the possibility of tuning via pressure; from weakly interacting, all the way to the super Tonks-Girardeau gas of strongly interacting hard-core particles. 


### Description
This repository includes links, code, scripts, and data to perform analysis and generate all figures in a paper.

### Requirements
The data in this project was generated via experimental neutron scattering and quantum Monte Carlo simulations.  Processed data is included in the [data](https://github.com/DelMaestroGroup/papers-code-preplated-nanopores-scattering/tree/main/data) directory and the full raw simulation data set is available online at [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6012499.svg)](https://doi.org/10.5281/zenodo.6012499)

1. A minimal environment to execute these notebooks can be installed via

<code>
pip install -r requirements.txt
</code>

2. For plotting a single package `cmaptools` must be installed by hand.  See instructions [here](https://github.com/shaharkadmiel/cmaptools).

3. All quantum Monte Carlo data was generated with our [open source path integral software](https://code.delmaestro.org).

### Support
The creation of these materials was supported in part by the National Science Foundation under Award Nos. [DMR-1809027](http://www.nsf.gov/awardsearch/showAward?AWD_ID=1809027) and [DMR-1808440](http://www.nsf.gov/awardsearch/showAward?AWD_ID=1808440).

[<img width="100px" src="https://www.nsf.gov/images/logos/NSF_4-Color_bitmap_Logo.png">](http://www.nsf.gov/awardsearch/showAward?AWD_ID=1808440)

### Figures

#### Figure 1: Adsorption and structure inside nanopores 
<img src="https://github.com/DelMaestroGroup/papers-code-preplated-nanopores-scattering/blob/71f0fe1747ae45510ad7be02f20f7d895e203596/figures/He_Ar_MCM41_isotherm_radial.png" width="400px">

#### Figure 2: Elastic scattering from <sup>4</sup>He confined inside MCM-41 
<img src="https://github.com/DelMaestroGroup/papers-code-preplated-nanopores-scattering/blob/090a905d98b83e22c98dba1ec171f0d6048c069f/figures/SQ_exp_theory.svg" width="600px">

#### Figure 3: Inelastic scattering of a one-dimensional quantum liquid

<img src="https://github.com/DelMaestroGroup/papers-code-preplated-nanopores-scattering/blob/8b96c66893cf370301410c9863b3400dbb255dfa/figures/SQE_exp_theory_vert.svg" width="400px">

#### Figure 4: Energy and temperature dependence of the inelastic scattering branch 
<img src="https://github.com/DelMaestroGroup/papers-code-preplated-nanopores-scattering/blob/8b96c66893cf370301410c9863b3400dbb255dfa/figures/LL_fit_Qinc_T_dep.svg" width="600px">

#### Figure S1: Elastic scattering from confined helium: raw data 
<img src="https://github.com/DelMaestroGroup/papers-code-preplated-nanopores-scattering/blob/8b96c66893cf370301410c9863b3400dbb255dfa/figures/exp_elastic_scattering.svg" width="400px">

<!-- This figure is released under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) and can be freely copied, redistributed and remixed. -->

