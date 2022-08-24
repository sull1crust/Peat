# Peat

The following code creates a linear dataset of SAR backscatter values (angle- and vegetation-corrected) and finds its relationship to water table depths in South Pennine peatlands.
The purpose of this is to use remote sensing values as a proxy for hydrological conditions in wetlands, and then as a means of measuring the landscape's resilience to shocks (drought, low precipitation).
GEE API uses Javascript, while R was used for some data pre- and post-processing.

Necessary assets from external sources:
- shapefiles of desired peatland area (in this case, Natural England, https://naturalengland-defra.opendata.arcgis.com/datasets/Defra::peaty-soils-location-england/)
- weather and soil temperature data (Met Office MIDAS data, https://catalogue.ceda.ac.uk/uuid/dbd451271eb04662beade68da43546e1)
- local hydrological conditions time series (Moors for the Future partnership provided)
