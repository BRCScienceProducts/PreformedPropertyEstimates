# PreformedPropertyEstimates
Gridded global estimates of preformed biogeochemical seawater properties.
3D longitude (360 degrees) by latitude (180 degrees) by 33 depth levels

Properties include:
Phosphate (pP)
Nitrate (pN)
Silicate (pSi)
Total titration seawater alkalinity (pTA)

Calculated using the approach detailed in Carter et al. (submitted).

Summary: A transport matrix (OCIM) is used to infer where interior ocean seawater last left surface mixed layers.  Then (Default) regressions (or interpolations) are used to infer the initial properties of these contributions. 

v1 is the version following peer review... it is identical to v1 except that
	- the netcdf file includes pO, which was mistakenly omitted at submission
	- the marginal sea mask has been reduced to single precision to keep the file size below the 100 mb limit
v0 is the version at submission... this will be updated to v1 if/when initially published online.

"Default" estimates are obtained using the regression approach detailed in this manuscript.  "Interpolated" estimates are obtained using the interpolated properties at the base of the mixed layers.

Preformed properties are assumed to be at steady state and are inferred from the hydrographic record from ~1970 to ~2014.  These estimates are challenged by long term trends in N, P, O2, and TA.  The effects of these trends should be small, compared to the significant uncertainties in the estimates, for decades yet.
