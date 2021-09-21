# i6mA-CNN: Identifying DNA N6-Methyladenine Sites in Mice using CNN with Multiple Kernel Sizes


#### T-H Nguyen-Vo, Q. H. Trinh, L. Nguyen, P-U. Nguyen-Hoang, [S. Rahardja](http://www.susantorahardja.com/)*, [B. P. Nguyen](https://homepages.ecs.vuw.ac.nz/~nguyenb5/about.html)∗

![alt text](https://github.com/mldlproject/2022-i6mA-CNN/blob/main/i6mA_CNN_abs0.svg)

## Motivation
N6-methyladenine (6mA) is one of the widespread epigenetic modifications that commonly occur in DNA sequences of both eukaryotes and prokaryotes. At the N6-methyladenine sites, 
the catalysis of adenine methylation reactions is controlled by methyltransferase attaching a methyl group to the sixth position of the adenine’s purine cyclic structure. 
In prokaryotes, N6-methyladenine was demonstrated to be closely associated with various biochemical processes such as DNA replication, repair, transcription, and cellular 
defense. Unlike RNA 6mA, the understandings of DNA 6mA’s roles and behaviors are relatively inadequate, especially in eukaryotes. Hence, identifying the N6-methyladenine site 
is highly essential to not only partially reveal its biological functions but also to gain more insights into 6mA. The sequence samples were retrieved from the MethSMRT 
Database and then refined to create a benchmark dataset. The sequence samples are of Mus musculus (mice) species. In this study, we propose i6mA-CNN, an more effective computational
model to predict N6-methyladenine sites in DNA sequences using convolutional neural networks with multiple kernel sizes and one-hot encoding. 



## Results
Results on the indenepdent test set shows that i6mA-CNN is an effective, stable, and robust prediction model for recognizing N6-methyladenine sites in DNA sequences of mice. 
i6mA-CNN achieves both AUC-ROC and AUC-PR values of 0.98 for prediction tasks on standard sequence samples and AUC-ROC of about 0.50 and AUC-PR of up to 0.51 for 
prediction tasks on non-standard sequence samples. Besides, comparative analysis on model performance confirms our method is a better prediction model compared to other state-of-the-art methods.


## Availability and implementation
Source code and data are available upon request. 

## Web-based Application
[Click here](http://13.238.182.15:888/) (Being implemented)

## Contact 
[Go to contact information](https://homepages.ecs.vuw.ac.nz/~nguyenb5/contact.html)
