# GeoERA Keyword Thesaurus
A collection of ~2500 geoscientific terms in English (keywords), with unique web addresses (URIs), delivered in RDF format, with translations in different languages, with links to standardized codelists (INSPIRE, GeoSciML, GEMET), thesaurus like modeled in accordance with the search use case and metadata tagging in MICKA. Hosted in an EGDI central repository, online available via web API (Sparql) to drive search systems.
Deployed in versioned updates according to a governance workflow. See also our GitHub **[project](https://github.com/GeoEra-GIP/WP4-Semantics/projects/1)** or **[PDF](https://github.com/GeoEra-GIP/WP4-Semantics/blob/master/Keyword%20Thesaurus/img/keywords.pdf)** for overview.

A provisional application for **testing a semantic search** can be found **[here](https://schmar00.github.io/semantic-search/)**  
For testing database queries with **SparQl** you can use this **[endpoint](https://resource.geolba.ac.at/PoolParty/sparql/geoera_keyword)**  
Both already using v1.1!  

![test application](/Keyword%20Thesaurus/img/Keyword_TEST_screen2.jpg) ![visualization](/Keyword%20Thesaurus/img/gephi_thumbnail.jpg)

## version 1.0
[GeoERA-Keyword-Thesaurus_v1](https://github.com/GeoEra-GIP/WP4-Semantics/blob/master/Keyword%20Thesaurus/GeoERA-Keyword-Thesaurus_1.0.zip)
includes a selection of evaluated and compiled vocabularies, mainly from resources like GEMET, INSPIRE or CGI - see our [report](https://geoera.eu/wp-content/uploads/2019/11/D4.2-GeoERA-Keyword-Thesaurus.pdf)

## version 1.1
**release notes (draft 3.2.2020):**  
Fully translated into German language (where not English labels used)  
  
**1) Concepts merged, URI voided, and preserved name as hiddenLabel:**  
natural hazard category => natural hazard  
composition chemistry category => chemical composition  
resource assessment category => resource assessment   
aquifer type => aquifer  
geophysical station type => geophysical station rank => geophysical station  
energy type => energy  
soil layer type => soil layer  
spatial data service type => spatial data service  
geographic processing services => spatial data service  
Pan-European Code for Reporting of Exploration Results, Mineral Resources and Reserves (PERC) => PERC Code  
freshwater => fresh water

**2) Concepts renamed, URI changed, and preserved name as hiddenLabel:**  
exposed element category => exposed element  
reserve assessment category => reserve assessment   
exploration activity type => exploration activity  
active well type => active well   
aquifer media type => aquifer media  
anthropogenic geomorphologic feature type => anthropogenic geomorphologic feature   
geologic unit type => geologic unit  
commodity type => commodity   
geophysical campaign type => geophysical campaign  
geophysical station type => geophysical station  
human health and safety consequence type => human health and safety consequence  
fossil fuel type => fossil fuel  
mining activity type => mining activity  
mineral occurence type => mineral occurence  
mineral exploration activity type => mineral exploration activity  
natural geomorphologic feature type => natural geomorphologic feature  
natural hydrogeological object type => natural hydrogeological object  
geological objects collection type => geological objects collection  
curve model type => curve model  
controlled activity type => controlled activity  
oil, gas and chemicals appurtenance type => oil, gas and chemicals appurtenance  
thermal appurtenance type => thermal appurtenance  
water appurtenance type => water appurtenance  
soil plot type => soil plot  
resource type => data resource  
Norwegian Petroleum Directorate classification (NPD-2001) => NPD-2001  
mmonazite => monazite  
  
**3) Concepts only renamed**  
resource type => data resource  
processing activity type => mining activity process  
classification of spatial data services => geographic processing services  
metadata codelist => metadata  
climate and climatic change => climate  
geographic processing services => spatial data service  
land use categories of Hierarchical INSPIRE Land Use Classification System => HILUCS  
categories of Hierarchical Supplementary Regulation Code List (HSRCL) => HSRCL  
United States Geological Survey => USGS classification  
HREE => heavy rare-earth elements  
LREE => light rare-earth elements  
geographic communication services => communication service  
geographic human interaction services => human interaction service  
geographic data-structure viewer => data-structure viewer  
geographic spreadsheet viewer => spreadsheet viewer  
geographic symbol editor => symbol editor  
geographic model/information management service => model and information management service  
geographic processing services – metadata => geographic processing service  
geographic workflow/task management services = > workflow and task management service  
geographic processing services – thematic => thematic processing service  
geographic processing services – temporal => temporal processing service  
geographic processing services – spatial => spatial processing service  
flow => flow (member)  
processing => geophysical processing  
measurement => geophysical measurement  
interpretation => geophysical interpretation   
  
**4) Concepts deleted without substitution**  
topic categories in accordance with EN ISO 19115  
  
**5) Concepts newly created**  
vocabulary  
thesaurus  
codelist  

**6) New skos:broader**  
chemical composition => chemical property  
natural gas, oil, .. extraction => extraction   
Search category "Information System" partly rearranged  
  
**7) New search category**  
not yet  

**8) Correction of "displaced" INSPIRE mappings for ..**  
alluvial plain, anthropogenic geomorphologic feature, artificial drainage, artificial levee, borehole logging, cave, cone penetration test, flight line, geophysical measurement, geophysical profile, geophysical station, geophysical swath, georadar profile, hydroelectric energy, Ludfordian, multi-electrode dc profile, pond, renewable energy source, reservoir lake, river basin, seismic line, valley, watershed  
  
**Correction of "displaced" GEMET mappings for ..**  
global warming, greenhouse effect, ozone layer depletion, sea level rise, climatic change, climate change adaptation, climate change mitigation, climate change impact  
  
**9) Removed remaining commas or slashes from URIs**  
http://resource.geolba.ac.at/geoera_keyword/oil,-gas-and-chemicals-network-node => http://resource.geolba.ac.at/geoera_keyword/oil-gas-and-chemicals-network-node
 
## version 2.0
**release notes (10.3.2020):**  
**1) new URIs according to new EGS domain name:**  
All keyword concepts have got new identifiers based on the new domain name **"data.geoscience.earth"** registered by EGS. URI patterns are adapted to the naming conventions of geoscience.earth host. E.g. for the keyword ***hazard*** the URI was changed from previous testing environment ***http://resource.geolba.ac.at/geoera_keyword/hazard*** to ***https://data.geoscience.earth/ncl/geoera/keyword/1358***. The previous URIs remain in the Keyword Thesaurus to query with property "http://purl.org/dc/terms/replaces". As soon as the Keyword Thesaurus is in the registry all URIs will be resolvable at data.geoscience.earth. Meanwhile and for testing purposes we provide a [Sparql endpoint](https://resource.geolba.ac.at/PoolParty/sparql/keyword) to query the data base (triple store).

**2) Fully translated into Slovenian, Spanish and German language:**  
Initially the Keyword Thesaurus is already available in 4 languages. In some cases, no translation was carried out. Especially for abbreviations in international context.

**3) All previous changes included:**  
The Keyword Thesaurus now contains all modifications as described under v1.1 above.








