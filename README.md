# Identification of Genetic Interaction Related to Ovarian Cancer Chemoresistance

This repository contains code used to generate the results in Identification of Genetic Interaction Related to Ovarian Cancer Chemoresistance.

## Main Idea
This paper investigates the genetic interaction (GI) related to ovarian cancer (OCa) chemoresistance (CR). To decrease the complexity of establishing gene networks, individual signature genes related to OCa-CR are identified using a gradient boosting decision tree (GBDT) algorithm. Additionally, the genetic interaction coefficient (GIC) is proposed for further identification of the signature gene pairs on OCa-CR. Totally 24 signature gene pairs are selected that include 10 individual signature genes using data from the Cancer Genome Atlas (TCGA). Then the influence of signature gene pairs on OCa-CR is explored. Finally, a signature gene pair based prediction of OCa-CR is identified. The area under the curve (AUC) result reaches 0.9658, while the AUC of individual signature gene-based prediction is only 0.6823. This improvement shows that our proposed method is a useful tool to investigate GI related to OCa-CR.

## Repository Structure
* **TCGA data cleaning.ipynb**: Clean and merge gene expression level, gene name and PFS data
* **Identification of individual signature genes and prediction results.ipynb**: Split training set and test set, apply GBDT to identify individual signature genes and present their prediction results 
* **Identification of signature gene pairs and prediction results.ipynb** Use genetic interaction coefficient (GIC) to identify signature gene pairs and present their prediction results
