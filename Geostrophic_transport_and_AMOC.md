## Geostrophic transport and relating AMOC series

https://github.com/Rosecodee/assignment2

## Part 1 — Geostrophic transport

The Upper Meridional Overturning (UMO) transport was calculated using TEOS-10 dynamic height differences be- tween the eastern and western boundaries, vertically in- tegrated to the average AMOC maximum depth ( 1100 m). The integration was deliberately restricted to these upper 1100 m rather than the full ocean depth to isolate the southward-flowing interior transport, which, together with the northward-flowing Ekman and Florida Current transports, defines the upper limb of the AMOC. Ex- tending the integration beyond this depth would merge opposing flow regimes with the deep boundary currents and obscure the upper-ocean return flow structure.

The interior geostrophic estimate displays strong agree- ment with the published TRANS UMO, yielding a linear correlation coefficient of r= 0.76. While the signals match closely, the geostrophic estimate exhibits higher variabil- ity (broader dynamic range from −35 Sv to +5 Sv) com- pared to TRANS UMO.

*Part 2 — Evaluating time series*

## 2A — Single series: seasonal cycle and trend

The monthly climatology, deseasonalised series, and au- tocorrelation were computed for both MOC and TRANS UMO using the remove seasonal cycle, autocorr, and integral timescale functions implemented in correlation trends.

Both 26◦N MOC and TRANS UMO exhibit distinct seasonal climatologies:

MOC: Reaches its minimum transport in April (∼ 14.6 Sv) and peaks in November (∼ 19.8 Sv).

TRANS UMO: Shows a minimum southward transport (least negative) in November (∼ −14.3 Sv) and maximum southward flow in July (∼ −19.8 Sv).

Removing the monthly climatologies yields deseason- alised time series that preserve their respective mean lev- els (≈ 17.2 Sv for MOC and ≈ −17.5 Sv for TRANS UMO).


The integral decorrelation timescale (T∗) was evalu- ated to determine the effective sample size (EDOF = Nraw/(2T∗)):

MOC: T∗

= 18.6 days, indicating fast

atmospheric/Ekman-driven decorrelation.

TRANS UMO: T∗ = 60.6 days, reflecting the longer

baroclinic/mesoscale oceanic memory of the interior field.

Linear trends were fitted to the deseasonalised series, evaluating significance via effective degrees of freedom (peff):

MOC Trend: −0.0928±0.047 Sv/yr. With peff = 0.051, the trend is not statistically significant at the 95% con- fidence level (p > 0.05), highlighting that ignoring au- tocorrelation would have falsely suggested a significant

decline.

TRANS UMO Trend: −0.1094 ± 0.035 Sv/yr. With peff = 0.003, this strengthening southward transport trend remains statistically significant (p < 0.05) even af- ter accounting for high temporal persistence.

## 2B — A pair of series: cross-correlation and lead/lag

Both TRANS EKMAN and MOC are derived from the same standardised RAPID product and are defined on an identical TIME grid. Therefore, no additional processing was required to match the filtering or align the two series to a common time grid.

The −0.5 day lag demonstrates that surface wind- stress-driven Ekman transport leads the overall overturn- ing transport almost instantaneously. Because Ekman transport contributes directly to the upper-limb transport budget, fluctuations in wind stress immediately project onto the total MOC. Given the short memory of T∗ ≈ 18.6 days, the relationship provides strong physical evi- dence that short-term AMOC variability at 26◦N is heav- ily wind-driven rather than density-driven.

However, this near-zero-lag relationship should not be interpreted as purely dynamical, since by construction MOC = TRANS FC + TRANS EKMAN + TRANS UMO. Thus, TRANS EKMAN is an additive component of MOC rather than an independent predictor. As a cross-check, the correlation between TRANS UMO and MOC was also computed, yielding r ≈ 0.25 at a peak lag of ∼ 6.5 days, consistent with the lecture reference value of ≈ 0.28. This confirms the analysis pipeline and indicates that the geostrophic component has a substan- tially weaker relationship with MOC variability than the wind-driven Ekman component.

## Part 3 — Depth Sensitivity of Transport

As the additional analysis, the Part 1 interior geostrophic transport was recomputed at three integration depths (700, 1000, 1100 m) and compared both to each other and to TRANS UMO.

*Table 1: Transport statistics for different maximum inte- gration depths.*

|   |   | zmax (m) Mean (Sv) Std (Sv) | r vs UMO |
| --- | --- | --- | --- |
| 700 | -16.38 | 4.40 | 0.787 |
| 1000 | -14.11 | 5.29 | 0.772 |
| 1100 | -13.46 | 5.50 | 0.762 |

The interior geostrophic transport is clearly sensitive to the chosen integration depth. Extending the integration from 700 m to 1100 m weakens the mean southward trans- port (from −16.4 to −13.5 Sv) while slightly increasing its standard deviation from 4.4 Sv to 5.5 Sv reflecting the


additional, more variable water-mass contributions incor- porated at depth. Correlation with the published TRANS UMO is highest at 700 m (r = 0.79) and decreases slightly toward 1100 m (r = 0.76)
