### Dataset:
The Antibiotic Resistance Microbiology Dataset (ARMD)
(doi.org/10.5061/dryad.jq2bvq8kp) [1].

### Objective:
The aim of this exploratory data analysis is to identify patterns of antimicrobial resistance across selected organisms, culture types, and antibiotic susceptibility profiles. A particular challenge of this dataset is the ambiguity of patient demographics. This dataset contains clinical information from real patient data, and was collected using electronic health records from Stanford Healthcare. Demographic features have undergone thorough de-identification. Ages have been aggregated into bins of age ranges (e.g. 18- 24, 25-34, 35-44, etc.). Genders are labeled as binary classifiers (1 and 0), without indicating which value corresponds to male or female. For the context of this EDA, demographics will not be used to form causal associations.

### Specific questions to address:
1) Which organisms show the highest resistance rates?
2) What are the resistance profiles of specific antibiotics across selected organisms with high clinical relevance?
3) What proportion of selected organisms are present across sample types (urine, blood, respiratory)?

### Dataset Reference: Version Oct 22, 2025
[1] Nateghi Haredasht, Fateme; Amrollahi, Fatemeh; Maddali, Manoj et al. (2025). Antibiotic
Resistance Microbiology Dataset (ARMD): A resource for antimicrobial resistance from EHRs
[Dataset]. Dryad. https://doi.org/10.5061/dryad.jq2bvq8kp

### Sub-datasets:
`demographics.csv`: Includes patient demographic information at the time of the culture order.

`adi_scores.csv`: Contains Area Deprivation Index (ADI) data mapped to cohort ZIP codes (the ZIP codes were removed from this dataset for patient de-identification).

`cohort.csv`: Contains primary information about microbiological cultures, including culture type, organism identified, and antibiotic susceptibility.

`resistance.csv`: Contains data on microbial resistance and the timeline of resistance development.
