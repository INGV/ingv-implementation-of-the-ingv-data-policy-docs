DOIs
====

The Data Management Office will, where possible, associate each element
of the Data Registry with a persistent DOI, entering the related
metadata into the DataCite registry [1]_.

Guidelines for Assignment
-------------------------

Assignment of a DOI is bound by a series of mandatory conditions, since:

-  a web page to be associated, called the “Landing Page,” must be
   available and openly accessible;

-  it must be possible to access the data directly from the Landing
   Page;

-  a Creative Commons license must be associated with the identified
   data;

-  the list of metadata must be compiled in accordance with the DataCite
   scheme [2]_.

The convention executed in 2013 between INGV and CRUI (Conference of
Italian University Rectors) provides two DOI prefixes:

-  “10.6092/INGV.IT-“ a sub-code of the CRUI prefix, shared with other
   institutions, and with explicit reference to INGV;

-  “10.13127,”a neutral prefix for INGV’s exclusive use.

The DOI is structured with a prefix and a suffix; here is an example
based on the code with the CRUI prefix:

|image0|

The following are the guidelines for assigning identifiers, drawn up
taking consideration of the indications contained in the DOI
Handbook [3]_.

The code “10.6092/INGV.IT-“ is to be used for the data whose ownership
belongs to INGV exclusively, and whose geographic coverage is of
strictly national interest. The DOI codes based on this prefix must
comply with the following structure:

10.6092/INGV.IT/< data-group>/<specific identifier>

The prefix “10.13127” is to be used when the use of an anonymous code is
desirable, for example in the case in which data is to be identified to
which several institutions have contributed, or that are of
international importance, or in the case in which the use of
“non-speaking” identification codes – a term of the trade by which it is
meant that the code presents no intelligible form – is requested. The
DOI codes based on this prefix must comply with the following structure:

10.13127/< data-group>/<specific identifier>

Complex groups of the Registry’s elements may adapt a common base code,
followed by a (“/”), followed in term by a different identifier for each
element in the data group; there may be more than one sublevel,
depending on each specific data group’s complexity.

Groups of data containing different versions of the same element must
adopt a constant prefix, adding the version after the period (“.”).

