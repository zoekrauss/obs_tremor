# obs_tremor
Repository for the manuscript "Potential Shallow Tectonic Tremor Signals Near the Deformation Front in Central Cascadia"

<img width="760" alt="Screenshot 2024-12-19 at 4 16 00 PM" src="https://github.com/user-attachments/assets/afe1f263-5068-4a45-a1bf-309d984c3dc6" />

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
See folder envelope_cc/
1. Perform envelope cross-correlation between the two OOI stations: *parallel_envelope_cc.ipynb*
2. Plot comparison between envelope cross-correlation and STA/LTA triggering, and calculate overlaps: *compare_cc_triggering.ipynb*

### Tremor detection
See folder tremor_detection/
1. Perform emergent signal detection via STA/LTA triggering: *parallel_stalta_triggering.ipynb*
2. Perform classification on detected signals: *parallel_classification.ipynb*
3. Example plot of classification, from Figure 2: *classification_figure.ipynb*
4. Plot results from Hikurangi: *plot_detections_hikurangi.ipynb*
5. Plot results from the OOI: *plot_detections_ooi.ipynb*
6. Attenuate a tremor signal using Azimi's relation: *attenuation.ipynb*

