Clinical codes used to define cardiovascular diseases
For manuscript "Temporal trends and patterns in cardiovascular disease incidence. A population-based study in 22 million individuals."

For each condition, a list of diagnostic codes from was compiled to identify diagnoses based on the coding schemes in use in each data source (International Classification of Diseases, tenth revision (ICD-10) for diagnoses recorded in secondary care; ICD-9 (in use until 31/12/2000) and ICD-10 for diagnoses recorded on death certificates (used in sensitivity analyses only); UK Office of Population Census and Surveys classification (OPCS-4) for procedures performed in secondary care settings; and CPRD Aurum and CPRD Gold code dictionaries for primary care data, which include a combination of Read, SNOMED, and local EMIS codes.

These code lists are presented in the attached file "2024-01-19_CVD_incidence_diagnostic_codes_table_for_appendix.txt" on our GitHub repository (see https://github.com/nathalieconrad/CVD_incidence).  

Codes used in sensitivity analyses referring to broader disease definitions presented in Figure S3 are labelled accordingly.

*** IMPORTANT ****
CPRD strongly recommends that medcodes, prodcodes, SNOMED codes and any other long numeric identifiers are imported, stored, and processed as text rather than integers. In CPRD Aurum, unique identifiers such as these can be up to 19 digits in length. Standard software packages including R, Stata,
SPSS, and Excel are unable to store integers of this magnitude without loss of precision. In other words, these software packages will retain incorrect approximations if these unique identifiers are stored as integers. 