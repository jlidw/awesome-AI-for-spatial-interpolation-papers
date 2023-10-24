# AI for Spatial Interpolation Papers
Despite recent developments in spatiotemporal data mining, most of which have been on time series forecasting and spatiotemporal forecasting problems, far less attention has been paid to spatial/spatiotemporal interpolation.

In this repository, a list of papers (with available codes) related to spatial interpolation is given, which will be updated ASAP once the papers are announced in the corresponding top AI conferences/journals. Hope this list can help those interested in AI for Spatial/Spatiotemporal Interpolation Analysis.

Welcome to contribute the related papers. Please open an issue or email me.

📧: jlidw\[AT\]connect.ust.hk

## Foundations

### Interpolation
**Spatial Interpolation \[1\]** is the traditional method for spatial estimation, which is a process of using values at observed locations to estimate values at unobserved ones in geographic space.

**Spatiotemporal Interpolation** is an extension of spatial interpolation, which adds a time dimension to spatial data and estimates values at unobserved locations given the values from observed locations **during a period**.

> \[1\]: Some works may use another term **extrapolation**. Strictly speaking, interpolation and extrapolation are similar things but different ranges. Interpolation means predicting the values within the spatial range of the known locations, while extrapolation will predict the values outside the spatial range of the known locations.
We can optionally use one of these two items when the range of predicted locations is not considered a constraint.
> 
> Here, we follow the environmental science \[2\] to use the term **interpolation**, as *all spatial interpolation methods can generate an extrapolation*.
>> \[2\]: Li, Jin, and Andrew D. Heap. A review of spatial interpolation methods for environmental scientists. (2008): 137-145. 


### Interpolation vs. Prediction/Estimation/Inference
Todo

## Papers
### Spatial Interpolation
- SSIN: Self-Supervised Learning for Rainfall Spatial Interpolation, in *SIGMOD* 2023. [\[Paper\]](https://dl.acm.org/doi/10.1145/3589321), [\[Code\]](https://github.com/jlidw/SSIN)
- Rainfall Spatial Interpolation with Graph Neural Networks, in *DASFAA* 2023. [\[Paper\]](https://link.springer.com/chapter/10.1007/978-3-031-30678-5_14), [\[Code\]](https://github.com/jlidw/GSI)
- Deep geometric neural network for spatial interpolation, in *SIGSPATIAL* 2022. [\[Paper\]](https://dl.acm.org/doi/10.1145/3557915.3561008)
- Kriging convolutional networks, in *AAAI* 2020. [\[Paper\]](https://ojs.aaai.org/index.php/AAAI/article/view/5716), [\[Code\]](https://github.com/tufts-ml/KCN)
  

### Spatiotemporal Interpolation


