![Picture of art installation of networked cables](SUMMA_horrendogram.png)

## Overview


### Introduction

The model API pySUMMA was created through this research as an example model API. pySUMMA wraps the hydrologic model Structure for Unifying Multiple Modeling Alternative (SUMMA) (Clark et al., 2015a). SUMMA is a general hydrologic modeling environment offering the ability to conduct model experiments with controlled and systematic evaluation of multiple model representations of hydrologic processes and scaling behavior. The SUMMA model simulates both the thermodynamics, the storage and flux of energy such as the heat balance of the vegetation canopy, snow, and soil affected by the radiative fluxes, as well as the hydrology, the storage and transmission of water (for example, vertical and lateral transmission of water through vegetation canopy, snow, soil, aquifer and river within a catchment system). The flexible hierarchical spatial structure of SUMMA supports different spatial configurations including the size and shape of model elements with Grouped Response Units (GRUs) (Kouwen et al., 1993) and Hydrologic Response Units (HRUs). In addition, the flexible structure enables researchers to consider the lateral flux of water across the model domain and complex topographical properties like hillslopes and riparian areas. This flexibility within SUMMA enables hydrologists to find solutions for the application of scaling behavior in relation to different physical processes

SUMMA also enables hydrologists to select the appropriate physical process methods and model complexity. This process implements a modular structure that is supported by the conservation equations to calculate each process in a controlled and systematic way. This unified process helps users to concentrate important physical parameterizations with higher complexity and, conversely, to simplify specific processes to minimize uncertainty according to the purpose and characteristics of biophysics and hydrology. Moreover, the structure of SUMMA, which consists of a core (solver) and outer branches, enables the output of a numerical solution from SUMMA so that the user can evaluate the accuracy and efficiency of the model. Therefore, SUMMA supports flexibility to simulate different options of physical processes and numerical solutions.


### Documentation
SUMMA documentation is available [online](http://summa.readthedocs.io/) and remains a work in progress. Additional SUMMA information including publications, test data sets, and sample applications can be found on the [SUMMA web site](http://www.ral.ucar.edu/projects/summa) at NCAR.

pySUMMA documentation is available [online](https://pysumma.readthedocs.io/) and remains a work in progress.

### Credits
SUMMA's initial implementation is described in two papers published in [Water Resources Research](http://onlinelibrary.wiley.com/journal/10.1002/(ISSN)1944-7973). If you use SUMMA, please credit these two publications.

 * Clark, M. P., B. Nijssen, J. D. Lundquist, D. Kavetski, D. E. Rupp, R. A. Woods, J. E. Freer, E. D. Gutmann, A. W. Wood, L. D. Brekke, J. R. Arnold, D. J. Gochis, R. M. Rasmussen, 2015a: A unified approach for process-based hydrologic modeling: Part 1. Modeling concept. _Water Resources Research_, [doi:10.1002/2015WR017198](http://dx.doi.org/10.1002/2015WR017198).<a id="clark_2015a"></a>

 * Clark, M. P., B. Nijssen, J. D. Lundquist, D. Kavetski, D. E. Rupp, R. A. Woods, J. E. Freer, E. D. Gutmann, A. W. Wood, D. J. Gochis, R. M. Rasmussen, D. G. Tarboton, V. Mahat, G. N. Flerchinger, D. G. Marks, 2015b: A unified approach for process-based hydrologic modeling: Part 2. Model implementation and case studies. _Water Resources Research_, [doi:10.1002/2015WR017200](http://dx.doi.org/10.1002/2015WR017200).<a id="clark_2015b"></a>

In addition, an NCAR technical note describes the SUMMA implementation in detail:

 * Clark, M. P., B. Nijssen, J. D. Lundquist, D. Kavetski, D. E. Rupp, R. A. Woods, J. E. Freer, E. D. Gutmann, A. W. Wood, L. D. Brekke, J. R. Arnold, D. J. Gochis, R. M. Rasmussen, D. G. Tarboton, V. Mahat, G. N. Flerchinger, D. G. Marks, 2015c: The structure for unifying multiple modeling alternatives (SUMMA), Version 1.0: Technical Description. _NCAR Technical Note NCAR/TN-514+STR_, 50 pp., [doi:10.5065/D6WQ01TD](http://dx.doi.org/10.5065/D6WQ01TD).<a id="clark_2015c"></a>
 
 pySUMMA is described in a papers published in [Environmental Modelling & Software] (https://www.sciencedirect.com/journal/environmental-modelling-and-software)
  * Choi, Y.-D., Goodall, J.L., Sadler, J.M., Castronova, A.M., Bennett, A., Li, Z., Nijssen, B., Wang, S., Clark, M.P., Ames, D.P., Horsburgh, J.S., Yi, H., Bandaragoda, C., Seul, M., Hooper, R., Tarboton, D.G., 2021. Toward open and reproducible environmental modeling by integrating online data repositories, computational environments, and model Application Programming Interfaces. Environ. Model. Softw. [doi.org/10.1016/j.envsoft.2020.104888](https://doi.org/10.1016/j.envsoft.2020.104888)