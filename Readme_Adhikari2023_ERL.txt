Title: Data for 'Nature's contributions to people and the Sustainable Development Goals in Nepal'

Recommended Citation: Adhikari, B., Prescott, G., Urbach, D., Chettri, N., & Fischer, M. (2022). Nature’s contributions to people and the sustainable development goals in Nepal. Environmental Research Letters. https://doi.org/10.1088/1748-9326/ac8e1e

Principal Investigator: Markus Fischer (markus.fischer@ips.unibe.ch)

Authors:
Biraj Adhikari (biraj.adhikari@ips.unibe.ch, ORCID: 0000-0002-4260-8706)
Graham W Prescott (graham.prescott.research@gmail.com, ORCID:0000-0001-5123-514X)
Davnah Urbach (davnah.payne@ips.unibe.ch, ORCID: 0000-0001-9170-7834)
Nakul Chettri (nakul.chettri@icimod.org, ORCID: 0000-0002-3338-8879)
Markus Fischer (markus.fischer@ips.unibe.ch, ORCID: 0000-0002-5589-5900)

Date of data collection: November 2020 - August 2021
Location of data collection: Kathmandu, Nepal
Date of final release: 

Data Overview:
This repository contains data relevant to a literature review on the state of research on Nature's Contributions to People (NCPs) in Nepal, the trends and drivers of change of NCPs, and the linkages of the NCPs to the Sustainable Development Goals (SDGs). It contains 4 .csv files (data), and one .rmd file which contains script for all figures 3, 5, 6 and 7 used in the manuscript.
Data Overview:

ForFig3_ResearchTrends_Methods:
We used this .csv file to make Figure 3 of the manuscript. It contains information on title, first author, year and method used in analysis of the 140 articles we analyzed in this study. The "SN" column is the reference ID of each article used in the manuscript, and is used in subsequent files as well. 
The "Authors" column is the name of the first or the first and second authors (in case where only 2 authors) of the paper we analyzed. The "Title" column is the title of the paper we analyzed.The "Year" column is the year the paper was published. The "Method" column is the method applied by the paper to analyze NCP, classified into Socio-cultural, Monetary, and Biophysical, as per Harrisson et al. (2018).

ForFig5_6_DriversTrends.csv:
We used this .csv file to make the stacked bar charts of Figure 5 and Figure 6 of the manuscript. 
The "SN Ref" column is the reference ID of the article, which can be checked in the .csv file described above.
The "Quote" column is the text from papers which has information on (i) trends in ecosystems or NCPs, and if available (ii) direct and/or indirect drivers causing the trends.
The "Nature" column indicates which ecosystem (Forest, Farmland, Freshwater, Grassland, Others, and Directly to NCP), the "NCP" column indicates which NCP (categorized into 18 categories based on the IPBES classification) the text refers to. The "NCP Category" column indicates whether the said NCP is a regulating, material or non-material NCP.   
We also categorized direct and indirect drivers based on the IPBES classification (Direct Drivers: Land-use Change, Climate Change, Direct Exploitation, Invasive Alien Species, and Pollution; Indirect Drivers: Institutions and Governance, Demographic and Sociocultural, Economic and Technological).	
If there were more than one drivers of change for a particular NCP, we have included them in additional columns. In order to avoid multiple counts for trends of a particular NCP, we introduced the "TrendCount" column. For example, columns 3, 4 and 5 refers to the same trend of decreasing WQN, but has 3 Direct Drivers. Therefore, each TrendCount is given a weight of 0.33 so that the total trend adds upto 1.

ForFig5_NCPCount.csv:
We used this .csv file to make the line chart of Figure 5
The "SN Ref" column is the reference ID of the article, which can be checked in the first .csv file described above.
Each column indicates an NCP, and each cell of a row denotes whether that NCP was analyzed (1) or not (0). The last row is the total number of occurrences of each NCP.

ForFig7_NCPSDGLinkages.csv:
We used this .csv file to make Figure 7.
The "SN Ref" column is the reference ID of the article, which can be checked in the first .csv file described above.
The "Quote" Column is the text from papers which has information on which NCP is contributing towards which SDG. "Remarks from text" are the authors' own remarks based on the text and the overall context of the article. 
The contribution of NCPs are classified as positive or negative, and indicated in the column "Effect (pos/neg)"
The "NCP" column indicates which NCP (categorized into 18 categories according to IPBES) the text refers to, while the "Contribution to SDG" column indicates which SDG the NCP is contributing towards.
The "Ecosystem" column indicates which ecosystem (Forest, Farmland, Freshwater, Agroforest, Grassland, Others) the NCP is being supplied from. 

Codes for NCPS:
HAB (Habitat Creation and Maintenance), POL (Pollination and dispersal of seeds and other propagules), AIR (Regulation of Air Quality), CLI (Regulation of Climate), WQN (Regulation of Freshwater Quantity, Location, and Timing), WQL (Regulation of Freshwater and Coastal Water Quality), SOI (Formation, Protection, and Decontamination of Soils and Sediments), HAZ (Regulation of Hazards and Extreme Events), ORG (Regulation of Organisms Detrimental to Humans), NRG (Energy), FOD (Food and Feed), MAT (Materials and Assistance), MED (Medicinal, Biochemical, and Genetic Resources), INS (Learning and Inspiration), EXP (Physical and Psychological Experiences), IDE (Supporting Identities), and OPT (Maintenance of Options).
  
References:
Harrison P A et al 2018 Selecting methods for ecosystem service assessment: a decision tree approach Ecosyst. Serv. 29 481–98
IPBES 2019 Global Assessment Report of the Intergovernmental Science-Policy Platform on Biodiversity and Ecosystem Services

