# Classic-MUSIC

The **MUSIC (Multiple Signal Classification)** algorithm is a localization technique based on the spatial decomposition of the covariance matrix of the received signals. It performs an exhaustive grid search in the angular domain to identify peaks in the pseudo-spectrum. Classic MUSIC assumes that the number of sources is known a priori; therefore, in this project, we implemented criteria to estimate it.

## 📌 Features
- Antenna Array Design: ULA.
- Scenario: Free space with Line-of-Sight.
- System: MIMO, M-MIMO.
- Steering vector: Taylor approximation.

## 📌 File Description

| File                 | Description                                  |
|----------------------|----------------------------------------------|
| `main.m`            | Main script for the MUSIC algorithm          |
| `signals.m`         | Generates/processes signals                  |
| `responsearray.m`   | Defines the array response matrix            |
| `aic_estimation.m`  | Implements the AIC criterion                |
| `gap_estimation.m`  | Implements the natural separation criterion  |
| `mdl_estimation.m`  | Implements the MDL criterion                |
| `music.m`           | Implementation of the MUSIC algorithm        |
