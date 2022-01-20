# GAN-FS
This repo consists of the codes and datasets of the research paper, "A GAN and Feature Selection-Based Oversampling Technique for
Intrusion Detection".
# Abstract :
In recent years, there have been numerous cyber security issues that have caused considerable damage to the society. The development of efficient and reliable Intrusion Detection Systems (IDSs) is an effective countermeasure against the growing cyber threats. In modern high-bandwidth, large-scale network environments, traditional IDSs suffer from a high rate of missed and false alarms. Researchers have introduced machine learning techniques into intrusion detection with good results. However, due to the scarcity of attack data, such methods’ training sets are usually unbalanced, affecting the analysis performance. In this paper, we survey and analyze the design principles and shortcomings of existing oversampling methods. Based on the findings, we take the perspective of imbalance and high dimensionality of datasets in the field of intrusion detection and propose an oversampling technique based on Generative Adversarial Networks (GAN) and feature selection. Specifically, we model the complex high-dimensional distribution of attacks based on Gradient Penalty Wasserstein GAN (WGAN-GP) to generate additional attack samples. We then select a subset of features representing the entire dataset based on analysis of variance, ultimately generating a rebalanced low-dimensional dataset for machine learning training. To evaluate the effectiveness of our proposal, we conducted experiments based on the NSL-KDD, UNSW-NB15, and CICIDS-2017 datasets. The experimental results show that our method can effectively improve the detection performance of machine learning models and  outperform the baselines.
# Keywords :
Intrusion detection, GAN, Feature selection, Unbalanced dataset, Oversampling
# Authors :
Xiaodong Liu<sup>1</sup>, Tong<sup>1,2</sup>, Zhang Runzi<sup>3,4</sup>, Di Wu<sup>1</sup>, Yongheng Liu<sup>1</sup>, Zhen Yang<sup>1,2</sup>
<sup>1</sup>Faculty of Information Technology, Beijing University of Technology
<sup>2</sup>Engineering Research Center of Intelligent Perception and Autonomous  Control, Ministry of Education
<sup>3</sup>NSFOCUS Technologies Group Co., Ltd., Beijing, 100089
<sup>4</sup>Department of Automation, Tsinghua University, Beijing, 100084
