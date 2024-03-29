# The Papers of Adversarial Examples

We have given a complete list of adversarial examples [here](https://xiaosenwang.com/adv_papers.html) where the raw data is [here](https://github.com/Trustworthy-AI-Group/Adversarial_Examples_Papers).

[A Complete List of All (arXiv) Adversarial Example Papers](https://nicholas.carlini.com/writing/2019/all-adversarial-example-papers.html)

## Adversarial Examples in Computer Vision

[Newest paper](./CV.md)

### Adversarial Attack

**[1]** Christian Szegedy, Wojciech Zaremba, Ilya Sutskever, Joan Bruna, Dumitru Erhan, Ian Goodfellow and Rob Fergus. [Intriguing properties of neural networks](https://arxiv.org/abs/1312.6199). ICLR 2014.

#### Gradented-Based Attack

**[1]** Ian J. Goodfellow, Jonathon Shlens and Christian Szegedy. [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572). ICLR 2015.

**[2]** Cihang Xie, Zhishuai Zhang, Yuyin Zhou, Song Bai, Jianyu Wang, Zhou Ren, and Alan L Yuille. [Improving transferability of adversarial examples with input diversity](https://arxiv.org/abs/1803.06978). CVPR 2019.

**[3]** Lei Wu, Zhanxing Zhu, Cheng Tai and Weinan E. [Enhancing the Transferability of Adversarial Examples with Noise Reduced Gradient](https://arxiv.org/abs/1802.09707). ICLR 2018 rejected. 

**[4]** Yinpeng Dong, Fangzhou Liao, Tianyu Pang, Hang Su, Jun Zhu, Xiaolin Hu and Jianguo Li. [Boosting Adversarial Attacks with Momentum](https://arxiv.org/abs/1710.06081). CVPR 2018.

**[5]** Lianli Gao, Qilong Zhang, Jingkuan Song, Xianglong Liu and Heng Tao Shen. [Patch-wise Attack for Fooling Deep Neural Network](https://arxiv.org/abs/2007.06765). ECCV 2020.

#### GAN-Based Attack

**[1]** Hyrum S. Anderson, Jonathan Woodbridge and Bobby Filar. [DeepDGA: Adversarially-Tuned Domain Generation and Detection](https://arxiv.org/abs/1610.01969) AISec 2016.

**[2]** Chaowei Xiao, Bo Li, Jun-Yan Zhu, Warren He, Mingyan Liu and Dawn Song. [Generating Adversarial Examples with Adversarial Networks](https://arxiv.org/abs/1801.02610). IJCAI 2018.


**[3]** Yang Song, Rui Shu, Nate Kushman and Stefano Ermon. [Constructing Unrestricted Adversarial Examples with Generative Models](https://arxiv.org/abs/1805.07894). NeurIPS 2018.

**[4]** Xiaosen Wang, Kun He and John E. Hopcroft. [AT-GAN: A Generative Attack Model for Adversarial Transferring on Generative Adversarial Nets](https://arxiv.org/abs/1904.07793). arXiv Preprint arXiv:1904.07793 2019.

**[5]** Tao Bai, Jun Zhao, Jinlin Zhu, Shoudong Han, Jiefeng Chen and Bo Li. [AI-GAN: Attack-Inspired Generation of Adversarial Examples](https://arxiv.org/abs/2002.02196). arXiv Preprint arXiv:2002.02196 2020.

#### Transferability

[full list](./transferability.md)

**[1]** Jiadong Lin, Chuanbiao Song, Kun He, Liwei Wang, John E. Hopcroft. [Nesterov Accelerated Gradient and Scale Invariance for Improving Transferability of Adversarial Examples](https://arxiv.org/abs/1908.06281). ICLR 2020.

**[2]** Weibin Wu, Yuxin Su, Xixian Chen, Shenglin Zhao, Irwin King, Michael R. Lyu, Yu-Wing Tai. [Boosting the Transferability of Adversarial Samples via Attention](http://openaccess.thecvf.com/content_CVPR_2020/papers/Wu_Boosting_the_Transferability_of_Adversarial_Samples_via_Attention_CVPR_2020_paper.pdf). CVPR 2020.

**[3]** Nathan Inkawhich, Kevin Liang, Lawrence Carin and Yiran Chen. [Transferable Perturbations of Deep Feature Distributions](https://openreview.net/forum?id=rJxAo2VYwr). ICLR 2020.

**[4]** Kaizhao Liang, Jacky Y. Zhang, Oluwasanmi Koyejo, Bo Li. [Does Adversarial Transferability Indicate Knowledge Transferability?](https://arxiv.org/abs/2006.14512). arXiv Preprint arXiv:2006.14512 2020.

**[5]** Junhua Zou, Zhisong Pan, Junyang Qiu, Xin Liu, Ting Rui, Wei Li. [Improving the Transferability of Adversarial Examples with Resized-Diverse-Inputs, Diversity-Ensemble and Region Fitting](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670562.pdf). ECCV 2020.

**[6]** Cihang Xie, Zhishuai Zhang, Yuyin Zhou, Song Bai, Jianyu Wang, Zhou Ren, Alan Yuille. [Improving Transferability of Adversarial Examples with Input Diversity](https://arxiv.org/abs/1803.06978). CVPR 2019.

**[7]** Yinpeng Dong, Tianyu Pang, Hang Su, Jun Zhu. [Evading Defenses to Transferable Adversarial Examples by Translation-Invariant Attacks](https://arxiv.org/abs/1904.02884). CVPR 2019.

**[8]** Yinpeng Dong, Fangzhou Liao, Tianyu Pang, Hang Su, Jun Zhu, Xiaolin Hu, Jianguo Li. [Boosting Adversarial Attacks with Momentum](https://arxiv.org/abs/1710.06081). CVPR 2018.

**[9]** Xiaosen Wang, Xuanran He, Jingdong Wang, Kun He. [Admix: Enhancing the Transferability of Adversarial Attacks](https://arxiv.org/abs/2102.00436). ICCV 2021.

**[10]** Xiaosen Wang, Kun He. [Enhancing the Transferability of Adversarial Attacks through Variance Tuning](https://xiaosen-wang.github.io/publication/variancetuning/VT.pdf). CVPR 2021.

**[11]** Xiaosen Wang, Jiadong Lin, Han Hu, Jingdong Wang, Kun He. [Boosting Adversarial Transferability through Enhanced Momentum](https://arxiv.org/abs/2103.10609). BMVC 2021.

**[12]** Weibin Wu, Yuxin Su, Michael R. Lyu, Irwin King. [Improving the Transferability of Adversarial Samples With Adversarial Transformations](https://openaccess.thecvf.com/content/CVPR2021/papers/Wu_Improving_the_Transferability_of_Adversarial_Samples_With_Adversarial_Transformations_CVPR_2021_paper.pdf). CVPR 2020.

**[13]** Zhibo Wang, Hengchang Guo, Zhifei Zhang, Wenxin Liu, Zhan Qin, Kui Ren. [Feature Importance-aware Transferable Adversarial Attacks](https://arxiv.org/abs/2107.14185). ICCV 2021.

# Hard Label Attack

**[1]** Wieland Brendel, Jonas Rauber, Matthias Bethge. [Decision-Based Adversarial Attacks: Reliable Attacks Against Black-Box Machine Learning Models](https://arxiv.org/abs/1712.04248). ICLR 2018.

**[2]** Andrew Ilyas, Logan Engstrom, Anish Athalye, Jessy Lin. [Black-box Adversarial Attacks with Limited Queries and Information](https://arxiv.org/abs/1804.08598). ICML 2018.

**[3]** Minhao Cheng, Thong Le, Pin-Yu Chen, Jinfeng Yi, Huan Zhang, Cho-Jui Hsieh. [Query-Efficient Hard-label Black-box Attack:An Optimization-based Approach](https://arxiv.org/abs/1807.04457). ICLR 2019.

**[4]** Yinpeng Dong, Hang Su, Baoyuan Wu, Zhifeng Li, Wei Liu, Tong Zhang, Jun Zhu. [Efficient Decision-based Black-box Adversarial Attacks on Face Recognition](https://arxiv.org/abs/1904.04433). CVPR 2019.

**[5]** Yujia Liu, Seyed-Mohsen Moosavi-Dezfooli, Pascal Frossard. [A geometry-inspired decision-based attack](https://arxiv.org/abs/1903.10826). ICCV 2019.

**[6]** Jianbo Chen, Michael I. Jordan, Martin J. Wainwright. [HopSkipJumpAttack: A Query-Efficient Decision-Based Attack](https://arxiv.org/abs/1904.02144). SP 2020.

**[7]** Minhao Cheng, Simranjit Singh, Patrick Chen, Pin-Yu Chen, Sijia Liu, Cho-Jui Hsieh. [Sign-OPT: A Query-Efficient Hard-label Adversarial Attack](https://arxiv.org/abs/1909.10773). ICLR 2020.

**[8]** Ali Rahmati, Seyed-Mohsen Moosavi-Dezfooli, Pascal Frossard, Huaiyu Dai. [GeoDA: a geometric framework for black-box adversarial attacks](https://arxiv.org/abs/2003.06468). CVPR 2020.

**[9]** Huichen Li, Xiaojun Xu, Xiaolu Zhang, Shuang Yang, Bo Li. [QEBA: Query-Efficient Boundary-Based Blackbox Attack](https://arxiv.org/abs/2005.14137). CVPR 2020.

**[10]** Weilun Chen, Zhaoxiang Zhang, Xiaolin Hu, Baoyuan Wu. [Boosting Decision-based Black-box Adversarial Attacks with Random Sign Flip](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123600273.pdf). ECCV 2020.

**[11]** Thibault Maho, Teddy Furon, Erwan Le Merrer. [SurFree: a fast surrogate-free black-box attack](https://arxiv.org/abs/2011.12807). CVPR 2021.

**[12]** Huichen Li, Linyi Li, Xiaojun Xu, Xiaolu Zhang, Shuang Yang, Bo Li. [Nonlinear Projection Based Gradient Estimation for Query Efficient Blackbox Attacks](https://arxiv.org/abs/2102.13184). AISTATS 2021.

**[13]** Xiaosen Wang, Zeliang Zhang, Kangheng Tong, Dihong Gong, Kun He, Zhifeng Li, Wei Liu. [Triangle Attack: A Query-efficient Decision-based Adversarial Attack](https://arxiv.org/abs/2112.06569). ECCV 2022.

**[14]** Satya Narayan Shukla, Anit Kumar Sahu, Devin Willmott, J. Zico Kolter. [Simple and Efficient Hard Label Black-box Adversarial Attacks in Low Query Budget Regimes](https://arxiv.org/abs/2007.07210). KDD 2021.

#### Unrestricted Adversarial Examples

**[1]** Yang Song, Rui Shu, Nate Kushman and Stefano Ermon. [Constructing Unrestricted Adversarial Examples with Generative Models](https://arxiv.org/abs/1805.07894). NeurIPS 2018.

**[2]** Xiaosen Wang, Kun He and John E. Hopcroft. [AT-GAN: A Generative Attack Model for Adversarial Transferring on Generative Adversarial Nets](https://arxiv.org/abs/1904.07793). arXiv Preprint arXiv:1904.07793.

#### Black-box attacks

**[1]** Pin-Yu Chen, Huan Zhang, Yash Sharma, Jinfeng Yi, Cho-Jui Hsieh. [ZOO: Zeroth Order Optimization based Black-box Attacks to Deep Neural Networks without Training Substitute Models](https://arxiv.org/abs/1708.03999). ACM Workshop on Artificial Intelligence and Security (AISec) 2017.

**[2]** Andrew Ilyas, Logan Engstrom, Anish Athalye, Jessy Lin. [Black-box Adversarial Attacks with Limited Queries and Information](https://arxiv.org/abs/1804.08598). ICML 2018.

**[3]** Andrew Ilyas, Logan Engstrom, Aleksander Madry. [Prior Convictions: Black-Box Adversarial Attacks with Bandits and Priors](https://arxiv.org/abs/1807.07978). ICLR 2019.

**[4]** Arjun Nitin Bhagoji, Warren He, Bo Li, Dawn Song. [Practical Black-box Attacks on Deep Neural Networks using Efficient Query Mechanisms](https://openaccess.thecvf.com/content_ECCV_2018/papers/Arjun_Nitin_Bhagoji_Practical_Black-box_Attacks_ECCV_2018_paper.pdf). ECCV 2018.

**[5]** Shuyu Cheng, Yinpeng Dong, Tianyu Pang, Hang Su and Jun Zhu. [Improving Black-box Adversarial Attacks with a Transfer-based Prior](https://arxiv.org/abs/1906.06919). NeurIPS 2019.

#### Hard-label attacks

**[1]** Wieland Brendel, Jonas Rauber and Matthias Bethge. [Decision-Based Adversarial Attacks: Reliable Attacks Against Black-Box Machine Learning Models](https://arxiv.org/abs/1712.04248). ICLR 2018.

**[2]** Andrew Ilyas, Logan Engstrom, Anish Athalye and Jessy Lin. [Black-box Adversarial Attacks with Limited Queries and Information](https://arxiv.org/abs/1804.08598). ICML 2018.

**[3]** Yinpeng Dong, Hang Su, Baoyuan Wu, Zhifeng Li, Wei Liu, Tong Zhang and Jun Zhu. [Efficient Decision-based Black-box Adversarial Attacks on Face Recognition](https://arxiv.org/abs/1904.04433). CVPR 2019.

**[4]** Minhao Cheng, Thong Le, Pin-Yu Chen, Jinfeng Yi, Huan Zhang and Cho-Jui Hsieh. [Query-Efficient Hard-label Black-box Attack:An Optimization-based Approach](https://arxiv.org/abs/1807.04457). ICLR 2019.

**[5]** Minhao Cheng, Simranjit Singh, Patrick Chen, Pin-Yu Chen, Sijia Liu and Cho-Jui Hsieh. [Sign-OPT: A Query-Efficient Hard-label Adversarial Attack](https://arxiv.org/abs/1909.10773). ICLR 2020.

**[6]** Weilun Chen, Zhaoxiang Zhang, Xiaolin Hu, and Baoyuan Wu. [Boosting Decision-based Black-box Adversarial Attacks with Random Sign Flip](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123600273.pdf). ECCV 2020. 

**[7]** Yujia Liu, Seyed-Mohsen Moosavi-Dezfooli, Pascal Frossard. [A Geometry-Inspired Decision-Based Attack](https://openaccess.thecvf.com/content_ICCV_2019/papers/Liu_A_Geometry-Inspired_Decision-Based_Attack_ICCV_2019_paper.pdf). ICCV 2019.

**[8]** Thibault Maho, Teddy Furon, Erwan Le Merrer. [SurFree: a fast surrogate-free black-box attack](https://arxiv.org/abs/2011.12807). arXiv Preprint arXiv:2011.12807.

#### Others

**[1]** Xiaoyi Dong, Jiangfan Han, Dongdong Chen, Jiayang Liu, Huanyu Bian, Zehua Ma, Hongsheng Li, Xiaogang Wang, Weiming Zhang and Nenghai Yu. [Robust Superpixel-Guided Attentional Adversarial Attack](http://openaccess.thecvf.com/content_CVPR_2020/html/Dong_Robust_Superpixel-Guided_Attentional_Adversarial_Attack_CVPR_2020_paper.html). CVPR 2020.

**[2]** Linxi Jiang, Xingjun Ma, Zejia Weng, James Bailey and Yu-Gang Jiang. [Imbalanced Gradients: A New Cause of Overestimated Adversarial Robustness](https://arxiv.org/abs/2006.13726). arXiv Preprint arXiv:2006.13726.

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

**[9]** Yuanhao Xiong and Cho-Jui Hsieh. [Improved Adversarial Training via Learned Optimizer](https://arxiv.org/abs/2004.12227). arXiv Preprint arXiv:2004.12227.

**[10]** Pranjal Awasthi, Natalie Frank and Mehryar Mohri. [Adversarial Learning Guarantees for Linear Hypotheses and Neural Networks](https://arxiv.org/abs/2004.13617). arXiv Preprint arXiv:2004.13617.

**[11]** Yisen Wang, Difan Zou, Jinfeng Yi, James Bailey, Xingjun Ma and Quanquan Gu. [Improving Adversarial Robustness Requires Revisiting Misclassified Examples](https://openreview.net/forum?id=rklOg6EFwS). ICLR 2020.

**[12]** Chang Xiao, Peilin Zhong, Changxi Zheng. [Enhancing Adversarial Defense by k-Winners-Take-All](https://openreview.net/forum?id=Skgvy64tvr). ICLR 2020.

**[13]** Saehyung Lee, Hyungyu Lee and Sungroh Yoon. [Adversarial Vertex Mixup: Toward Better Adversarially Robust Generalization](https://arxiv.org/abs/2003.02484). CVPR 2020.

**[14]** Gavin Weiguang Ding, Yash Sharma, Kry Yik Chau Lui and Ruitong Huang. [MMA Training: Direct Input Space Margin Maximization through Adversarial Training](https://arxiv.org/abs/1812.02637). ICLR 2020.

**[15]** Harini Kannan, Alexey Kurakin and Ian Goodfellow. [Adversarial Logit Pairing](https://arxiv.org/abs/1803.06373). arXiv Preprint arXiv:1803.06373.

**[16]** Cihang Xie, Mingxing Tan, Boqing Gong, Alan Yuille and Quoc V. Le. [Smooth Adversarial Training](https://arxiv.org/abs/2006.14536). arXiv Preprint arXiv:2006.14536.

**[17]** Anh Bui, Trung Le, He Zhao, Paul Montague, Olivier deVel, Tamas Abraham and Dinh Phung. [Improving Adversarial Robustness by Enforcing Local and Global Compactness](https://arxiv.org/abs/2007.05123). ECCV 2020.

**[18]** David Stutz, Matthias Hein and Bernt Schiele. [Confidence-Calibrated Adversarial Training: Generalizing to Unseen Attacks](https://arxiv.org/abs/1910.06259). ICML 2020.

**[19]** Tianyu Pang, Chao Du, and Jun Zhu. [Max-Mahalanobis Linear Discriminant Analysis Networks](http://ml.cs.tsinghua.edu.cn/~jun/pub/mmlda-dnn.pdf). ICML 2018.

**[20]** Ali Shafahi, Mahyar Najibi, Amin Ghiasi, Zheng Xu, John Dickerson, Christoph Studer, Larry S. Davis, Gavin Taylor, Tom Goldstein. [Adversarial Training for Free!](https://arxiv.org/abs/1904.12843). NeurIPS 2019.

**[21]** Yinpeng Dong, Zhijie Deng, Tianyu Pang, Hang Su, Jun Zhu. [Adversarial Distributional Training for Robust Deep Learning](https://arxiv.org/abs/2002.05999). NeurIPS 2020.

**[22]** Alex Lamb, Vikas Verma, Juho Kannala, Yoshua Bengio. [Interpolated Adversarial Training: Achieving Robust Neural Networks without Sacrificing Too Much Accuracy]. ACM AISec 2019.

**[23]** Alfred Laugros, Alice Caplier, Matthieu Ospici. [Addressing Neural Network Robustness with Mixup and Targeted Labeling Adversarial Training](https://arxiv.org/abs/2008.08384). ECCV 2019.

**[24]** Saehyung Lee, Hyungyu Lee, Sungroh Yoon. [Adversarial Vertex Mixup: Toward Better Adversarially Robust Generalization](https://arxiv.org/abs/2003.02484). CVPR 2020.

**[25]** Tao Bai, Jinqi Luo, Jun Zhao, Bihan Wen, Qian Wang. [Recent Advances in Adversarial Training for Adversarial Robustness](https://arxiv.org/abs/2102.01356). arXiv Preprint arXiv:2102.01356 2021.

**[26]** Leslie Rice, Eric Wong, J. Zico Kolter. [Overfitting in adversarially robust deep learning](https://arxiv.org/abs/2002.11569). ICML 2020.

**[27]** Jason Bunk, Srinjoy Chattopadhyay, B. S. Manjunath, Shivkumar Chandrasekaran. [Adversarially Optimized Mixup for Robust Classification](https://arxiv.org/abs/2103.11589).  arXiv Preprint arXiv:2103.11589 2021.

**[28]** Zuxuan Wu, Tom Goldstein, Larry S. Davis, Ser-Nam Lim. [THAT: Two Head Adversarial Training for Improving Robustness at Scale](https://arxiv.org/abs/2103.13612). arXiv Preprint arXiv:2103.13612 2021.

**[29]** Xiaosen Wang, Bhavya Kailkhura, Krishnaram Kenthapadi, Bo Li. [I-PGD-AT: Efficient Adversarial Training via Imitating Iterative PGD Attack](https://openreview.net/pdf?id=TEt7PsVZux6). openreview 2021.

**[30]** Xiaosen Wang, Chuanbiao Song, Kun He. [Multi-stage Optimization based Adversarial Training](https://arxiv.org/abs/2106.15357). arXiv Preprint arXiv:2106.15357 2021.


#### Fast Adversarial Training

**[1]** Eric Wong, Leslie Rice, J. Zico Kolter. [Fast is better than free: Revisiting adversarial training](https://arxiv.org/abs/2001.03994). ICLR 2020.

**[2]** Maksym Andriushchenko, Nicolas Flammarion. [Understanding and Improving Fast Adversarial Training](https://arxiv.org/abs/2007.02617). NeurIPS 2020.

**[3]** Hoki Kim, Woojin Lee, Jaewook Lee. [Understanding Catastrophic Overfitting in Single-step Adversarial Training](https://arxiv.org/abs/2010.01799). AAAI 2021.

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

**[4]** Zhun Deng, Linjun Zhang, Amirata Ghorbani and James Zou. [Improving Adversarial Robustness via Unlabeled Out-of-Domain Data](https://arxiv.org/abs/2006.08476). arXiv Preprint arXiv:2006.08476 2020.

**[5]** Tianyu Pang, Kun Xu, Yinpeng Dong, Chao Du, Ning Chen and Jun Zhu. [Rethinking Softmax Cross-Entropy Loss for Adversarial Robustness](https://arxiv.org/abs/1905.10626). ICLR 2020.

## Others
**[1]** Haohan Wang, Xindi Wu, Zeyi Huang, Eric P. Xing. [High Frequency Component Helps Explain the Generalization of Convolutional Neural Networks](https://arxiv.org/abs/1905.13545). CVPR 2020.

**[2]** Hongyi Zhang, Moustapha Cisse, Yann N. Dauphin and David Lopez-Paz. [Mixup: Beyond Empirical Risk Minimization](https://arxiv.org/abs/1710.09412). ICLR 2018.

**[3]** Ludwig Schmidt, Shibani Santurkar, Dimitris Tsipras, Kunal Talwar and Aleksander Mądry. [Adversarially Robust Generalization Requires More Data](https://arxiv.org/abs/1804.11285). NeurIPS 2018.

**[4]** Tianyuan Zhang and Zhanxing Zhu. [Interpreting Adversarially Trained Convolutional Neural Networks](https://arxiv.org/abs/1905.09797). ICML 2019.

**[5]** Robert Geirhos, Patricia Rubisch, Claudio Michaelis, Matthias Bethge, Felix A. Wichmann and Wieland Brendel. [ImageNet-trained CNNs are biased towards texture; increasing shape bias improves accuracy and robustness](https://arxiv.org/abs/1811.12231). ICLR 2019.

**[6]** Dong Yin, Raphael Gontijo Lopes, Jonathon Shlens, Ekin D. Cubuk and Justin Gilmer. [A Fourier Perspective on Model Robustness in Computer Vision](https://arxiv.org/abs/1906.08988). NeurIPS 2019.

**[7]** Chengzhi Mao, Amogh Gupta, Vikram Nitin, Baishakhi Ray, Shuran Song, Junfeng Yang and Carl Vondrick. [Multitask Learning Strengthens Adversarial Robustness](https://arxiv.org/abs/2007.07236). arXiv Preprint arXiv:2007.07236.

**[8]** Xiao Wang, Siyue Wang, Pin-Yu Chen, Yanzhi Wang, Brian Kulis, Xue Lin and Peter Chin. [Protecting Neural Networks with Hierarchical Random Switching: Towards Better Robustness-Accuracy Trade-off for Stochastic Defenses](https://arxiv.org/abs/1908.07116). IJCAI 2019.

**[9]** Matteo Terzi, Alessandro Achille, Marco Maggipinto, Gian Antonio Susto. [Adversarial Training Reduces Information and Improves Transferability](https://arxiv.org/abs/2007.11259). arXiv Preprint arXiv:2007.11259 2020.

## Adversarial Examples in Natural Language Processing

### Survey

**[1]** Wei Emma Zhang, Quan Z. Sheng, Ahoud Alhazmi and Chenliang Li. [Adversarial Attacks on Deep Learning Models in Natural Language Processing: A Survey](https://arxiv.org/abs/1901.06796). arXiv Preprint arXiv:1901.06796 2019.

**[2]** Wenqi Wang, Lina Wang, Benxiao Tang, Run Wang and Aoshuang Ye. [Towards a Robust Deep Neural Network in Text Domain A Survey](https://arxiv.org/abs/1902.07285). arXiv Preprint arXiv:1902.07285 2019.

[Newest paper](./NLP.md)

### Adversarial Attack

**[1]** John X. Morris, Eli Lifland, Jin Yong Yoo and Yanjun Qi. [TextAttack: A Framework for Adversarial Attacks in Natural Language Processing](https://arxiv.org/abs/2005.05909). arXiv Preprint axXiv:2005.05909 2020.


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

**[11]** Yuan Zang, Fanchao Qi, Chenghao Yang, Zhiyuan Liu, Meng Zhang, Qun Liu and Maosong Sun. [Word-level Textual Adversarial Attacking as Combinatorial Optimizatio](https://arxiv.org/abs/1910.12196). ACL 2020.

**[12]** Xiaosen Wang, Yichen Yang, Yihe Deng and Kun He. [Adversarial Training with Fast Gradient Projection Method against Synonym Substitution based Text Attacks](https://arxiv.org/abs/2008.03709). AAAI 2021.

**[13]** Linyang Li, Yunfan Shao, Demin Song, Xipeng Qiu and Xuanjing Huang. [Generating Adversarial Examples in Chinese Texts Using Sentence-Pieces](https://arxiv.org/abs/2012.14769). arXiv Preprint arXiv:2012.14769 2020.

**[14]** Bushra Sabir, M. Ali Babar, Raj Gaire. [ReinforceBug: A Framework to Generate Adversarial Textual Examples](https://arxiv.org/abs/2103.08306). NAACL 2021.

**[15]** Xuanli He, Lingjuan Lyu, Qiongkai Xu, Licaho Sun. [Model Extraction and Adversarial Transferability, Your BERT is Vulnerable!](https://arxiv.org/pdf/2103.10013v1.pdf). NAACL 2021.

**[16]** Zhao Meng, Roger Wattenhofer. [A Geometry-Inspired Attack for Generating Natural Language Adversarial Examples](https://arxiv.org/abs/2010.01345). COLING 2020.

**[17]** Rishabh Maheshwary, Saket Maheshwary, Vikram Pudi. [A Strong Baseline for Query Efficient Attacks in a Black Box Setting](https://arxiv.org/pdf/2109.04775.pdf). EMNLP 2021.

**[18]** Yangyi Chen, Jin Su, Wei Wei. [Multi-granularity Textual Adversarial Attack with Behavior Cloning](https://arxiv.org/abs/2109.04367). EMNLP 2021.

**[19]** Shengcai Liu, Ning Lu, Cheng Chen, Ke Tang. [Efficient Combinatorial Optimization for Word-level Adversarial Textual Attack](https://arxiv.org/abs/2109.02229)arXiv Preprint arXiv:2109.02229 2021. 

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

**[3]** Yi Zhou, Xiaoqing Zheng, Cho-Jui Hsieh, Kai-wei Chang and Xuanjing Huang. [Defense against Adversarial Attacks in NLP via Dirichlet Neighborhood Ensemble](https://arxiv.org/abs/2006.11627). arXiv Preprint arXiv:2006.11627 2020.

**[4]** Xiaosen Wang, Yichen Yang, Yihe Deng and Kun He. [Adversarial Training with Fast Gradient Projection Method against Synonym Substitution based Text Attacks](https://arxiv.org/abs/2008.03709). AAAI 2021.

**[5]** Rishabh Maheshwary, Saket Maheshwary and Vikram Pudi. [Generating Natural Language Attacks in a Hard Label Black Box Setting](https://arxiv.org/abs/2012.14956). AAAI 2021.

**[6]** Chenglei Si, Zhengyan Zhang, Fanchao Qi, Zhiyuan Liu, Yasheng Wang, Qun Liu, Maosong Sun. [Better Robustness by More Coverage: Adversarial Training with Mixup Augmentation for Robust Fine-tuning](https://arxiv.org/abs/2012.15699). arXiv Preprint arXiv:2012.15699 2020.

**[7]** Xinshuai Dong, Xinshuai_Dong, Anh Tuan Luu, Rongrong Ji, Hong Liu. [Towards Robustness Against Natural Language Word Substitutions](https://openreview.net/forum?id=ks5nebunVn_). ICLR 2021.

**[8]** Jin Yong Yoo, Yanjun Qi. [Towards Improving Adversarial Training of NLP Models](https://arxiv.org/abs/2109.00544). EMNLP Findings 2021.

**[9]** Rongzhou Bao, Jiayi Wang, Hai Zhao. [Defending Pre-trained Language Models from Adversarial Word Substitutions Without Performance Sacrifice](https://arxiv.org/abs/2105.14553). ACL Findings 2021.

**[10]** Yichen Yang, Xiaosen Wang, Kun He. [Robust Textual Embedding against Word-level Adversarial Attacks](https://arxiv.org/abs/2202.13817). UAI 2022.



#### Both

**[1]** Nestor Rodriguez and Sergio Rojas-Galeano. [Shielding Google's language toxicity model against adversarial attacks](https://arxiv.org/abs/1801.01828). arXiv Preprint arXiv:1801.01828 2018.

#### Certified defense

**[1]** Robin Jia, Aditi Raghunathan, Kerem Göksel and Percy Liang. [Certified Robustness to Adversarial Word Substitutions](https://arxiv.org/abs/1909.00986). EMNLP-IJCNLP 2019.

**[2]** Po-Sen Huang, Robert Stanforth, Johannes Welbl, Chris Dyer, Dani Yogatama, Sven Gowal, Krishnamurthy Dvijotham, Pushmeet Kohli. [Achieving Verified Robustness to Symbol Substitutions via Interval Bound Propagation](https://arxiv.org/abs/1909.01492). EMNLP-IJCNLP 2019.

**[3]** Jiehang Zeng, Xiaoqing Zheng, Jianhan Xu, Linyang Li, Liping Yuan, Xuanjing Huang. [Certified Robustness to Text Adversarial Attacks by Randomized [MASK]](https://arxiv.org/abs/2105.03743). ACL Findings 2021.

### Detection

**[1]** Yichao Zhou, Jyun-Yu Jiang, Kai-Wei Chang and Wei Wang. [Learning to Discriminate Perturbations for Blocking Adversarial Attacks in Text Classification](https://arxiv.org/abs/1909.03084). EMNLP-IJCNLP 2019.

**[2]** Maximilian Mozes, Pontus Stenetorp, Bennett Kleinberg, Lewis D. Griffin. [Frequency-Guided Word Substitutions for Detecting Textual Adversarial Examples](https://arxiv.org/abs/2004.05887). EACL 2021.

**[3]** Xiaosen Wang, Yifeng Xiong, Kun He. [Randomized Substitution and Vote for Textual Adversarial Example Detection](https://arxiv.org/abs/2109.05698). UAI 2022.
