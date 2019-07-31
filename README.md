# Landsat Land Surface Temperature (LST) Retrieval – Google Earth Engine (GEE) Implementation

Method used by ...(2019) (link/doi)

GEE Implementation of the Single-Channel (SC) algorithm developed by Jiménez-Muñoz & Sobrino (2003), 
Jiménez-Muñoz et al. (2009) and Jiménez-Muñoz et al. (2014) for retrieving statistical metrics of LST
from Landsat TM, ETM+ and OLI-TIRS data.
The atmospheric functions used in the algorithm are approximated using data on atmospheric water vapor
content from the NCEP/NCAR Reanalysis Data. Currently, the approximation is optimized for high-latitude 
regions with usually low water vapor content. 
Surface emissivity is calculated using the Simplified Normalized Difference Vegetation Index 
Threshold (SNDVI) approach as described by Sobrino et al. (2008).

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

The minimal installation of the Earth Engine Python API is required (see: https://developers.google.com/earth-engine/python_install)
The following commands need to be executable without any error messages:

```
import ee
ee.Initialize()
```


### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
