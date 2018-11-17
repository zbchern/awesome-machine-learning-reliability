# Awesome Machine Learning Reliability [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![Awesome Machine Learning On Source Code](img/adversarial_example.png)
> ###### <p align="right"> *Figure from "[Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572)" by Goodfellow et al. ICLR15*</p>

A curated list of awesome papers regarding machine learning reliability, inspired by [Awesome Computer Vision](https://github.com/jbhuang0604/awesome-computer-vision) and [Awesome Adversarial Machine Learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning).

## Computer Vision

### Benchmarking
* [ICLR19_Submission] [Benchmarking Neural Network Robustness to Common Corruptions and Perturbations](https://openreview.net/forum?id=HJz6tiCqYm) - Anonymous Authors.
 
### Attack

#### Classification
* [ICML18] [Obfuscated Gradients Give a False Sense of Security: Circumventing Defenses to Adversarial Examples](https://nicholas.carlini.com/papers/2018_icml_obfuscatedgradients.pdf) - Anish Athalye*, Nicholas Carlini*, and David Wagner. [[code]](https://github.com/anishathalye/obfuscated-gradients) [[talk]](https://nicholas.carlini.com/talks/2018_icml_obfuscatedgradients.mp4)
* [S&P17] [Towards Evaluating the Robustness of Neural Networks](https://nicholas.carlini.com/papers/2017_sp_nnrobustattacks.pdf) - Nicholas Carlini and David Wagner. [[talk]](https://www.youtube.com/watch?v=yIXNL88JBWQ)
* [ICLR15] [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572) - Ian J. Goodfellow, Jonathon Shlens, and Christian Szegedy.

#### Other CV Tasks
* [IJCAI17] [Tactics of Adversarial Attack on Deep Reinforcement Learning Agents](https://arxiv.org/abs/1703.06748) - Yen-Chen Lin, Zhang-Wei Hong, Yuan-Hong Liao, Meng-Li Shih, Ming-Yu Liu, and Min Sun.

#### Real-World Attack
* [CVPR18] [Robust Physical-World Attacks on Deep Learning Models](https://arxiv.org/abs/1707.08945) - Kevin Eykholt, Ivan Evtimov, Earlence Fernandes, Bo Li, Amir Rahmati, Chaowei Xiao, Atul Prakash, Tadayoshi Kohno, and Dawn Song.

### Defense

#### Adversarial Training

* [ICLR18] [Towards Deep Learning Models Resistant to Adversarial Attacks](https://arxiv.org/abs/1706.06083) - Aleksander Madry, Aleksandar Makelov, Ludwig Schmidt, Dimitris Tsipras, and Adrian Vladu. [[code (mnist)]](https://github.com/MadryLab/mnist_challenge) [[code (cifar10)]](https://github.com/MadryLab/cifar10_challenge)
* [ICLR18] [Generating Natural Adversarial Examples](https://arxiv.org/abs/1710.11342) - Zhengli Zhao, Dheeru Dua, Sameer Singh

#### Detection

* [NIPS18] [Attacks Meet Interpretability: Attribute-steered Detection of Adversarial Samples](https://arxiv.org/abs/1810.11580) - Guanhong Tao, Shiqing Ma, Yingqi Liu, and Xiangyu Zhang.

#### Model Compression

* [IEEE S&P16] [Distillation as a Defense to Adversarial Perturbations against Deep Neural Networks](https://arxiv.org/abs/1511.04508) - Nicolas Papernot, Patrick McDaniel, Xi Wu, Somesh Jha, and Ananthram Swami.


## Natural Language Processing and Speech
* [Arxiv18] [Identifying and Controlling Important Neurons in Neural Machine Translation](https://arxiv.org/abs/1811.01157) - Anthony Bau, Yonatan Belinkov, Hassan Sajjad, Nadir Durrani, Fahim Dalvi, and James Glass.
* [Arxiv18] [Robust Neural Machine Translation with Joint Textual and Phonetic Embedding](https://arxiv.org/abs/1810.06729) - Hairong Liu, Mingbo Ma, Liang Huang, Hao Xiong, Zhongjun He.
* [Arxiv18] [Improving the Robustness of Speech Translation](https://arxiv.org/abs/1811.00728) - Xiang Li, Haiyang Xue, Wei Chen, Yang Liu, Yang Feng, Qun Liu.
* [ICLR18] [Synthetic and Natural Noise Both Break Neural Machine Translation](https://arxiv.org/abs/1711.02173) - Yonatan Belinkov and Yonatan Bisk.
* [ACL18] [Towards Robust Neural Machine Translation](http://aclweb.org/anthology/P18-1163) - Yong Cheng, Zhaopeng Tu, Fandong Meng, Junjie Zhai, and Yang Liu.
* [ACL18] [Did the Model Understand the Question?](https://arxiv.org/abs/1805.054923) - Pramod Kaushik Mudrakarta, Ankur Taly, Mukund Sundararajan, and Kedar Dhamdhere.
* [ACL18] [Trick Me If You Can: Adversarial Writing of Trivia Challenge Questions [Student Research Workshop]](http://aclweb.org/anthology/P18-3018) - Eric Wallace, Jordan Boyd-Graber.
* [EMNLP18] [Generating natural language adversarial examples](https://arxiv.org/abs/1804.07998) - Moustafa Alzantot, Yash Sharma, Ahmed Elgohary, Bo-Jhang Ho, Mani Srivastava, Kai-Wei Chang.
* [NAACL18] [Adversarial Example Generation with Syntactically Controlled Paraphrase Networks](http://aclweb.org/anthology/N18-1170) - Mohit Iyyer, John Wieting, Kevin Gimpel, Luke Zettlemoyer 
* [COLING18] [On Adversarial Examples for Character-Level Neural Machine Translation](http://aclweb.org/anthology/C18-1055) - Javid Ebrahimi, Daniel Lowd, Dejing Dou
* [ICLR17] [Adversarial Training Methods for Semi-Supervised Text Classification](https://arxiv.org/abs/1605.07725) - Takeru Miyato, Andrew M. Dai, and Ian Goodfellow.
* [EMNLP17] [Adversarial Examples for Evaluating Reading Comprehension Systems](https://arxiv.org/abs/1707.07328) - Robin Jia and Percy Liang.
* [CSAW16] [Hidden Voice Commands](https://nicholas.carlini.com/papers/2016_usenix_hiddenvoicecommands.pdf) - Nicholas Carlini, Pratyush Mishra, Tavish Vaidya, Yuankai Zhang, Micah Sherr, Clay Shields, David Wagner, and Wenchao Zhou. [[talk]](https://www.usenix.org/conference/usenixsecurity16/technical-sessions/presentation/carlini)


## Testing
* [FSE18] [MODE: Automated Neural Network Model Debugging via State Differential Analysis and Input Selection](https://www.cs.purdue.edu/homes/ma229/papers/FSE18.pdf) - Shiqing Ma, Yingqi Liu, Wen-Chuan Lee, Xiangyu Zhang, Ananth Grama.
* [ASE18] [DeepGauge: Multi-Granularity Testing Criteria for Deep Learning Systems](https://arxiv.org/abs/1803.07519) - Lei Ma, Felix Juefei-Xu, Fuyuan Zhang, Jiyuan Sun, Minhui Xue, Bo Li, Chunyang Chen, Ting Su, Li Li, Yang Liu, Jianjun Zhao, Yadong Wang.
* [ICSE18] [DeepTest: Automated Testing of Deep-Neural-Network-driven Autonomous Cars](https://arxiv.org/abs/1708.08559) - Yuchi Tian, Kexin Pei, Suman Jana, Baishakhi Ray.
* [SOSP17] [DeepXplore: Automated Whitebox Testing of Deep Learning Systems](https://arxiv.org/abs/1705.06640) - Kexin Pei, Yinzhi Cao, Junfeng Yang, Suman Jana.

## Empirical Study
* [ECCV18] [Is Robustness the Cost of Accuracy? -- A Comprehensive Study on the Robustness of 18 Deep Image Classification Models](https://arxiv.org/abs/1808.01688) - Dong Su, Huan Zhang, Hongge Chen, Jinfeng Yi, Pin-Yu Chen, Yupeng Gao.

## Survey
* [Arxiv18] [Threat of Adversarial Attacks on Deep Learning in Computer Vision: A Survey](https://arxiv.org/abs/1801.00553) - Naveed Akhtar and Ajmal Mian.
