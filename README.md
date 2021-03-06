# ML_Antibiotic_Protein_Peptide_binding
Machine Learning -based Method for Identification of Antibiotic Peptide Binding Pockets in Proteins

To build a machine learning based model for identification of Antibiotic Peptide binding pockets in proteins. There are many protein structures available but not all are functionally annotated so, this study aims at identifying the antibiotic therapeutic peptide binding pockets from other class of peptides using various machine learning models. As these therapeutic peptides are found to be advantageous over small molecules.
         
Specific aim:
   a) Collection of antibiotic & non-antibiotic(Cancer, Viral) peptides from Propedia database.
   b) Retrieving only residues that are within specified distance of 4Å from the peptides.
   c) Flagging and binning of residues specific to each pocket.
   d) Build a machine learning model for identifying native from non-native peptide class.
   e) Evaluate the model based on different metrics like accuracy, MCC.
   
Conclusion: 
The model build using machine learning based approach for identification of antibiotic peptide binding pockets in proteins is found to be robust with an
overall accuracy above 70% with RF outperforming all of the other models with an accuracy of 91% with a 10-fold MCC-CV of 91%.
