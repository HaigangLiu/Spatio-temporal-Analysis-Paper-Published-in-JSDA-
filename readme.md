# Paper Abstract

*This is a research paper Dr. Hitchcock, Dr Samadi and I published on Journal of Statistical Distributions and Applications. Interested reader can find the compiled pdf that is located in the `out` folder.*

To investigate the relationship between flood gage height and precipitation in South Carolina from 2012 to 2016, we built a conditional autoregressive (CAR) model using a Bayesian hierarchical framework.

This approach allows the modelling of the main spatio-temporal properties of water height dynamics over multiple locations, accounting for the effect of river network, geomorphology, and forcing rainfall. In this respect, a proximity matrix based on watershed information was used to capture the spatial structure of gage height measurements in and around South Carolina. The temporal structure was handled by a first-order autoregressive term in the model. 

Several covariates, including the elevation of the sites and effects of seasonality, were examined, along with daily rainfall amount.
A non-normal error structure was used to account for the heavy-tailed distribution of maximum gage heights. The proposed model captured some key features of the flood process such as seasonality and a stronger association between precipitation and flooding during summer season. The model is able to forecast short term flood gage height which is crucial for informed emergency decision.

As a byproduct, we also developed a Python library to retrieve and handle environmental data provided by some main agencies in the United States. This library can be of general usefulness for studies requiring rainfall, flow, and geomorphological information over specific areas of the conterminous US.