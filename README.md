# The Papers of Adversarial Examples

[A Complete List of All (arXiv) Adversarial Example Papers](https://nicholas.carlini.com/writing/2019/all-adversarial-example-papers.html)

## Adversarial Examples in Computer Vision

[Newest paper](./CV.md)

### Adversarial Attack

**[1]** Christian Szegedy, Wojciech Zaremba, Ilya Sutskever, Joan Bruna, Dumitru Erhan, Ian Goodfellow and Rob Fergus. [Intriguing properties of neural networks](https://arxiv.org/abs/1312.6199). ICLR 2014.

#### Gradented-Based Attack

**[1]** Ian J. Goodfellow, Jonathon Shlens and Christian Szegedy. [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572). ICLR 2015.

**[2]** Cihang Xie, Zhishuai Zhang, Yuyin Zhou, Song Bai, Jianyu Wang, Zhou Ren, and Alan L Yuille. [Improving transferability of adversarial examples with input diversity](https://arxiv.org/abs/1803.06978). CVPR 2019.

**[3]** Jiadong Lin, Chuanbiao Song, Kun He, Liwei Wang, John E. Hopcroft. [Nesterov Accelerated Gradient and Scale Invariance for Improving Transferability of Adversarial Examples](https://arxiv.org/abs/1908.06281). arXiv Preprint arXiv:1908.06281 2019.

**[4]** Lei Wu, Zhanxing Zhu, Cheng Tai and Weinan E. [Enhancing the Transferability of Adversarial Examples with Noise Reduced Gradient](https://arxiv.org/abs/1802.09707). ICLR 2018 rejected. 

**[4]** Yinpeng Dong, Fangzhou Liao, Tianyu Pang, Hang Su, Jun Zhu, Xiaolin Hu and Jianguo Li. [Boosting Adversarial Attacks with Momentum](https://arxiv.org/abs/1710.06081). CVPR 2018.

#### GAN-Based Attack

**[1]** Hyrum S. Anderson, Jonathan Woodbridge and Bobby Filar. [DeepDGA: Adversarially-Tuned Domain Generation and Detection](https://arxiv.org/abs/1610.01969) AISec 2016.

**[2]** Chaowei Xiao, Bo Li, Jun-Yan Zhu, Warren He, Mingyan Liu and Dawn Song. [Generating Adversarial Examples with Adversarial Networks](https://arxiv.org/abs/1801.02610). IJCAI 2018.


**[3]** Yang Song, Rui Shu, Nate Kushman and Stefano Ermon. [Constructing Unrestricted Adversarial Examples with Generative Models](https://arxiv.org/abs/1805.07894). NeurIPS 2018.

**[4]** Xiaosen Wang, Kun He and John E. Hopcroft. [AT-GAN: A Generative Attack Model for Adversarial Transferring on Generative Adversarial Nets](https://arxiv.org/abs/1904.07793). arXiv Preprint arXiv:1904.07793 2019.

**[5]** Tao Bai, Jun Zhao, Jinlin Zhu, Shoudong Han, Jiefeng Chen and Bo Li. [AI-GAN: Attack-Inspired Generation of Adversarial Examples](https://arxiv.org/abs/2002.02196). arXiv Preprint arXiv:2002.02196 2020.

#### Unrestricted Adversarial Examples

**[1]** Yang Song, Rui Shu, Nate Kushman and Stefano Ermon. [Constructing Unrestricted Adversarial Examples with Generative Models](https://arxiv.org/abs/1805.07894). NeurIPS 2018.

**[2]** Xiaosen Wang, Kun He and John E. Hopcroft. [AT-GAN: A Generative Attack Model for Adversarial Transferring on Generative Adversarial Nets](https://arxiv.org/abs/1904.07793). arXiv Preprint arXiv:1904.07793.

### Unrecognized Images

**[1]** Anh Nguyen, Jason Yosinski and Jeff Clune. [Deep Neural Networks are Easily Fooled: High Confidence Predictions for Unrecognizable Images](https://arxiv.org/abs/1412.1897). CVPR 2015.

### Adversarial Defense

#### Adversarial Training

**[1]** Ian J. Goodfellow, Jonathon Shlens and Christian Szegedy. [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572). ICLR 2015.

**[2]** Runtian Zhai, Tianle Cai, Di He, Chen Dan, Kun He, John Hopcroft and Liwei Wang. [Adversarially Robust Generalization Just Requires More Unlabeled Data](https://arxiv.org/abs/1906.00555) arXiv Preprint arXiv:1906.00555.


**[3]** Yair Carmon, Aditi Raghunathan, Ludwig Schmidt, Percy Liang and John C. Duchi. [Unlabeled Data Improves Adversarial Robustness](https://arxiv.org/abs/1905.13736). arXiv Preprint arXiv:1905.13736.

**[4]** Jonathan Uesato, Jean-Baptiste Alayrac, Po-Sen Huang, Robert Stanforth, Alhussein Fawzi and Pushmeet Kohli. [Are Labels Required for Improving Adversarial Robustness?](https://arxiv.org/abs/1905.13725). arXiv Preprint arXiv:1905.13725.

**[5]** Chuanbiao Song, Kun He, Liwei Wang and John E. Hopcroft. [Improving the Generalization of Adversarial Training with Domain Adaptation ](https://openreview.net/forum?id=SyfIfnC5Ym). ICLR 2019.

**[6]** Hang Yu, Aishan Liu, Xianglong Liu, Gengchao Li, Ping Luo, Ran Cheng, Jichen Yang and Chongzhi Zhang. [PDA: Progressive Data Augmentation for General Robustness of Deep Neural Networks](https://arxiv.org/abs/1909.04839). arXiv Preprint arXiv:1909.04839.

**[7]** Chuanbiao Song, Kun He, Jiadong Lin, Liwei Wang and John E. Hopcroft. [Robust Local Features for Improving the Generalization of Adversarial Training](https://arxiv.org/abs/1909.10147). ICLR 2020.

**[8]** Hongyang Zhang, Yaodong Yu, Jiantao Jiao, Eric P. Xing, Laurent El Ghaoui, Michael I. Jordan. [Theoretically Principled Trade-off between Robustness and Accuracy](https://arxiv.org/abs/1901.08573). ICML 2019.

#### GAN-Based Defense

**[1]** Pouya Samangouei, Maya Kabkab and Rama Chellappa. [Defense-GAN: Protecting Classifiers Against Adversarial Attacks Using Generative Models](https://arxiv.org/abs/1805.06605). ICLR 2018.

**[2]** Yang Song, Taesup Kim, Sebastian Nowozin, Stefano Ermon and Nate Kushman. [PixelDefend: Leveraging Generative Models to Understand and Defend against Adversarial Examples](https://arxiv.org/abs/1710.10766) ICLR 2018.

**[3]** Guoqing Jin, Shiwei Shen, Dongming Zhang, Feng Dai and Yongdong Zhang. [APE-GAN: Adversarial Perturbation Elimination with GAN](https://arxiv.org/abs/1707.05474). ICASSP 2019.

#### Certified defense

**[1]** Eric Wong and J. Zico Kolter. [Provable defenses against adversarial examples via the convex outer adversarial polytope](https://arxiv.org/abs/1711.00851). ICML 2017.

**[2]** Sven Gowal, Krishnamurthy Dvijotham, Robert Stanforth, Rudy Bunel, Chongli Qin, Jonathan Uesato, Relja Arandjelovic, Timothy Mann and Pushmeet Kohli. [Scalable Verified Training for Provably Robust Image Classification](http://openaccess.thecvf.com/content_ICCV_2019/supplemental/Gowal_Scalable_Verified_Training_ICCV_2019_supplemental.pdf). ICCV 2019.

**[3]** Jeremy M Cohen, Elan Rosenfeld and J. Zico Kolter. [Certified Adversarial Robustness via Randomized Smoothing](https://arxiv.org/abs/1902.02918). ICML 2019.

**[4]** Guang-He Lee, Yang Yuan, Shiyu Chang and Tommi S. Jaakkola. [Tight Certificates of Adversarial Robustness for Randomly Smoothed Classifiers](https://arxiv.org/abs/1906.04948). NeurIPS 2019.

#### Others
**[1]** Matthew J. Roos. [Utilizing a null class to restrict decision spaces and defend against neural network adversarial attacks](https://arxiv.org/abs/2002.10084). arXiv Preprint arXiv:2002.10084 2020.

**[2]** Alvin Chan, Yi Tay, Yew Soon Ong and Jie Fu. [Jacobian Adversarially Regularized Networks for Robustness](https://arxiv.org/abs/1912.10185). ICLR 2020.

**[3]** Christian Etmann, Sebastian Lunz, Peter Maass and Carola-Bibiane Schönlieb. [On the Connection Between Adversarial Robustness and Saliency Map Interpretability](https://arxiv.org/abs/1905.04172). ICML 2019.

## Adversarial Examples in Natural Language Processing

### Survey

**[1]** Wei Emma Zhang, Quan Z. Sheng, Ahoud Alhazmi and Chenliang Li. [Adversarial Attacks on Deep Learning Models in Natural Language Processing: A Survey](https://arxiv.org/abs/1901.06796). arXiv Preprint arXiv:1901.06796 2019.

**[2]** Wenqi Wang, Lina Wang, Benxiao Tang, Run Wang and Aoshuang Ye. [Towards a Robust Deep Neural Network in Text Domain A Survey](https://arxiv.org/abs/1902.07285). arXiv Preprint arXiv:1902.07285 2019.

[Newest paper](./NLP.md)

### Adversarial Attack


#### Character-Level

**[1]** Javid Ebrahimi, Anyi Rao, Daniel Lowd and Dejing Dou. [HotFlip: White-Box Adversarial Examples for Text Classification](https://arxiv.org/abs/1712.06751). ACL 2018.

**[2]** Ji Gao, Jack Lanchantin, Mary Lou Soffa and Yanjun Qi. [Black-box Generation of Adversarial Text Sequences to Evade Deep Learning Classifiers](https://arxiv.org/abs/1801.04354). IEEE S&P workshop 2018.

#### Word-Level

**[1]** Nicolas Papernot, Patrick McDaniel, Ananthram Swami and Richard Harang. [Crafting Adversarial Input Sequences for Recurrent Neural Networks](https://arxiv.org/abs/1604.08275). MILCOM 2016.

**[2]** Volodymyr Kuleshov, Shantanu Thakoor, Tingfung Lau and Stefano Ermon. [Adversarial Examples for Natural Language Classification Problems ](https://openreview.net/pdf?id=r1QZ3zbAZ). ICLR 2018 rejected.

**[3]** Moustafa Alzantot, Yash Sharma, Ahmed Elgohary, Bo-Jhang Ho, Mani Srivastava and Kai-Wei Chang. [Generating Natural Language Adversarial Examples](https://arxiv.org/abs/1804.07998). EMNLP 2018.

**[4]** Shuhuai Ren, Yihe Deng, Kun He and Wanxiang Che. [Generating Natural Language Adversarial Examples through Probability Weighted Word Saliency](https://www.aclweb.org/anthology/P19-1103). ACL 2019.

**[5]** Huangzhao Zhang, Hao Zhou, Ning Miao and Lei Li. [Generating Fluent Adversarial Examples for Natural Languages](https://www.aclweb.org/anthology/P19-1559). ACL 2019.

**[6]** Yi-Ting Tsai, Min-Chu Yang and Han-Yu Chen. [Adversarial Attack on Sentiment Classification](https://www.aclweb.org/anthology/W19-4824). ACL workshop 2019.

**[7]** Samuel Barham and Soheil Feizi. [Interpretable Adversarial Training for Text](https://arxiv.org/abs/1905.12864) arXiv Preprint arXiv:1905.12864 2019.

**[8]** Di Jin, Zhijing Jin, Joey Tianyi Zhou and Peter Szolovits. [Is BERT Really Robust? Natural Language Attack on Text Classification and Entailment](https://arxiv.org/abs/1907.11932) arXiv Preprint arXiv:1907.11932 2019.

**[9]** Xiaosen Wang, Hao Jin and Kun He. [Natural Language Adversarial Attacks and Defenses in Word Level](https://arxiv.org/abs/1909.06723). arXiv Preprint arXiv:1909.06723 2019.

**[10]** Suranjana Samanta and Sameep Mehta. [Towards Crafting Text Adversarial Samples](​https://arxiv.org/pdf/1707.02812.pdf). arXiv Preprint arXiv:1707.02812 2017.

#### Both

**[1]** Bin Liang, Hongcheng Li, Miaoqiang Su, Pan Bian, Xirong Li and Wenchang Shi. [Deep text classification can be fooled](https://arxiv.org/abs/1704.08006). IJCAI 2018. 

**[2]** Jinfeng Li, Shouling Ji, Tianyu Du, Bo Li and Ting Wang. [TextBugger: Generating Adversarial Text Against Real-world Applications](https://arxiv.org/abs/1812.05271). NDSS 2019.


#### Universal Adversarial Examples

**[1]** Di Li, Danilo Vasconcellos Vargas and Sakurai Kouichi. [Universal Rules for Fooling Deep Neural Networks based Text Classification](https://arxiv.org/abs/1901.07132). CEC 2019.

**[2]** Melika Behjati, Seyed-Mohsen Moosavi-Dezfooli, Mahdieh Soleymani Baghshah and Pascal Frossard. [Universal Adversarial Attacks on Text Classifiers](https://ieeexplore.ieee.org/document/8682430/authors#authors). ICASSP 2019.

### Adversarial Defense

#### Character-Level

**[1]** Danish Pruthi, Bhuwan Dhingra and Zachary C. Lipton. [Combating Adversarial Misspellings with Robust Word Recognition](https://arxiv.org/abs/1905.11268). ACL 2019.

**[2]** Hui Liu, Yongzheng Zhang, Yipeng Wang, Zheng Lin, Yige Chen. [Joint Character-level Word Embedding and Adversarial Stability Training to Defend Adversarial Text](https://www.aaai.org/Papers/AAAI/2020GB/AAAI-LiuH.1396.pdf). AAAI 2020.

#### Word-Level

**[1]** Ishai Rosenberg, Asaf Shabtai, Yuval Elovici and Lior Rokach. [Defense Methods Against Adversarial Examples for Recurrent Neural Networks](https://arxiv.org/abs/1901.09963). arXiv Preprint arXiv:1901.09963 2019.

**[2]** Xiaosen Wang, Hao Jin and Kun He. [Natural Language Adversarial Attacks and Defenses in Word Level](https://arxiv.org/abs/1909.06723). arXiv Preprint arXiv:1909.06723 2019.

#### Both

**[1]** Nestor Rodriguez and Sergio Rojas-Galeano. [Shielding Google's language toxicity model against adversarial attacks](https://arxiv.org/abs/1801.01828). arXiv Preprint arXiv:1801.01828 2018.

**[2]** Yichao Zhou, Jyun-Yu Jiang, Kai-Wei Chang and Wei Wang. [Learning to Discriminate Perturbations for Blocking Adversarial Attacks in Text Classification](https://arxiv.org/abs/1909.03084). EMNLP-IJCNLP 2019.

#### Certified defense

**[1]** Robin Jia, Aditi Raghunathan, Kerem Göksel and Percy Liang. [Certified Robustness to Adversarial Word Substitutions](https://arxiv.org/abs/1909.00986). EMNLP-IJCNLP 2019.

**[2]** Po-Sen Huang, Robert Stanforth, Johannes Welbl, Chris Dyer, Dani Yogatama, Sven Gowal, Krishnamurthy Dvijotham, Pushmeet Kohli. [Achieving Verified Robustness to Symbol Substitutions via Interval Bound Propagation](https://arxiv.org/abs/1909.01492). EMNLP-IJCNLP 2019.