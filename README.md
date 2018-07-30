# A federal catalogue of Public Services in Belgium
A federal catalogue of public services, compiling public service descriptions at the Walloon, Flemish and federal levels, all displayed on a user-friendly and easily searchable webpage.

## Introduction
In highly federated countries such as Belgium, citizens and businesses regularly face challenges in accessing information on public services available in their country, as the information is spread over different local, regional and national portals. In addition, other issues arise when trying to access the information:

There are different portals for locating public service descriptions and the information is offered in different languages;
The descriptions do not follow a common structure, and
No portal provides a comprehensive overview of all the public services available across Belgium.
In Belgium, the different regions are responsible for providing the public services in their jurisdiction. Therefore, to provide an effective overview of all public services available in Belgium, the regions need to exchange a large quantity of information on their public services.

The pilot can be accessed [here](http://cpsv-ap.semic.eu/cpsv-ap_harvester_federal_pilot/).

## Functional description
To accomplish the **creation of an interfederal catalogue of services**, we designed a pilot to implement a **user-centric portal** where to offer public service descriptions from the different regions and authorities, based on the harvesting of information from multiple sources into a common system. To achieve this there was a mapping between the Flemish data model, i.e. the [IPDC](https://overheid.vlaanderen.be/producten-diensten/register-of-products-and-service-provision-ipdc) (interbestuurlijke producten- en dienstencatalogus), a mapping between the Walloon data model, i.e. [NOSTRA](http://www.patrimoineculturel.org/index.php?page=wallonia-nostra), and the CPSV-AP and a mapping between the data model of Fedict and the CPSV-AP. These mappings have been used for creating CPSV-AP compliant descriptions of public services. 
![portal BE](https://github.com/catalogue-of-services-isa/cpsv-ap_harvester_federalPilot_Belgium/blob/master/images/portal%20BE_0.png?raw=true)

**Using the CPSV-AP as a common language** between the different data models made the exchange and integration of data between public administrations more efficient, as public services only needed to be described once. By collecting data from both Flanders and Wallonia as well as on the federal level, the pilot is an overarching project for Belgium that provides a proof of concept for the interchangeability of descriptions with a user-centric visualisation. These descriptions are categorised and ordered on life event, business event, sector, etc., to make them easily searchable. An example of the implemented solution can be seen below.
![portal BE site](https://github.com/catalogue-of-services-isa/cpsv-ap_harvester_federalPilot_Belgium/blob/master/images/portal%20BE%20site.png?raw=true)

## Results
The final outcome of the pilot was a website where the harvested data was visualised in a user-centric way.This provides a proof-of-concept for harmonising information based on the CPSV-AP as common vocabulary. A snapshot can be seen below.
![portal BE example](https://github.com/catalogue-of-services-isa/cpsv-ap_harvester_federalPilot_Belgium/blob/master/images/portal%20BE%20example.png?raw=true)

## Technical description
Both the [CPSV-AP Mapping Editor](https://github.com/catalogue-of-services-isa/cpsv-ap_mapping_tool) and the [CPSV-AP Data Harvester](https://github.com/catalogue-of-services-isa/CPSV-AP_harvester/) were used. The Mapping Editor mapped the data models of Flanders, Wallonia and the federal level to the CPSV-AP, which was used as a common vocabulary. The public service descriptions from the three sources were transformed using the mappings, creating CPSV-AP compliant descriptions. These descriptions were then harvested and visualised in the user-centric portal. This can be seen in the figure below.
![FinlandEstonia pilot](https://github.com/catalogue-of-services-isa/cpsv-ap_harvester_federalPilot_Belgium/blob/master/images/BE%20pilot%20technical(1).png?raw=true)
