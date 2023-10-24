# AI for Spatial Interpolation Papers
Despite recent developments in spatiotemporal data mining, most of which have been on time series forecasting and spatiotemporal forecasting problems, far less attention has been paid to spatial/spatiotemporal interpolation.

In this repository, a list of papers (with available codes) related to spatial interpolation is given, which will be updated ASAP once the papers are announced in the corresponding AI conferences/journals. Hope this list can help those interested in AI for Spatial/Spatiotemporal Interpolation Analysis.

Welcome to contribute the related papers. Please open an issue or email me.

📧: jlidw\[AT\]connect.ust.hk

## Foundations

### Spatial Interpolation
**Spatial Interpolation<sup>#1</sup>** is the traditional method for spatial estimation, which is a process of using values at observed locations to estimate values at unobserved ones in geographic space.

> <sup>#1</sup>Some works may use another term **extrapolation**. Strictly speaking, interpolation and extrapolation are similar things but different ranges. Interpolation means predicting the values within the spatial range of the known locations, while extrapolation will predict the values outside the spatial range of the known locations.
We can optionally use one of these two items when the range of predicted locations is not considered a constraint.
> 
> Here, we follow the geoscience [^1] to use the term **interpolation**, as *all spatial interpolation methods can generate an extrapolation*.
[^1]: A review of spatial interpolation methods for environmental scientists, *Geoscience Australia*, 2008.

### Spatiotemporal Interpolation
**Spatiotemporal Interpolation<sup>#2</sup>** is an extension of spatial interpolation, which adds a time dimension to spatial data and estimates values at unobserved locations given the values from observed locations **during a period**.

> <sup>#2</sup>Some AI works use **Spatiotemporal Kriging** to represent the spatiotemporal interpolation task, which is **conceptually wrong**. Kriging [^2] is a general term denoting a number of geostatistical techniques for interpolation. Essentially, kriging is a method rather than a task. Particularly, the term Spatiotemporal Kriging [^3] itself is a method of spatiotemporal interpolation based on spatiotemporal covariogram, which is an extension of Kriging.
[^2] [Kriging (Wikipedia).](https://en.wikipedia.org/wiki/Kriging#Methods)
[^3] Spatial and Spatio-Temporal Geostatistical Modeling and Kriging, *John Wiley & Sons* 2015.
 
### Spatial Interpolation vs. Spatial Inference/Prediction/Estimation
Will add the corresponding discussion later.

### Spatial Interpolation vs. Time Series Imputation
Spatial interpolation is to “predict” data for **any locations with no historical observations** according to sparse station observations. This problem is fundamentally different and more challenging than multivariate time-series imputation, which assumes data at **certain locations** is **partially missing across time**.

## Method Comparison
Will add a table later.

## Papers
### Spatial Interpolation
- SSIN: Self-Supervised Learning for Rainfall Spatial Interpolation, in *SIGMOD* 2023. [\[Paper\]](https://dl.acm.org/doi/10.1145/3589321), [\[Code\]](https://github.com/jlidw/SSIN)
- Rainfall Spatial Interpolation with Graph Neural Networks, in *DASFAA* 2023. [\[Paper\]](https://link.springer.com/chapter/10.1007/978-3-031-30678-5_14), [\[Code\]](https://github.com/jlidw/GSI)
- Deep geometric neural network for spatial interpolation, in *SIGSPATIAL* 2022. [\[Paper\]](https://dl.acm.org/doi/10.1145/3557915.3561008)
- Kriging Convolutional Networks, in *AAAI* 2020. [\[Paper\]](https://arxiv.org/abs/2306.09463), [\[Code\]](https://github.com/tufts-ml/KCN)

### Spatiotemporal Interpolation
- Graph Neural Processes for Spatio-Temporal Extrapolation, in *KDD* 2023. [\[Paper\]](https://arxiv.org/abs/2305.18719), [\[Code\]](https://github.com/hjf1997/STGNP)
- INCREASE: Inductive Graph Representation Learning for Spatio-Temporal Kriging, in *WWW* 2023. [\[Paper\]](https://arxiv.org/abs/2302.02738), [\[Code\]](https://github.com/zhengchuanpan/INCREASE)
- Decoupling Long-and Short-Term Patterns in Spatiotemporal Inference, in *TNNLS* 2023. [\[Paper\]](https://arxiv.org/abs/2109.09506)
- Inductive Graph Neural Networks for Spatiotemporal Kriging, in *AAAI* 2021. [\[Paper\]](https://arxiv.org/abs/2006.07527), [\[Code\]](https://github.com/Kaimaoge/IGNNK)

