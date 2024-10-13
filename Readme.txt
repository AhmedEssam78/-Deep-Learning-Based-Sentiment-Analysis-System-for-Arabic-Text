Code files in a Python Notebook/Jupyter Notebook if possible. But, in all ways, a full working code must be submitted.
- https://drive.google.com/drive/folders/1sX32NSQMsuiRTzze-lbgt9M5KOuCRom9?usp=sharing

A list of all dependencies and installation instructions to get the code fully working. 
- Make sure to install the following lines to get the code fully working:
!pip install transformers==4.12.2
!pip install farasapy==0.0.14
!pip install pyarabic==0.6.14
!git clone https://github.com/aub-mind/arabert
!pip install emoji==1.6.1
!pip install sentencepiece==0.1.96
!pip install numpy torch transformers
!pip uninstall googletrans -y
!pip install googletrans==4.0.0rc1
!pip install torch


Data files, provide permanent links for huge datasets or upload the dataset directly to the submission form if tiny (less than 100 MB).
- We have 3 datasets that should be downloaded locally to your PC:
1) LABR_reviews.tsv
2) HARD_reviews.txt
3) Augmented_dataset.csv
- You should use the augmented dataset directly instead of taking 13 hours to re-run the code of data augmentation.

Your model weights, a permanent link if possible or upload it directly to the submission form if tiny (less than 1 GB).
- All of the model weightd are uploaded under the folder named 'output-dir'.