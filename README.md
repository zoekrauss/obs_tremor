# obs_tremor
Repository for the manuscript "Potential shallow tectonic tremor signals near the deformation front in central Cascadia"

### Environmental modeling - wind speeds and bottom currents
See folder environmental_modeling/
1. Read in and process seismic data, saving hourly medians: *parallel_hourly_medians.ipynb*
2. Smooth hourly seismic data: *smooth_hourly_medians.ipynb*
3. Read in and process wind speed data: *read_era5_winddata.ipynb*
4. Read in and process bottom current data: *read_bottomcurrents.ipynb*
5. Plot the time series of environmental data: *plot_environmental_data.ipynb*
6. Fit wind speed model: *fit_windspeeds.ipynb*
7. Fit bottom current model: *fit_bottomcurrents.ipynb*

### Envelope cross-correlation - for comparison to STA/LTA triggering
1. Perform envelope cross-correlation between the two OOI stations: *parallel_envelope_cc.ipynb*
2. Plot comparison between envelope cross-correlation and STA/LTA triggering, and calculate overlaps: *compare_cc_triggering.ipynb*

