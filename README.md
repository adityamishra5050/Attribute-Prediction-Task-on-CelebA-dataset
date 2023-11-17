# Attribute-Prediction-Task-on-CelebA-dataset

Perform Attribute Prediction Task on CelebA [1] dataset for the attributes available in the
dataset. For this task, use a VGG16/ResNet18 backbone and train your model in a Multi-Task
Learning fashion. Report the following:
1. Train the model for the prediction of 8 attributes out of 40 attributes and report the
following:
a. Mention your choice of attributes, backbone, and other parameters and the
reason behind your choice. 
b. Report task-wise accuracy. 
c. Report the overall accuracy.
2.Refer to the work of Malhotra et al. and report the following:
a. Drop rate for each task (any of the four metrics described
in the paper). 

b. Explanation step-by-step on how you computed the drop rate. 
c. Analyze your observations and discuss them in the report. 
d. Use your drop rate to calculate task-wise activation probability (since you are
using a single metric to calculate drop rate, task-wise activation probability can
be modified accordingly) and implement the DST algorithm and report the gain in
performance with your analysis.
