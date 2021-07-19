# marinedata-vocabulary-guidance
As an interim solution to vocabulary harmonization, this repository will develop guidance for data managers on how to select an appropriate vocabulary for their oceanographic observations.





Parameter Level
===============

## Chemistry, Physical

### CF Standard Names

https://cfconventions.org/

If your dataset contains the measurement of a physical property, the conventions for CF (Climate and Forecast) metadata (and acompanying netCDF format) are most likely a good choice.

The CF standard names list is maintained by the CF governance group here:
https://cfconventions.org/standard-names.html

New names can be suggested via the github repository. New terms undergo rigorous inspection and discussion before approval.


#### CF Standard Names Strengths

- Strong community support

#### CF Limitations

- Biological and genomic data (improving?)
- Slow pace of suggesting new terms (subjective and also improving)


### GCMD

https://gcmd.earthdata.nasa.gov/

A NASA product developed for in house projects.



#### GCMD Strengths

- Good for data discovery purposes
- Extensive list


#### GCMD Limitations

- Developed for remote sensors, less relevant to in situ programs (this is changing)


### Chemistry, Physical General Commentary




## Biology

### Worms

https://www.marinespecies.org/index.php

The World Register of Marine Species is an authoritative classification and catalogue of marine names.


#### Strengths

- Marine specific
- Incredibly responsive team


#### Limitations

- potental conflicts with other resources (improving?)


### Itis

https://www.itis.gov/

The Integrated Taxonomic Information System. Authoritative taxonomic information on plants, animals, fungi, and microbes of North America and the world.


#### Strengths

- Taxonomic Serial Number

#### Limitations

- Not marine specific (improving? harmonization with WoRMS?)


### NCBI Taxonomy

https://www.ncbi.nlm.nih.gov/taxonomy

The Taxonomy Database is a curated classification and nomenclature for all of the organisms in the public sequence databases. This currently represents about 10% of the described species of life on the planet.


#### Strengths

- Taxids

#### Limitations

- Genomics oriented (more information and perspective welcome)


### Biology Commentary


- OBIS and Darwincore: Many programs request biological data be submitted to OBIS, which requires DarwinCore, which requires use of WoRMS in combination with NVS. OBIS is a fantastic data aggregator but it should be noted that data can be used outside the OBIS framework.


### Atmospheric



### Geologic








------------------ 
Upcoming

### Units

### Metadata

### Ontologies
