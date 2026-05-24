# Thesis_AthayaKyla
This repository consists of all the code for the MSc thesis *Shrink to Protect: A comparatie Study of TinyML Compression Techniques for On-Device Android Malware Detection*. This thesis looks into whether TinyML compression techniques, namely quantization, pruning, and knowledge distillation, can preserve classification performance under deployment constraints using Random Forest, Multilayer perceptron, and XGBoost on the CCCS-CIC-AndMal-2020 Dataset. The static features used in this thesis were sourced from a cleaned version available on Kaggle, and the duplicate entries and inconsistent samples had been removed. 

The dataset are not included in this repository because of its size. Attach is the link to both sources separately and place them in a data folder before running the notebooks. 

**Download from official site:** https://www.unb.ca/cic/datasets/andmal2020.html
**Download clean dataset:** https://www.kaggle.com/code/dhoogla/cccs-cic-andmal2020-00-cleaning-static

##Notebooks 
Notebooks : 
RQ1_final_clean : baseline model across 30 seeds 
RQ2_30seeds : Research Question 2,3, and 4 across 30 seeds 

result: presented in a CSV file
