# Sea Level Rise and Human Wellbeing Evidence Map
Mével, G., Charlotte H. Chang, Yuta J. Masuda & Brian E. Robinson

## Supplementary Information
_File: "MSc_thesis_chap1_review_supp-info_v5.pdf"_

Contains additional graphs and tables referred to in the article, as well as the LLM prompts used.

## Database 1 - Publication metadata and geolocation
_File: "MSc_chap1_full-dataset_public_20260201.csv"_

Contains all the data used for analyses and graphs of the article. Rows describe the 5,584 papers included in the review. 

**ID_GM:** Unique ID for each publication. 

**authors:** Authors of the publication. 

**year:** Year of publication. 

**title:** Title of publication. 

**title_upper:** Simplified title to help exclude duplicate in the analysis. 

**abstract:** Abstract of publication, as provided by WoS or Scopus.

**journal:** Journal of publication. 

**DOI:** DOI of publication

**address_1st:** Address of the 1st author, as provided by WoS or Scopus. 

**AI_relevance**: Decision of LLM following relevancy classification. 

**from_search_XXXX:**: 4-letter code of the relationships that this publication touches on. *15 relationships exist between 3 hazards and 5 wellbeing dimensions.*

**nb_boxes_present:** Number of relationships this publication touches on. 

**X_paper:** Coastal hazards and human wellbeing dimensions touched on. _1 or 0_

**study_ISO:** ISO-2 code for the country where this study takes place. 

**study_SUBREGION:** Subregion where this study takes place. 

**study_CONTINENT:** Continent where this study takes place. 

**study_PART:** Part of the world (Global North or South) where this study takes place. 

**author_ISO:** ISO-2 code for the country where the 1st author is affiliated. 

**author_SUBREGION:** Subregion where the 1st author is affiliated. 

**author_CONTINENT:** Continent where the 1st author is affiliated. 

**author_PART:** Part of the world (Global North or South) where the 1st author is affiliated. 

**author_from_country:** Is the 1st author academically affiliated to the country where the study takes place?

**author_from_subregion:** Is the 1st author academically affiliated to the subregion where the study takes place?

**nb_authors:** Number of authors on this publication. 

**disciplines_wos:** Discipline.s of the journal in WoS Master Journal List. 

**language_original:** Original language of the publication. 

## Database 2 - SLR exposure vs number of publications
_File: "MSc_chap1_comparison_SLR-exposure_nb-papers_allcountries_public_20260209.csv"_

Contains the processed data of SLR exposure for each country. Based on Kulp, S. A., & Strauss, B. H. (2019). New elevation data triple estimates of global vulnerability to sea-level rise and coastal flooding. Nature Communications, 10(1), 4844. https://doi.org/10.1038/s41467-019-12808-z

**country:** Coastal country name.

**nb_papers_about:** Number of papers identified about this county in our evidence map. 

**nb_people_exposed_M:** Number of people, in millions, exposed to SLR in 2050 based on Kulp & Strauss, 2019. Model selected: Scenario K14, Coastal DEM, RCP 4.5, 2050, permanent inundation.

**noref_XXXX:** This country doesn't doesn't have a match between the evidence map dataset or in the SLR dataset from Kulp & Strauss. This can be because of two reasons. 1- (n=2) The country is located above 60°N, so the SLR model is undefined at this latitude. 2- (n=59) Because there are less than 0.01M people exposed in the model, therefore the number of people exposed is rounded up to 0. 

**SIDS:** Flags the 39 Small Island Developing States, as defined by the UN (https://www.un.org/ohrlls/content/list-sids).
