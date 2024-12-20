## Coefficient Values with RB<sub>DL</sub> as input
| Technology   |   RB<sub>DL</sub> |   Intercept |
|:-------------|------------------:|------------:|
| LTE800       |         0.0315528 |   0.164314  |
| LTE1800      |         0.0374293 |   0.11344   |
| LTE2100      |         0.0370305 |   0.0804473 |
| LTE700       |         0.0329667 |   0.136152  |
| LTE2600      |         0.0379063 |   0.0846887 |
| NR3700       |         0.0174514 |   0.172008  |


## Coefficient Values with RB<sub>UL</sub> as input
| Technology   |   RB<sub>UL</sub> |   Intercept |
|:-------------|------------------:|------------:|
| LTE800       |         0.0270632 |   0.164314  |
| LTE1800      |         0.0357895 |   0.11344   |
| LTE2100      |         0.0325234 |   0.0804473 |
| LTE700       |         0.0375575 |   0.136152  |
| LTE2600      |         0.0357681 |   0.0846887 |
| NR3700       |         0.0188975 |   0.172008  |


## Coefficient Values with V<sub>DL</sub> as input
| Technology   |   V<sub>DL</sub> |   Intercept |
|:-------------|-----------------:|------------:|
| LTE800       |        0.0329357 |   0.164314  |
| LTE1800      |        0.033867  |   0.11344   |
| LTE2100      |        0.0353307 |   0.0804473 |
| LTE700       |        0.0343582 |   0.136152  |
| LTE2600      |        0.0346719 |   0.0846887 |
| NR3700       |        0.0115447 |   0.172008  |


## Coefficient Values with V<sub>UL</sub> as input
| Technology   |   V<sub>UL</sub> |   Intercept |
|:-------------|-----------------:|------------:|
| LTE800       |        0.0327935 |   0.164314  |
| LTE1800      |        0.0308295 |   0.11344   |
| LTE2100      |        0.0319429 |   0.0804473 |
| LTE700       |        0.0249523 |   0.136152  |
| LTE2600      |        0.0312541 |   0.0846887 |
| NR3700       |        0.0126419 |   0.172008  |


## Coefficient Values with RB<sub>DL</sub>, RB<sub>UL</sub>, V<sub>DL</sub>, V<sub>UL</sub> as input
| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |   Intercept |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|------------:|
| LTE800       |        0.00677064 |        0          |       0.0139811  |       0.0168893  |   0.164314  |
| LTE1800      |        0.0250943  |        0.0146262  |       0          |       0          |   0.11344   |
| LTE2100      |        0.0288169  |        0          |       0.00264328 |       0.00732861 |   0.0804473 |
| LTE700       |        0          |        0.0264101  |       0.0163318  |       0          |   0.136152  |
| LTE2600      |        0.0300514  |        0.00873037 |       0          |       0          |   0.0846887 |
| NR3700       |        0.00649684 |        0.0137042  |       0          |       0          |   0.172008  |


## Coefficient Values with RB<sub>DL</sub>, RB<sub>UL</sub>, V<sub>DL</sub>, V<sub>UL</sub>, A, P<sub>Max</sub> as input
| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |          A |   P<sub>Max</sub> |   Intercept |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|-----------:|------------------:|------------:|
| LTE800       |        0.0153616  |        0.0244331  |       0.0130261  |       0          | 0.0449087  |        0.00845511 |   0.164314  |
| LTE1800      |        0.0254852  |        0.0096302  |       0.00284617 |       0          | 0.00544393 |        0.012962   |   0.11344   |
| LTE2100      |        0.0272363  |        0          |       0.00480793 |       0.00617138 | 0.00234302 |        0.0113268  |   0.0804473 |
| LTE700       |        0.00391373 |        0.00271275 |       0.0245309  |       0          | 0          |        0.0448367  |   0.136152  |
| LTE2600      |        0.0299358  |        0.0091082  |       0          |       0          | 0          |        0.00472072 |   0.0846887 |
| NR3700       |        0.00649684 |        0.0137042  |       0          |       0          | 0          |        0          |   0.172008  |


## Mean of the different features
| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |       A |   P<sub>Max</sub> |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|--------:|------------------:|
| LTE800       |          38.6305  |          27.4647  |      2.11826e+06 |           565730 | 1.21121 |           16.7105 |
| LTE1800      |          31.1909  |          17.2263  |      4.62459e+06 |           865810 | 1.27206 |           23.9143 |
| LTE2100      |          26.6114  |          16.4242  |      3.51952e+06 |           611446 | 1.28583 |           23.0545 |
| LTE700       |          28.538   |          22.0759  |      1.56634e+06 |           428744 | 1.14895 |           23.966  |
| LTE2600      |          26.0579  |          14.9612  |      4.54872e+06 |           579259 | 1.22376 |           20.6613 |
| NR3700       |           2.02952 |           4.26484 | 858866           |           196490 | 1       |           33.8844 |


## Standard deviation of the different features
| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |           A |   P<sub>Max</sub> |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|------------:|------------------:|
| LTE800       |          26.7515  |          14.2199  |      1.70298e+06 |           442460 | 0.0733745   |           5.42811 |
| LTE1800      |          26.927   |          11.0668  |      4.57807e+06 |           801434 | 0.0962163   |           7.84596 |
| LTE2100      |          26.1144  |          10.7448  |      3.91658e+06 |           679919 | 0.11093     |           6.25684 |
| LTE700       |          19.1205  |           9.37748 |      1.09489e+06 |           355126 | 2.22045e-16 |           4.09812 |
| LTE2600      |          29.5047  |          10.05    |      6.31457e+06 |           813962 | 0.0845249   |           3.37693 |
| NR3700       |           1.44035 |           2.22183 |      1.12992e+06 |           221793 | 0           |           0       |

## Unit of measurement of the different features
RB<sub>DL</sub>: % <br>
RB<sub>UL</sub>: % <br>
V<sub>DL</sub> : kbyte <br>
V<sub>UL</sub> : kbyte <br>
A: linear power ratio $10^{\frac{dB}{10}}$ <br>
P<sub>Max</sub>: dBm <br>
Power Demand: kW
