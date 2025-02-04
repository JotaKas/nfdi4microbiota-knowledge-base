---
title: Data Reuse
category: Research-Data-Management
layout: default
docs_css: markdown
redirect_from: /Research-Data-Management
---

# Benefits and drawbacks

Making data reusable benefits researchers who publish their data, researchers who reuse data, and society. 

Researchers who publish their data see an increase in their scientific reputation, citations and collaborations {% cite rehwald_2022 pauls_2023 %}. In addition, researchers who publish their data not only comply with the [FAIR Data Principles](https://nfdi4microbiota.github.io/nfdi4microbiota-knowledge-base/Research-Data-Management/04-fair), but also avoid bias in the body of evidence {% cite IOM_2015 %}, increase transparency and thus trust in research {% cite engelhardt_2022 rehwald_2022 pauls_2023 %}. Finally, by sharing their resources and perspectives, researchers who publish their data enable other researchers to build on their work, accelerating scientific discovery {% cite engelhardt_2022 IOM_2015 rehwald_2022 %}.

Researchers can recycle unique data by performing secondary analyses to answer new research questions and/or with new methods {% cite rehwald_2022 pauls_2023 %}. Reusing data in this way saves resources such as time, energy and money {% cite engelhardt_2022 FSD rehwald_2022 pauls_2023 %}. Data reuse also increases collaboration and, over time, enables the comparison of different samples {% cite rehwald_2022 pauls_2023 %}. Indeed, data reuse is essential for interdisciplinary experiments and cross-cutting research approaches {% cite pavone_2020 %}.

Making data reusable can also benefit society. It reduces unnecessary experimentation {% cite rehwald_2022 %}, avoids duplication of data collection and minimises collection from hard-to-reach, vulnerable or over-researched populations {% cite FSD rehwald_2022 %}. It also enables replication and thus promotes reproducibility. Finally, it benefits teaching and improves the link between academia and industry {% cite rehwald_2022 %}.

As suggested by Sielemann *et al.* 2020 {% cite sielemann_2020 %}, there are also challenges, limitations and risks associated with data reuse.

For researchers who publish their data, preparing datasets for reuse is time-consuming. 

For researchers reusing data, there are risks such as unknown quality and denormalisation (i.e. "the same data is stored multiple times in the same database under different names/identifiers"). There is also the challenge of comparing and integrating datasets from different sources {% cite sielemann_2020 %}.

# Relevant licenses and terms of use
See [Licenses](https://nfdi4microbiota.github.io/nfdi4microbiota-knowledge-base/Research-Data-Management/26-licenses).

# Criteria for selection trustworthy datasets

Below is a list of criteria for selecting trustworthy datasets {% cite bres_2022 sielemann_2020 %}. As in Sielemann *et al.* 2020 {% cite sielemann_2020 %}, for each possible criterion, several questions to consider are listed.

* **Integrity of the source**
    * Is the source/submitter associated with data fabrication/plagiarism?
    * Is the way missing values handled documented?
 
* **Biases**
    * How was the data generated?
    * Is the data generation clearly and precisely documented?
  
* **Missing metainformation (sparsity)**
    * Do you have all relevant information?
    * Is the information understandable and consistent?
    
* **Integration of datasets from different sources**
    * Is the data comparable?
    * Are the methods used for data generation and analysis well documented and comparable?
    
* **Quality issues**
    * Is the quality high enough to reach your goals?
    * Are there any scores/hints available to check the quality of the dataset?
    
* **Copyright/Legal issues**
    * Are there any restrictions for reuse and publication of the data, especially due to the [Nagoya protocol](https://www.cbd.int/abs/)?
   
* **Further documentation**
    * Is the research purpose/(hypo-)thesis well documented?
    * Is it documented whether the data are raw or processed? 

# Data discovery

## Services to search for data

### Registries of data repositories
* Registry of Research Data Repositories ([re3data.org](https://www.re3data.org/))
* [OpenAIRE Explore](https://explore.openaire.eu/)
* [OpenDOAR](https://v2.sherpa.ac.uk/opendoar/)
* [FAIRsharing.org](https://fairsharing.org/)
* [Master Data Repository List](https://clarivate.com/webofsciencegroup/master-data-repository-list/)

### Search engines

* [NCBI Datasets](https://www.ncbi.nlm.nih.gov/datasets/)
* **Google**
    * [Dataset Search](https://datasetsearch.research.google.com/)
    * Keywork + "dataset"
* **Library search engines**
    * Bielefeld Academic Search Engine ([BASE](https://www.base-search.net/))
    * [LIVIVO – The Search Portal for Life Sciences](https://www.livivo.de/app)
* **Discipline-specific search engines**
    * Bacterial and Viral Bioinformatics Resource Center ([BV-BRC](https://www.bv-brc.org/))
    * [NFDI4Chem Search](https://search.nfdi4chem.de/)
    * [Study Hub NFDI4Health COVID-19](https://csh.nfdi4health.de/)
    * [TerrestrialMetagenomeDB](https://webapp.ufz.de/tmdb/)
* [Mendeley Data](https://data.mendeley.com/)

### (Meta)data aggregators
* [B2FIND](https://b2find.eudat.eu/)
* [data.europa.eu](https://data.europa.eu/en)
* [DataCite Commons](https://commons.datacite.org/)
* [gesisDataSearch](https://datasearch.gesis.org/start)

### Services where data can be published
* **Interdisciplinary and [discipline-specific](https://nfdi4microbiota.github.io/nfdi4microbiota-knowledge-base/Research-Data-Management/22-data-repositories) repositories**
* **Data reports**
* **Data journals** (see e.g. [here](https://www.forschungsdaten.org/index.php/Data_Journals))

## Strategies to search for data

The Consortium of European Social Science Data Archives (CESSDA) {% cite cessda_2017 %} has produced a list of steps in data discovery. The main ones are outlined below, and you can look at their [website](https://dmeg.cessda.eu/) for the sub-steps.
1. Develop a clear picture of the research data you need
2. Locate appropriate data resources
3. Set up a search query and search the data resource
4. Select data candidates
5. Evaluate data quality

CESSDA also suggests three steps to adjust your search strategy {% cite cessda_2017 %}:
1. Use appropriate words in appropriate fields
2. Broaden your scope
3. Narrow your scope

# Data citation

## Common standards for data citation

### Interdisciplinary
* **DataCite 2019**: Creator (PublicationYear): Title. Version. Publisher. (resourceTypeGeneral). Identifier
* **FORCE 11**: Author(s), Year, Data set title, Data repository or archive, Version, Global persistent identifier (preferably as link)
* [BibGuru](https://app.bibguru.com/p/3420f069-22ea-42f6-ba23-4bc6b8ae37e4)
* [DOI Citation Formatter](https://citation.crosscite.org/)
* [How to Cite Datasets and Link to Publications](https://www.dcc.ac.uk/guidance/how-guides/cite-datasets)

### For nucleic acid sequences and functional genomics
* [How do I cite my ArrayExpress data sets in my publication?](https://www.ebi.ac.uk/biostudies/arrayexpress/help#cite)
* [How to Cite Data in ENA](https://www.ebi.ac.uk/ena/browser/about/citing-ena)
* [Citing and linking to the GEO database](https://www.ncbi.nlm.nih.gov/geo/info/linking.html)
* [How do I cite NCBI services and databases?](https://support.nlm.nih.gov/knowledgebase/article/KA-03391/en-us)

## Code citation
Code citation allows for greater recognition of research software. Some major platforms and tools offer code citation: GitHub, GitLab, JabRef, Zenodo and Zotero {% cite escience_center_2021 %}.

# How-tos

## How to make your data reusable?
* Properly document your data with metadata {% cite pavone_2020 %}.
* Use common metadata standards and terminologies {% cite pavone_2020 %}.
* Standardise your data.
* Share your raw data with an open licence.

## How to maximise already existing data?
See Wood-Charlson *et al.* 2022 {% cite wood-charlson_2022 %}.

# References
{% bibliography --cited_in_order %}
