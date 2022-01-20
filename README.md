# GAN-FS
This repo consists of the codes and datasets of the research paper, "[A GAN and Feature Selection-Based Oversampling Technique for
Intrusion Detection](https://www.hindawi.com/journals/scn/2021/9947059/)".
## Abstract :
In recent years, there have been numerous cyber security issues that have caused considerable damage to the society. The development of efficient and reliable Intrusion Detection Systems (IDSs) is an effective countermeasure against the growing cyber threats. In modern high-bandwidth, large-scale network environments, traditional IDSs suffer from a high rate of missed and false alarms. Researchers have introduced machine learning techniques into intrusion detection with good results. However, due to the scarcity of attack data, such methods’ training sets are usually unbalanced, affecting the analysis performance. In this paper, we survey and analyze the design principles and shortcomings of existing oversampling methods. Based on the findings, we take the perspective of imbalance and high dimensionality of datasets in the field of intrusion detection and propose an oversampling technique based on Generative Adversarial Networks (GAN) and feature selection. Specifically, we model the complex high-dimensional distribution of attacks based on Gradient Penalty Wasserstein GAN (WGAN-GP) to generate additional attack samples. We then select a subset of features representing the entire dataset based on analysis of variance, ultimately generating a rebalanced low-dimensional dataset for machine learning training. To evaluate the effectiveness of our proposal, we conducted experiments based on the NSL-KDD, UNSW-NB15, and CICIDS-2017 datasets. The experimental results show that our method can effectively improve the detection performance of machine learning models and  outperform the baselines.
## Keywords :
Intrusion detection, GAN, Feature selection, Unbalanced dataset, Oversampling
## Authors :
[Xiaodong Liu](https://orcid.org/0000-0002-5307-8165)<sup>1</sup>, Tong<sup>1,2</sup>, Zhang Runzi<sup>3,4</sup>, Di Wu<sup>1</sup>, Yongheng Liu<sup>1</sup>, Zhen Yang<sup>1,2</sup>  
<sup>1</sup>Faculty of Information Technology, Beijing University of Technology  
<sup>2</sup>Engineering Research Center of Intelligent Perception and Autonomous  Control, Ministry of Education  
<sup>3</sup>NSFOCUS Technologies Group Co., Ltd., Beijing, 100089  
<sup>4</sup>Department of Automation, Tsinghua University, Beijing, 100084  
## Usage
### Install packages
python-->3.8.3
keras-->2.3.1
### Generate attack samples
run generator.ipynb to generate attack samples
### Train & Test IDS
run GAN-FS.ipynb to build IDS with rebalanced dataset
### Baseline
run baseline.ipynb to  to compare baseline results
## Recommended Citation :
If you use this repository in your research, cite the the following papers :  
Xiaodong Liu, Tong Li, Runzi Zhang, Di Wu, Yongheng Liu, Zhen Yang, "A GAN and Feature Selection-Based Oversampling Technique for Intrusion Detection", Security and Communication Networks, vol. 2021, Article ID 9947059, 15 pages, 2021.
## Bibtex Format :
@article{liu2021gan,  
  title={A GAN and Feature Selection-Based Oversampling Technique for Intrusion Detection},  
  author={Liu, Xiaodong and Li, Tong and Zhang, Runzi and Wu, Di and Liu, Yongheng and Yang, Zhen},  
  journal={Security and Communication Networks},  
  volume={2021},  
  year={2021},  
  publisher={Hindawi}  
}
## Contact
e-mail: liuxiaodongpro@163.com
