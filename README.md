# Genomics Hackathon 2024

## Update after Hackathon

We are making available testing data with labels: https://github.com/BioGeMT/DLforGenomics/raw/main/data/Hejret_2023/miRNA_test_set_10_label.tsv

Feel free to use this data to evaluate your models. The evaluation metric is the area under the precision-recall curve (look at see sklearn.metrics.auc and sklearn.metrics.precision_recall_curve).

If you have a new solution, especially with area under the precision-recall curve above 0.661, let us know.

## Description

Training data: https://github.com/BioGeMT/DLforGenomics/raw/main/data/Hejret_2023/miRNA_train_set.tsv

Testing data: https://github.com/BioGeMT/DLforGenomics/raw/main/data/Hejret_2023/miRNA_test_set_10.tsv

Submission:
- Add a new column to the file miRNA_test_set_10.tsv
- Name of column = name of your solution
- Values = your predictions (ideally in the range from 0 to 1)
- Sent the file to the address: biogemt@um.edu.mt 
- Subject: Genomics Hackathon
- Deadline: 12.6.2024 23:59

Evaluation metrics:
- The area under the precision-recall curve (see sklearn.metrics.auc and sklearn.metrics.precision_recall_curve) 

Result announcements:
- The best solution will be awarded a prize on Friday 14th at 11:00
- Several best solutions will be invited to give a short presentation on Friday 14th at 11:00


# Deep Learning for Genomics

## Program

### Day 1
- Introduction to Machine Learning - linear regression, perceptron, CNNs
- Hands-on: Computing k-mers and using ML classifier

### Day 2
- Hands-on: One-hot-encoding and 1D convolution
- Hands-on: One-hot-encoding and RNN/LSTM
- Hands-on: 2D-binding matrix and 2D convolution

### Day 3
- Hands-on: Transfer Learning
- Hands-on: Interpreting 2D CNN on miRNA binding site data

## Additional Resources

Where to go next:
- (perfect for explaining ML basics) StatQuest!!! https://statquest.org/
- (perfect for beginners eager to use ML in biology) MIT course Computational Systems Biology: Deep Learning in the Life Sciences https://mit6874.github.io/
- (slightly more advanced) Yannic Kilcher’s channel explaining various DL papers: https://www.youtube.com/channel/UCZHmQk67mSJgfCCTn7xBfew
- (perfect for beginners to quickly run some code) TensorFlow tutorials: https://www.tensorflow.org/tutorials/keras/classification
- (deep dive into interpretation techniques) Interpretable Machine Learning https://christophm.github.io/interpretable-ml-book/
