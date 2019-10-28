Metadata
========

The following is the list of metadata needed to describe each element in
the Data Registry (Table 1). This list may foreseeably be supplemented
in light of institutional needs or future recommendations by Agenzia
Digitale per l’Italia (AgID) [1]_; these possible supplements will be
carried out by the Data Management Office and made appropriately known
to personnel and at any rate made available on the website of the Data
Management Office.

Table 1. Metadata describing each element entered into the Data Registry

+-----------------------------------+-----------------------------------+
| **Metadata**                      | **Description of the metadata**   |
+-----------------------------------+-----------------------------------+
| ID                                | Record identifier.                |
+-----------------------------------+-----------------------------------+
| Data Group ID                     | Identifier of the group of        |
|                                   | elements.                         |
+-----------------------------------+-----------------------------------+
| Data Group                        | Full name of the group of         |
|                                   | elements.                         |
+-----------------------------------+-----------------------------------+
| Data Group Acronym                | Acronym, if any, associated with  |
|                                   | the group.                        |
+-----------------------------------+-----------------------------------+
| Name                              | Full name of the element.         |
+-----------------------------------+-----------------------------------+
| Acronym                           | Acronym, if any, associated with  |
|                                   | the element.                      |
+-----------------------------------+-----------------------------------+
| Type of Element                   | Type of element (e.g.: “Digital   |
|                                   | database,” Digital data not       |
|                                   | structured in a database,”        |
|                                   | “Physical samples”).              |
+-----------------------------------+-----------------------------------+
| Description                       | Brief description of the element. |
+-----------------------------------+-----------------------------------+
| Persistent Identifiers            | Persistent identifiers associated |
|                                   | with the element.                 |
+-----------------------------------+-----------------------------------+
| Class                             | -  Volcanology data               |
|                                   |                                   |
|                                   | -  Geochemical data (geochemical  |
|                                   |    analyses of rocks, water, and  |
|                                   |    gas)                           |
|                                   |                                   |
|                                   | -  Geodetic data                  |
|                                   |                                   |
|                                   | -  Seismological and infrasonic   |
|                                   |    data (Earth and sea)           |
|                                   |                                   |
|                                   | -  Data of physical samples       |
|                                   |    (samples and physical          |
|                                   |    parameters of rocks, minerals, |
|                                   |    and various materials)         |
|                                   |                                   |
|                                   | -  Data of atmospheric geophysics |
|                                   |    and Aeronomy                   |
|                                   |                                   |
|                                   | -  Geological data (Earth and     |
|                                   |    sea)                           |
|                                   |                                   |
|                                   | -  Geophysical data (geomagnetic, |
|                                   |    geoelectric, EM, etc.), Earth  |
|                                   |    and sea                        |
|                                   |                                   |
|                                   | -  Data from Numerical Modelling  |
|                                   |                                   |
|                                   | -  Remote sensing data            |
+-----------------------------------+-----------------------------------+
| Level                             | -  Level 0: raw data or basic     |
|                                   |    data, that underwent no level  |
|                                   |    of processing, excluding at    |
|                                   |    most an automatic-type         |
|                                   |    validation (examples:          |
|                                   |    waveforms, GPS data,           |
|                                   |    uncalibrated images, rock      |
|                                   |    samples).                      |
|                                   |                                   |
|                                   | -  Level 1: data products         |
|                                   |    obtained from automatic or     |
|                                   |    semiautomatic procedures       |
|                                   |    (examples: location,           |
|                                   |    magnitude, focal mechanisms of |
|                                   |    earthquakes, shakemaps,        |
|                                   |    historic series of the         |
|                                   |    amplitude of the volcano       |
|                                   |    tremor, and of movement of GPS |
|                                   |    stations).                     |
|                                   |                                   |
|                                   | -  Level 2: data products         |
|                                   |    obtained from the search       |
|                                   |    activity and at any rated      |
|                                   |    based on non-automatic         |
|                                   |    procedures (examples: crust    |
|                                   |    models, strain maps, source    |
|                                   |    models of earthquakes and of   |
|                                   |    deformations, numerical        |
|                                   |    simulation models of volcanic  |
|                                   |    processes, results of          |
|                                   |    geophysical campaigns,         |
|                                   |    laboratory measurements on     |
|                                   |    samples taken for scientific   |
|                                   |    purposes).                     |
|                                   |                                   |
|                                   | -  Level 3: integrated data       |
|                                   |    products obtained from complex |
|                                   |    analyses that supplement       |
|                                   |    several Level 2 products, or   |
|                                   |    from analyses that supplement  |
|                                   |    Level 1 or 2 products of       |
|                                   |    different types and/or         |
|                                   |    originating from different     |
|                                   |    communities (examples: hazard  |
|                                   |    maps, catalogues of active     |
|                                   |    faults, volcanic activity      |
|                                   |    reports).                      |
+-----------------------------------+-----------------------------------+
| Geographic coverage               | This may be indicated with text   |
|                                   | (examples: World; Europe; Italy;  |
|                                   | Etna; province of Catania), or    |
|                                   | with the coordinates of the       |
|                                   | vertices representing the polygon |
|                                   | of geographic coverage, coded     |
|                                   | with the WKT standard [6]_.       |
+-----------------------------------+-----------------------------------+
| Data coding formats               | Where possible, indicating a      |
|                                   | reference to the standard for the |
|                                   | less-common formats.              |
+-----------------------------------+-----------------------------------+
| Associated metadata               | If a metadata model is adopted    |
|                                   | for the description of the        |
|                                   | resource on the whole and/or of   |
|                                   | its content, indicate which       |
|                                   | (examples: Dublin Core, DCAT,     |
|                                   | DataCite, RNDT, INSPIRE).         |
|                                   | Indicate “custom” if these are    |
|                                   | metadata coded in accordance with |
|                                   | an internal, not widespread       |
|                                   | standard.                         |
+-----------------------------------+-----------------------------------+
| Data type                         | Dynamic data or static data.      |
+-----------------------------------+-----------------------------------+
| Update frequency                  | In the case of dynamic data, the  |
|                                   | frequency with which the content  |
|                                   | is modified is specified here     |
|                                   | (e.g.: continuously recorded      |
|                                   | “data streaming”), regardless of  |
|                                   | the reason leading to the         |
|                                   | modification.                     |
+-----------------------------------+-----------------------------------+
| Purpose of use                    | Different case and settings for   |
|                                   | use of the data (examples:        |
|                                   | emergency, communication,         |
|                                   | training, commercial uses).       |
+-----------------------------------+-----------------------------------+
| Data Manager                      | INGV employee of reference who    |
|                                   | sees to the scientific and        |
|                                   | administrative aspects related to |
|                                   | the data. In addition to name,    |
|                                   | surname, and affiliation, the     |
|                                   | ORCID must be present.            |
+-----------------------------------+-----------------------------------+
| Technical Manager                 | INGV employee of reference who    |
|                                   | sees to the technological aspects |
|                                   | related to the Database. In       |
|                                   | addition to name, surname, and    |
|                                   | affiliation, the ORCID must be    |
|                                   | present.                          |
+-----------------------------------+-----------------------------------+
| Data Producer                     | Individual employee or group of   |
|                                   | employees of INGV that produces   |
|                                   | the data. For each employee, the  |
|                                   | name, surname, and affiliation,   |
|                                   | must be indicated, the role       |
|                                   | defined, where possible expressed |
|                                   | in accordance with the            |
|                                   | OpenAire [7]_ specifications, and |
|                                   | the ORCID code provided.          |
+-----------------------------------+-----------------------------------+
| Database organization             | Type of organization of the       |
|                                   | archiving of the data (examples:  |
|                                   | monitoring network, database, raw |
|                                   | data on filesystem or cloud,      |
|                                   | document archive, archive of      |
|                                   | physical samples, photographic    |
|                                   | archive).                         |
+-----------------------------------+-----------------------------------+
| Involved INGV Sections            | List of Sections and offices      |
|                                   | involved in creating and managing |
|                                   | the data (examples: ONT, RM1,     |
|                                   | RM2, OV, OE, PA, BO, PI, MI).     |
+-----------------------------------+-----------------------------------+
| URLs                              | Web address(es) like the homepage |
|                                   | (Landing page), or pages related  |
|                                   | to such services as data search   |
|                                   | and displaying, transferring,     |
|                                   | transforming, editing, and/or     |
|                                   | updating the data.                |
+-----------------------------------+-----------------------------------+
| Web Service                       | Indication of any modes of access |
|                                   | to the data via Web service or    |
|                                   | API (Application Programming      |
|                                   | Interface) or other procedures    |
|                                   | that can be automated, with       |
|                                   | indication of the adopted         |
|                                   | standard (examples: RESTful,      |
|                                   | SOAP, CGI). If available,         |
|                                   | indicate the Web address from     |
|                                   | which it is possible to access;   |
+-----------------------------------+-----------------------------------+
| Documentation                     | Link to the documentation of      |
|                                   | reference, both scientific and    |
|                                   | technological in nature. If       |
|                                   | available, compile with the DOI   |
|                                   | of the publications, or otherwise |
|                                   | with URL.                         |
+-----------------------------------+-----------------------------------+
| Citation                          | Bibliographic citation of the     |
|                                   | data.                             |
+-----------------------------------+-----------------------------------+
| Keywords                          | List of keywords identifying the  |
|                                   | data. Obligatory compilation of a |
|                                   | list in English; addition of a    |
|                                   | list in Italian is optional.      |
+-----------------------------------+-----------------------------------+
| Status                            | Values admitted: “in planning,”   |
|                                   | “in development,” “operative.”    |
|                                   | Indicate “legacy” for data or     |
|                                   | products no longer managed or     |
|                                   | updated, but still accessible.    |
+-----------------------------------+-----------------------------------+
| Ownership                         | Control over the data belongs to  |
|                                   | INGV, except for cases in which   |
|                                   | other institutions are involved.  |
+-----------------------------------+-----------------------------------+
| License                           | Type of Creative Commons license  |
|                                   | associated with the data and/or   |
|                                   | the database, since they might    |
|                                   | differ (the license associated    |
|                                   | with the container is different   |
|                                   | from the license associated with  |
|                                   | the content).                     |
+-----------------------------------+-----------------------------------+
| Access to the data                | The admitted values are           |
|                                   | “anonymous,” “registered,”        |
|                                   | “authorized.” If not applicable,  |
|                                   | briefly describe any alternative  |
|                                   | terms of access.                  |
+-----------------------------------+-----------------------------------+
| Open Data Class                   | Class according to the “5 stars”  |
|                                   | classification [8]_ that defines  |
|                                   | the type of Open Data.            |
+-----------------------------------+-----------------------------------+
| Metadata classes                  | Class according to the metadata   |
|                                   | classification proposed by        |
|                                   | Agenzia per l'Italia Digitale     |
|                                   | (“Levels of the model for         |
|                                   | metadata” from “Linee Guida       |
|                                   | Nazionali per la Valorizzazione   |
|                                   | del Patrimonio Informativo        |
|                                   | Pubblico 2016”).                  |
+-----------------------------------+-----------------------------------+
| RNDT                              | Indication of the relevance of    |
|                                   | the data for the purposes of      |
|                                   | Repertorio Nazionale dei Dati     |
|                                   | Territoriali (national registry   |
|                                   | of spatial data).                 |
+-----------------------------------+-----------------------------------+
| Projects / initiatives of         | Project(s)s and/or initiative(s)  |
| reference                         | of reference for the indicated    |
|                                   | data and/or product (examples:    |
|                                   | INGV-DPC, H2020 Convention –      |
|                                   | followed by the project name –,   |
|                                   | EPOS, EMSO, MED-SUV).             |
+-----------------------------------+-----------------------------------+
| Other institutions involved       | In the case in which institutions |
|                                   | other than INGV have contributed  |
|                                   | towards creating the data,        |
|                                   | indicate which, specifying for    |
|                                   | each level of contribution        |
|                                   | (examples: negligible, marginal,  |
|                                   | substantial).                     |
+-----------------------------------+-----------------------------------+
| Links                             | It is possible to indicate links  |
|                                   | and the type of relationship in   |
|                                   | accordance with OpenAire          |
|                                   | guidelines [9]_. It is possible   |
|                                   | to establish links to other       |
|                                   | Registry elements, or to elements |
|                                   | outside the Registry, such as for |
|                                   | example publications, or other    |
|                                   | Databases making said data        |
|                                   | available.                        |
+-----------------------------------+-----------------------------------+
| Data creation date                | Date when the data were created.  |
+-----------------------------------+-----------------------------------+
| Record creation date              | Date when the element was entered |
|                                   | into the Data Registry.           |
+-----------------------------------+-----------------------------------+
| Date of last update of the record | Date of last update of the        |
|                                   | information pertaining to the     |
|                                   | element.                          |
+-----------------------------------+-----------------------------------+
| Notes                             | Any additional notes of use for   |
|                                   | the purposes of the Data          |
|                                   | Registry.                         |
+-----------------------------------+-----------------------------------+

.. [1]
   Agenzia Digitale per l'Italia. Linee Guida per i cataloghi dati.

.. [2]
   Well-known text, ISO/IEC 13249-3:2016,
   https://en.wildpedia.org/wiki/Well-known_text

.. [3]
   OpenAire. OpenAIRE Guidelines for Data Archives.

.. [4]
   5 stars Open Data. http://5stardata.info

.. [5]
   OpenAire. Guidelines for Data Archives.

.. [6]
   Well-known text, ISO/IEC 13249-3:2016,
   https://en.wildpedia.org/wiki/Well-known_text

.. [7]
   OpenAire. OpenAIRE Guidelines for Data Archives.

.. [8]
   5 stars Open Data. http://5stardata.info

.. [9]
   OpenAire. Guidelines for Data Archives.
