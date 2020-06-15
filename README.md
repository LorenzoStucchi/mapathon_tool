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

* Folium
* Jupyter Notebook
* Pandas
* [Overpass](https://github.com/mvexel/overpass-api-python-wrapper/releases)

### Installing

The requirements could be installed using:

```
pip instal -r requirements.txt
```


## Use

Brief description of the different option

### building_rank
The first tool can be used during a mapathon to evaluate who mapped the high number of building, check also if some user didn't insert the tag.
The parameters to be set are:
- the bounding box
- the time of the event (*must be* converted in UTC format)

### building_user
(*OLD VERSION*)
This tool can be used to evaluate how a group of user mapped building during a certain time span.
The parameters to be set are:
- the bounding box
- the days to analyze
- the list of the username, to be inserted in the file *user_list.csv* add a  username for each line

## Future work
- Analysis of other elements mapped (ex. roads).
