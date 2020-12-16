# rw-dynamicworld-cd
A repository holding code and example notebooks for change detection methods and post-classificaiton processing for the Dynamic World Land Cover product.

All Python modules are contained in the [wri_change_detection](https://github.com/wri/rw-dynamicworld-cd/tree/master/wri_change_detection) folder which will soon be installable via pip as well. Jupyter notebooks demonstrating methods for change detection and post-classification processing are contained in the [demo_notebooks](https://github.com/wri/rw-dynamicworld-cd/tree/master/demo_notebooks) folder.

The demo notebooks contain 4 notebooks:
1. [MapBiomas_Spatial_Temporal_Filters.ipynb](https://github.com/wri/rw-dynamicworld-cd/blob/master/demo_notebooks/MapBiomas_Spatial_Temporal_Filters.ipynb): demonstrating the application of gap filling, spatial filters, temporal filters, frequency filters, and incidence filters following code from the [MapBiomas](https://github.com/mapbiomas-brazil) land cover product.
2. [NeighborhoodPrediction_LC_ChangeDetection_Example.ipynb](https://github.com/wri/rw-dynamicworld-cd/blob/master/demo_notebooks/NeighborhoodPrediction_LC_ChangeDetection_Example.ipynb): allows the user to train a model to predict whether change that occurs from year<sub>i</sub> to year<sub>i+1</sub> stays consistent in year<sub>i+2</sub> using properties of the neighboring pixels as predictor variables.
3. [SeasonalProbabilitiesPrediction_LC_ChangeDetection_Example.ipynb](https://github.com/wri/rw-dynamicworld-cd/blob/master/demo_notebooks/SeasonalProbabilitiesPrediction_LC_ChangeDetection_Example.ipynb): allows the user to train a model to predict whether change that occurs from year<sub>i</sub> to year<sub>i+1</sub> stays consistent in year<sub>i+2</sub> sing seasonal class probabilities in year<sub>i</sub> and the difference in seasonal class probabilities from year<sub>i</sub> to year<sub>i+1</sub>.
