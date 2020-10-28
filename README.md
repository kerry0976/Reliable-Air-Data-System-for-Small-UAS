# Reliable-Air-Data-System-for-Small-UAS

This folder contains my PhD final Defense Slides and link to my defense talk. 

Dissertation: http://hdl.handle.net/11299/216822

Slides: https://github.com/kerry0976/Reliable-Air-Data-System-for-Small-UAS/blob/master/PhDFinalDefense_KerrySun.pdf

Youtube Link: https://youtu.be/if1iN6_L9dk

## Reliable Air Data Solutions for Small Unmanned Aircraft Systems

### Abstract ###
This dissertation examines the problem of increasing Air Data System (ADS) relia- bility for small Unmanned Aerial Systems (UAS). A reliable ADS is required for the safe operation of aircraft; traditionally, a hardware redundant ADS design has been used. However, hardware redundancy is not feasible in small UAS since reliable ADS are expensive, and many small UAS have more stringent size, weight, and power constraints. The impracticality and limitations of hardware redundancy have motivated research in the last decade to identify alternatives to traditional ADS. In particular, estimating air data quantities, often denoted as Synthetic Air Data System (SADS), has become a viable strategy of interest. This dissertation examines the use of SADS to increase ADS reliability for small UAS.

The key challenges associated with increasing ADS reliability in UAS are examined. First, calibrating low-cost air data sensors for small UAS is not well addressed in the open literature. Most existing calibration techniques do not work well with small UAS operating at low airspeeds, especially when the effects of wind cannot be ignored. This dissertation develops a method for calibrating a 5-hole probe sensor applied on small UAS using only using data from an IMU and GNSS. Second, many SADS use the aerodynamic parameters to help estimate air data quantities, but the accurate aerodynamic model is often unavailable. This dissertation proposes a model-free SADS which allows estimating angle of attack and sideslip without the need for an aerodynamic model. The performance and observability of this SADS are tested using both simulation and flight data.

In addition, the problem of ADS integrity is addressed by systematically designing and analyzing the performance to ensure that it satisfies probabilistic continuity and integrity certification requirements. An ADS Fault Detection and Isolation (FDI) algorithm to detect and mitigate the effect of realistic Pitot tube failure modes is designed. The approach used is the Integrity Monitoring framework, which has been used successfully with GNSS-based precision landing systems for commercial aircraft. The FDI algorithm is validated with a flight data set in which a Pitot tube failed due to water blockage.
