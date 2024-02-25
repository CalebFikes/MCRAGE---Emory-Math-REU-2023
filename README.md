# Fair-Health-AI
Contributors:
Keira Behal, Alina Chen, Caleb Fikes, Sophia Xiao
Advisor: Xi Yunazhe
We would also like to acknowledge Huan He and Tianshi Xu for their collaboration and insight.

Work for this project was produced during the Emory Math Department's "Data for Social Justice REU" in the summer of 2023. More information on this project/program can be found here:
https://www.math.emory.edu/site/cmds-reuret/projects/2023-ai-for-healthcare/

This work is sponsored by NSF DMS 2051019.

## Abstract
In the field of healthcare, electronic health records (EHR) serve as crucial training data for developing machine learning models for diagnosis, treatment, and the management of healthcare resources. However, medical datasets are often imbalanced in terms of sensitive attributes such as race/ethnicity, gender, and age. Machine learning models trained on class-imbalanced EHR datasets perform significantly worse in deployment for individuals of the minority classes compared to samples from majority classes, which may lead to inequitable healthcare outcomes for minority groups. To address this challenge, we propose Minority Class Rebalancing through Augmentation by Generative modeling (MCRAGE), a novel approach to augment imbalanced datasets using samples generated by a deep generative model. The MCRAGE process involves training a Conditional Denoising Diffusion Probabilistic Model (CDDPM) capable of generating high-quality synthetic EHR samples from underrepresented classes. We use this synthetic data to augment the existing imbalanced dataset, thereby achieving a more balanced distribution across all classes, which can be used to train an unbiased machine learning model. We measure the performance of MCRAGE versus alternative approaches using Accuracy, F1 score and AUROC.

## Arxiv Link
https://arxiv.org/abs/2310.18430
