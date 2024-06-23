The objective is to automate Diabetic Retinopathy (DR) detection using color fundus photography, aiding early intervention and reducing healthcare burdens. Current solutions are manual, time-consuming, and resource-intensive. Framed as supervised offline learning, performance will be measured using accuracy, sensitivity, specificity, and AUC-ROC.

Success hinges on high model accuracy and sensitivity to prompt early intervention, with comparable tasks in image classification and medical diagnosis. Human expertise is available for data labeling and validation. Assumptions include accurate data labeling and generalizability to diverse populations.These assumptions will be verified through expert review and external dataset validation.

The dataset comprises high-resolution retina images captured under various imaging conditions, with each subject having both left and right fields. Images are labeled with subject IDs and side indicators (e.g., "1_left.jpeg" denotes the left eye of patient ID 1). Clinicians rated the presence of diabetic retinopathy on a scale of 0 to 4, with the distribution of labels as follows: {0: 25,810, 1: 2,443, 2: 5,292, 4: 708, 3: 873}. The task is to develop an automated analysis system to assign scores based on this scale. The dataset includes images from different models and cameras, potentially affecting visual appearance. Some images depict the retina anatomically, while others are inverted. Inverted images are identifiable by the position of the macula relative to the optic nerve or the presence of a notch. Noise may exist in both images and labels, necessitating the development of robust algorithms capable of functioning amid variation and noise.

A clinician has rated the presence of diabetic retinopathy in each image on a scale of 0 to 4, according to the following scale:

0 - No DR

1 - Mild

2 - Moderate

3 - Severe

4 - Proliferative DR
