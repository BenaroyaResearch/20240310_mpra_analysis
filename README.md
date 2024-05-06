# 20240310_mpra_analysis

This is the most up to date replication analysis of Mouri et al. and there are multiple other small projects in here as well. 

The main folder architecture is that you take a results table from primary data (ex. OLJR.C_Tcell_emVAR_glm_20240310.out) and plug it into the 20240310_mpra_merge_creation.Rmd. This creates the MPRA merge table in hg19 which you then plug into 20240310_mpra_hg_19_to_38.Rmd. This generates a hg19, hg38 and a hg19&38 table. Then plug those tables into 20240310_mouri_et_al_replication_code_in_line.Rmd and generate the MPRA plots. Based on the plots_dir you put in the code. 

Side projects to find MPRA variant enrichment in fine mapping data:

1. eqtl_enrichment

2. PICS2

3. UK_biobank_finemapping_enrichment

