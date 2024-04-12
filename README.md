# Solar-Reflected-Dark-Matter-Flux
This is the solar reflected dark matter (SRDM) fluxes.
Our earlier work on solar reflected dark matter with heavy mediators : https://arxiv.org/abs/2102.12483
Our simulation code: https://github.com/temken/DaMaSCUS-SUN

This repository contains SRDM fluxes:
for DM with heavy dark photon mediator      : labelled as 'DPC' (dark photon contact interaction)
for DM with ultralight dark photon mediator : labelled as 'DPLM' (dark photon light mediator)

Important details:
(a). We use in-medium effect in the Sun, in both cases: light mediator AND heavy mediator.
(b). Simulation sample size in each simulation is 1000. This number is significantly lower than our paper result (to come). Our paper result (to come) uses a much larger sample size 100000. Reason for a lower sample size here is to limit the computation time to an acceptable level. Lower sample size results in less smooth flux curves and less smooth direct detection constraints. This is a random error, brings slight, random fluctuation of the final result of direct detection constraints.

Results are differential fluxes: dPhi/dv versus v
In each file:
first column  :  v        in  km/sec
second column :  dPhi/dv  in  cm^-2 sec^-1 (km/sec)^-1

In each folder there are many 'Differential_SRDM_Flux' files, they are results at grid points on the plane of DM masses and DM-electron reference cross sections.

For DPC:
File is named as 'Differential_SRDM_Flux_DPC_Row_Column'

Range of cross-section: [1e-40, 1e-31]cm^2, log steps: 45 (including each ends).
Row ranges from 0 to 44 as the index in logspace (Row = 0 for 1e-40 cm^2, Row = 44 for 1e-31 cm^2).

Range of DM mass: [0.001, 10]MeV, log steps: 30 (including each ends).
Column ranges from 0 to 29 as the index in logspace (Column = 0 for 0.001 MeV, Column = 29 for 10 MeV).

For DPLM:
File is named as 'Differential_SRDM_Flux_DPLM_Row_Column'

Range of cross-section: [1e-40, 1e-30]cm^2, log steps: 50 (including each ends).
Row ranges from 0 to 49 as the index in logspace (Row = 0 for 1e-40 cm^2, Row = 49 for 1e-30 cm^2).

Range of DM mass: [0.01, 3]MeV, log steps: 30 (including each ends).
Column ranges from 0 to 29 as the index in logspace (Column = 0 for 0.01 MeV, Column = 29 for 3 MeV).

Readme files are attached in the folders of the result as well.
