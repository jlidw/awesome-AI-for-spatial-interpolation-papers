# AI for Spatial Interpolation Papers

## Definition
**Spatial Interpolation[^1]** is the traditional method for spatial estimation, which is a process of using values at observed locations to estimate values at unobserved ones in geographic space.

**Spatiotemporal Interpolation** is an extension of spatial interpolation, which adds a time dimension to spatial data and estimates values at unobserved locations given the observations from sampled locations **during a period**.

[^1]: Some works may use another term **"extrapolation"**. Strictly speaking, interpolation and extrapolation are similar things but different ranges. Interpolation means predicting the values within the spatial range of the known locations, while extrapolation will predict the values outside the spatial range of the known locations.
We can optionally use one of these two items when the range of predicted locations is not considered a constraint.
Here, we follow the environmental science[^2] to use the term **interpolation**, as *all spatial interpolation methods can be used to generate an extrapolation.* 
[^2]: >Li, Jin, and Andrew D. Heap. "A review of spatial interpolation methods for environmental scientists." (2008): 137-145.