The suffix’s length should not exceed 50 characters, and may contain the
following characters: numbers (0-9), upper-case letters of the
English-language alphabet (A-Z); the “minus” sign (“-"” and the
“underscore” sign (“_”).

To disseminate the use of the associated DOI codes, it is recommended
that reference to the code always be added in presentations, abstracts,
posters, technical reports, social networks, and above all,
publications. For a more functional use, it is recommended that the code
be presented in the form of a resolvable address (e.g.:
https://doi.org/10.13127/xxxx).

Guidelines for Compiling Metadata
---------------------------------

The metadata to be associated with the DOI adopt the DataCite
schema [4]_ in its most recent version. This document makes reference to
version 4.1 of the scheme (the most recent one at the time of the
drawing up hereof); it is foreseeable that in the future, these may vary
with new versions, and therefore the Data Management Office will be
responsible for signalling any updates on its web page.

The following is a list of available metadata; for each, specification
is made of the tag to be used, the number of possible occurrences, the
definition in accordance with the DataCite scheme, and an indication on
the content. The metadata are subdivided into those with mandatory
compilation (Table 2), which is to say the presence of which is
obligatory for entering data into the Data Registry, and metadata with
optional compilation (Table 3).

The metadata are compiled using the XML format; if possible, the Data
Management Office will make appropriate tools available to simplify the
process of compiling this file.

Table 2 - Metadata with mandatory compilation.

+-----------------+-----------------+-----------------+-----------------+
| **Tag**         | **Occurr.**     | **Definition    | **Content**     |
|                 |                 | according to    |                 |
|                 |                 | DataCite        |                 |
|                 |                 | (v4.1)**        |                 |
+-----------------+-----------------+-----------------+-----------------+
| Identifier      | 1               | The Identifier  | Compiled with   |
|                 |                 | is a unique     | the assigned    |
|                 |                 | string that     | DOI code.       |
|                 |                 | identifies a    |                 |
|                 |                 | resource. For   |                 |
|                 |                 | software,       |                 |
|                 |                 | determine       |                 |
|                 |                 | whether the     |                 |
|                 |                 | identifier is   |                 |
|                 |                 | for a specific  |                 |
|                 |                 | version of a    |                 |
|                 |                 | piece of        |                 |
|                 |                 | software, (per  |                 |
|                 |                 | the Forcell     |                 |
|                 |                 | Software        |                 |
|                 |                 | Citation        |                 |
|                 |                 | Principles [6]_ |                 |
|                 |                 | ),              |                 |
|                 |                 | or for all      |                 |
|                 |                 | versions.       |                 |
+-----------------+-----------------+-----------------+-----------------+
| Title           | 1               | A name or title | Title in        |
|                 |                 | by which a      | English; any    |
|                 |                 | resource is     | acronym is      |
|                 |                 | known. May be   | added in        |
|                 |                 | the title of a  | parentheses. It |
|                 |                 | dataset or the  | is possible to  |
|                 |                 | name of a piece | specify the     |
|                 |                 | of software.    | title           |
|                 |                 |                 | translated into |
|                 |                 |                 | other languages |
|                 |                 |                 | using the       |
|                 |                 |                 | attribute       |
|                 |                 |                 | “TranslatedTitl |
|                 |                 |                 | e.”             |
+-----------------+-----------------+-----------------+-----------------+
| Publication     | 1               | The year when   | Year of first   |
| Year            |                 | the data was or | publication of  |
|                 |                 | will be made    | the datadi      |
|                 |                 | publicly        | prima           |
|                 |                 | available. In   | pubblicazione   |
|                 |                 | the case of     | dei dati.       |
|                 |                 | resources such  |                 |
|                 |                 | as software or  |                 |
|                 |                 | dynamic data    |                 |
|                 |                 | where there may |                 |
|                 |                 | be multiple     |                 |
|                 |                 | releases in one |                 |
|                 |                 | year, include   |                 |
|                 |                 | the             |                 |
|                 |                 | Date/dateType/d |                 |
|                 |                 | ateInformation  |                 |
|                 |                 | property and    |                 |
|                 |                 | sub-properties  |                 |
|                 |                 | to provide more |                 |
|                 |                 | information     |                 |
|                 |                 | about the       |                 |
|                 |                 | publication or  |                 |
|                 |                 | release date    |                 |
|                 |                 | details.        |                 |
+-----------------+-----------------+-----------------+-----------------+
| Resource Type   | 1               | A description   | For the         |
|                 |                 | of the          | purposes of the |
|                 |                 | resource.       | Data Registry,  |
|                 |                 |                 | it is usually   |
|                 |                 |                 | compiled with   |
|                 |                 |                 | “Dataset.” The  |
|                 |                 |                 | DataCite scheme |
|                 |                 |                 | leaves the      |
|                 |                 |                 | field’s         |
|                 |                 |                 | compilation     |
|                 |                 |                 | open.           |
+-----------------+-----------------+-----------------+-----------------+
| Description     | 1-n             | All additional  | Text            |
|                 |                 | information     | description of  |
|                 |                 | that does not   | the data, clear |
|                 |                 | fit in any of   | and concise and |
|                 |                 | the other       | in English. Add |
|                 |                 | categories. May | the             |
|                 |                 | be used for     | “DescriptionTyp |
|                 |                 | technical       | e”              |
|                 |                 | information.    | attribute       |
|                 |                 |                 | compiled with   |
|                 |                 |                 | “Abstract.”     |
|                 |                 |                 | Other types of  |
|                 |                 |                 | descriptions    |
|                 |                 |                 | can also be     |
|                 |                 |                 | added:          |
|                 |                 |                 | “Methods,”      |
|                 |                 |                 | "SeriesInformat |
|                 |                 |                 | ion,”           |
|                 |                 |                 | “TableOfContent |
|                 |                 |                 | s,”             |
|                 |                 |                 | “TechnicalInfo. |
|                 |                 |                 | ”               |
+-----------------+-----------------+-----------------+-----------------+
| Subject         | 1-n             | Subject,        | Free            |
|                 |                 | keyword,        | compilation,    |
|                 |                 | classification  | taking care to  |
|                 |                 | code, or key    | specify the     |
|                 |                 | phrase          | “SubjectScheme” |
|                 |                 | describing the  | attribute       |
|                 |                 | resource.       | indicating the  |
|                 |                 |                 | classification  |
|                 |                 |                 | scheme used.    |
+-----------------+-----------------+-----------------+-----------------+
| GeoLocation     | 1-n             | Spatial region  | A               |
|                 |                 | or named place  | “GeoLocationPla |
|                 |                 | where the data  | ce”             |
|                 |                 | was gathered or | series and/or a |
|                 |                 | about which the | “GeoLocationPol |
|                 |                 | data is         | ygon”           |
|                 |                 | focused.        | series, and/or  |
|                 |                 |                 | a               |
|                 |                 |                 | “GeoLocationPol |
|                 |                 |                 | ygon”           |
|                 |                 |                 | series may be   |
|                 |                 |                 | specified.      |
+-----------------+-----------------+-----------------+-----------------+
| Publisher       | 1               | The name of the | Enter the name  |
|                 |                 | entity that     | of the          |
|                 |                 | holds,          | Institution     |
|                 |                 | archives,       | that makes the  |
|                 |                 | publishes       | data available. |
|                 |                 | prints,         | The field is    |
|                 |                 | distributes,    | compiled with   |
|                 |                 | releases,       | “Istituto       |
|                 |                 | issues, or      | Nazionale di    |
|                 |                 | produces the    | Geofisica e     |
|                 |                 | resource. This  | Vulcanologia    |
|                 |                 | property will   | (INGV).”        |
|                 |                 | be used to      |                 |
|                 |                 | formulate the   |                 |
|                 |                 | citation, so    |                 |
|                 |                 | consider the    |                 |
|                 |                 | prominence of   |                 |
|                 |                 | the role. For   |                 |
|                 |                 | software, use   |                 |
|                 |                 | Publisher for   |                 |
|                 |                 | the code        |                 |
|                 |                 | repository. If  |                 |
|                 |                 | there is an     |                 |
|                 |                 | entity other    |                 |
|                 |                 | than a code     |                 |
|                 |                 | repository,     |                 |
|                 |                 | that “holds,    |                 |
|                 |                 | archives,       |                 |
|                 |                 | publishes,      |                 |
|                 |                 | prints,         |                 |
|                 |                 | distributes,    |                 |
|                 |                 | releases,       |                 |
|                 |                 | issues, or      |                 |
|                 |                 | produces” the   |                 |
|                 |                 | code, use the   |                 |
|                 |                 | property        |                 |
|                 |                 | Contributor /   |                 |
|                 |                 | contributorType |                 |
|                 |                 | /               |                 |
|                 |                 | hostinglnstitut |                 |
|                 |                 | ion             |                 |
|                 |                 | for the code    |                 |
|                 |                 | repository.     |                 |
+-----------------+-----------------+-----------------+-----------------+
| Creator         | 1-n             | The main        | List the main   |
|                 |                 | researchers     | scientific      |
|                 |                 | involved in     | and/or          |
|                 |                 | producing the   | technological   |
|                 |                 | data, or the    | managers,       |
|                 |                 | authors of the  | indicating the  |
|                 |                 | publication, in | affiliation and |
|                 |                 | priority order. | ORCID           |
|                 |                 |                 | identifier code |
|                 |                 |                 | for each. In    |
|                 |                 |                 | addition to the |
|                 |                 |                 | main managers,  |
|                 |                 |                 | a generic       |
|                 |                 |                 | reference to    |
|                 |                 |                 | the Working     |
|                 |                 |                 | Group can also  |
|                 |                 |                 | be entered.     |
+-----------------+-----------------+-----------------+-----------------+
| Contributor     | 1-n             | The institution | List the        |
|                 |                 | or person       | persons that    |
|                 |                 | responsible for | contributed to  |
|                 |                 | collecting,     | the data,       |
|                 |                 | managing,       | identifying for |
|                 |                 | distributing,   | each the role   |
|                 |                 | or otherwise    | carried out,    |
|                 |                 | contributing to | affiliation,    |
|                 |                 | the development | and ORCID code. |
|                 |                 | of the          | Institutions    |
|                 |                 | resource. To    | can also be     |
|                 |                 | supply multiple | added. Set the  |
|                 |                 | contributors,   | “nameType”      |
|                 |                 | repeat this     | attribute as    |
|                 |                 | property. For   | “personal” for  |
|                 |                 | software, if    | persons and     |
|                 |                 | there is an     | “organizational |
|                 |                 | alternate       | ”               |
|                 |                 | entity that     | for             |
|                 |                 | "holds,         | institutions.   |
|                 |                 | archives,       | The roles       |
|                 |                 | publishes,      | provided for    |
|                 |                 | prints,         | are:            |
|                 |                 | distributes,    | ContactPerson,  |
|                 |                 | releases,       | DataCollector,  |
|                 |                 | issues, or      | DataCurator,    |
|                 |                 | produces" the   | DataManager,    |
|                 |                 | code, use the   | Distributor,    |
|                 |                 | contributorType | Editor,         |
|                 |                 | “hostingInstítu | Hostinglnstitut |
|                 |                 | tion”           | ion,            |
|                 |                 | for the code    | Other,          |
|                 |                 | repository.     | Producer,       |
|                 |                 |                 | ProjectLeader,  |
|                 |                 |                 | ProjectManager, |
|                 |                 |                 | ProjectMember,  |
|                 |                 |                 | RegistrationAge |
|                 |                 |                 | ncy,            |
|                 |                 |                 | RegistrationAut |
|                 |                 |                 | hority,         |
|                 |                 |                 | RelatedPerson,  |
|                 |                 |                 | ResearchGroup,  |
|                 |                 |                 | RightsHolder,   |
|                 |                 |                 | Researcher,     |
|                 |                 |                 | Sponsor,        |
|                 |                 |                 | Supervisor, and |
|                 |                 |                 | WorkPackageLead |
|                 |                 |                 | er              |
+-----------------+-----------------+-----------------+-----------------+
| Rights          | 1               | Any rights      | Type of         |
|                 |                 | information for | Creative        |
|                 |                 | this resource   | Commons         |
|                 |                 |                 | license.        |
+-----------------+-----------------+-----------------+-----------------+
| Funding         | 1-n             | Information     | List of         |
| Reference       |                 | about financial | institutions    |
|                 |                 | support         | that funded the |
|                 |                 | (funding) for   | creation of the |
|                 |                 | the resource    | data.           |
|                 |                 | being           |                 |
|                 |                 | registered      |                 |
+-----------------+-----------------+-----------------+-----------------+
| Date            | 0-1             | Different dates | If available,   |
|                 |                 | relevant to the | compile with    |
|                 |                 | work. The       | relevant dates. |
|                 |                 | “dateType”      |                 |
|                 |                 | attribute may   |                 |
|                 |                 | contain:        |                 |
|                 |                 | Accepted,       |                 |
|                 |                 | Available,      |                 |
|                 |                 | Copyrighted,    |                 |
|                 |                 | Collected,      |                 |
|                 |                 | Created,        |                 |
|                 |                 | Issued,         |                 |
|                 |                 | Submitted,      |                 |
|                 |                 | Updated, Valid. |                 |
+-----------------+-----------------+-----------------+-----------------+
| Language        | 0-1             | The primary     | Compile with    |
|                 |                 | language of the | the English     |
|                 |                 | resource        | wording of the  |
|                 |                 |                 | language in     |
|                 |                 |                 | which the data  |
|                 |                 |                 | are publicly    |
|                 |                 |                 | available.      |
+-----------------+-----------------+-----------------+-----------------+
| Alternate       | 0-n             | An identifier   | If the data     |
| Identifier      |                 | or identifiers  | have            |
|                 |                 | other than the  | relationships,  |
|                 |                 | primary         | of any nature,  |
|                 |                 | Identifier      | with other      |
|                 |                 | applied to the  | research        |
|                 |                 | resource being  | products        |
|                 |                 | registered.     | associated with |
|                 |                 | This may be any | identifiers,    |
|                 |                 | alphanumeric    | this tag can be |
|                 |                 | string which is | used to         |
|                 |                 | unique within   | establish a     |
|                 |                 | its domain of   | link. See the   |
|                 |                 | issue. May be   | list of         |
|                 |                 | used for local  | admitted        |
|                 |                 | identifiers.    | relationships   |
|                 |                 | Alternate       | below.          |
|                 |                 | Identifier      |                 |
|                 |                 | should be used  |                 |
|                 |                 | for another     |                 |
|                 |                 | identifier of   |                 |
|                 |                 | the same        |                 |
|                 |                 | instance (same  |                 |
|                 |                 | location, same  |                 |
|                 |                 | file).          |                 |
+-----------------+-----------------+-----------------+-----------------+
| Size            | 0-n             | Size (e.g.      | If the data can |
|                 |                 | bytes, pages,   | be quantified,  |
|                 |                 | inches, etc.)   | compile this    |
|                 |                 | or duration     | field           |
|                 |                 | (extent) e.g.   |                 |
|                 |                 | hours, minutes, |                 |
|                 |                 | days, etc., of  |                 |
|                 |                 | a resource      |                 |
+-----------------+-----------------+-----------------+-----------------+
| Format          | 0-n             | Technical       | If the data are |
|                 |                 | format of the   | available in    |
|                 |                 | resource. Use   | one or more     |
|                 |                 | file extension  | data coding     |
|                 |                 | or MIME type    | standards,      |
|                 |                 | where possible  | indicate the    |
|                 |                 |                 | formats here.   |
+-----------------+-----------------+-----------------+-----------------+

Relationships with other research products
------------------------------------------

The DataCite metadata schema allows the DOI to be linked to other
digital resources available on the Internet. The “relatedldentifier” tag
tasked with establishing these links can specify, in the
“relatedIdentifierType” attribute, one of the following types of
identifier: ARK, arXiv, bibcode, DOI, EAN13, EISSN, Handle, IGSN, ISBN,
ISSN, ISTC, LISSN, LSID, PMID, PURL, UPC, URL, URN. The type of
relationship between the DOI and another digital resource is specified
using the “relationType” attribute. Table 4 Lists the admitted
relationships in which (A) represents the data being described in the
Data Registry that is associated with the DOI, and (B) the digital
element that is being linked.

*Table 4 – List of types of relationships admitted by the DataCite
metadata scheme.*

+-----------------------------------+-----------------------------------+
| **Type of relationship**          | **Description provided by         |
|                                   | DataCite**                        |
+-----------------------------------+-----------------------------------+
| IsCitedBy                         | Indicates that B includes A in a  |
|                                   | citation                          |
+-----------------------------------+-----------------------------------+
| Cites                             | Indicates that A includes B in a  |
|                                   | citation                          |
+-----------------------------------+-----------------------------------+
| IsSupplementTo                    | Indicates that A is a supplement  |
|                                   | to B                              |
+-----------------------------------+-----------------------------------+
| IsSupplementedBy                  | Indicates that B is a supplement  |
|                                   | to A                              |
+-----------------------------------+-----------------------------------+
| IsContinuedBy                     | Indicates A is continued by the   |
|                                   | work B                            |
+-----------------------------------+-----------------------------------+
| Continues                         | Indicates A is a continuation of  |
|                                   | the work B                        |
+-----------------------------------+-----------------------------------+
| Describes                         | Indicates A describes B           |
+-----------------------------------+-----------------------------------+
| IsDescribedBy                     | Indicates A is described by B     |
+-----------------------------------+-----------------------------------+
| HasMetadata                       | Indicates resource A has          |
|                                   | additional metadata B             |
+-----------------------------------+-----------------------------------+
| IsMetadataFor                     | Indicates additional metadata A   |
|                                   | for a resource B                  |
+-----------------------------------+-----------------------------------+
| HasVersion                        | Indicates A has a version (B)     |
+-----------------------------------+-----------------------------------+
| IsVersionOf                       | Indicates A is a version of B     |
+-----------------------------------+-----------------------------------+
| IsNewVersionOf                    | Indicates A is a new edition of   |
|                                   | B, where the new edition has been |
|                                   | modified or updated               |
+-----------------------------------+-----------------------------------+
| IsPreviousVersionOf               | Indicates A is a previous edition |
|                                   | of B                              |
+-----------------------------------+-----------------------------------+
| IsPartOf                          | Indicates A is a portion of B;    |
|                                   | may be used for elements of a     |
|                                   | series                            |
+-----------------------------------+-----------------------------------+
| HasPart                           | Indicates A includes the part B   |
+-----------------------------------+-----------------------------------+
| IsReferencedBy                    | Indicates A is used as a source   |
|                                   | of information by B               |
+-----------------------------------+-----------------------------------+
| References                        | Indicates B is used as a source   |
|                                   | of information for A              |
+-----------------------------------+-----------------------------------+
| IsDocumentedBy                    | Indicates B is documentation      |
|                                   | about or explaining A             |
+-----------------------------------+-----------------------------------+
| Documents                         | Indicates A is documentation      |
|                                   | about B                           |
+-----------------------------------+-----------------------------------+
| IsCompiledBy                      | Indicates B is used to compile or |
|                                   | create A                          |
+-----------------------------------+-----------------------------------+
| Compiles                          | Indicates B is the result of a    |
|                                   | compile or creation event using A |
+-----------------------------------+-----------------------------------+
| IsVariantFormOf                   | Indicates A is a variant or       |
|                                   | different form of B               |
+-----------------------------------+-----------------------------------+
| IsOriginalFormOf                  | Indicates A is the original form  |
|                                   | of B                              |
+-----------------------------------+-----------------------------------+
| IsIdenticalTo                     | Indicates that A is identical to  |
|                                   | B, for use when there is a need   |
|                                   | to register two separate          |
|                                   | instances of the same resource    |
+-----------------------------------+-----------------------------------+
| IsReviewedBy                      | Indicates that A is reviewed by B |
+-----------------------------------+-----------------------------------+
| Reviews                           | Indicates that A is a review of B |
+-----------------------------------+-----------------------------------+
| IsDerivedFrom                     | Indicates B is a source upon      |
|                                   | which A is based                  |
+-----------------------------------+-----------------------------------+
| I IsSourceOf                      | Indicates A is a source upon      |
|                                   | which B is based                  |
+-----------------------------------+-----------------------------------+
| IsRequiredBy                      | Indicates A is required by B      |
+-----------------------------------+-----------------------------------+
| Requires                          | Indicates A requires B            |
+-----------------------------------+-----------------------------------+

Identification of Fragments of Complex Data
-------------------------------------------

In order to recover a subset of a set of data (fragment or subset) that
is associated with a DOI, solutions may be used to avoid the unnecessary
assignment of many different identifiers for each possible fragment of
the original data. Towards this end, the concept of “fragment
identifier” is introduced.

This solution is supported by the DataCite registry, which implemented
the “Media Fragment Identifiers” (MFIDs), a standard developed by W3C
and based on IETF (Internet Engineering Task Force) recommendations,
designed to simplify access to such data flows as video or audio. The
call is structured as follows:

<scheme name> <hierarchical part> [ ? <query> ] [ # <fragment> ]

Since they are based on the Handle System [7]_, DOIs can use “Template
handles,” which allow an undefined number of parameters to be added to
the identifier, inserted after the hash sign (“#”). This solution was
taken into consideration by the “Data Citation” working group [8]_ from
the Research Data Alliance (RDA), which recommended it in a dynamic data
setting. The technique for extracting data subsets with the aid of
parameters is called “data slicing.” In the seismological setting,
trials are underway [9]_  [10]_in the context of the European
COOPEUS [11]_, ENVRI [12]_, and EUDAT  [13]_projects.

.. [1]
   DataCite. https://www.datacite.org,/

.. [2]
   DataCite metadata scheme. https://schema.datacite.org/

.. [3]
   International DOI Foundation. DOI Handbook.
   https://www.doi.org/hb.html

.. [4]
   DataCite. Metadata scheme. https://schema.datacite.org,/

.. [5]
   Smith AM, Katz DS, Niemeyer KE, FORCE11 Software Citation Working
   Group (2016). Software citation principles. PeerJ Computer Science.
   https://doi.org/10.7717/peerj-cs.86

.. [6]
   Smith AM, Katz DS, Niemeyer KE, FORCE11 Software Citation Working
   Group (2016). Software citation principles. PeerJ Computer Science.
   https://doi.org/10.7717/peerj-cs.86

.. [7]
   Handle Registry. https://www.handle.net/

.. [8]
   Rauber A., Asmi A., van Uytvanck D., Pri511 S. (2015). Data Citation
   of Evolving Data.
   https://rd-alliance.org/system/files/documents/RDA-DC-Recommendations_150924.pdf

.. [9]
   Klump J. and Huber R. (2016). DOI for geoscience data - how early
   practices shape present perceptions. Earth Science Informatics, 9(1):
   123-136. https://doi.org/10.1007/s12145-015-0231-5

.. [10]
   46 Huber R., Asmi A., Buck J., De Luca J.M., Diepenbroek D.,
   Michelini A. (2015). Data citation and digital identifiers for time
   series data / environmental research infrastructures. Joint
   COOPEUS/ENVRI/EUDAT PID workshop, Bremen, 25-26 June 2013.
   https://doi.org/10.6084/m9.figshare.1285728.v1

.. [11]
   https://www.coopeus.eu/

.. [12]
   https://envri.eu/

.. [13]
   https://eudat.eu/

.. |image0| image:: ./media/image3.png
   :width: 3.1875in
   :height: 1.22523in
