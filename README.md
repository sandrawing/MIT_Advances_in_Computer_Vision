## MIT Advances in Computer Vision

Final Project (Gain Full Mark, 40/40)

Deep Transfer Learning for Covid-19 Detection


Recent studies have shown that comprehending and mitigating the low clinical sensitivity of the 
SARS-CoV-2 RT-PCR testing is pivotal to the containment of the global coronavirus pandemic. 
In this paper, we propose a complementary method for rapid coronavirus detection from CT scans, 
based on the deep transfer learning paradigm. The idea is to use fine-tuning methods as a baseline, 
and to apply mapping-based and generative methods to enhance the transferability of knowledge and to improve 
the model performance on the Covid-19 detection task. As for the fine-tuning method, the VGG architecture performs 
the best, achieving an accuracy 75.83\%, an F-1 score of 76.68\% and an AUC of 83.95\%. 
The mapping-based method is used to predict correct labels while keeping the domain invariant. 
Applying our selected domain confusion metric on the ResNet50 model, the method achieves an accuracy of 80.00\%, 
an F1-score of 80.93\% and an AUC of 86.29\%, outperforming the baseline strongly. The generative methods are 
used to alleviate the training data scarcity issue, associated with the fine-tuning methods. The VGG architecture 
fine-tuned on the updated dataset with generative and affine augmentations had an accuracy of 78.31\%, an 
F-1 score of 80.45\% and an AUC of 85.39\%. The results indicate that both proposed methods outperform the baseline and 
thus bring closer the idea of using deep transfer learning on CT scans as a complementary method for rapid Covid-19 detection.
