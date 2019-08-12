# Welcome to the ATLAS Open Data Hackathon

This is a documentation to run the resources to-be-released at the [ATLAS Open Data](http://opendata.atlas.cern) project!

# Data and MonteCarlo samples at 13 TeV centre-of-mass energy

- **8 TeV Run 1** samples
 * http://opendata.atlas.cern/extendedanalysis/datasets.php
    * You can get/read one by one, using the URL, from a Jupyter notebook, for example.
    * Or download the ZIP file with all in there.
    * References
       * [Online book](http://opendata.atlas.cern/books/current/openatlasdatatools/_book/variable_names.html)
       * [ATL-OREACH-PUB-2016-001](https://cds.cern.ch/record/2203649/files/ATL-OREACH-PUB-2016-001.pdf)

- **13 TeV Run 2** samples
 * ```/eos/project/a/atlas-outreach/projects/open-data/OpenDataTuples/```
    * Please, avoid any modification, you can simply read directly using LXPLUS (use it as *read-only* area).
    * You need to subscribe to the e-group “atlas-outreach-data-and-tools" to get access.
       * Click [here to subscribe](https://e-groups.cern.ch/e-groups/Egroup.do?egroupId=10162344)
    * Reference
       * [ATL-COM-OREACH-2019-002](https://cds.cern.ch/record/2664887/files/ATL-COM-OREACH-2019-002.pdf)


**Notes**
* We develop the 13 TeV ```TTree``` to be compatible with the 8 TeV ```TTree```.
* This means that in case something is developed using the 8 TeV samples, can be easily modified to fit the 13 TeV ```TTree```.


## What are they?
* They are several collections of samples.
* The collections are defined by the filters that were applied.
* Those filters are:
   * **1lep**
     * MC (55G)
     * Data (54G)
   * **2lep**
     * MC (32G)
     * Data (2.5G)
   * **GamGam**
     * MC (635M)
     * Data (1.4G)
   * **1lep1tau**
     * MC (886M)
     * Data (204M)
   * **1tau**
     * Data (191M)
     * MC (107M)
   * **2tau**
     * MC (36M)
     * Data (55M)
   * **1fatjet1lep**
     * Data (11M)
     * MC (6.0G)

* More details about the samples, production status can be seen [here](https://docs.google.com/spreadsheets/d/1zPlEUikKfXJhqD_LohXQ5x85n9gPPV69tUlngGt2gWo/edit#gid=4912678).

# Analysis Examples frameworks
Explore several of the collections using the Analysis frameworks:

## Notes

### DOI and CERN Open Data access
Datasets have/will have DOI's that allow their citation.
