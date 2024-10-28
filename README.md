# Power-Consumption-Model
# M4T Model

The following tables present the coefficients of the M4T models, organized by input feature. Each table corresponds to a particular model variation, with columns listing the input features included in that variation. The values in each cell represent the estimated coefficient for the associated feature.

## Coefficient Values with RB<sub>DL</sub> as input

| Technology   |   RB<sub>DL</sub> |   Intercept |
|:-------------|------------------:|------------:|
| LTE 800       |        0.00117947 |   0.118751  |
| LTE 1800      |        0.00139003 |   0.070084  |
| LTE 2100      |        0.00141801 |   0.0427121 |
| LTE 700       |        0.00172415 |   0.0869485 |
| LTE 2600      |        0.00128475 |   0.0512108 |
| NR 3700       |        0.0121161  |   0.147418  |


## Coefficient Values with RB<sub>UL</sub> as input
| Technology   |   RB<sub>UL</sub> |   Intercept |
|:-------------|------------------:|------------:|
| LTE 800       |        0.0019032  |   0.112044  |
| LTE 1800      |        0.00323397 |   0.0577311 |
| LTE 2100      |        0.0030269  |   0.0307328 |
| LTE 700       |        0.00400507 |   0.0477366 |
| LTE 2600      |        0.00355902 |   0.0314413 |
| NR 3700       |        0.00850539 |   0.135734  |


| Technology   |   V<sub>DL</sub> |   Intercept |
|:-------------|-----------------:|------------:|
| LTE 800       |      1.934 &middot; 10 <sup> - 08  </sup> |   0.123347  |
| LTE 1800      |      7.39765 &middot; 10 <sup> - 09 </sup> |   0.0792292 |
| LTE 2100      |      9.02079 &middot; 10 <sup> - 09 </sup> |   0.0486984 |
| LTE 700       |      3.13804 &middot; 10 <sup> - 08 </sup> |   0.0869999 |
| LTE 2600      |      5.49077 &middot; 10 <sup> - 09 </sup> |   0.0597127 |
| NR 3700       |      1.02173 &middot; 10 <sup> - 08 </sup> |   0.163233  |


| Technology   |   V<sub>UL</sub> |   Intercept |
|:-------------|-----------------:|------------:|
| LTE 800       |      7.41163 &middot; 10 <sup> - 08 </sup> |   0.122385  |
| LTE 1800      |      3.84679 &middot; 10 <sup> - 08 </sup> |   0.0801344 |
| LTE 2100      |      4.69804 &middot; 10 <sup> - 08 </sup> |   0.0517213 |
| LTE 700       |      7.02632 &middot; 10 <sup> - 08 </sup> |   0.106027  |
| LTE 2600      |      3.83975 &middot; 10 <sup> - 08 </sup> |   0.0624466 |
| NR 3700       |      5.69984 &middot; 10 <sup> - 08 </sup> |   0.160808  |


| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |   F |   B |          A |   P<sub>Max</sub> |   Intercept |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|----:|----:|-----------:|------------------:|------------:|
| LTE 800       |       0.000435926 |       0.00223956  |      1.07034 &middot; 10 <sup> - 08 </sup> |     -1.93946 &middot; 10 <sup> - 08 </sup> |   0 |   0 |  0.640399  |       0.00166187  |  -0.729164  |
| LTE 1800      |       0.000906812 |       0.00106663  |      9.91245 &middot; 10 <sup> - 10 </sup> |     -3.52038 &middot; 10 <sup> - 09 </sup> |   0 |   0 |  0.0574126 |       0.0016095   |  -0.0462763 |
| LTE 2100      |       0.00113901  |      -0.000407147 |      1.04481 &middot; 10 <sup> - 09 </sup> |      1.26937 &middot; 10 <sup> - 08 </sup> |   0 |   0 |  0.0183311 |       0.00178236  |  -0.0192772 |
| LTE 700       |       7.08723 &middot; 10 <sup> - 05 </sup> |       0.00112223  |      2.41482 &middot; 10 <sup> - 08  </sup> |     -2.11711 &middot; 10 <sup> - 08 </sup> |   0 |   0 |  0         |       0.0105631   |  -0.172546  |
| LTE 2600      |       0.00101334  |       0.000577968 |     -3.20289 &middot; 10 <sup> - 10  </sup>|      1.6857 &middot; 10 <sup> - 09 </sup>  |   0 |   0 | -0.168632  |       0.000273335 |   0.250833  |
| NR 3700       |       0.00689771  |       0.0063547   |     -2.50702 &middot; 10 <sup> - 09  </sup>|     -9.88026 &middot; 10 <sup> - 09  </sup> |   0 |   0 |  0         |       0           |   0.135002  |


| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |          A |   P<sub>Max</sub> |   Intercept |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|-----------:|------------------:|------------:|
| LTE 800       |       0.000435926 |       0.00223956  |      1.07034 &middot; 10 <sup> - 08 </sup> |     -1.93946 &middot; 10 <sup> - 08  </sup> |  0.640399  |       0.00166187  |  -0.729164  |
| LTE 1800      |       0.000906812 |       0.00106663  |      9.91245 &middot; 10 <sup> - 10 </sup> |     -3.52038 &middot; 10 <sup> - 09 </sup> |  0.0574126 |       0.0016095   |  -0.0462763 |
| LTE 2100      |       0.00113901  |      -0.000407147 |      1.04481 &middot; 10 <sup> - 09 </sup> |      1.26937 &middot; 10 <sup> - 08 </sup> |  0.0183311 |       0.00178236  |  -0.0192772 |
| LTE 700       |       7.08723 &middot; 10 <sup> - 05 </sup> |       0.00112223  |      2.41482 &middot; 10 <sup> - 08 </sup> |     -2.11711 &middot; 10 <sup> - 08 </sup> |  0         |       0.0105631   |  -0.172546  |
| LTE 2600      |       0.00101334  |       0.000577968 |     -3.20289 &middot; 10 <sup> - 10 |      1.6857 &middot; 10 <sup> - 09 </sup>  | -0.168632  |       0.000273335 |   0.250833  |
| NR 3700       |       0.00689771  |       0.0063547   |     -2.50702 &middot; 10 <sup> - 09 |     -9.88026 &middot; 10 <sup> - 09 </sup> |  0         |       0           |   0.135002  |
