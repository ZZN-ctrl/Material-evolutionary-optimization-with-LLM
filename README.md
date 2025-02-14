1. AL.csv is the AL dataset ouput from evolutionary optimization

2. HEA.csv is the HEA dataset output from evolutionary optimization

3. Merged_Data.csv is the dataset after merging 

4. LLM_coding_prompt_step2_HEA.txt & LLM_coding_prompt_step2_AL.txt use the training data of HEA (K1) and Al (K2) to generate K3 and K4. This two txt documents include the coding part, the prompt string part and K3, K4

5. LLM_coding_prompt_step3_evaluation.txt represents the LLM evaluation for the merged data. This document include the coding part and prompt string part

6. The output after LLM evaluation for experiments is recorded in Final_output.csv, where the "YS UTS Elongation" values are predicted by LLM
