# Reliable-Air-Data-System-for-Small-UAS

This folder contains my PhD final Defense Slides and link to my defense talk. 

## Reliable Air Data Solutions for Small Unmanned Aircraft Systems##

### Abstract ###
A reliable Air Data System (ADS) ensures the safety and performance of an aircraft. A redundant ADS design, or the hardware redundancy approach, guarantees the reliability of the ADS. However, hardware redundancy is not feasible for small Unmanned Aerial Systems (UAS). Not only is a decent ADS expensive, but many small UAS cannot have multiple ADS due to size, weight, and power constraints. The impracticality and limitations of hardware redundancy have led to an increasing research interest in designing alternative ADS in the last decade. In particular, estimating air data quantities, often denoted as Synthetic Air Data System (SADS), has become a viable strategy to improve the reliability of ADS on small UAS.

There still remain many challenges regarding the reliability of ADS on small UAS. First, calibrating low-cost air data sensors for small UAS is not well addressed. Most existing calibration techniques do not work well with small UAS operating at low airspeeds, especially when the wind effect can no longer be ignored. How can we develop an air data calibration method tailored to small UAS? This dissertation develops a method for calibrating a 5-hole probe sensor applied on small UAS using only flight data.

Second, many SADS use the aerodynamic parameters to help estimate air data quantities, but the accurate aerodynamic model is often unavailable. How can we estimate the air data accurately without the aerodynamic model? This dissertation proposes a model-free SADS. The performance and observability of this ADS are tested using both simulation and flight data.

Lastly, many SADS focus on the accuracy, but the integrity of these systems is not addressed. How do we systematically design and analyze the integrity of ADS for small UAS such that it can be certified in the future? This dissertation designs an air data Fault Detection and Isolation (FDI) algorithm using a dual Pitot tube design. This design can be applied to detect and mitigate Pitot tube failure modes. The integrity of the ADS is established by leveraging the Integrity Monitoring framework. The FDI algorithm is validated with a flight data set that contains a known Water-Blockage fault signature.
