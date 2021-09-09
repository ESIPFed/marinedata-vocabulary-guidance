Overview
========

The use of controlled vocabularies is foundational to the goal of more FAIR (Findable, Accessible, Interoperable, Reusable) data. 

### Findable

Controlled vocabularies will be central to efforts of federated search and general data discoverability. The role of controlled vocabularies is to offer standard keywords associated with datasets, at varying levels of specificity. It should be noted that parameter names and keywords serve a different role, as parameter names are meant to be maximally specific, while keywords can be more general in varying degrees. Of course, where this line is drawn is open to interpretation.

Illustration: 
hydrography (keyword)
nitrite (keyword)
vs 
mole_concentration_of_nitrate_and_nitrite_in_sea_water	
mole_concentration_of_nitrite_in_sea_water		
moles_of_nitrate_and_nitrite_per_unit_mass_in_sea_water		
moles_of_nitrite_per_unit_mass_in_sea_water

### Accessible

The idea of accessibility is normally outside the discussion of controlled vocabularies as it is often happening, but it should be noted that all of the infrastructure that data accessibility depends on, (networks, the internet, computer architecture, data exchange and storage platforms, etc) depend on their own highly regular ecosystem of controlled vocabularies. This aspect will be omitted from the discussion for now, though that could change should it be useful.


### Interoperable and Reusable

Measurements are of little use without knowing what is being measured. Controlled vocabularies facilite both machine and human interfaces for combining and using data. 

## Vocabulary Lists and Thesauri

The form of controlled vocabulary which is most basic and possibly familiar to users is of the form of a list of terms with definitions. A thesaurus extends this information with additional mappings and definitions between terms, such as work underway by the Nerc Vocabulary Server (NVS).

## Controlled Vocabularies and Ontologies

The terms controlled vocabularies and ontologies are often used interchangeably, but it is useful to remain aware of their functional distinctness. Controlled vocabularies can be described as a set of strict terms and definitions, and ontologies can be described as maps of relationships between terms, or formal context. Ontologies are constructed of controlled vocabularies, and controlled vocabularies are defined by ontologies, but they are not synonymous. It is imaginable that one day, the distinction will be irrelevant functionally, but it is still useful today.

An ontology, broadly speaking, could be defined as a formal categorization scheme for information. For Data Management purposes, ontologies form a way to categorize data (or information) in a way that makes it more useful. Alignment with the FAIR principles as described above is one way to measure increased usefulness.

### Ontologies in Data Management by Use

#### Use for Parameter Naming
Ontologies contribute to parameter identification both in the function of creating parameter names (see efforts by NVS or the RDA I-Adopt Working Group). 

#### Use for Metadata Relationships

Ontologies also provide context to individual measurements by embedding them in a more comprehensive framework of metadata.


#### Use for a Data Categorization 

Example:
https://www.ebi.ac.uk/ols/ontologies/envo/terms?iri=http%3A%2F%2Fpurl.obolibrary.org%2Fobo%2FCHEBI_17632

The Marine Data Cluster plans future discussions on ontologies.
