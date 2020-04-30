# COVID-19

## Background
Coronavirus disease 2019 (COVID-19) has surprised the world since the beginning of 2020, and the rapid growth of COVID-19 is beyond the capability of doctors and hospitals that could deal in many areas. The chest computed tomography (CT) could be serve as an effective tool in detection of COVID-19. Its valuable to develop automatic detection of COVID-19.
## Material and Methods
The collected dataset consisted of 521 COVID-19 chest CT images, 397 normal chest CT images, 76 bacterial pneumonia chest CT images and 48 SARS chest CT images obtained by exhaustively searching available data on the Internet. Then, these data are divided into three sets, referred to training set, validation set and testing set. Sixteen data augmentation operations are designed to enrich the training set in deep learning training phase. Multiple experiments were conducted to analyze the performance of the model in the detection of COVID-19 both in case of no noisy labels and noisy labels. The performance was assessed by the area under the receiver operating characteristic (AUC), sensitivity, specificity and accuracy.
## Results
The data augmentation operations on the training set is effective for improvement of the model performance. The area under the receiver operating characteristic curve is 0.9689 with (95% CI: 0.9308, 1) in case of no noisy labels, while the per-exam sensitivity, specificity and accuracy for detecting COVID-19 in the independent testing set are 90.52%, 91.58% and 91.21%, respectively. Besides, the model is robust when part of the training samples is marked incorrectly. The AUC is 92.23% in the case of noisy labels of 10% in the training set.
## Conclusion
A deep learning model with insufficient samples can be developed by using data augmentation in assisting medical workers in making quick and correct diagnosis of COVID-19.
## Keywords
COVID-19 · Chest CT · Deep Learning · Data Augmentation · Noisy Labels
## Performance
We proposed a new COVID-19 diagnosis method by using CNN with ShuffleNet V2 as the backbone so as to efficiently distinguish the COVID-19 patients from those who are not infected or infected by other pneumonia (bacterial pneumonia or SARS). 

If you find our work useful, please ciet:

@Article{hu2020automated,

  author  = {Runwen Hu, Guanqi Ruan, Shijun Xiang, Minghui Huang, Qiaoyi Liang, Jingxuan Li},
  
  title   = {Automated Diagnosis of COVID-19 Using Deep Learning and Data Augmentation on Chest CT},
  
  journal = {medrxiv},
  
  year    = {2020},
  
}
