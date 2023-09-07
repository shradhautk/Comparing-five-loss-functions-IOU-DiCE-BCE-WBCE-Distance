# Comparing-five-loss-functions-IOU-DiCE-BCE-WBCE-Distance

By utilizing this repository, individuals can determine the most effective loss function for accurately segmenting transmission electron microscopy images that contain material defects. More details on results that are obtained using this code could be found in my recent publication: 
Application of deep learning semantic segmentation model to helium bubbles and voids in nuclear materials, S. Agarwal, A. Sawant, M. Faisal, S. E. Copp, J. Reyes-Zacarias, Yan-Ru Lin, S. J. Zinkle. Engineering Applications of Artificial Intelligence 126, 106747.


These five script sets up an image segmentation model, trains it, evaluates the performance based on the particular loss function selected, and provides various visualization and metric calculation functions to assess the model's effectiveness in segmenting images.
The primary objective of this experiment is to compare and evaluate the performance of various loss functions in the context of semantic segmentation of helium cavities in electron microscopy images. 
Specifically, we aim to identify the most effective loss function for accurately segmenting these radiation-induced defects, which play a crucial role in determining the swelling value of nuclear materials. By assessing different loss functions, including Dice, Cross-entropy, Weighted Binary Cross Entropy (WBCE),
and Intersection over Union (IOU), we seek to identify the optimal approach to enhance the precision and reliability of the segmentation process, ultimately contributing to the safe operation of nuclear reactors and materials.

Some highlights of the results using this code from the paper mentioned above:
WBCE showed some issues with mask overlap and inaccuracies. Dice loss function outperformed others, achieving the highest precision, recall, IOU, and F1-score. However, Distance map-based loss function (DML) showed higher promise in improving object detection performance especially at the boundaries and created more precise masks, closely matching voids or bubbles. Please refer to the above paper for more details.


