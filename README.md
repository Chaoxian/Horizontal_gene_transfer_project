# Horizontal_gene_transfer_project
Three python scripts are wrote for inferring HGT event. Parse_blast_result.py will be used to parse blastp result based on HGT AI, HGT Index, as well as HGT Identify. 
HGT AI = best_hit_Evalue_in_A_database + 1e-180) - log(best_hit_Evalue_in_B_database + 1e-180); HGT Index = best_hit_Score_in_A_database - best_hit_Score_in_B_database; HGT Identify = best_hit_Identify_in_A_database - best_hit_Identify_in_B_database
