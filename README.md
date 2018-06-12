# Leeds LifeLongJoints Model
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1254286.svg)](https://doi.org/10.5281/zenodo.1254286)

This is the model used in an FP7 European Commission project called
Lifelongjoints (https://lifelongjoints.eu/). The model was used to investigate
hip loads using a large dataset collect at Leeds Teaching Hospital NHS Trust.

## Get the data

The dataset contained a 140 total hip replacement patients performing a series
of activities of daily living. Note that, this model does not contain any
patient data. The data is available directly from the "Research Data Leeds
Repository", and must be downloaded separately from this model.

Data will be released periodically over the coming months/years. The first test release of data can be found here:

    Lunn, David and Chapman, Graham and Redmond, Anthony (2018) Motion analysis in total joint replacement patients:
    Data Release 1. University of Leeds. [Dataset](https://doi.org/10.5518/345)

## How to use the model:

1. Download data (see above).
2. Exact data (subfolder with c3d files) into the  `C3D-files` directory. 

```
   C3D-files
    ├───LLJ_029\
    |      fast_03_.c3d
    |      fast_04_.c3d
    |      ...
    |      ..
    ├───LLJ_129\
    ├───LLJ_140\
```

3. Find the corresponding `main.any` files in the `Subjects` folder. E.g. (`Subjects/LLJ_029/main.any`)

4. Load the main file execute the `Main.RunAnalysis` operation. 
