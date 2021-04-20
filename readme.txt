This documentation accompanies Stata do files that read IPUMS ATUS data, identify "additional" same-sex couples in the American Time Use Survey, and replicate analyses in "A Research Note Describing a More Inclusive Approach to Identifying Same-Sex Cohabiters in the American Time Use Survey", authored by Sarah Flood and Katie Genadek.

This code refers to data downloaded from IPUMS ATUS (www.atusdata.org). The paper includes 2003-2019 ATUS data for all ATUS respondents and members of their households. Variables required to replicate the analyses are listed in 

atusx_extracts/

The code assumes the following directory structure:

/atusx_extracts
/data
/logs
/tables2
a_run_ipums_extract.txt
b_recode_pvars.txt
c_link_partner_who_and_act_records.txt
d_descriptives.txt


