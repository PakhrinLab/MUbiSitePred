# MMUbiPred
Multimodal deep learning for predicting protein ubiquitination sites

## Evaluate Model
Programs were executed using anaconda version: 2020.07, please use the same

The programs were developed in the following environment. python : 3.8.3.final.0, python-bits : 64, OS : Linux, OS-release : 5.8.0-38-generic, machine : x86_64, processor : x86_64, pandas : 1.0.5, numpy : 1.18.5, pip : 20.1.1, scipy : 1.4.1, scikit-learn : 0.23.1., keras : 2.4.3, tensorflow : 2.3.1.

Please place the Large_Dataset_Independent_Test_Set_Assessment.ipynb, aaindex31.txt, Positive_10_percent_independent_test_set_DeepUBI.fasta, Negative_10_percent_independent_test_set_DeepUBI.fasta, and DeepUBI_AAindex_One_Hot_Emb_drop_out2423.h5 in the same directory where you will execute the python program. Execute the Large_Dataset_Independent_Test_Set_Assessment.ipynb python program to obtain the reported result for general ubiquitination sites.

Please execute MMUbiPred_Comparision_with_Palistha_Shresthas_ubiquitination_ProtGPT2_finetuning_method.ipynb file all the data are uploaded in the github. It has thoroughly beaten ubiquitination predictor available at https://www.nature.com/articles/s41467-024-51071-9

Please place the Human_Dataset_Independent_Test_Set_Assessment.ipynb, aaindex31.txt, Ubiquitylation_81_window_Testing_positive.fasta, Ubiquitylation_81_window_Testing_negative.fasta, and DeepUBImodel_HubiPred_AAindex_One_Hot_Emb_drop_out_changed73887.h5 in the same directory where you will execute the python program. Execute the Human_Dataset_Independent_Test_Set_Assessment.ipynb python program to obtain the reported result for Human ubiquitination sites.

Please place the Plant_Dataset_Independent_Test_Set_Assessment.ipynb, aaindex31.txt, Positive_UbiCom_testing.fasta, Negative_UbiCom_testing.fasta, and UBICOMB_DeepUBI_AAindex_One_Hot_ProtT5_drop_out_Changed3257.h5 in the same directory where you will execute the python program. Execute the Plant_Dataset_Independent_Test_Set_Assessment.ipynb python program to obtain the reported result for plant ubiquitination sites.

*** All preliminary data and models required are uploaded at https://drive.google.com/drive/folders/1Bcx55mlv4FKqK2XVTww8XBaNqocnP71q?usp=sharing

If you need any futher help please contact Dr. Subash C. Pakhrin at pakhrins@uhd.edu.
