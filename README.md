# Extract Buildings From ERI

The goal for this right now is to develop a workflow for developing training data from ERI using open street map or other publicly available building footprints. 

Then use those images to train models using the Segmentation gym workflow.

(another example of a basic unet with INRIA data is here: https://github.com/ebgoldstein/BuildingUNET)

#### Environment uses parts of CoastSeg:

> conda create -n ENV python=3.10

> conda activate ENV

> conda install -c conda-forge rasterio geopandas pandas numpy scikit-learn scikit-image matplotlib notebook tqdm -y

Note that an `environment.yml` is also included in the repository.