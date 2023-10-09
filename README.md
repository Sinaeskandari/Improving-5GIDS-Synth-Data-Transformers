# Improving-5GIDS-Synth-Data-Transformers

This is my final thesis for Bachelor's degree in IUST. I address the issue of class imbalance in the existing datasets. I mainly focus on the 5G-NIDD dataset. A conditional GAN model was used to generate data for the purpose of balancing the dataset.I used the FT-Transformer architecture for classification and managed to improve the performance on the dataset
compared to other methods.

## Abstract

In today's world, cyber attacks have become widespread and can have catastrophic consequences for organizations and individuals. This is especially true in the era of 5G development, where the expansion and prevalence of these networks make securing them critically important. Destructive activities often exploit vulnerabilities in the network, making the development of resilient security measures essential. Intrusion detection systems have been developed as a defense mechanism against these threats, designed to monitor and identify unauthorized accesses, abnormal behaviors, and various types of attacks. However, the effectiveness of these systems is heavily dependent on the quality and quantity of the available training data. Many existing datasets for attack detection suffer from the unbalance problem, where certain types of attacks are underrepresented, leading to biased models and reduced system performance.

The goal of this project is to address the unbalanced nature of the datasets using deep learning methods, particularly focusing on generative adversarial networks for synthetic data generation and transformer models for classification. The aim is to achieve higher accuracy in the classification problem. To tackle the unbalance issue in the dataset, a model called the generative adversarial model is designed and trained on the dataset.

This model is trained to capture the patterns and features of both majority and minority classes and balance the dataset accordingly.\\
The synthetic generated data is then added to the original dataset, and by leveraging modern transformer-based architectures, the classification accuracy is improved on the new training data. This approach aims to enhance the performance of the intrusion detection system and make it more resistant to cyber attacks.

Keywords: Network Intrusion Detection System, 5G network, Deep Learning, Generative Adversarial Networks, Transformer, Unbalanced Dataset
