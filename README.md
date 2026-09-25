# Functional-Connectivity-SEEG-Epilepsy
Dataset, reference list (RIS) for the systematic review- "Stereoelectroencephalography-Based Functional Connectivity in Drug-Resistant Epilepsy: A Systematic Review of Methods, Reporting Standards, and Clinical Utility " can be found here

## Included Studies (`included_studies.ris`)

This repository includes a RIS file listing the 61 studies included in the
review. These are the papers that passed full-text screening and were used
for data extraction, figures and tables.

**Contents:** bibliographic records (authors, title, journal, year, DOI,
abstract where available) for each included study.

**How to use it:**
- Import it into a reference manager (Zotero, EndNote, Mendeley) with
  *File → Import*.
- It can also be loaded into screening tools such as Rayyan or Covidence, or
  read in Python/R (e.g., `rispy` or `revtools`) for further analysis.

**Notes:**
- Records were exported from Scopus, Pubmed, and Web of Science between
  Jan2010 to Dec2025
- The search strategy used was:
  
        (Functional AND Connectivity) AND ((Intracranial AND EEG) OR (iEEG) OR (stereo AND electroencephalography) OR (SEEG))
  
- The databases searched and the full search strategy are
  described in the Methods section of the manuscript.
- Study-level extracted data are in `tables.xlsx`.
