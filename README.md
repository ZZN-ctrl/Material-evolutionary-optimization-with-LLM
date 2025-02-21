# **Evolutionary Optimization**

1. HEA-dataset-12Dec2024-me.csv and refined_al-alloy-dataset-29Oct2024 are the input historical data of HEA and AL alloy.

2. AL.csv is the AL dataset ouput from evolutionary optimization

3. HEA.csv is the HEA dataset output from evolutionary optimization

4. Merged_Data.csv is the dataset after merging 


# **LLM evaluation**
1. LLM_coding_prompt1_HEA.txt is the *Coding and Prompt* for generating Knowledge book of HEA (Generate HEA_knowledge2_0.txt)

2. LLM_coding_prompt1_AL.txt is the *Coding and Prompt* for generating Knowledge book of AL (Generate AL_knowledge2_0.txt)

3. LLM_coding_pompt2_HEA.txt is *Coding and Prompt* for evaluate the candidate C1 of HEA (C1 is the expanded candidate training data introducted in LLM_iteration.ipynb)

4. LLM_coding_pompt2_AL.txt is *Coding and Prompt* for evaluate the candidate C2 of HEA (C2 is the expanded candidate training data introducted in LLM_iteration.ipynb)

5. LLM_coding_pompt3_HEA.txt is *Coding and Prompt* for updating knowledge book of HEA (Genertae HEA_knowledge2_1.txt-HEA_knowledge2_10.txt)

6. LLM_coding_pompt3_AL.txt is *Coding and Prompt* for updating knowledge book of AL (Genertae AL_knowledge2_1.txt-AL_knowledge2_10.txt)

7. LLM_coding_prompt4_evaluation.txt represents the LLM evaluation for the merged data. This document include the coding part and prompt string part

9. After density screening, the remaining solutions are evaluated by LLM and stored in reevaluate_output.csv, where the "YS UTS Elongation" values are predicted by LLM

10. Finally, the 20 selected solutions are recorded in Final_output.csv
