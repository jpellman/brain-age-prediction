# Notes on "Prediction of Individual Brain Maturity Using fMRI", Dosenbach et al, Science, 2010

* An SVM classifier can be used to predict age (MVPA).
* 5 min of resting state data; 61 adults, 61 kids; matched for brain volume and movement
* SVM trained directly on age rather than proxies (hormonal levels, etc)
* Validated on two other datasets of 195 scans and 186 scans (event-related but converted to resting-state)
* Most important features for classifier:
 * Weakening of short range connections; segregation
 * Strengthening of long range connections; integration
 * Greater weight to segregation
