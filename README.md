# Mapathon Results
The project is Jupyter notebook that provides different tools that can be used during a mapathon.

* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installing](#installing)
* [Use](#use)
  * [building_rank](#building_rank)
  * [building_user](#building_user)
* [Future work](#future-work)
  
## Getting Started

### Prerequisites

For running the following packages are needed and is tested with that version:

* Folium 0.10.0
* Jupyter Notebook 6.0.1
* Pandas 0.25.3
* Overpass 0.6.1

### Installing

*Overpass* library is available [here](https://github.com/mvexel/overpass-api-python-wrapper/releases) and can be installed with

```
pip instal overpass
```

Other packages can be installed creating a conda environment.

## Use

Brief description of the different option

### building_rank
The first tool can be used during a mapathon to evaluate who mapped the high number of building. 
The parameters to be set are:
- the bounding box
- the time of the event (*must be* converted in UTC format)

### building_user
This tool can be used to evaluate how a group of user mapped building during a certain time span.
The parameters to be set are:
- the bounding box
- the days to analyze
- the list of the username, to be inserted in the file *user_list.csv* add a  username for each line

## Future work
- Analysis of other elements mapped (ex. roads).
