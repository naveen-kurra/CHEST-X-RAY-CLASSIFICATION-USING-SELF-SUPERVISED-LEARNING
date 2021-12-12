# CHEST-X-RAY-CLASSIFICATION-USING-SELF-SUPERVISED-LEARNING
Accepted in the below conference
International Conference on
RECENT TRENDS IN APPLIED SCIENCES & COMPUTING ENGINEERING
(RTASCE 2021)
//Scopus Indexed Journal//

  In recent times, models trained using an unsupervised learning mechanism called self-supervised learning has been performing on par with models trained with the help of supervised learning, where you don’t need a large labelled dataset to train a good model. In this paper, we show how models that are trained with self-supervised mechanism on large unlabeled Chest X-Ray images outperform models which are trained with the help of supervised transfer learning in the classification task.
  We have used SimCLR approach since it is very effective than other approaches proposed. So, we use SimCLR approach for the pretext task on the unlabeled chest x-ray images and for the downstream task, we have used the trained model to correctly classify normal vs abnormal chest x-rays containing pneumonia on two datasets that are relatively smaller.
  In general, our approach is divided into two parts. Firstly, we perform the pretext task, where a model learns useful representations from the unlabeled chest x-ray images. In this part, we employ the SimCLR based self-supervised learning methodology, where the images are split into different batches and each image in a batch is augmented with positive and negative pairs and the model learns to distinguish the positive and negative pairs.The main aim of self-supervised training using a pretext task is to make the model learn useful representations and features from the unlabeled data. This is done with the help of contrastive learning which tries to differentiate between similar and dissimilar images. It consists of three parts, data augmentation module, a projection head and a contrastive loss function
