
[![DOI](https://zenodo.org/badge/915041148.svg)](https://doi.org/10.5281/zenodo.14630326)

# Description

This project takes as input one or more PubMed CSV exports, placed in the [data/pubmed/results/](data/pubmed/results/) directory. It adds useful columns to the CSV file, maps the PubMed IDs to Microsoft Academic Graph IDs, uses the MAGIDs to look up citation and disruption data from Wu et al., 2023 to score each article, and saves the scored output to a styled Excel spreadsheet.

### PubMed Search Documentation and Replication

The searches used to create the PubMed CSV exports are documented in [DisruptivePapersFetalSurgery-PubMedSearchDocumentation-202303.xlsx](data/pubmed/searches/DisruptivePapersFetalSurgery-PubMedSearchDocumentation-202303.xlsx). They cover Congenital Diaphragmatic Hernia (CDH), Congenital Pulmonary Airway Malfunction (CPAM), Neural Tube Defects (NTD), and Twin-to-Twin Transfusion Syndrome (TTTS), with each search documented on a separate spreadsheet tab.

The searches can be replicated by either copying and pasting the full search string from each spreadsheet tab into PubMed or clicking on the number in the Results column. Once replicated, the search results can be exported to CSV via the *Save* button. Select *All results* and *CSV* format, then click *Create file*. Re-running the searches should not be necessary unless the Small Teams group releases an update to the disruption dataset, which was last updated in 2021.

### References

Wu, L., Wang, D., & Evans, J. (2023). Replication Data for: Large teams develop and small teams disrupt science and technology [Data set]. Harvard Dataverse. <https://doi.org/10.7910/DVN/JPWNNK>
