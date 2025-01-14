# awesome-Federated-Learning
The repository collects papers(mainly from arxiv.org), Frameworks, projects, datasets of federated learning on bellow themes:

> * [Papers][Introduction&Survey](https://github.com/ChanChiChoi/awesome-Federated-Learning#introduction--survey)  
> * [Papers&Statistical][Distributed Optimization](https://github.com/ChanChiChoi/awesome-Federated-Learning#distributed-optimization)
> * [Papers&Statistical][Non-IID and Model Personalization](https://github.com/ChanChiChoi/awesome-Federated-Learning#non-iid-and-model-personalization)
> * [Papers&Statistical][Semi-Supervised Learning](https://github.com/ChanChiChoi/awesome-Federated-Learning#semi-supervised-learning)
> * [Papers&Statistical][Vertical Federated Learning](https://github.com/ChanChiChoi/awesome-Federated-Learning#vertical-federated-learning)
> * [Papers&Statistical][Hierarchical Federated Learning && Horizontal Federated Learning](https://github.com/ChanChiChoi/awesome-Federated-Learning#hierarchical-federated-learning--horizontal-federated-learning)
> * [Papers&Statistical][Decentralized Federated Learning](https://github.com/ChanChiChoi/awesome-Federated-Learning#decentralized-federated-learning)
> * [Papers&Statistical][Federated Transfer Learning](https://github.com/ChanChiChoi/awesome-Federated-Learning#federated-transfer-learning)
> * [Papers&Statistical][Neural Architecture Search](https://github.com/ChanChiChoi/awesome-Federated-Learning#neural-architecture-search)
> * [Papers&Statistical][Continual Learning](https://github.com/ChanChiChoi/awesome-Federated-Learning#continual-learning)
> * [Papers&Statistical][Reinforcement Learning && Robotics](https://github.com/ChanChiChoi/awesome-Federated-Learning#reinforcement-learning--robotics)
> * [Papers&Statistical][Bayesian Learning](https://github.com/ChanChiChoi/awesome-Federated-Learning#bayesian-learning)
> * [Papers&Trustworthiness][Adversarial-Attack-and-Defense](https://github.com/ChanChiChoi/awesome-Federated-Learning#adversarial-attack-and-defense)
> * [Papers&Trustworthiness][Privacy](https://github.com/ChanChiChoi/awesome-Federated-Learning#privacy--homomorphic-encryption)
> * [Papers&Trustworthiness][Incentive Mechanism && Fairness](https://github.com/ChanChiChoi/awesome-Federated-Learning#incentive-mechanism--fairness)
> * [Papers&System][Communication-Efficiency](https://github.com/ChanChiChoi/awesome-Federated-Learning#computation-efficiency)
> * [Papers&System][Straggler Problem](https://github.com/ChanChiChoi/awesome-Federated-Learning#straggler-problem)
> * [Papers&System][Computation Efficiency](https://github.com/ChanChiChoi/awesome-Federated-Learning#computation-efficiency)
> * [Papers&System][Wireless Communication && Cloud Computing && Networking](https://github.com/ChanChiChoi/awesome-Federated-Learning#wireless-communication--cloud-computing--networking)
> * [Papers&System][System Design](https://github.com/ChanChiChoi/awesome-Federated-Learning#system-design)
> * [Papers&Models][Models](https://github.com/ChanChiChoi/awesome-Federated-Learning#models)
> * [Papers&Applications][Natural language Processing](https://github.com/ChanChiChoi/awesome-Federated-Learning#natural-language-processing)
> * [Papers&Applications][Computer Vision](https://github.com/ChanChiChoi/awesome-Federated-Learning#computer-vision)
> * [Papers&Applications][Health Care](https://github.com/ChanChiChoi/awesome-Federated-Learning#health-care)
> * [Papers&Applications][Transportation](https://github.com/ChanChiChoi/awesome-Federated-Learning#transportation)
> * [Papers&Applications][Recommendation System](https://github.com/ChanChiChoi/awesome-Federated-Learning#recommendation-system)
> * [Papers&Applications][Speech Recognition](https://github.com/ChanChiChoi/awesome-Federated-Learning#speech-recognition)  
> * [Papers&Applications][Finance && Blockchain](https://github.com/ChanChiChoi/awesome-Federated-Learning#finance--blockchain)
> * [Papers&Applications][Smart City && Other Applications](https://github.com/ChanChiChoi/awesome-Federated-Learning#smart-city--other-applications)
> * [Papers&Others][uncategorized](https://github.com/ChanChiChoi/awesome-Federated-Learning#uncategorized)
> * [Blogs&&Tutorials](https://github.com/ChanChiChoi/awesome-Federated-Learning#blogs--tutorials)
> * [Framework](https://github.com/ChanChiChoi/awesome-Federated-Learning#framework)  
> * [Projects](https://github.com/ChanChiChoi/awesome-Federated-Learning#projects)
> * [Datasets && Benchmark](https://github.com/ChanChiChoi/awesome-Federated-Learning#datasets--benchmark)
> * [Scholars](https://github.com/ChanChiChoi/awesome-Federated-Learning#scholars)
> * [Conferences and Workshops](https://github.com/ChanChiChoi/awesome-Federated-Learning#conferences-and-workshops)
> * [Company](https://github.com/ChanChiChoi/awesome-Federated-Learning#company)

also, some papers and links collected from:
- [1-] [chaoyanghe/Awesome-Federated-Learning](https://github.com/chaoyanghe/Awesome-Federated-Learning)
- [2] [weimingwill/awesome-federated-learning](https://github.com/weimingwill/awesome-federated-learning)
- [3] [lokinko/Federated-Learning](https://github.com/lokinko/Federated-Learning)
- [4-] [tushar-semwal/awesome-federated-computing](https://github.com/tushar-semwal/awesome-federated-computing)
- [5-] [poga/awesome-federated-learning](https://github.com/poga/awesome-federated-learning)
- [6-] [timmers/awesome-federated-learning](https://github.com/timmers/awesome-federated-learning)
- [7-] [innovation-cat/Awesome-Federated-Machine-Learning](https://github.com/innovation-cat/Awesome-Federated-Machine-Learning)
- [8-] [ZeroWangZY/federated-learning](https://github.com/ZeroWangZY/federated-learning)
- [9-] [lee-man/federated-learning](https://github.com/lee-man/federated-learning)
- [10-] [albarqouni/Federated-Learning-In-Healthcare](https://github.com/albarqouni/Federated-Learning-In-Healthcare)
- [11][huweibo/Awesome-Federated-Learning-on-Graph-and-GNN-papers](https://github.com/huweibo/Awesome-Federated-Learning-on-Graph-and-GNN-papers)


ps:LM:Linear Models; DM:Decision Trees; NN:Neural Networks; CM:Cryptographic Methods; DP:Differential Privacy; MA:Model Aggregation

---
## Introduction && Survey
- Dwork, C. (2008). [Differential privacy: a survey of results](https://www.researchgate.net/profile/Minzhu_Xie2/publication/220908334_A_Practical_Parameterized_Algorithm_for_the_Individual_Haplotyping_Problem_MLF/links/0deec5328063473edc000000/A-Practical-Parameterized-Algorithm-for-the-Individual-Haplotyping-Problem-MLF.pdf#page=12). In TAMC’08 Proceedings of the 5th international conference on Theory and applications of models of computation (Vol. 4978, pp. 1–19).
- Dwork C. [Differential privacy in new settings](https://core.ac.uk/download/pdf/187048361.pdf)[C]//Proceedings of the twenty-first annual ACM-SIAM symposium on Discrete Algorithms. Society for Industrial and Applied Mathematics, 2010: 174-183.
- Dwork C.  [A firm foundation for private data analysis](http://www.mathcs.emory.edu/~lxiong/cs573_f18/share/readings/firm-CACM-2011.pdf) Communications of the ACM, vol. 54, no. 1, pp. 86–95, 2011
- [BOOK]Dwork C, Roth A. [The algorithmic foundations of differential privacy](http://www.tau.ac.il/~saharon/BigData2018/privacybook.pdf)[J]. Foundations and Trends in Theoretical Computer Science, 2014, 9(3-4): 211-407.
- Yu S. [Big privacy: Challenges and opportunities of privacy study in the age of big data](https://ieeexplore.ieee.org/iel7/6287639/6514899/07485855.pdf)[J]. IEEE access, 2016, 4: 2751-2763.
- Zhu T, Li G, Zhou W, et al. Differentially private data publishing and analysis: A survey[J]. IEEE Transactions on Knowledge and Data Engineering, 2017, 29(8): 1619-1638.
- Vadhan S. [The complexity of differential privacy](https://privacytools.seas.harvard.edu/files/privacytools/files/manuscript_2016.pdf)[M]//Tutorials on the Foundations of Cryptography. Springer, Cham, 2017: 347-450.
- Zhao P, Zhang G, Wan S, et al. [A survey of local differential privacy for securing internet of vehicles](https://www.researchgate.net/profile/Ping_Zhao41/publication/337842824_A_survey_of_local_differential_privacy_for_securing_internet_of_vehicles/links/5fd7308b45851553a0b573ca/A-survey-of-local-differential-privacy-for-securing-internet-of-vehicles.pdf)[J]. The Journal of Supercomputing, 2019: 1-22.
- Pejó B, Desfontaines D. [SoK: differential privacies](https://research.google/pubs/pub48777.pdf)[J]. 2020.
- Wagner I, Eckhoff D. [Technical privacy metrics: a systematic survey](https://arxiv.org/pdf/1512.00327)[J]. ACM Computing Surveys (CSUR), 2018, 51(3): 1-38.
- Ben-Nun T, Hoefler T. [Demystifying parallel and distributed deep learning: An in-depth concurrency analysis](https://arxiv.org/pdf/1802.09941)[J]. ACM Computing Surveys (CSUR), 2019, 52(4): 1-43.
- Hassan M U, Rehmani M H, Chen J. [Differential privacy techniques for cyber physical systems: a survey](https://arxiv.org/pdf/1812.02282)[J]. IEEE Communications Surveys & Tutorials, 2019, 22(1): 746-789.
- Vepakomma P, Swedish T, Raskar R, et al. [No Peek: A Survey of private distributed deep learning](https://arxiv.org/pdf/1812.03288.pdf)[J]. arXiv preprint arXiv:1812.03288, 2018.
- [TIST]Qiang Yang, Yang Liu, Tianjian Chen, Yongxin Tong .[Federated Machine Learning: Concept and Applications](https://arxiv.org/pdf/1902.04885) [J]. arXiv preprint arXiv:1902.04885.
- Han Y, Wang X, Leung V, et al. [Convergence of Edge Computing and Deep Learning: A Comprehensive Survey](https://arxiv.org/pdf/1907.08349.pdf)[J]. arXiv preprint arXiv:1907.08349, 2019.
- Qinbin Li, Zeyi Wen, Bingsheng He .[Federated Learning Systems: Vision, Hype and Reality for Data Privacy and Protection](https://arxiv.org/pdf/1907.09693) [J]. arXiv preprint arXiv:1907.09693.
- Solmaz Niknam, Harpreet S. Dhillon, Jeffery H. Reed .[Federated Learning for Wireless Communications: Motivation, Opportunities and Challenges](https://arxiv.org/pdf/1908.06847) [J]. arXiv preprint arXiv:1908.06847.
- Tian Li, Anit Kumar Sahu, Ameet Talwalkar, Virginia Smith .[Federated Learning: Challenges, Methods, and Future Directions](https://arxiv.org/pdf/1908.07873) [J]. arXiv preprint arXiv:1908.07873.
- Wei Yang Bryan Lim, Nguyen Cong Luong, Dinh Thai Hoang, Yutao Jiao, Ying-Chang Liang, Qiang Yang, Dusit Niyato, Chunyan Miao .[Federated Learning in Mobile Edge Networks: A Comprehensive Survey](https://arxiv.org/pdf/1909.11875) [J]. arXiv preprint arXiv:1909.11875.
- D. Verma, S. Calo, S. Witherspoon, E. Bertino, A. Abu Jabal, A. Swami, G. Cirincione, S. Julier, G. White, G. de Mel, G. Pearson .[Federated Learning for Coalition Operations](https://arxiv.org/pdf/1910.06799) [J]. arXiv preprint arXiv:1910.06799.
- Hsieh K. [Machine Learning Systems for Highly-Distributed and Rapidly-Growing Data](https://arxiv.org/pdf/1910.08663)[J]. arXiv preprint arXiv:1910.08663, 2019.
- Bhardwaj K, Suda N, [Marculescu R. EdgeAI: A Vision for Deep Learning in IoT Era](https://arxiv.org/pdf/1910.10356)[J]. IEEE Design & Test, 2019.
- Jie Xu, Fei Wang .[Federated Learning for Healthcare Informatics](https://arxiv.org/pdf/1911.06270) [J]. arXiv preprint arXiv:1911.06270.
- Lan Q, Zhang Z, Du Y, et al. [An Introduction to Communication Efficient Edge Machine Learning](https://arxiv.org/pdf/1912.01554)[J]. arXiv preprint arXiv:1912.01554, 2019.
- Anudit Nagar .[Privacy-Preserving Blockchain Based Federated Learning with Differential Data Sharing](https://arxiv.org/pdf/1912.04859) [J]. arXiv preprint arXiv:1912.04859.
- [good]Peter Kairouz, H. Brendan McMahan, Brendan Avent, Aurélien Bellet, Mehdi Bennis, Arjun Nitin Bhagoji, Keith Bonawitz, Zachary Charles, Graham Cormode, Rachel Cummings, Rafael G.L. D'Oliveira, Salim El Rouayheb, David Evans, Josh Gardner, Zachary Garrett, Adrià Gascón, Badih Ghazi, Phillip B. Gibbons, Marco Gruteser, Zaid Harchaoui, Chaoyang He, Lie He, Zhouyuan Huo, Ben Hutchinson, Justin Hsu, Martin Jaggi, Tara Javidi, Gauri Joshi, Mikhail Khodak, Jakub Konečný, Aleksandra Korolova, Farinaz Koushanfar, Sanmi Koyejo, Tancrède Lepoint, Yang Liu, Prateek Mittal, Mehryar Mohri, Richard Nock, Ayfer Özgür, Rasmus Pagh, Mariana Raykova, Hang Qi, Daniel Ramage, Ramesh Raskar, Dawn Song, Weikang Song, Sebastian U. Stich, Ziteng Sun, Ananda Theertha Suresh, Florian Tramèr, Praneeth Vepakomma, Jianyu Wang, Li Xiong, Zheng Xu, Qiang Yang, Felix X. Yu, Han Yu, Sen Zhao .[Advances and Open Problems in Federated Learning](https://arxiv.org/pdf/1912.04977) [J]. arXiv preprint arXiv:1912.04977.
- Shi Y, Yang K, Jiang T, et al. [Communication-efficient edge AI: Algorithms and systems](https://arxiv.org/pdf/2002.09668)[J]. arXiv preprint arXiv:2002.09668, 2020.
- Ahmed Imteaj, Urmish Thakker, Shiqiang Wang, Jian Li, M. Hadi Amini .[Federated Learning for Resource-Constrained IoT Devices: Panoramas and State-of-the-art](https://arxiv.org/pdf/2002.10610) [J]. arXiv preprint arXiv:2002.10610.
- Yilun Jin, Xiguang Wei, Yang Liu, Qiang Yang .[A Survey towards Federated Semi-supervised Learning](https://arxiv.org/pdf/2002.11545) [J]. arXiv preprint arXiv:2002.11545.
- Lingjuan Lyu, Han Yu, Qiang Yang .[Threats to Federated Learning: A Survey](https://arxiv.org/pdf/2003.02133) [J]. arXiv preprint arXiv:2003.02133.
- Viraj Kulkarni, Milind Kulkarni, Aniruddha Pant .[Survey of Personalization Techniques for Federated Learning](https://arxiv.org/pdf/2003.08673) [J]. arXiv preprint arXiv:2003.08673.
- Christopher Briggs, Zhong Fan, Peter Andras .[A Review of Privacy Preserving Federated Learning for Private IoT Analytics](https://arxiv.org/pdf/2004.11794) [J]. arXiv preprint arXiv:2004.11794.
- Yi Liu, Xingliang Yuan, Zehui Xiong, Jiawen Kang, Xiaofei Wang, Dusit Niyato .[Federated Learning for 6G Communications: Challenges, Methods, and Future Directions](https://arxiv.org/pdf/2006.02931) [J]. arXiv preprint arXiv:2006.02931.
- Seyyedali Hosseinalipour, Christopher G. Brinton, Vaneet Aggarwal, Huaiyu Dai, Mung Chiang .[From Federated Learning to Fog Learning: Towards Large-Scale Distributed Machine Learning in Heterogeneous Wireless Networks](https://arxiv.org/pdf/2006.03594) [J]. arXiv preprint arXiv:2006.03594.
- Gupta A, Lanteigne C, Kingsley S. [SECure: A Social and Environmental Certificate for AI Systems](https://arxiv.org/pdf/2006.06217)[J]. arXiv preprint arXiv:2006.06217, 2020.
- Yang M, Lyu L, Zhao J, et al. [Local differential privacy and its applications: A comprehensive survey](https://arxiv.org/pdf/2008.03686)[J]. arXiv preprint arXiv:2008.03686, 2020.
- Huang W, Zhou S, Zhu T, et al. [the Connection between Cryptography and Differential Privacy: a Survey](https://arxiv.org/pdf/2011.00976)[J]. arXiv preprint arXiv:2011.00976, 2020.
- Zhifeng Jiang, Wei Wang, Bo Li, Qiang Yang. [Towards Efficient Synchronous Federated Training: A Survey on System Optimization Strategies](https://ieeexplore.ieee.org/document/9780218) [J]. IEEE TBD 2022


## Distributed Optimization
- Konečný J, McMahan B, Ramage D. [Federated optimization: Distributed optimization beyond the datacenter](https://arxiv.org/pdf/1511.03575)[J]. arXiv preprint arXiv:1511.03575, 2015.
- 【FedAvg】[Baseline]Brendan McMahan H, Moore E, Ramage D, et al. [Communication-Efficient Learning of Deep Networks from Decentralized Data](https://arxiv.org/pdf/1602.05629.pdf)[J]. arXiv, 2016: arXiv: 1602.05629.
- Jakub Konečný, H. Brendan McMahan, Daniel Ramage, Peter Richtárik .[Federated Optimization: Distributed Machine Learning for On-Device  Intelligence](https://arxiv.org/pdf/1610.02527) [J]. arXiv preprint arXiv:1610.02527.
- [NIPS]Virginia Smith, Chao-Kai Chiang, Maziar Sanjabi, Ameet Talwalkar .[Federated Multi-Task Learning](https://arxiv.org/pdf/1705.10467) [J]. arXiv preprint arXiv:1705.10467.
- Jiang Z, Balu A, Hegde C, et al. [Collaborative Deep Learning in Fixed Topology Networks](https://arxiv.org/pdf/1706.07880.pdf)[J]. arXiv preprint arXiv:1706.07880, 2017.
- Jakub Konečný .[Stochastic, Distributed and Federated Optimization for Machine Learning](https://arxiv.org/pdf/1707.01155) [J]. arXiv preprint arXiv:1707.01155.
- Wang S, Tuor T, Salonidis T, et al. [Adaptive Federated Learning in Resource Constrained Edge Computing Systems](https://arxiv.org/pdf/1804.05271.pdf)[J]. arXiv preprint arXiv:1804.05271, 2018.
- Stich S U.[Local SGD converges fast and communicates little](https://arxiv.org/pdf/1805.09767.pdf)[J]. arXiv preprint arXiv:1805.09767, 2018.
- Tianyi Chen, Georgios B. Giannakis, Tao Sun, Wotao Yin[LAG: Lazily Aggregated Gradient for Communication-Efficient Distributed Learning](https://arxiv.org/abs/1805.09965) [J]. arXiv preprint arXiv:1805.09965.
- Agarwal, Naman, et al. [CpSGD: Communication-Efficient and Differentially-Private Distributed SGD.](https://arxiv.org/abs/1805.10559) NIPS’18 Proceedings of the 32nd International Conference on Neural Information Processing Systems, vol. 31, 2018, pp. 7575–7586.
- Lin T, Stich S U, Patel K K, et al. [Don't Use Large Mini-Batches, Use Local SGD](https://arxiv.org/pdf/1808.07217)[J]. arXiv preprint arXiv:1808.07217, 2018.
- Wang J, Joshi G. [Cooperative SGD: A unified framework for the design and analysis of communication-efficient SGD algorithms](https://arxiv.org/pdf/1808.07576)[J]. arXiv preprint arXiv:1808.07576, 2018.
- Koskela A, Honkela A. [Learning Rate Adaptation for Federated and Differentially Private Learning](https://arxiv.org/pdf/1809.03832)[J]. arXiv preprint arXiv:1809.03832, 2018.
- Bui T D, Nguyen C V, Swaroop S, et al. [Partitioned variational inference: A unified framework encompassing federated and continual learning](https://arxiv.org/pdf/1811.11206)[J]. arXiv preprint arXiv:1811.11206, 2018.
- Li T, Sahu A K, Zaheer M, et al. [Federated optimization in heterogeneous networks](https://proceedings.mlsys.org/paper/2020/file/38af86134b65d0f10fe33d30dd76442e-Paper.pdf)[J]. Proceedings of Machine Learning and Systems, 2020, 2: 429-450.<br>[code:[litian96/FedProx](https://github.com/litian96/FedProx)]
- Anit Kumar Sahu, Tian Li, Maziar Sanjabi, Manzil Zaheer, Ameet Talwalkar, Virginia Smith .[On the Convergence of Federated Optimization in Heterogeneous Networks](https://arxiv.org/pdf/1812.06127) [J]. arXiv preprint arXiv:1812.06127.
- Mohri M, Sivek G, Suresh A T. [Agnostic federated learning](https://arxiv.org/pdf/1902.00146)[J]. arXiv preprint arXiv:1902.00146, 2019.
- Neel Guha, Ameet Talwalkar, Virginia Smith .[One-Shot Federated Learning](https://arxiv.org/pdf/1902.11175) [J]. arXiv preprint arXiv:1902.11175.
- Xie C, Koyejo S, Gupta I. [Asynchronous federated optimization](https://arxiv.org/pdf/1903.03934)[J]. arXiv preprint arXiv:1903.03934, 2019.
- Eichner H, Koren T, McMahan H B, et al. [Semi-cyclic stochastic gradient descent](https://arxiv.org/pdf/1904.10120)[J]. arXiv preprint arXiv:1904.10120, 2019.
- Thakkar O, Andrew G, McMahan H B. [Differentially private learning with adaptive clipping](https://arxiv.org/pdf/1905.03871)[J]. arXiv preprint arXiv:1905.03871, 2019.
- [ICML]Mikhail Yurochkin, Mayank Agarwal, Soumya Ghosh, Kristjan Greenewald, Trong Nghia Hoang, Yasaman Khazaeni .[Bayesian Nonparametric Federated Learning of Neural Networks](https://arxiv.org/pdf/1905.12022) [J]. arXiv preprint arXiv:1905.12022.<br>[code:[IBM/probabilistic-federated-neural-matching](https://github.com/IBM/probabilistic-federated-neural-matching)]
- [good]Luca Corinzia, Joachim M. Buhmann .[Variational Federated Multi-Task Learning](https://arxiv.org/pdf/1906.06268) [J]. arXiv preprint arXiv:1906.06268.
- Avishek Ghosh, Justin Hong, Dong Yin, Kannan Ramchandran .[Robust Federated Learning in a Heterogeneous Environment](https://arxiv.org/pdf/1906.06629) [J]. arXiv preprint arXiv:1906.06629.
- Ghazi B, Pagh R, Velingker A. [Scalable and differentially private distributed aggregation in the shuffled model](https://arxiv.org/pdf/1906.08320)[J]. arXiv preprint arXiv:1906.08320, 2019.
- Khaled A, Mishchenko K, Richtárik P. [First analysis of local gd on heterogeneous data](https://arxiv.org/pdf/1909.04715)[J]. arXiv preprint arXiv:1909.04715, 2019.
- Khaled A, Richtárik P. [Gradient descent with compressed iterates](https://arxiv.org/pdf/1909.04716)[J]. arXiv preprint arXiv:1909.04716, 2019.
- Khaled A, Mishchenko K, Richtárik P. [Tighter theory for local SGD on identical and heterogeneous data](https://arxiv.org/pdf/1909.04746.pdf)[C]//International Conference on Artificial Intelligence and Statistics. PMLR, 2020: 4519-4529.
- Li B, Cen S, Chen Y, et al. [Communication-efficient distributed optimization in networks with gradient tracking](https://arxiv.org/pdf/1909.05844)[J]. arXiv preprint arXiv:1909.05844, 2019.
- Wei Liu, Li Chen, Yunfei Chen, Wenyi Zhang .[Accelerating Federated Learning via Momentum Gradient Descent](https://arxiv.org/pdf/1910.03197) [J]. arXiv preprint arXiv:1910.03197.
- Chaoyang He, Conghui Tan, Hanlin Tang, Shuang Qiu, Ji Liu .[Central Server Free Federated Learning over Single-sided Trust Social Networks](https://arxiv.org/pdf/1910.04956) [J]. arXiv preprint arXiv:1910.04956.
- [ICML][no IID]Sai Praneeth Karimireddy, Satyen Kale, Mehryar Mohri, Sashank J. Reddi, Sebastian U. Stich, Ananda Theertha Suresh .[SCAFFOLD: Stochastic Controlled Averaging for On-Device Federated Learning](https://arxiv.org/pdf/1910.06378) [J]. arXiv preprint arXiv:1910.06378.<br>[video:[scaffold-stochastic-controlled-averaging-for-federated-learning](https://slideslive.com/38927610/scaffold-stochastic-controlled-averaging-for-federated-learning)]
- Xin Yao, Tianchi Huang, Rui-Xiao Zhang, Ruiyu Li, Lifeng Sun .[Federated Learning with Unbiased Gradient Aggregation and Controllable Meta Updating](https://arxiv.org/pdf/1910.08234) [J]. arXiv preprint arXiv:1910.08234.
- Farzin Haddadpour, Mehrdad Mahdavi .[On the Convergence of Local Descent Methods in Federated Learning](https://arxiv.org/pdf/1910.14425) [J]. arXiv preprint arXiv:1910.14425.
- Saeedeh Parsaeefard, Iman Tabrizian, Alberto Leon Garcia .[Representation of Federated Learning via Worst-Case Robust Optimization Theory](https://arxiv.org/pdf/1912.05571) [J]. arXiv preprint arXiv:1912.05571.
- Sharma P, Khanduri P, Bulusu S, et al. [Parallel Restarted SPIDER--Communication Efficient Distributed Nonconvex Optimization with Optimal Computation Complexity](https://arxiv.org/pdf/1912.06036)[J]. arXiv preprint arXiv:1912.06036, 2019.
- Jakovetić D, Bajović D, Xavier J, et al. [Primal–Dual Methods for Large-Scale and Distributed Convex Optimization and Data Analytics](https://arxiv.org/pdf/1912.08546.pdf)J]. Proceedings of the IEEE, 2020, 108(11): 1923-1938.
- Chraibi S, Khaled A, Kovalev D, et al. [Distributed Fixed Point Methods with Compressed Iterates](https://arxiv.org/pdf/1912.09925)[J]. arXiv preprint arXiv:1912.09925, 2019.
- Tian Li, Anit Kumar Sahu, Manzil Zaheer, Maziar Sanjabi, Ameet Talwalkar, Virginia Smith .[FedDANE: A Federated Newton-Type Method](https://arxiv.org/pdf/2001.01920) [J]. arXiv preprint arXiv:2001.01920.
- Zhouyuan Huo, Qian Yang, Bin Gu, Lawrence Carin. Heng Huang .[Faster On-Device Training Using New Federated Momentum Algorithm](https://arxiv.org/pdf/2002.02090) [J]. arXiv preprint arXiv:2002.02090.
- Filip Hanzely, Peter Richtárik .[Federated Learning of a Mixture of Global and Local Models](https://arxiv.org/pdf/2002.05516) [J]. arXiv preprint arXiv:2002.05516.
- [ICLR]Hongyi Wang, Mikhail Yurochkin, Yuekai Sun, Dimitris Papailiopoulos, Yasaman Khazaeni .[Federated Learning with Matched Averaging](https://arxiv.org/pdf/2002.06440) [J]. arXiv preprint arXiv:2002.06440.<br>[code:[IBM/FedMA](https://github.com/IBM/FedMA)]
- Yan Y, Niu C, Ding Y, et al. [Distributed Non-Convex Optimization with Sublinear Speedup under Intermittent Client Availability](https://arxiv.org/pdf/2002.07399)[J]. arXiv preprint arXiv:2002.07399, 2020.
- Ding Y, Niu C, Yan Y, et al. [Distributed Optimization over Block-Cyclic Data](https://arxiv.org/pdf/2002.07454)[J]. arXiv preprint arXiv:2002.07454, 2020.
- Elsa Rizk, Stefan Vlaski, Ali H. Sayed .[Dynamic Federated Learning](https://arxiv.org/pdf/2002.08782) [J]. arXiv preprint arXiv:2002.08782.
- Mher Safaryan, Egor Shulgin, Peter Richtárik .[Uncertainty Principle for Communication Compression in Distributed and Federated Learning and the Search for an Optimal Compressor](https://arxiv.org/pdf/2002.08958) [J]. arXiv preprint arXiv:2002.08958.
- Wang J, Liang H, Joshi G. [Overlap Local-SGD: An Algorithmic Approach to Hide Communication Delays in Distributed SGD](https://arxiv.org/pdf/2002.09539.pdf)[J]. arXiv preprint arXiv:2002.09539, 2020.
- Qiong Wu, Kaiwen He, Xu Chen .[Personalized Federated Learning for Intelligent IoT Applications: A Cloud-Edge based Framework](https://arxiv.org/pdf/2002.10671) [J]. arXiv preprint arXiv:2002.10671.
- Yassine Laguel, Krishna Pillutla, Jérôme Malick, Zaid Harchaoui .[Device Heterogeneity in Federated Learning: A Superquantile Approach](https://arxiv.org/pdf/2002.11223) [J]. arXiv preprint arXiv:2002.11223.
- Chen T, Sun Y, Yin W. [LASG: Lazily Aggregated Stochastic Gradients for Communication-Efficient Distributed Learning](https://arxiv.org/pdf/2002.11360)[J]. arXiv preprint arXiv:2002.11360, 2020.
- [ICML]Zhize Li, Dmitry Kovalev, Xun Qian, Peter Richtárik .[Acceleration for Compressed Gradient Descent in Distributed and Federated Optimization](https://arxiv.org/pdf/2002.11364) [J]. arXiv preprint arXiv:2002.11364.<br>[video:[v1](https://slideslive.com/38927921/acceleration-for-compressed-gradient-descent-in-distributed-optimization)]
- [Baseline]Sashank Reddi, Zachary Charles, Manzil Zaheer, Zachary Garrett, Keith Rush, Jakub Konečný, Sanjiv Kumar, H. Brendan McMahan .[Adaptive Federated Optimization](https://arxiv.org/pdf/2003.00295) [J]. arXiv preprint arXiv:2003.00295.
- Alekh Agarwal, John Langford, Chen-Yu Wei .[Federated Residual Learning](https://arxiv.org/pdf/2003.12880) [J]. arXiv preprint arXiv:2003.12880.
- [ICML][communication]Grigory Malinovsky, Dmitry Kovalev, Elnur Gasanov, Laurent Condat, Peter Richtarik .[From Local SGD to Local Fixed Point Methods for Federated Learning](https://arxiv.org/pdf/2004.01442) [J]. arXiv preprint arXiv:2004.01442.<br>[video:[v1](https://slideslive.com/38928320/from-local-sgd-to-local-fixed-point-methods-for-federated-learning)]
- Khanduri P, Sharma P, Kafle S, et al. [Distributed Stochastic Non-Convex Optimization: Momentum-Based Variance Reduction](https://arxiv.org/pdf/2005.00224)[J]. arXiv preprint arXiv:2005.00224, 2020.
- [NIPS][Acceleration]Reese Pathak, Martin J. Wainwright .[FedSplit: An algorithmic framework for fast federated optimization](https://arxiv.org/pdf/2005.05238) [J]. arXiv preprint arXiv:2005.05238.
- Han Cha, Jihong Park, Hyesung Kim, Mehdi Bennis, Seong-Lyun Kim .[Proxy Experience Replay: Federated Distillation for Distributed Reinforcement Learning](https://arxiv.org/pdf/2005.06105) [J]. arXiv preprint arXiv:2005.06105.
- Spiridonoff A, Olshevsky A, [Paschalidis I C. Local SGD With a Communication Overhead Depending Only on the Number of Workers](https://arxiv.org/pdf/2006.02582)[J]. arXiv preprint arXiv:2006.02582, 2020.
- Yi X, Zhang S, Yang T, et al. [A Primal-Dual SGD Algorithm for Distributed Nonconvex Optimization](https://arxiv.org/pdf/2006.03474)[J]. arXiv preprint arXiv:2006.03474, 2020.
- Shen S, Cheng Y, Liu J, et al. [STL-SGD: Speeding Up Local SGD with Stagewise Communication Period](https://arxiv.org/pdf/2006.06377)[J]. arXiv preprint arXiv:2006.06377, 2020.
- Om Thakkar, Swaroop Ramaswamy, Rajiv Mathews, Françoise Beaufays .[Understanding Unintended Memorization in Federated Learning](https://arxiv.org/pdf/2006.07490) [J]. arXiv preprint arXiv:2006.07490.
- [NIPS][Privacy]Amirhossein Reisizadeh, Farzan Farnia, Ramtin Pedarsani, Ali Jadbabaie .[Robust Federated Learning: The Case of Affine Distribution Shifts](https://arxiv.org/pdf/2006.08907) [J]. arXiv preprint arXiv:2006.08907.
- [NIPS]Honglin Yuan, Tengyu Ma .[Federated Accelerated Stochastic Gradient Descent](https://arxiv.org/pdf/2006.08950) [J]. arXiv preprint arXiv:2006.08950.<br>[code:[hongliny/FedAc-NeurIPS20](https://github.com/hongliny/FedAc-NeurIPS20)]
- Yanjie Dong, Georgios B. Giannakis, Tianyi Chen, Julian Cheng, Md. Jahangir Hossain, Victor C. M. Leung .[Communication-Efficient Robust Federated Learning Over Heterogeneous Datasets](https://arxiv.org/pdf/2006.09992) [J]. arXiv preprint arXiv:2006.09992.
- Ye T, Xiao P, Sun R. [DEED: A General Quantization Scheme for Communication Efficiency in Bits](https://arxiv.org/pdf/2006.11401)[J]. arXiv preprint arXiv:2006.11401, 2020.
- Adarsh Barik, Jean Honorio .[Exact Support Recovery in Federated Regression with One-shot Communication](https://arxiv.org/pdf/2006.12583) [J]. arXiv preprint arXiv:2006.12583.
- Thinh T. Doan .[Local Stochastic Approximation: A Unified View of Federated Learning and Distributed Multi-Task Reinforcement Learning Algorithms](https://arxiv.org/pdf/2006.13460) [J]. arXiv preprint arXiv:2006.13460.
- Charles Z, Konečný J. [On the outsized importance of learning rates in local update methods](https://arxiv.org/pdf/2007.00878)[J]. arXiv preprint arXiv:2007.00878, 2020.
- [Baseline][NIPS]Jianyu Wang, Qinghua Liu, Hao Liang, Gauri Joshi, H. Vincent Poor .[Tackling the Objective Inconsistency Problem in Heterogeneous Federated Optimization](https://arxiv.org/pdf/2007.07481) [J]. arXiv preprint arXiv:2007.07481.
- Farzin Haddadpour, Mohammad Mahdi Kamani, Aryan Mokhtari, Mehrdad Mahdavi .[Federated Learning with Compression: Unified Analysis and Sharp Guarantees](https://arxiv.org/pdf/2007.01154) [J]. arXiv preprint arXiv:2007.01154.
- Amani Abu Jabal, Elisa Bertino, Jorge Lobo, Dinesh Verma, Seraphin Calo, Alessandra Russo .[FLAP -- A Federated Learning Framework for Attribute-based Access Control Policies](https://arxiv.org/pdf/2010.09767) [J]. arXiv preprint arXiv:2010.09767.


## Non-IID and Model Personalization
- Takayuki Nishio, Ryo Yonetani .[Client Selection for Federated Learning with Heterogeneous Resources in  Mobile Edge](https://arxiv.org/pdf/1804.08333) [J]. arXiv preprint arXiv:1804.08333.
- Yue Zhao, Meng Li, Liangzhen Lai, Naveen Suda, Damon Civin, Vikas Chandra .[Federated Learning with Non-IID Data](https://arxiv.org/pdf/1806.00582) [J]. arXiv preprint arXiv:1806.00582.
- Eunjeong Jeong, Seungeun Oh, Hyesung Kim, Jihong Park, Mehdi Bennis, Seong-Lyun Kim .[Communication-Efficient On-Device Machine Learning: Federated Distillation and Augmentation under Non-IID Private Data](https://arxiv.org/pdf/1811.11479) [J]. arXiv preprint arXiv:1811.11479.
- Xudong Sun, Andrea Bommert, Florian Pfisterer, Jörg Rahnenführer, Michel Lang, Bernd Bischl .[High Dimensional Restrictive Federated Model Selection with multi-objective Bayesian Optimization over shifted distributions](https://arxiv.org/pdf/1902.08999) [J]. arXiv preprint arXiv:1902.08999.
- [good]Felix Sattler, Simon Wiedemann, Klaus-Robert Müller, Wojciech Samek .[Robust and Communication-Efficient Federated Learning from Non-IID Data](https://arxiv.org/pdf/1903.02891) [J]. arXiv preprint arXiv:1903.02891.
- Yoshida N, Nishio T, Morikura M, et al. [Hybrid-FL for wireless networks: Cooperative learning mechanism using non-IID data](https://arxiv.org/pdf/1905.07210)[C]//ICC 2020-2020 IEEE International Conference on Communications (ICC). IEEE, 2020: 1-7.
- Chen X, Chen T, Sun H, et al. [Distributed training with heterogeneous data: Bridging median-and mean-based algorithms](https://arxiv.org/pdf/1906.01736.pdf)[J]. Advances in Neural Information Processing Systems, 2020, 33.
- Moming Duan .[Astraea: Self-balancing Federated Learning for Improving Classification Accuracy of Mobile Deep Learning Applications](https://arxiv.org/pdf/1907.01132) [J]. arXiv preprint arXiv:1907.01132.
- [ICLR]Li X, Huang K, Yang W, et al. [On the convergence of fedavg on non-iid data](https://arxiv.org/pdf/1907.02189)[J]. arXiv preprint arXiv:1907.02189, 2019.<br>[code:[lx10077/fedavgpy](https://github.com/lx10077/fedavgpy)]
- Eunjeong Jeong, Seungeun Oh, Jihong Park, Hyesung Kim, Mehdi Bennis, Seong-Lyun Kim .[Multi-hop Federated Private Data Augmentation with Sample Compression](https://arxiv.org/pdf/1907.06426) [J]. arXiv preprint arXiv:1907.06426.
- Tzu-Ming Harry Hsu, Hang Qi, Matthew Brown .[Measuring the Effects of Non-Identical Data Distribution for Federated Visual Classification](https://arxiv.org/pdf/1909.06335) [J]. arXiv preprint arXiv:1909.06335.
- Guan Wang, Charlie Xiaoqian Dang, Ziye Zhou .[Measure Contribution of Participants in Federated Learning](https://arxiv.org/pdf/1909.08525) [J]. arXiv preprint arXiv:1909.08525.
- Yihan Jiang, Jakub Konečný, Keith Rush, Sreeram Kannan .[Improving Federated Learning Personalization via Model Agnostic Meta Learning](https://arxiv.org/pdf/1909.12488) [J]. arXiv preprint arXiv:1909.12488.
- Hsieh K, Phanishayee A, Mutlu O, et al. [The non-iid data quagmire of decentralized machine learning](https://arxiv.org/abs/1910.00189)[C]//International Conference on Machine Learning. PMLR, 2020: 4387-4398.
- Felix Sattler, Klaus-Robert Müller, Wojciech Samek .[Clustered Federated Learning: Model-Agnostic Distributed Multi-Task Optimization under Privacy Constraints](https://arxiv.org/pdf/1910.01991) [J]. arXiv preprint arXiv:1910.01991.
- Neta Shoham (Edgify), Tomer Avidor (Edgify), Aviv Keren (Edgify), Nadav Israel (Edgify), Daniel Benditkis (Edgify), Liron Mor-Yosef (Edgify), Itai Zeitak (Edgify) .[Overcoming Forgetting in Federated Learning on Non-IID Data](https://arxiv.org/pdf/1910.07796) [J]. arXiv preprint arXiv:1910.07796.
- Xin Yao, Tianchi Huang, Rui-Xiao Zhang, Ruiyu Li, Lifeng Sun .[Federated Learning with Unbiased Gradient Aggregation and Controllable Meta Updating](https://arxiv.org/pdf/1910.08234) [J]. arXiv preprint arXiv:1910.08234.
- Kangkang Wang, Rajiv Mathews, Chloé Kiddon, Hubert Eichner, Françoise Beaufays, Daniel Ramage .[Federated Evaluation of On-device Personalization](https://arxiv.org/pdf/1910.10252) [J]. arXiv preprint arXiv:1910.10252.
- [ICLR]Xingchao Peng, Zijun Huang, Yizhe Zhu, Kate Saenko .[Federated Adversarial Domain Adaptation](https://arxiv.org/pdf/1911.02054) [J]. arXiv preprint arXiv:1911.02054.
- Manoj Ghuhan Arivazhagan, Vinay Aggarwal, Aaditya Kumar Singh, Sunav Choudhary .[Federated Learning with Personalization Layers](https://arxiv.org/pdf/1912.00818) [J]. arXiv preprint arXiv:1912.00818.
- Hesham Mostafa .[Robust Federated Learning Through Representation Matching and Adaptive Hyper-parameters](https://arxiv.org/pdf/1912.13075) [J]. arXiv preprint arXiv:1912.13075.
- Paul Pu Liang, Terrance Liu, Liu Ziyin, Ruslan Salakhutdinov, Louis-Philippe Morency .[Think Locally, Act Globally: Federated Learning with Local and Global Representations](https://arxiv.org/pdf/2001.01523) [J]. arXiv preprint arXiv:2001.01523.
- Sen Lin, Guang Yang, Junshan Zhang .[A Collaborative Learning Framework via Federated Meta-Learning](https://arxiv.org/pdf/2001.03229) [J]. arXiv preprint arXiv:2001.03229.
- Tiffany Tuor, Shiqiang Wang, Bong Jun Ko, Changchang Liu, Kin K. Leung .[Data Selection for Federated Learning with Relevant and Irrelevant Data at Clients](https://arxiv.org/pdf/2001.08300) [J]. arXiv preprint arXiv:2001.08300.
- Yiqiang Chen, Xiaodong Yang, Xin Qin, Han Yu, Biao Chen, Zhiqi Shen .[FOCUS: Dealing with Label Quality Disparity in Federated Learning](https://arxiv.org/pdf/2001.11359) [J]. arXiv preprint arXiv:2001.11359.
- Tao Yu, Eugene Bagdasaryan, Vitaly Shmatikov .[Salvaging Federated Learning by Local Adaptation](https://arxiv.org/pdf/2002.04758) [J]. arXiv preprint arXiv:2002.04758.
- Jia Qian, Xenofon Fafoutis, Lars Kai Hansen .[Towards Federated Learning: Robustness Analytics to Data Heterogeneity](https://arxiv.org/pdf/2002.05038) [J]. arXiv preprint arXiv:2002.05038.
- Alireza Fallah, Aryan Mokhtari, Asuman Ozdaglar .[Personalized Federated Learning: A Meta-Learning Approach](https://arxiv.org/pdf/2002.07948) [J]. arXiv preprint arXiv:2002.07948.
- Yishay Mansour, Mehryar Mohri, Jae Ro, Ananda Theertha Suresh .[Three Approaches for Personalization with Applications to Federated Learning](https://arxiv.org/pdf/2002.10619) [J]. arXiv preprint arXiv:2002.10619.
- Viraj Kulkarni, Milind Kulkarni, Aniruddha Pant .[Survey of Personalization Techniques for Federated Learning](https://arxiv.org/pdf/2003.08673) [J]. arXiv preprint arXiv:2003.08673.
- Zhikun Chen, Daofeng Li, Ming Zhao, Sihai Zhang, Jinkang Zhu .[Semi-Federated Learning](https://arxiv.org/pdf/2003.12795) [J]. arXiv preprint arXiv:2003.12795.
- Yuyang Deng, Mohammad Mahdi Kamani, Mehrdad Mahdavi .[Adaptive Personalized Federated Learning](https://arxiv.org/pdf/2003.13461) [J]. arXiv preprint arXiv:2003.13461.
- Wei Chen, Kartikeya Bhardwaj, Radu Marculescu .[FedMAX: Mitigating Activation Divergence for Accurate and Communication-Efficient Federated Learning](https://arxiv.org/pdf/2004.03657) [J]. arXiv preprint arXiv:2004.03657.
- [ICML]Felix X. Yu, Ankit Singh Rawat, Aditya Krishna Menon, Sanjiv Kumar .[Federated Learning with Only Positive Labels](https://arxiv.org/pdf/2004.10342) [J]. arXiv preprint arXiv:2004.10342.<br>[video:[federated-learning-with-only-positive-labels](https://slideslive.com/38928322/federated-learning-with-only-positive-labels)]
- Christopher Briggs, Zhong Fan, Peter Andras .[Federated learning with hierarchical clustering of local updates to improve training on non-IID data](https://arxiv.org/pdf/2004.11791) [J]. arXiv preprint arXiv:2004.11791.
- Ming Xie, Guodong Long, Tao Shen, Tianyi Zhou, Xianzhi Wang, Jing Jiang .[Multi-Center Federated Learning](https://arxiv.org/pdf/2005.01026) [J]. arXiv preprint arXiv:2005.01026.
- Han Cha, Jihong Park, Hyesung Kim, Mehdi Bennis, Seong-Lyun Kim .[Proxy Experience Replay: Federated Distillation for Distributed Reinforcement Learning](https://arxiv.org/pdf/2005.06105) [J]. arXiv preprint arXiv:2005.06105.
- Ahn S, Ozgur A, Pilanci M. [Global Multiclass Classification from Heterogeneous Local Models](https://arxiv.org/pdf/2005.10848)[J]. arXiv preprint arXiv:2005.10848, 2020.
- Xinwei Zhang, Mingyi Hong, Sairaj Dhople, Wotao Yin, Yang Liu .[FedPD: A Federated Learning Framework with Optimal Rates and Adaptivity to Non-IID Data](https://arxiv.org/pdf/2005.11418) [J]. arXiv preprint arXiv:2005.11418.
- Cong Wang, Yuanyuan Yang, Pengzhan Zhou .[Towards Efficient Scheduling of Federated Mobile Devices under Computational and Statistical Heterogeneity](https://arxiv.org/pdf/2005.12326) [J]. arXiv preprint arXiv:2005.12326.
- Xin Yao, Lifeng Sun .[Continual Local Training for Better Initialization of Federated Models](https://arxiv.org/pdf/2005.12657) [J]. arXiv preprint arXiv:2005.12657.
- [NIPS]Avishek Ghosh, Jichan Chung, Dong Yin, Kannan Ramchandran .[An Efficient Framework for Clustered Federated Learning](https://arxiv.org/pdf/2006.04088) [J]. arXiv preprint arXiv:2006.04088.
- MyungJae Shin, Chihoon Hwang, Joongheon Kim, Jihong Park, Mehdi Bennis, Seong-Lyun Kim .[XOR Mixup: Privacy-Preserving Data Augmentation for One-Shot Federated Learning](https://arxiv.org/pdf/2006.05148) [J]. arXiv preprint arXiv:2006.05148.
- Yichen Ruan, Xiaoxi Zhang, Shu-Che Liang, Carlee Joe-Wong .[Towards Flexible Device Participation in Federated Learning for Non-IID Data](https://arxiv.org/pdf/2006.06954) [J]. arXiv preprint arXiv:2006.06954.
- [NIPS]Tao Lin, Lingjing Kong, Sebastian U. Stich, Martin Jaggi .[Ensemble Distillation for Robust Model Fusion in Federated Learning](https://arxiv.org/pdf/2006.07242) [J]. arXiv preprint arXiv:2006.07242.
- [NIPS]Canh T. Dinh, Nguyen H. Tran, Tuan Dung Nguyen .[Personalized Federated Learning with Moreau Envelopes](https://arxiv.org/pdf/2006.08848) [J]. arXiv preprint arXiv:2006.08848.<br>[code:[CharlieDinh/pFedMe](https://github.com/CharlieDinh/pFedMe)]
- [NIPS][Privacy]Amirhossein Reisizadeh, Farzan Farnia, Ramtin Pedarsani, Ali Jadbabaie .[Robust Federated Learning: The Case of Affine Distribution Shifts](https://arxiv.org/pdf/2006.08907) [J]. arXiv preprint arXiv:2006.08907.
- Kavya Kopparapu, Eric Lin, Jessica Zhao .[FedCD: Improving Performance in non-IID Federated Learning](https://arxiv.org/pdf/2006.09637) [J]. arXiv preprint arXiv:2006.09637.
- Kavya Kopparapu, Eric Lin .[FedFMC: Sequential Efficient Federated Learning on Non-iid Data](https://arxiv.org/pdf/2006.10937) [J]. arXiv preprint arXiv:2006.10937.
- Wonyong Jeong, Jaehong Yoon, Eunho Yang, Sung Ju Hwang .[Federated Semi-Supervised Learning with Inter-Client Consistency](https://arxiv.org/pdf/2006.12097) [J]. arXiv preprint arXiv:2006.12097.
- Laura Rieger, Rasmus M. Th. Høegh, Lars K. Hansen .[Client Adaptation improves Federated Learning with Simulated Non-IID Clients](https://arxiv.org/pdf/2007.04806) [J]. arXiv preprint arXiv:2007.04806.


## Semi-Supervised Learning
- Papernot N, Abadi M, Erlingsson U, et al. [Semi-supervised knowledge transfer for deep learning from private training data](https://arxiv.org/pdf/1610.05755.pdf,)[J]. arXiv preprint arXiv:1610.05755, 2016.
- Papernot N, Song S, Mironov I, et al. [Scalable private learning with pate](https://arxiv.org/pdf/1802.08908.pdf?ref=hackernoon.com)[J]. arXiv preprint arXiv:1802.08908, 2018.
- Wonyong Jeong, Jaehong Yoon, Eunho Yang, Sung Ju Hwang .[Federated Semi-Supervised Learning with Inter-Client Consistency](https://arxiv.org/pdf/2006.12097) [J]. arXiv preprint arXiv:2006.12097.


## Vertical Federated Learning
- [LM][CM]A. P. Sanil, A. F. Karr, X. Lin, and J. P. Reiter, "Privacy preserving regression modelling via distributed computation," in Proceedings of the tenth ACM SIGKDD international conference on Knowledge discovery and data mining. ACM, 2004, pp. 677–682.
- [LM][CM]Stephen Hardy, Wilko Henecka, Hamish Ivey-Law, Richard Nock, Giorgio Patrini, Guillaume Smith, Brian Thorne .[Private federated learning on vertically partitioned data via entity  resolution and additively homomorphic encryption](https://arxiv.org/pdf/1711.10677) [J]. arXiv preprint arXiv:1711.10677.
-  .[Entity Resolution and Federated Learning get a Federated Resolution](https://arxiv.org/pdf/1803.04035) [J]. arXiv preprint arXiv:1803.04035.
- [NN][CM]Y. Liu, T. Chen, and Q. Yang, [Secure federated transfer learning](https://arxiv.org/pdf/1812.03337)[J] arXiv preprint arXiv:1812.03337, 2018.
- [DT][CM]Kewei Cheng, Tao Fan, Yilun Jin, Yang Liu, Tianjian Chen, Qiang Yang .[SecureBoost: A Lossless Federated Learning Framework](https://arxiv.org/pdf/1901.08755) [J]. arXiv preprint arXiv:1901.08755.
- Shengwen Yang, Bing Ren, Xuhui Zhou, Liping Liu .[Parallel Distributed Logistic Regression for Vertical Federated Learning without Third-Party Coordinator](https://arxiv.org/pdf/1911.09824) [J]. arXiv preprint arXiv:1911.09824.
- Kai Yang, Tao Fan, Tianjian Chen, Yuanming Shi, Qiang Yang .[A Quasi-Newton Method Based Vertical Federated Learning Framework for Logistic Regression](https://arxiv.org/pdf/1912.00513) [J]. arXiv preprint arXiv:1912.00513.
- Yang Liu, Yan Kang, Xinwei Zhang, Liping Li, Yong Cheng, Tianjian Chen, Mingyi Hong, Qiang Yang .[A Communication Efficient Vertical Federated Learning Framework](https://arxiv.org/pdf/1912.11187) [J]. arXiv preprint arXiv:1912.11187.
- Siwei Feng, Han Yu .[Multi-Participant Multi-Class Vertical Federated Learning](https://arxiv.org/pdf/2001.11154) [J]. arXiv preprint arXiv:2001.11154.
- Yang Liu, Xiong Zhang, Libin Wang .[Asymmetrical Vertical Federated Learning](https://arxiv.org/pdf/2004.07427) [J]. arXiv preprint arXiv:2004.07427.
- Tianyi Chen, Xiao Jin, Yuejiao Sun, Wotao Yin .[VAFL: a Method of Vertical Asynchronous Federated Learning](https://arxiv.org/pdf/2007.06081) [J]. arXiv preprint arXiv:2007.06081.


## Hierarchical Federated Learning && Horizontal Federated Learning
- [NN][MA]P. Blanchard, R. Guerraoui, J. Stainer et al., "Machine learning with adversaries: Byzantine tolerant gradient descent," in Advances in Neural Information Processing Systems, 2017, pp. 119–129. 
- [LM][CM]V. Nikolaenko, U. Weinsberg, S. Ioannidis, M. Joye, D. Boneh, and N. Taft, "Privacy-preserving ridge regression on hundreds of millions of records," in 2013 IEEE Symposium on Security and Privacy. IEEE, 2013, pp. 334–348.
- [LM][MA]Y. Chen, L. Su, and J. Xu, "Distributed statistical machine learning in adversarial settings: Byzantine gradient descent," Proceedings of the ACM on Measurement and Analysis of Computing Systems, vol. 1, no. 2, p. 44, 2017.
- [DT][DP]L. Zhao, L. Ni, S. Hu, Y. Chen, P. Zhou, F. Xiao, and L. Wu, "Inprivate digging: Enabling tree-based distributed data mining with differential privacy," in INFOCOM. IEEE, 2018, pp. 2087–2095.
- [LM][CM]Y.-R. Chen, A. Rezapour, and W.-G. Tzeng, "Privacy-preserving ridge regression on distributed data," Information Sciences, vol. 451, pp. 34–49, 2018.
- [NN][MA] Nilsson A, Smith S, Ulm G, et al. [A performance evaluation of federated learning algorithms](https://www.researchgate.net/profile/Gregor_Ulm/publication/329106719_A_Performance_Evaluation_of_Federated_Learning_Algorithms/links/5c0fabcfa6fdcc494febf907/A-Performance-Evaluation-of-Federated-Learning-Algorithms.pdf)[C]//Proceedings of the Second Workshop on Distributed Infrastructures for Deep Learning. 2018: 1-8.
- [NN][DP,MA]Shokri R, Shmatikov V. [Privacy-preserving deep learning](http://www.cs.cornell.edu/~shmat/shmat_ccs15.pdf)[C]//Proceedings of the 22nd ACM SIGSAC conference on computer and communications security. 2015: 1310-1321.
- [NN][CM,MA]Bonawitz K, Ivanov V, Kreuter B, et al. [Practical secure aggregation for privacy-preserving machine learning](https://www.researchgate.net/profile/Keith_Bonawitz/publication/320678967_Practical_Secure_Aggregation_for_Privacy-Preserving_Machine_Learning/links/5acb89dcaca272abdc635fc5/Practical-Secure-Aggregation-for-Privacy-Preserving-Machine-Learning.pdf)[C]//Proceedings of the 2017 ACM SIGSAC Conference on Computer and Communications Security. 2017: 1175-1191.
- [NN][MA][Baseline]Brendan McMahan H, Moore E, Ramage D, et al. [Communication-Efficient Learning of Deep Networks from Decentralized Data](https://arxiv.org/pdf/1602.05629.pdf)[J]. arXiv, 2016: arXiv: 1602.05629.
- [LM][MA]Jakub Konečný, H. Brendan McMahan, Daniel Ramage, Peter Richtárik .[Federated Optimization: Distributed Machine Learning for On-Device  Intelligence](https://arxiv.org/pdf/1610.02527) [J]. arXiv preprint arXiv:1610.02527.
- [NN][MA]Jakub Konečný, H. Brendan McMahan, Felix X. Yu, Peter Richtárik, Ananda Theertha Suresh, Dave Bacon .[Federated Learning: Strategies for Improving Communication Efficiency](https://arxiv.org/pdf/1610.05492) [J]. arXiv preprint arXiv:1610.05492.
- [LM,DT,NN][DP,MA]Papernot N, Abadi M, Erlingsson U, et al. [Semi-supervised knowledge transfer for deep learning from private training data](https://arxiv.org/pdf/1610.05755.pdf,)[J]. arXiv preprint arXiv:1610.05755, 2016.
- [LM][MA][NIPS]Virginia Smith, Chao-Kai Chiang, Maziar Sanjabi, Ameet Talwalkar .[Federated Multi-Task Learning](https://arxiv.org/pdf/1705.10467) [J]. arXiv preprint arXiv:1705.10467.
- [NN][DP,MA]McMahan H B, Ramage D, Talwar K, et al. [Learning differentially private recurrent language models](https://arxiv.org/pdf/1710.06963)[J]. arXiv preprint arXiv:1710.06963, 2017.
- [NN][DP,MA]Robin C. Geyer, Tassilo Klein, Moin Nabi .[Differentially Private Federated Learning: A Client Level Perspective](https://arxiv.org/pdf/1712.07557) [J]. arXiv preprint arXiv:1712.07557.
- [NN][MA]Fei Chen, Zhenhua Dong, Zhenguo Li, Xiuqiang He .[Federated Meta-Learning for Recommendation](https://arxiv.org/pdf/1802.07876) [J]. arXiv preprint arXiv:1802.07876.
- [LM,NN][MA]Wang S, Tuor T, Salonidis T, et al. [Adaptive Federated Learning in Resource Constrained Edge Computing Systems](https://arxiv.org/pdf/1804.05271.pdf)[J]. arXiv preprint arXiv:1804.05271, 2018.
- [NN][MA]Takayuki Nishio, Ryo Yonetani .[Client Selection for Federated Learning with Heterogeneous Resources in  Mobile Edge](https://arxiv.org/pdf/1804.08333) [J]. arXiv preprint arXiv:1804.08333.
- [GPD][MA][]Sumudu Samarakoon, Mehdi Bennis, Walid Saad, Merouane Debbah .[Distributed Federated Learning for Ultra-Reliable Low-Latency Vehicular  Communications](https://arxiv.org/pdf/1807.08127) [J]. arXiv preprint arXiv:1807.08127.
- [LM][MA]Hyesung Kim, Jihong Park, Mehdi Bennis, Seong-Lyun Kim .[On-Device Federated Learning via Blockchain and its Latency Analysis](https://arxiv.org/pdf/1808.03949) [J]. arXiv preprint arXiv:1808.03949.
- [NN][MA]Gregor Ulm, Emil Gustavsson, Mats Jirstrand .[Functional Federated Learning in Erlang (ffl-erl)](https://arxiv.org/pdf/1808.08143) [J]. arXiv preprint arXiv:1808.08143.
- [NN][MA]Xiaofei Wang, Yiwen Han, Chenyang Wang, Qiyang Zhao, Xu Chen, Min Chen .[In-Edge AI: Intelligentizing Mobile Edge Computing, Caching and  Communication by Federated Learning](https://arxiv.org/pdf/1809.07857) [J]. arXiv preprint arXiv:1809.07857.
- [NN][MA]Andrew Hard, Kanishka Rao, Rajiv Mathews, Françoise Beaufays, Sean Augenstein, Hubert Eichner, Chloé Kiddon, Daniel Ramage .[Federated Learning for Mobile Keyboard Prediction](https://arxiv.org/pdf/1811.03604) [J]. arXiv preprint arXiv:1811.03604.
- [NN][MA]Eunjeong Jeong, Seungeun Oh, Hyesung Kim, Jihong Park, Mehdi Bennis, Seong-Lyun Kim .[Communication-Efficient On-Device Machine Learning: Federated Distillation and Augmentation under Non-IID Private Data](https://arxiv.org/pdf/1811.11479) [J]. arXiv preprint arXiv:1811.11479.
- [LM,NN][MA]Abhishek Bhowmick, John Duchi, Julien Freudiger, Gaurav Kapoor, Ryan Rogers .[Protection Against Reconstruction and Its Applications in Private Federated Learning](https://arxiv.org/pdf/1812.00984) [J]. arXiv preprint arXiv:1812.00984.
- [LM,DT,NN][CM,DP,MA]S. Truex, N. Baracaldo, A. Anwar, T. Steinke, H. Ludwig, and R. Zhang, [A hybrid approach to privacy-preserving federated learning](https://arxiv.org/pdf/1812.03224)[J] arXiv preprint arXiv:1812.03224, 2018. 
- [NN][MA]Hangyu Zhu, Yaochu Jin .[Multi-objective Evolutionary Federated Learning](https://arxiv.org/pdf/1812.07478) [J]. arXiv preprint arXiv:1812.07478.
- [LM][MA]Muhammad Ammad-ud-din, Elena Ivannikova, Suleiman A. Khan, Were Oyomno, Qiang Fu, Kuan Eeik Tan, Adrian Flanagan .[Federated Collaborative Filtering for Privacy-Preserving Personalized Recommendation System](https://arxiv.org/pdf/1901.09888) [J]. arXiv preprint arXiv:1901.09888.
- [NN][MA]Boyi Liu, Lujia Wang, Ming Liu, Chengzhong Xu .[Lifelong Federated Reinforcement Learning: A Learning Architecture for Navigation in Cloud Robotic Systems](https://arxiv.org/pdf/1901.06455) [J]. arXiv preprint arXiv:1901.06455.
- [LM,NN][MA][ICML]Mehryar Mohri, Gary Sivek, Ananda Theertha Suresh .[Agnostic Federated Learning](https://arxiv.org/pdf/1902.00146) [J]. arXiv preprint arXiv:1902.00146.
- [NN][MA]Felix Sattler, Simon Wiedemann, Klaus-Robert Müller, Wojciech Samek .[Robust and Communication-Efficient Federated Learning from Non-IID Data](https://arxiv.org/pdf/1903.02891) [J]. arXiv preprint arXiv:1903.02891.
- Lumin Liu, Jun Zhang, S. H. Song, Khaled B. Letaief .[Edge-Assisted Hierarchical Federated Learning with Non-IID Data](https://arxiv.org/pdf/1905.06641) [J]. arXiv preprint arXiv:1905.06641.
- [LM,NN][MA][ICLR]Tian Li, Maziar Sanjabi, Virginia Smith .[Fair Resource Allocation in Federated Learning](https://arxiv.org/pdf/1905.10497) [J]. arXiv preprint arXiv:1905.10497.<br>[code:[litian96/fair_flearn](https://github.com/litian96/fair_flearn)]
- [NN][MA][ICML]Mikhail Yurochkin, Mayank Agarwal, Soumya Ghosh, Kristjan Greenewald, Trong Nghia Hoang, Yasaman Khazaeni .[Bayesian Nonparametric Federated Learning of Neural Networks](https://arxiv.org/pdf/1905.12022) [J]. arXiv preprint arXiv:1905.12022.<br>[code:[IBM/probabilistic-federated-neural-matching](https://github.com/IBM/probabilistic-federated-neural-matching)]
- Wang J, Sahu A K, Yang Z, et al. [MATCHA: Speeding up decentralized SGD via matching decomposition sampling](https://arxiv.org/pdf/1905.09435)[J]. arXiv preprint arXiv:1905.09435, 2019.
- Feng Liao, Hankz Hankui Zhuo, Xiaoling Huang, Yu Zhang .[Federated Hierarchical Hybrid Networks for Clickbait Detection](https://arxiv.org/pdf/1906.00638) [J]. arXiv preprint arXiv:1906.00638.
- [NN][MA]Luca Corinzia, Joachim M. Buhmann .[Variational Federated Multi-Task Learning](https://arxiv.org/pdf/1906.06268) [J]. arXiv preprint arXiv:1906.06268.
- [DT][CM]Yang Liu, Zhuo Ma, Ximeng Liu, Siqi Ma, Surya Nepal, Robert Deng .[Boosting Privately: Privacy-Preserving Federated Extreme Boosting for Mobile Crowdsensing](https://arxiv.org/pdf/1907.10218) [J]. arXiv preprint arXiv:1907.10218.
- Mehdi Salehi Heydar Abad, Emre Ozfatura, Deniz Gunduz, Ozgur Ercetin .[Hierarchical Federated Learning Across Heterogeneous Cellular Networks](https://arxiv.org/pdf/1909.02362) [J]. arXiv preprint arXiv:1909.02362.
- [NN][GAN]Aleksei Triastcyn, Boi Faltings .[Federated Generative Privacy](https://arxiv.org/pdf/1910.08385) [J]. arXiv preprint arXiv:1910.08385.
- [DT][Hash]Qinbin Li, Zeyi Wen, Bingsheng He .[Practical Federated Gradient Boosting Decision Trees](https://arxiv.org/pdf/1911.04206) [J]. arXiv preprint arXiv:1911.04206.
- Li H, Meng D, Li X. [Knowledge Federation: Hierarchy and Unification](https://arxiv.org/pdf/2002.01647)[J]. arXiv preprint arXiv:2002.01647, 2020.
- Siqi Luo, Xu Chen, Qiong Wu, Zhi Zhou, Shuai Yu .[HFEL: Joint Edge Association and Resource Allocation for Cost-Efficient Hierarchical Federated Edge Learning](https://arxiv.org/pdf/2002.11343) [J]. arXiv preprint arXiv:2002.11343.
- Aidmar Wainakh, Alejandro Sanchez Guinea, Tim Grube, Max Mühlhäuser .[Enhancing Privacy via Hierarchical Federated Learning](https://arxiv.org/pdf/2004.11361) [J]. arXiv preprint arXiv:2004.11361.
- Christopher Briggs, Zhong Fan, Peter Andras .[Federated learning with hierarchical clustering of local updates to improve training on non-IID data](https://arxiv.org/pdf/2004.11791) [J]. arXiv preprint arXiv:2004.11791.


## Decentralized Federated Learning
- Lian X, Zhang C, Zhang H, et al. [Can decentralized algorithms outperform centralized algorithms? a case study for decentralized parallel stochastic gradient descent](https://arxiv.org/pdf/1705.09056.pdf)[C]//Advances in Neural Information Processing Systems. 2017: 5330-5340.
- Shayan M, Fung C, Yoon C J M, et al. [Biscotti: A ledger for private and secure peer-to-peer machine learning](https://arxiv.org/pdf/1811.09904)[J]. arXiv preprint arXiv:1811.09904, 2018.
- Abhijit Guha Roy, Shayan Siddiqui, Sebastian Pölsterl, Nassir Navab, Christian Wachinger .[BrainTorrent: A Peer-to-Peer Environment for Decentralized Federated Learning](https://arxiv.org/pdf/1905.06731) [J]. arXiv preprint arXiv:1905.06731.
- Wang J, Sahu A K, Yang Z, et al. [MATCHA: Speeding up decentralized SGD via matching decomposition sampling](https://arxiv.org/pdf/1905.09435)[J]. arXiv preprint arXiv:1905.09435, 2019.
- Lalitha A, Wang X, Kilinc O, et al. [Decentralized bayesian learning over graphs](https://arxiv.org/pdf/1905.10466)[J]. arXiv preprint arXiv:1905.10466, 2019.
- Chaoyang He, Conghui Tan, Hanlin Tang, Shuang Qiu, Ji Liu .[Central Server Free Federated Learning over Single-sided Trust Social Networks](https://arxiv.org/pdf/1910.04956) [J]. arXiv preprint arXiv:1910.04956.
- Ye H, Luo L, Zhou Z, et al. [Multi-consensus Decentralized Accelerated Gradient Descent](https://arxiv.org/pdf/2005.00797)[J]. arXiv preprint arXiv:2005.00797, 2020.


## Federated Transfer Learning
- Eunjeong Jeong, Seungeun Oh, Hyesung Kim, Jihong Park, Mehdi Bennis, Seong-Lyun Kim .[Communication-Efficient On-Device Machine Learning: Federated Distillation and Augmentation under Non-IID Private Data](https://arxiv.org/pdf/1811.11479) [J]. arXiv preprint arXiv:1811.11479.
- [good]Yang Liu, Tianjian Chen, Qiang Yang .[Secure Federated Transfer Learning](https://arxiv.org/pdf/1812.03337) [J]. arXiv preprint arXiv:1812.03337.
- Jin-Hyun Ahn, Osvaldo Simeone, Joonhyuk Kang .[Wireless Federated Distillation for Distributed Edge Learning with Heterogeneous Data](https://arxiv.org/pdf/1907.02745) [J]. arXiv preprint arXiv:1907.02745.
- Han Cha, Jihong Park, Hyesung Kim, Seong-Lyun Kim, Mehdi Bennis .[Federated Reinforcement Distillation with Proxy Experience Memory](https://arxiv.org/pdf/1907.06536) [J]. arXiv preprint arXiv:1907.06536.
- Daliang Li, Junpu Wang .[FedMD: Heterogenous Federated Learning via Model Distillation](https://arxiv.org/pdf/1910.03581) [J]. arXiv preprint arXiv:1910.03581.
- Shreya Sharma, Xing Chaoping, Yang Liu, Yan Kang .[Secure and Efficient Federated Transfer Learning](https://arxiv.org/pdf/1910.13271) [J]. arXiv preprint arXiv:1910.13271.
- Chang H, Shejwalkar V, Shokri R, et al. [Cronus: Robust and Heterogeneous Collaborative Learning with Black-Box Knowledge Transfer](https://arxiv.org/pdf/1912.11279)[J]. arXiv preprint arXiv:1912.11279, 2019.
- Jin-Hyun Ahn, Osvaldo Simeone, Joonhyuk Kang .[Cooperative Learning via Federated Distillation over Fading Channels](https://arxiv.org/pdf/2002.01337) [J]. arXiv preprint arXiv:2002.01337.
- Li H, Meng D, Li X. [Knowledge Federation: Hierarchy and Unification](https://arxiv.org/pdf/2002.01647)[J]. arXiv preprint arXiv:2002.01647, 2020.
- Fay D, Sjölund J, Oechtering T J. [Decentralized Differentially Private Segmentation with PATE](https://arxiv.org/pdf/2004.06567)[J]. arXiv preprint arXiv:2004.06567, 2020.
- Han Cha, Jihong Park, Hyesung Kim, Mehdi Bennis, Seong-Lyun Kim .[Proxy Experience Replay: Federated Distillation for Distributed Reinforcement Learning](https://arxiv.org/pdf/2005.06105) [J]. arXiv preprint arXiv:2005.06105.


## Neural Architecture Search
- Xu M, Zhao Y, Bian K, et al. [Neural Architecture Search over Decentralized Data](https://arxiv.org/pdf/2002.06352)[J]. arXiv preprint arXiv:2002.06352, 2020.
- Hangyu Zhu, Yaochu Jin .[Real-time Federated Evolutionary Neural Architecture Search](https://arxiv.org/pdf/2003.02793) [J]. arXiv preprint arXiv:2003.02793.
- Chaoyang He, Murali Annavaram, Salman Avestimehr .[FedNAS: Federated Deep Learning via Neural Architecture Search](https://arxiv.org/pdf/2004.08546) [J]. arXiv preprint arXiv:2004.08546.
- Ishika Singh, Haoyi Zhou, Kunlin Yang, Meng Ding, Bill Lin, Pengtao Xie .[Differentially-private Federated Neural Architecture Search](https://arxiv.org/pdf/2006.10559) [J]. arXiv preprint arXiv:2006.10559.
- Hangyu Zhu, Haoyu Zhang, Yaochu Jin .[From Federated Learning to Federated Neural Architecture Search: A Survey](https://arxiv.org/pdf/2009.05868) [J]. arXiv preprint arXiv:2009.05868.
- Anubhav Garg, Amit Kumar Saha, Debo Dutta .[Direct Federated Neural Architecture Search](https://arxiv.org/pdf/2010.06223) [J]. arXiv preprint arXiv:2010.06223.


## Continual Learning
- Jaehong Yoon, Wonyong Jeong, Giwoong Lee, Eunho Yang, Sung Ju Hwang .[Federated Continual Learning with Adaptive Parameter Communication](https://arxiv.org/pdf/2003.03196) [J]. arXiv preprint arXiv:2003.03196.


## Reinforcement Learning && Robotics
- Luong, Nguyen Cong, et al. [Efficient Training Management for Mobile Crowd-Machine Learning: A Deep Reinforcement Learning Approach.](https://arxiv.org/pdf/1812.03633) IEEE Wireless Communications Letters, vol. 8, no. 5, 2019, pp. 1345–1348.
- Boyi Liu, Lujia Wang, Ming Liu, Chengzhong Xu .[Lifelong Federated Reinforcement Learning: A Learning Architecture for Navigation in Cloud Robotic Systems](https://arxiv.org/pdf/1901.06455) [J]. arXiv preprint arXiv:1901.06455.
- [good]Hankz Hankui Zhuo, Wenfeng Feng, Qian Xu, Qiang Yang, Yufeng Lin .[Federated Reinforcement Learning](https://arxiv.org/pdf/1901.08277) [J]. arXiv preprint arXiv:1901.08277.
- Boyi Liu, Lujia Wang, Ming Liu, Cheng-Zhong Xu .[Federated Imitation Learning: A Privacy Considered Imitation Learning Framework for Cloud Robotic Systems with Heterogeneous Sensor Data](https://arxiv.org/pdf/1909.00895) [J]. arXiv preprint arXiv:1909.00895.
- Haozhao Wang, Zhihao Qu, Song Guo, Xin Gao, Ruixuan Li, Baoliu Ye .[Intermittent Pulling with Local Compensation for Communication-Efficient Federated Learning](https://arxiv.org/pdf/2001.08277) [J]. arXiv preprint arXiv:2001.08277.


## Bayesian Learning
- Xudong Sun, Andrea Bommert, Florian Pfisterer, Jörg Rahnenführer, Michel Lang, Bernd Bischl .[High Dimensional Restrictive Federated Model Selection with multi-objective Bayesian Optimization over shifted distributions](https://arxiv.org/pdf/1902.08999) [J]. arXiv preprint arXiv:1902.08999.
- Mrinank Sharma, Michael Hutchinson, Siddharth Swaroop, Antti Honkela, Richard E. Turner .[Differentially Private Federated Variational Inference](https://arxiv.org/pdf/1911.10563) [J]. arXiv preprint arXiv:1911.10563.


## Adversarial-Attack-and-Defense
- Hitaj B, Ateniese G, Perez-Cruz F. [Deep models under the GAN: information leakage from collaborative deep learning](https://arxiv.org/pdf/1702.07464.pdf)[C]//Proceedings of the 2017 ACM SIGSAC Conference on Computer and Communications Security. 2017: 603-618.
- [ICLR]Xie C, Huang K, Chen P Y, et al. [DBA: Distributed Backdoor Attacks against Federated Learning](http://www.openreview.net/pdf?id=rkgyS0VFvr)[C]//International Conference on Learning Representations. 2019.<br>[code:[AI-secure/DBA](https://github.com/AI-secure/DBA)]
- Yin D, Chen Y, Ramchandran K, et al. [Byzantine-robust distributed learning: Towards optimal statistical rates](https://arxiv.org/pdf/1803.01498)[J]. arXiv preprint arXiv:1803.01498, 2018.
- Melis L, Song C, De Cristofaro E, et al. [Exploiting unintended feature leakage in collaborative learning](https://arxiv.org/pdf/1805.04049)[C]//2019 IEEE Symposium on Security and Privacy (SP). IEEE, 2019: 691-706. <br>[code:[csong27/property-inference-collaborative-ml](https://github.com/csong27/property-inference-collaborative-ml)]
- [good]Eugene Bagdasaryan, Andreas Veit, Yiqing Hua, Deborah Estrin, Vitaly Shmatikov .[How To Backdoor Federated Learning](https://arxiv.org/pdf/1807.00459) [J]. arXiv preprint arXiv:1807.00459.<br>[code:[ebagdasa/backdoor_federated_learning](https://github.com/ebagdasa/backdoor_federated_learning)]
- Clement Fung, Chris J.M. Yoon, Ivan Beschastnikh .[Mitigating Sybils in Federated Learning Poisoning](https://arxiv.org/pdf/1808.04866) [J]. arXiv preprint arXiv:1808.04866.
- Li L, Xu W, Chen T, et al. [RSA: Byzantine-robust stochastic aggregation methods for distributed learning from heterogeneous datasets](https://www.aaai.org/ojs/index.php/AAAI/article/view/3968/3846)[C]//Proceedings of the AAAI Conference on Artificial Intelligence. 2019, 33: 1544-1551. 
- Fung C, Koerner J, Grant S, et al. [Dancing in the dark: private multi-party machine learning in an untrusted setting](https://arxiv.org/pdf/1811.09712)[J]. arXiv preprint arXiv:1811.09712, 2018.
- [ICML]Arjun Nitin Bhagoji, Supriyo Chakraborty, Prateek Mittal, Seraphin Calo .[Analyzing Federated Learning through an Adversarial Lens](https://arxiv.org/pdf/1811.12470) [J]. arXiv preprint arXiv:1811.12470.<br>[code:[inspire-group/ModelPoisoning](https://github.com/inspire-group/ModelPoisoning)]
- Zhibo Wang, Mengkai Song, Zhifei Zhang, Yang Song, Qian Wang, Hairong Qi .[Beyond Inferring Class Representatives: User-Level Privacy Leakage From Federated Learning](https://arxiv.org/pdf/1812.00535) [J]. arXiv preprint arXiv:1812.00535.
- Milad Nasr, Reza Shokri, Amir Houmansadr .[Comprehensive Privacy Analysis of Deep Learning: Stand-alone and Federated Learning under Passive and Active White-box Inference Attacks](https://arxiv.org/pdf/1812.00910) [J]. arXiv preprint arXiv:1812.00910.
- Abhishek Bhowmick, John Duchi, Julien Freudiger, Gaurav Kapoor, Ryan Rogers .[Protection Against Reconstruction and Its Applications in Private Federated Learning](https://arxiv.org/pdf/1812.00984) [J]. arXiv preprint arXiv:1812.00984.
- Chen, Qingrong, et al. [Differentially Private Data Generative Models.](https://arxiv.org/pdf/1812.02274) ArXiv Preprint ArXiv:1812.02274, 2018.
- Zhu L, Liu Z, Han S. [Deep leakage from gradients](https://papers.nips.cc/paper/9617-deep-leakage-from-gradients.pdf)[C]//Advances in Neural Information Processing Systems. 2019: 14774-14784.
- [NIPS]Baruch, Moran, et al. [A Little Is Enough: Circumventing Defenses For Distributed Learning.](https://arxiv.org/pdf/1902.06156) ArXiv Preprint ArXiv:1902.06156, 2019.
- [AAAI]Yufei Han, Xiangliang Zhang .[Robust Federated Training via Collaborative Machine Teaching using Trusted Instances](https://arxiv.org/pdf/1905.02941) [J]. arXiv preprint arXiv:1905.02941.
- Dong Y, Cheng J, Hossain M J, et al. [Secure distributed on-device learning networks with Byzantine adversaries](https://arxiv.org/pdf/1906.00887)[J]. IEEE Network, 2019, 33(6): 180-187.
- Yang Liu, Zhuo Ma, Ximeng Liu, Siqi Ma, Surya Nepal, Robert Deng .[Boosting Privately: Privacy-Preserving Federated Extreme Boosting for Mobile Crowdsensing](https://arxiv.org/pdf/1907.10218) [J]. arXiv preprint arXiv:1907.10218.
- Hongyu Li, Tianqi Han .[An End-to-End Encrypted Neural Network for Gradient Updates Transmission in Federated Learning](https://arxiv.org/pdf/1908.08340) [J]. arXiv preprint arXiv:1908.08340.
- Luis Muñoz-González, Kenneth T. Co, Emil C. Lupu .[Byzantine-Robust Federated Machine Learning through Adaptive Model Averaging](https://arxiv.org/pdf/1909.05125) [J]. arXiv preprint arXiv:1909.05125.
- Zhaorui Li, Zhicong Huang, Chaochao Chen, Cheng Hong .[Quantification of the Leakage in Federated Learning](https://arxiv.org/pdf/1910.05467) [J]. arXiv preprint arXiv:1910.05467.
- Lixu Wang, Shichao Xu, Xiao Wang, Qi Zhu .[Eavesdrop the Composition Proportion of Training Labels in Federated Learning](https://arxiv.org/pdf/1910.06044) [J]. arXiv preprint arXiv:1910.06044.
- Suyi Li, Yong Cheng, Yang Liu, Wei Wang, Tianjian Chen .[Abnormal Client Behavior Detection in Federated Learning](https://arxiv.org/pdf/1910.09933) [J]. arXiv preprint arXiv:1910.09933.
- Fan Ang, Li Chen, Nan Zhao, Yunfei Chen, Weidong Wang, F. Richard Yu .[Robust Federated Learning with Noisy Communication](https://arxiv.org/pdf/1911.00251) [J]. arXiv preprint arXiv:1911.00251.
- [good]Ziteng Sun, Peter Kairouz, Ananda Theertha Suresh, H. Brendan McMahan .[Can You Really Backdoor Federated Learning?](https://arxiv.org/pdf/1911.07963) [J]. arXiv preprint arXiv:1911.07963.
- Minghong Fang, Xiaoyu Cao, Jinyuan Jia, Neil Zhenqiang Gong .[Local Model Poisoning Attacks to Byzantine-Robust Federated Learning](https://arxiv.org/pdf/1911.11815) [J]. arXiv preprint arXiv:1911.11815.
- Jierui Lin, Min Du, Jian Liu .[Free-riders in Federated Learning: Attacks and Defenses](https://arxiv.org/pdf/1911.12560) [J]. arXiv preprint arXiv:1911.12560.
- Chang H, Shejwalkar V, Shokri R, et al. [Cronus: Robust and Heterogeneous Collaborative Learning with Black-Box Knowledge Transfer](https://arxiv.org/pdf/1912.11279)[J]. arXiv preprint arXiv:1912.11279, 2019.
- Shuhao Fu, Chulin Xie, Bo Li, Qifeng Chen .[Attack-Resistant Federated Learning with Residual-based Reweighting](https://arxiv.org/pdf/1912.11464) [J]. arXiv preprint arXiv:1912.11464.
- Josh Payne, Ashish Kundu .[Towards Deep Federated Defenses Against Malware in Cloud Ecosystems](https://arxiv.org/pdf/1912.12370) [J]. arXiv preprint arXiv:1912.12370.
- Krishna Pillutla, Sham M. Kakade, Zaid Harchaoui .[Robust Aggregation for Federated Learning](https://arxiv.org/pdf/1912.13445) [J]. arXiv preprint arXiv:1912.13445.
- Suyi Li, Yong Cheng, Wei Wang, Yang Liu, Tianjian Chen .[Learning to Detect Malicious Clients for Robust Federated Learning](https://arxiv.org/pdf/2002.00211) [J]. arXiv preprint arXiv:2002.00211.
- Richeng Jin, Yufan Huang, Xiaofan He, Huaiyu Dai, Tianfu Wu .[Stochastic-Sign SGD for Federated Learning with Theoretical Guarantees](https://arxiv.org/pdf/2002.10940) [J]. arXiv preprint arXiv:2002.10940.
- Yang Y R, Li W J. [BASGD: Buffered Asynchronous SGD for Byzantine Learning](https://arxiv.org/pdf/2003.00937)[J]. arXiv preprint arXiv:2003.00937, 2020.
- Huafei Zhu, Zengxiang Li, Merivyn Cheah, Rick Siow Mong Goh .[Privacy-preserving Weighted Federated Learning within Oracle-Aided MPC Framework](https://arxiv.org/pdf/2003.07630) [J]. arXiv preprint arXiv:2003.07630.
- Rui Hu, Yuanxiong Guo, E. Paul. Ratazzi, Yanmin Gong .[Differentially Private Federated Learning for Resource-Constrained Internet of Things](https://arxiv.org/pdf/2003.12705) [J]. arXiv preprint arXiv:2003.12705.
- [NIPS]Jonas Geiping, Hartmut Bauermeister, Hannah Dröge, Michael Moeller .[Inverting Gradients -- How easy is it to break privacy in federated learning?](https://arxiv.org/pdf/2003.14053) [J]. arXiv preprint arXiv:2003.14053.<br>[code:[JonasGeiping/invertinggradients](https://github.com/JonasGeiping/invertinggradients)]
- David Enthoven, Zaid Al-Ars .[An Overview of Federated Deep Learning Privacy Attacks and Defensive Strategies](https://arxiv.org/pdf/2004.04676) [J]. arXiv preprint arXiv:2004.04676.
- Amit Portnoy, Danny Hendler .[Towards Realistic Byzantine-Robust Federated Learning](https://arxiv.org/pdf/2004.04986) [J]. arXiv preprint arXiv:2004.04986.
- Gan Sun, Yang Cong (Senior Member, IEEE), Jiahua Dong, Qiang Wang, Ji Liu .[Data Poisoning Attacks on Federated Machine Learning](https://arxiv.org/pdf/2004.10020) [J]. arXiv preprint arXiv:2004.10020.
- Wenqi Wei, Ling Liu, Margaret Loper, Ka-Ho Chow, Mehmet Emre Gursoy, Stacey Truex, Yanzhao Wu .[A Framework for Evaluating Gradient Leakage Attacks in Federated Learning](https://arxiv.org/pdf/2004.10397) [J]. arXiv preprint arXiv:2004.10397.
- Xinjian Luo, Xiangqi Zhu .[Exploiting Defenses against GAN-Based Feature Inference Attacks in Federated Learning](https://arxiv.org/pdf/2004.12571) [J]. arXiv preprint arXiv:2004.12571.
- Renuga Kanagavelu, Zengxiang Li, Juniarto Samsudin, Yechao Yang, Feng Yang, Rick Siow Mong Goh, Mervyn Cheah, Praewpiraya Wiwatphonthana, Khajonpong Akkarajitsakul, Shangguang Wangz .[Two-Phase Multi-Party Computation Enabled Privacy-Preserving Federated Learning](https://arxiv.org/pdf/2005.11901) [J]. arXiv preprint arXiv:2005.11901.
- Chien-Lun Chen, Leana Golubchik, Marco Paolieri .[Backdoor Attacks on Federated Meta-Learning](https://arxiv.org/pdf/2006.07026) [J]. arXiv preprint arXiv:2006.07026.
- Zeou Hu, Kiarash Shaloudegi, Guojun Zhang, Yaoliang Yu .[FedMGDA+: Federated Learning meets Multi-objective Optimization](https://arxiv.org/pdf/2006.11489) [J]. arXiv preprint arXiv:2006.11489.
- Data D, Diggavi S. [Byzantine-Resilient High-Dimensional SGD with Local Iterations on Heterogeneous Data](https://arxiv.org/pdf/2006.13041)[J]. arXiv preprint arXiv:2006.13041, 2020.
- Song Y, Liu T, Wei T, et al. [FDA3: Federated Defense Against Adversarial Attacks for Cloud-Based IIoT Applications](https://arxiv.org/pdf/2006.15632)[J]. IEEE Transactions on Industrial Informatics, 2020.


## Privacy && Homomorphic Encryption
- [Baseline]Brendan McMahan H, Moore E, Ramage D, et al. [Communication-Efficient Learning of Deep Networks from Decentralized Data](https://arxiv.org/pdf/1602.05629.pdf)[J]. arXiv, 2016: arXiv: 1602.05629.
- [NIPS]Keith Bonawitz, Vladimir Ivanov, Ben Kreuter, Antonio Marcedone, H. Brendan McMahan, Sarvar Patel, Daniel Ramage, Aaron Segal, Karn Seth .[Practical Secure Aggregation for Federated Learning on User-Held Data](https://arxiv.org/pdf/1611.04482) [J]. arXiv preprint arXiv:1611.04482.
- Bonawitz K, Ivanov V, Kreuter B, et al. [Practical secure aggregation for privacy-preserving machine learning](https://www.researchgate.net/profile/Keith_Bonawitz/publication/320678967_Practical_Secure_Aggregation_for_Privacy-Preserving_Machine_Learning/links/5acb89dcaca272abdc635fc5/Practical-Secure-Aggregation-for-Privacy-Preserving-Machine-Learning.pdf)[C]//Proceedings of the 2017 ACM SIGSAC Conference on Computer and Communications Security. 2017: 1175-1191.
- Stephen Hardy, Wilko Henecka, Hamish Ivey-Law, Richard Nock, Giorgio Patrini, Guillaume Smith, Brian Thorne .[Private federated learning on vertically partitioned data via entity  resolution and additively homomorphic encryption](https://arxiv.org/pdf/1711.10677) [J]. arXiv preprint arXiv:1711.10677.
- McMahan H B, Ramage D, Talwar K, et al. [Learning differentially private recurrent language models](https://arxiv.org/pdf/1710.06963)[J]. arXiv preprint arXiv:1710.06963, 2017.
- [good]Robin C. Geyer, Tassilo Klein, Moin Nabi .[Differentially Private Federated Learning: A Client Level Perspective](https://arxiv.org/pdf/1712.07557) [J]. arXiv preprint arXiv:1712.07557.
- Papernot N, Song S, Mironov I, et al. [Scalable private learning with pate](https://arxiv.org/pdf/1802.08908.pdf?ref=hackernoon.com)[J]. arXiv preprint arXiv:1802.08908, 2018.
- Orekondy T, Oh S J, Zhang Y, et al. [Gradient-Leaks: Understanding and Controlling Deanonymization in Federated Learning](https://arxiv.org/pdf/1805.05838)[J]. arXiv preprint arXiv:1805.05838, 2018.
- [good]Eugene Bagdasaryan, Andreas Veit, Yiqing Hua, Deborah Estrin, Vitaly Shmatikov .[How To Backdoor Federated Learning](https://arxiv.org/pdf/1807.00459) [J]. arXiv preprint arXiv:1807.00459.<br>[code:[ebagdasa/backdoor_federated_learning](https://github.com/ebagdasa/backdoor_federated_learning)]
- Ryffel T, Trask A, Dahl M, et al. [A generic framework for privacy preserving deep learning](https://arxiv.org/pdf/1811.04017.pdf!)[J]. arXiv preprint arXiv:1811.04017, 2018.
- [ICML]Arjun Nitin Bhagoji, Supriyo Chakraborty, Prateek Mittal, Seraphin Calo .[Analyzing Federated Learning through an Adversarial Lens](https://arxiv.org/pdf/1811.12470) [J]. arXiv preprint arXiv:1811.12470.<br>[code:[inspire-group/ModelPoisoning](https://github.com/inspire-group/ModelPoisoning)]
- Zhibo Wang, Mengkai Song, Zhifei Zhang, Yang Song, Qian Wang, Hairong Qi .[Beyond Inferring Class Representatives: User-Level Privacy Leakage From Federated Learning](https://arxiv.org/pdf/1812.00535) [J]. arXiv preprint arXiv:1812.00535.
- Vepakomma P, Gupta O, Dubey A, et al. [Reducing leakage in distributed deep learning for sensitive health data](https://www.researchgate.net/profile/Praneeth_Vepakomma2/publication/333171913_Reducing_leakage_in_distributed_deep_learning_for_sensitive_health_data/links/5cdeb29a299bf14d95a1772c/Reducing-leakage-in-distributed-deep-learning-for-sensitive-health-data.pdf)[J]. arXiv preprint arXiv:1812.00564, 2019.
- Milad Nasr, Reza Shokri, Amir Houmansadr .[Comprehensive Privacy Analysis of Deep Learning: Stand-alone and Federated Learning under Passive and Active White-box Inference Attacks](https://arxiv.org/pdf/1812.00910) [J]. arXiv preprint arXiv:1812.00910.
- Stacey Truex, Nathalie Baracaldo, Ali Anwar, Thomas Steinke, Heiko Ludwig, Rui Zhang .[A Hybrid Approach to Privacy-Preserving Federated Learning](https://arxiv.org/pdf/1812.03224) [J]. arXiv preprint arXiv:1812.03224.
- Zhao L, Wang Q, Zou Q, et al. [Privacy-preserving collaborative deep learning with unreliable participants](https://arxiv.org/pdf/1812.10113)[J]. IEEE Transactions on Information Forensics and Security, 2019, 15: 1486-1500.
- Aleksei Triastcyn, Boi Faltings .[Federated Generative Privacy](https://arxiv.org/pdf/1910.08385) [J]. arXiv preprint arXiv:1910.08385.
- Zhu L, Liu Z, Han S. [Deep leakage from gradients](https://papers.nips.cc/paper/9617-deep-leakage-from-gradients.pdf)[C]//Advances in Neural Information Processing Systems. 2019: 14774-14784.
- Kang Wei, Jun Li, Ming Ding, Chuan Ma, Howard H. Yang, Farokhi Farhad, Shi Jin, Tony Q. S. Quek, H. Vincent Poor .[Federated Learning with Differential Privacy: Algorithms and Performance Analysis](https://arxiv.org/pdf/1911.00222) [J]. arXiv preprint arXiv:1911.00222.
- Zaoxing Liu, Tian Li, Virginia Smith, Vyas Sekar .[Enhancing the Privacy of Federated Learning with Sketching](https://arxiv.org/pdf/1911.01812) [J]. arXiv preprint arXiv:1911.01812.
- Aleksei Triastcyn, Boi Faltings .[Federated Learning with Bayesian Differential Privacy](https://arxiv.org/pdf/1911.10071) [J]. arXiv preprint arXiv:1911.10071.
- Runhua Xu, Nathalie Baracaldo, Yi Zhou, Ali Anwar, Heiko Ludwig .[HybridAlpha: An Efficient Approach for Privacy-Preserving Federated Learning](https://arxiv.org/pdf/1912.05897) [J]. arXiv preprint arXiv:1912.05897.
- Daniel Peterson, Pallika Kanani, Virendra J. Marathe .[Private Federated Learning with Domain Adaptation](https://arxiv.org/pdf/1912.06733) [J]. arXiv preprint arXiv:1912.06733.
- Zhao B, Mopuri K R, Bilen H. [iDLG: Improved Deep Leakage from Gradients](https://arxiv.org/pdf/2001.02610)[J]. arXiv preprint arXiv:2001.02610, 2020
- Chen D, Orekondy T, Fritz M. [Gs-wgan: A gradient-sanitized approach for learning differentially private generators](https://proceedings.neurips.cc/paper/2020/file/9547ad6b651e2087bac67651aa92cd0d-Paper.pdf)[J]. Advances in Neural Information Processing Systems, 2020, 33.
- Jeon J, Kim J, Kim J, et al. [Privacy-preserving deep learning computation for geo-distributed medical big-data platforms](https://arxiv.org/pdf/2001.02932)[C]//2019 49th Annual IEEE/IFIP International Conference on Dependable Systems and Networks–Supplemental Volume (DSN-S). IEEE, 2019: 3-4.
- Olivia Choudhury, Aris Gkoulalas-Divanis, Theodoros Salonidis, Issa Sylla, Yoonyoung Park, Grace Hsu, Amar Das .[Anonymizing Data for Privacy-Preserving Federated Learning](https://arxiv.org/pdf/2002.09096) [J]. arXiv preprint arXiv:2002.09096.
- Yan Feng, Xue Yang, Weijun Fang, Shu-Tao Xia, Xiaohu Tang .[Practical and Bilateral Privacy-preserving Federated Learning](https://arxiv.org/pdf/2002.09843) [J]. arXiv preprint arXiv:2002.09843.
- Ruixuan Liu, Yang Cao, Masatoshi Yoshikawa, Hong Chen .[FedSel: Federated SGD under Local Differential Privacy with Top-k Dimension Selection](https://arxiv.org/pdf/2003.10637) [J]. arXiv preprint arXiv:2003.10637.
- Katevas K, Bagdasaryan E, Waterman J, et al. [Decentralized Policy-Based Private Analytics](https://arxiv.org/pdf/2003.06612)[J]. arXiv preprint arXiv:2003.06612, 2020. 
- Yang Liu, Zhuo Ma, Ximeng Liu, Jianfeng Ma .[Learn to Forget: User-Level Memorization Elimination in Federated Learning](https://arxiv.org/pdf/2003.10933) [J]. arXiv preprint arXiv:2003.10933.
- Kalikinkar Mandal, Guang Gong .[PrivFL: Practical Privacy-preserving Federated Regressions on High-dimensional Data over Mobile Networks](https://arxiv.org/pdf/2004.02264) [J]. arXiv preprint arXiv:2004.02264.
- Yusuke Koda, Koji Yamamoto, Takayuki Nishio, Masahiro Morikura .[Differentially Private AirComp Federated Learning with Power Adaptation Harnessing Receiver Noise](https://arxiv.org/pdf/2004.06337) [J]. arXiv preprint arXiv:2004.06337.
- Fay D, Sjölund J, Oechtering T J. [Decentralized Differentially Private Segmentation with PATE](https://arxiv.org/pdf/2004.06567)[J]. arXiv preprint arXiv:2004.06567, 2020.
- Yang Zhao, Jun Zhao, Mengmeng Yang, Teng Wang, Ning Wang, Lingjuan Lyu, Dusit Niyato, Kwok Yan Lam .[Local Differential Privacy based Federated Learning for Internet of Things](https://arxiv.org/pdf/2004.08856) [J]. arXiv preprint arXiv:2004.08856.
- Aidmar Wainakh, Alejandro Sanchez Guinea, Tim Grube, Max Mühlhäuser .[Enhancing Privacy via Hierarchical Federated Learning](https://arxiv.org/pdf/2004.11361) [J]. arXiv preprint arXiv:2004.11361.
- M.A.P. Chamikara, P.Bertok, I.Khalil, D.Liu, S.Camtepe .[Privacy Preserving Distributed Machine Learning with Federated Learning](https://arxiv.org/pdf/2004.12108) [J]. arXiv preprint arXiv:2004.12108.
- Zhicong Liang, Bao Wang, Quanquan Gu, Stanley Osher, Yuan Yao .[Exploring Private Federated Learning with Laplacian Smoothing](https://arxiv.org/pdf/2005.00218) [J]. arXiv preprint arXiv:2005.00218.
- Semih Yagli, Alex Dytso, H. Vincent Poor .[Information-Theoretic Bounds on the Generalization Error and Privacy Leakage in Federated Learning](https://arxiv.org/pdf/2005.02503) [J]. arXiv preprint arXiv:2005.02503.
- Fagbohungbe O, Reza S R, Dong X, et al. [Efficient Privacy Preserving Edge Computing Framework for Image Classification](https://arxiv.org/pdf/2005.04563)[J]. arXiv preprint arXiv:2005.04563, 2020.
- Will Abramson, Adam James Hall, Pavlos Papadopoulos, Nikolaos Pitropakis, William J Buchanan. [A Distributed Trust Framework for Privacy-Preserving Machine Learning](https://arxiv.org/abs/2006.02456)[J]. arXiv preprint arXiv:2006.02456
- Stacey Truex, Ling Liu, Ka-Ho Chow, Mehmet Emre Gursoy, Wenqi Wei .[LDP-Fed: Federated Learning with Local Differential Privacy](https://arxiv.org/pdf/2006.03637) [J]. arXiv preprint arXiv:2006.03637.
- Lie He, Sai Praneeth Karimireddy, Martin Jaggi. [Secure Byzantine-Robust Machine Learning](https://arxiv.org/abs/2006.04747)[J]. arXiv preprint arXiv:2006.04747 
- Dongzhu Liu, Osvaldo Simeone .[Privacy For Free: Wireless Federated Learning Via Uncoded Transmission With Adaptive Power Control](https://arxiv.org/pdf/2006.05459) [J]. arXiv preprint arXiv:2006.05459.
- César Sabater, Aurélien Bellet, Jan Ramon. [Distributed Differentially Private Averaging with Improved Utility and Robustness to Malicious Parties](https://arxiv.org/abs/2006.07218)[J]. arXiv preprint arXiv:2006.07218


## Incentive Mechanism && Fairness
- Dwork, C. (2008). [Differential privacy: a survey of results](https://www.researchgate.net/profile/Minzhu_Xie2/publication/220908334_A_Practical_Parameterized_Algorithm_for_the_Individual_Haplotyping_Problem_MLF/links/0deec5328063473edc000000/A-Practical-Parameterized-Algorithm-for-the-Individual-Haplotyping-Problem-MLF.pdf#page=12). In TAMC’08 Proceedings of the 5th international conference on Theory and applications of models of computation (Vol. 4978, pp. 1–19).
- Dwork C. [Differential privacy in new settings](https://core.ac.uk/download/pdf/187048361.pdf)[C]//Proceedings of the twenty-first annual ACM-SIAM symposium on Discrete Algorithms. Society for Industrial and Applied Mathematics, 2010: 174-183.
- Dwork C.  [A firm foundation for private data analysis](http://www.mathcs.emory.edu/~lxiong/cs573_f18/share/readings/firm-CACM-2011.pdf) Communications of the ACM, vol. 54, no. 1, pp. 86–95, 2011
- [BOOK]Dwork C, Roth A. [The algorithmic foundations of differential privacy](http://www.tau.ac.il/~saharon/BigData2018/privacybook.pdf)[J]. Foundations and Trends in Theoretical Computer Science, 2014, 9(3-4): 211-407.
- Yu S. [Big privacy: Challenges and opportunities of privacy study in the age of big data](https://ieeexplore.ieee.org/iel7/6287639/6514899/07485855.pdf)[J]. IEEE access, 2016, 4: 2751-2763.
- Zhu T, Li G, Zhou W, et al. Differentially private data publishing and analysis: A survey[J]. IEEE Transactions on Knowledge and Data Engineering, 2017, 29(8): 1619-1638.
- Vadhan S. [The complexity of differential privacy](https://privacytools.seas.harvard.edu/files/privacytools/files/manuscript_2016.pdf)[M]//Tutorials on the Foundations of Cryptography. Springer, Cham, 2017: 347-450.
- Zhao P, Zhang G, Wan S, et al. [A survey of local differential privacy for securing internet of vehicles](https://www.researchgate.net/profile/Ping_Zhao41/publication/337842824_A_survey_of_local_differential_privacy_for_securing_internet_of_vehicles/links/5fd7308b45851553a0b573ca/A-survey-of-local-differential-privacy-for-securing-internet-of-vehicles.pdf)[J]. The Journal of Supercomputing, 2019: 1-22.
- Pejó B, Desfontaines D. [SoK: differential privacies](https://research.google/pubs/pub48777.pdf)[J]. 2020.
- Wagner I, Eckhoff D. [Technical privacy metrics: a systematic survey](https://arxiv.org/pdf/1512.00327)[J]. ACM Computing Surveys (CSUR), 2018, 51(3): 1-38.
- Ben-Nun T, Hoefler T. [Demystifying parallel and distributed deep learning: An in-depth concurrency analysis](https://arxiv.org/pdf/1802.09941)[J]. ACM Computing Surveys (CSUR), 2019, 52(4): 1-43.
- Hassan M U, Rehmani M H, Chen J. [Differential privacy techniques for cyber physical systems: a survey](https://arxiv.org/pdf/1812.02282)[J]. IEEE Communications Surveys & Tutorials, 2019, 22(1): 746-789.
- Vepakomma P, Swedish T, Raskar R, et al. [No Peek: A Survey of private distributed deep learning](https://arxiv.org/pdf/1812.03288.pdf)[J]. arXiv preprint arXiv:1812.03288, 2018.
- [TIST]Qiang Yang, Yang Liu, Tianjian Chen, Yongxin Tong .[Federated Machine Learning: Concept and Applications](https://arxiv.org/pdf/1902.04885) [J]. arXiv preprint arXiv:1902.04885.
- Han Y, Wang X, Leung V, et al. [Convergence of Edge Computing and Deep Learning: A Comprehensive Survey](https://arxiv.org/pdf/1907.08349.pdf)[J]. arXiv preprint arXiv:1907.08349, 2019.
- Qinbin Li, Zeyi Wen, Bingsheng He .[Federated Learning Systems: Vision, Hype and Reality for Data Privacy and Protection](https://arxiv.org/pdf/1907.09693) [J]. arXiv preprint arXiv:1907.09693.
- Solmaz Niknam, Harpreet S. Dhillon, Jeffery H. Reed .[Federated Learning for Wireless Communications: Motivation, Opportunities and Challenges](https://arxiv.org/pdf/1908.06847) [J]. arXiv preprint arXiv:1908.06847.
- Tian Li, Anit Kumar Sahu, Ameet Talwalkar, Virginia Smith .[Federated Learning: Challenges, Methods, and Future Directions](https://arxiv.org/pdf/1908.07873) [J]. arXiv preprint arXiv:1908.07873.
- Wei Yang Bryan Lim, Nguyen Cong Luong, Dinh Thai Hoang, Yutao Jiao, Ying-Chang Liang, Qiang Yang, Dusit Niyato, Chunyan Miao .[Federated Learning in Mobile Edge Networks: A Comprehensive Survey](https://arxiv.org/pdf/1909.11875) [J]. arXiv preprint arXiv:1909.11875.
- D. Verma, S. Calo, S. Witherspoon, E. Bertino, A. Abu Jabal, A. Swami, G. Cirincione, S. Julier, G. White, G. de Mel, G. Pearson .[Federated Learning for Coalition Operations](https://arxiv.org/pdf/1910.06799) [J]. arXiv preprint arXiv:1910.06799.
- Hsieh K. [Machine Learning Systems for Highly-Distributed and Rapidly-Growing Data](https://arxiv.org/pdf/1910.08663)[J]. arXiv preprint arXiv:1910.08663, 2019.
- Bhardwaj K, Suda N, [Marculescu R. EdgeAI: A Vision for Deep Learning in IoT Era](https://arxiv.org/pdf/1910.10356)[J]. IEEE Design & Test, 2019.
- Jie Xu, Fei Wang .[Federated Learning for Healthcare Informatics](https://arxiv.org/pdf/1911.06270) [J]. arXiv preprint arXiv:1911.06270.
- Lan Q, Zhang Z, Du Y, et al. [An Introduction to Communication Efficient Edge Machine Learning](https://arxiv.org/pdf/1912.01554)[J]. arXiv preprint arXiv:1912.01554, 2019.
- Anudit Nagar .[Privacy-Preserving Blockchain Based Federated Learning with Differential Data Sharing](https://arxiv.org/pdf/1912.04859) [J]. arXiv preprint arXiv:1912.04859.
- [good]Peter Kairouz, H. Brendan McMahan, Brendan Avent, Aurélien Bellet, Mehdi Bennis, Arjun Nitin Bhagoji, Keith Bonawitz, Zachary Charles, Graham Cormode, Rachel Cummings, Rafael G.L. D'Oliveira, Salim El Rouayheb, David Evans, Josh Gardner, Zachary Garrett, Adrià Gascón, Badih Ghazi, Phillip B. Gibbons, Marco Gruteser, Zaid Harchaoui, Chaoyang He, Lie He, Zhouyuan Huo, Ben Hutchinson, Justin Hsu, Martin Jaggi, Tara Javidi, Gauri Joshi, Mikhail Khodak, Jakub Konečný, Aleksandra Korolova, Farinaz Koushanfar, Sanmi Koyejo, Tancrède Lepoint, Yang Liu, Prateek Mittal, Mehryar Mohri, Richard Nock, Ayfer Özgür, Rasmus Pagh, Mariana Raykova, Hang Qi, Daniel Ramage, Ramesh Raskar, Dawn Song, Weikang Song, Sebastian U. Stich, Ziteng Sun, Ananda Theertha Suresh, Florian Tramèr, Praneeth Vepakomma, Jianyu Wang, Li Xiong, Zheng Xu, Qiang Yang, Felix X. Yu, Han Yu, Sen Zhao .[Advances and Open Problems in Federated Learning](https://arxiv.org/pdf/1912.04977) [J]. arXiv preprint arXiv:1912.04977.
- Shi Y, Yang K, Jiang T, et al. [Communication-efficient edge AI: Algorithms and systems](https://arxiv.org/pdf/2002.09668)[J]. arXiv preprint arXiv:2002.09668, 2020.
- Ahmed Imteaj, Urmish Thakker, Shiqiang Wang, Jian Li, M. Hadi Amini .[Federated Learning for Resource-Constrained IoT Devices: Panoramas and State-of-the-art](https://arxiv.org/pdf/2002.10610) [J]. arXiv preprint arXiv:2002.10610.
- Yilun Jin, Xiguang Wei, Yang Liu, Qiang Yang .[A Survey towards Federated Semi-supervised Learning](https://arxiv.org/pdf/2002.11545) [J]. arXiv preprint arXiv:2002.11545.
- Lingjuan Lyu, Han Yu, Qiang Yang .[Threats to Federated Learning: A Survey](https://arxiv.org/pdf/2003.02133) [J]. arXiv preprint arXiv:2003.02133.
- Viraj Kulkarni, Milind Kulkarni, Aniruddha Pant .[Survey of Personalization Techniques for Federated Learning](https://arxiv.org/pdf/2003.08673) [J]. arXiv preprint arXiv:2003.08673.
- Christopher Briggs, Zhong Fan, Peter Andras .[A Review of Privacy Preserving Federated Learning for Private IoT Analytics](https://arxiv.org/pdf/2004.11794) [J]. arXiv preprint arXiv:2004.11794.
- Yi Liu, Xingliang Yuan, Zehui Xiong, Jiawen Kang, Xiaofei Wang, Dusit Niyato .[Federated Learning for 6G Communications: Challenges, Methods, and Future Directions](https://arxiv.org/pdf/2006.02931) [J]. arXiv preprint arXiv:2006.02931.
- Seyyedali Hosseinalipour, Christopher G. Brinton, Vaneet Aggarwal, Huaiyu Dai, Mung Chiang .[From Federated Learning to Fog Learning: Towards Large-Scale Distributed Machine Learning in Heterogeneous Wireless Networks](https://arxiv.org/pdf/2006.03594) [J]. arXiv preprint arXiv:2006.03594.
- Gupta A, Lanteigne C, Kingsley S. [SECure: A Social and Environmental Certificate for AI Systems](https://arxiv.org/pdf/2006.06217)[J]. arXiv preprint arXiv:2006.06217, 2020.
- Yang M, Lyu L, Zhao J, et al. [Local differential privacy and its applications: A comprehensive survey](https://arxiv.org/pdf/2008.03686)[J]. arXiv preprint arXiv:2008.03686, 2020.


## Communication-Efficiency
- [good]Jakub Konečný, H. Brendan McMahan, Felix X. Yu, Peter Richtárik, Ananda Theertha Suresh, Dave Bacon .[Federated Learning: Strategies for Improving Communication Efficiency](https://arxiv.org/pdf/1610.05492) [J]. arXiv preprint arXiv:1610.05492.
- Yujun Lin, Song Han, Huizi Mao, Yu Wang, William J. Dally. [Deep Gradient Compression: Reducing the Communication Bandwidth for Distributed Training](https://arxiv.org/abs/1712.01887)[J]. arXiv preprint arXiv:1712.01887
- Nilsson A, Smith S, Ulm G, et al. [A performance evaluation of federated learning algorithms](https://www.researchgate.net/profile/Gregor_Ulm/publication/329106719_A_Performance_Evaluation_of_Federated_Learning_Algorithms/links/5c0fabcfa6fdcc494febf907/A-Performance-Evaluation-of-Federated-Learning-Algorithms.pdf)[C]//Proceedings of the Second Workshop on Distributed Infrastructures for Deep Learning. 2018: 1-8.
- Bui T D, Nguyen C V, Swaroop S, et al. [Partitioned variational inference: A unified framework encompassing federated and continual learning](https://arxiv.org/pdf/1811.11206)[J]. arXiv preprint arXiv:1811.11206, 2018.
- [good]Sebastian Caldas, Jakub Konečny, H. Brendan McMahan, Ameet Talwalkar .[Expanding the Reach of Federated Learning by Reducing Client Resource Requirements](https://arxiv.org/pdf/1812.07210) [J]. arXiv preprint arXiv:1812.07210.
- Hangyu Zhu, Yaochu Jin .[Multi-objective Evolutionary Federated Learning](https://arxiv.org/pdf/1812.07478) [J]. arXiv preprint arXiv:1812.07478.
- Neel Guha, Ameet Talwalkar, Virginia Smith .[One-Shot Federated Learning](https://arxiv.org/pdf/1902.11175) [J]. arXiv preprint arXiv:1902.11175.
- Yang Chen, Xiaoyan Sun, Yaochu Jin .[Communication-Efficient Federated Deep Learning with Asynchronous Model Update and Temporally Weighted Aggregation](https://arxiv.org/pdf/1903.07424) [J]. arXiv preprint arXiv:1903.07424.
- Chenghao Hu, Jingyan Jiang, Zhi Wang .[Decentralized Federated Learning: A Segmented Gossip Approach](https://arxiv.org/pdf/1908.07782) [J]. arXiv preprint arXiv:1908.07782.
- Abhishek Singh, Praneeth Vepakomma, Otkrist Gupta, Ramesh Raskar .[Detailed comparison of communication efficiency of split learning and federated learning](https://arxiv.org/pdf/1909.09145) [J]. arXiv preprint arXiv:1909.09145.
- Wentai Wu, Ligang He, Weiwei Lin, RuiMao, Stephen Jarvis .[SAFA: a Semi-Asynchronous Protocol for Fast Federated Learning with Low Overhead](https://arxiv.org/pdf/1910.01355) [J]. arXiv preprint arXiv:1910.01355.
- Yuqing Du, Sheng Yang, Kaibin Huang. [High-Dimensional Stochastic Gradient Quantization for Communication-Efficient Edge Learning](https://arxiv.org/abs/1910.03865)[J]. arXiv preprint arXiv:1019.03865
- Yan Z. [Gradient Sparification for Asynchronous Distributed Training](https://arxiv.org/pdf/1910.10929)[J]. arXiv preprint arXiv:1910.10929, 2019. 
- Anis Elgabli, Jihong Park, Sabbir Ahmed, Mehdi Bennis .[L-FGADMM: Layer-Wise Federated Group ADMM for Communication Efficient Decentralized Deep Learning](https://arxiv.org/pdf/1911.03654) [J]. arXiv preprint arXiv:1911.03654.
- Xinyan Dai, Xiao Yan, Kaiwen Zhou, Han Yang, Kelvin K. W. Ng, James Cheng, Yu Fan .[Hyper-Sphere Quantization: Communication-Efficient SGD for Federated Learning](https://arxiv.org/pdf/1911.04655) [J]. arXiv preprint arXiv:1911.04655.
- Asad M, Moustafa A, Ito T. [FedOpt: Towards Communication Efficiency and Privacy Preservation in Federated Learning](https://www.mdpi.com/2076-3417/10/8/2864/pdf)[J]. Applied Sciences, 2020, 10(8): 2864.
- Haozhao Wang, Zhihao Qu, Song Guo, Xin Gao, Ruixuan Li, Baoliu Ye .[Intermittent Pulling with Local Compensation for Communication-Efficient Federated Learning](https://arxiv.org/pdf/2001.08277) [J]. arXiv preprint arXiv:2001.08277.
- Anbu Huang, Yuanyuan Chen, Yang Liu, Tianjian Chen, Qiang Yang .[RPN: A Residual Pooling Network for Efficient Federated Learning](https://arxiv.org/pdf/2001.08600) [J]. arXiv preprint arXiv:2001.08600.
- Tang Z, Shi S, Chu X. [Communication-efficient decentralized learning with sparsification and adaptive peer selection](https://arxiv.org/pdf/2002.09692)[J]. arXiv preprint arXiv:2002.09692, 2020.
- Naifu Zhang, Meixia Tao .[Gradient Statistics Aware Power Control for Over-the-Air Federated Learning in Fading Channels](https://arxiv.org/pdf/2003.02089) [J]. arXiv preprint arXiv:2003.02089.
- Jinjin Xu, Wenli Du, Ran Cheng, Wangli He, Yaochu Jin .[Ternary Compression for Communication-Efficient Federated Learning](https://arxiv.org/pdf/2003.03564) [J]. arXiv preprint arXiv:2003.03564.
- Shaoxiong Ji, Wenqi Jiang, Anwar Walid, Xue Li .[Dynamic Sampling and Selective Masking for Communication-Efficient Federated Learning](https://arxiv.org/pdf/2003.09603) [J]. arXiv preprint arXiv:2003.09603.
- Muhammad Asad, Ahmed Moustafa, Takayuki Ito, Muhammad Aslam .[Evaluating the Communication Efficiency in Federated Learning Algorithms](https://arxiv.org/pdf/2004.02738) [J]. arXiv preprint arXiv:2004.02738.
- Mohammad Mohammadi Amiri, Deniz Gunduz, Sanjeev R. Kulkarni, H. Vincent Poor .[Federated Learning With Quantized Global Model Updates](https://arxiv.org/pdf/2006.10672) [J]. arXiv preprint arXiv:2006.10672.
- Horváth S, Richtárik P. [A Better Alternative to Error Feedback for Communication-Efficient Distributed Learning](https://arxiv.org/pdf/2006.11077)[J]. arXiv preprint arXiv:2006.11077, 2020.
- Xiang Ma, Haijian Sun, Rose Qingyang Hu .[Scheduling Policy and Power Allocation for Federated Learning in NOMA Based MEC](https://arxiv.org/pdf/2006.13044) [J]. arXiv preprint arXiv:2006.13044.
- Constantin Philippenko, Aymeric Dieuleveut .[Artemis: tight convergence guarantees for bidirectional compression in Federated Learning](https://arxiv.org/pdf/2006.14591) [J]. arXiv preprint arXiv:2006.14591.
- Shen T, Zhang J, Jia X, et al. [Federated Mutual Learning](https://arxiv.org/pdf/2006.16765)[J]. arXiv preprint arXiv:2006.16765, 2020.
- Farzin Haddadpour, Mohammad Mahdi Kamani, Aryan Mokhtari, Mehrdad Mahdavi .[Federated Learning with Compression: Unified Analysis and Sharp Guarantees](https://arxiv.org/pdf/2007.01154) [J]. arXiv preprint arXiv:2007.01154.


## Straggler Problem
- Sukjong Ha, Jingjing Zhang, Osvaldo Simeone, Joonhyuk Kang .[Coded Federated Computing in Wireless Networks with Straggling Devices and Imperfect CSI](https://arxiv.org/pdf/1901.05239) [J]. arXiv preprint arXiv:1901.05239.
- Linara Adilova, Julia Rosenzweig, Michael Kamp .[Information-Theoretic Perspective of Federated Learning](https://arxiv.org/pdf/1911.07652) [J]. arXiv preprint arXiv:1911.07652.
- Jinhyun So, Basak Guler, A. Salman Avestimehr .[Turbo-Aggregate: Breaking the Quadratic Aggregation Barrier in Secure Federated Learning](https://arxiv.org/pdf/2002.04156) [J]. arXiv preprint arXiv:2002.04156.
- Sagar Dhakal, Saurav Prakash, Yair Yona, Shilpa Talwar, Nageen Himayat .[Coded Federated Learning](https://arxiv.org/pdf/2002.09574) [J]. arXiv preprint arXiv:2002.09574.
- Zhifeng Jiang, Wei Wang, Baochun Li, Bo Li. [Pisces: Efficient Federated Learning via Guided Asynchronous Training](https://dl.acm.org/doi/abs/10.1145/3542929.3563463) [J] ACM SoCC 2022


## Computation Efficiency
- Li L, Xiong H, Guo Z, et al. [SmartPC: Hierarchical Pace Control in Real-Time Federated Learning System](https://www.ece.ucf.edu/~zsguo/pubs/conference_workshop/RTSS2019b.pdf)[C]//2019 IEEE Real-Time Systems Symposium (RTSS). IEEE, 2019: 406-418.
- Kumar D, Ramkumar A A, Sindhu R, et al. [Decaf: Iterative collaborative processing over the edge](https://www.usenix.org/system/files/hotedge19-paper-kumar.pdf)[C]//2nd {USENIX} Workshop on Hot Topics in Edge Computing (HotEdge 19). 2019.
- Vepakomma, Praneeth, et al. [Split Learning for Health: Distributed Deep Learning without Sharing Raw Patient Data.](https://arxiv.org/pdf/1812.00564) ArXiv Preprint ArXiv:1812.00564, 2018.
- Jinke Ren, Guanding Yu, Guangyao Ding .[Accelerating DNN Training in Wireless Federated Edge Learning System](https://arxiv.org/pdf/1905.09712) [J]. arXiv preprint arXiv:1905.09712.
- Vito Walter Anelli, Yashar Deldjoo, Tommaso Di Noia, Antonio Ferrara .[Towards Effective Device-Aware Federated Learning](https://arxiv.org/pdf/1908.07420) [J]. arXiv preprint arXiv:1908.07420.
- Yuang Jiang, Shiqiang Wang, Bong Jun Ko, Wei-Han Lee, Leandros Tassiulas .[Model Pruning Enables Efficient Federated Learning on Edge Devices](https://arxiv.org/pdf/1909.12326) [J]. arXiv preprint arXiv:1909.12326.
- Nicolas Skatchkovsky, Hyeryung Jang, Osvaldo Simeone .[Federated Neuromorphic Learning of Spiking Neural Networks for Low-Power Edge Intelligence](https://arxiv.org/pdf/1910.09594) [J]. arXiv preprint arXiv:1910.09594.
- Yujing Chen, Yue Ning, Huzefa Rangwala .[Asynchronous Online Federated Learning for Edge Devices](https://arxiv.org/pdf/1911.02134) [J]. arXiv preprint arXiv:1911.02134.
- Chaoyue Niu, Fan Wu, Shaojie Tang, Lifeng Hua, Rongfei Jia, Chengfei Lv, Zhihua Wu, Guihai Chen .[Secure Federated Submodel Learning](https://arxiv.org/pdf/1911.02254) [J]. arXiv preprint arXiv:1911.02254.
- Zirui Xu, Zhao Yang, Jinjun Xiong, Jianlei Yang, Xiang Chen .[ELFISH: Resource-Aware Federated Learning on Heterogeneous Edge Devices](https://arxiv.org/pdf/1912.01684) [J]. arXiv preprint arXiv:1912.01684.
- Martin Isaksson, Karl Norrman .[Secure Federated Learning in 5G Mobile Networks](https://arxiv.org/pdf/2004.06700) [J]. arXiv preprint arXiv:2004.06700.
- Sohei Itahara, Takayuki Nishio, Masahiro Morikura, Koji Yamamoto .[Lottery Hypothesis based Unsupervised Pre-training for Model Compression in Federated Learning](https://arxiv.org/pdf/2004.09817) [J]. arXiv preprint arXiv:2004.09817.
- Chandra Thapa, M.A.P. Chamikara, Seyit Camtepe .[SplitFed: When Federated Learning Meets Split Learning](https://arxiv.org/pdf/2004.12088) [J]. arXiv preprint arXiv:2004.12088.
- Rapp M, Khalili R, Henkel J. [Distributed Learning on Heterogeneous Resource-Constrained Devices](https://arxiv.org/pdf/2006.05403)[J]. arXiv preprint arXiv:2006.05403, 2020.


## Wireless Communication && Cloud Computing && networking
- Feraudo A, Yadav P, Safronov V, et al. [CoLearn: enabling federated learning in MUD-compliant IoT edge networks](https://www.researchgate.net/profile/Poonam_Yadav14/publication/341424819_CoLearn_Enabling_Federated_Learning_in_MUD-compliant_IoT_Edge_Networks/links/5ebf7fc5299bf1c09ac0b5dd/CoLearn-Enabling-Federated-Learning-in-MUD-compliant-IoT-Edge-Networks.pdf)[C]//Proceedings of the Third ACM International Workshop on Edge Systems, Analytics and Networking. 2020: 25-30.
- Umair Mohammad, Sameh Sorour .[Adaptive Task Allocation for Asynchronous Federated Mobile Edge Learning](https://arxiv.org/pdf/1905.01656) [J]. arXiv preprint arXiv:1905.01656.
- Xiaofei Wang, Yiwen Han, Chenyang Wang, Qiyang Zhao, Xu Chen, Min Chen .[In-Edge AI: Intelligentizing Mobile Edge Computing, Caching and  Communication by Federated Learning](https://arxiv.org/pdf/1809.07857) [J]. arXiv preprint arXiv:1809.07857.
- Shaohan Feng, Dusit Niyato, Ping Wang, Dong In Kim, Ying-Chang Liang .[Joint Service Pricing and Cooperative Relay Communication for Federated Learning](https://arxiv.org/pdf/1811.12082) [J]. arXiv preprint arXiv:1811.12082.
- Mingzhe Chen, Omid Semiari, Walid Saad, Xuanlin Liu, Changchuan Yin .[Federated Echo State Learning for Minimizing Breaks in Presence in Wireless Virtual Reality Networks](https://arxiv.org/pdf/1812.01202) [J]. arXiv preprint arXiv:1812.01202.
- Guangxu Zhu, Yong Wang, Kaibin Huang .[Low-Latency Broadband Analog Aggregation for Federated Edge Learning](https://arxiv.org/pdf/1812.11494) [J]. arXiv preprint arXiv:1812.11494.
- Kai Yang, Tao Jiang, Yuanming Shi, Zhi Ding .[Federated Learning via Over-the-Air Computation](https://arxiv.org/pdf/1812.11750) [J]. arXiv preprint arXiv:1812.11750.
- Tran N H, Bao W, Zomaya A, et al. [Federated learning over wireless networks: Optimization model design and analysis](http://163.180.116.116/layouts/net/publications/data/2019)Federated%20Learning%20over%20Wireless%20Network.pdf)[C]//IEEE INFOCOM 2019-IEEE Conference on Computer Communications. IEEE, 2019: 1387-1395.
- Amiri M M, Gündüz D. [Machine learning at the wireless edge: Distributed stochastic gradient descent over-the-air](https://arxiv.org/pdf/1901.00844)[J]. IEEE Transactions on Signal Processing, 2020, 68: 2155-2169.
- Guan Wang .[Interpret Federated Learning with Shapley Values](https://arxiv.org/pdf/1905.04519) [J]. arXiv preprint arXiv:1905.04519.
- Qian J, Sengupta S, Hansen L K. [Active learning solution on distributed edge computing](https://arxiv.org/pdf/1906.10718)[J]. arXiv preprint arXiv:1906.10718, 2019.
- Yang Zhao, Jun Zhao, Linshan Jiang, Rui Tan, Dusit Niyato .[Mobile Edge Computing, Blockchain and Reputation-based Crowdsourcing IoT Federated Learning: A Secure, Decentralized and Privacy-preserving System](https://arxiv.org/pdf/1906.10893) [J]. arXiv preprint arXiv:1906.10893.
- Qunsong Zeng, Yuqing Du, Kin K. Leung, Kaibin Huang .[Energy-Efficient Radio Resource Allocation for Federated Edge Learning](https://arxiv.org/pdf/1907.06040) [J]. arXiv preprint arXiv:1907.06040.
- Mohammad Mohammadi Amiri, Deniz Gunduz .[Federated Learning over Wireless Fading Channels](https://arxiv.org/pdf/1907.09769) [J]. arXiv preprint arXiv:1907.09769.
- Evita Bakopoulou, Balint Tillman, Athina Markopoulou .[A Federated Learning Approach for Mobile Packet Classification](https://arxiv.org/pdf/1907.13113) [J]. arXiv preprint arXiv:1907.13113.
- Xin Yao, Tianchi Huang, Chenglei Wu, Rui-Xiao Zhang, Lifeng Sun .[Federated Learning with Additional Mechanisms on Clients to Reduce Communication Costs](https://arxiv.org/pdf/1908.05891) [J]. arXiv preprint arXiv:1908.05891.
- Howard H. Yang, Zuozhu Liu, Tony Q. S. Quek, H. Vincent Poor .[Scheduling Policies for Federated Learning in Wireless Networks](https://arxiv.org/pdf/1908.06287) [J]. arXiv preprint arXiv:1908.06287.
- Mehdi Salehi Heydar Abad, Emre Ozfatura, Deniz Gunduz, Ozgur Ercetin .[Hierarchical Federated Learning Across Heterogeneous Cellular Networks](https://arxiv.org/pdf/1909.02362) [J]. arXiv preprint arXiv:1909.02362.
- Chuan Ma, Jun Li, Ming Ding, Howard Hao Yang, Feng Shu, Tony Q. S. Quek, H. Vincent Poor .[On Safeguarding Privacy and Security in the Framework of Federated Learning](https://arxiv.org/pdf/1909.06512) [J]. arXiv preprint arXiv:1909.06512.
- Mingzhe Chen, Zhaohui Yang, Walid Saad, Changchuan Yin, H. Vincent Poor, Shuguang Cui .[A Joint Learning and Communications Framework for Federated Learning over Wireless Networks](https://arxiv.org/pdf/1909.07972) [J]. arXiv preprint arXiv:1909.07972.
- Tung T. Vu, Duy T. Ngo, Nguyen H. Tran, Hien Quoc Ngo, Minh N. Dao, Richard H. Middleton .[Cell-Free Massive MIMO for Wireless Federated Learning](https://arxiv.org/pdf/1909.12567) [J]. arXiv preprint arXiv:1909.12567.
- Jack Goetz, Kshitiz Malik, Duc Bui, Seungwhan Moon, Honglei Liu, Anuj Kumar .[Active Federated Learning](https://arxiv.org/pdf/1909.12641) [J]. arXiv preprint arXiv:1909.12641.
- Amirhossein Reisizadeh, Aryan Mokhtari, Hamed Hassani, Ali Jadbabaie, Ramtin Pedarsani .[FedPAQ: A Communication-Efficient Federated Learning Method with Periodic Averaging and Quantization](https://arxiv.org/pdf/1909.13014) [J]. arXiv preprint arXiv:1909.13014.
- Jiawen Kang, Zehui Xiong, Dusit Niyato, Yuze Zou, Yang Zhang, Mohsen Guizani .[Reliable Federated Learning for Mobile Networks](https://arxiv.org/pdf/1910.06837) [J]. arXiv preprint arXiv:1910.06837.
- Huy T. Nguyen, Nguyen Cong Luong, Jun Zhao, Chau Yuen, Dusit Niyato .[Resource Allocation in Mobility-Aware Federated Learning Networks: A Deep Reinforcement Learning Approach](https://arxiv.org/pdf/1910.09172) [J]. arXiv preprint arXiv:1910.09172.
- Canh Dinh, Nguyen H. Tran, Minh N. H. Nguyen, Choong Seon Hong, Wei Bao, Albert Y. Zomaya, Vincent Gramoli .[Federated Learning over Wireless Networks: Convergence Analysis and Resource Allocation](https://arxiv.org/pdf/1910.13067) [J]. arXiv preprint arXiv:1910.13067.
- Howard H. Yang, Ahmed Arafa, Tony Q. S. Quek, H. Vincent Poor .[Age-Based Scheduling Policy for Federated Learning in Mobile Edge Networks](https://arxiv.org/pdf/1910.14648) [J]. arXiv preprint arXiv:1910.14648.
- Yuxuan Sun, Sheng Zhou, Deniz Gündüz .[Energy-Aware Analog Aggregation for Federated Learning with Redundant Data](https://arxiv.org/pdf/1911.00188) [J]. arXiv preprint arXiv:1911.00188.
- Wenqi Shi, Sheng Zhou, Zhisheng Niu .[Device Scheduling with Fast Convergence for Wireless Federated Learning](https://arxiv.org/pdf/1911.00856) [J]. arXiv preprint arXiv:1911.00856.
- Zhaohui Yang, Mingzhe Chen, Walid Saad, Choong Seon Hong, Mohammad Shikh-Bahaei .[Energy Efficient Federated Learning Over Wireless Communication Networks](https://arxiv.org/pdf/1911.02417) [J]. arXiv preprint arXiv:1911.02417.
- Jun Li, Xiaoman Shen, Lei Chen, Jiajia Chen .[Bandwidth Slicing to Boost Federated Learning in Edge Computing](https://arxiv.org/pdf/1911.07615) [J]. arXiv preprint arXiv:1911.07615.
- Keith Bonawitz, Fariborz Salehi, Jakub Konečný, Brendan McMahan, Marco Gruteser .[Federated Learning with Autotuned Communication-Efficient Secure Aggregation](https://arxiv.org/pdf/1912.00131) [J]. arXiv preprint arXiv:1912.00131.
- Jinho Choi, Shiva Raj Pokhrel .[Federated learning with multichannel ALOHA](https://arxiv.org/pdf/1912.06273) [J]. arXiv preprint arXiv:1912.06273.
- Yanan Li, Shusen Yang, Xuebin Ren, Cong Zhao .[Asynchronous Federated Learning with Differential Privacy for Edge Intelligence](https://arxiv.org/pdf/1912.07902) [J]. arXiv preprint arXiv:1912.07902.
- Stefano Savazzi, Monica Nicoli, Vittorio Rampa .[Federated Learning with Cooperating Devices: A Consensus Approach for Massive IoT Networks](https://arxiv.org/pdf/1912.13163) [J]. arXiv preprint arXiv:1912.13163.
- Guangxu Zhu, Yuqing Du, Deniz Gunduz, Kaibin Huang .[One-Bit Over-the-Air Aggregation for Communication-Efficient Federated Edge Learning: Design and Convergence Analysis](https://arxiv.org/pdf/2001.05713) [J]. arXiv preprint arXiv:2001.05713.
- Mingzhe Chen, H. Vincent Poor, Walid Saad, Shuguang Cui .[Convergence Time Optimization for Federated Learning over Wireless Networks](https://arxiv.org/pdf/2001.07845) [J]. arXiv preprint arXiv:2001.07845.
- Wei-Ting Chang, Ravi Tandon .[Communication Efficient Federated Learning over Multiple Access Channels](https://arxiv.org/pdf/2001.08737) [J]. arXiv preprint arXiv:2001.08737.
- Mohammad Mohammadi Amiri, Deniz Gunduz, Sanjeev R. Kulkarni, H. Vincent Poor .[Update Aware Device Scheduling for Federated Learning at the Wireless Edge](https://arxiv.org/pdf/2001.10402) [J]. arXiv preprint arXiv:2001.10402.
- Chakraborty S, Mohammed H, Saha D. [Learning from Peers at the Wireless Edge](https://arxiv.org/pdf/2001.11567.pdf)[C]//2020 International Conference on COMmunication Systems & NETworkS (COMSNETS). IEEE, 2020: 779-784.
- Mohamed Seif, Ravi Tandon, Ming Li .[Wireless Federated Learning with Local Differential Privacy](https://arxiv.org/pdf/2002.05151) [J]. arXiv preprint arXiv:2002.05151.
- Tengchan Zeng, Omid Semiari, Mohammad Mozaffari, Mingzhe Chen, Walid Saad, Mehdi Bennis .[Federated Learning in the Sky: Joint Power Allocation and Scheduling with UAV Swarms](https://arxiv.org/pdf/2002.08196) [J]. arXiv preprint arXiv:2002.08196.
- Hong Xing, Osvaldo Simeone, Suzhi Bi .[Decentralized Federated Learning via SGD over Wireless D2D Networks](https://arxiv.org/pdf/2002.12507) [J]. arXiv preprint arXiv:2002.12507.
- Praneeth Narayanamurthy, Namrata Vaswani, Aditya Ramamoorthy .[Federated Over-the-Air Subspace Learning from Incomplete Data](https://arxiv.org/pdf/2002.12873) [J]. arXiv preprint arXiv:2002.12873.
- Xiaopeng Mo, Jie Xu .[Energy-Efficient Federated Edge Learning with Joint Communication and Computation Design](https://arxiv.org/pdf/2003.00199) [J]. arXiv preprint arXiv:2003.00199.
- Kang Wei, Jun Li, Ming Ding, Chuan Ma, Hang Su, Bo Zhang, H. Vincent Poor .[Performance Analysis and Optimization in Privacy-Preserving Federated Learning](https://arxiv.org/pdf/2003.00229) [J]. arXiv preprint arXiv:2003.00229.
- Haijian Sun, Xiang Ma, Rose Qingyang Hu .[Adaptive Federated Learning With Gradient Compression in Uplink NOMA](https://arxiv.org/pdf/2003.01344) [J]. arXiv preprint arXiv:2003.01344.
- Yo-Seb Jeon, Mohammad Mohammadi Amiri, Jun Li, H. Vincent Poor .[Gradient Estimation for Federated Learning over Massive MIMO Communication Systems](https://arxiv.org/pdf/2003.08059) [J]. arXiv preprint arXiv:2003.08059.
- Sihua Wang, Mingzhe Chen, Changchuan Yin, Walid Saad, Choong Seon Hong, Shuguang Cui, H. Vincent Poor .[Federated Learning for Task and Resource Allocation in Wireless High Altitude Balloon Networks](https://arxiv.org/pdf/2003.09375) [J]. arXiv preprint arXiv:2003.09375.
- Rui Hu, Yuanxiong Guo, E. Paul. Ratazzi, Yanmin Gong .[Differentially Private Federated Learning for Resource-Constrained Internet of Things](https://arxiv.org/pdf/2003.12705) [J]. arXiv preprint arXiv:2003.12705.
- Jinke Ren, Yinghui He, Dingzhu Wen, Guanding Yu, Kaibin Huang, Dongning Guo .[Scheduling in Cellular Federated Edge Learning with Importance and Channel Awareness](https://arxiv.org/pdf/2004.00490) [J]. arXiv preprint arXiv:2004.00490.
- Yuzheng Li, Chuan Chen, Nan Liu, Huawei Huang, Zibin Zheng, Qiang Yan .[A Blockchain-based Decentralized Federated Learning Framework with Committee Consensus](https://arxiv.org/pdf/2004.00773) [J]. arXiv preprint arXiv:2004.00773.
- Nguyen Quang Hieu, Tran The Anh, Nguyen Cong Luong, Dusit Niyato, Dong In Kim, Erik Elmroth .[Resource Management for Blockchain-enabled Federated Learning: A Deep Reinforcement Learning Approach](https://arxiv.org/pdf/2004.04104) [J]. arXiv preprint arXiv:2004.04104.
- Jie Xu, Heqiang Wang .[Client Selection and Bandwidth Allocation in Wireless Federated Learning Networks: A Long-Term Perspective](https://arxiv.org/pdf/2004.04314) [J]. arXiv preprint arXiv:2004.04314.
- Kai Yang, Yuanming Shi, Yong Zhou, Zhanpeng Yang, Liqun Fu, Wei Chen .[Federated Machine Learning for Intelligent IoT via Reconfigurable Intelligent Surface](https://arxiv.org/pdf/2004.05843) [J]. arXiv preprint arXiv:2004.05843.
- Martin Isaksson, Karl Norrman .[Secure Federated Learning in 5G Mobile Networks](https://arxiv.org/pdf/2004.06700) [J]. arXiv preprint arXiv:2004.06700.
- Richeng Jin, Xiaofan He, Huaiyu Dai .[On the Design of Communication Efficient Federated Learning over Wireless Networks](https://arxiv.org/pdf/2004.07351) [J]. arXiv preprint arXiv:2004.07351.
- Meng Jiang, Taeho Jung, Ryan Karl, Tong Zhao .[Federated Dynamic GNN with Secure Aggregation](https://arxiv.org/pdf/2009.07351) [J]. arXiv preprint arXiv:2009.07351.
- Tu Y, Ruan Y, Wang S, et al. [Network-Aware Optimization of Distributed Learning for Fog Computing](https://arxiv.org/pdf/2004.08488)[J]. arXiv preprint arXiv:2004.08488, 2020.
- Yu D, Park S H, Simeone O, et al. [Optimizing Over-the-Air Computation in IRS-Aided C-RAN Systems](https://arxiv.org/pdf/2004.09168)[J]. arXiv preprint arXiv:2004.09168, 2020.
- Yong Xiao, Guangming Shi, Marwan Krunz .[Towards Ubiquitous AI in 6G with Federated Learning](https://arxiv.org/pdf/2004.13563) [J]. arXiv preprint arXiv:2004.13563.
- Ha-Vu Tran, Georges Kaddoum, Hany Elgala, Chadi Abou-Rjeily, Hemani Kaushal .[Lightwave Power Transfer for Federated Learning-based Wireless Networks](https://arxiv.org/pdf/2005.03977) [J]. arXiv preprint arXiv:2005.03977.
- Zhijin Qin, Geoffrey Ye Li, Hao Ye .[Federated Learning and Wireless Communications](https://arxiv.org/pdf/2005.05265) [J]. arXiv preprint arXiv:2005.05265.
- Yi Liu, Jialiang Peng, Jiawen Kang, Abdullah M. Iliyasu, Dusit Niyato, Ahmed A. Abd El-Latif .[A Secure Federated Learning Framework for 5G Networks](https://arxiv.org/pdf/2005.05752) [J]. arXiv preprint arXiv:2005.05752.
- Amir Sonee, Stefano Rini .[Efficient Federated Learning over Multiple Access Channel with Differential Privacy Constraints](https://arxiv.org/pdf/2005.07776) [J]. arXiv preprint arXiv:2005.07776.
- Ahmet M. Elbir, Sinem Coleri .[Federated Deep Learning Framework For Hybrid Beamforming in mm-Wave Massive MIMO](https://arxiv.org/pdf/2005.09969) [J]. arXiv preprint arXiv:2005.09969.
- Mingzhe Chen, H. Vincent Poor, Walid Saad, Shuguang Cui .[Wireless Communications for Collaborative Federated Learning in the Internet of Things](https://arxiv.org/pdf/2006.02499) [J]. arXiv preprint arXiv:2006.02499.
- Nir Shlezinger, Mingzhe Chen, Yonina C. Eldar, H. Vincent Poor, Shuguang Cui .[UVeQFed: Universal Vector Quantization for Federated Learning](https://arxiv.org/pdf/2006.03262) [J]. arXiv preprint arXiv:2006.03262.
- Seungeun Oh, Jihong Park, Eunjeong Jeong, Hyesung Kim, Mehdi Bennis, Seong-Lyun Kim .[Mix2FLD: Downlink Federated Learning After Uplink Federated Distillation With Two-Way Mixup](https://arxiv.org/pdf/2006.09801) [J]. arXiv preprint arXiv:2006.09801.
- Tourani R, Srikanteswara S, Misra S, et al. [Democratizing the Edge: A Pervasive Edge Computing Framework](https://arxiv.org/pdf/2007.00641)[J]. arXiv preprint arXiv:2007.00641, 2020.


## System Design
- [Baseline]Brendan McMahan H, Moore E, Ramage D, et al. [Communication-Efficient Learning of Deep Networks from Decentralized Data](https://arxiv.org/pdf/1602.05629.pdf)[J]. arXiv, 2016: arXiv: 1602.05629.
- Ryffel T, Trask A, Dahl M, et al. [A generic framework for privacy preserving deep learning](https://arxiv.org/pdf/1811.04017.pdf!)[J]. arXiv preprint arXiv:1811.04017, 2018.
- [good]Keith Bonawitz, Hubert Eichner, Wolfgang Grieskamp, Dzmitry Huba, Alex Ingerman, Vladimir Ivanov, Chloe Kiddon, Jakub Konecny, Stefano Mazzocchi, H. Brendan McMahan, Timon Van Overveldt, David Petrou, Daniel Ramage, Jason Roselander .[Towards Federated Learning at Scale: System Design](https://arxiv.org/pdf/1902.01046) [J]. arXiv preprint arXiv:1902.01046.
- Paritosh Ramanan, Kiyoshi Nakayama, Ratnesh Sharma .[BAFFLE : Blockchain based Aggregator Free Federated Learning](https://arxiv.org/pdf/1909.07452) [J]. arXiv preprint arXiv:1909.07452.
- Galtier M N, Marini C. [Substra: a framework for privacy-preserving, traceable and collaborative Machine Learning](https://arxiv.org/pdf/1910.11567)[J]. arXiv preprint arXiv:1910.11567, 2019.
- Anirban Das, Thomas Brunschwiler .[Privacy is What We Care About: Experimental Investigation of Federated Learning on Edge Devices](https://arxiv.org/pdf/1911.04559) [J]. arXiv preprint arXiv:1911.04559.
- Zirui Xu, Zhao Yang, Jinjun Xiong, Jianlei Yang, Xiang Chen .[ELFISH: Resource-Aware Federated Learning on Heterogeneous Edge Devices](https://arxiv.org/pdf/1912.01684) [J]. arXiv preprint arXiv:1912.01684.
- Qinghe Jing, Weiyan Wang, Junxue Zhang, Han Tian, Kai Chen .[Quantifying the Performance of Federated Transfer Learning](https://arxiv.org/pdf/1912.12795) [J]. arXiv preprint arXiv:1912.12795.
- Jiang J, Ji S, Long G. [Decentralized knowledge acquisition for mobile internet applications](https://idp.springer.com/authorize/casa?redirect_uri=https://link.springer.com/content/pdf/10.1007/s11280-019-00775-w.pdf&casa_token=n41M2VzZ6UkAAAAA:K-Z0rlst7vi-5s47Hytmmo0N7oRKWglGXJuhjFR200FdUMg_YoeJ8J7e5eT64C2AE4lv61Xu72czRXQ)[J]. World Wide Web, 2020: 1-17.
- Pengchao Han, Shiqiang Wang, Kin K. Leung .[Adaptive Gradient Sparsification for Efficient Federated Learning: An Online Learning Approach](https://arxiv.org/pdf/2001.04756) [J]. arXiv preprint arXiv:2001.04756.
- Zheng Chai, Ahsan Ali, Syed Zawad, Stacey Truex, Ali Anwar, Nathalie Baracaldo, Yi Zhou, Heiko Ludwig, Feng Yan, Yue Cheng .[TiFL: A Tier-based Federated Learning System](https://arxiv.org/pdf/2001.09249) [J]. arXiv preprint arXiv:2001.09249.
- Rongfei Zeng, Shixun Zhang, Jiaqi Wang, Xiaowen Chu .[FMore: An Incentive Scheme of Multi-dimensional Auction for Federated Learning in MEC](https://arxiv.org/pdf/2002.09699) [J]. arXiv preprint arXiv:2002.09699.
- Liu D, Chen X, Zhou Z, et al. [HierTrain: Fast Hierarchical Edge AI Learning with Hybrid Parallelism in Mobile-Edge-Cloud Computing](https://arxiv.org/pdf/2003.09876.pdf)[J]. IEEE Open Journal of the Communications Society, 2020.
- Thomas Hiessl, Daniel Schall, Jana Kemnitz, Stefan Schulte .[Industrial Federated Learning -- Requirements and System Design](https://arxiv.org/pdf/2005.06850) [J]. arXiv preprint arXiv:2005.06850.
- Wu G, Gong S. [Decentralised Learning from Independent Multi-Domain Labels for Person Re-Identification](https://arxiv.org/pdf/2006.04150)[J]. arXiv preprint arXiv:2006.04150, 2020.
- Chengxu Yang, QiPeng Wang, Mengwei Xu, Shangguang Wang, Kaigui Bian, Xuanzhe Liu .[Heterogeneity-Aware Federated Learning](https://arxiv.org/pdf/2006.06983) [J]. arXiv preprint arXiv:2006.06983.
- Georgios Damaskinos, Rachid Guerraoui, Anne-Marie Kermarrec, Vlad Nitu, Rhicheek Patra, Francois Taiani .[FLeet: Online Federated Learning via Staleness Awareness and Performance Prediction](https://arxiv.org/pdf/2006.07273) [J]. arXiv preprint arXiv:2006.07273.
- Nuria Rodríguez-Barroso, Goran Stipcich, Daniel Jiménez-López, José Antonio Ruiz-Millán, Eugenio Martínez-Cámara, Gerardo González-Seco, M. Victoria Luzón, Miguel Ángel Veganzones, Francisco Herrera .[Federated Learning and Differential Privacy: Software tools analysis, the Sherpa.ai FL framework and methodological guidelines for preserving data privacy](https://arxiv.org/pdf/2007.00914) [J]. arXiv preprint arXiv:2007.00914.
- Chaoyang He, Songze Li, Jinhyun So, Mi Zhang, Hongyi Wang, Xiaoyang Wang, Praneeth Vepakomma, Abhishek Singh, Hang Qiu, Li Shen, Peilin Zhao, Yan Kang, Yang Liu, Ramesh Raskar, Qiang Yang, Murali Annavaram, Salman Avestimehr .[FedML: A Research Library and Benchmark for Federated Machine Learning](https://arxiv.org/pdf/2007.13518) [J]. arXiv preprint arXiv:2007.13518.<br>[code:[FedML-AI/FedML](https://github.com/FedML-AI/FedML)]
- Daniel J. Beutel, Taner Topal, Akhil Mathur, Xinchi Qiu, Titouan Parcollet, Nicholas D. Lane .[Flower: A Friendly Federated Learning Research Framework](https://arxiv.org/pdf/2007.14390) [J]. arXiv preprint arXiv:2007.14390.


## Models
- Cho M, Lai L, Xu W. [Distributed Dual Coordinate Ascent in General Tree Networks and Its Application in Federated Learning](https://arxiv.org/pdf/1703.04785)[J]. arXiv preprint arXiv:1703.04785, 2017.
- Hardy C, Le Merrer E, Sericola B. [Md-gan: Multi-discriminator generative adversarial networks for distributed datasets](https://arxiv.org/pdf/1811.03850)[C]//2019 IEEE International Parallel and Distributed Processing Symposium (IPDPS). IEEE, 2019: 866-877.
- Chen, Qingrong, et al. [Differentially Private Data Generative Models.](https://arxiv.org/pdf/1812.02274) ArXiv Preprint ArXiv:1812.02274, 2018.
- Yang Liu, Yingting Liu, Zhijie Liu, Junbo Zhang, Chuishi Meng, Yu Zheng .[Federated Forest](https://arxiv.org/pdf/1905.10053) [J]. arXiv preprint arXiv:1905.10053.
- Di Chai, Leye Wang, Kai Chen, Qiang Yang .[Secure Federated Matrix Factorization](https://arxiv.org/pdf/1906.05108) [J]. arXiv preprint arXiv:1906.05108.
- Ickin S, Vandikas K, Fiedler M. [Privacy preserving qoe modeling using collaborative learning](https://arxiv.org/pdf/1906.09248)[C]//Proceedings of the 4th Internet-QoE Workshop on QoE-based Analysis and Management of Data Communication Networks. 2019: 13-18.
- Mengwei Yang, Linqi Song, Jie Xu, Congduan Li, Guozhen Tan .[The Tradeoff Between Privacy and Accuracy in Anomaly Detection Using Federated XGBoost](https://arxiv.org/pdf/1907.07157) [J]. arXiv preprint arXiv:1907.07157.
- Seok-Ju Hahn, Junghye Lee .[Privacy-preserving Federated Bayesian Learning of a Generative Model for Imbalanced Classification of Clinical Data](https://arxiv.org/pdf/1910.08489) [J]. arXiv preprint arXiv:1910.08489.
- Qinbin Li, Zeyi Wen, Bingsheng He .[Practical Federated Gradient Boosting Decision Trees](https://arxiv.org/pdf/1911.04206) [J]. arXiv preprint arXiv:1911.04206.
- [ICLR]Augenstein, Sean, et al. [Generative Models for Effective ML on Private, Decentralized Datasets](https://arxiv.org/abs/1911.06679) ArXiv Preprint ArXiv:1911.06679, 2019.<br>[code:[tensorflow/gan](https://github.com/tensorflow/gan)]
- Feng Z, Xiong H, Song C, et al. [SecureGBM: Secure multi-party gradient boosting](https://arxiv.org/pdf/1911.11997)[C]//2019 IEEE International Conference on Big Data (Big Data). IEEE, 2019: 1312-1321.
- Shuai Wang, Tsung-Hui Chang .[Federated Clustering via Matrix Factorization Models: From Model Averaging to Gradient Sharing](https://arxiv.org/pdf/2002.04930) [J]. arXiv preprint arXiv:2002.04930.
- Yang Liu, Mingxin Chen, Wenxi Zhang, Junbo Zhang, Yu Zheng .[Federated Extra-Trees with Privacy Preserving](https://arxiv.org/pdf/2002.07323) [J]. arXiv preprint arXiv:2002.07323.
- Rei Ito, Mineto Tsukada, Hiroki Matsutani .[An On-Device Federated Learning Approach for Cooperative Anomaly Detection](https://arxiv.org/pdf/2002.12301) [J]. arXiv preprint arXiv:2002.12301.
- Chenyou Fan, Ping Liu .[Federated Generative Adversarial Learning](https://arxiv.org/pdf/2005.03793) [J]. arXiv preprint arXiv:2005.03793.
- Mathieu Andreux, Andre Manoel, Romuald Menuet, Charlie Saillard, Chloé Simpson .[Federated Survival Analysis with Discrete-Time Cox Models](https://arxiv.org/pdf/2006.08997) [J]. arXiv preprint arXiv:2006.08997.
- Dashan Gao, Ben Tan, Ce Ju, Vincent W. Zheng, Qiang Yang .[Privacy Threats Against Federated Matrix Factorization](https://arxiv.org/pdf/2007.01587) [J]. arXiv preprint arXiv:2007.01587.



## Natural language Processing
- David Leroy, Alice Coucke, Thibaut Lavril, Thibault Gisselbrecht, Joseph Dureau .[Federated Learning for Keyword Spotting](https://arxiv.org/pdf/1810.05512) [J]. arXiv preprint arXiv:1810.05512.
- [good]Andrew Hard, Kanishka Rao, Rajiv Mathews, Françoise Beaufays, Sean Augenstein, Hubert Eichner, Chloé Kiddon, Daniel Ramage .[Federated Learning for Mobile Keyboard Prediction](https://arxiv.org/pdf/1811.03604) [J]. arXiv preprint arXiv:1811.03604.
- Timothy Yang, Galen Andrew, Hubert Eichner, Haicheng Sun, Wei Li, Nicholas Kong, Daniel Ramage, Françoise Beaufays .[Applied Federated Learning: Improving Google Keyboard Query Suggestions](https://arxiv.org/pdf/1812.02903) [J]. arXiv preprint arXiv:1812.02903.
- Ji S, Pan S, Long G, et al. [Learning private neural language modeling with attentive aggregation](https://arxiv.org/pdf/1812.07108)[C]//2019 International Joint Conference on Neural Networks (IJCNN). IEEE, 2019: 1-8.<br>[code:[shaoxiongji/fed-att](https://github.com/shaoxiongji/fed-att)]
- Jiang, Di, et al. [Federated Topic Modeling](https://dl.acm.org/doi/10.1145/3357384.3357909) Proceedings of the 28th ACM International Conference on Information and Knowledge Management, 2019, pp. 1071–1080.
- Mingqing Chen, Rajiv Mathews, Tom Ouyang, Françoise Beaufays .[Federated Learning Of Out-Of-Vocabulary Words](https://arxiv.org/pdf/1903.10635) [J]. arXiv preprint arXiv:1903.10635.
- Rajagopal. A, Nirmala. V .[Federated AI lets a team imagine together: Federated Learning of GANs](https://arxiv.org/pdf/1906.03595) [J]. arXiv preprint arXiv:1906.03595.
- Swaroop Ramaswamy, Rajiv Mathews, Kanishka Rao, Françoise Beaufays .[Federated Learning for Emoji Prediction in a Mobile Keyboard](https://arxiv.org/pdf/1906.04329) [J]. arXiv preprint arXiv:1906.04329.
- Dianbo Liu, Dmitriy Dligach, Timothy Miller .[Two-stage Federated Phenotyping and Patient Representation Learning](https://arxiv.org/pdf/1908.05596) [J]. arXiv preprint arXiv:1908.05596.
- Duc Bui, Kshitiz Malik, Jack Goetz, Honglei Liu, Seungwhan Moon, Anuj Kumar, Kang G. Shin .[Federated User Representation Learning](https://arxiv.org/pdf/1909.12535) [J]. arXiv preprint arXiv:1909.12535.
- Mingqing Chen, Ananda Theertha Suresh, Rajiv Mathews, Adeline Wong, Cyril Allauzen, Françoise Beaufays, Michael Riley .[Federated Learning of N-gram Language Models](https://arxiv.org/pdf/1910.03432) [J]. arXiv preprint arXiv:1910.03432.
- Florian Hartmann, Sunah Suh, Arkadiusz Komarzewski, Tim D. Smith, Ilana Segall .[Federated Learning for Ranking Browser History Suggestions](https://arxiv.org/pdf/1911.11807) [J]. arXiv preprint arXiv:1911.11807.
- Dianbo Liu, Tim Miller .[Federated pretraining and fine tuning of BERT using clinical notes from multiple silos](https://arxiv.org/pdf/2002.08562) [J]. arXiv preprint arXiv:2002.08562.
- Suyu Ge, Fangzhao Wu, Chuhan Wu, Tao Qi, Yongfeng Huang, Xing Xie .[FedNER: Privacy-preserving Medical Named Entity Recognition with Federated Learning](https://arxiv.org/pdf/2003.09288) [J]. arXiv preprint arXiv:2003.09288.
- Joel Stremmel, Arjun Singh .[Pretraining Federated Text Models for Next Word Prediction](https://arxiv.org/pdf/2005.04828) [J]. arXiv preprint arXiv:2005.04828.
- Om Thakkar, Swaroop Ramaswamy, Rajiv Mathews, Françoise Beaufays .[Understanding Unintended Memorization in Federated Learning](https://arxiv.org/pdf/2006.07490) [J]. arXiv preprint arXiv:2006.07490.


## Computer Vision
- Tzu-Ming Harry Hsu, Hang Qi, Matthew Brown .[Measuring the Effects of Non-Identical Data Distribution for Federated Visual Classification](https://arxiv.org/pdf/1909.06335) [J]. arXiv preprint arXiv:1909.06335.
- Yang Liu, Anbu Huang, Yun Luo, He Huang, Youzhi Liu, Yuanyuan Chen, Lican Feng, Tianjian Chen, Han Yu, Qiang Yang .[FedVision: An Online Visual Object Detection Platform Powered by Federated Learning](https://arxiv.org/pdf/2001.06202) [J]. arXiv preprint arXiv:2001.06202.
- [CVPR]Tzu-Ming Harry Hsu, Hang Qi, Matthew Brown .[Federated Visual Classification with Real-World Data Distribution](https://arxiv.org/pdf/2003.08082) [J]. arXiv preprint arXiv:2003.08082.<br>[code:[google-research/federated_vision_datasets](https://github.com/google-research/google-research/tree/master/federated_vision_datasets)]
- Rui Shao, Pramuditha Perera, Pong C. Yuen, Vishal M. Patel .[Federated Face Anti-spoofing](https://arxiv.org/pdf/2005.14638) [J]. arXiv preprint arXiv:2005.14638.



## Health Care
- Sheller M J, Reina G A, Edwards B, et al. [Multi-institutional deep learning modeling without sharing patient data: A feasibility study on brain tumor segmentation](https://arxiv.org/abs/1810.04304)[C]//International MICCAI Brainlesion Workshop. Springer, Cham, 2018: 92-104.
- Santiago Silva, Boris Gutman, Eduardo Romero, Paul M Thompson, Andre Altmann, Marco Lorenzi .[Federated Learning in Distributed Medical Databases: Meta-Analysis of Large-Scale Subcortical Brain Data](https://arxiv.org/pdf/1810.08553) [J]. arXiv preprint arXiv:1810.08553.
- Dianbo Liu, Timothy Miller, Raheel Sayeed, Kenneth Mandl .[FADL:Federated-Autonomous Deep Learning for Distributed Electronic Health Record](https://arxiv.org/pdf/1811.11400) [J]. arXiv preprint arXiv:1811.11400.
- Li Huang, Yifeng Yin, Zeng Fu, Shifa Zhang, Hao Deng, Dianbo Liu .[LoAdaBoost:Loss-Based AdaBoost Federated Machine Learning on medical Data](https://arxiv.org/pdf/1811.12629) [J]. arXiv preprint arXiv:1811.12629.
- Li Huang, Dianbo Liu .[Patient Clustering Improves Efficiency of Federated Machine Learning to predict mortality and hospital stay time using distributed Electronic Medical Records](https://arxiv.org/pdf/1903.09296) [J]. arXiv preprint arXiv:1903.09296.
- Yiqiang Chen, Jindong Wang, Chaohui Yu, Wen Gao, Xin Qin .[FedHealth: A Federated Transfer Learning Framework for Wearable Healthcare](https://arxiv.org/pdf/1907.09173) [J]. arXiv preprint arXiv:1907.09173.
- Dashan Gao, Ce Ju, Xiguang Wei, Yang Liu, Tianjian Chen, Qiang Yang .[HHHFL: Hierarchical Heterogeneous Horizontal Federated Learning for Electroencephalography](https://arxiv.org/pdf/1909.05784) [J]. arXiv preprint arXiv:1909.05784.
- Wenqi Li, Fausto Milletarì, Daguang Xu, Nicola Rieke, Jonny Hancox, Wentao Zhu, Maximilian Baust, Yan Cheng, Sébastien Ourselin, M. Jorge Cardoso, Andrew Feng .[Privacy-preserving Federated Brain Tumour Segmentation](https://arxiv.org/pdf/1910.00962) [J]. arXiv preprint arXiv:1910.00962.
- [good]Dianbo Liu, Timothy A Miller, Kenneth D. Mandl .[Confederated Machine Learning on Horizontally and Vertically Separated Medical Data for Large-Scale Health System Intelligence](https://arxiv.org/pdf/1910.02109) [J]. arXiv preprint arXiv:1910.02109.
- Rulin Shao, Hui Liu, Dianbo Liu .[Privacy Preserving Stochastic Channel-Based Federated Learning with Neural Network Pruning](https://arxiv.org/pdf/1910.02115) [J]. arXiv preprint arXiv:1910.02115.
- Olivia Choudhury, Aris Gkoulalas-Divanis, Theodoros Salonidis, Issa Sylla, Yoonyoung Park, Grace Hsu, Amar Das .[Differential Privacy-enabled Federated Learning for Sensitive Health Data](https://arxiv.org/pdf/1910.02578) [J]. arXiv preprint arXiv:1910.02578.
- Sabri Boughorbel, Fethi Jarray, Neethu Venugopal, Shabir Moosa, Haithum Elhadi, Michel Makhlouf .[Federated Uncertainty-Aware Learning for Distributed Hospital EHR Data](https://arxiv.org/pdf/1910.12191) [J]. arXiv preprint arXiv:1910.12191.
- Jonathan Passerat-Palmbach, Tyler Farnan, Robert Miller, Marielle S. Gross, Heather Leigh Flannery, Bill Gleim .[A blockchain-orchestrated Federated Learning architecture for healthcare consortia](https://arxiv.org/pdf/1910.12603) [J]. arXiv preprint arXiv:1910.12603.
- Stephen R. Pfohl, Andrew M. Dai, Katherine Heller .[Federated and Differentially Private Learning for Electronic Health Records](https://arxiv.org/pdf/1911.05861) [J]. arXiv preprint arXiv:1911.05861.
- Jie Xu, Fei Wang .[Federated Learning for Healthcare Informatics](https://arxiv.org/pdf/1911.06270) [J]. arXiv preprint arXiv:1911.06270.
- Sharma P, Shamout F E, Clifton D A. [Preserving patient privacy while training a predictive model of in-hospital mortality](https://arxiv.org/pdf/1912.00354)[J]. arXiv preprint arXiv:1912.00354, 2019.
- Songtao Lu, Yawen Zhang, Yunlong Wang, Christina Mack .[Learn Electronic Health Records by Fully Decentralized Federated Learning](https://arxiv.org/pdf/1912.01792) [J]. arXiv preprint arXiv:1912.01792.
- Xiaoxiao Li, Yufeng Gu, Nicha Dvornek, Lawrence Staib, Pamela Ventola, James S. Duncan .[Multi-site fMRI Analysis Using Privacy-preserving Federated Learning and Domain Adaptation: ABIDE Results](https://arxiv.org/pdf/2001.05647) [J]. arXiv preprint arXiv:2001.05647.
- R. Bey, R. Goussault, M. Benchoufi, R. Porcher .[Stratified cross-validation for unbiased and privacy-preserving federated learning](https://arxiv.org/pdf/2001.08090) [J]. arXiv preprint arXiv:2001.08090.
- Jianfei Cui, Dianbo Liu .[Federated machine learning with Anonymous Random Hybridization (FeARH) on medical records](https://arxiv.org/pdf/2001.09751) [J]. arXiv preprint arXiv:2001.09751.
- Olivia Choudhury, Aris Gkoulalas-Divanis, Theodoros Salonidis, Issa Sylla, Yoonyoung Park, Grace Hsu, Amar Das .[Anonymizing Data for Privacy-Preserving Federated Learning](https://arxiv.org/pdf/2002.09096) [J]. arXiv preprint arXiv:2002.09096.
- Nicola Rieke, Jonny Hancox, Wenqi Li, Fausto Milletari, Holger Roth, Shadi Albarqouni, Spyridon Bakas, Mathieu N. Galtier, Bennett Landman, Klaus Maier-Hein, Sebastien Ourselin, Micah Sheller, Ronald M. Summers, Andrew Trask, Daguang Xu, Maximilian Baust, M. Jorge Cardoso .[The Future of Digital Health with Federated Learning](https://arxiv.org/pdf/2003.08119) [J]. arXiv preprint arXiv:2003.08119.
- Ce Ju, Dashan Gao, Ravikiran Mane, Ben Tan, Yang Liu, Cuntai Guan .[Federated Transfer Learning for EEG Signal Classification](https://arxiv.org/pdf/2004.12321) [J]. arXiv preprint arXiv:2004.12321.
- Binhang Yuan, Song Ge, Wenhui Xing .[A Federated Learning Framework for Healthcare IoT devices](https://arxiv.org/pdf/2005.05083) [J]. arXiv preprint arXiv:2005.05083.
- Ce Ju, Ruihui Zhao, Jichao Sun, Xiguang Wei, Bo Zhao, Yang Liu, Hongshan Li, Tianjian Chen, Xinwei Zhang, Dashan Gao, Ben Tan, Han Yu, Yuan Jin .[Privacy-Preserving Technology to Help Millions of People: Federated Prediction Model for Stroke Prevention](https://arxiv.org/pdf/2006.10517) [J]. arXiv preprint arXiv:2006.10517.


## Transportation
- Sumudu Samarakoon, Mehdi Bennis, Walid Saad, Merouane Debbah .[Federated Learning for Ultra-Reliable Low-Latency V2V Communications](https://arxiv.org/pdf/1805.09253) [J]. arXiv preprint arXiv:1805.09253.
- Sumudu Samarakoon, Mehdi Bennis, Walid Saad, Merouane Debbah .[Distributed Federated Learning for Ultra-Reliable Low-Latency Vehicular  Communications](https://arxiv.org/pdf/1807.08127) [J]. arXiv preprint arXiv:1807.08127.
- Yuris Mulya Saputra, Dinh Thai Hoang, Diep N. Nguyen, Eryk Dutkiewicz, Markus Dominik Mueck, Srikathyayani Srikanteswara .[Energy Demand Prediction with Federated Learning for Electric Vehicle Networks](https://arxiv.org/pdf/1909.00907) [J]. arXiv preprint arXiv:1909.00907.
- Xinle Liang, Yang Liu, Tianjian Chen, Ming Liu, Qiang Yang .[Federated Transfer Reinforcement Learning for Autonomous Driving](https://arxiv.org/pdf/1910.06001) [J]. arXiv preprint arXiv:1910.06001.
- Ye D, Yu R, Pan M, et al. [Federated learning in vehicular edge computing: A selective model aggregation approach](https://ieeexplore.ieee.org/iel7/6287639/8948470/08964354.pdf)[J]. IEEE Access, 2020, 8: 23920-23935.
- Bekir Sait Ciftler, Abdullatif Albaseer, Noureddine Lasla, Mohamed Abdallah .[Federated Learning for Localization: A Privacy-Preserving Crowdsourcing Method](https://arxiv.org/pdf/2001.01911) [J]. arXiv preprint arXiv:2001.01911.
- Chaochao Chen, Jun Zhou, Bingzhe Wu, Wenjin Fang, Li Wang, Yuan Qi, Xiaolin Zheng. [Practical Privacy Preserving POI Recommendation](https://arxiv.org/pdf/2003.02834.pdf) [J]. arXiv preprint arXiv:2003.02834.
- Feng Yin, Zhidi Lin, Yue Xu, Qinglei Kong, Deshi Li, Sergios Theodoridis, Shuguang (Robert)Cui .[FedLoc: Federated Learning Framework for Cooperative Localization and Location Data Processing](https://arxiv.org/pdf/2003.03697) [J]. arXiv preprint arXiv:2003.03697.
- Hamid Shiri, Jihong Park, Mehdi Bennis .[Communication-Efficient Massive UAV Online Path Control: Federated Learning Meets Mean-Field Game Theory](https://arxiv.org/pdf/2003.04451) [J]. arXiv preprint arXiv:2003.04451.
- Yi Liu, James J.Q. Yu, Jiawen Kang, Dusit Niyato, Shuyu Zhang .[Privacy-preserving Traffic Flow Prediction: A Federated Learning Approach](https://arxiv.org/pdf/2003.08725) [J]. arXiv preprint arXiv:2003.08725.
- van Hulst J M, Zeni M, Kröller A, et al. [Beyond privacy regulations: an ethical approach to data usage in transportation](https://arxiv.org/pdf/2004.00491)[J]. arXiv preprint arXiv:2004.00491, 2020.
- Yuris Mulya Saputra, Diep N. Nguyen, Dinh Thai Hoang, Thang Xuan Vu, Eryk Dutkiewicz, Symeon Chatzinotas .[Federated Learning Meets Contract Theory: Energy-Efficient Framework for Electric Vehicle Networks](https://arxiv.org/pdf/2004.01828) [J]. arXiv preprint arXiv:2004.01828.
- Wei Yang Bryan Lim, Jianqiang Huang, Zehui Xiong, Jiawen Kang, Dusit Niyato, Xian-Sheng Hua, Cyril Leung, Chunyan Miao .[Towards Federated Learning in UAV-Enabled Internet of Vehicles: A Multi-Dimensional Contract-Matching Approach](https://arxiv.org/pdf/2004.03877) [J]. arXiv preprint arXiv:2004.03877.
- Ahmet M. Elbir, S. Coleri .[Federated Learning for Vehicular Networks](https://arxiv.org/pdf/2006.01412) [J]. arXiv preprint arXiv:2006.01412.


## Recommendation System
- Fei Chen, Zhenhua Dong, Zhenguo Li, Xiuqiang He .[Federated Meta-Learning for Recommendation](https://arxiv.org/pdf/1802.07876) [J]. arXiv preprint arXiv:1802.07876.
- Muhammad Ammad-ud-din, Elena Ivannikova, Suleiman A. Khan, Were Oyomno, Qiang Fu, Kuan Eeik Tan, Adrian Flanagan .[Federated Collaborative Filtering for Privacy-Preserving Personalized Recommendation System](https://arxiv.org/pdf/1901.09888) [J]. arXiv preprint arXiv:1901.09888.
- Di Chai, Leye Wang, Kai Chen, Qiang Yang .[Secure Federated Matrix Factorization](https://arxiv.org/pdf/1906.05108) [J]. arXiv preprint arXiv:1906.05108.
- Feng Liao, Hankz Hankui Zhuo, Xiaoling Huang, Yu Zhang .[Federated Hierarchical Hybrid Networks for Clickbait Detection](https://arxiv.org/pdf/1906.00638) [J]. arXiv preprint arXiv:1906.00638.
- Lin Y, Ren P, Chen Z, et al. [Meta Matrix Factorization for Federated Rating Predictions](https://arxiv.org/pdf/1910.10086.pdf)[C]//Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval. 2020: 981-990.
- Ribero M, Henderson J, Williamson S, et al. [Federating Recommendations Using Differentially Private Prototypes](https://arxiv.org/pdf/2003.00602)[J]. arXiv preprint arXiv:2003.00602, 2020.
- Tao Qi, Fangzhao Wu, Chuhan Wu, Yongfeng Huang, Xing Xie .[FedRec: Privacy-Preserving News Recommendation with Federated Learning](https://arxiv.org/pdf/2003.09592) [J]. arXiv preprint arXiv:2003.09592.
- Adrian Flanagan, Were Oyomno, Alexander Grigorievskiy, Kuan Eeik Tan, Suleiman A. Khan, Muhammad Ammad-Ud-Din .[Federated Multi-view Matrix Factorization for Personalized Recommendations](https://arxiv.org/pdf/2004.04256) [J]. arXiv preprint arXiv:2004.04256.
- Tan Li, Linqi Song, Christina Fragouli .[Federated Recommendation System via Differential Privacy](https://arxiv.org/pdf/2005.06670) [J]. arXiv preprint arXiv:2005.06670.
- Chen Chen, Jingfeng Zhang, Anthony K. H. Tung, Mohan Kankanhalli, Gang Chen .[Robust Federated Recommendation System](https://arxiv.org/pdf/2006.08259) [J]. arXiv preprint arXiv:2006.08259.


## Speech Recognition
- Andrew Hard, Kurt Partridge, Cameron Nguyen, Niranjan Subrahmanya, Aishanee Shah, Pai Zhu, Ignacio Lopez Moreno, Rajiv Mathews .[Training Keyword Spotting Models on Non-IID Data with Federated Learning](https://arxiv.org/pdf/2005.10406) [J]. arXiv preprint arXiv:2005.10406.


## Finance && Blockchain 
- Hyesung Kim, Jihong Park, Mehdi Bennis, Seong-Lyun Kim .[On-Device Federated Learning via Blockchain and its Latency Analysis](https://arxiv.org/pdf/1808.03949) [J]. arXiv preprint arXiv:1808.03949.
- Toyotaro Suzumura, Yi Zhou, Natahalie Baracaldo, Guangnan Ye, Keith Houck, Ryo Kawahara, Ali Anwar, Lucia Larise Stavarache, Yuji Watanabe, Pablo Loyola, Daniel Klyashtorny, Heiko Ludwig, Kumar Bhaskaran .[Towards Federated Graph Learning for Collaborative Financial Crimes Detection](https://arxiv.org/pdf/1909.12946) [J]. arXiv preprint arXiv:1909.12946.
- Yuan Liu, Shuai Sun, Zhengpeng Ai, Shuangfeng Zhang, Zelei Liu, Han Yu .[FedCoin: A Peer-to-Peer Payment System for Federated Learning](https://arxiv.org/pdf/2002.11711) [J]. arXiv preprint arXiv:2002.11711.


## Smart City &&  Other Applications
- Nguyen T D, Marchal S, Miettinen M, et al. [DIoT: A federated self-learning anomaly detection system for IoT](https://arxiv.org/pdf/1804.07474.pdf)[C]//2019 IEEE 39th International Conference on Distributed Computing Systems (ICDCS). IEEE, 2019: 756-767.
- Yujing Chen, Yue Ning, Zheng Chai, Huzefa Rangwala .[Federated Multi-task Hierarchical Attention Model for Sensor Analytics](https://arxiv.org/pdf/1905.05142) [J]. arXiv preprint arXiv:1905.05142.
- Tagliasacchi M, Gfeller B, Quitry F C, et al. [Self-supervised audio representation learning for mobile devices](https://arxiv.org/pdf/1907.10218.pdf)[J]. arXiv preprint arXiv:1905.11796, 2019.
- Feng J, Rong C, Sun F, et al. [Pmf: A privacy-preserving human mobility prediction framework via federated learning](https://vonfeng.github.io/files/UbiComp2020_PMF_Final.pdf)[J]. Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies, 2020, 4(1): 1-21.
- Abdullatif Albaseer, Bekir Sait Ciftler, Mohamed Abdallah, Ala Al-Fuqaha .[Exploiting Unlabeled Data in Smart Cities using Federated Learning](https://arxiv.org/pdf/2001.04030) [J]. arXiv preprint arXiv:2001.04030.
- Nicolas Aussel (INF, ACMES-SAMOVAR, IP Paris), Sophie Chabridon (IP Paris, INF, ACMES-SAMOVAR), Yohan Petetin (TIPIC-SAMOVAR, CITI, IP Paris) .[Combining Federated and Active Learning for Communication-efficient Distributed Failure Prediction in Aeronautics](https://arxiv.org/pdf/2001.07504) [J]. arXiv preprint arXiv:2001.07504.
- Zhuzhu Wang, Yilong Yang, Yang Liu, Ximeng Liu, Brij B. Gupta, Jianfeng Ma .[Cloud-based Federated Boosting for Mobile Crowdsensing](https://arxiv.org/pdf/2005.05304) [J]. arXiv preprint arXiv:2005.05304.


## Uncategorized
### 2002
- Vaidya J, Clifton C. [Privacy preserving association rule mining in vertically partitioned data](https://www.cs.purdue.edu/homes/clifton/DistDM/kdd02.pdf)[C]//Proceedings of the eighth ACM SIGKDD international conference on Knowledge discovery and data mining. 2002: 639-644.

### 2003
- [k-means]Vaidya J, Clifton C. [Privacy-preserving k-means clustering over vertically partitioned data](https://www.cerias.purdue.edu/tools_and_resources/bibtex_archive/archive/2003-47.pdf)[C]//Proceedings of the ninth ACM SIGKDD international conference on Knowledge discovery and data mining. 2003: 206-215.


### 2004 
- [Naive Bayes]Vaidya J, Clifton C. [Privacy preserving naive bayes classifier for vertically partitioned data](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.215.2035&rep=rep1&type=pdf)[C]//Proceedings of the 2004 SIAM international conference on data mining. Society for Industrial and Applied Mathematics, 2004: 522-526.

### 2015
- Shokri R, Shmatikov V. [Privacy-preserving deep learning](http://www.cs.cornell.edu/~shmat/shmat_ccs15.pdf)[C]//Proceedings of the 22nd ACM SIGSAC conference on computer and communications security. 2015: 1310-1321.

### 2016
- Abadi M, Chu A, Goodfellow I, et al. [Deep Learning with Differential Privacy](https://arxiv.org/pdf/1607.00133.pdf)[J]. arXiv preprint arXiv:1607.00133, 2016.
- Shokri R, Stronati M, Song C, et al. [Membership inference attacks against machine learning models](https://arxiv.org/pdf/1610.05820)[C]//2017 IEEE Symposium on Security and Privacy (SP). IEEE, 2017: 3-18.<br>[code:[csong27/membership-inference](https://github.com/csong27/membership-inference)]


### 2017
- Aono Y, Hayashi T, Wang L, et al. [Privacy-preserving deep learning via additively homomorphic encryption](https://eprint.iacr.org/2017/715.pdf)[J]. IEEE Transactions on Information Forensics and Security, 2017, 13(5): 1333-1345.
- [SGX]Bahmani R, Barbosa M, Brasser F, et al. [Secure multiparty computation from SGX](https://hal.archives-ouvertes.fr/hal-01898742/file/2016-1057.pdf)[C]//International Conference on Financial Cryptography and Data Security. Springer, Cham, 2017: 477-497.
- Mohassel P, Zhang Y. Secureml: [A system for scalable privacy-preserving machine learning](http://web.eecs.umich.edu/~mosharaf/Readings/SecureML.pdf)[C]//2017 IEEE Symposium on Security and Privacy (SP). IEEE, 2017: 19-38.
- [SGX]Md Nazmus Sadat, Md Momin Al Aziz, Noman Mohammed, Feng Chen, Shuang Wang, Xiaoqian Jiang .[SAFETY: Secure gwAs in Federated Environment Through a hYbrid solution  with Intel SGX and Homomorphic Encryption](https://arxiv.org/pdf/1703.02577) [J]. arXiv preprint arXiv:1703.02577.
- [KDD]Yejin Kim, Jimeng Sun, Hwanjo Yu, Xiaoqian Jiang .[Federated Tensor Factorization for Computational Phenotyping](https://arxiv.org/pdf/1704.03141) [J]. arXiv preprint arXiv:1704.03141.
- Xu Jiang, Nan Guan, Xiang Long, Wang Yi .[Semi-Federated Scheduling of Parallel Real-Time Tasks on Multiprocessors](https://arxiv.org/pdf/1705.03245) [J]. arXiv preprint arXiv:1705.03245.
- Gabriela Montoya, Hala Skaf-Molli, Katja Hose .[The Odyssey Approach for Optimizing Federated SPARQL Queries](https://arxiv.org/pdf/1705.06135) [J]. arXiv preprint arXiv:1705.06135.
- Benedicto B. Balilo Jr., Bobby D. Gerardo, Ruji P. Medina, Yungcheol Byun .[A Unique One-Time Password Table Sequence Pattern Authentication:  Application to Bicol University Union of Federated Faculty Association, Inc.  (BUUFFAI) eVoting System](https://arxiv.org/pdf/1708.00562) [J]. arXiv preprint arXiv:1708.00562.
- Chang K, Balachandar N, Lam C K, et al. [Institutionally Distributed Deep Learning Networks](https://arxiv.org/pdf/1709.05929)[J]. arXiv preprint arXiv:1709.05929, 2017.
- Niklas Ueter, Georg von der Brüggen, Jian-Jia Chen, Jing Li, Kunal Agrawal .[Reservation-Based Federated Scheduling for Parallel Real-Time Tasks](https://arxiv.org/pdf/1712.05040) [J]. arXiv preprint arXiv:1712.05040.
- Saurabh Kumar, Pararth Shah, Dilek Hakkani-Tur, Larry Heck .[Federated Control with Hierarchical Multi-Agent Deep Reinforcement  Learning](https://arxiv.org/pdf/1712.08266) [J]. arXiv preprint arXiv:1712.08266.


### 2018
- Yu Z, Hu J, Min G, et al. [Federated learning based proactive content caching in edge computing](https://ore.exeter.ac.uk/repository/bitstream/handle/10871/36227/Globecom_2018.pdf?sequence=1)[C]//2018 IEEE Global Communications Conference (GLOBECOM). IEEE, 2018: 1-6.
- Wang S, Tuor T, Salonidis T, et al. [When edge meets learning: Adaptive control for resource-constrained distributed machine learning](https://dsprdpub.cc.ic.ac.uk:8443/bitstream/10044/1/58765/2/Infocom_2018_distributed_ML.pdf)[C]//IEEE INFOCOM 2018-IEEE Conference on Computer Communications. IEEE, 2018: 63-71.
- Caldas S, Smith V, Talwalkar A. [Federated Kernelized Multi-Task Learning](https://systemsandml.org/Conferences/2019/doc/2018/30.pdf)[C]//SysML Conference 2018. 2018.
- Juvekar C, Vaikuntanathan V, Chandrakasan A. [{GAZELLE}: A low latency framework for secure neural network inference](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-juvekar.pdf)[C]//27th {USENIX} Security Symposium ({USENIX} Security 18). 2018: 1651-1669.
- [ICLR]Popov V, Kudinov M, Piontkovskaya I, et al. [Distributed fine-tuning of language models on private data](https://openreview.net/pdf?id=HkgNdt26Z)[C]//International Conference on Learning Representations. 2018.
-  .[Improving Privacy and Trust in Federated Identity Using SAML with Hash  Based Encryption Algorithm](https://arxiv.org/pdf/1803.02891) [J]. arXiv preprint arXiv:1803.02891.
- Milosz Pacholczyk, Krzysztof Rzadca
 .[Fair non-monetary scheduling in federated clouds](https://arxiv.org/pdf/1803.06178) [J]. arXiv preprint arXiv:1803.06178.
- Ronghua Xu, Yu Chen, Erik Blasch, Genshe Chen .[A Federated Capability-based Access Control Mechanism for Internet of  Things (IoTs)](https://arxiv.org/pdf/1805.00825) [J]. arXiv preprint arXiv:1805.00825.
- Orekondy T, Oh S J, Zhang Y, et al. [Gradient-Leaks: Understanding and Controlling Deanonymization in Federated Learning](https://arxiv.org/pdf/1805.05838)[J]. arXiv preprint arXiv:1805.05838, 2018.
- Loïc Baron (NPA, CNRS), Radomir Klacza (UPMC, NPA), Pauline Gaudet-Chardonnet (NPA, UPMC), Amira Bradai (UPMC, NPA), Ciro Scognamiglio (UPMC, NPA), Serge Fdida (NPA, LINCS) .[Next generation portal for federated testbeds MySlice v2: from prototype  to production](https://arxiv.org/pdf/1806.04467) [J]. arXiv preprint arXiv:1806.04467.
- Christopher Rackauckas, Qing Nie .[Confederated Modular Differential Equation APIs for Accelerated  Algorithm Development and Benchmarking](https://arxiv.org/pdf/1807.06430) [J]. arXiv preprint arXiv:1807.06430.
- Pablo Orviz Fernandez, Joao Pina, Alvaro Lopez Garcia, Isabel Campos Plasencia, Mario David, Jorge Gomes .[umd-verification: Automation of Software Validation for the EGI  federated e-Infrastructure](https://arxiv.org/pdf/1807.11318) [J]. arXiv preprint arXiv:1807.11318.
- Tobias Grubenmann, Abraham Bernstein, Dmitry Moor, Sven Seuken .[FedMark: A Marketplace for Federated Data on the Web](https://arxiv.org/pdf/1808.06298) [J]. arXiv preprint arXiv:1808.06298.
- Phong, Le Trieu, and Tran Thi Phuong. [Privacy-Preserving Deep Learning via Weight Transmission.](https://arxiv.org/abs/1809.03272) IEEE Transactions on Information Forensics and Security, vol. 14, no. 11, 2019, pp. 3003–3015.
- Dinesh Verma, Simon Julier, Greg Cirincione .[Federated AI for building AI Solutions across Multiple Agencies](https://arxiv.org/pdf/1809.10036) [J]. arXiv preprint arXiv:1809.10036.
- Qijun Zhu, Dandan Li, Dik Lun Lee .[C-DLSI: An Extended LSI Tailored for Federated Text Retrieval](https://arxiv.org/pdf/1810.02579) [J]. arXiv preprint arXiv:1810.02579.
- John Sherlock, Manoj Muniswamaiah, Lauren Clarke, Shawn Cicoria .[Review of Barriers for Federated Identity Adoption for Users and Organizations](https://arxiv.org/pdf/1810.06152) [J]. arXiv preprint arXiv:1810.06152.
- Thanos Yannakis, Pavlos Fafalios, Yannis Tzitzikas .[Heuristics-based Query Reordering for Federated Queries in SPARQL 1.1 and SPARQL-LD](https://arxiv.org/pdf/1810.09780) [J]. arXiv preprint arXiv:1810.09780.
- Álvaro García-Pérez, Alexey Gotsman .[Federated Byzantine Quorum Systems (Extended Version)](https://arxiv.org/pdf/1811.03642) [J]. arXiv preprint arXiv:1811.03642.
- Jan Trienes, Andrés Torres Cano, Djoerd Hiemstra .[Recommending Users: Whom to Follow on Federated Social Networks](https://arxiv.org/pdf/1811.09292) [J]. arXiv preprint arXiv:1811.09292.


### 2019
- Ren J, Wang H, Hou T, et al. [Federated learning-based computation offloading optimization in edge computing-supported internet of things](https://ieeexplore.ieee.org/iel7/6287639/8600701/08728285.pdf)[J]. IEEE Access, 2019, 7: 69194-69201.
- Díaz González F. [Federated Learning for Time Series Forecasting Using LSTM Networks: Exploiting Similarities Through Clustering](https://www.diva-portal.org/smash/get/diva2:1334598/FULLTEXT01.pdf)[J]. 2019.
- Yang W, Zhang Y, Ye K, et al. [FFD: A Federated Learning Based Method for Credit Card Fraud Detection](https://link.springer.com/chapter/10.1007/978-3-030-23551-2_2)[C]//International Conference on Big Data. Springer, Cham, 2019: 18-32.
- Yao X, Huang T, Wu C, et al. [Towards faster and better federated learning: A feature fusion approach](https://ieeexplore.ieee.org/abstract/document/8803001/)[C]//2019 IEEE International Conference on Image Processing (ICIP). IEEE, 2019: 175-179.
- Lu S, Yao Y, Shi W. [Collaborative learning on the edges: A case study on connected vehicles](https://www.usenix.org/system/files/hotedge19-paper-lu.pdf)[C]//2nd {USENIX} Workshop on Hot Topics in Edge Computing (HotEdge 19). 2019.
- Li Y. [Federated Learning for Time Series Forecasting Using Hybrid Model](https://www.diva-portal.org/smash/get/diva2:1334629/FULLTEXT01.pdf)[J]. 2019.
- Anusha Lalitha, Osman Cihan Kilinc, Tara Javidi, Farinaz Koushanfar .[Peer-to-peer Federated Learning on Graphs](https://arxiv.org/pdf/1901.11173) [J]. arXiv preprint arXiv:1901.11173.
- Łukasz Lachowski .[Complexity of the quorum intersection property of the Federated Byzantine Agreement System](https://arxiv.org/pdf/1902.06493) [J]. arXiv preprint arXiv:1902.06493.
- Wennan Zhu, Peter Kairouz, Haicheng Sun, Brendan McMahan, Wei Li .[Federated Heavy Hitters Discovery with Differential Privacy](https://arxiv.org/pdf/1902.08534) [J]. arXiv preprint arXiv:1902.08534.
- Oussama Habachi, Mohamed-Ali Adjif, Jean-Pierre Cances .[Fast Uplink Grant for NOMA: a Federated Learning based Approach](https://arxiv.org/pdf/1904.07975) [J]. arXiv preprint arXiv:1904.07975.
- Sunny Sanyal, Dapeng Wu, Boubakr Nour .[A Federated Filtering Framework for Internet of Medical Things](https://arxiv.org/pdf/1905.01138) [J]. arXiv preprint arXiv:1905.01138.
- Sumit Kumar Monga, Sheshadri K R, Yogesh Simmhan .[ElfStore: A Resilient Data Storage Service for Federated Edge and Fog Resources](https://arxiv.org/pdf/1905.08932) [J]. arXiv preprint arXiv:1905.08932.
- Thomas Hardjono .[A Federated Authorization Framework for Distributed Personal Data and Digital Identity](https://arxiv.org/pdf/1906.03552) [J]. arXiv preprint arXiv:1906.03552.
- Bob Iannucci, Aviral Shrivastava, Mohammad Khayatian .[TickTalk -- Timing API for Dynamically Federated Cyber-Physical Systems](https://arxiv.org/pdf/1906.03982) [J]. arXiv preprint arXiv:1906.03982.
- Nishant Saurabh, Dragi Kimovski, Simon Ostermann, Radu Prodan .[VM Image Repository and Distribution Models for Federated Clouds: State of the Art, Possible Directions and Open Issues](https://arxiv.org/pdf/1906.09182) [J]. arXiv preprint arXiv:1906.09182.
- Peter Mell, Jim Dray, James Shook .[Smart Contract Federated Identity Management without Third Party Authentication Services](https://arxiv.org/pdf/1906.11057) [J]. arXiv preprint arXiv:1906.11057.
- Maria L. B. A. Santos, Jessica C. Carneiro, Antonio M. R. Franco, Fernando A. Teixeira, Marco A. Henriques, Leonardo B. Oliveira .[A Federated Lightweight Authentication Protocol for the Internet of Things](https://arxiv.org/pdf/1907.05527) [J]. arXiv preprint arXiv:1907.05527.
- Andreas Grammenos, Rodrigo Mendoza-Smith, Cecilia Mascolo, Jon Crowcroft .[Federated PCA with Adaptive Rank Estimation](https://arxiv.org/pdf/1907.08059) [J]. arXiv preprint arXiv:1907.08059.
- Andrew Prout, William Arcand, David Bestor, Bill Bergeron, Chansup Byun, Vijay Gadepally, Michael Houle, Matthew Hubbell, Michael Jones, Anna Klein, Peter Michaleas, Lauren Milechin, Julie Mullen, Antonio Rosa, Siddharth Samsi, Charles Yee, Albert Reuther, Jeremy Kepner .[Securing HPC using Federated Authentication](https://arxiv.org/pdf/1908.07573) [J]. arXiv preprint arXiv:1908.07573.
- [ICLR]Li J, Khodak M, Caldas S, et al. [Differentially private meta-learning](https://arxiv.org/pdf/1909.05830)[J]. arXiv preprint arXiv:1909.05830, 2019.
- Sharma V, Vepakomma P, Swedish T, et al. [ExpertMatcher: Automating ML Model Selection for Users in Resource Constrained Countries](https://arxiv.org/pdf/1910.02312)[J]. arXiv preprint arXiv:1910.02312, 2019.
- Rulin Shao, Hongyu He, Hui Liu, Dianbo Liu .[Stochastic Channel-Based Federated Learning for Medical Data Privacy Preserving](https://arxiv.org/pdf/1910.11160) [J]. arXiv preprint arXiv:1910.11160.
- Shashi Raj Pandey, Nguyen H. Tran, Mehdi Bennis, Yan Kyaw Tun, Aunas Manzoor, Choong Seon Hong .[A Crowdsourcing Framework for On-Device Federated Learning](https://arxiv.org/pdf/1911.01046) [J]. arXiv preprint arXiv:1911.01046.
- Kun Ma, Antoine Bagula, Olasupo Ajayi .[Quality of Service (QoS) Modelling in Federated Cloud Computing](https://arxiv.org/pdf/1911.03051) [J]. arXiv preprint arXiv:1911.03051.
- Daniele D'Agostino, Luca Roverelli, Gabriele Zereik, Giuseppe La Rocca, Andrea De Luca, Ruben Salvaterra, Andrea Belfiore, Gianni Lisini, Giovanni Novara, Andrea Tiengo .[A science gateway for Exploring the X-ray Transient and variable sky using EGI Federated Cloud](https://arxiv.org/pdf/1911.06560) [J]. arXiv preprint arXiv:1911.06560.
- André Gaul, Ismail Khoffi, Jörg Liesen, Torsten Stüber .[Mathematical Analysis and Algorithms for Federated Byzantine Agreement Systems](https://arxiv.org/pdf/1912.01365) [J]. arXiv preprint arXiv:1912.01365.
- Xidi Qu, Shengling Wang, Qin Hu, Xiuzhen Cheng .[Proof of Federated Learning: A Novel Energy-recycling Consensus Algorithm](https://arxiv.org/pdf/1912.11745) [J]. arXiv preprint arXiv:1912.11745.
- Boyi Liu, Lujia Wang, Ming Liu, Cheng-Zhong Xu .[Federated Imitation Learning: A Novel Framework for Cloud Robotic Systems with Heterogeneous Sensor Data](https://arxiv.org/pdf/1912.12204) [J]. arXiv preprint arXiv:1912.12204.
- Zhaoxian Wu, Qing Ling, Tianyi Chen, Georgios B. Giannakis .[Federated Variance-Reduced Stochastic Gradient Descent with Robustness to Byzantine Attacks](https://arxiv.org/pdf/1912.12716) [J]. arXiv preprint arXiv:1912.12716.


### 2020
- Ye D, Yu R, Pan M, et al. [Federated learning in vehicular edge computing: A selective model aggregation approach](https://ieeexplore.ieee.org/iel7/6287639/8948470/08964354.pdf)[J]. IEEE Access, 2020, 8: 23920-23935.
- Wang X, Wang C, Li X, et al. [Federated deep reinforcement learning for internet of things with decentralized cooperative edge caching](http://www.mosaic-lab.org/uploads/papers/169d0b9c-0c8f-441f-9600-0c04c0afc8e1.pdf)[J]. IEEE Internet of Things Journal, 2020.
- Semwal T, Mulay A, Agrawal A M. [FedPerf: A Practitioners’ Guide to Performance of Federated Learning Algorithms](https://osf.io/q3vkt/download?format=pdf)[J]. 2020.
- [ICML][communication]Hamer, Jenny, et al. [FedBoost: A Communication-Efficient Algorithm for Federated Learning.](https://proceedings.icml.cc/static/paper_files/icml/2020/5967-Paper.pdf) ICML 2020: 37th International Conference on Machine Learning, vol. 1, 2020.<br>[video:[fedboost-a-communicationefficient-algorithm-for-federated-learning](https://slideslive.com/38928463/fedboost-a-communicationefficient-algorithm-for-federated-learning?ref=speaker-16993-latest)]
- [NIPS][non-I.I.D, personalization]Fallah A, Mokhtari A, Ozdaglar A. [Personalized Federated Learning with Theoretical Guarantees: A Model-Agnostic Meta-Learning Approach](http://proceedings.neurips.cc/paper/2020/file/24389bfe4fe2eba8bf9aa9203a44cdad-Paper.pdf)[J]. Advances in Neural Information Processing Systems, 2020, 33.
- [NIPS]Dubey A, Pentland A S. [Differentially-Private Federated Linear Bandits](http://proceedings.neurips.cc/paper/2020/file/4311359ed4969e8401880e3c1836fbe1-Paper.pdf)[J]. Advances in Neural Information Processing Systems, 2020, 33.<br> [code:[abhimanyudubey/private_federated_linear_bandits](https://github.com/abhimanyudubey/private_federated_linear_bandits)]
- [NIPS]Grammenos A, Mendoza Smith R, Crowcroft J, et al. [Federated Principal Component Analysis](https://papers.nips.cc/paper/2020/file/47a658229eb2368a99f1d032c8848542-Paper.pdf)[J]. Advances in Neural Information Processing Systems, 2020, 33.<br>[code:[andylamp/federated_pca](https://github.com/andylamp/federated_pca)]
- [NIPS][Privacy]Deng Y, Kamani M M, Mahdavi M. [Distributionally Robust Federated Averaging](https://proceedings.neurips.cc/paper/2020/file/ac450d10e166657ec8f93a1b65ca1b14-Paper.pdf)[J]. Advances in Neural Information Processing Systems, 2020, 33.<br>[code:[MLOPTPSU/FedTorch](https://github.com/MLOPTPSU/FedTorch)]
- [NIPS]He C, Annavaram M, Avestimehr S. [Group Knowledge Transfer: Federated Learning of Large CNNs at the Edge](http://proceedings.neurips.cc/paper/2020/file/a1d4c20b182ad7137ab3606f0e3fc8a4-Paper.pdf)[J]. Advances in Neural Information Processing Systems, 2020, 33.<br>[code:[FedML-AI/FedML/tree/master/fedml_experiments/distributed/fedgkt](https://github.com/FedML-AI/FedML/tree/master/fedml_experiments/distributed/fedgkt)]
- [NIPS]So J, Guler B, Avestimehr S. [A Scalable Approach for Privacy-Preserving Collaborative Machine Learning](http://proceedings.neurips.cc/paper/2020/file/5bf8aaef51c6e0d363cbe554acaf3f20-Paper.pdf)[J]. Advances in Neural Information Processing Systems, 2020, 33.
- [NIPS]Chen X, Chen T, Sun H, et al. [Distributed training with heterogeneous data: Bridging median-and mean-based algorithms](https://proceedings.neurips.cc/paper/2020/file/f629ed9325990b10543ab5946c1362fb-Paper.pdf)[J]. Advances in Neural Information Processing Systems, 2020, 33.
- [NIPS]Bistritz I, Mann A, Bambos N. [Distributed Distillation for On-Device Learning](https://proceedings.neurips.cc/paper/2020/file/fef6f971605336724b5e6c0c12dc2534-Paper.pdf)[J]. Advances in Neural Information Processing Systems, 2020, 33.
- [NIPS]Li J, Abbas W, Koutsoukos X. [Byzantine Resilient Distributed Multi-Task Learning](http://proceedings.neurips.cc/paper/2020/file/d37eb50d868361ea729bb4147eb3c1d8-Paper.pdf)[J]. Advances in Neural Information Processing Systems, 2020, 33.
- [NIPS]Ghosh A, Maity R K, Mazumdar A. [Distributed Newton Can Communicate Less and Resist Byzantine Workers](https://proceedings.neurips.cc/paper/2020/file/d17e6bcbcef8de3f7a00195cfa5706f1-Paper.pdf)[J]. Advances in Neural Information Processing Systems, 2020, 33.
- [NIPS]Sohn J, Han D J, Choi B, et al. [Election coding for distributed learning: Protecting SignSGD against Byzantine attacks](http://proceedings.neurips.cc/paper/2020/file/a7f0d2b95c60161b3f3c82f764b1d1c9-Paper.pdf)[J]. Advances in Neural Information Processing Systems, 2020, 33.
- Guo C, Hannun A, Knott B, et al. [Secure multiparty computations in floating-point arithmetic](https://arxiv.org/pdf/2001.03192.pdf)[J]. arXiv preprint arXiv:2001.03192, 2020.
- Kemchi Sofiane, Abdelhafid Zitouni (LIRE), Mahieddine Djoudi (TECHNÉ - EA 6316) .[Self Organization Agent Oriented Dynamic Resource Allocation on Open Federated Clouds Environment](https://arxiv.org/pdf/2001.07496) [J]. arXiv preprint arXiv:2001.07496.
- Tien-Dung Cao, Tram Truong-Huu, Hien Tran, Khanh Tran .[A Federated Learning Framework for Privacy-preserving and Parallel Training](https://arxiv.org/pdf/2001.09782) [J]. arXiv preprint arXiv:2001.09782.
- Huawei Huang, Kangying Lin, Song Guo, Pan Zhou, Zibin Zheng .[Prophet: Proactive Candidate-Selection for Federated Learning by Predicting the Qualities of Training and Reporting Phases](https://arxiv.org/pdf/2002.00577) [J]. arXiv preprint arXiv:2002.00577.
- Madhusanka Manimel Wadu, Sumudu Samarakoon, Mehdi Bennis .[Federated Learning under Channel Uncertainty: Joint Client Scheduling and Resource Allocation](https://arxiv.org/pdf/2002.00802) [J]. arXiv preprint arXiv:2002.00802.
- Yingyu Li, Anqi Huang, Yong Xiao, Xiaohu Ge, Sumei Sun, Han-Chieh Chao .[Federated Orchestration for Network Slicing of Bandwidth and Computational Resource](https://arxiv.org/pdf/2002.02451) [J]. arXiv preprint arXiv:2002.02451.
- Martin Florian, Sebastian Henningsen, Björn Scheuermann .[The Sum of Its Parts: Analysis of Federated Byzantine Agreement Systems](https://arxiv.org/pdf/2002.08101) [J]. arXiv preprint arXiv:2002.08101.
- Philipp D. Rohde, Maria-Esther Vidal .[Optimizing Federated Queries Based on the Physical Design of a Data Lake](https://arxiv.org/pdf/2002.08102) [J]. arXiv preprint arXiv:2002.08102.
- Corey Tessler, Venkata P. Modekurthy, Nathan Fisher, Abusayeed Saifullah .[Bringing Inter-Thread Cache Benefits to Federated Scheduling -- Extended Results & Technical Report](https://arxiv.org/pdf/2002.12516) [J]. arXiv preprint arXiv:2002.12516.
- Yansong Gao, Minki Kim, Sharif Abuadbba, Yeonjae Kim, Chandra Thapa, Kyuyeon Kim, Seyit A. Camtepe, Hyoungshick Kim, Surya Nepal .[End-to-End Evaluation of Federated Learning and Split Learning for Internet of Things](https://arxiv.org/pdf/2003.13376) [J]. arXiv preprint arXiv:2003.13376.
- Rui Hu, Yanmin Gong, Yuanxiong Guo .[CPFed: Communication-Efficient and Privacy-Preserving Federated Learning](https://arxiv.org/pdf/2003.13761) [J]. arXiv preprint arXiv:2003.13761.
- Stefan Vlaski, Ali H. Sayed .[Second-Order Guarantees in Centralized, Federated and Decentralized Nonconvex Optimization](https://arxiv.org/pdf/2003.14366) [J]. arXiv preprint arXiv:2003.14366.
- Dale Stansberry, Suhas Somnath, Jessica Breet, Gregory Shutt, Mallikarjun Shankar .[DataFed: Towards Reproducible Research via Federated Data Management](https://arxiv.org/pdf/2004.03710) [J]. arXiv preprint arXiv:2004.03710.
- Ryan Chard, Yadu Babuji, Zhuozhao Li, Tyler Skluzacek, Anna Woodard, Ben Blaiszik, Ian Foster, Kyle Chard .[funcX: A Federated Function Serving Fabric for Science](https://arxiv.org/pdf/2005.04215) [J]. arXiv preprint arXiv:2005.04215.
- Utkarsh Chandra Srivastava, Dhruv Upadhyay, Vinayak Sharma .[Intracranial Hemorrhage Detection Using Neural Network Based Methods With Federated Learning](https://arxiv.org/pdf/2005.08644) [J]. arXiv preprint arXiv:2005.08644.
- GeunHyeong Lee, Soo-Yong Shin .[Reliability and Performance Assessment of Federated Learning on Clinical Benchmark Data](https://arxiv.org/pdf/2005.11756) [J]. arXiv preprint arXiv:2005.11756.
- Hans Albert Lianto, Yang Zhao, Jun Zhao .[Responsive Web User Interface to Recover Training Data from User Gradients in Federated Learning](https://arxiv.org/pdf/2006.04695) [J]. arXiv preprint arXiv:2006.04695.
- [NIPS]Woodworth B, Patel K K, Srebro N. [Minibatch vs Local SGD for Heterogeneous Distributed Learning](https://arxiv.org/pdf/2006.04735)[J]. arXiv preprint arXiv:2006.04735, 2020.
- Zhize Li, Peter Richtárik .[A Unified Analysis of Stochastic Gradient Methods for Nonconvex Federated Optimization](https://arxiv.org/pdf/2006.07013) [J]. arXiv preprint arXiv:2006.07013.
- Mohammad Rasouli, Tao Sun, Ram Rajagopal .[FedGAN: Federated Generative Adversarial Networks for Distributed Data](https://arxiv.org/pdf/2006.07228) [J]. arXiv preprint arXiv:2006.07228.
- Yann Fraboni, Richard Vidal, Marco Lorenzi .[Free-rider Attacks on Model Aggregation in Federated Learning](https://arxiv.org/pdf/2006.11901) [J]. arXiv preprint arXiv:2006.11901.
- Anis Elgabli, Jihong Park, Chaouki Ben Issaid, Mehdi Bennis .[Harnessing Wireless Channels for Scalable and Privacy-Preserving Federated Learning](https://arxiv.org/pdf/2007.01790) [J]. arXiv preprint arXiv:2007.01790.
- Wenchao Xia, Tony Q. S. Quek, Kun Guo, Wanli Wen, Howard H. Yang, Hongbo Zhu .[Multi-Armed Bandit Based Client Scheduling for Federated Learning](https://arxiv.org/pdf/2007.02315) [J]. arXiv preprint arXiv:2007.02315.
- Saurav Prakash, Sagar Dhakal, Mustafa Akdeniz, A. Salman Avestimehr, Nageen Himayat .[Coded Computing for Federated Learning at the Edge](https://arxiv.org/pdf/2007.03273) [J]. arXiv preprint arXiv:2007.03273.
- Zhaohui Yang, Mingzhe Chen, Walid Saad, Choong Seon Hong, Mohammad Shikh-Bahaei, H. Vincent Poor, Shuguang Cui .[Delay Minimization for Federated Learning Over Wireless Communication Networks](https://arxiv.org/pdf/2007.03462) [J]. arXiv preprint arXiv:2007.03462.
- Kun Li, Fanglan Zheng, Jiang Tian, Xiaojia Xiang .[A Federated F-score Based Ensemble Model for Automatic Rule Extraction](https://arxiv.org/pdf/2007.03533) [J]. arXiv preprint arXiv:2007.03533.
- Mustafa Safa Ozdayi, Murat Kantarcioglu, Yulia R. Gel .[Defending Against Backdoors in Federated Learning with Robust Learning Rate](https://arxiv.org/pdf/2007.03767) [J]. arXiv preprint arXiv:2007.03767.
- Yutao Huang, Lingyang Chu, Zirui Zhou, Lanjun Wang, Jiangchuan Liu, Jian Pei, Yong Zhang .[Personalized Federated Learning: An Attentive Collaboration Approach](https://arxiv.org/pdf/2007.03797) [J]. arXiv preprint arXiv:2007.03797.
- Vaikkunth Mugunthan, Ravi Rahman, Lalana Kagal .[BlockFLow: An Accountable and Privacy-Preserving Solution for Federated Learning](https://arxiv.org/pdf/2007.03856) [J]. arXiv preprint arXiv:2007.03856.
- Hossein Hosseini, Sungrack Yun, Hyunsin Park, Christos Louizos, Joseph Soriaga, Max Welling .[Federated Learning of User Authentication Models](https://arxiv.org/pdf/2007.04618) [J]. arXiv preprint arXiv:2007.04618.
- [NIPS]Hongyi Wang, Kartik Sreenivasan, Shashank Rajput, Harit Vishwakarma, Saurabh Agarwal, Jy-yong Sohn, Kangwook Lee, Dimitris Papailiopoulos .[Attack of the Tails: Yes, You Really Can Backdoor Federated Learning](https://arxiv.org/pdf/2007.05084) [J]. arXiv preprint arXiv:2007.05084.
- Mikko A. Heikkilä, Antti Koskela, Kana Shimizu, Samuel Kaski, Antti Honkela .[Differentially private cross-silo federated learning](https://arxiv.org/pdf/2007.05553) [J]. arXiv preprint arXiv:2007.05553.
- Boyi Liu, Bingjie Yan, Yize Zhou, Yifan Yang, Yixian Zhang .[Experiments of Federated Learning for COVID-19 Chest X-ray Images](https://arxiv.org/pdf/2007.05592) [J]. arXiv preprint arXiv:2007.05592.
- Zhaonan Qu, Kaixiang Lin, Jayant Kalagnanam, Zhaojian Li, Jiayu Zhou, Zhengyuan Zhou .[Federated Learning's Blessing: FedAvg has Linear Speedup](https://arxiv.org/pdf/2007.05690) [J]. arXiv preprint arXiv:2007.05690.
- Balázs Pejó .[The Good, The Bad, and The Ugly: Quality Inference in Federated Learning](https://arxiv.org/pdf/2007.06236) [J]. arXiv preprint arXiv:2007.06236.
- Jer Shyuan Ng, Wei Yang Bryan Lim, Hong-Ning Dai, Zehui Xiong, Jianqiang Huang, Dusit Niyato, Xian-Sheng Hua, Cyril Leung, Chunyan Miao .[Joint Auction-Coalition Formation Framework for Communication-Efficient Federated Learning in UAV-Enabled Internet of Vehicles](https://arxiv.org/pdf/2007.06378) [J]. arXiv preprint arXiv:2007.06378.
- Rajesh Kumar, Abdullah Aman Khan, Sinmin Zhang, WenYong Wang, Yousif Abuidris, Waqas Amin, Jay Kumar .[Blockchain-Federated-Learning and Deep Learning Models for COVID-19 detection using CT Imaging](https://arxiv.org/pdf/2007.06537) [J]. arXiv preprint arXiv:2007.06537.
- Qunsong Zeng, Yuqing Du, Kaibin Huang, Kin K. Leung .[Energy-Efficient Resource Management for Federated Edge Learning with CPU-GPU Heterogeneous Computing](https://arxiv.org/pdf/2007.07122) [J]. arXiv preprint arXiv:2007.07122.
- Wenqi Shi, Sheng Zhou, Zhisheng Niu, Miao Jiang, Lu Geng .[Joint Device Scheduling and Resource Allocation for Latency Constrained Wireless Federated Learning](https://arxiv.org/pdf/2007.07174) [J]. arXiv preprint arXiv:2007.07174.
- Hanchi Ren, Jingjing Deng, Xianghua Xie .[Privacy Preserving Text Recognition with Gradient-Boosting for Federated Learning](https://arxiv.org/pdf/2007.07296) [J]. arXiv preprint arXiv:2007.07296.
- [ICML][communication]Daniel Rothchild, Ashwinee Panda, Enayat Ullah, Nikita Ivkin, Ion Stoica, Vladimir Braverman, Joseph Gonzalez, Raman Arora .[FetchSGD: Communication-Efficient Federated Learning with Sketching](https://arxiv.org/pdf/2007.07682) [J]. arXiv preprint arXiv:2007.07682.<br>[code:[kiddyboots216/CommEfficient](https://github.com/kiddyboots216/CommEfficient); video:[fetchsgd-communicationefficient-federated-learning-with-sketching](https://slideslive.com/38928454/fetchsgd-communicationefficient-federated-learning-with-sketching)]
- Shashank Jere, Qiang Fan, Bodong Shang, Lianjun Li, Lingjia Liu .[Federated Learning in Mobile Edge Computing: An Edge-Learning Perspective for Beyond 5G](https://arxiv.org/pdf/2007.08030) [J]. arXiv preprint arXiv:2007.08030.
- Rafa Gâlvez, Veelasha Moonsamy, Claudia Diaz .[Less is More: A privacy-respecting Android malware classifier using Federated Learning](https://arxiv.org/pdf/2007.08319) [J]. arXiv preprint arXiv:2007.08319.
- Vale Tolpegin, Stacey Truex, Mehmet Emre Gursoy, Ling Liu .[Data Poisoning Attacks Against Federated Learning Systems](https://arxiv.org/pdf/2007.08432) [J]. arXiv preprint arXiv:2007.08432.
- Vito Walter Anelli, Yashar Deldjoo, Tommaso Di Noia, Antonio Ferrara .[Prioritized Multi-Criteria Federated Learning](https://arxiv.org/pdf/2007.08893) [J]. arXiv preprint arXiv:2007.08893.
- Marten van Dijk, Nhuong V. Nguyen, Toan N. Nguyen, Lam M. Nguyen, Quoc Tran-Dinh, Phuong Ha Nguyen .[Asynchronous Federated Learning with Reduced Number of Rounds and with Differential Privacy from Less Aggregated Gaussian Noise](https://arxiv.org/pdf/2007.09208) [J]. arXiv preprint arXiv:2007.09208.
- Jed Mills, Jia Hu, Geyong Min .[User-Oriented Multi-Task Federated Deep Learning for Mobile Edge Computing](https://arxiv.org/pdf/2007.09236) [J]. arXiv preprint arXiv:2007.09236.
- Seyyedali Hosseinalipour, Sheikh Shams Azam, Christopher G. Brinton, Nicolo Michelusi, Vaneet Aggarwal, David J. Love, Huaiyu Dai .[Multi-Stage Hybrid Federated Learning over Large-Scale Wireless Fog Networks](https://arxiv.org/pdf/2007.09511) [J]. arXiv preprint arXiv:2007.09511.
- Yi Liu, Sahil Garg, Jiangtian Nie, Yang Zhang, Zehui Xiong, Jiawen Kang, M. Shamim Hossain .[Deep Anomaly Detection for Time-series Data in Industrial IoT: A Communication-Efficient On-device Federated Learning Approach](https://arxiv.org/pdf/2007.09712) [J]. arXiv preprint arXiv:2007.09712.
- Zhaoxiong Yang, Shuihai Hu, Kai Chen .[FPGA-Based Hardware Accelerator of Homomorphic Encryption for Efficient Federated Learning](https://arxiv.org/pdf/2007.10560) [J]. arXiv preprint arXiv:2007.10560.
- Yang Liu, Jiaheng Wei .[Incentives for Federated Learning: a Hypothesis Elicitation Approach](https://arxiv.org/pdf/2007.10596) [J]. arXiv preprint arXiv:2007.10596.
- Heiko Ludwig, Nathalie Baracaldo, Gegi Thomas, Yi Zhou, Ali Anwar, Shashank Rajamoni, Yuya Ong, Jayaram Radhakrishnan, Ashish Verma, Mathieu Sinn, Mark Purcell, Ambrish Rawat, Tran Minh, Naoise Holohan, Supriyo Chakraborty, Shalisha Whitherspoon, Dean Steuer, Laura Wynter, Hifaz Hassan, Sean Laguna, Mikhail Yurochkin, Mayank Agarwal, Ebube Chuba, Annie Abay .[IBM Federated Learning: an Enterprise Framework White Paper V0.1](https://arxiv.org/pdf/2007.10987) [J]. arXiv preprint arXiv:2007.10987.
- Jinhyun So, Basak Guler, A. Salman Avestimehr .[Byzantine-Resilient Secure Federated Learning](https://arxiv.org/pdf/2007.11115) [J]. arXiv preprint arXiv:2007.11115.
- Sin Kit Lo, Qinghua Lu, Chen Wang, Hye-Young Paik, Liming Zhu .[A Systematic Literature Review on Federated Machine Learning: From A Software Engineering Perspective](https://arxiv.org/pdf/2007.11354) [J]. arXiv preprint arXiv:2007.11354.
- Wenqing Zhang, Yang Qiu, Song Bai, Rui Zhang, Xiaolin Wei, Xiang Bai .[FedOCR: Communication-Efficient Federated Learning for Scene Text Recognition](https://arxiv.org/pdf/2007.11462) [J]. arXiv preprint arXiv:2007.11462.
- Yi Liu, Jiangtian Nie, Xuandi Li, Syed Hassan Ahmed, Wei Yang Bryan Lim, Chunyan Miao .[Federated Learning in the Sky: Aerial-Ground Air Quality Sensing Framework with UAV Swarms](https://arxiv.org/pdf/2007.12004) [J]. arXiv preprint arXiv:2007.12004.
- Chuhan Wu, Fangzhao Wu, Tao Di, Yongfeng Huang, Xing Xie .[FedCTR: Federated Native Ad CTR Prediction with Multi-Platform User Behavior Data](https://arxiv.org/pdf/2007.12135) [J]. arXiv preprint arXiv:2007.12135.
- Aaqib Saeed, Flora D. Salim, Tanir Ozcelebi, Johan Lukkien .[Federated Self-Supervised Learning of Multi-Sensor Representations for Embedded Intelligence](https://arxiv.org/pdf/2007.13018) [J]. arXiv preprint arXiv:2007.13018.
- Yuben Qu, Chao Dong, Jianchao Zheng, Qihui Wu, Yun Shen, Fan Wu, Alagan Anpalagan .[Empowering the Edge Intelligence by Air-Ground Integrated Federated Learning in 6G Networks](https://arxiv.org/pdf/2007.13054) [J]. arXiv preprint arXiv:2007.13054.
- Hung T. Nguyen, Vikash Sehwag, Seyyedali Hosseinalipour, Christopher G. Brinton, Mung Chiang, H. Vincent Poor .[Fast-Convergent Federated Learning](https://arxiv.org/pdf/2007.13137) [J]. arXiv preprint arXiv:2007.13137.
- Chandra Thapa, Jun Wen Tang, Sharif Abuadbba, Yansong Gao, Yifeng Zheng, Seyit A. Camtepe, Surya Nepal, Mahathir Almashor .[FedEmail: Performance Measurement of Privacy-friendly Phishing Detection Enabled by Federated Learning](https://arxiv.org/pdf/2007.13300) [J]. arXiv preprint arXiv:2007.13300.
- Anmin Fu, Xianglong Zhang, Naixue Xiong, Yansong Gao, Huaqun Wang .[VFL: A Verifiable Federated Learning with Privacy-Preserving for Big Data in Industrial IoT](https://arxiv.org/pdf/2007.13585) [J]. arXiv preprint arXiv:2007.13585.
- Yue Xiao, Yu Ye, Shaocheng Huang, Li Hao, Zheng Ma, Ming Xiao, Shahid Mumtaz .[Fully Decentralized Federated Learning Based Beamforming Design for UAV Communications](https://arxiv.org/pdf/2007.13614) [J]. arXiv preprint arXiv:2007.13614.
- Wentai Wu, Ligang He, Weiwei Lin, Rui Mao .[Accelerating Federated Learning over Reliability-Agnostic Clients in Mobile Edge Computing Systems](https://arxiv.org/pdf/2007.14374) [J]. arXiv preprint arXiv:2007.14374.
- Constance Beguier, Eric W. Tramel .[SAFER: Sparse Secure Aggregation for Federated Learning](https://arxiv.org/pdf/2007.14861) [J]. arXiv preprint arXiv:2007.14861.
- Ruichen Jiang, Sheng Zhou .[Cluster-Based Cooperative Digital Over-the-Air Aggregation for Wireless Federated Edge Learning](https://arxiv.org/pdf/2008.00994) [J]. arXiv preprint arXiv:2008.00994.
- Rui Hu, Yanmin Gong, Yuanxiong Guo .[Sparsified Privacy-Masking for Communication-Efficient and Privacy-Preserving Federated Learning](https://arxiv.org/pdf/2008.01558) [J]. arXiv preprint arXiv:2008.01558.
- Dimitrios Dimitriadis, Kenichi Kumatani, Robert Gmyr, Yashesh Gaur, Sefik Emre Eskimez .[Federated Transfer Learning with Dynamic Gradient Aggregation](https://arxiv.org/pdf/2008.02452) [J]. arXiv preprint arXiv:2008.02452.
- Huafei Zhu .[On the relationship between (secure) multi-party computation and (secure) federated learning](https://arxiv.org/pdf/2008.02609) [J]. arXiv preprint arXiv:2008.02609.
- Filip Granqvist, Matt Seigel, Rogier van Dalen, Áine Cahill, Stephen Shum, Matthias Paulik .[Improving on-device speaker verification using federated learning with privacy](https://arxiv.org/pdf/2008.02651) [J]. arXiv preprint arXiv:2008.02651.
- Ang Li, Jingwei Sun, Binghui Wang, Lin Duan, Sicheng Li, Yiran Chen, Hai Li .[LotteryFL: Personalized and Communication-Efficient Federated Learning with Lottery Ticket Hypothesis on Non-IID Datasets](https://arxiv.org/pdf/2008.03371) [J]. arXiv preprint arXiv:2008.03371.
- Sai Praneeth Karimireddy, Martin Jaggi, Satyen Kale, Mehryar Mohri, Sashank J. Reddi, Sebastian U. Stich, Ananda Theertha Suresh .[Mime: Mimicking Centralized Stochastic Algorithms in Federated Learning](https://arxiv.org/pdf/2008.03606) [J]. arXiv preprint arXiv:2008.03606.
- 【SplitNN】Iker Ceballos, Vivek Sharma, Eduardo Mugica, Abhishek Singh, Albert Roman, Praneeth Vepakomma, and Ramesh Raskar. [SplitNN-driven vertical partitioning](https://arxiv.org/pdf/2008.04137.pdf). arXiv preprint arXiv:2008.04137, 2018.
- Jack Goetz, Ambuj Tewari .[Federated Learning via Synthetic Data](https://arxiv.org/pdf/2008.04489) [J]. arXiv preprint arXiv:2008.04489.
- Kenta Nagura, Song Bian, Takashi Sato .[FedNNNN: Norm-Normalized Neural Network Aggregation for Fast and Accurate Federated Learning](https://arxiv.org/pdf/2008.04538) [J]. arXiv preprint arXiv:2008.04538.
- Shahar Azulay, Lior Raz, Amir Globerson, Tomer Koren, Yehuda Afek .[Holdout SGD: Byzantine Tolerant Federated Learning](https://arxiv.org/pdf/2008.04612) [J]. arXiv preprint arXiv:2008.04612.
- Jiawen Kang, Zehui Xiong, Chunxiao Jiang, Yi Liu, Song Guo, Yang Zhang, Dusit Niyato, Cyril Leung, Chunyan Miao .[Scalable and Communication-efficient Decentralized Federated Edge Learning with Multi-blockchain Framework](https://arxiv.org/pdf/2008.04743) [J]. arXiv preprint arXiv:2008.04743.
- Farzin Haddadpour, Belhal Karimi, Ping Li, Xiaoyun Li .[FedSKETCH: Communication-Efficient and Private Federated Learning via Sketching](https://arxiv.org/pdf/2008.04975) [J]. arXiv preprint arXiv:2008.04975.
- Dianbo Sui, Yubo Chen, Kang Liu, Jun Zhao .[Distantly Supervised Relation Extraction in Federated Settings](https://arxiv.org/pdf/2008.05049) [J]. arXiv preprint arXiv:2008.05049.
- Latif U. Khan, Walid Saad, Zhu Han, Choong Seon Hong .[Dispersed Federated Learning: Vision, Taxonomy, and Future Directions](https://arxiv.org/pdf/2008.05189) [J]. arXiv preprint arXiv:2008.05189.
- Weituo Hao, Nikhil Mehta, Kevin J Liang, Pengyu Cheng, Mostafa El-Khamy, Lawrence Carin .[WAFFLe: Weight Anonymized Factorization for Federated Learning](https://arxiv.org/pdf/2008.05687) [J]. arXiv preprint arXiv:2008.05687.
- Yuncheng Wu, Shaofeng Cai, Xiaokui Xiao, Gang Chen, Beng Chin Ooi .[Privacy Preserving Vertical Federated Learning for Tree-based Models](https://arxiv.org/pdf/2008.06170) [J]. arXiv preprint arXiv:2008.06170.
- Sohei Itahara, Takayuki Nishio, Yusuke Koda, Masahiro Morikura, Koji Yamamoto .[Distillation-Based Semi-Supervised Federated Learning for Communication-Efficient Collaborative Training with Non-IID Private Data](https://arxiv.org/pdf/2008.06180) [J]. arXiv preprint arXiv:2008.06180.
- Bin Gu, Zhiyuan Dang, Xiang Li, Heng Huang .[Federated Doubly Stochastic Kernel Learning for Vertically Partitioned Data](https://arxiv.org/pdf/2008.06197) [J]. arXiv preprint arXiv:2008.06197.
- Lixu Wang, Shichao Xu, Xiao Wang, Qi Zhu .[Towards Class Imbalance in Federated Learning](https://arxiv.org/pdf/2008.06217) [J]. arXiv preprint arXiv:2008.06217.
- Bin Gu, An Xu, Zhouyuan Huo, Cheng Deng, Heng Huang .[Privacy-Preserving Asynchronous Federated Learning Algorithms for Multi-Party Vertically Collaborative Learning](https://arxiv.org/pdf/2008.06233) [J]. arXiv preprint arXiv:2008.06233.
- Mingshu Cong, Han Yu, Xi Weng, Jiabao Qu, Yang Liu, Siu Ming Yiu .[A VCG-based Fair Incentive Mechanism for Federated Learning](https://arxiv.org/pdf/2008.06680) [J]. arXiv preprint arXiv:2008.06680.
- Fuxun Yu, Weishan Zhang, Zhuwei Qin, Zirui Xu, Di Wang, Chenchen Liu, Zhi Tian, Xiang Chen .[Heterogeneous Federated Learning](https://arxiv.org/pdf/2008.06767) [J]. arXiv preprint arXiv:2008.06767.
- Antonious M. Girgis, Deepesh Data, Suhas Diggavi, Peter Kairouz, Ananda Theertha Suresh .[Shuffled Model of Federated Learning: Privacy, Communication and Accuracy Trade-offs](https://arxiv.org/pdf/2008.07180) [J]. arXiv preprint arXiv:2008.07180.
- Vito Walter Anelli, Yashar Deldjoo, Tommaso Di Noia, Antonio Ferrara, Fedelucio Narducci .[How to Put Users in Control of their Data via Federated Pair-Wise Recommendation](https://arxiv.org/pdf/2008.07192) [J]. arXiv preprint arXiv:2008.07192.
- Yuan Liang, Yange Guo, Yanxia Gong, Chunjie Luo, Jianfeng Zhan, Yunyou Huang .[An Isolated Data Island Benchmark Suite for Federated Learning](https://arxiv.org/pdf/2008.07257) [J]. arXiv preprint arXiv:2008.07257.
- Buse Gul Atli, Yuxi Xia, Samuel Marchal, N. Asokan .[WAFFLE: Watermarking in Federated Learning](https://arxiv.org/pdf/2008.07298) [J]. arXiv preprint arXiv:2008.07298.
- 【SiloBN】Mathieu Andreux, Jean Ogier du Terrail, Constance Beguier, Eric W. Tramel .[Siloed Federated Learning for Multi-Centric Histopathology Datasets](https://arxiv.org/pdf/2008.07424) [J]. arXiv preprint arXiv:2008.07424.
- Minchul Kim, Jungwoo Lee .[Information-Theoretic Privacy in Federated Submodel learning](https://arxiv.org/pdf/2008.07656) [J]. arXiv preprint arXiv:2008.07656.
- [MICCAIW]Yousef Yeganeh, Azade Farshad, Nassir Navab, Shadi Albarqouni .[Inverse Distance Aggregation for Federated Learning with Non-IID Data](https://arxiv.org/pdf/2008.07665) [J]. arXiv preprint arXiv:2008.07665.
- Junjie Tan, Ying-Chang Liang, Nguyen Cong Luong, Dusit Niyato .[Toward Smart Security Enhancement of Federated Learning Networks](https://arxiv.org/pdf/2008.08330) [J]. arXiv preprint arXiv:2008.08330.
- Frank Po-Chen Lin, Christopher G. Brinton, Nicolò Michelusi .[Federated Learning with Communication Delay in Edge Networks](https://arxiv.org/pdf/2008.09323) [J]. arXiv preprint arXiv:2008.09323.
- Behzad Khamidehi, Elvino S. Sousa .[Federated Learning for Cellular-connected UAVs: Radio Mapping and Path Planning](https://arxiv.org/pdf/2008.10054) [J]. arXiv preprint arXiv:2008.10054.
- Mingkai Huang, Hao Li, Bing Bai, Chang Wang, Kun Bai, Fei Wang .[A Federated Multi-View Deep Learning Framework for Privacy-Preserving Recommendations](https://arxiv.org/pdf/2008.10808) [J]. arXiv preprint arXiv:2008.10808.
- Yan Kang, Yang Liu, Tianjian Chen .[FedMVT: Semi-supervised Vertical Federated Learning with MultiView Training](https://arxiv.org/pdf/2008.10838) [J]. arXiv preprint arXiv:2008.10838.
- Ahmet M. Elbir, Sinem Coleri .[Federated Learning for Channel Estimation in Conventional and IRS-Assisted Massive MIMO](https://arxiv.org/pdf/2008.10846) [J]. arXiv preprint arXiv:2008.10846.
- Mohammad Mohammadi Amiri, Deniz Gunduz, Sanjeev R. Kulkarni, H. Vincent Poor .[Convergence of Federated Learning over a Noisy Downlink](https://arxiv.org/pdf/2008.11141) [J]. arXiv preprint arXiv:2008.11141.
- Dimitris Stripelis, Jose Luis Ambite .[Accelerating Federated Learning in Heterogeneous Data and Computational Environments](https://arxiv.org/pdf/2008.11281) [J]. arXiv preprint arXiv:2008.11281.
- Zhengming Zhang, Zhewei Yao, Yaoqing Yang, Yujun Yan, Joseph E. Gonzalez, Michael W. Mahoney .[Benchmarking Semi-supervised Federated Learning](https://arxiv.org/pdf/2008.11364) [J]. arXiv preprint arXiv:2008.11364.
- Dongming Han, Wei Chen, Rusheng Pan, Yijing Liu, Jiehui Zhou, Ying Xu, Tianye Zhang, Changjie Fan, Jianrong Tao, Xiaolong (Luke)Zhang .[GraphFederator: Federated Visual Analysis for Multi-party Graphs](https://arxiv.org/pdf/2008.11989) [J]. arXiv preprint arXiv:2008.11989.
- Lingjuan Lyu, Xinyi Xu, Qian Wang .[Collaborative Fairness in Federated Learning](https://arxiv.org/pdf/2008.12161) [J]. arXiv preprint arXiv:2008.12161.
- Tejaswini Mallavarapu, Luke Cranfill, Junggab Son, Eun Hye Kim, Reza M. Parizi, John Morris .[A Federated Approach for Fine-Grained Classification of Fashion Apparel](https://arxiv.org/pdf/2008.12350) [J]. arXiv preprint arXiv:2008.12350.
- Seok-Ju Hahn, Junghye Lee .[GRAFFL: Gradient-free Federated Learning of a Bayesian Generative Model](https://arxiv.org/pdf/2008.12925) [J]. arXiv preprint arXiv:2008.12925.
- Afaf Taïk, Soumaya Cherkaoui .[Federated Edge Learning : Design Issues and Challenges](https://arxiv.org/pdf/2009.00081) [J]. arXiv preprint arXiv:2009.00081.
- Sinem Sav, Apostolos Pyrgelis, Juan R. Troncoso-Pastoriza, David Froelicher, Jean-Philippe Bossuat, Joao Sa Sousa, Jean-Pierre Hubaux .[POSEIDON: Privacy-Preserving Federated Neural Network Learning](https://arxiv.org/pdf/2009.00349) [J]. arXiv preprint arXiv:2009.00349.
- Daiqing Li, Amlan Kar, Nishant Ravikumar, Alejandro F Frangi, Sanja Fidler .[Fed-Sim: Federated Simulation for Medical Imaging](https://arxiv.org/pdf/2009.00668) [J]. arXiv preprint arXiv:2009.00668.
- Sheng Lin, Chenghong Wang, Hongjia Li, Jieren Deng, Yanzhi Wang, Caiwen Ding .[ESMFL: Efficient and Secure Models for Federated Learning](https://arxiv.org/pdf/2009.01867) [J]. arXiv preprint arXiv:2009.01867.
- Holger R. Roth, Ken Chang, Praveer Singh, Nir Neumark, Wenqi Li, Vikash Gupta, Sharut Gupta, Liangqiong Qu, Alvin Ihsani, Bernardo C. Bizzo, Yuhong Wen, Varun Buch, Meesam Shah, Felipe Kitamura, Matheus Mendonça, Vitor Lavor, Ahmed Harouni, Colin Compas, Jesse Tetreault, Prerna Dogra, Yan Cheng, Selnur Erdal, Richard White, Behrooz Hashemian, Thomas Schultz, Miao Zhang, Adam McCarthy, B. Min Yun, Elshaimaa Sharaf, Katharina V. Hoebel, Jay B. Patel, Bryan Chen, Sean Ko, Evan Leibovitz, Etta D. Pisano, Laura Coombs, Daguang Xu, Keith J. Dreyer, Ittai Dayan, Ram C. Naidu, Mona Flores, Daniel Rubin, Jayashree Kalpathy-Cramer .[Federated Learning for Breast Density Classification: A Real-World Implementation](https://arxiv.org/pdf/2009.01871) [J]. arXiv preprint arXiv:2009.01871.
- Hong-You Chen, Wei-Lun Chao .[FedDistill: Making Bayesian Model Ensemble Applicable to Federated Learning](https://arxiv.org/pdf/2009.01974) [J]. arXiv preprint arXiv:2009.01974.
- Tung T. Vu, Duy T. Ngo, Hien Quoc Ngo, Minh N. Dao, Nguyen H. Tran, Richard H. Middleton .[User Selection Approaches to Mitigate the Straggler Effect for Federated Learning on Cell-Free Massive MIMO Networks](https://arxiv.org/pdf/2009.02031) [J]. arXiv preprint arXiv:2009.02031.
- Pei Fang, Zhendong Cai, Hui Chen, QingJiang Shi .[FLFE: A Communication-Efficient and Privacy-Preserving Federated Feature Engineering Framework](https://arxiv.org/pdf/2009.02557) [J]. arXiv preprint arXiv:2009.02557.
- Basheer Qolomany, Kashif Ahmad, Ala Al-Fuqaha, Junaid Qadir .[Particle Swarm Optimized Federated Learning For Industrial IoT and Smart City Services](https://arxiv.org/pdf/2009.02560) [J]. arXiv preprint arXiv:2009.02560.
- Weishan Zhang, Qinghua Lu, Qiuyu Yu, Zhaotong Li, Yue Liu, Sin Kit Lo, Shiping Chen, Xiwei Xu, Liming Zhu .[Blockchain-based Federated Learning for Failure Detection in Industrial IoT](https://arxiv.org/pdf/2009.02643) [J]. arXiv preprint arXiv:2009.02643.
- Chang Wang, Jian Liang, Mingkai Huang, Bing Bai, Kun Bai, Hao Li .[Hybrid Differentially Private Federated Learning on Vertically Partitioned Data](https://arxiv.org/pdf/2009.02763) [J]. arXiv preprint arXiv:2009.02763.
- Boyi Liu, Bingjie Yan, Yize Zhou, Jun Wang, Li Liu, Yuhan Zhang, Xiaolan Nie .[A Real-time Contribution Measurement Method for Participants in Federated Learning](https://arxiv.org/pdf/2009.03510) [J]. arXiv preprint arXiv:2009.03510.
- Mohammad Naseri, Jamie Hayes, Emiliano De Cristofaro .[Toward Robustness and Privacy in Federated Learning: Experimenting with Local and Central Differential Privacy](https://arxiv.org/pdf/2009.03561) [J]. arXiv preprint arXiv:2009.03561.
- Maria Peifer, Alejandro Ribeiro .[Federated Classification using Parsimonious Functions in Reproducing Kernel Hilbert Spaces](https://arxiv.org/pdf/2009.03768) [J]. arXiv preprint arXiv:2009.03768.
- Lichao Sun, Lingjuan Lyu .[Federated Model Distillation with Noise-Free Differential Privacy](https://arxiv.org/pdf/2009.05537) [J]. arXiv preprint arXiv:2009.05537.
- Rui Hu, Yanmin Gong .[Trading Data For Learning: Incentive Mechanism For On-Device Federated Learning](https://arxiv.org/pdf/2009.05604) [J]. arXiv preprint arXiv:2009.05604.
- Sudipta Paul, Poushali Sengupta, Subhankar Mishra .[FLaPS: Federated Learning and Privately Scaling](https://arxiv.org/pdf/2009.06005) [J]. arXiv preprint arXiv:2009.06005.
- Tianhao Wang, Johannes Rausch, Ce Zhang, Ruoxi Jia, Dawn Song .[A Principled Approach to Data Valuation for Federated Learning](https://arxiv.org/pdf/2009.06192) [J]. arXiv preprint arXiv:2009.06192.
- Fanglan Zheng, Erihe, Kun Li, Jiang Tian, Xiaojia Xiang .[A Vertical Federated Learning Method for Interpretable Scorecard and Its Application in Credit Scoring](https://arxiv.org/pdf/2009.06218) [J]. arXiv preprint arXiv:2009.06218.
- Pengqian Yu, Laura Wynter, Shiau Hong Lim .[Fed+: A Family of Fusion Algorithms for Federated Learning](https://arxiv.org/pdf/2009.06303) [J]. arXiv preprint arXiv:2009.06303.
- Rahif Kassab, Osvaldo Simeone .[Federated Generalized Bayesian Learning via Distributed Stein Variational Gradient Descent](https://arxiv.org/pdf/2009.06419) [J]. arXiv preprint arXiv:2009.06419.
- Qianqian Tong, Guannan Liang, Jinbo Bi .[Effective Federated Adaptive Gradient Methods with Non-IID Decentralized Data](https://arxiv.org/pdf/2009.06557) [J]. arXiv preprint arXiv:2009.06557.
- Anxun He, Jianzong Wang, Zhangcheng Huang, Jing Xiao .[FedSmart: An Auto Updating Federated Learning Optimization Mechanism](https://arxiv.org/pdf/2009.07455) [J]. arXiv preprint arXiv:2009.07455.
- Yanlin Zhou, George Pu, Xiyao Ma, Xiaolin Li, Dapeng Wu .[Distilled One-Shot Federated Learning](https://arxiv.org/pdf/2009.07999) [J]. arXiv preprint arXiv:2009.07999.
- Ruixuan Liu, Yang Cao, Hong Chen, Ruoyang Guo, Masatoshi Yoshikawa .[FLAME: Differentially Private Federated Learning in the Shuffle Model](https://arxiv.org/pdf/2009.08063) [J]. arXiv preprint arXiv:2009.08063.
- Jie Peng, Zhaoxian Wu, Qing Ling .[Byzantine-Robust Variance-Reduced Federated Learning over Distributed Non-i.i.d. Data](https://arxiv.org/pdf/2009.08161) [J]. arXiv preprint arXiv:2009.08161.
- Matei Grama, Maria Musat, Luis Muñoz-González, Jonathan Passerat-Palmbach, Daniel Rueckert, Amir Alansary .[Robust Aggregation for Adaptive Privacy Preserving Federated Learning in Healthcare](https://arxiv.org/pdf/2009.08294) [J]. arXiv preprint arXiv:2009.08294.
- Zhengjie Yang, Wei Bao, Dong Yuan, Nguyen H. Tran, Albert Y. Zomaya .[Federated Learning with Nesterov Accelerated Gradient Momentum Method](https://arxiv.org/pdf/2009.08716) [J]. arXiv preprint arXiv:2009.08716.
- Chuan Ma, Jun Li, Ming Ding, Long Shi, Taotao Wang, Zhu Han, H. Vincent Poor .[When Federated Learning Meets Blockchain: A New Distributed Learning Paradigm](https://arxiv.org/pdf/2009.09338) [J]. arXiv preprint arXiv:2009.09338.
- Takayuki Nishio, Ryoichi Shinkuma, Narayan B. Mandayam .[Estimation of Individual Device Contributions for Incentivizing Federated Learning](https://arxiv.org/pdf/2009.09371) [J]. arXiv preprint arXiv:2009.09371.
- Javad Mohammadi, Jesse Thornburg .[Connecting Distributed Pockets of EnergyFlexibility through Federated Computations:Limitations and Possibilities](https://arxiv.org/pdf/2009.10182) [J]. arXiv preprint arXiv:2009.10182.
- Ming Y. Lu, Dehan Kong, Jana Lipkova, Richard J. Chen, Rajendra Singh, Drew F. K. Williamson, Tiffany Y. Chen, Faisal Mahmood .[Federated Learning for Computational Pathology on Gigapixel Whole Slide Images](https://arxiv.org/pdf/2009.10190) [J]. arXiv preprint arXiv:2009.10190.
- Tra Huong Thi Le, Nguyen H. Tran, Yan Kyaw Tun, Minh N. H. Nguyen, Shashi Raj Pandey, Zhu Han, Choong Seon Hong .[An Incentive Mechanism for Federated Learning in Wireless Cellular network: An Auction Approach](https://arxiv.org/pdf/2009.10269) [J]. arXiv preprint arXiv:2009.10269.
- Weishan Zhang, Tao Zhou, Qinghua Lu, Xiao Wang, Chunsheng Zhu, Haoyun Sun, Zhipeng Wang, Sin Kit Lo, Fei-Yue Wang .[Dynamic Fusion based Federated Learning for COVID-19 Detection](https://arxiv.org/pdf/2009.10401) [J]. arXiv preprint arXiv:2009.10401.
- Shuai Yu, Xu Chen, Zhi Zhou, Xiaowen Gong, Di Wu .[When Deep Reinforcement Learning Meets Federated Learning: Intelligent Multi-Timescale Resource Management for Multi-access Edge Computing in 5G Ultra Dense Network](https://arxiv.org/pdf/2009.10601) [J]. arXiv preprint arXiv:2009.10601.
- Cheng Chen, Ziyi Chen, Yi Zhou, Bhavya Kailkhura .[FedCluster: Boosting the Convergence of Federated Learning via Cluster-Cycling](https://arxiv.org/pdf/2009.10748) [J]. arXiv preprint arXiv:2009.10748.
- Zhuoran Ma, Jianfeng Ma, Yinbin Miao, Ximeng Liu, Kim-Kwang Raymond Choo, Robert H. Deng .[Pocket Diagnosis: Secure Federated Learning against Poisoning Attack in the Cloud](https://arxiv.org/pdf/2009.10918) [J]. arXiv preprint arXiv:2009.10918.
- Swanand Kadhe, Nived Rajaraman, O. Ozan Koyluoglu, Kannan Ramchandran .[FastSecAgg: Scalable Secure Aggregation for Privacy-Preserving Federated Learning](https://arxiv.org/pdf/2009.11248) [J]. arXiv preprint arXiv:2009.11248.
- Tomer Sery, Nir Shlezinger, Kobi Cohen, Yonina C. Eldar .[Over-the-Air Federated Learning from Heterogeneous Data](https://arxiv.org/pdf/2009.12787) [J]. arXiv preprint arXiv:2009.12787.
- Shaoming Song, Yunfeng Shao, Jian Li .[Loosely Coupled Federated Learning Over Generative Models](https://arxiv.org/pdf/2009.12999) [J]. arXiv preprint arXiv:2009.12999.
- Latif U. Khan, Walid Saad, Zhu Han, Ekram Hossain, Choong Seon Hong .[Federated Learning for Internet of Things: Recent Advances, Taxonomy, and Open Challenges](https://arxiv.org/pdf/2009.13012) [J]. arXiv preprint arXiv:2009.13012.
- Naoya Yoshida, Takayuki Nishio, Masahiro Morikura, Koji Yamamoto .[MAB-based Client Selection for Federated Learning with Uncertain Resources in Mobile Networks](https://arxiv.org/pdf/2009.13879) [J]. arXiv preprint arXiv:2009.13879.
- Ahmed Roushdy Elkordy, A. Salman Avestimehr .[Secure Aggregation with Heterogeneous Quantization in Federated Learning](https://arxiv.org/pdf/2009.14388) [J]. arXiv preprint arXiv:2009.14388.
- Laércio Lima Pilla (ParSys - LRI) .[Optimal Task Assignment to Heterogeneous Federated Learning Devices](https://arxiv.org/pdf/2010.00239) [J]. arXiv preprint arXiv:2010.00239.
- Kate Donahue, Jon Kleinberg .[Model-sharing Games: Analyzing Federated Learning Under Voluntary Participation](https://arxiv.org/pdf/2010.00753) [J]. arXiv preprint arXiv:2010.00753.
- Qinbin Li, Bingsheng He, Dawn Song .[Model-Agnostic Round-Optimal Federated Learning via Knowledge Transfer](https://arxiv.org/pdf/2010.01017) [J]. arXiv preprint arXiv:2010.01017.
- Zhuqing Jia, Syed A. Jafar .[$X$-Secure $T$-Private Federated Submodel Learning](https://arxiv.org/pdf/2010.01059) [J]. arXiv preprint arXiv:2010.01059.
- Yae Jee Cho, Jianyu Wang, Gauri Joshi .[Client Selection in Federated Learning: Convergence Analysis and Power-of-Choice Selection Strategies](https://arxiv.org/pdf/2010.01243) [J]. arXiv preprint arXiv:2010.01243.
- Enmao Diao, Jie Ding, Vahid Tarokh .[HeteroFL: Computation and Communication Efficient Federated Learning for Heterogeneous Clients](https://arxiv.org/pdf/2010.01264) [J]. arXiv preprint arXiv:2010.01264.
- Edvin Listo Zec, Olof Mogren, John Martinsson, Leon René Sütfeld, Daniel Gillblad .[Federated learning using a mixture of experts](https://arxiv.org/pdf/2010.02056) [J]. arXiv preprint arXiv:2010.02056.
- [NIPS][non-I.I.D,personalization]Filip Hanzely, Slavomír Hanzely, Samuel Horváth, Peter Richtárik .[Lower Bounds and Optimal Algorithms for Personalized Federated Learning](https://arxiv.org/pdf/2010.02372) [J]. arXiv preprint arXiv:2010.02372.
- Alyazeed Albasyoni, Mher Safaryan, Laurent Condat, Peter Richtárik .[Optimal Gradient Compression for Distributed and Federated Learning](https://arxiv.org/pdf/2010.03246) [J]. arXiv preprint arXiv:2010.03246.
- Yuqing Zhu, Xiang Yu, Yi-Hsuan Tsai, Francesco Pittaluga, Masoud Faraki, Manmohan chandraker, Yu-Xiang Wang .[Voting-based Approaches For Differentially Private Federated Learning](https://arxiv.org/pdf/2010.04851) [J]. arXiv preprint arXiv:2010.04851.
- Wei Du, Depeng Xu, Xintao Wu, Hanghang Tong .[Fairness-aware Agnostic Federated Learning](https://arxiv.org/pdf/2010.05057) [J]. arXiv preprint arXiv:2010.05057.
- Maruan Al-Shedivat, Jennifer Gillenwater, Eric Xing, Afshin Rostamizadeh .[Federated Learning via Posterior Averaging: A New Perspective and Practical Algorithms](https://arxiv.org/pdf/2010.05273) [J]. arXiv preprint arXiv:2010.05273.
- David Byrd, Antigoni Polychroniadou .[Differentially Private Secure Multi-Party Computation for Federated Learning in Financial Applications](https://arxiv.org/pdf/2010.05867) [J]. arXiv preprint arXiv:2010.05867.
- Zheng Chai, Yujing Chen, Liang Zhao, Yue Cheng, Huzefa Rangwala .[FedAT: A Communication-Efficient Federated Learning Method with Asynchronous Tiers under Non-IID Data](https://arxiv.org/pdf/2010.05958) [J]. arXiv preprint arXiv:2010.05958.
- Fan Lai, Xiangfeng Zhu, Harsha V. Madhyastha, Mosharaf Chowdhury .[Oort: Informed Participant Selection for Scalable Federated Learning](https://arxiv.org/pdf/2010.06081) [J]. arXiv preprint arXiv:2010.06081.
- Anwaar Ulhaq, Oliver Burmeister .[COVID-19 Imaging Data Privacy by Federated Learning Design: A Theoretical Framework](https://arxiv.org/pdf/2010.06177) [J]. arXiv preprint arXiv:2010.06177.
- Xinchi Qiu, Titouan Parcolle, Daniel J. Beutel, Taner Topal, Akhil Mathur, Nicholas D. Lane .[A first look into the carbon footprint of federated learning](https://arxiv.org/pdf/2010.06537) [J]. arXiv preprint arXiv:2010.06537.
- Moming Duan, Duo Liu, Xinyuan Ji, Renping Liu, Liang Liang, Xianzhang Chen, Yujuan Tan .[FedGroup: Ternary Cosine Similarity-based Clustered Federated Learning Framework toward High Accuracy in Heterogeneous Data](https://arxiv.org/pdf/2010.06870) [J]. arXiv preprint arXiv:2010.06870.
- Harsh Bimal Desai, Mustafa Safa Ozdayi, Murat Kantarcioglu .[BlockFLA: Accountable Federated Learning via Hybrid Blockchain Architecture](https://arxiv.org/pdf/2010.07427) [J]. arXiv preprint arXiv:2010.07427.
- Saurav Prakash, Amir Salman Avestimehr .[Mitigating Byzantine Attacks in Federated Learning](https://arxiv.org/pdf/2010.07541) [J]. arXiv preprint arXiv:2010.07541.
- Raouf Kerkouche, Gergely Ács, Claude Castelluccia .[Federated Learning in Adversarial Settings](https://arxiv.org/pdf/2010.07808) [J]. arXiv preprint arXiv:2010.07808.
- Nour Moustafa, Marwa Keshk, Essam Debie, Helge Janicke .[Federated TON_IoT Windows Datasets for Evaluating AI-based Security Applications](https://arxiv.org/pdf/2010.08522) [J]. arXiv preprint arXiv:2010.08522.
- Nathalie Majcherczyk, Nishan Srishankar, Carlo Pinciroli .[Flow-FL: Data-Driven Federated Learning for Spatio-Temporal Predictions in Multi-Robot Systems](https://arxiv.org/pdf/2010.08595) [J]. arXiv preprint arXiv:2010.08595.
- Jiale Guo, Ziyao Liu, Kwok-Yan Lam, Jun Zhao, Yiqiang Chen, Chaoping Xing .[Secure Weighted Aggregation in Federated Learning](https://arxiv.org/pdf/2010.08730) [J]. arXiv preprint arXiv:2010.08730.
- Fan Mo, Anastasia Borovykh, Mohammad Malekzadeh, Hamed Haddadi, Soteris Demetriou .[Layer-wise Characterization of Latent Information Leakage in Federated Learning](https://arxiv.org/pdf/2010.08762) [J]. arXiv preprint arXiv:2010.08762.
- Fengda Zhang, Kun Kuang, Zhaoyang You, Tao Shen, Jun Xiao, Yin Zhang, Chao Wu, Yueting Zhuang, Xiaolin Li .[Federated Unsupervised Representation Learning](https://arxiv.org/pdf/2010.08982) [J]. arXiv preprint arXiv:2010.08982.
- Yifan Luo, Jindan Xu, Wei Xu, Kezhi Wang .[Sliding Differential Evolution Scheduling for Federated Learning in Bandwidth-Limited Networks](https://arxiv.org/pdf/2010.08991) [J]. arXiv preprint arXiv:2010.08991.
- Sheng Shen, Tianqing Zhu, Di Wu, Wei Wang, Wanlei Zhou .[From Distributed Machine Learning To Federated Learning: In The View Of Data Privacy And Security](https://arxiv.org/pdf/2010.09258) [J]. arXiv preprint arXiv:2010.09258.
- Vatsal Patel, Sarth Kanani, Tapan Pathak, Pankesh Patel, Muhammad Intizar Ali, John Breslin .[A Demonstration of Smart Doorbell Design Using Federated Deep Learning](https://arxiv.org/pdf/2010.09687) [J]. arXiv preprint arXiv:2010.09687.
- Mohammad Mohammadi Amiri, Tolga M. Duman, Deniz Gunduz, Sanjeev R. Kulkarni, H. Vincent Poor .[Blind Federated Edge Learning](https://arxiv.org/pdf/2010.10030) [J]. arXiv preprint arXiv:2010.10030.
- Xinjian Luo, Yuncheng Wu, Xiaokui Xiao, Beng Chin Ooi .[Feature Inference Attack on Model Predictions in Vertical Federated Learning](https://arxiv.org/pdf/2010.10152) [J]. arXiv preprint arXiv:2010.10152.
- [NIPS]Zhongxiang Dai, Kian Hsiang Low, Patrick Jaillet .[Federated Bayesian Optimization via Thompson Sampling](https://arxiv.org/pdf/2010.10154) [J]. arXiv preprint arXiv:2010.10154.
- Raed Abdel Sater, A. Ben Hamza .[A Federated Learning Approach to Anomaly Detection in Smart Buildings](https://arxiv.org/pdf/2010.10293) [J]. arXiv preprint arXiv:2010.10293.
- Yupeng Jiang, Yong Li, Yipeng Zhou, Xi Zheng .[Mitigating Sybil Attacks on Differential Privacy based Federated Learning](https://arxiv.org/pdf/2010.10572) [J]. arXiv preprint arXiv:2010.10572.
- Yifan Hu, Wei Xia, Jun Xiao, Chao Wu .[GFL: A Decentralized Federated Learning Framework Based On Blockchain](https://arxiv.org/pdf/2010.10996) [J]. arXiv preprint arXiv:2010.10996.
- Abhimanyu Dubey, Alex Pentland .[Differentially-Private Federated Linear Bandits](https://arxiv.org/pdf/2010.11425) [J]. arXiv preprint arXiv:2010.11425.
- Jinliang Yuan, Mengwei Xu, Xiao Ma, Ao Zhou, Xuanzhe Liu, Shangguang Wang .[Hierarchical Federated Learning through LAN-WAN Orchestration](https://arxiv.org/pdf/2010.11612) [J]. arXiv preprint arXiv:2010.11612.
- [NIPS]Othmane Marfoq, Chuan Xu, Giovanni Neglia, Richard Vidal .[Throughput-Optimal Topology Design for Cross-Silo Federated Learning](https://arxiv.org/pdf/2010.12229) [J]. arXiv preprint arXiv:2010.12229.<br>[code:[omarfoq/communication-in-cross-silo-fl](https://github.com/omarfoq/communication-in-cross-silo-fl)]
- Komal Krishna Mogilipalepu, Sumanth Kumar Modukuri, Amarlingam Madapu, Sundeep Prabhakar Chepuri .[Federated Deep Unfolding for Sparse Recovery](https://arxiv.org/pdf/2010.12616) [J]. arXiv preprint arXiv:2010.12616.
- Zhaowei Zhu, Jingxuan Zhu, Ji Liu, Yang Liu .[Federated Bandit: A Gossiping Approach](https://arxiv.org/pdf/2010.12763) [J]. arXiv preprint arXiv:2010.12763.
- Mingyang Chen, Wen Zhang, Zonggang Yuan, Yantao Jia, Huajun Chen .[FedE: Embedding Knowledge Graphs in Federated Setting](https://arxiv.org/pdf/2010.12882) [J]. arXiv preprint arXiv:2010.12882.
- Jiayi Wang, Shiqiang Wang, Rong-Rong Chen, Mingyue Ji .[Local Averaging Helps: Hierarchical Federated Learning and Convergence Analysis](https://arxiv.org/pdf/2010.12998) [J]. arXiv preprint arXiv:2010.12998.
- Wen Sun, Shiyu Lei, Lu Wang, Zhiqiang Liu, Yan Zhang .[Adaptive Federated Learning and Digital Twin for Industrial Internet of Things](https://arxiv.org/pdf/2010.13058) [J]. arXiv preprint arXiv:2010.13058.
- Wanli Ni, Yuanwei Liu, Zhaohui Yang, Hui Tian, Xuemin Shen .[Federated Learning in Multi-RIS Aided Systems](https://arxiv.org/pdf/2010.13333) [J]. arXiv preprint arXiv:2010.13333.
- Dick Carrillo, Lam Duc Nguyen, Pedro H. J. Nardelli, Evangelos Pournaras, Plinio Morita, Demóstenes Z. Rodríguez, Merim Dzaferagic, Harun Siljak, Alexander Jung, Laurent Hébert-Dufresne, Irene Macaluso, Mehar Ullah, Gustavo Fraidenraich, Petar Popovski .[Containing Future Epidemics with Trustworthy Federated Systems for Ubiquitous Warning and Response](https://arxiv.org/pdf/2010.13392) [J]. arXiv preprint arXiv:2010.13392.
- Elsa Rizk, Stefan Vlaski, Ali H. Sayed .[Optimal Importance Sampling for Federated Learning](https://arxiv.org/pdf/2010.13600) [J]. arXiv preprint arXiv:2010.13600.
- Wenlin Chen, Samuel Horvath, Peter Richtarik .[Optimal Client Sampling for Federated Learning](https://arxiv.org/pdf/2010.13723) [J]. arXiv preprint arXiv:2010.13723.
- Y. Sarcheshmehpour, M. Leinonen, A. Jung .[Federated Learning From Big Data Over Networks](https://arxiv.org/pdf/2010.14159) [J]. arXiv preprint arXiv:2010.14159.
- Jun Li, Lei Chen, Jiajia Chen .[Scalable Federated Learning over Passive Optical Networks](https://arxiv.org/pdf/2010.15454) [J]. arXiv preprint arXiv:2010.15454.
- Sudipan Saha, Tahir Ahmad .[Federated Transfer Learning: concept and applications](https://arxiv.org/pdf/2010.15561) [J]. arXiv preprint arXiv:2010.15561.
- Mustafa Safa Ozdayi, Murat Kantarcioglu, Rishabh Iyer .[Improving Accuracy of Federated Learning in Non-IID Settings](https://arxiv.org/pdf/2010.15582) [J]. arXiv preprint arXiv:2010.15582.
- Dhruv Guliani, Francoise Beaufays, Giovanni Motta .[Training Speech Recognition Models with Federated Learning: A Quality/Cost Framework](https://arxiv.org/pdf/2010.15965) [J]. arXiv preprint arXiv:2010.15965.
- Olga Zolotareva (1), Reza Nasirigerdeh (1), Julian Matschinske (1), Reihaneh Torkzadehmahani (1), Tobias Frisch (2), Julian Späth (1), David B. Blumenthal (1), Amir Abbasinejad (1 and 4), Paolo Tieri (3 nad 4), Nina K. Wenke (1), Markus List (1), Jan Baumbach (1 and 2) ((1) Chair of Experimental Bioinformatics, TUM School of Life Sciences, Technical University of Munich, Munich, Germany, (2) Department of Mathematics and Computer Science, University of Southern Denmark, Odense, Denmark, (3) CNR National Research Council, IAC Institute for Applied Computing, Rome, Italy, (4) SapienzaUniversity of Rome, Rome, Italy) .[Flimma: a federated and privacy-preserving tool for differential gene expression analysis](https://arxiv.org/pdf/2010.16403) [J]. arXiv preprint arXiv:2010.16403.
- Yuchen Zhao, Hanyang Liu, Honglin Li, Payam Barnaghi, Hamed Haddadi .[Semi-supervised Federated Learning for Activity Recognition](https://arxiv.org/pdf/2011.00851) [J]. arXiv preprint arXiv:2011.00851.
- Chen Wu, Xian Yang, Sencun Zhu, Prasenjit Mitra .[Mitigating Backdoor Attacks in Federated Learning](https://arxiv.org/pdf/2011.01767) [J]. arXiv preprint arXiv:2011.01767.
- Tiansheng Huang, Weiwei Lin, Wentai Wu, Ligang He, Keqin Li, Albert Y.Zomaya .[An Efficiency-boosting Client Selection Scheme for Federated Learning with Fairness Guarantee](https://arxiv.org/pdf/2011.01783) [J]. arXiv preprint arXiv:2011.01783.
- Kenneth Stewart, Yanqi Gu .[One-Shot Federated Learning with Neuromorphic Processors](https://arxiv.org/pdf/2011.01813) [J]. arXiv preprint arXiv:2011.01813.
- Zhaolin Ren, Aoxiao Zhong, Zhengyuan Zhou, Na Li .[Federated LQR: Learning through Sharing](https://arxiv.org/pdf/2011.01815) [J]. arXiv preprint arXiv:2011.01815.
- Sebastien Andreina, Giorgia Azzurra Marson, Helen Möllering, Ghassan Karame .[BaFFLe: Backdoor detection via Feedback-based Federated Learning](https://arxiv.org/pdf/2011.02167) [J]. arXiv preprint arXiv:2011.02167.
- Hyowoon Seo, Jihong Park, Seungeun Oh, Mehdi Bennis, Seong-Lyun Kim .[Federated Knowledge Distillation](https://arxiv.org/pdf/2011.02367) [J]. arXiv preprint arXiv:2011.02367.
- Zhihua Tian, Rui Zhang, Xiaoyang Hou, Jian Liu, Kui Ren .[FederBoost: Private Federated Learning for GBDT](https://arxiv.org/pdf/2011.02796) [J]. arXiv preprint arXiv:2011.02796.
- Junjie Pang, Jianbo Li, Zhenzhen Xie, Yan Huang, Zhipeng Cai .[Collaborative City Digital Twin For Covid-19 Pandemic: A Federated Learning Solution](https://arxiv.org/pdf/2011.02883) [J]. arXiv preprint arXiv:2011.02883.
- Ali Abedi, Shehroz S. Khan .[FedSL: Federated Split Learning on Distributed Sequential Data in Recurrent Neural Networks](https://arxiv.org/pdf/2011.03180) [J]. arXiv preprint arXiv:2011.03180.
- Gautham Krishna Gudur, Bala Shyamala Balaji, Satheesh K. Perepu .[Resource-Constrained Federated Learning with Heterogeneous Labels and Models](https://arxiv.org/pdf/2011.03206) [J]. arXiv preprint arXiv:2011.03206.
- Leye Wang, Han Yu, Xiao Han .[Federated Crowdsensing: Framework and Challenges](https://arxiv.org/pdf/2011.03208) [J]. arXiv preprint arXiv:2011.03208.
- Longfei Zheng, Jun Zhou, Chaochao Chen, Bingzhe Wu, Li Wang, Benyu Zhang .[ASFGNN: Automated Separated-Federated Graph Neural Network](https://arxiv.org/pdf/2011.03248) [J]. arXiv preprint arXiv:2011.03248.
- Nader Bouacida, Jiahui Hou, Hui Zang, Xin Liu .[Adaptive Federated Dropout: Improving Communication Efficiency and Generalization for Federated Learning](https://arxiv.org/pdf/2011.04050) [J]. arXiv preprint arXiv:2011.04050.
- Javad Ghareh Chamani (1), Dimitrios Papadopoulos (1) ((1) Hong Kong University of Science and Technology) .[Mitigating Leakage in Federated Learning with Trusted Hardware](https://arxiv.org/pdf/2011.04948) [J]. arXiv preprint arXiv:2011.04948.
- Zhibin Wang, Jiahang Qiu, Yong Zhou, Yuanming Shi, Liqun Fu, Wei Chen, Khaled B. Lataief .[Federated Learning via Intelligent Reflecting Surface](https://arxiv.org/pdf/2011.05051) [J]. arXiv preprint arXiv:2011.05051.
- Nguyen Truong, Kai Sun, Siyao Wang, Florian Guitton, Yike Guo .[Privacy Preservation in Federated Learning: Insights from the GDPR Perspective](https://arxiv.org/pdf/2011.05411) [J]. arXiv preprint arXiv:2011.05411.
- Raouf Kerkouche, Gergely Ács, Claude Castelluccia, Pierre Genevès .[Compression Boosts Differentially Private Federated Learning](https://arxiv.org/pdf/2011.05578) [J]. arXiv preprint arXiv:2011.05578.
- Xiaowen Cao, Guangxu Zhu, Jie Xu, Shuguang Cui .[Optimized Power Control for Over-the-Air Federated Edge Learning](https://arxiv.org/pdf/2011.05587) [J]. arXiv preprint arXiv:2011.05587.
- Jiangcheng Qin, Baisong Liu .[A Novel Privacy-Preserved Recommender System Framework based on Federated Learning](https://arxiv.org/pdf/2011.05614) [J]. arXiv preprint arXiv:2011.05614.
- Saurav Prakash, Sagar Dhakal, Mustafa Akdeniz, Yair Yona, Shilpa Talwar, Salman Avestimehr, Nageen Himayat .[Coded Computing for Low-Latency Federated Learning over Wireless Edge Networks](https://arxiv.org/pdf/2011.06223) [J]. arXiv preprint arXiv:2011.06223.
- Dipankar Sarkar, Ankur Narang, Sumit Rai .[Fed-Focal Loss for imbalanced data classification in Federated Learning](https://arxiv.org/pdf/2011.06283) [J]. arXiv preprint arXiv:2011.06283.
- Lixuan Yang, Cedric Beliard, Dario Rossi .[Heterogeneous Data-Aware Federated Learning](https://arxiv.org/pdf/2011.06393) [J]. arXiv preprint arXiv:2011.06393.
- Shuhao Xia, Jingyang Zhu, Yuhan Yang, Yong Zhou, Yuanming Shi, Wei Chen .[Fast Convergence Algorithm for Analog Federated Learning](https://arxiv.org/pdf/2011.06658) [J]. arXiv preprint arXiv:2011.06658.
- Anna Bogdanova, Akie Nakai, Yukihiko Okada, Akira Imakura, Tetsuya Sakurai .[Federated Learning System without Model Sharing through Integration of Dimensional Reduced Data Representations](https://arxiv.org/pdf/2011.06803) [J]. arXiv preprint arXiv:2011.06803.
- Jiyue Huang, Rania Talbi, Zilong Zhao, Sara Boucchenak, Lydia Y. Chen, Stefanie Roos .[An Exploratory Analysis on Users' Contributions in Federated Learning](https://arxiv.org/pdf/2011.06830) [J]. arXiv preprint arXiv:2011.06830.
- Ahmet M. Elbir .[Hybrid Federated and Centralized Learning](https://arxiv.org/pdf/2011.06892) [J]. arXiv preprint arXiv:2011.06892.
- Mohammad Bakhtiari, Reza Nasirigerdeh, Reihaneh Torkzadehmahani, Amirhossein Bayat, David B. Blumenthal, Markus List, Jan Baumbach .[Federated Multi-Mini-Batch: An Efficient Training Approach to Federated Learning in Non-IID Environments](https://arxiv.org/pdf/2011.07006) [J]. arXiv preprint arXiv:2011.07006.
- Huiwen Wu, Cen Chen, Li Wang .[A Theoretical Perspective on Differentially Private Federated Multi-task Learning](https://arxiv.org/pdf/2011.07179) [J]. arXiv preprint arXiv:2011.07179.
- Dipankar Sarkar, Sumit Rai, Ankur Narang .[CatFedAvg: Optimising Communication-efficiency and Classification Accuracy in Federated Learning](https://arxiv.org/pdf/2011.07229) [J]. arXiv preprint arXiv:2011.07229.
- Mahdi Boloursaz Mashhadi, Nir Shlezinger, Yonina C. Eldar, Deniz Gunduz .[FedRec: Federated Learning of Universal Receivers over Fading Channels](https://arxiv.org/pdf/2011.07271) [J]. arXiv preprint arXiv:2011.07271.
- Anbu Huang .[Dynamic backdoor attacks against federated learning](https://arxiv.org/pdf/2011.07429) [J]. arXiv preprint arXiv:2011.07429.
- Harry Cai, Daniel Rueckert, Jonathan Passerat-Palmbach .[2CP: Decentralized Protocols to Transparently Evaluate Contributivity in Blockchain Federated Learning Environments](https://arxiv.org/pdf/2011.07516) [J]. arXiv preprint arXiv:2011.07516.
- Honglin Yuan, Manzil Zaheer, Sashank Reddi .[Federated Composite Optimization](https://arxiv.org/pdf/2011.08474) [J]. arXiv preprint arXiv:2011.08474.
- Burak Hasircioglu, Deniz Gunduz .[Private Wireless Federated Learning with Anonymous Over-the-Air Computation](https://arxiv.org/pdf/2011.08579) [J]. arXiv preprint arXiv:2011.08579.
- Tiansheng Huang, Weiwei Lin, Keqin Li, Albert Y. Zomaya .[Stochastic Client Selection for Federated Learning with Volatile Clients](https://arxiv.org/pdf/2011.08756) [J]. arXiv preprint arXiv:2011.08756.
- Haiqin Weng, Juntao Zhang, Feng Xue, Tao Wei, Shouling Ji, Zhiyuan Zong .[Privacy Leakage of Real-World Vertical Federated Learning](https://arxiv.org/pdf/2011.09290) [J]. arXiv preprint arXiv:2011.09290.
- Nick Angelou, Ayoub Benaissa, Bogdan Cebere, William Clark, Adam James Hall, Michael A. Hoeh, Daniel Liu, Pavlos Papadopoulos, Robin Roehm, Robert Sandmann, Phillipp Schoppmann, Tom Titcombe .[Asymmetric Private Set Intersection with Applications to Contact Tracing and Private Vertical Federated Machine Learning](https://arxiv.org/pdf/2011.09350) [J]. arXiv preprint arXiv:2011.09350.
- Nicolas Kourtellis, Kleomenis Katevas, Diego Perino .[FLaaS: Federated Learning as a Service](https://arxiv.org/pdf/2011.09359) [J]. arXiv preprint arXiv:2011.09359.
- Di Chai, Leye Wang, Kai Chen, Qiang Yang .[FedEval: A Benchmark System with a Comprehensive Evaluation Model for Federated Learning](https://arxiv.org/pdf/2011.09655) [J]. arXiv preprint arXiv:2011.09655.
- Ihab Mohammed, Shadha Tabatabai, Ala Al-Fuqaha, Faissal El Bouanani, Junaid Qadir, Basheer Qolomany, Mohsen Guizani .[Budgeted Online Selection of Candidate IoT Clients to Participate in Federated Learning](https://arxiv.org/pdf/2011.09849) [J]. arXiv preprint arXiv:2011.09849.
- Yunlong Lu, Xiaohong Huang, Ke Zhang, Sabita Maharjan, Yan Zhang .[Low-latency Federated Learning and Blockchain for Edge Association in Digital Twin empowered 6G Networks](https://arxiv.org/pdf/2011.09902) [J]. arXiv preprint arXiv:2011.09902.
- Hang Liu, Xiaojun Yuan, Ying-Jun Angela Zhang .[Reconfigurable Intelligent Surface Enabled Federated Learning: A Unified Communication-Learning Design Approach](https://arxiv.org/pdf/2011.10282) [J]. arXiv preprint arXiv:2011.10282.
- Xinyi Xu, Lingjuan Lyu .[Towards Building a Robust and Fair Federated Learning System](https://arxiv.org/pdf/2011.10464) [J]. arXiv preprint arXiv:2011.10464.
- Hong Lin, Lidan Shou, Ke Chen, Gang Chen, Sai Wu .[LINDT: Tackling Negative Federated Learning with Local Adaptation](https://arxiv.org/pdf/2011.11160) [J]. arXiv preprint arXiv:2011.11160.
- Miao Yang, Akitanoshou Wong, Hongbin Zhu, Haifeng Wang, Hua Qian .[Federated learning with class imbalance reduction](https://arxiv.org/pdf/2011.11266) [J]. arXiv preprint arXiv:2011.11266.
- Yilun Lin, Chaochao Chen, Cen Chen, Li Wang .[Improving Federated Relational Data Modeling via Basis Alignment and Weight Penalty](https://arxiv.org/pdf/2011.11369) [J]. arXiv preprint arXiv:2011.11369.
- Dong Yang, Ziyue Xu, Wenqi Li, Andriy Myronenko, Holger R. Roth, Stephanie Harmon, Sheng Xu, Baris Turkbey, Evrim Turkbey, Xiaosong Wang, Wentao Zhu, Gianpaolo Carrafiello, Francesca Patella, Maurizio Cariati, Hirofumi Obinata, Hitoshi Mori, Kaku Tamura, Peng An, Bradford J. Wood, Daguang Xu .[Federated Semi-Supervised Learning for COVID Region Segmentation in Chest CT using Multi-National Data from China, Italy, Japan](https://arxiv.org/pdf/2011.11750) [J]. arXiv preprint arXiv:2011.11750.
- Minh N. H. Nguyen, Nguyen H. Tran, Yan Kyaw Tun, Zhu Han, Choong Seon Hong .[Toward Multiple Federated Learning Services Resource Sharing in Mobile Edge Networks](https://arxiv.org/pdf/2011.12469) [J]. arXiv preprint arXiv:2011.12469.
- Sen Lin, Li Yang, Zhezhi He, Deliang Fan, Junshan Zhang .[MetaGater: Fast Learning of Conditional Channel Gated Networks via Federated Meta-Learning](https://arxiv.org/pdf/2011.12511) [J]. arXiv preprint arXiv:2011.12511.
- Hangyu Zhu, Rui Wang, Yaochu Jin, Kaitai Liang, Jianting Ning .[Distributed Additive Encryption and Quantization for Privacy Preserving Federated Deep Learning](https://arxiv.org/pdf/2011.12623) [J]. arXiv preprint arXiv:2011.12623.
- Yong Xiao, Yingyu Li, Guangming Shi, H. Vincent Poor .[Optimizing Resource-Efficiency for Federated Edge Intelligence in IoT Networks](https://arxiv.org/pdf/2011.12691) [J]. arXiv preprint arXiv:2011.12691.
- Helin Yang, Jun Zhao, Zehui Xiong, Kwok-Yan Lam, Sumei Sun, Liang Xiao .[Privacy-Preserving Federated Learning for UAV-Enabled Networks: Learning-Based Joint Scheduling and Resource Management](https://arxiv.org/pdf/2011.14197) [J]. arXiv preprint arXiv:2011.14197.
- Chandra Thapa, M.A.P. Chamikara, Seyit A. Camtepe .[Advancements of federated learning towards privacy preservation: from federated learning to split learning](https://arxiv.org/pdf/2011.14818) [J]. arXiv preprint arXiv:2011.14818.
- [??]Shashi Raj Pandey, Minh N.H. Nguyen, Tri Nguyen Dang, Nguyen H. Tran, Kyi Thar, Zhu Han, Choong Seon Hong .[Edge-assisted Democratized Learning Towards Federated Analytics](https://arxiv.org/pdf/2012.00425) [J]. arXiv preprint arXiv:2012.00425.
- Felix Sattler, Arturo Marban, Roman Rischke, Wojciech Samek .[Communication-Efficient Federated Distillation](https://arxiv.org/pdf/2012.00632) [J]. arXiv preprint arXiv:2012.00632.
- Hongda Wu, Ping Wang .[Fast-Convergent Federated Learning with Adaptive Weighting](https://arxiv.org/pdf/2012.00661) [J]. arXiv preprint arXiv:2012.00661.
- K. R. Jayaram, Archit Verma, Ashish Verma, Gegi Thomas, Colin Sutcher-Shepard .[MYSTIKO : : Cloud-Mediated, Private, Federated Gradient Descent](https://arxiv.org/pdf/2012.00740) [J]. arXiv preprint arXiv:2012.00740.
- Zhe Liu, Fuchun Peng .[Federated Marginal Personalization for ASR Rescoring](https://arxiv.org/pdf/2012.00898) [J]. arXiv preprint arXiv:2012.00898.
- Stefan Vlaski, Elsa Rizk, Ali H. Sayed .[Second-Order Guarantees in Federated Learning](https://arxiv.org/pdf/2012.01474) [J]. arXiv preprint arXiv:2012.01474.
- Xu Guo, Pengwei Xing, Siwei Feng, Boyang Li, Chunyan Miao .[Federated Learning with Diversified Preference for Humor Recognition](https://arxiv.org/pdf/2012.01675) [J]. arXiv preprint arXiv:2012.01675.
- Seunghan Yang, Hyoungseob Park, Junyoung Byun, Changick Kim .[Robust Federated Learning with Noisy Labels](https://arxiv.org/pdf/2012.01700) [J]. arXiv preprint arXiv:2012.01700.
- Giulio Zizzo, Ambrish Rawat, Mathieu Sinn, Beat Buesser .[FAT: Federated Adversarial Training](https://arxiv.org/pdf/2012.01791) [J]. arXiv preprint arXiv:2012.01791.
- Yi Liu, Li Zhang, Ning Ge, Guanghao Li .[A Systematic Literature Review on Federated Learning: From A Model Quality Perspective](https://arxiv.org/pdf/2012.01973) [J]. arXiv preprint arXiv:2012.01973.
- Jun Li, Yumeng Shao, Ming Ding, Chuan Ma, Kang Wei, Zhu Han, H. Vincent Poor .[Blockchain Assisted Decentralized Federated Learning (BLADE-FL) with Lazy Clients](https://arxiv.org/pdf/2012.02044) [J]. arXiv preprint arXiv:2012.02044.
- Annie Abay, Yi Zhou, Nathalie Baracaldo, Shashank Rajamoni, Ebube Chuba, Heiko Ludwig .[Mitigating Bias in Federated Learning](https://arxiv.org/pdf/2012.02447) [J]. arXiv preprint arXiv:2012.02447.
- Gautham Krishna Gudur, Satheesh K. Perepu .[Federated Learning with Heterogeneous Labels and Models for Mobile Activity Monitoring](https://arxiv.org/pdf/2012.02539) [J]. arXiv preprint arXiv:2012.02539.
- Peng Xiao, Samuel Cheng .[Probabilistic Federated Learning of Neural Networks Incorporated with Global Posterior Information](https://arxiv.org/pdf/2012.03178) [J]. arXiv preprint arXiv:2012.03178.
- Jin-woo Lee, Jaehoon Oh, Sungsu Lim, Se-Young Yun, Jae-Gil Lee .[TornadoAggregate: Accurate and Scalable Federated Learning via the Ring-Based Architecture](https://arxiv.org/pdf/2012.03214) [J]. arXiv preprint arXiv:2012.03214.
- Taehyeon Kim, Sangmin Bae, Jin-woo Lee, Seyoung Yun .[Accurate and Fast Federated Learning via Combinatorial Multi-Armed Bandits](https://arxiv.org/pdf/2012.03270) [J]. arXiv preprint arXiv:2012.03270.
- Zewei Long, Liwei Che, Yaqing Wang, Muchao Ye, Junyu Luo, Jinze Wu, Houping Xiao, Fenglong Ma .[FedSemi: An Adaptive Federated Semi-Supervised Learning Framework](https://arxiv.org/pdf/2012.03292) [J]. arXiv preprint arXiv:2012.03292.
- Mohamed K. Abdel-Aziz, Cristina Perfecto, Sumudu Samarakoon, Mehdi Bennis, Walid Saad .[Vehicular Cooperative Perception Through Action Branching and Federated Reinforcement Learning](https://arxiv.org/pdf/2012.03414) [J]. arXiv preprint arXiv:2012.03414.
- Yeongwoo Kim, Ezeddin Al Hakim, Johan Haraldson, Henrik Eriksson, José Mairton B. da Silva Jr., Carlo Fischione .[Dynamic Clustering in Federated Learning](https://arxiv.org/pdf/2012.03788) [J]. arXiv preprint arXiv:2012.03788.
- Sihui Zheng, Cong Shen, Xiang Chen .[Design and Analysis of Uplink and Downlink Communications for Federated Learning](https://arxiv.org/pdf/2012.04057) [J]. arXiv preprint arXiv:2012.04057.
- Rudrajit Das, Abolfazl Hashemi, Sujay Sanghavi, Inderjit S. Dhillon .[Improved Convergence Rates for Non-Convex Federated Learning with Compression](https://arxiv.org/pdf/2012.04061) [J]. arXiv preprint arXiv:2012.04061.
- Binghui Wang, Ang Li, Hai Li, Yiran Chen .[GraphFL: A Federated Learning Framework for Semi-Supervised Node Classification on Graphs](https://arxiv.org/pdf/2012.04187) [J]. arXiv preprint arXiv:2012.04187.
- Tian Li, Shengyuan Hu, Ahmad Beirami, Virginia Smith .[Federated Multi-Task Learning for Competing Constraints](https://arxiv.org/pdf/2012.04221) [J]. arXiv preprint arXiv:2012.04221.
- Yi Liu, Xingliang Yuan, Ruihui Zhao, Yifeng Zheng, Yefeng Zheng .[RC-SSFL: Towards Robust and Communication-efficient Semi-supervised Federated Learning System](https://arxiv.org/pdf/2012.04432) [J]. arXiv preprint arXiv:2012.04432.
- Yi Liu, Ruihui Zhao, Jiawen Kang, Abdulsalam Yassine, Dusit Niyato, Jialiang Peng .[Towards Communication-efficient and Attack-Resistant Federated Edge Learning for Industrial Internet of Things](https://arxiv.org/pdf/2012.04436) [J]. arXiv preprint arXiv:2012.04436.
- Jin-woo Lee, Jaehoon Oh, Yooju Shin, Jae-Gil Lee, Se-Young Yoon .[Accurate and Fast Federated Learning via IID and Communication-Aware Grouping](https://arxiv.org/pdf/2012.04857) [J]. arXiv preprint arXiv:2012.04857.
- Mohammad Salehi, Ekram Hossain .[Federated Learning in Unreliable and Resource-Constrained Cellular Wireless Networks](https://arxiv.org/pdf/2012.05137) [J]. arXiv preprint arXiv:2012.05137.
- Beongjun Choi, Jy-yong Sohn, Dong-Jun Han, Jaekyun Moon .[Communication-Computation Efficient Secure Aggregation for Federated Learning](https://arxiv.org/pdf/2012.05433) [J]. arXiv preprint arXiv:2012.05433.
- Naram Mhaisen, Alaa Awad, Amr Mohamed, Aiman Erbad, Mohsen Guizani .[Analysis and Optimal Edge Assignment For Hierarchical Federated Learning on Non-IID Data](https://arxiv.org/pdf/2012.05622) [J]. arXiv preprint arXiv:2012.05622.
- Canh T. Dinh, Nguyen H. Tran, Tuan Dung Nguyen, Wei Bao, Amir Rezaei Balef .[DONE: Distributed Newton-type Method for Federated Edge Learning](https://arxiv.org/pdf/2012.05625) [J]. arXiv preprint arXiv:2012.05625.
- Jingwei Sun, Ang Li, Binghui Wang, Huanrui Yang, Hai Li, Yiran Chen .[Provable Defense against Privacy Leakage in Federated Learning from Representation Perspective](https://arxiv.org/pdf/2012.06043) [J]. arXiv preprint arXiv:2012.06043.
- J. Li, L. Lyu, X. Liu, X. Zhang, X. Lyu .[FLEAM: A Federated Learning Empowered Architecture to Mitigate DDoS in Industrial IoT](https://arxiv.org/pdf/2012.06150) [J]. arXiv preprint arXiv:2012.06150.
- Lingjuan Lyu, Han Yu, Xingjun Ma, Lichao Sun, Jun Zhao, Qiang Yang, Philip S. Yu .[Privacy and Robustness in Federated Learning: Attacks and Defenses](https://arxiv.org/pdf/2012.06337) [J]. arXiv preprint arXiv:2012.06337.
- Yuya Jeremy Ong, Yi Zhou, Nathalie Baracaldo, Heiko Ludwig .[Adaptive Histogram-Based Gradient Boosted Trees for Federated Learning](https://arxiv.org/pdf/2012.06670) [J]. arXiv preprint arXiv:2012.06670.
- Yuhao Zhou, Ye Qing, Jiancheng Lv .[Communication-Efficient Federated Learning with Compensated Overlap-FedAvg](https://arxiv.org/pdf/2012.06706) [J]. arXiv preprint arXiv:2012.06706.
- Alberto Blanco-Justicia, Josep Domingo-Ferrer, Sergio Martínez, David Sánchez, Adrian Flanagan, Kuan Eeik Tan .[Achieving Security and Privacy in Federated Learning Systems: Survey, Research Challenges and Future Directions](https://arxiv.org/pdf/2012.06810) [J]. arXiv preprint arXiv:2012.06810.
- Yung-Lin Hsu, Chen-Feng Liu, Sumudu Samarakoon, Hung-Yu Wei, Mehdi Bennis .[Age-Optimal Power Allocation in Industrial IoT: A Risk-Sensitive Federated Learning Approach](https://arxiv.org/pdf/2012.06860) [J]. arXiv preprint arXiv:2012.06860.
- Noor Ali Al-Athba Al-Marri, Bekir Sait Ciftler, Mohamed Abdallah .[Federated Mimic Learning for Privacy Preserving Intrusion Detection](https://arxiv.org/pdf/2012.06974) [J]. arXiv preprint arXiv:2012.06974.
- Beomyeol Jeon, S.M. Ferdous, Muntasir Raihan Rahman, Anwar Walid .[Privacy-preserving Decentralized Aggregation for Federated Learning](https://arxiv.org/pdf/2012.07183) [J]. arXiv preprint arXiv:2012.07183.
- Elsa Rizk, Stefan Vlaski, Ali H. Sayed .[Federated Learning under Importance Sampling](https://arxiv.org/pdf/2012.07383) [J]. arXiv preprint arXiv:2012.07383.
- Qiong Wu, Xu Chen, Zhi Zhou, Junshan Zhang .[FedHome: Cloud-Edge based Personalized Federated Learning for In-Home Health Monitoring](https://arxiv.org/pdf/2012.07450) [J]. arXiv preprint arXiv:2012.07450.
- Yae Jee Cho, Samarth Gupta, Gauri Joshi, Osman Yağan .[Bandit-based Communication-Efficient Client Selection Strategies for Federated Learning](https://arxiv.org/pdf/2012.08009) [J]. arXiv preprint arXiv:2012.08009.
- Yang He, Maximilian Zenk, Mario Fritz .[CosSGD: Nonlinear Quantization for Communication-efficient Federated Learning](https://arxiv.org/pdf/2012.08241) [J]. arXiv preprint arXiv:2012.08241.
- Bing Luo, Xiang Li, Shiqiang Wang, Jianwei Huang, Leandros Tassiulas .[Cost-Effective Federated Learning Design](https://arxiv.org/pdf/2012.08336) [J]. arXiv preprint arXiv:2012.08336.
- Michael Zhang, Karan Sapra, Sanja Fidler, Serena Yeung, Jose M. Alvarez .[Personalized Federated Learning with First Order Model Optimization](https://arxiv.org/pdf/2012.08565) [J]. arXiv preprint arXiv:2012.08565.
- Sheng Yue, Ju Ren, Jiang Xin, Sen Lin, Junshan Zhang .[Inexact-ADMM Based Federated Meta-Learning for Fast and Continual Edge Learning](https://arxiv.org/pdf/2012.08677) [J]. arXiv preprint arXiv:2012.08677.
- Dingwei Li, Qinglong Chang, Lixue Pang, Yanfang Zhang, Xudong Sun, Jikun Ding, Liang Zhang .[More Industry-friendly: Federated Learning with High Efficient Design](https://arxiv.org/pdf/2012.08809) [J]. arXiv preprint arXiv:2012.08809.
- Emre Ozfatura, Kerem Ozfatura, Deniz Gunduz .[FedADC: Accelerated Federated Learning with Drift Control](https://arxiv.org/pdf/2012.09102) [J]. arXiv preprint arXiv:2012.09102.
- Wei Huang, Tianrui Li, Dexian Wang, Shengdong Du, Junbo Zhang .[Fairness and Accuracy in Federated Learning](https://arxiv.org/pdf/2012.10069) [J]. arXiv preprint arXiv:2012.10069.
- Rachit Agarwal, Tarek Elsaleh, Elias Tragos .[GDPR-inspired IoT Ontology enabling Semantic Interoperability, Federation of Deployments and Privacy-Preserving Applications](https://arxiv.org/pdf/2012.10314) [J]. arXiv preprint arXiv:2012.10314.
- Jiasi Weng, Jian Weng, Hongwei Huang, Chengjun Cai, Cong Wang .[FedServing: A Federated Prediction Serving Framework Based on Incentive Mechanism](https://arxiv.org/pdf/2012.10566) [J]. arXiv preprint arXiv:2012.10566.
- Yihao Xue, Chaoyue Niu, Zhenzhe Zheng, Shaojie Tang, Chengfei Lv, Fan Wu, Guihai Chen .[Toward Understanding the Influence of Individual Clients in Federated Learning](https://arxiv.org/pdf/2012.10936) [J]. arXiv preprint arXiv:2012.10936.
- Rui Chen, Liang Li, Kaiping Xue, Chi Zhang, Lingjia Liu, Miao Pan .[To Talk or to Work: Energy Efficient Federated Learning over Mobile Devices via the Weight Quantization and 5G Transmission Co-Design](https://arxiv.org/pdf/2012.11070) [J]. arXiv preprint arXiv:2012.11070.
- Vito Walter Anelli, Yashar Deldjoo, Tommaso Di Noia, Antonio Ferrara, Fedelucio Narducci .[FedeRank: User Controlled Feedback with Federated Recommender Systems](https://arxiv.org/pdf/2012.11328) [J]. arXiv preprint arXiv:2012.11328.
- Liang Li, Dian Shi, Ronghui Hou, Hui Li, Miao Pan, Zhu Han .[To Talk or to Work: Flexible Communication Compression for Energy Efficient Federated Learning over Heterogeneous Mobile Edge Devices](https://arxiv.org/pdf/2012.11804) [J]. arXiv preprint arXiv:2012.11804.
- Sonal Doomra, Naman Kohli, Shounak Athavale .[Turn Signal Prediction: A Federated Learning Case Study](https://arxiv.org/pdf/2012.12401) [J]. arXiv preprint arXiv:2012.12401.
- Xinwei Zhang, Wotao Yin, Mingyi Hong, Tianyi Chen .[Hybrid Federated Learning: Algorithms and Implementation](https://arxiv.org/pdf/2012.12420) [J]. arXiv preprint arXiv:2012.12420.
- Chengxi Li, Gang Li, Pramod K. Varshney .[Decentralized Federated Learning via Mutual Knowledge Transfer](https://arxiv.org/pdf/2012.13063) [J]. arXiv preprint arXiv:2012.13063.
- Gaoyang Liu, Yang Yang, Xiaoqiang Ma, Chen Wang, Jiangchuan Liu .[Federated Unlearning](https://arxiv.org/pdf/2012.13891) [J]. arXiv preprint arXiv:2012.13891.
- Ruiyuan Wu, Anna Scaglione, Hoi-To Wai, Nurullah Karakoc, Kari Hreinsson, Wing-Kin Ma .[Federated Block Coordinate Descent Scheme for Learning Global and Personalized Models](https://arxiv.org/pdf/2012.13900) [J]. arXiv preprint arXiv:2012.13900.
- Xiaoyu Cao, Minghong Fang, Jia Liu, Neil Zhenqiang Gong .[FLTrust: Byzantine-robust Federated Learning via Trust Bootstrapping](https://arxiv.org/pdf/2012.13995) [J]. arXiv preprint arXiv:2012.13995.
- Zheqi Zhu, Shuo Wan, Pingyi Fan, Khaled B. Letaief .[Federated Multi-Agent Actor-Critic Learning for Age Sensitive Mobile Edge Computing](https://arxiv.org/pdf/2012.14137) [J]. arXiv preprint arXiv:2012.14137.
- Amirhossein Reisizadeh, Isidoros Tziotis, Hamed Hassani, Aryan Mokhtari, Ramtin Pedarsani .[Straggler-Resilient Federated Learning: Leveraging the Interplay Between Statistical Accuracy and System Heterogeneity](https://arxiv.org/pdf/2012.14453) [J]. arXiv preprint arXiv:2012.14453.
- Seunghoon Lee, Chanho Park, Song-Nam Hong, Yonina C. Eldar, Namyoon Lee .[Bayesian Federated Learning over Wireless Networks](https://arxiv.org/pdf/2012.15486) [J]. arXiv preprint arXiv:2012.15486.
- Binbin Guo, Yuan Mei, Danyang Xiao, Weigang Wu, Ye Yin, Hongli Chang .[PFL-MoE: Personalized Federated Learning Based on Mixture of Experts](https://arxiv.org/pdf/2012.15589) [J]. arXiv preprint arXiv:2012.15589.
- Baturalp Buyukates, Sennur Ulukus .[Timely Communication in Federated Learning](https://arxiv.org/pdf/2012.15831) [J]. arXiv preprint arXiv:2012.15831.


### 2021
- Qianqian Tong, Guannan Liang, Tan Zhu, Jinbo Bi .[Federated Nonconvex Sparse Learning](https://arxiv.org/pdf/2101.00052) [J]. arXiv preprint arXiv:2101.00052.
- David Enthoven, Zaid Al-Ars .[Fidel: Reconstructing Private Training Samples from Weight Updates in Federated Learning](https://arxiv.org/pdf/2101.00159) [J]. arXiv preprint arXiv:2101.00159.
- Yuris Mulya Saputra, Dinh Thai Hoang, Diep N. Nguyen, Eryk Dutkiewicz .[Dynamic Federated Learning-Based Economic Framework for Internet-of-Vehicles](https://arxiv.org/pdf/2101.00191) [J]. arXiv preprint arXiv:2101.00191.
- Su Wang, Mengyuan Lee, Seyyedali Hosseinalipour, Roberto Morabito, Mung Chiang, Christopher G. Brinton .[Device Sampling for Heterogeneous Federated Learning: Theory, Algorithms, and Implementation](https://arxiv.org/pdf/2101.00787) [J]. arXiv preprint arXiv:2101.00787.
- Parimala M, Swarna Priya R M, Quoc-Viet Pham, Kapal Dev, Praveen Kumar Reddy Maddikunta, Thippa Reddy Gadekallu, Thien Huynh-The .[Fusion of Federated Learning and Industrial Internet of Things: A Survey](https://arxiv.org/pdf/2101.00798) [J]. arXiv preprint arXiv:2101.00798.
- Zhiyan Chen, Murat Simsek, Burak Kantarci .[Federated Learning-Based Risk-Aware Decision toMitigate Fake Task Impacts on CrowdsensingPlatforms](https://arxiv.org/pdf/2101.01266) [J]. arXiv preprint arXiv:2101.01266.
- Zhaohui Yang, Mingzhe Chen, Kai-Kit Wong, H. Vincent Poor, Shuguang Cui .[Federated Learning for 6G: Applications, Challenges, and Opportunities](https://arxiv.org/pdf/2101.01338) [J]. arXiv preprint arXiv:2101.01338.
- Christodoulos Pappas, Dimitris Chatzopoulos, Spyros Lalis, Manolis Vavalis .[IPLS : A Framework for Decentralized Federated Learning](https://arxiv.org/pdf/2101.01901) [J]. arXiv preprint arXiv:2101.01901.
- Francesco Malandrino, Carla Fabiana Chiasserini .[Federated Learning at the Network Edge: When Not All Nodes are Created Equal](https://arxiv.org/pdf/2101.01995) [J]. arXiv preprint arXiv:2101.01995.
- Xizixiang Wei, Cong Shen .[Federated Learning over Noisy Channels: Convergence Analysis and Design Examples](https://arxiv.org/pdf/2101.02198) [J]. arXiv preprint arXiv:2101.02198.
- Thien Duc Nguyen, Phillip Rieger, Hossein Yalame, Helen Möllering, Hossein Fereidooni, Samuel Marchal, Markus Miettinen, Azalia Mirhoseini, Ahmad-Reza Sadeghi, Thomas Schneider, Shaza Zeitouni .[FLGUARD: Secure and Private Federated Learning](https://arxiv.org/pdf/2101.02281) [J]. arXiv preprint arXiv:2101.02281.
- Sin Kit Lo, Qinghua Lu, Liming Zhu, Hye-young Paik, Xiwei Xu, Chen Wang .[Architectural Patterns for the Design of Federated Learning Systems](https://arxiv.org/pdf/2101.02373) [J]. arXiv preprint arXiv:2101.02373.
- Constance Beguier, Jean Ogier du Terrail, Iqraa Meah, Mathieu Andreux, Eric W. Tramel .[Differentially Private Federated Learning for Cancer Prediction](https://arxiv.org/pdf/2101.02997) [J]. arXiv preprint arXiv:2101.02997.
- Olakunle Ibitoye, M. Omair Shafiq, Ashraf Matrawy .[DiPSeN: Differentially Private Self-normalizing Neural Networks For Adversarial Robustness in Federated Learning](https://arxiv.org/pdf/2101.03218) [J]. arXiv preprint arXiv:2101.03218.
- Hang Chen, Syed Ali Asif, Jihong Park, Chien-Chung Shen, Mehdi Bennis .[Robust Blockchained Federated Learning with Model Validation and Proof-of-Stake Inspired Consensus](https://arxiv.org/pdf/2101.03300) [J]. arXiv preprint arXiv:2101.03300.
- Stefano Savazzi, Monica Nicoli, Mehdi Bennis, Sanaz Kianoush, Luca Barbieri .[Opportunities of Federated Learning in Connected, Cooperative and Automated Industrial Systems](https://arxiv.org/pdf/2101.03367) [J]. arXiv preprint arXiv:2101.03367.
- Jie Xu, Heqiang Wang, Lixing Chen .[Bandwidth Allocation for Multiple Federated Learning Services in Wireless Edge Networks](https://arxiv.org/pdf/2101.03627) [J]. arXiv preprint arXiv:2101.03627.
- Ahmed Imteaj, M. Hadi Amini .[FedAR: Activity and Resource-Aware Federated Learning Model for Distributed Mobile Robots](https://arxiv.org/pdf/2101.03705) [J]. arXiv preprint arXiv:2101.03705.
- Yao Fu, Yipeng Zhou, Di Wu, Shui Yu, Yonggang Wen, Chao Li .[On the Practicality of Differential Privacy in Federated Learning by Tuning Iteration Times](https://arxiv.org/pdf/2101.04163) [J]. arXiv preprint arXiv:2101.04163.
- Ognjen Rudovic, Nicolas Tobis, Sebastian Kaltwang, Björn Schuller, Daniel Rueckert, Jeffrey F. Cohn, Rosalind W. Picard .[Personalized Federated Deep Learning for Pain Estimation From Face Images](https://arxiv.org/pdf/2101.04800) [J]. arXiv preprint arXiv:2101.04800.
- Dian Shi, Liang Li, Rui Chen, Pavana Prakash, Miao Pan, Yuguang Fang .[Towards Energy Efficient Federated Learning over 5G+ Mobile Devices](https://arxiv.org/pdf/2101.04866) [J]. arXiv preprint arXiv:2101.04866.
- Priyanka Mary Mammen .[Federated Learning: Opportunities and Challenges](https://arxiv.org/pdf/2101.05428) [J]. arXiv preprint arXiv:2101.05428.
- Shenghui Li, Edith Ngai, Fanghua Ye, Thiemo Voigt .[Auto-weighted Robust Federated Learning with Corrupted Data Sources](https://arxiv.org/pdf/2101.05880) [J]. arXiv preprint arXiv:2101.05880.
- Jun Li, Yumeng Shao, Kang Wei, Ming Ding, Chuan Ma, Long Shi, Zhu Han, H. Vincent Poor .[Blockchain Assisted Decentralized Federated Learning (BLADE-FL): Performance Analysis and Resource Allocation](https://arxiv.org/pdf/2101.06905) [J]. arXiv preprint arXiv:2101.06905.
- Kaiqiang Qi, Tingting Liu, Chenyang Yang .[Federated Learning Based Proactive Handover in Millimeter-wave Vehicular Networks](https://arxiv.org/pdf/2101.07032) [J]. arXiv preprint arXiv:2101.07032.
- Jean-Francois Rajotte, Sumit Mukherjee, Caleb Robinson, Anthony Ortiz, Christopher West, Juan Lavista Ferres, Raymond T Ng .[Reducing bias and increasing utility by federated generative modeling of medical images using a centralized adversary](https://arxiv.org/pdf/2101.07235) [J]. arXiv preprint arXiv:2101.07235.
- Adnan Qayyum, Kashif Ahmad, Muhammad Ahtazaz Ahsan, Ala Al-Fuqaha, Junaid Qadir .[Collaborative Federated Learning For Healthcare: Multi-Modal COVID-19 Diagnosis at the Edge](https://arxiv.org/pdf/2101.07511) [J]. arXiv preprint arXiv:2101.07511.
- Yaoxin Zhuo, Baoxin Li .[FedNS: Improving Federated Learning for collaborative image classification on mobile clients](https://arxiv.org/pdf/2101.07995) [J]. arXiv preprint arXiv:2101.07995.
- Naifu Zhang, Meixia Tao, Jia Wang .[Rate Region for Indirect Multiterminal Source Coding in Federated Learning](https://arxiv.org/pdf/2101.08696) [J]. arXiv preprint arXiv:2101.08696.
- Emre Ozfatura, Kerem Ozfatura, Deniz Gunduz .[Time-Correlated Sparsification for Communication-Efficient Federated Learning](https://arxiv.org/pdf/2101.08837) [J]. arXiv preprint arXiv:2101.08837.
- Song WenJie, Shen Xuan .[Vertical federated learning based on DFP and BFGS](https://arxiv.org/pdf/2101.09428) [J]. arXiv preprint arXiv:2101.09428.
- Cengis Hasan .[Incentive Mechanism Design for Federated Learning: Hedonic Game Approach](https://arxiv.org/pdf/2101.09673) [J]. arXiv preprint arXiv:2101.09673.
- Ajesh Koyatan Chathoth (1), Abhyuday Jagannatha (2), Stephen Lee (1) ((1) University of Pittsburgh, (2) University of Massachusetts Amherst) .[Federated Intrusion Detection for IoT with Heterogeneous Cohort Privacy](https://arxiv.org/pdf/2101.09878) [J]. arXiv preprint arXiv:2101.09878.
- Shuaicheng Ma, Yang Cao, Li Xiong .[Transparent Contribution Evaluation for Secure Federated Learning on Blockchain](https://arxiv.org/pdf/2101.10572) [J]. arXiv preprint arXiv:2101.10572.
- Ranwa Al Mallah, David Lopez, Bilal Farooq .[Untargeted Poisoning Attack Detection in Federated Learning via Behavior Attestation](https://arxiv.org/pdf/2101.10904) [J]. arXiv preprint arXiv:2101.10904.
- Haibo Yang, Minghong Fang, Jia Liu .[Achieving Linear Speedup with Partial Worker Participation in Non-IID Federated Learning](https://arxiv.org/pdf/2101.11203) [J]. arXiv preprint arXiv:2101.11203.
- Yiying Li, Wei Zhou, Huaimin Wang, Haibo Mi, Timothy M. Hospedales .[FedH2L: Federated Learning with Model and Statistical Heterogeneity](https://arxiv.org/pdf/2101.11296) [J]. arXiv preprint arXiv:2101.11296.
- Mohammad Malekzadeh, Burak Hasircioglu, Nitish Mital, Kunal Katarya, Mehmet Emre Ozfatura, Deniz Gündüz .[Dopamine: Differentially Private Federated Learning on Medical Data](https://arxiv.org/pdf/2101.11693) [J]. arXiv preprint arXiv:2101.11693.
- Ning Ge, Guanghao Li, Li Zhang, Yi Liu Yi Liu .[Failure Prediction in Production Line Based on Federated Learning: An Empirical Study](https://arxiv.org/pdf/2101.11715) [J]. arXiv preprint arXiv:2101.11715.
- Kang Wei, Jun Li, Ming Ding, Chuan Ma, Yo-Seb Jeon, H. Vincent Poor .[Covert Model Poisoning Against Federated Learning: Algorithm Design and Optimization](https://arxiv.org/pdf/2101.11799) [J]. arXiv preprint arXiv:2101.11799.
- Xinle Liang, Yang Liu, Jiahuan Luo, Yuanqin He, Tianjian Chen, Qiang Yang .[Self-supervised Cross-silo Federated Neural Architecture Search](https://arxiv.org/pdf/2101.11896) [J]. arXiv preprint arXiv:2101.11896.
- Shuai Wang, Yuncong Hong, Rui Wang, Qi Hao, Yik-Chung Wu, Derrick Wing Kwan Ng .[Edge Federated Learning Via Unit-Modulus Over-The-Air Computation (Extended Version)](https://arxiv.org/pdf/2101.12051) [J]. arXiv preprint arXiv:2101.12051.
- Chengshuai Shi, Cong Shen .[Federated Multi-Armed Bandits](https://arxiv.org/pdf/2101.12204) [J]. arXiv preprint arXiv:2101.12204.
- Nima Mohammadi, Jianan Bai, Qiang Fan, Yifei Song, Yang Yi, Lingjia Liu .[Differential Privacy Meets Federated Learning under Communication Constraints](https://arxiv.org/pdf/2101.12240) [J]. arXiv preprint arXiv:2101.12240.
- Cong T. Nguyen, Dinh Thai Hoang, Diep N. Nguyen, Yong Xiao, Hoang-Anh Pham, Eryk Dutkiewicz, Nguyen Huynh Tuong .[FedChain: Secure Proof-of-Stake-based Framework for Federated-blockchain Systems](https://arxiv.org/pdf/2101.12428) [J]. arXiv preprint arXiv:2101.12428.
- Shunpu Tang, Wenqi Zhou, Lunyuan Chen, Lijia Lai, Junjuan Xia, Liseng Fan .[Battery-constrained Federated Edge Learning in UAV-enabled IoT for B5G/6G Networks](https://arxiv.org/pdf/2101.12472) [J]. arXiv preprint arXiv:2101.12472.
- Hong Xing, Osvaldo Simeone, Suzhi Bi .[Federated Learning over Wireless Device-to-Device Networks: Algorithms and Convergence Analysis](https://arxiv.org/pdf/2101.12704) [J]. arXiv preprint arXiv:2101.12704.
- Wenzhuo Yang, Yipeng Zhou, Maio Hu, Di Wu, James Xi Zheng, Hui Wang, Song Guo .[Gain without Pain: Offsetting DP-injected Nosies Stealthily in Cross-device Federated Learning](https://arxiv.org/pdf/2102.00404) [J]. arXiv preprint arXiv:2102.00404.
- Syed Zawad, Ahsan Ali, Pin-Yu Chen, Ali Anwar, Yi Zhou, Nathalie Baracaldo, Yuan Tian, Feng Yan .[Curse or Redemption? How Data Heterogeneity Affects the Robustness of Federated Learning](https://arxiv.org/pdf/2102.00655) [J]. arXiv preprint arXiv:2102.00655.
- Agrin Hilmkil, Sebastian Callh, Matteo Barbieri, Leon René Sütfeld, Edvin Listo Zec, Olof Mogren .[Scaling Federated Learning for Fine-tuning of Large Language Models](https://arxiv.org/pdf/2102.00875) [J]. arXiv preprint arXiv:2102.00875.
- Thorsten Wittkopp, Alexander Acker .[Decentralized Federated Learning Preserves Model and Data Privacy](https://arxiv.org/pdf/2102.00880) [J]. arXiv preprint arXiv:2102.00880.
- Zhaohua Zheng, Yize Zhou, Yilong Sun, Zhang Wang, Boyi Liu, Keqiu Li .[Federated Learning in Smart Cities: A Comprehensive Survey](https://arxiv.org/pdf/2102.01375) [J]. arXiv preprint arXiv:2102.01375.
- Amirhossein Malekijoo, Mohammad Javad Fadaeieslam, Hanieh Malekijou, Morteza Homayounfar, Farshid Alizadeh-Shabdiz, Reza Rawassizadeh .[FEDZIP: A Compression Framework for Communication-Efficient Federated Learning](https://arxiv.org/pdf/2102.01593) [J]. arXiv preprint arXiv:2102.01593.
- Wentai Wu, Ligang He, Weiwei Lin, Rui Mao, Chenlin Huang, Wei Song .[FedProf: Optimizing Federated Learning with Dynamic Data Profiling](https://arxiv.org/pdf/2102.01733) [J]. arXiv preprint arXiv:2102.01733.
- Xiaoyu Cao, Jinyuan Jia, Neil Zhenqiang Gong .[Provably Secure Federated Learning against Malicious Clients](https://arxiv.org/pdf/2102.01854) [J]. arXiv preprint arXiv:2102.01854.
- Liangxi Liu, Feng Zheng .[A Bayesian Federated Learning Framework with Multivariate Gaussian Product](https://arxiv.org/pdf/2102.01936) [J]. arXiv preprint arXiv:2102.01936.
- Qinbin Li, Yiqun Diao, Quan Chen, Bingsheng He .[Federated Learning on Non-IID Data Silos: An Experimental Study](https://arxiv.org/pdf/2102.02079) [J]. arXiv preprint arXiv:2102.02079.
- Zhuosheng Zhang, Jiarui Li, Shucheng Yu, Christian Makaya .[SAFELearning: Enable Backdoor Detectability In Federated Learning With Secure Aggregation](https://arxiv.org/pdf/2102.02402) [J]. arXiv preprint arXiv:2102.02402.
- Felix Sattler, Tim Korjakow, Roman Rischke, Wojciech Samek .[FedAUX: Leveraging Unlabeled Auxiliary Data in Federated Learning](https://arxiv.org/pdf/2102.02514) [J]. arXiv preprint arXiv:2102.02514.
- Dimitris Stripelis, Jose Luis Ambite .[Semi-Synchronous Federated Learning](https://arxiv.org/pdf/2102.02849) [J]. arXiv preprint arXiv:2102.02849.
- Chunmei Xu, Shengheng Liu, Zhaohui Yang, Yongming Huang, Dusit Niyato, Kai-Kit Wong .[Learning Rate Optimization for Federated Learning Exploiting Over-the-air Computation](https://arxiv.org/pdf/2102.02946) [J]. arXiv preprint arXiv:2102.02946.
- Wenting Zou, Li Li, Zichen Xu, Chengzhong Xu .[DEAL: Decremental Energy-Aware Learning in a Federated System](https://arxiv.org/pdf/2102.03051) [J]. arXiv preprint arXiv:2102.03051.
- Alexandru Nelus, Rene Glitza, Rainer Martin .[Estimation of Microphone Clusters in Acoustic Sensor Networks using Unsupervised Federated Learning](https://arxiv.org/pdf/2102.03109) [J]. arXiv preprint arXiv:2102.03109.
- Tomoya Murata, Taiji Suzuki .[Bias-Variance Reduced Local SGD for Less Heterogeneous Federated Learning](https://arxiv.org/pdf/2102.03198) [J]. arXiv preprint arXiv:2102.03198.
- Tengchan Zeng, Omid Semiari, Mingzhe Chen, Walid Saad, Mehdi Bennis .[Federated Learning on the Road: Autonomous Controller Design for Connected and Autonomous Vehicles](https://arxiv.org/pdf/2102.03401) [J]. arXiv preprint arXiv:2102.03401.
- Karan Singhal, Hakim Sidahmed, Zachary Garrett, Shanshan Wu, Keith Rush, Sushant Prakash .[Federated Reconstruction: Partially Local Federated Learning](https://arxiv.org/pdf/2102.03448) [J]. arXiv preprint arXiv:2102.03448.
- Anirban Das, Stacy Patterson .[Multi-Tier Federated Learning for Vertically Partitioned Data](https://arxiv.org/pdf/2102.03620) [J]. arXiv preprint arXiv:2102.03620.
- An Xu, Heng Huang .[Double Momentum SGD for Federated Learning](https://arxiv.org/pdf/2102.03970) [J]. arXiv preprint arXiv:2102.03970.
- Rui Yin, Zhiqun Zou, Celimuge Wu, Jiantao Yuan, Xianfu Chen .[Distributed Spectrum and Power Allocation for D2D-U Networks: A Scheme based on NN and Federated Learning](https://arxiv.org/pdf/2102.04359) [J]. arXiv preprint arXiv:2102.04359.
- Xiaodong Cui, Songtao Lu, Brian Kingsbury .[Federated Acoustic Modeling For Automatic Speech Recognition](https://arxiv.org/pdf/2102.04429) [J]. arXiv preprint arXiv:2102.04429.
- Divyansh Jhunjhunwala, Advait Gadhikar, Gauri Joshi, Yonina C. Eldar .[Adaptive Quantization of Model Updates for Communication-Efficient Federated Learning](https://arxiv.org/pdf/2102.04487) [J]. arXiv preprint arXiv:2102.04487.
- Zhuoning Yuan, Zhishuai Guo, Yi Xu, Yiming Ying, Tianbao Yang .[Federated Deep AUC Maximization for Heterogeneous Data with a Constant Communication Complexity](https://arxiv.org/pdf/2102.04635) [J]. arXiv preprint arXiv:2102.04635.
- Yikai Zhang, Hui Qu, Qi Chang, Huidong Liu, Dimitris Metaxas, Chao Chen .[Training Federated GANs with Theoretical Guarantees: A Universal Aggregation Approach](https://arxiv.org/pdf/2102.04655) [J]. arXiv preprint arXiv:2102.04655.
- Muah Kim, Onur Günlü, Rafael F. Schaefer .[Federated Learning with Local Differential Privacy: Trade-offs between Privacy, Utility, and Communication](https://arxiv.org/pdf/2102.04737) [J]. arXiv preprint arXiv:2102.04737.
- Chuhan Wu, Fangzhao Wu, Yang Cao, Yongfeng Huang, Xing Xie .[FedGNN: Federated Graph Neural Network for Privacy-Preserving Recommendation](https://arxiv.org/pdf/2102.04925) [J]. arXiv preprint arXiv:2102.04925.
- Qian Yang, Jianyi Zhang, Weituo Hao, Gregory Spell, Lawrence Carin .[FLOP: Federated Learning on Medical Datasets using Partial Networks](https://arxiv.org/pdf/2102.05218) [J]. arXiv preprint arXiv:2102.05218.
- Ching Pui Wan, Qifeng Chen .[Robust Federated Learning with Attack-Adaptive Aggregation](https://arxiv.org/pdf/2102.05257) [J]. arXiv preprint arXiv:2102.05257.
- Omid Aramoon, Pin-Yu Chen, Gang Qu, Yuan Tian .[Meta Federated Learning](https://arxiv.org/pdf/2102.05561) [J]. arXiv preprint arXiv:2102.05561.
- Kai-Fung Chu, Lintao Zhang .[Privacy-Preserving Self-Taught Federated Learning for Heterogeneous Data](https://arxiv.org/pdf/2102.05883) [J]. arXiv preprint arXiv:2102.05883.
- Xingyu Li, Zhe Qu, Bo Tang, Zhuo Lu .[Stragglers Are Not Disaster: A Hybrid Federated Learning Algorithm with Delayed Gradients](https://arxiv.org/pdf/2102.06329) [J]. arXiv preprint arXiv:2102.06329.
- Charlie Hou, Kiran K. Thekumparampil, Giulia Fanti, Sewoong Oh .[Efficient Algorithms for Federated Saddle Point Optimization](https://arxiv.org/pdf/2102.06333) [J]. arXiv preprint arXiv:2102.06333.
- Peter Kairouz, Ziyu Liu, Thomas Steinke .[The Distributed Discrete Gaussian Mechanism for Federated Learning with Secure Aggregation](https://arxiv.org/pdf/2102.06387) [J]. arXiv preprint arXiv:2102.06387.
- Konstantin Mishchenko, Ahmed Khaled, Peter Richtárik .[Proximal and Federated Random Reshuffling](https://arxiv.org/pdf/2102.06704) [J]. arXiv preprint arXiv:2102.06704.
- Dmitriy Dovzhenko (1 and 2), Maksim Lednev (1), Konstantin Mochalov (3), Ivan Vaskan (3 and 4), Pavel Samokhvalov (1), Yury Rakovich (5), Igor Nabiev (1 and 6) ((1) National Research Nuclear University MEPhI (Moscow Engineering Physics Institute) Moscow, Russian Federation, (2) Department of Physics and Astronomy, University of Southampton, Southampton, United Kingdom, (3) Shemyakin-Ovchinnikov Institute of Bioorganic Chemistry, Russian Academy of Sciences, 117997 Moscow, Russian Federation, (4) Moscow Institute of Physics and Technology, Dolgoprudny, Moscow, Russian Federation, (5) IKERBASQUE, Basque Foundation for Science, Bilbao, Donostia International Physics Center, Poliimeros y Materiales Avanzados: Fisica, Quimica y Tecnologia, UPVEHU, Centro de Fisica de Materiales (MPC, CSIC-UPV/EHU) Donostia - San Sebastian, Spain, (6) Laboratoire de Recherche en Nanosciences, Universite de Reims Champagne-Ardenne, Reims, France) .[Strong exciton-photon coupling with colloidal quantum dots in a tuneable microcavity](https://arxiv.org/pdf/2102.07013) [J]. arXiv preprint arXiv:2102.07013.
- Lyutianyang Zhang, Hao Yin, Zhanke Zhou, Sumit Roy, Yaping Sun .[Enhancing WiFi Multiple Access Performance with Federated Deep Reinforcement Learning](https://arxiv.org/pdf/2102.07019) [J]. arXiv preprint arXiv:2102.07019.
- Aritra Mitra, Rayana Jaafar, George J. Pappas, Hamed Hassani .[Achieving Linear Convergence in Federated Learning under Objective and Systems Heterogeneity](https://arxiv.org/pdf/2102.07053) [J]. arXiv preprint arXiv:2102.07053.
- Liam Collins, Hamed Hassani, Aryan Mokhtari, Sanjay Shakkottai .[Exploiting Shared Representations for Personalized Federated Learning](https://arxiv.org/pdf/2102.07078) [J]. arXiv preprint arXiv:2102.07078.
- Canh T. Dinh, Tung T. Vu, Nguyen H. Tran, Minh N. Dao, Hongyu Zhang .[FedU: A Unified Framework for Federated Multi-Task Learning with Laplacian Regularization](https://arxiv.org/pdf/2102.07148) [J]. arXiv preprint arXiv:2102.07148.
- Ahmet M. Elbir, Sinem Coleri, Kumar Vijay Mishra .[Federated Dropout Learning for Hybrid Beamforming With Spatial Path Index Modulation In Multi-User mmWave-MIMO Systems](https://arxiv.org/pdf/2102.07450) [J]. arXiv preprint arXiv:2102.07450.
- Ahmed M. Abdelmoniem, Chen-Yu Ho, Pantelis Papageorgiou, Muhammad Bilal, Marco Canini .[On the Impact of Device and Behavioral Heterogeneity in Federated Learning](https://arxiv.org/pdf/2102.07500) [J]. arXiv preprint arXiv:2102.07500.
- 【FedBN】Xiaoxiao Li, Meirui Jiang, Xiaofei Zhang, Michael Kamp, Qi Dou .[FedBN: Federated Learning on Non-IID Features via Local Batch Normalization](https://arxiv.org/pdf/2102.07623) [J]. arXiv preprint arXiv:2102.07623.
- Xinchi Qiu, Titouan Parcollet, Javier Fernandez-Marques, Pedro Porto Buarque de Gusmao, Daniel J. Beutel, Taner Topal, Akhil Mathur, Nicholas D. Lane .[A first look into the carbon footprint of federated learning](https://arxiv.org/pdf/2102.07627) [J]. arXiv preprint arXiv:2102.07627.
- Junshan Zhang, Na Li, Mehmet Dedeoglu .[Federated Learning over Wireless Networks: A Band-limited Coordinated Descent Approach](https://arxiv.org/pdf/2102.07972) [J]. arXiv preprint arXiv:2102.07972.
- Jinjin Xu, Yaochu Jin, Wenli Du, Sai Gu .[A Federated Data-Driven Evolutionary Algorithm](https://arxiv.org/pdf/2102.08288) [J]. arXiv preprint arXiv:2102.08288.
- Dimitris Stripelis, Jose Luis Ambite, Pradeep Lam, Paul Thompson .[Scaling Neuroscience Research using Federated Learning](https://arxiv.org/pdf/2102.08440) [J]. arXiv preprint arXiv:2102.08440.
- Matthias Paulik, Matt Seigel, Henry Mason, Dominic Telaar, Joris Kluivers, Rogier van Dalen, Chi Wai Lau, Luke Carlson, Filip Granqvist, Chris Vandevelde, Sudeep Agarwal, Julien Freudiger, Andrew Byde, Abhishek Bhowmick, Gaurav Kapoor, Si Beaumont, Áine Cahill, Dominic Hughes, Omid Javidbakht, Fei Dong, Rehan Rishi, Stanley Hung .[Federated Evaluation and Tuning for On-Device Personalization: System Design & Applications](https://arxiv.org/pdf/2102.08503) [J]. arXiv preprint arXiv:2102.08503.
- David S. Johnson, Wolfgang Lorenz, Michael Taenzer, Stylianos Mimilakis, Sascha Grollmisch, Jakob Abeßer, Hanna Lukashevich .[DESED-FL and URBAN-FL: Federated Learning Datasets for Sound Event Detection](https://arxiv.org/pdf/2102.08833) [J]. arXiv preprint arXiv:2102.08833.
- Xiaohang Xu, Hao Peng, Lichao Sun, Yan Niu, Hongyuan Ma, Lianzhong Liu, Lifang He .[Federated Depression Detection from Multi-SourceMobile Health Data](https://arxiv.org/pdf/2102.09342) [J]. arXiv preprint arXiv:2102.09342.
- Afaf Taik, Zoubeir Mlika, Soumaya Cherkaoui .[Data-Aware Device Scheduling for Federated Edge Learning](https://arxiv.org/pdf/2102.09491) [J]. arXiv preprint arXiv:2102.09491.
- Filip Hanzely, Boxin Zhao, Mladen Kolar .[Personalized Federated Learning: A Unified Framework and Universal Optimization Techniques](https://arxiv.org/pdf/2102.09743) [J]. arXiv preprint arXiv:2102.09743.
- Bowen Zhao, Ximeng Liu, Wei-neng Chen .[When Crowdsensing Meets Federated Learning: Privacy-Preserving Mobile Crowdsensing System](https://arxiv.org/pdf/2102.10109) [J]. arXiv preprint arXiv:2102.10109.
- Dimitrios Michael Manias, Abdallah Shami .[Making a Case for Federated Learning in the Internet of Vehicles and Intelligent Transportation Systems](https://arxiv.org/pdf/2102.10142) [J]. arXiv preprint arXiv:2102.10142.
- Seyedehsara Nayer, Namrata Vaswani .[Fast and Sample-Efficient Federated Low Rank Matrix Recovery from Column-wise Linear and Quadratic Projections](https://arxiv.org/pdf/2102.10217) [J]. arXiv preprint arXiv:2102.10217.
- Xinghan Wang, Xiaoxiong Zhong, Yuanyuan Yang, Tingting Yang .[CFLMEC: Cooperative Federated Learning for Mobile Edge Computing](https://arxiv.org/pdf/2102.10591) [J]. arXiv preprint arXiv:2102.10591.
- Sina Rezaei Aghdam, Ehsan Amid, Marija Furdek, Alexandre Graell i Amat .[Privacy-Preserving Wireless Federated Learning Exploiting Inherent Hardware Impairments](https://arxiv.org/pdf/2102.10639) [J]. arXiv preprint arXiv:2102.10639.
- Yuwen Cao, Setareh Maghsudi, Tomoaki Ohtsuki .[Mobility-Aware Routing and Caching: A Federated Learning Assisted Approach](https://arxiv.org/pdf/2102.10743) [J]. arXiv preprint arXiv:2102.10743.
- Hang Liu, Xiaojun Yuan, Ying-Jun Angela Zhang .[CSIT-Free Federated Edge Learning via Reconfigurable Intelligent Surface](https://arxiv.org/pdf/2102.10749) [J]. arXiv preprint arXiv:2102.10749.
- Krishna Yadav, B.B Gupta .[Clustering Algorithm to Detect Adversaries in Federated Learning](https://arxiv.org/pdf/2102.10799) [J]. arXiv preprint arXiv:2102.10799.
- Jeongmin Chae, Songnam Hong .[Multiple Kernel-Based Online Federated Learning](https://arxiv.org/pdf/2102.10861) [J]. arXiv preprint arXiv:2102.10861.
- Qinqing Zheng, Shuxiao Chen, Qi Long, Weijie J. Su .[Federated $f$-Differential Privacy](https://arxiv.org/pdf/2102.11158) [J]. arXiv preprint arXiv:2102.11158.
- Basak Guler, Aylin Yener .[Sustainable Federated Learning](https://arxiv.org/pdf/2102.11274) [J]. arXiv preprint arXiv:2102.11274.
- Ahmet M. Elbir, Anastasios K. Papazafeiropoulos, Symeon Chatzinotas .[Federated Learning for Physical Layer Design](https://arxiv.org/pdf/2102.11777) [J]. arXiv preprint arXiv:2102.11777.
- Kaan Ozkara, Navjot Singh, Deepesh Data, Suhas Diggavi .[QuPeL: Quantized Personalization with Applications to Federated Learning](https://arxiv.org/pdf/2102.11786) [J]. arXiv preprint arXiv:2102.11786.
- Eoin Brophy, Maarten De Vos, Geraldine Boylan, Tomas Ward .[Estimation of Continuous Blood Pressure from PPG via a Federated Learning Approach](https://arxiv.org/pdf/2102.12245) [J]. arXiv preprint arXiv:2102.12245.
- Qunsong Zeng, Yuqing Du, Kaibin Huang .[Wirelessly Powered Federated Edge Learning: Optimal Tradeoffs Between Convergence and Power Transfer](https://arxiv.org/pdf/2102.12357) [J]. arXiv preprint arXiv:2102.12357.
- Yuyang Deng, Mohammad Mahdi Kamani, Mehrdad Mahdavi .[Distributionally Robust Federated Averaging](https://arxiv.org/pdf/2102.12660) [J]. arXiv preprint arXiv:2102.12660.
- Konstantinos Demertzis .[Blockchained Federated Learning for Threat Defense](https://arxiv.org/pdf/2102.12746) [J]. arXiv preprint arXiv:2102.12746.
- Shaoxiong Ji, Teemu Saravirta, Shirui Pan, Guodong Long, Anwar Walid .[Emerging Trends in Federated Learning: From Model Fusion to Federated X Learning](https://arxiv.org/pdf/2102.12920) [J]. arXiv preprint arXiv:2102.12920.
- Chengshuai Shi, Cong Shen, Jing Yang .[Federated Multi-armed Bandits with Personalization](https://arxiv.org/pdf/2102.13101) [J]. arXiv preprint arXiv:2102.13101.
- Ranwa Al Mallah, Godwin Badu-Marfo, Bilal Farooq .[Cybersecurity Threats in Connected and Automated Vehicles based Federated Learning Systems](https://arxiv.org/pdf/2102.13256) [J]. arXiv preprint arXiv:2102.13256.
- Jie Zhao, Xinghua Zhu, Jianzong Wang, Jing Xiao .[Efficient Client Contribution Evaluation for Horizontal Federated Learning](https://arxiv.org/pdf/2102.13314) [J]. arXiv preprint arXiv:2102.13314.
- Samuel Horvath, Stefanos Laskaridis, Mario Almeida, Ilias Leontiadis, Stylianos I. Venieris, Nicholas D. Lane .[FjORD: Fair and Accurate Federated Learning under heterogeneous targets with Ordered Dropout](https://arxiv.org/pdf/2102.13451) [J]. arXiv preprint arXiv:2102.13451.
- Yong Liu, Xinghua Zhu, Jianzong Wang, Jing Xiao .[A Quantitative Metric for Privacy Leakage in Federated Learning](https://arxiv.org/pdf/2102.13472) [J]. arXiv preprint arXiv:2102.13472.
- Yulin Shao, Deniz Gunduz, Soung Chang Liew .[Federated Edge Learning with Misaligned Over-The-Air Computation](https://arxiv.org/pdf/2102.13604) [J]. arXiv preprint arXiv:2102.13604.
- Morgan Ekmefjord, Addi Ait-Mlouk, Sadi Alawadi, Mattias Åkesson, Desislava Stoyanova, Ola Spjuth, Salman Toor, Andreas Hellander .[Scalable federated machine learning with FEDn](https://arxiv.org/pdf/2103.00148) [J]. arXiv preprint arXiv:2103.00148.
- Raouf Kerkouche, Gergely Ács, Claude Castelluccia, Pierre Genevès .[Constrained Differentially Private Federated Learning for Low-bandwidth Devices](https://arxiv.org/pdf/2103.00342) [J]. arXiv preprint arXiv:2103.00342.
- Wanli Ni, Yuanwei Liu, Zhaohui Yang, Hui Tian, Xuemin Shen .[Integrating Over-the-Air Federated Learning and Non-Orthogonal Multiple Access: What Role can RIS Play?](https://arxiv.org/pdf/2103.00435) [J]. arXiv preprint arXiv:2103.00435.
- Roozbeh Yousefzadeh .[Federated Learning without Revealing the Decision Boundaries](https://arxiv.org/pdf/2103.00695) [J]. arXiv preprint arXiv:2103.00695.
- Don Kurian Dennis, Tian Li, Virginia Smith .[Heterogeneity for the Win: One-Shot Federated Clustering](https://arxiv.org/pdf/2103.00697) [J]. arXiv preprint arXiv:2103.00697.
- Xiao Guo, Xiang Li, Xiangyu Chang, Shusen Wang, Zhihua Zhang .[Privacy-Preserving Distributed SVD via Federated Power](https://arxiv.org/pdf/2103.00704) [J]. arXiv preprint arXiv:2103.00704.
- Alysa Ziying Tan, Han Yu, Lizhen Cui, Qiang Yang .[Towards Personalized Federated Learning](https://arxiv.org/pdf/2103.00710) [J]. arXiv preprint arXiv:2103.00710.
- Qingsong Zhang, Bin Gu, Cheng Deng, Heng Huang .[Secure Bilevel Asynchronous Vertical Federated Learning with Backward Updating](https://arxiv.org/pdf/2103.00958) [J]. arXiv preprint arXiv:2103.00958.
- Rui Wang, Heju Li, Erwu Liu .[Blockchain-Based Federated Learning in Mobile Edge Networks with Application in Internet of Vehicles](https://arxiv.org/pdf/2103.01116) [J]. arXiv preprint arXiv:2103.01116.
- Devansh Shah, Parijat Dube, Supriyo Chakraborty, Ashish Verma .[Adversarial training in communication constrained federated learning](https://arxiv.org/pdf/2103.01319) [J]. arXiv preprint arXiv:2103.01319.
- Hyun-Suk Lee, Jang-Won Lee .[Adaptive Transmission Scheduling in Wireless Networks for Asynchronous Federated Learning](https://arxiv.org/pdf/2103.01422) [J]. arXiv preprint arXiv:2103.01422.
- Bingyan Liu, Yao Guo, Xiangqun Chen .[PFA: Privacy-preserving Federated Adaptation for Effective Model Personalization](https://arxiv.org/pdf/2103.01548) [J]. arXiv preprint arXiv:2103.01548.
- Shuxiao Chen, Qinqing Zheng, Qi Long, Weijie J. Su .[A Theorem of the Alternative for Personalized Federated Learning](https://arxiv.org/pdf/2103.01901) [J]. arXiv preprint arXiv:2103.01901.
- Mohamed Seif, Wei-Ting Chang, Ravi Tandon .[Privacy Amplification for Federated Learning via User Sampling and Wireless Aggregation](https://arxiv.org/pdf/2103.01953) [J]. arXiv preprint arXiv:2103.01953.
- Pengfei Guo, Puyang Wang, Jinyuan Zhou, Shanshan Jiang, Vishal M. Patel .[Multi-institutional Collaborations for Improving Deep Learning-based Magnetic Resonance Image Reconstruction Using Federated Learning](https://arxiv.org/pdf/2103.02148) [J]. arXiv preprint arXiv:2103.02148.
- Dian Fan, Xiaojun Yuan, Ying-Jun Angela Zhang .[Temporal-Structure-Assisted Gradient Aggregation for Over-the-Air Federated Edge Learning](https://arxiv.org/pdf/2103.02270) [J]. arXiv preprint arXiv:2103.02270.
- Bahador Bakhshi, Josep Mangues-Bafalluy .[R-Learning Based Admission Control for Service Federation in Multi-domain 5G Networks](https://arxiv.org/pdf/2103.02964) [J]. arXiv preprint arXiv:2103.02964.
- Avrim Blum, Nika Haghtalab, Richard Lanas Phillips, Han Shao .[One for One, or All for All: Equilibria and Optimality of Collaboration in Federated Learning](https://arxiv.org/pdf/2103.03228) [J]. arXiv preprint arXiv:2103.03228.
- Chuanhong Liu, Caili Guo, Yang Yang, Mingzhe Chen, H. Vincent Poor, Shuguang Cui .[Optimization of User Selection and Bandwidth Allocation for Federated Learning in VLC/RF Systems](https://arxiv.org/pdf/2103.03444) [J]. arXiv preprint arXiv:2103.03444.
- Nhan H. Pham, Lam M. Nguyen, Dzung T. Phan, Quoc Tran-Dinh .[Federated Learning with Randomized Douglas-Rachford Splitting Methods](https://arxiv.org/pdf/2103.03452) [J]. arXiv preprint arXiv:2103.03452.
- Cosmin I. Bercea, Benedikt Wiestler, Daniel Rueckert, Shadi Albarqouni .[FedDis: Disentangled Federated Learning for Unsupervised Brain Pathology Segmentation](https://arxiv.org/pdf/2103.03705) [J]. arXiv preprint arXiv:2103.03705.
- Zijian Zhang, Shuai Wang, Yuncong Hong, Liangkai Zhou, Qi Hao .[Distributed Dynamic Map Fusion via Federated Learning for Intelligent Networked Vehicles](https://arxiv.org/pdf/2103.03786) [J]. arXiv preprint arXiv:2103.03786.
- Runhua Xu, Nathalie Baracaldo, Yi Zhou, Ali Anwar, James Joshi, Heiko Ludwig .[FedV: Privacy-Preserving Federated Learning over Vertically Partitioned Data](https://arxiv.org/pdf/2103.03918) [J]. arXiv preprint arXiv:2103.03918.
- Aviv Shamsian, Aviv Navon, Ethan Fetaya, Gal Chechik .[Personalized Federated Learning using Hypernetworks](https://arxiv.org/pdf/2103.04628) [J]. arXiv preprint arXiv:2103.04628.
- Zachary Charles, Jakub Konečný .[Convergence and Accuracy Trade-Offs in Federated Learning and Meta-Learning](https://arxiv.org/pdf/2103.05032) [J]. arXiv preprint arXiv:2103.05032.
- Javier Rojo, Juan Hernandez, Juan Manuel Murillo, Jose Garcia-Alonso .[Blockchains' federation for integrating distributed health data using a patient-centered approach](https://arxiv.org/pdf/2103.05406) [J]. arXiv preprint arXiv:2103.05406.
- Quande Liu, Cheng Chen, Jing Qin, Qi Dou, Pheng-Ann Heng .[FedDG: Federated Domain Generalization on Medical Image Segmentation via Episodic Learning in Continuous Frequency Space](https://arxiv.org/pdf/2103.06030) [J]. arXiv preprint arXiv:2103.06030.
- Zhenyi Lin, Xiaoyang Li, Vincent K. N. Lau, Yi Gong, Kaibin Huang .[Deploying Federated Learning in Large-Scale Cellular Networks: Spatial Convergence Analysis](https://arxiv.org/pdf/2103.06056) [J]. arXiv preprint arXiv:2103.06056.
- Xiaoqing Tan, Chung-Chou H. Chang, Lu Tang .[A Tree-based Federated Learning Approach for Personalized Treatment Effect Estimation from Heterogeneous Data Sources](https://arxiv.org/pdf/2103.06261) [J]. arXiv preprint arXiv:2103.06261.
- Aqeel Anwar, Arijit Raychowdhury .[Multi-Task Federated Reinforcement Learning with Adversaries](https://arxiv.org/pdf/2103.06473) [J]. arXiv preprint arXiv:2103.06473.
- Zebang Shen, Hamed Hassani, Satyen Kale, Amin Karbasi .[Federated Functional Gradient Boosting](https://arxiv.org/pdf/2103.06972) [J]. arXiv preprint arXiv:2103.06972.
- Renhao Lu, Weizhe Zhang, Qiong Li, Xiaoxiong Zhong, Athanasios V. Vasilakos .[Auction Based Clustered Federated Learning in Mobile Edge Computing System](https://arxiv.org/pdf/2103.07150) [J]. arXiv preprint arXiv:2103.07150.
- Pallika Kanani, Virendra J. Marathe, Daniel Peterson, Rave Harpaz, Steve Bright .[Private Cross-Silo Federated Learning for Extracting Vaccine Adverse Event Mentions](https://arxiv.org/pdf/2103.07491) [J]. arXiv preprint arXiv:2103.07491.
- Nicholas Malecki, Hye-young Paik, Aleksandar Ignjatovic, Alan Blair, Elisa Bertino .[Simeon -- Secure Federated Machine Learning Through Iterative Filtering](https://arxiv.org/pdf/2103.07704) [J]. arXiv preprint arXiv:2103.07704.
- Meghana Thiyyakat, Subramaniam Kalambur, Dinkar Sitaram .[Megha: Decentralized Global Fair Scheduling for Federated Clusters](https://arxiv.org/pdf/2103.08413) [J]. arXiv preprint arXiv:2103.08413.
- Chencheng Ye, Ying Cui .[Sample-based Federated Learning via Mini-batch SSCA](https://arxiv.org/pdf/2103.09506) [J]. arXiv preprint arXiv:2103.09506.
- Stefano Savazzi, Sanaz Kianoush, Vittorio Rampa, Mehdi Bennis .[A Framework for Energy and Carbon Footprint Analysis of Distributed and Federated Edge Learning](https://arxiv.org/pdf/2103.10346) [J]. arXiv preprint arXiv:2103.10346.
- Frank Po-Chen Lin, Seyyedali Hosseinalipour, Sheikh Shams Azam, Christopher G. Brinton, Nicolo Michelusi .[Two Timescale Hybrid Federated Learning with Cooperative D2D Local Model Aggregations](https://arxiv.org/pdf/2103.10481) [J]. arXiv preprint arXiv:2103.10481.
- Cheng Shen, Wanli Xue .[An Experiment Study on Federated LearningTestbed](https://arxiv.org/pdf/2103.10579) [J]. arXiv preprint arXiv:2103.10579.
- Quoc-Viet Pham, Ming Zeng, Rukhsana Ruby, Thien Huynh-The, Won-Joo Hwang .[UAV Communications for Sustainable Federated Learning](https://arxiv.org/pdf/2103.11073) [J]. arXiv preprint arXiv:2103.11073.
- Stefan Arnold, Dilara Yesilbas .[Demystifying the Effects of Non-Independence in Federated Learning](https://arxiv.org/pdf/2103.11226) [J]. arXiv preprint arXiv:2103.11226.
- Jingheng Zheng, Wanli Ni, Hui Tian .[QoS-Constrained Federated Learning Empowered by Intelligent Reflecting Surface](https://arxiv.org/pdf/2103.11551) [J]. arXiv preprint arXiv:2103.11551.
- George Pu, Yanlin Zhou, Dapeng Wu, Xiaolin Li .[Server Averaging for Federated Learning](https://arxiv.org/pdf/2103.11619) [J]. arXiv preprint arXiv:2103.11619.
- Haizhou Liu, Xuan Zhang, Hongbin Sun .[A Federated Learning Framework in Smart Grid: Securing Power Traces in Collaborative Learning](https://arxiv.org/pdf/2103.11870) [J]. arXiv preprint arXiv:2103.11870.
- Hongyi Zhang, Jan Bosch, Helena Holmström Olsson .[Real-time End-to-End Federated Learning: An Automotive Case Study](https://arxiv.org/pdf/2103.11879) [J]. arXiv preprint arXiv:2103.11879.
- Samuel Yen-Chi Chen, Shinjae Yoo .[Federated Quantum Machine Learning](https://arxiv.org/pdf/2103.12010) [J]. arXiv preprint arXiv:2103.12010.
- Xing Xu, Rongpeng Li, Zhifeng Zhao, Honggang Zhang .[The Gradient Convergence Bound of Federated Multi-Agent Reinforcement Learning with Efficient Communication](https://arxiv.org/pdf/2103.13026) [J]. arXiv preprint arXiv:2103.13026.
- Sangsu Lee, Xi Zheng, Jie Hua, Haris Vikalo, Christine Julien .[Opportunistic Federated Learning: An Exploration of Egocentric Collaboration for Pervasive Computing Applications](https://arxiv.org/pdf/2103.13266) [J]. arXiv preprint arXiv:2103.13266.
- Chit Wutyee Zaw, Shashi Raj Pandey, Kitae Kim, Choong Seon Hong .[Energy-aware Resource Management for Federated Learning in Multi-access Edge Computing Systems](https://arxiv.org/pdf/2103.13293) [J]. arXiv preprint arXiv:2103.13293.
- Minxue Tang, Xuefei Ning, Yitu Wang, Yu Wang, Yiran Chen .[FedGP: Correlation-Based Active Client Selection for Heterogeneous Federated Learning](https://arxiv.org/pdf/2103.13822) [J]. arXiv preprint arXiv:2103.13822.
- Lumin Liu, Jun Zhang, Shenghui Song, Khaled B. Letaief .[Hierarchical Quantized Federated Learning: Convergence Analysis and System Design](https://arxiv.org/pdf/2103.14272) [J]. arXiv preprint arXiv:2103.14272.
- Andreas Haupt, Vaikkunth Mugunthan .[Prior-Free Auctions for the Demand Side of Federated Learning](https://arxiv.org/pdf/2103.14375) [J]. arXiv preprint arXiv:2103.14375.
- Pavlos Papadopoulos, Will Abramson, Adam J. Hall, Nikolaos Pitropakis, William J. Buchanan .[Privacy and Trust Redefined in Federated Machine Learning](https://arxiv.org/pdf/2103.15753) [J]. arXiv preprint arXiv:2103.15753.
- Hadi Jamali-Rad, Mohammad Abdizadeh, Attila Szabo .[Federated Learning with Taskonomy for Non-IID Data](https://arxiv.org/pdf/2103.15947) [J]. arXiv preprint arXiv:2103.15947.
- Cheng Chen, Bhavya Kailkhura, Ryan Goldhahn, Yi Zhou .[Certifiably-Robust Federated Adversarial Learning via Randomized Smoothing](https://arxiv.org/pdf/2103.16031) [J]. arXiv preprint arXiv:2103.16031.
- Xin Fan, Yue Wang, Yan Huo, Zhi Tian .[1-Bit Compressive Sensing for Efficient Federated Learning Over the Air](https://arxiv.org/pdf/2103.16055) [J]. arXiv preprint arXiv:2103.16055.
- Qinbin Li, Bingsheng He, Dawn Song .[Model-Contrastive Federated Learning](https://arxiv.org/pdf/2103.16257) [J]. arXiv preprint arXiv:2103.16257.
- Georgios Th. Papadopoulos, Asterios Leonidis, Margherita Antona, Constantine Stephanidis .[User profile-driven large-scale multi-agent learning from demonstration in federated human-robot collaborative environments](https://arxiv.org/pdf/2103.16434) [J]. arXiv preprint arXiv:2103.16434.
- Lintao Li, Longwei Yang, Xin Guo, Yuanming Shi, Haiming Wang, Wei Chen, Khaled B. Letaief .[Delay Analysis of Wireless Federated Learning Based on Saddle Point Approximation and Large Deviation Theory](https://arxiv.org/pdf/2103.16994) [J]. arXiv preprint arXiv:2103.16994.
- Tomer Gafni, Nir Shlezinger, Kobi Cohen, Yonina C. Eldar, H. Vincent Poor .[Federated Learning: A Signal Processing Perspective](https://arxiv.org/pdf/2103.17150) [J]. arXiv preprint arXiv:2103.17150.
- Francesco Pase, Marco Giordani, Michele Zorzi .[On the Convergence Time of Federated Learning Over Wireless Networks Under Imperfect CSI](https://arxiv.org/pdf/2104.00331) [J]. arXiv preprint arXiv:2104.00331.
- Akihito Taya, Takayuki Nishio, Masahiro Morikura, Koji Yamamoto .[Decentralized and Model-Free Federated Learning: Consensus-Based Distillation in Function Space](https://arxiv.org/pdf/2104.00352) [J]. arXiv preprint arXiv:2104.00352.
- Chenyou Fan, Jianwei Huang .[Federated Few-Shot Learning with Adversarial Learning](https://arxiv.org/pdf/2104.00365) [J]. arXiv preprint arXiv:2104.00365.
- Daniele Romanini, Adam James Hall, Pavlos Papadopoulos, Tom Titcombe, Abbas Ismail, Tudor Cebere, Robert Sandmann, Robin Roehm, Michael A. Hoeh .[PyVertical: A Vertical Federated Learning Framework for Multi-headed SplitNN](https://arxiv.org/pdf/2104.00489) [J]. arXiv preprint arXiv:2104.00489.
- Qinyong Wang, Hongzhi Yin, Tong Chen, Junliang Yu, Alexander Zhou, Xiangliang Zhang .[Fast-adapting and Privacy-preserving Federated Recommender System](https://arxiv.org/pdf/2104.00919) [J]. arXiv preprint arXiv:2104.00919.
- Umair Qudus, Muhammad Saleem, Axel-Cyrille Ngonga Ngomo, Young-koo Lee .[An Empirical Evaluation of Cost-based Federated SPARQL Query Processing Engines](https://arxiv.org/pdf/2104.00984) [J]. arXiv preprint arXiv:2104.00984.
- Haijin Wang, Caomingzhe Si, Junhua Zhao .[A Federated Learning Framework for Non-Intrusive Load Monitoring](https://arxiv.org/pdf/2104.01618) [J]. arXiv preprint arXiv:2104.01618.
- Dinh C. Nguyen, Ming Ding, Quoc-Viet Pham, Pubudu N. Pathirana, Long Bao Le, Aruna Seneviratne, Jun Li, Dusit Niyato, H. Vincent Poor .[Federated Learning Meets Blockchain in Edge Computing: Opportunities and Challenges](https://arxiv.org/pdf/2104.01776) [J]. arXiv preprint arXiv:2104.01776.
- Aman Priyanshu, Rakshit Naidu .[FedPandemic: A Cross-Device Federated Learning Approach Towards Elementary Prognosis of Diseases During a Pandemic](https://arxiv.org/pdf/2104.01864) [J]. arXiv preprint arXiv:2104.01864.
- Jae Ro, Mingqing Chen, Rajiv Mathews, Mehryar Mohri, Ananda Theertha Suresh .[Communication-Efficient Agnostic Federated Averaging](https://arxiv.org/pdf/2104.02748) [J]. arXiv preprint arXiv:2104.02748.
- Akhil Mathur, Daniel J. Beutel, Pedro Porto Buarque de Gusmão, Javier Fernandez-Marques, Taner Topal, Xinchi Qiu, Titouan Parcollet, Yan Gao, Nicholas D. Lane .[On-device Federated Learning with Flower](https://arxiv.org/pdf/2104.03042) [J]. arXiv preprint arXiv:2104.03042.
- Afaf Taik, Boubakr Nour, Soumaya Cherkaoui .[Empowering Prosumer Communities in Smart Grid with Wireless Communications and Federated Edge Learning](https://arxiv.org/pdf/2104.03169) [J]. arXiv preprint arXiv:2104.03169.
- Xin Fan, Yue Wang, Yan Huo, Zhi Tian .[Joint Optimization of Communications and Federated Learning Over the Air](https://arxiv.org/pdf/2104.03490) [J]. arXiv preprint arXiv:2104.03490.
- Jinu Gong, Osvaldo Simeone, Joonhyuk Kang .[Bayesian Variational Federated Learning and Unlearning in Decentralized Networks](https://arxiv.org/pdf/2104.03834) [J]. arXiv preprint arXiv:2104.03834.
- Chunnan Wang, Bozhou Chen, Geng Li, Hongzhi Wang .[FL-AGCNS: Federated Learning Framework for Automatic Graph Convolutional Network Search](https://arxiv.org/pdf/2104.04141) [J]. arXiv preprint arXiv:2104.04141.
- Abdullatif Albaseer, Mohamed Abdallah, Ala Al-Fuqaha, Aiman Erbad .[Threshold-Based Data Exclusion Approach for Energy-Efficient Federated Edge Learning](https://arxiv.org/pdf/2104.05509) [J]. arXiv preprint arXiv:2104.05509.
- Ronghua Xu, Yu Chen .[Fed-DDM: A Federated Ledgers based Framework for Hierarchical Decentralized Data Marketplaces](https://arxiv.org/pdf/2104.05583) [J]. arXiv preprint arXiv:2104.05583.
- Chencheng Ye, Ying Cui .[Sample-based and Feature-based Federated Learning via Mini-batch SSCA](https://arxiv.org/pdf/2104.06011) [J]. arXiv preprint arXiv:2104.06011.
- Yuzhu Mao, Zihao Zhao, Guangfeng Yan, Yang Liu, Tian Lan, Linqi Song, Wenbo Ding .[Communication Efficient Federated Learning with Adaptive Quantization](https://arxiv.org/pdf/2104.06023) [J]. arXiv preprint arXiv:2104.06023.
- Sreya Francis, Irene Tenison, Irina Rish .[Towards Causal Federated Learning For Enhanced Robustness and Privacy](https://arxiv.org/pdf/2104.06557) [J]. arXiv preprint arXiv:2104.06557.
- Rui Shao, Pramuditha Perera, Pong C. Yuen, Vishal M. Patel .[Federated Generalized Face Presentation Attack Detection](https://arxiv.org/pdf/2104.06595) [J]. arXiv preprint arXiv:2104.06595.
- Heng Zhu, Qing Ling .[BROADCAST: Reducing Both Stochastic and Compression Noise to Robustify Communication-Efficient Federated Learning](https://arxiv.org/pdf/2104.06685) [J]. arXiv preprint arXiv:2104.06685.
- Jing Ma, Si-Ahmed Naas, Stephan Sigg, Xixiang Lyu .[Privacy-preserving Federated Learning based on Multi-key Homomorphic Encryption](https://arxiv.org/pdf/2104.06824) [J]. arXiv preprint arXiv:2104.06824.
- Cong Shen, Jie Xu, Sihui Zheng, Xiang Chen .[Resource Rationing for Wireless Federated Learning: Concept, Benefits, and Challenges](https://arxiv.org/pdf/2104.06990) [J]. arXiv preprint arXiv:2104.06990.
- Chaoyang He, Keshav Balasubramanian, Emir Ceyani, Yu Rong, Peilin Zhao, Junzhou Huang, Murali Annavaram, Salman Avestimehr .[FedGraphNN: A Federated Learning System and Benchmark for Graph Neural Networks](https://arxiv.org/pdf/2104.07145) [J]. arXiv preprint arXiv:2104.07145.
- Poojan Oza, Vishal M. Patel .[Federated Learning-based Active Authentication on Mobile Devices](https://arxiv.org/pdf/2104.07158) [J]. arXiv preprint arXiv:2104.07158.
- Aurélien Bellet, Anne-Marie Kermarrec, Erick Lavoie .[D-Cliques: Compensating NonIIDness in Decentralized Federated Learning with Topology](https://arxiv.org/pdf/2104.07365) [J]. arXiv preprint arXiv:2104.07365.
- Aiden Durrant, Milan Markovic, David Matthews, David May, Jessica Enright, Georgios Leontidis .[The Role of Cross-Silo Federated Learning in Facilitating Data Sharing in the Agri-Food Sector](https://arxiv.org/pdf/2104.07468) [J]. arXiv preprint arXiv:2104.07468.
- Li Li, Moming Duan, Duo Liu, Yu Zhang, Ao Ren, Xianzhang Chen, Yujuan Tan, Chengliang Wang .[FedSAE: A Novel Self-Adaptive Federated Learning Framework in Heterogeneous Systems](https://arxiv.org/pdf/2104.07515) [J]. arXiv preprint arXiv:2104.07515.
- Yuben Qu, Haipeng Dai, Yan Zhuang, Jiafa Chen, Chao Dong, Fan Wu, Song Guo .[Decentralized Federated Learning for UAV Networks: Architecture, Challenges, and Opportunities](https://arxiv.org/pdf/2104.07557) [J]. arXiv preprint arXiv:2104.07557.
- Dinh C. Nguyen, Ming Ding, Pubudu N. Pathirana, Aruna Seneviratne, Jun Li, H. Vincent Poor .[Federated Learning for Internet of Things: A Comprehensive Survey](https://arxiv.org/pdf/2104.07914) [J]. arXiv preprint arXiv:2104.07914.
- Bo Zhao, Peng Sun, Liming Fang, Tao Wang, Keyu Jiang .[FedCom: A Byzantine-Robust Local Model Aggregation Rule Using Data Commitment for Federated Learning](https://arxiv.org/pdf/2104.08020) [J]. arXiv preprint arXiv:2104.08020.
- Claudio Bettini, Gabriele Civitarese, Riccardo Presotto .[Personalized Semi-Supervised Federated Learning for Human Activity Recognition](https://arxiv.org/pdf/2104.08094) [J]. arXiv preprint arXiv:2104.08094.
- Zhao Wang, Yifan Hu, Jun Xiao, Chao Wu .[Efficient Ring-topology Decentralized Federated Learning with Deep Generative Models for Industrial Artificial Intelligent](https://arxiv.org/pdf/2104.08100) [J]. arXiv preprint arXiv:2104.08100.
- Yu Zhang, Moming Duan, Duo Liu, Li Li, Ao Ren, Xianzhang Chen, Yujuan Tan, Chengliang Wang .[CSAFL: A Clustered Semi-Asynchronous Federated Learning Framework](https://arxiv.org/pdf/2104.08184) [J]. arXiv preprint arXiv:2104.08184.
- Hossein Hosseini, Hyunsin Park, Sungrack Yun, Christos Louizos, Joseph Soriaga, Max Welling .[Federated Learning of User Verification Models Without Sharing Embeddings](https://arxiv.org/pdf/2104.08776) [J]. arXiv preprint arXiv:2104.08776.
- Bill Yuchen Lin, Chaoyang He, Zihang Zeng, Hulin Wang, Yufen Huang, Mahdi Soltanolkotabi, Xiang Ren, Salman Avestimehr .[FedNLP: A Research Platform for Federated Learning in Natural Language Processing](https://arxiv.org/pdf/2104.08815) [J]. arXiv preprint arXiv:2104.08815.
- Jianyang Ren, Wanli Ni, Gaofeng Nie, Hui Tian .[Research on Resource Allocation for Efficient Federated Learning](https://arxiv.org/pdf/2104.09177) [J]. arXiv preprint arXiv:2104.09177.
- Valerian Rey, Pedro Miguel Sánchez Sánchez, Alberto Huertas Celdrán, Gérôme Bovet, Martin Jaggi .[Federated Learning for Malware Detection in IoT Devices](https://arxiv.org/pdf/2104.09994) [J]. arXiv preprint arXiv:2104.09994.
- Yu Xianjia, Jorge Peña Queralta, Jukka Heikkonen, Tomi Westerlund .[An Overview of Federated Learning at the Edge and Distributed Ledger Technologies for Robotic and Autonomous Systems](https://arxiv.org/pdf/2104.10141) [J]. arXiv preprint arXiv:2104.10141.
- Yingda Xia, Dong Yang, Wenqi Li, Andriy Myronenko, Daguang Xu, Hirofumi Obinata, Hitoshi Mori, Peng An, Stephanie Harmon, Evrim Turkbey, Baris Turkbey, Bradford Wood, Francesca Patella, Elvira Stellato, Gianpaolo Carrafiello, Anna Ierardi, Alan Yuille, Holger Roth .[Auto-FedAvg: Learnable Federated Averaging for Multi-Institutional Medical Image Segmentation](https://arxiv.org/pdf/2104.10195) [J]. arXiv preprint arXiv:2104.10195.
- Irene Tenison, Sreya Francis, Irina Rish .[Gradient Masked Federated Optimization](https://arxiv.org/pdf/2104.10322) [J]. arXiv preprint arXiv:2104.10322.
- Chenxin Xu, Rong Xia, Yong Xiao, Yingyu Li, Guangming Shi, Kwang-cheng Chen .[Federated Traffic Synthesizing and Classification Using Generative Adversarial Networks](https://arxiv.org/pdf/2104.10400) [J]. arXiv preprint arXiv:2104.10400.
- Jiehan Zhou, Shouhua Zhang, Qinghua Lu, Wenbin Dai, Min Chen, Xin Liu, Susanna Pirttikangas, Yang Shi, Weishan Zhang, Enrique Herrera-Viedma .[A Survey on Federated Learning and its Applications for Accelerating Industrial Internet of Things](https://arxiv.org/pdf/2104.10501) [J]. arXiv preprint arXiv:2104.10501.
- Gabriele Costa, Fabio Pinelli, Simone Soderi, Gabriele Tolomei .[Covert Channel Attack to Federated Learning Systems](https://arxiv.org/pdf/2104.10561) [J]. arXiv preprint arXiv:2104.10561.
- Rajesh Kumar, WenYong Wang, Cheng Yuan, Jay Kumar, Zakria, He Qing, Ting Yang, Abdullah Aman Khan .[Blockchain based Privacy-Preserved Federated Learning for Medical Images: A Case Study of COVID-19 CT Scans](https://arxiv.org/pdf/2104.10903) [J]. arXiv preprint arXiv:2104.10903.
- Sheyda Zarandi, Hina Tabassum .[Federated Double Deep Q-learning for Joint Delay and Energy Minimization in IoT networks](https://arxiv.org/pdf/2104.11320) [J]. arXiv preprint arXiv:2104.11320.
- Tao Sun, Dongsheng Li, Bao Wang .[Decentralized Federated Averaging](https://arxiv.org/pdf/2104.11375) [J]. arXiv preprint arXiv:2104.11375.
- Saeedeh Parsaeefard, Sayed Ehsan Etesami, Alberto Leon Garcia .[Robust Federated Learning by Mixture of Experts](https://arxiv.org/pdf/2104.11700) [J]. arXiv preprint arXiv:2104.11700.
- Frank W. Bentrem, Michael A. Corsello, Joshua J. Palm .[Leveraging Sharing Communities to Achieve Federated Learning for Cybersecurity](https://arxiv.org/pdf/2104.11763) [J]. arXiv preprint arXiv:2104.11763.
- Pavlos S. Bouzinis, Panagiotis D. Diamantoulakis, George K. Karagiannidis .[Wireless Federated Learning (WFL) for 6G Networks -- Part II: The Compute-then-Transmit NOMA Paradigm](https://arxiv.org/pdf/2104.12005) [J]. arXiv preprint arXiv:2104.12005.
- Chen Zhao, Zhipeng Gao, Qian Wang, Kaile Xiao, Zijia Mo, M. Jamal Deen .[FedSup: A Communication-Efficient Federated Learning Fatigue Driving Behaviors Supervision Framework](https://arxiv.org/pdf/2104.12086) [J]. arXiv preprint arXiv:2104.12086.
- Zhefeng Qiao, Xianghao Yu, Jun Zhang, Khaled B. Letaief .[Communication-Efficient Federated Learning with Dual-Side Low-Rank Compression](https://arxiv.org/pdf/2104.12416) [J]. arXiv preprint arXiv:2104.12416.
- Sejin Seo, Seung-Woo Ko, Jihong Park, Seong-Lyun Kim, Mehdi Bennis .[Communication-Efficient and Personalized Federated Lottery Ticket Learning](https://arxiv.org/pdf/2104.12501) [J]. arXiv preprint arXiv:2104.12501.
- Longling Zhang, Bochen Shen, Ahmed Barnawi, Shan Xi, Neeraj Kumar, Yi Wu .[FedDPGAN: Federated Differentially Private Generative Adversarial Networks Framework for the Detection of COVID-19 Pneumonia](https://arxiv.org/pdf/2104.12581) [J]. arXiv preprint arXiv:2104.12581.
- Yuchang Sun, Jiawei Shao, Yuyi Mao, Jun Zhang .[Semi-Decentralized Federated Edge Learning for Fast Convergence on Non-IID Data](https://arxiv.org/pdf/2104.12678) [J]. arXiv preprint arXiv:2104.12678.
- José Mairton B. da Silva Jr., Konstantinos Ntougias, Ioannis Krikidis, Gábor Fodor, Carlo Fischione .[Simultaneous Wireless Information and Power Transfer for Federated Learning](https://arxiv.org/pdf/2104.12749) [J]. arXiv preprint arXiv:2104.12749.
- Syed Eqbal Alam, Fabian Wirth, Jia Yuan Yu .[Multi-resource allocation for federated settings: A non-homogeneous Markov chain model](https://arxiv.org/pdf/2104.12828) [J]. arXiv preprint arXiv:2104.12828.
- Yanjun Zhang, Guangdong Bai, Xue Li, Surya Nepal, Ryan K L Ko .[Confined Gradient Descent: Privacy-preserving Optimization for Federated Learning](https://arxiv.org/pdf/2104.13050) [J]. arXiv preprint arXiv:2104.13050.
- Mingrui Cao, Long Zhang, Bin Cao .[Towards On-Device Federated Learning: A Direct Acyclic Graph-based Blockchain Approach](https://arxiv.org/pdf/2104.13092) [J]. arXiv preprint arXiv:2104.13092.
- Shuo Yuan, Bin Cao, Yao Sun, Mugen Peng .[Secure and Efficient Federated Learning Through Layering and Sharding Blockchain](https://arxiv.org/pdf/2104.13130) [J]. arXiv preprint arXiv:2104.13130.
- Elsa Rizk, Ali H. Sayed .[A Graph Federated Architecture with Privacy Preserving Learning](https://arxiv.org/pdf/2104.13215) [J]. arXiv preprint arXiv:2104.13215.
- Weituo Hao, Mostafa El-Khamy, Jungwon Lee, Jianyi Zhang, Kevin J Liang, Changyou Chen, Lawrence Carin .[Towards Fair Federated Learning with Zero-Shot Data Augmentation](https://arxiv.org/pdf/2104.13417) [J]. arXiv preprint arXiv:2104.13417.
- Andreas Grammenos, Evangelia Kalyvianaki, Peter Pietzuch .[Pronto: Federated Task Scheduling](https://arxiv.org/pdf/2104.13429) [J]. arXiv preprint arXiv:2104.13429.
- Maha Aldosary, Norah Alqahtani .[Federated Identity Management (FIdM) Systems Limitation And Solutions](https://arxiv.org/pdf/2104.14018) [J]. arXiv preprint arXiv:2104.14018.
- Yan Gao, Titouan Parcollet, Salah Zaiem, Javier Fernandez-Marques, Pedro P. B. de Gusmao, Daniel J. Beutel, Nicholas D. Lane .[End-to-End Speech Recognition from Federated Acoustic Models](https://arxiv.org/pdf/2104.14297) [J]. arXiv preprint arXiv:2104.14297.
- Ji Liu, Jizhou Huang, Yang Zhou, Xuhong Li, Shilei Ji, Haoyi Xiong, Dejing Dou .[From Distributed Machine Learning to Federated Learning: A Survey](https://arxiv.org/pdf/2104.14362) [J]. arXiv preprint arXiv:2104.14362.
- Fan Mo, Hamed Haddadi, Kleomenis Katevas, Eduard Marin, Diego Perino, Nicolas Kourtellis .[PPFL: Privacy-preserving Federated Learning with Trusted Execution Environments](https://arxiv.org/pdf/2104.14380) [J]. arXiv preprint arXiv:2104.14380.
- Shuang Zhang, Liyao Xiang, Xi Yu, Pengzhi Chu, Yingqi Chen, Chen Cen, Li Wang .[Privacy-Preserving Federated Learning on Partitioned Attributes](https://arxiv.org/pdf/2104.14383) [J]. arXiv preprint arXiv:2104.14383.
- Debora Caldarola, Massimiliano Mancini, Fabio Galasso, Marco Ciccone, Emanuele Rodolà, Barbara Caputo .[Cluster-driven Graph Federated Learning over Multiple Domains](https://arxiv.org/pdf/2104.14628) [J]. arXiv preprint arXiv:2104.14628.
- Matei Moldoveanu, Abdellatif Zaidi .[On In-network learning. A Comparative Study with Federated and Split Learning](https://arxiv.org/pdf/2104.14929) [J]. arXiv preprint arXiv:2104.14929.
- Zheng Wang, Xiaoliang Fan, Jianzhong Qi, Chenglu Wen, Cheng Wang, Rongshan Yu .[Federated Learning with Fair Averaging](https://arxiv.org/pdf/2104.14937) [J]. arXiv preprint arXiv:2104.14937.
- Yue Tan, Guodong Long, Lu Liu, Tianyi Zhou, Qinghua Lu, Jing Jiang, Chengqi Zhang .[FedProto: Federated Prototype Learning over Heterogeneous Devices](https://arxiv.org/pdf/2105.00243) [J]. arXiv preprint arXiv:2105.00243.
- Hanchi Ren, Jingjing Deng, Xianghua Xie .[GRNN: Generative Regression Neural Network -- A Data Leakage Attack for Federated Learning](https://arxiv.org/pdf/2105.00529) [J]. arXiv preprint arXiv:2105.00529.
- Saeed Vahidian, Mahdi Morafah, Bill Lin .[Personalized Federated Learning by Structured and Unstructured Pruning under Data Heterogeneity](https://arxiv.org/pdf/2105.00562) [J]. arXiv preprint arXiv:2105.00562.
- Daniel Garcia Bernal, Lodovico Giaretta, Sarunas Girdzijauskas, Magnus Sahlgren .[Federated Word2Vec: Leveraging Federated Learning to Encourage Collaborative Representation Learning](https://arxiv.org/pdf/2105.00831) [J]. arXiv preprint arXiv:2105.00831.
- Pavlos S. Bouzinis, Panagiotis D. Diamantoulakis, George K. Karagiannidis .[Wireless Federated Learning (WFL) for 6G Networks -- Part I: Research Challenges and Future Trends](https://arxiv.org/pdf/2105.00842) [J]. arXiv preprint arXiv:2105.00842.
- Shuo Wan, Jiaxun Lu, Pingyi Fan, Yunfeng Shao, Chenghui Peng, Khaled B. letaief .[Convergence Analysis and System Design for Federated Learning over Wireless Networks](https://arxiv.org/pdf/2105.00872) [J]. arXiv preprint arXiv:2105.00872.
- Sicong Che, Hao Peng, Lichao Sun, Yong Chen, Lifang He .[Federated Multi-View Learning for Private Medical Data Integration and Analysis](https://arxiv.org/pdf/2105.01603) [J]. arXiv preprint arXiv:2105.01603.
- Tianhao Wu, Mingzhi Jiang, Yinhui Han, Zheng Yuan, Lin Zhang .[Density-Aware Federated Imitation Learning for Connected and Automated Vehicles with Unsignalized Intersection](https://arxiv.org/pdf/2105.01889) [J]. arXiv preprint arXiv:2105.01889.
- Fan Bai, Jiaxiang Wu, Pengcheng Shen, Shaoxin Li, Shuigeng Zhou .[Federated Face Recognition](https://arxiv.org/pdf/2105.02501) [J]. arXiv preprint arXiv:2105.02501.
- Fang-Qi Li, Shi-Lin Wang, Alan Wee-Chung Liew .[Towards Practical Watermark for Deep Neural Networks in Federated Learning](https://arxiv.org/pdf/2105.03167) [J]. arXiv preprint arXiv:2105.03167.
- Chuan Chen, Weibo Hu, Ziyue Xu, Zibin Zheng .[FedGL: Federated Graph Learning Framework with Global Self-Supervision](https://arxiv.org/pdf/2105.03170) [J]. arXiv preprint arXiv:2105.03170.
- Ahmet M. Elbir, Sinem Coleri .[A Family of Hybrid Federated and Centralized Learning Architectures in Machine Learning](https://arxiv.org/pdf/2105.03288) [J]. arXiv preprint arXiv:2105.03288.
- Pengyuan Zhou, Pei Fang, Pan Hui .[Loss Tolerant Federated Learning](https://arxiv.org/pdf/2105.03591) [J]. arXiv preprint arXiv:2105.03591.
- Mauro Piva, Gaia Maselli, Francesco Restuccia .[The Tags Are Alright: Robust Large-Scale RFID Clone Detection Through Federated Data-Augmented Radio Fingerprinting](https://arxiv.org/pdf/2105.03671) [J]. arXiv preprint arXiv:2105.03671.
- Lorenzo Minto, Moritz Haller, Hamed Haddadi, Benjamin Livshits .[Stronger Privacy for Federated Collaborative Filtering with Implicit Feedback](https://arxiv.org/pdf/2105.03941) [J]. arXiv preprint arXiv:2105.03941.
- Pengcheng Ren, Tongjiang Yan .[Latency Analysis of Consortium Blockchained Federated Learning](https://arxiv.org/pdf/2105.04087) [J]. arXiv preprint arXiv:2105.04087.
- Laizhong Cui, Xiaoxin Su, Yipeng Zhou, Yi Pan .[Slashing Communication Traffic in Federated Learning by Transmitting Clustered Model Updates](https://arxiv.org/pdf/2105.04153) [J]. arXiv preprint arXiv:2105.04153.
- Efthymios Tzinis, Jonah Casebeer, Zhepei Wang, Paris Smaragdis .[Separate but Together: Unsupervised Federated Learning for Speech Enhancement from Non-IID Data](https://arxiv.org/pdf/2105.04727) [J]. arXiv preprint arXiv:2105.04727.
- Chang Li, Hua Ouyang .[Federated Unbiased Learning to Rank](https://arxiv.org/pdf/2105.04761) [J]. arXiv preprint arXiv:2105.04761.
- Baihe Huang, Xiaoxiao Li, Zhao Song, Xin Yang .[FL-NTK: A Neural Tangent Kernel-based Framework for Federated Learning Convergence Analysis](https://arxiv.org/pdf/2105.05001) [J]. arXiv preprint arXiv:2105.05001.
- Lunchen Xie, Jiaqi Liu, Songtao Lu, Tsung-hui Chang, Qingjiang Shi .[An Efficient Learning Framework For Federated XGBoost Using Secret Sharing And Distributed Optimization](https://arxiv.org/pdf/2105.05717) [J]. arXiv preprint arXiv:2105.05717.
- Julian Matschinske, Julian Späth, Reza Nasirigerdeh, Reihaneh Torkzadehmahani, Anne Hartebrodt, Balázs Orbán, Sándor Fejér, Olga Zolotareva, Mohammad Bakhtiari, Béla Bihari, Marcus Bloice, Nina C Donner, Walid Fdhila, Tobias Frisch, Anne-Christin Hauschild, Dominik Heider, Andreas Holzinger, Walter Hötzendorfer, Jan Hospes, Tim Kacprowski, Markus Kastelitz, Markus List, Rudolf Mayer, Mónika Moga, Heimo Müller, Anastasia Pustozerova, Richard Röttger, Anna Saranti, Harald HHW Schmidt, Christof Tschohl, Nina K Wenke, Jan Baumbach .[The FeatureCloud AI Store for Federated Learning in Biomedicine and Beyond](https://arxiv.org/pdf/2105.05734) [J]. arXiv preprint arXiv:2105.05734.
- Sarthak Pati, Ujjwal Baid, Maximilian Zenk, Brandon Edwards, Micah Sheller, G. Anthony Reina, Patrick Foley, Alexey Gruzdev, Jason Martin, Shadi Albarqouni, Yong Chen, Russell Taki Shinohara, Annika Reinke, David Zimmerer, John B. Freymann, Justin S. Kirby, Christos Davatzikos, Rivka R. Colen, Aikaterini Kotrotsou, Daniel Marcus, Mikhail Milchenko, Arash Nazeri, Hassan Fathallah-Shaykh, Roland Wiest, Andras Jakab, Marc-Andre Weber, Abhishek Mahajan, Lena Maier-Hein, Jens Kleesiek, Bjoern Menze, Klaus Maier-Hein, Spyridon Bakas .[The Federated Tumor Segmentation (FeTS) Challenge](https://arxiv.org/pdf/2105.05874) [J]. arXiv preprint arXiv:2105.05874.
- Yann Fraboni, Richard Vidal, Laetitia Kameni, Marco Lorenzi .[Clustered Sampling: Low-Variance and Improved Representativity for Clients Selection in Federated Learning](https://arxiv.org/pdf/2105.05883) [J]. arXiv preprint arXiv:2105.05883.
- Chuan Ma, Jun Li, Ming Ding, Kang Wei, Wen Chen, H. Vincent Poor .[Federated Learning with Unreliable Clients: Performance Analysis and Mechanism Design](https://arxiv.org/pdf/2105.06256) [J]. arXiv preprint arXiv:2105.06256.
- G Anthony Reina, Alexey Gruzdev, Patrick Foley, Olga Perepelkina, Mansi Sharma, Igor Davidyuk, Ilya Trushkin, Maksim Radionov, Aleksandr Mokrov, Dmitry Agapov, Jason Martin, Brandon Edwards, Micah J. Sheller, Sarthak Pati, Prakash Narayana Moorthy, Shih-han Wang, Prashant Shah, Spyridon Bakas .[OpenFL: An open-source framework for Federated Learning](https://arxiv.org/pdf/2105.06413) [J]. arXiv preprint arXiv:2105.06413.
- Hongda Wu, Ping Wang .[Node Selection Toward Faster Convergence for Federated Learning on Non-IID Data](https://arxiv.org/pdf/2105.07066) [J]. arXiv preprint arXiv:2105.07066.
- Weiming Zhuang, Xin Gan, Yonggang Wen, Shuai Zhang .[EasyFL: A Low-code Federated Learning Platform For Dummies](https://arxiv.org/pdf/2105.07603) [J]. arXiv preprint arXiv:2105.07603.
- Weiming Zhuang, Xin Gan, Yonggang Wen, Xuesen Zhang, Shuai Zhang, Shuai Yi .[Towards Unsupervised Domain Adaptation for Deep Face Recognition under Privacy Constraints via Federated Learning](https://arxiv.org/pdf/2105.07606) [J]. arXiv preprint arXiv:2105.07606.
- Hao Peng, Haoran Li, Yangqiu Song, Vincent Zheng, Jianxin Li .[Differentially Private Federated Knowledge Graphs Embedding](https://arxiv.org/pdf/2105.07615) [J]. arXiv preprint arXiv:2105.07615.
- Marc C. Green, Mark D. Plumbley .[Federated Learning With Highly Imbalanced Audio Data](https://arxiv.org/pdf/2105.08550) [J]. arXiv preprint arXiv:2105.08550.
- Jiahui Geng, Neel Kanwal, Martin Gilje Jaatun, Chunming Rong .[DID-eFed: Facilitating Federated Learning as a Service with Decentralized Identities](https://arxiv.org/pdf/2105.08671) [J]. arXiv preprint arXiv:2105.08671.
- Di Chai, Leye Wang, Lianzhi Fu, Junxue Zhang, Kai Chen, Qiang Yang .[Federated Singular Vector Decomposition](https://arxiv.org/pdf/2105.08925) [J]. arXiv preprint arXiv:2105.08925.
- Umberto Michieli, Mete Ozay .[Prototype Guided Federated Learning of Visual Feature Representations](https://arxiv.org/pdf/2105.08982) [J]. arXiv preprint arXiv:2105.08982.
- Aashish Kolluri, Teodora Baluta, Prateek Saxena .[Private Hierarchical Clustering in Federated Networks](https://arxiv.org/pdf/2105.09057) [J]. arXiv preprint arXiv:2105.09057.
- Rajitha Hathurusinghe, Isar Nejadgholi, Miodrag Bolic .[A Privacy-Preserving Approach to Extraction of Personal Information through Automatic Annotation and Federated Learning](https://arxiv.org/pdf/2105.09198) [J]. arXiv preprint arXiv:2105.09198.
- Aidmar Wainakh, Fabrizio Ventola, Till Müßig, Jens Keim, Carlos Garcia Cordero, Ephraim Zimmer, Tim Grube, Kristian Kersting, Max Mühlhäuser .[User Label Leakage from Gradients in Federated Learning](https://arxiv.org/pdf/2105.09369) [J]. arXiv preprint arXiv:2105.09369.
- Pau-Chen Cheng, Kevin Eykholt, Zhongshu Gu, Hani Jamjoom, K. R. Jayaram, Enriquillo Valdez, Ashish Verma .[Separation of Powers in Federated Learning](https://arxiv.org/pdf/2105.09400) [J]. arXiv preprint arXiv:2105.09400.
- Ruikang Zhong, Xiao Liu, Yuanwei Liu, Yue Chen, Zhu Han .[Mobile Reconfigurable Intelligent Surfaces for NOMA Networks: Federated Learning Approaches](https://arxiv.org/pdf/2105.09462) [J]. arXiv preprint arXiv:2105.09462.
- Minh-Duc Hoang, Linh Le, Anh-Tuan Nguyen, Trang Le, Hoang D. Nguyen .[Federated Artificial Intelligence for Unified Credit Assessment](https://arxiv.org/pdf/2105.09484) [J]. arXiv preprint arXiv:2105.09484.
- Xiaolin Chen, Shuai Zhou, Kai Yang, Hao Fan, Zejin Feng, Zhong Chen, Hu Wang, Yongji Wang .[Fed-EINI: An Efficient and Interpretable Inference Framework for Decision Tree Ensembles in Federated Learning](https://arxiv.org/pdf/2105.09540) [J]. arXiv preprint arXiv:2105.09540.
- Latif U. Khan, Yan Kyaw Tun, Madyan Alsenwi, Muhammad Imran, Zhu Han, Choong Seon Hong .[A Dispersed Federated Learning Framework for 6G-Enabled Autonomous Driving Cars](https://arxiv.org/pdf/2105.09641) [J]. arXiv preprint arXiv:2105.09641.
- Zhuangdi Zhu, Junyuan Hong, Jiayu Zhou .[Data-Free Knowledge Distillation for Heterogeneous Federated Learning](https://arxiv.org/pdf/2105.10056) [J]. arXiv preprint arXiv:2105.10056.
- Abdullah M. Alqahtani, Barzan Yosuf, Sanaa H. Mohamed, Taisir E.H. El-Gorashi, Jaafar M.H. Elmirghani .[Energy Minimized Federated Fog Computing over Passive Optical Networks](https://arxiv.org/pdf/2105.10242) [J]. arXiv preprint arXiv:2105.10242.
- Reza Nasirigerdeh, Reihaneh Torkzadehmahani, Julian Matschinske, Jan Baumbach, Daniel Rueckert, Georgios Kaissis .[HyFed: A Hybrid Federated Framework for Privacy-preserving Machine Learning](https://arxiv.org/pdf/2105.10545) [J]. arXiv preprint arXiv:2105.10545.
- Shaoming Huang, Yong Zhou, Ting Wang, Yuanming Shi .[Byzantine-Resilient Federated Machine Learning via Over-the-Air Computation](https://arxiv.org/pdf/2105.10883) [J]. arXiv preprint arXiv:2105.10883.
- Milad Khademi Nori, Sangseok Yun, Il-Min Kim .[Fast Federated Learning by Balancing Communication Trade-Offs](https://arxiv.org/pdf/2105.11028) [J]. arXiv preprint arXiv:2105.11028.
- Haijin Wang, Caomingzhe Si, Junhua Zhao, Guolong Liu, Fushuan Wen .[Fed-NILM: A Federated Learning-based Non-Intrusive Load Monitoring Method for Privacy-Protection](https://arxiv.org/pdf/2105.11085) [J]. arXiv preprint arXiv:2105.11085.
- Huanding Zhang, Tao Shen, Fei Wu, Mingyang Yin, Hongxia Yang, Chao Wu .[Federated Graph Learning -- A Position Paper](https://arxiv.org/pdf/2105.11099) [J]. arXiv preprint arXiv:2105.11099.
- Fan Lai, Yinwei Dai, Xiangfeng Zhu, Mosharaf Chowdhury .[FedScale: Benchmarking Model and System Performance of Federated Learning](https://arxiv.org/pdf/2105.11367) [J]. arXiv preprint arXiv:2105.11367.
- Ali Raza, Kim Phuc Tran, Ludovic Koehl, Shujun Li .[Designing ECG Monitoring Healthcare System with Federated Transfer Learning and Explainable AI](https://arxiv.org/pdf/2105.12497) [J]. arXiv preprint arXiv:2105.12497.
- Yasmin SarcheshmehPour, Yu Tian, Linli Zhang, Alexander Jung .[Networked Federated Multi-Task Learning](https://arxiv.org/pdf/2105.12769) [J]. arXiv preprint arXiv:2105.12769.
- Hao Zhao, Fei Ji, Quansheng Guan, Qiang Li, Shuai Wang, Hefeng Dong, Miaowen Wen .[Federated Meta Learning Enhanced Acoustic Radio Cooperative Framework for Ocean of Things Underwater Acoustic Communications](https://arxiv.org/pdf/2105.13296) [J]. arXiv preprint arXiv:2105.13296.
- Fernando E. Casado, Dylan Lema, Marcos F. Criado, Roberto Iglesias, Carlos V. Regueiro, Senén Barro .[Concept drift detection and adaptation for federated and continual learning](https://arxiv.org/pdf/2105.13309) [J]. arXiv preprint arXiv:2105.13309.
- Christopher Briggs, Zhong Fan, Peter Andras .[Federated Learning for Short-term Residential Energy Demand Forecasting](https://arxiv.org/pdf/2105.13325) [J]. arXiv preprint arXiv:2105.13325.
- Jiahao Xie, Chao Zhang, Yunsong Zhang, Zebang Shen, Hui Qian .[A Federated Learning Framework for Nonconvex-PL Minimax Problems](https://arxiv.org/pdf/2105.14216) [J]. arXiv preprint arXiv:2105.14216.
- Qian Chen, Zilong Wang, Wenjing Zhang, Xiaodong Lin .[PPT: A Privacy-Preserving Global Model Training Protocol for Federated Learning in P2P Networks](https://arxiv.org/pdf/2105.14408) [J]. arXiv preprint arXiv:2105.14408.
- Lun Wang, Qi Pang, Shuai Wang, Dawn Song .[FED-$χ^2$: Privacy Preserving Federated Correlation Test](https://arxiv.org/pdf/2105.14618) [J]. arXiv preprint arXiv:2105.14618.
- Dinh C. Nguyen, Ming Ding, Pubudu N. Pathirana, Aruna Seneviratne, Jun Li, Dusit Niyato, H. Vincent Poor .[Federated Learning for Industrial Internet of Things in Future Industries](https://arxiv.org/pdf/2105.14659) [J]. arXiv preprint arXiv:2105.14659.
- Huanle Zhang, Jeonghoon Kim .[Towards a Federated Learning Framework for Heterogeneous Devices of Internet of Things](https://arxiv.org/pdf/2105.14675) [J]. arXiv preprint arXiv:2105.14675.
- Xiumei Deng, Jun Li, Chuan Ma, Kang Wei, Long Shi, Ming Ding, Wen Chen, H. Vincent Poor .[On Dynamic Resource Allocation for Blockchain Assisted Federated Learning over Wireless Channels](https://arxiv.org/pdf/2105.14708) [J]. arXiv preprint arXiv:2105.14708.
- Anis Elgabli, Chaouki Ben Issaid, Amrit S. Bedi, Mehdi Bennis, Vaneet Aggarwal .[Energy-Efficient and Federated Meta-Learning via Projected Stochastic Gradient Ascent](https://arxiv.org/pdf/2105.14772) [J]. arXiv preprint arXiv:2105.14772.
- Siddharth Divi, Habiba Farrukh, Berkay Celik .[Unifying Distillation with Personalization in Federated Learning](https://arxiv.org/pdf/2105.15191) [J]. arXiv preprint arXiv:2105.15191.
- Mahdi Chehimi, Walid Saad .[Quantum Federated Learning with Quantum Data](https://arxiv.org/pdf/2106.00005) [J]. arXiv preprint arXiv:2106.00005.
- He Yang .[H-FL: A Hierarchical Communication-Efficient and Privacy-Protected Architecture for Federated Learning](https://arxiv.org/pdf/2106.00275) [J]. arXiv preprint arXiv:2106.00275.
- Thanh Vinh Vo, Trong Nghia Hoang, Young Lee, Tze-Yun Leong .[Federated Estimation of Causal Effects from Observational Data](https://arxiv.org/pdf/2106.00456) [J]. arXiv preprint arXiv:2106.00456.
- Yuxuan Sun, Sheng Zhou, Zhisheng Niu, Deniz Gündüz .[Dynamic Scheduling for Over-the-Air Federated Edge Learning with Energy Constraints](https://arxiv.org/pdf/2106.00490) [J]. arXiv preprint arXiv:2106.00490.
- Amir Sonee, Stefano Rini, Yu-Chih Huang .[Wireless Federated Learning with Limited Communication and Differential Privacy](https://arxiv.org/pdf/2106.00564) [J]. arXiv preprint arXiv:2106.00564.
- Chenglin Li, Di Niu, Bei Jiang, Xiao Zuo, Jianming Yang .[Meta-HAR: Federated Representation Learning for Human Activity Recognition](https://arxiv.org/pdf/2106.00615) [J]. arXiv preprint arXiv:2106.00615.
- Maxime Vono, Vincent Plassier, Alain Durmus, Aymeric Dieuleveut, Eric Moulines .[QLSD: Quantised Langevin stochastic dynamics for Bayesian federated learning](https://arxiv.org/pdf/2106.00797) [J]. arXiv preprint arXiv:2106.00797.
- Yiqiang Chen, Wang Lu, Jindong Wang, Xin Qin .[FedHealth 2: Weighted Federated Transfer Learning via Batch Normalization for Personalized Healthcare](https://arxiv.org/pdf/2106.01009) [J]. arXiv preprint arXiv:2106.01009.
- Xiaochun Niu, Ermin Wei .[FedHybrid: A Hybrid Primal-Dual Algorithm Framework for Federated Optimization](https://arxiv.org/pdf/2106.01279) [J]. arXiv preprint arXiv:2106.01279.
- Enmao Diao, Jie Ding, Vahid Tarokh .[SemiFL: Communication Efficient Semi-Supervised Federated Learning with Unlabeled Clients](https://arxiv.org/pdf/2106.01432) [J]. arXiv preprint arXiv:2106.01432.
- Jianyu Wang, Zheng Xu, Zachary Garrett, Zachary Charles, Luyang Liu, Gauri Joshi .[Local Adaptivity in Federated Learning: Convergence and Consistency](https://arxiv.org/pdf/2106.02305) [J]. arXiv preprint arXiv:2106.02305.
- Sung Kuk Shyn, Donghee Kim, Kwangsu Kim .[FedCCEA : A Practical Approach of Client Contribution Evaluation for Federated Learning](https://arxiv.org/pdf/2106.02310) [J]. arXiv preprint arXiv:2106.02310.
- Chaoyang He, Emir Ceyani, Keshav Balasubramanian, Murali Annavaram, Salman Avestimehr .[SpreadGNN: Serverless Multi-task Federated Learning for Graph Neural Networks](https://arxiv.org/pdf/2106.02743) [J]. arXiv preprint arXiv:2106.02743.
- Mher Safaryan, Rustem Islamov, Xun Qian, Peter Richtárik .[FedNL: Making Newton-Type Methods Applicable to Federated Learning](https://arxiv.org/pdf/2106.02969) [J]. arXiv preprint arXiv:2106.02969.
- Gihun Lee, Yongjin Shin, Minchan Jeong, Se-Young Yun .[Preservation of the Global Knowledge by Not-True Self Knowledge Distillation in Federated Learning](https://arxiv.org/pdf/2106.03097) [J]. arXiv preprint arXiv:2106.03097.
- Jinhyun So, Ramy E. Ali, Basak Guler, Jiantao Jiao, Salman Avestimehr .[Securing Secure Aggregation: Mitigating Multi-Round Privacy Leakage in Federated Learning](https://arxiv.org/pdf/2106.03328) [J]. arXiv preprint arXiv:2106.03328.
- Alexandru Nelus, Rene Glitza, Rainer Martin .[Unsupervised Clustered Federated Learning in Complex Multi-source Acoustic Environments](https://arxiv.org/pdf/2106.03671) [J]. arXiv preprint arXiv:2106.03671.
- Xinran Gu, Kaixuan Huang, Jingzhao Zhang, Longbo Huang .[Fast Federated Learning in the Presence of Arbitrary Device Unavailability](https://arxiv.org/pdf/2106.04159) [J]. arXiv preprint arXiv:2106.04159.
- Shuyuan Zheng, Yang Cao, Masatoshi Yoshikawa .[Incentive Mechanism for Privacy-Preserving Federated Learning](https://arxiv.org/pdf/2106.04384) [J]. arXiv preprint arXiv:2106.04384.
- Vasileios Perifanis, Pavlos S. Efraimidis .[Federated Neural Collaborative Filtering](https://arxiv.org/pdf/2106.04405) [J]. arXiv preprint arXiv:2106.04405.
- Mikhail Khodak, Renbo Tu, Tian Li, Liam Li, Maria-Florina Balcan, Virginia Smith, Ameet Talwalkar .[Federated Hyperparameter Tuning: Challenges, Baselines, and Connections to Weight-Sharing](https://arxiv.org/pdf/2106.04502) [J]. arXiv preprint arXiv:2106.04502.
- Mi Luo, Fei Chen, Dapeng Hu, Yifan Zhang, Jian Liang, Jiashi Feng .[No Fear of Heterogeneity: Classifier Calibration for Federated Learning with Non-IID Data](https://arxiv.org/pdf/2106.05001) [J]. arXiv preprint arXiv:2106.05001.
- Chuizheng Meng, Sirisha Rambhatla, Yan Liu .[Cross-Node Federated Graph Neural Network for Spatio-Temporal Data Modeling](https://arxiv.org/pdf/2106.05223) [J]. arXiv preprint arXiv:2106.05223.
- Chandra Thapa, Kallol Krishna Karmakar, Alberto Huertas Celdran, Seyit Camtepe, Vijay Varadharajan, Surya Nepal .[FedDICE: A ransomware spread detection in a distributed integrated clinical environment using federated learning and SDN based mitigation](https://arxiv.org/pdf/2106.05434) [J]. arXiv preprint arXiv:2106.05434.
- Vaikkunth Mugunthan, Pawan Goyal, Lalana Kagal .[Multi-VFL: A Vertical Federated Learning System for Multiple Data and Label Owners](https://arxiv.org/pdf/2106.05468) [J]. arXiv preprint arXiv:2106.05468.
- Jiankai Sun, Xin Yang, Yuanshun Yao, Aonan Zhang, Weihao Gao, Junyuan Xie, Chong Wang .[Vertical Federated Learning without Revealing Intersection Membership](https://arxiv.org/pdf/2106.05508) [J]. arXiv preprint arXiv:2106.05508.
- Jaehoon Oh, Sangmook Kim, Se-Young Yun .[FedBABU: Towards Enhanced Representation for Federated Image Classification](https://arxiv.org/pdf/2106.06042) [J]. arXiv preprint arXiv:2106.06042.
- Liangqiong Qu, Yuyin Zhou, Paul Pu Liang, Yingda Xia, Feifei Wang, Li Fei-Fei, Ehsan Adeli, Daniel Rubin .[Rethinking Architecture Design for Tackling Data Heterogeneity in Federated Learning](https://arxiv.org/pdf/2106.06047) [J]. arXiv preprint arXiv:2106.06047.
- Maximilian Lam, Gu-Yeon Wei, David Brooks, Vijay Janapa Reddi, Michael Mitzenmacher .[Gradient Disaggregation: Breaking Privacy in Federated Learning by Reconstructing the User Participant Matrix](https://arxiv.org/pdf/2106.06089) [J]. arXiv preprint arXiv:2106.06089.
- Minseok Ryu, Kibaek Kim .[Differentially Private Federated Learning via Inexact ADMM](https://arxiv.org/pdf/2106.06127) [J]. arXiv preprint arXiv:2106.06127.
- Zhaomin Wu, Qinbin Li, Bingsheng He .[Exploiting Record Similarity for Practical Vertical Federated Learning](https://arxiv.org/pdf/2106.06312) [J]. arXiv preprint arXiv:2106.06312.
- Yeshwanth Venkatesha, Youngeun Kim, Leandros Tassiulas, Priyadarshini Panda .[Federated Learning with Spiking Neural Networks](https://arxiv.org/pdf/2106.06579) [J]. arXiv preprint arXiv:2106.06579.
- Li Chou, Zichang Liu, Zhuang Wang, Anshumali Shrivastava .[Efficient and Less Centralized Federated Learning](https://arxiv.org/pdf/2106.06627) [J]. arXiv preprint arXiv:2106.06627.
- John Nguyen, Kshitiz Malik, Hongyuan Zhan, Ashkan Yousefpour, Michael Rabbat, Mani Malek, Dzmitry Huba .[Federated Learning with Buffered Asynchronous Aggregation](https://arxiv.org/pdf/2106.06639) [J]. arXiv preprint arXiv:2106.06639.
- Madhusanka Manimel Wadu, Sumudu Samarakoon, Mehdi Bennis .[Joint Client Scheduling and Resource Allocation under Channel Uncertainty in Federated Learning](https://arxiv.org/pdf/2106.06796) [J]. arXiv preprint arXiv:2106.06796.
- Hangyu Zhu, Jinjin Xu, Shiqing Liu, Yaochu Jin .[Federated Learning on Non-IID Data: A Survey](https://arxiv.org/pdf/2106.06843) [J]. arXiv preprint arXiv:2106.06843.
- Sixing Yu, Phuong Nguyen, Ali Anwar, Ali Jannesari .[Adaptive Dynamic Pruning for Non-IID Federated Learning](https://arxiv.org/pdf/2106.06921) [J]. arXiv preprint arXiv:2106.06921.
- Shunfeng Chu, Jun Li, Jianxin Wang, Zhe Wang, Ming Ding, Yijin Zang, Yuwen Qian, Wen Chen .[Federated Learning Over Wireless Channels: Dynamic Resource Allocation and Task Scheduling](https://arxiv.org/pdf/2106.06934) [J]. arXiv preprint arXiv:2106.06934.
- Yaowei Han, Yang Cao, Masatoshi Yoshikawa .[Understanding the Interplay between Privacy and Robustness in Federated Learning](https://arxiv.org/pdf/2106.07033) [J]. arXiv preprint arXiv:2106.07033.
- Rudrajit Das, Abolfazl Hashemi, Sujay Sanghavi, Inderjit S. Dhillon .[DP-NormFedAvg: Normalizing Client Updates for Privacy-Preserving Federated Learning](https://arxiv.org/pdf/2106.07094) [J]. arXiv preprint arXiv:2106.07094.
- Haibo Yang, Jia Liu, Elizabeth S. Bentley .[CFedAvg: Achieving Efficient Communication and Fast Convergence in Non-IID Federated Learning](https://arxiv.org/pdf/2106.07155) [J]. arXiv preprint arXiv:2106.07155.
- Chuyang Ke, Jean Honorio .[Federated Myopic Community Detection with One-shot Communication](https://arxiv.org/pdf/2106.07255) [J]. arXiv preprint arXiv:2106.07255.
- Aleksandr Beznosikov, Vadim Sushko, Abdurakhmon Sadiev, Alexander Gasnikov .[Decentralized Personalized Federated Min-Max Problems](https://arxiv.org/pdf/2106.07289) [J]. arXiv preprint arXiv:2106.07289.
- Dimitrios Dimitriadis, Kenichi Kumatani, Robert Gmyr, Yashesh Gaur, Sefik Emre Eskimez .[Dynamic Gradient Aggregation for Federated Domain Adaptation](https://arxiv.org/pdf/2106.07578) [J]. arXiv preprint arXiv:2106.07578.
- Yu Zhang, Guoming Tang, Qianyi Huang, Yi Wang, Xudong Wang, Jiadong Lou .[FedNILM: Applying Federated Learning to NILM Applications at the Edge](https://arxiv.org/pdf/2106.07751) [J]. arXiv preprint arXiv:2106.07751.
- Zachary Charles, Zachary Garrett, Zhouyuan Huo, Sergei Shmulyian, Virginia Smith .[On Large-Cohort Training for Federated Learning](https://arxiv.org/pdf/2106.07820) [J]. arXiv preprint arXiv:2106.07820.
- Tuo Zhang, Chaoyang He, Tianhao Ma, Mark Ma, Salman Avestimehr .[Federated Learning for Internet of Things: A Federated Learning Framework for On-device Anomaly Data Detection](https://arxiv.org/pdf/2106.07976) [J]. arXiv preprint arXiv:2106.07976.
- Yandong Shi, Yong Zhou, Yuanming Shi .[Over-the-Air Decentralized Federated Learning](https://arxiv.org/pdf/2106.08011) [J]. arXiv preprint arXiv:2106.08011.
- Théo Jourdan, Antoine Boutet, Carole Frindel .[Privacy Assessment of Federated Learning using Private Personalized Layers](https://arxiv.org/pdf/2106.08060) [J]. arXiv preprint arXiv:2106.08060.
- Chulin Xie, Minghao Chen, Pin-Yu Chen, Bo Li .[CRFL: Certifiably Robust Federated Learning against Backdoor Attacks](https://arxiv.org/pdf/2106.08283) [J]. arXiv preprint arXiv:2106.08283.
- Wanli Ni, Yuanwei Liu, Yonina C. Eldar, Zhaohui Yang, Hui Tian .[STAR-RIS Enabled Heterogeneous Networks: Ubiquitous NOMA Communication and Pervasive Federated Learning](https://arxiv.org/pdf/2106.08592) [J]. arXiv preprint arXiv:2106.08592.
- Quande Liu, Hongzheng Yang, Qi Dou, Pheng-Ann Heng .[Federated Semi-supervised Medical Image Classification via Inter-client Relation Matching](https://arxiv.org/pdf/2106.08600) [J]. arXiv preprint arXiv:2106.08600.
- Rami Hamdi, Mingzhe Chen, Ahmed Ben Said, Marwa Qaraqe, H. Vincent Poor .[Federated Learning over Energy Harvesting Wireless Networks](https://arxiv.org/pdf/2106.08809) [J]. arXiv preprint arXiv:2106.08809.
- Xiaopeng Jiang, Shuai Zhao, Guy Jacobson, Rittwik Jana, Wen-Ling Hsu, Manoop Talasila, Syed Anwar Aftab, Yi Chen, Cristian Borcea .[FGLP: A Federated Fine-Grained Location Prediction System for Mobile Users](https://arxiv.org/pdf/2106.08946) [J]. arXiv preprint arXiv:2106.08946.
- Qi Xia, Qun Li .[QuantumFed: A Federated Learning Framework for Collaborative Quantum Training](https://arxiv.org/pdf/2106.09109) [J]. arXiv preprint arXiv:2106.09109.
- Joonyoung Song, Jong Chul Ye .[Federated CycleGAN for Privacy-Preserving Image-to-Image Translation](https://arxiv.org/pdf/2106.09246) [J]. arXiv preprint arXiv:2106.09246.
- Yuris Mulya Saputra, Diep N. Nguyen, Dinh Thai Hoang, Eryk Dutkiewicz .[Coded Federated Learning Framework for AI-Based Mobile Application Services with Privacy-Awareness](https://arxiv.org/pdf/2106.09261) [J]. arXiv preprint arXiv:2106.09261.
- Xiaowen Cao, Guangxu Zhu, Jie Xu, Zhiqin Wang, and Shuguang Cui .[Optimized Power Control Design for Over-the-Air Federated Edge Learning](https://arxiv.org/pdf/2106.09316) [J]. arXiv preprint arXiv:2106.09316.
- Yanmeng Wang, Yanqing Xu, Qingjiang Shi, Tsung-Hui Chang .[Quantized Federated Learning under Transmission Delay and Outage Constraints](https://arxiv.org/pdf/2106.09397) [J]. arXiv preprint arXiv:2106.09397.
- Zichen Ma, Yu Lu, Zihan Lu, Wenye Li, Jinfeng Yi, Shuguang Cui .[Towards Heterogeneous Clients with Elastic Federated Learning](https://arxiv.org/pdf/2106.09433) [J]. arXiv preprint arXiv:2106.09433.
- Shaashwat Agrawal, Sagnik Sarkar, Ons Aouedi, Gokul Yenduri, Kandaraj Piamrat, Sweta Bhattacharya, Praveen Kumar Reddy Maddikunta, Thippa Reddy Gadekallu .[Federated Learning for Intrusion Detection System: Concepts, Challenges and Future Directions](https://arxiv.org/pdf/2106.09527) [J]. arXiv preprint arXiv:2106.09527.
- Kate Donahue, Jon Kleinberg .[Optimality and Stability in Federated Learning: A Game-theoretic Approach](https://arxiv.org/pdf/2106.09580) [J]. arXiv preprint arXiv:2106.09580.
- Andrew Lowy, Meisam Razaviyayn .[Locally Differentially Private Federated Learning: Efficient Algorithms with Tight Risk Bounds](https://arxiv.org/pdf/2106.09779) [J]. arXiv preprint arXiv:2106.09779.
- Gautham Krishna Gudur, Satheesh K. Perepu .[Zero-Shot Federated Learning with New Classes for Audio Classification](https://arxiv.org/pdf/2106.10019) [J]. arXiv preprint arXiv:2106.10019.
- Wensheng Xia, Ying Li, Lan Zhang, Zhonghai Wu, Xiaoyong Yuan .[A Vertical Federated Learning Framework for Horizontally Partitioned Labels](https://arxiv.org/pdf/2106.10056) [J]. arXiv preprint arXiv:2106.10056.
- Junyuan Hong, Haotao Wang, Zhangyang Wang, Jiayu Zhou .[Federated Robustness Propagation: Sharing Adversarial Robustness in Federated Learning](https://arxiv.org/pdf/2106.10196) [J]. arXiv preprint arXiv:2106.10196.
- Prashant Khanduri, Pranay Sharma, Haibo Yang, Mingyi Hong, Jia Liu, Ketan Rajawat, Pramod K. Varshney .[STEM: A Stochastic Two-Sided Momentum Algorithm Achieving Near-Optimal Sample and Communication Complexities for Federated Learning](https://arxiv.org/pdf/2106.10435) [J]. arXiv preprint arXiv:2106.10435.
- Nhan Khanh Le, Yang Liu, Quang Minh Nguyen, Qingchen Liu, Fangzhou Liu, Quanwei Cai, Sandra Hirche .[FedXGBoost: Privacy-Preserving XGBoost for Federated Learning](https://arxiv.org/pdf/2106.10662) [J]. arXiv preprint arXiv:2106.10662.
- Jiyue Huang, Chi Hong, Lydia Y. Chen, Stefanie Roos .[Is Shapley Value fair? Improving Client Selection for Mavericks in Federated Learning](https://arxiv.org/pdf/2106.10734) [J]. arXiv preprint arXiv:2106.10734.
- Jing Xu, Sen Wang, Liwei Wang, Andrew Chi-Chih Yao .[FedCM: Federated Learning with Client-level Momentum](https://arxiv.org/pdf/2106.10874) [J]. arXiv preprint arXiv:2106.10874.
- Xinyang Lin, Hanting Chen, Yixing Xu, Chao Xu, Xiaolin Gui, Yiping Deng, Yunhe Wang .[Federated Learning with Positive and Unlabeled Data](https://arxiv.org/pdf/2106.10904) [J]. arXiv preprint arXiv:2106.10904.
- Feihu Huang, Junyi Li, Heng Huang .[Compositional Federated Learning: Applications in Distributionally Robust Averaging and Meta Learning](https://arxiv.org/pdf/2106.11264) [J]. arXiv preprint arXiv:2106.11264.
- Sin Kit Lo, Qinghua Lu, Hye-Young Paik, Liming Zhu .[FLRA: A Reference Architecture for Federated Learning Systems](https://arxiv.org/pdf/2106.11570) [J]. arXiv preprint arXiv:2106.11570.
- Xiang Ni, Xiaolong Xu, Lingjuan Lyu, Changhua Meng, Weiqiang Wang .[A Vertical Federated Learning Framework for Graph Convolutional Network](https://arxiv.org/pdf/2106.11593) [J]. arXiv preprint arXiv:2106.11593.
- Ning Zhang, Qian Ma, Xu Chen .[Enabling Long-Term Cooperation in Cross-Silo Federated Learning: A Repeated Game Perspective](https://arxiv.org/pdf/2106.11814) [J]. arXiv preprint arXiv:2106.11814.
- Jinjin Xu, Yaochu Jin, Wenli Du .[A Federated Data-Driven Evolutionary Algorithm for Expensive Multi/Many-objective Optimization](https://arxiv.org/pdf/2106.12086) [J]. arXiv preprint arXiv:2106.12086.
- Hua Huang, Fanhua Shang, Yuanyuan Liu, Hongying Liu .[Behavior Mimics Distribution: Combining Individual and Group Behaviors for Federated Learning](https://arxiv.org/pdf/2106.12300) [J]. arXiv preprint arXiv:2106.12300.
- Abdullatif Albaseer, Mohamed Abdallah, Ala Al-Fuqaha, Aiman Erbad .[Fine-Grained Data Selection for Improved Energy Efficiency of Federated Edge Learning](https://arxiv.org/pdf/2106.12561) [J]. arXiv preprint arXiv:2106.12561.
- Kang Wei, Jun Li, Chuan Ma, Ming Ding, Cailian Chen, Shi Jin, Zhu Han, H. Vincent Poor .[Low-Latency Federated Learning over Wireless Channels with Differential Privacy](https://arxiv.org/pdf/2106.13039) [J]. arXiv preprint arXiv:2106.13039.
- Xueyang Tang, Song Guo, Jingcai Guo .[Personalized Federated Learning with Clustered Generalization](https://arxiv.org/pdf/2106.13044) [J]. arXiv preprint arXiv:2106.13044.
- Yuchen Li, Yifan Bao, Liyao Xiang, Junhan Liu, Cen Chen, Li Wang, Xinbing Wang .[Privacy Threats Analysis to Secure Federated Learning](https://arxiv.org/pdf/2106.13076) [J]. arXiv preprint arXiv:2106.13076.
- Li Li, Huazhu Fu, Bo Han, Cheng-Zhong Xu, Ling Shao .[Federated Noisy Client Learning](https://arxiv.org/pdf/2106.13239) [J]. arXiv preprint arXiv:2106.13239.
- Han Xie, Jing Ma, Li Xiong, Carl Yang .[Federated Graph Classification over Non-IID Graphs](https://arxiv.org/pdf/2106.13423) [J]. arXiv preprint arXiv:2106.13423.
- Ke Zhang, Carl Yang, Xiaoxiao Li, Lichao Sun, Siu Ming Yiu .[Subgraph Federated Learning with Missing Neighbor Generation](https://arxiv.org/pdf/2106.13430) [J]. arXiv preprint arXiv:2106.13430.
- Xinwei Zhang, Xiangyi Chen, Mingyi Hong, Zhiwei Steven Wu, Jinfeng Yi .[Understanding Clipping for Federated Learning: Convergence and Client-Level Differential Privacy](https://arxiv.org/pdf/2106.13673) [J]. arXiv preprint arXiv:2106.13673.
- Yatin Dandi, Luis Barba, Martin Jaggi .[Implicit Gradient Alignment in Distributed and Federated Learning](https://arxiv.org/pdf/2106.13897) [J]. arXiv preprint arXiv:2106.13897.
- Priyam Basu, Tiasa Singha Roy, Rakshit Naidu, Zumrut Muftuoglu, Sahib Singh, Fatemehsadat Mireshghallah .[Benchmarking Differential Privacy and Federated Learning for BERT Models](https://arxiv.org/pdf/2106.13973) [J]. arXiv preprint arXiv:2106.13973.
- Haoming Ma, Xiaojun Yuan, Dian Fan, Zhi Ding, Xin Wang .[Multi-task Over-the-Air Federated Learning: A Non-Orthogonal Transmission Approach](https://arxiv.org/pdf/2106.14229) [J]. arXiv preprint arXiv:2106.14229.
- Leon Witt, Usama Zafar, KuoYeh Shen, Felix Sattler, Dan Li, Wojciech Samek .[Reward-Based 1-bit Compressed Federated Distillation on Blockchain](https://arxiv.org/pdf/2106.14265) [J]. arXiv preprint arXiv:2106.14265.
- Pravin Chandran, Raghavendra Bhat, Avinash Chakravarthi, Srikanth Chandar .[Weight Divergence Driven Divide-and-Conquer Approach for Optimal Federated Learning from non-IID Data](https://arxiv.org/pdf/2106.14503) [J]. arXiv preprint arXiv:2106.14503.
- Yifei Song, Hao-Hsuan Chang, Zhou Zhou, Shashank Jere, Lingjia Liu .[Federated Dynamic Spectrum Access](https://arxiv.org/pdf/2106.14976) [J]. arXiv preprint arXiv:2106.14976.
- Mehrdad Kiamari, Bhaskar Krishnamachari .[Bottleneck Time Minimization for Distributed Iterative Processes: Speeding Up Gossip-Based Federated Learning on Networked Computers](https://arxiv.org/pdf/2106.15048) [J]. arXiv preprint arXiv:2106.15048.
- Lili Su, Jiaming Xu, Pengkun Yang .[Achieving Statistical Optimality of Federated Learning: Beyond Stationary Points](https://arxiv.org/pdf/2106.15216) [J]. arXiv preprint arXiv:2106.15216.
- Sayan Chatterjee, Manjesh K. Hanawal .[Federated Learning for Intrusion Detection in IoT Security: A Hybrid Ensemble Approach](https://arxiv.org/pdf/2106.15349) [J]. arXiv preprint arXiv:2106.15349.
- Rongfei Zeng, Chao Zeng, Xingwei Wang, Bo Li, Xiaowen Chu .[A Comprehensive Survey of Incentive Mechanism for Federated Learning](https://arxiv.org/pdf/2106.15406) [J]. arXiv preprint arXiv:2106.15406.
- Idan Achituve, Aviv Shamsian, Aviv Navon, Gal Chechik, Ethan Fetaya .[Personalized Federated Learning with Gaussian Processes](https://arxiv.org/pdf/2106.15482) [J]. arXiv preprint arXiv:2106.15482.
- Su Wang, Seyyedali Hosseinalipour, Maria Gorlatova, Christopher G. Brinton, Mung Chiang .[UAV-assisted Online Machine Learning over Multi-Tiered Networks: A Hierarchical Nested Personalized Federated Learning Approach](https://arxiv.org/pdf/2106.15734) [J]. arXiv preprint arXiv:2106.15734.
- Meng Zhang, Ermin Wei, Randall Berry .[Faithful Edge Federated Learning: Scalability and Privacy](https://arxiv.org/pdf/2106.15905) [J]. arXiv preprint arXiv:2106.15905.
- Wanning Pan, Lichao Sun .[Global Knowledge Distillation in Federated Learning](https://arxiv.org/pdf/2107.00051) [J]. arXiv preprint arXiv:2107.00051.
- Tehrim Yoon, Sumin Shin, Sung Ju Hwang, Eunho Yang .[FedMix: Approximation of Mixup under Mean Augmented Federated Learning](https://arxiv.org/pdf/2107.00233) [J]. arXiv preprint arXiv:2107.00233.
- Hong-You Chen, Wei-Lun Chao .[On Bridging Generic and Personalized Federated Learning](https://arxiv.org/pdf/2107.00778) [J]. arXiv preprint arXiv:2107.00778.
- Geet Shingi, Harsh Saglani, Preeti Jain .[Segmented Federated Learning for Adaptive Intrusion Detection System](https://arxiv.org/pdf/2107.00881) [J]. arXiv preprint arXiv:2107.00881.
- Wenqi Wei, Ling Liu, Yanzhao Wu, Gong Su, Arun Iyengar .[Gradient-Leakage Resilient Federated Learning](https://arxiv.org/pdf/2107.01154) [J]. arXiv preprint arXiv:2107.01154.
- Zhuohang Li, Luyang Liu, Jiaxin Zhang, Jian Liu .[Byzantine-robust Federated Learning through Spatial-temporal Analysis of Local Model Updates](https://arxiv.org/pdf/2107.01477) [J]. arXiv preprint arXiv:2107.01477.
- Rasheed el-Bouri, Tingting Zhu, David A. Clifton .[Towards Scheduling Federated Deep Learning using Meta-Gradients for Inter-Hospital Learning](https://arxiv.org/pdf/2107.01707) [J]. arXiv preprint arXiv:2107.01707.
- Yipeng Zhou, Xuezheng Liu, Yao Fu, Di Wu, Chao Li, Shui Yu .[Optimizing the Numbers of Queries and Replies in Federated Learning with Differential Privacy](https://arxiv.org/pdf/2107.01895) [J]. arXiv preprint arXiv:2107.01895.
- Francesco Malandrino, Carla Fabiana Chiasserini .[Towards Node Liability in Federated Learning: Computational Cost and Network Overhead](https://arxiv.org/pdf/2107.02006) [J]. arXiv preprint arXiv:2107.02006.
- Miao Zhang, Liangqiong Qu, Praveer Singh, Jayashree Kalpathy-Cramer, Daniel L. Rubin .[SplitAVG: A heterogeneity-aware federated deep learning method for medical imaging](https://arxiv.org/pdf/2107.02375) [J]. arXiv preprint arXiv:2107.02375.
- Amelia Jiménez-Sánchez, Mickael Tardy, Miguel A. González Ballester, Diana Mateus, Gemma Piella .[Memory-aware curriculum federated learning for breast cancer classification](https://arxiv.org/pdf/2107.02504) [J]. arXiv preprint arXiv:2107.02504.
- Alexander Ziller, Dmitrii Usynin, Nicolas Remerscheid, Moritz Knolle, Marcus Makowski, Rickmer Braren, Daniel Rueckert, Georgios Kaissis .[Differentially private federated deep learning for multi-site medical image segmentation](https://arxiv.org/pdf/2107.02586) [J]. arXiv preprint arXiv:2107.02586.
- Van-Dinh Nguyen, Symeon Chatzinotas, Bjorn Ottersten, Trung Q. Duong .[FedFog: Network-Aware Optimization of Federated Learning over Wireless Fog-Cloud Systems](https://arxiv.org/pdf/2107.02755) [J]. arXiv preprint arXiv:2107.02755.
- Venkatesh Venkataramanan, Sridevi Kaza, Anuradha M. Annaswamy .[DER Forecast using Privacy Preserving Federated Learning](https://arxiv.org/pdf/2107.03248) [J]. arXiv preprint arXiv:2107.03248.
- Lukas Burkhalter, Hidde Lycklama, Alexander Viand, Nicolas Küchler, Anwar Hithnawi .[RoFL: Attestable Robustness for Secure Federated Learning](https://arxiv.org/pdf/2107.03311) [J]. arXiv preprint arXiv:2107.03311.
- Silvana Trindade, Luiz F. Bittencourt, Nelson L. S. da Fonseca .[Management of Resource at the Network Edge for Federated Learning](https://arxiv.org/pdf/2107.03428) [J]. arXiv preprint arXiv:2107.03428.
- Mohammad Mohammadi Amiri, Sanjeev R. Kulkarni, H. Vincent Poor .[Federated Learning with Downlink Device Selection](https://arxiv.org/pdf/2107.03510) [J]. arXiv preprint arXiv:2107.03510.
- Mohammed S. Al-Abiad, Md. Zoheb Hassan, Md. Jahangir Hossain .[Energy Efficient Federated Learning in Integrated Fog-Cloud Computing Enabled Internet-of-Things Networks](https://arxiv.org/pdf/2107.03520) [J]. arXiv preprint arXiv:2107.03520.
- Arash Mehrjou .[Federated Learning as a Mean-Field Game](https://arxiv.org/pdf/2107.03770) [J]. arXiv preprint arXiv:2107.03770.
- Akis Linardos, Kaisar Kushibar, Sean Walsh, Polyxeni Gkontra, Karim Lekadir .[Federated Learning for Multi-Center Imaging Diagnostics: A Study in Cardiovascular Disease](https://arxiv.org/pdf/2107.03901) [J]. arXiv preprint arXiv:2107.03901.
- Yao Peng, Meirong He, Yu Wang .[A Federated Semi-Supervised Learning Approach for Network Traffic Classification](https://arxiv.org/pdf/2107.03933) [J]. arXiv preprint arXiv:2107.03933.
- Peng Wu, Tales Imbiriba, Junha Park, Sunwoo Kim, Pau Closas .[Personalized Federated Learning over non-IID Data for Indoor Localization](https://arxiv.org/pdf/2107.04189) [J]. arXiv preprint arXiv:2107.04189.
- Di Wu, Rehmat Ullah, Paul Harvey, Peter Kilpatrick, Ivor Spence, Blesson Varghese .[FedAdapt: Adaptive Offloading for IoT Devices in Federated Learning](https://arxiv.org/pdf/2107.04271) [J]. arXiv preprint arXiv:2107.04271.
- Xuezhong Lin, Jingyu Pan, Jinming Xu, Yiran Chen, Cheng Zhuo .[Lithography Hotspot Detection via Heterogeneous Federated Learning with Local Adaptation](https://arxiv.org/pdf/2107.04367) [J]. arXiv preprint arXiv:2107.04367.
- Ren-Hung Hwang, Yuan-Cheng Lai, Ying-Dar Lin .[Offloading Optimization with Delay Distribution in the 3-tier Federated Cloud, Edge, and Fog Systems](https://arxiv.org/pdf/2107.05015) [J]. arXiv preprint arXiv:2107.05015.
- YinchuanLi, XiaofengLiu, XuZhang, YunfengShao, QingWang, YanhuiGeng .[Personalized Federated Learning via Maximizing Correlation with Sparse and Hierarchical Extensions](https://arxiv.org/pdf/2107.05330) [J]. arXiv preprint arXiv:2107.05330.
- Golsa Heidari, Ahmad Ramadan, Markus Stocker, Sören Auer .[Leveraging a Federation of Knowledge Graphs to Improve Faceted Search in Digital Libraries](https://arxiv.org/pdf/2107.05447) [J]. arXiv preprint arXiv:2107.05447.
- Alaa Awad Abdellatif, Naram Mhaisen, Amr Mohamed, Aiman Erbad, Mohsen Guizani, Zaher Dawy, Wassim Nasreddine .[Communication-Efficient Hierarchical Federated Learning for IoT Heterogeneous Systems with Imbalanced Data](https://arxiv.org/pdf/2107.06548) [J]. arXiv preprint arXiv:2107.06548.
- David Roschewitz, Mary-Anne Hartley, Luca Corinzia, Martin Jaggi .[IFedAvg: Interpretable Data-Interoperability for Federated Learning](https://arxiv.org/pdf/2107.06580) [J]. arXiv preprint arXiv:2107.06580.
- Matthias Reisser, Christos Louizos, Efstratios Gavves, Max Welling .[Federated Mixture of Experts](https://arxiv.org/pdf/2107.06724) [J]. arXiv preprint arXiv:2107.06724.
- M. Ya. Amusia (1, 2), A. S. Baltenkov (3), I. Woiciechowski (4),  ((1) Racah Institute of Physics, the Hebrew University, 91904, Jerusalem, Israel (2) Ioffe Physical-Technical Institute, 194021, St. Petersburg, Russian Federation, (3) Arifov Institute of Ion-Plasma and Laser Technologies, 100125, Tashkent, Uzbekistan, (4) Alderson Broaddus University, 101 College Hill Drive, WV 26416, Philippi, USA) .[Wigner time delay of a particle elastically scattered by a cluster of zero-range potentials](https://arxiv.org/pdf/2107.06798) [J]. arXiv preprint arXiv:2107.06798.
- Vasileios Tsouvalas, Aaqib Saeed, Tanir Ozcelebi .[Federated Self-Training for Semi-Supervised Audio Recognition](https://arxiv.org/pdf/2107.06877) [J]. arXiv preprint arXiv:2107.06877.
- Jianyu Wang, Zachary Charles, Zheng Xu, Gauri Joshi, H. Brendan McMahan, Blaise Aguera y Arcas, Maruan Al-Shedivat, Galen Andrew, Salman Avestimehr, Katharine Daly, Deepesh Data, Suhas Diggavi, Hubert Eichner, Advait Gadhikar, Zachary Garrett, Antonious M. Girgis, Filip Hanzely, Andrew Hard, Chaoyang He, Samuel Horvath, Zhouyuan Huo, Alex Ingerman, Martin Jaggi, Tara Javidi, Peter Kairouz, Satyen Kale, Sai Praneeth Karimireddy, Jakub Konecny, Sanmi Koyejo, Tian Li, Luyang Liu, Mehryar Mohri, Hang Qi, Sashank J. Reddi, Peter Richtarik, Karan Singhal, Virginia Smith, Mahdi Soltanolkotabi, Weikang Song, Ananda Theertha Suresh, Sebastian U. Stich, Ameet Talwalkar, Hongyi Wang, Blake Woodworth, Shanshan Wu, Felix X. Yu, Honglin Yuan, Manzil Zaheer, Mi Zhang, Tong Zhang, Chunxiang Zheng, Chen Zhu, Wennan Zhu .[A Field Guide to Federated Optimization](https://arxiv.org/pdf/2107.06917) [J]. arXiv preprint arXiv:2107.06917.
- Ye Yuan, Ruijuan Chen, Chuan Sun, Maolin Wang, Feng Hua, Xinlei Yi, Tao Yang, Jun Liu .[DeFed: A Principled Decentralized and Privacy-Preserving Federated Learning Algorithm](https://arxiv.org/pdf/2107.07171) [J]. arXiv preprint arXiv:2107.07171.
- Abdurakhmon Sadiev, Darina Dvinskikh, Aleksandr Beznosikov, Alexander Gasnikov .[Decentralized and Personalized Federated Learning](https://arxiv.org/pdf/2107.07190) [J]. arXiv preprint arXiv:2107.07190.
- Shaashwat Agrawal, Sagnik Sarkar, Mamoun Alazab, Praveen Kumar Reddy Maddikunta, Thippa Reddy Gadekallu, Quoc-Viet Pham .[Genetic CFL: Optimization of Hyper-Parameters in Clustered Federated Learning](https://arxiv.org/pdf/2107.07233) [J]. arXiv preprint arXiv:2107.07233.
- Yang Li, Jiazheng Li, Yi Wang .[Privacy-preserving Spatiotemporal Scenario Generation of Renewable Energies: A Federated Deep Generative Learning Approach](https://arxiv.org/pdf/2107.07738) [J]. arXiv preprint arXiv:2107.07738.
- Holger R. Roth, Dong Yang, Wenqi Li, Andriy Myronenko, Wentao Zhu, Ziyue Xu, Xiaosong Wang, Daguang Xu .[Federated Whole Prostate Segmentation in MRI with Personalized Neural Architectures](https://arxiv.org/pdf/2107.08111) [J]. arXiv preprint arXiv:2107.08111.
- Young Geun Kim, Carole-Jean Wu .[AutoFL: Enabling Heterogeneity-Aware Energy Efficient Federated Learning](https://arxiv.org/pdf/2107.08147) [J]. arXiv preprint arXiv:2107.08147.
- Liangqiong Qu, Niranjan Balachandar, Daniel L Rubin .[An Experimental Study of Data Heterogeneity in Federated Learning Methods for Medical Imaging](https://arxiv.org/pdf/2107.08371) [J]. arXiv preprint arXiv:2107.08371.
- Farnaz Tahmasebian, Jian Lou, Li Xiong .[RobustFed: A Truth Inference Approach for Robust Federated Learning](https://arxiv.org/pdf/2107.08402) [J]. arXiv preprint arXiv:2107.08402.
- Noa Onoszko, Gustav Karlsson, Olof Mogren, Edvin Listo Zec .[Decentralized federated learning of deep neural networks on non-iid data](https://arxiv.org/pdf/2107.08517) [J]. arXiv preprint arXiv:2107.08517.
- Haemin Lee, Joongheon Kim .[Trends in Blockchain and Federated Learning for Data Sharing in Distributed Platforms](https://arxiv.org/pdf/2107.08624) [J]. arXiv preprint arXiv:2107.08624.
- Zhenhou Hong, Jianzong Wang, Xiaoyang Qu, Jie Liu, Chendong Zhao, Jing Xiao .[Federated Learning with Dynamic Transformer for Text to Speech](https://arxiv.org/pdf/2107.08795) [J]. arXiv preprint arXiv:2107.08795.
- Guang Yang, Ke Mu, Chunhe Song, Zhijia Yang, Tierui Gong .[RingFed: Reducing Communication Costs in Federated Learning on Non-IID Data](https://arxiv.org/pdf/2107.08873) [J]. arXiv preprint arXiv:2107.08873.
- Zehong Lin, Hang Liu, Ying-Jun Angela Zhang .[Relay-Assisted Cooperative Federated Learning](https://arxiv.org/pdf/2107.09518) [J]. arXiv preprint arXiv:2107.09518.
- Tung T. Vu, Hien Quoc Ngo, Thomas L. Marzetta, Michail Matthaiou .[How Does Cell-Free Massive MIMO Support Multiple Federated Learning Groups?](https://arxiv.org/pdf/2107.09577) [J]. arXiv preprint arXiv:2107.09577.
- Jonatan Reyes, Lisa Di Jorio, Cecile Low-Kam, Marta Kersten-Oertel .[Precision-Weighted Federated Learning](https://arxiv.org/pdf/2107.09627) [J]. arXiv preprint arXiv:2107.09627.
- Jiankai Sun, Yuanshun Yao, Weihao Gao, Junyuan Xie, Chong Wang .[Defending against Reconstruction Attack in Vertical Federated Learning](https://arxiv.org/pdf/2107.09898) [J]. arXiv preprint arXiv:2107.09898.
- Monik Raj Behera, Sudhir Upadhyay, Suresh Shetty .[Federated Learning using Smart Contracts on Blockchains, based on Reward Driven Approach](https://arxiv.org/pdf/2107.10243) [J]. arXiv preprint arXiv:2107.10243.
- Naichen Shi, Fan Lai, Raed Al Kontar, Mosharaf Chowdhury .[Fed-ensemble: Improving Generalization through Model Ensembling in Federated Learning](https://arxiv.org/pdf/2107.10663) [J]. arXiv preprint arXiv:2107.10663.
- Muhammad Asad, Ahmed Moustafa, Takayuki Ito .[Federated Learning Versus Classical Machine Learning: A Convergence Comparison](https://arxiv.org/pdf/2107.10976) [J]. arXiv preprint arXiv:2107.10976.
- Osama Shahid, Seyedamin Pouriyeh, Reza M. Parizi, Quan Z. Sheng, Gautam Srivastava, Liang Zhao .[Communication Efficiency in Federated Learning: Achievements and Challenges](https://arxiv.org/pdf/2107.10996) [J]. arXiv preprint arXiv:2107.10996.
- Chung-Hsuan Hu, Zheng Chen, Erik G. Larsson .[Device Scheduling and Update Aggregation Policies for Asynchronous Federated Learning](https://arxiv.org/pdf/2107.11415) [J]. arXiv preprint arXiv:2107.11415.
- Maojun Zhang, Guangxu Zhu, Shuai Wang, Jiamo Jiang, Caijun Zhong, Shuguang Cui .[Accelerating Federated Edge Learning via Optimized Probabilistic Device Scheduling](https://arxiv.org/pdf/2107.11588) [J]. arXiv preprint arXiv:2107.11588.
- Dun Zeng, Siqi Liang, Xiangjing Hu, Zenglin Xu .[FedLab: A Flexible Federated Learning Framework](https://arxiv.org/pdf/2107.11621) [J]. arXiv preprint arXiv:2107.11621.
- Fengjiao Li, Jia Liu, Bo Ji .[Federated Learning with Fair Worker Selection: A Multi-Round Submodular Maximization Approach](https://arxiv.org/pdf/2107.11728) [J]. arXiv preprint arXiv:2107.11728.
- Ruoxuan Xiong, Allison Koenecke, Michael Powell, Zhu Shen, Joshua T. Vogelstein, Susan Athey .[Federated Causal Inference in Heterogeneous Observational Data](https://arxiv.org/pdf/2107.11732) [J]. arXiv preprint arXiv:2107.11732.
- Xin-Chun Li, Le Gan, De-Chuan Zhan, Yunfeng Shao, Bingshuai Li, Shaoming Song .[Aggregate or Not? Exploring Where to Privatize in DNN Based Federated Learning Under Different Non-IID Scenes](https://arxiv.org/pdf/2107.11954) [J]. arXiv preprint arXiv:2107.11954.
- Xin-Chun Li, De-Chuan Zhan, Yunfeng Shao, Bingshuai Li, Shaoming Song .[Preliminary Steps Towards Federated Sentiment Classification](https://arxiv.org/pdf/2107.11956) [J]. arXiv preprint arXiv:2107.11956.
- Wei Liu, Li Chen, Wenyi Zhang .[Decentralized Federated Learning: Balancing Communication and Computing Costs](https://arxiv.org/pdf/2107.12048) [J]. arXiv preprint arXiv:2107.12048.
- Pranjal Jain, Shreyas Goenka, Saurabh Bagchi, Biplab Banerjee, Somali Chaterji .[Federated Action Recognition on Heterogeneous Embedded Devices](https://arxiv.org/pdf/2107.12147) [J]. arXiv preprint arXiv:2107.12147.
- Yann Fraboni, Richard Vidal, Laetitia Kameni, Marco Lorenzi .[On The Impact of Client Sampling on Federated Learning Convergence](https://arxiv.org/pdf/2107.12211) [J]. arXiv preprint arXiv:2107.12211.
- Kamala Varma, Yi Zhou, Nathalie Baracaldo, Ali Anwar .[LEGATO: A LayerwisE Gradient AggregaTiOn Algorithm for Mitigating Byzantine Attacks in Federated Learning](https://arxiv.org/pdf/2107.12490) [J]. arXiv preprint arXiv:2107.12490.
- Ming Liu, Stella Ho, Mengqi Wang, Longxiang Gao, Yuan Jin, He Zhang .[Federated Learning Meets Natural Language Processing: A Survey](https://arxiv.org/pdf/2107.12603) [J]. arXiv preprint arXiv:2107.12603.
- Farwa K. Khan, Adrian Flanagan, Kuan E. Tan, Zareen Alamgir, Muhammad Ammad-Ud-Din .[A Payload Optimization Method for Federated Recommender Systems](https://arxiv.org/pdf/2107.13078) [J]. arXiv preprint arXiv:2107.13078.
- Siddharth Divi, Yi-Shan Lin, Habiba Farrukh, Z. Berkay Celik .[New Metrics to Evaluate the Performance and Fairness of Personalized Federated Learning](https://arxiv.org/pdf/2107.13173) [J]. arXiv preprint arXiv:2107.13173.
- Amit Chaulwar, Michael Huth .[Secure Bayesian Federated Analytics for Privacy-Preserving Trend Detection](https://arxiv.org/pdf/2107.13640) [J]. arXiv preprint arXiv:2107.13640.
- Xiaodian Cheng, Wanhang Lu, Xinyang Huang, Shuihai Hu, Kai Chen .[HAFLO: GPU-Based Acceleration for Federated Logistic Regression](https://arxiv.org/pdf/2107.13797) [J]. arXiv preprint arXiv:2107.13797.
- Kaan Ozkara, Navjot Singh, Deepesh Data, Suhas Diggavi .[QuPeD: Quantized Personalization via Distillation with Applications to Federated Learning](https://arxiv.org/pdf/2107.13892) [J]. arXiv preprint arXiv:2107.13892.
- Thilanka Munasinghe, HR Pasindu .[Sensing and Mapping for Better Roads: Initial Plan for Using Federated Learning and Implementing a Digital Twin to Identify the Road Conditions in a Developing Country -- Sri Lanka](https://arxiv.org/pdf/2107.14551) [J]. arXiv preprint arXiv:2107.14551.
- Chunjiang Che, Xiaoli Li, Chuan Chen, Xiaoyu He, Zibin Zheng .[A Decentralized Federated Learning Framework via Committee Mechanism with Convergence Guarantee](https://arxiv.org/pdf/2108.00365) [J]. arXiv preprint arXiv:2108.00365.
- Fenghe Hu, Yansha Deng, A. Hamid Aghvami .[A Scalable Federated Multi-agent Architecture for Networked Connected Communication Network](https://arxiv.org/pdf/2108.00506) [J]. arXiv preprint arXiv:2108.00506.
- Yuwei Sun, Ng Chong, Hideya Ochiai .[Information Stealing in Federated Learning Systems Based on Generative Adversarial Networks](https://arxiv.org/pdf/2108.00701) [J]. arXiv preprint arXiv:2108.00701.
- Kai Yue, Richeng Jin, Chau-Wai Wong, Huaiyu Dai .[Communication-Efficient Federated Learning via Predictive Coding](https://arxiv.org/pdf/2108.00918) [J]. arXiv preprint arXiv:2108.00918.
- Enrique Mármol Campos, Pablo Fernández Saura, Aurora González-Vidal, José L. Hernández-Ramos, Jorge Bernal Bernabe, Gianmarco Baldini, Antonio Skarmeta .[Evaluating Federated Learning for Intrusion Detection in Internet of Things: Review and Challenges](https://arxiv.org/pdf/2108.00974) [J]. arXiv preprint arXiv:2108.00974.
- Graham Cormode, Igor L. Markov .[Bit-efficient Numerical Aggregation and Stronger Privacy for Trust in Federated Analytics](https://arxiv.org/pdf/2108.01521) [J]. arXiv preprint arXiv:2108.01521.
- Joo Hun Yoo, Ha Min Son, Hyejun Jeong, Eun-Hye Jang, Ah Young Kim, Han Young Yu, Hong Jin Jeon, Tai-Myoung Chung .[Personalized Federated Learning with Clustering: Non-IID Heart Rate Variability Data Application](https://arxiv.org/pdf/2108.01903) [J]. arXiv preprint arXiv:2108.01903.
- Josep Domingo-Ferrer, Alberto Blanco-Justicia, Jesús Manjón, David Sánchez .[Secure and Privacy-Preserving Federated Learning via Co-Utility](https://arxiv.org/pdf/2108.01913) [J]. arXiv preprint arXiv:2108.01913.
- Jae Hun Ro, Ananda Theertha Suresh, Ke Wu .[FedJAX: Federated learning simulation with JAX](https://arxiv.org/pdf/2108.02117) [J]. arXiv preprint arXiv:2108.02117.
- Hao Ye, Le Liang, Geoffrey Li .[Decentralized Federated Learning with Unreliable Communications](https://arxiv.org/pdf/2108.02397) [J]. arXiv preprint arXiv:2108.02397.
- Sawan Singh Mahara, Shruti M., B. N. Bharath .[Multi-task Federated Edge Learning (MtFEEL) in Wireless Networks](https://arxiv.org/pdf/2108.02517) [J]. arXiv preprint arXiv:2108.02517.
- Igor Donevski, Jimmy Jessen Nielsen, Petar Popovski,  .[On Addressing Heterogeneity in Federated Learning for Autonomous Vehicles Connected to a Drone Orchestrator](https://arxiv.org/pdf/2108.02712) [J]. arXiv preprint arXiv:2108.02712.
- Xubo Yue, Maher Nouiehed, Raed Al Kontar .[GIFAIR-FL: An Approach for Group and Individual Fairness in Federated Learning](https://arxiv.org/pdf/2108.02741) [J]. arXiv preprint arXiv:2108.02741.
- Xiang Ma, Haijian Sun, Qun Wang, Rose Qingyang Hu .[User Scheduling for Federated Learning Through Over-the-Air Computation](https://arxiv.org/pdf/2108.02891) [J]. arXiv preprint arXiv:2108.02891.
- Dimitris Stripelis, Hamza Saleem, Tanmay Ghai, Nikhil Dhinagar, Umang Gupta, Chrysovalantis Anastasiou, Greg Ver Steeg, Srivatsan Ravi, Muhammad Naveed, Paul M. Thompson, Jose Luis Ambite .[Secure Neuroimaging Analysis using Federated Learning with Homomorphic Encryption](https://arxiv.org/pdf/2108.03437) [J]. arXiv preprint arXiv:2108.03437.
- Zhuofan Zhang, Mi Zhou, Kaicheng Niu, Chaouki Abdallah .[The Effect of Training Parameters and Mechanisms on Decentralized Federated Learning based on MNIST Dataset](https://arxiv.org/pdf/2108.03508) [J]. arXiv preprint arXiv:2108.03508.
- Shuang Dai, Fanlin Meng, Qian Wang, Xizhong Chen .[FederatedNILM: A Distributed and Privacy-preserving Framework for Non-intrusive Load Monitoring based on Federated Deep Learning](https://arxiv.org/pdf/2108.03591) [J]. arXiv preprint arXiv:2108.03591.
- Zhe Wang, Xinhang Li, Tianhao Wu, Chen Xu, Lin Zhang .[A Credibility-aware Swarm-Federated Deep Learning Framework in Internet of Vehicles](https://arxiv.org/pdf/2108.03981) [J]. arXiv preprint arXiv:2108.03981.
- Mingming Liu .[Fed-BEV: A Federated Learning Framework for Modelling Energy Consumption of Battery Electric Vehicles](https://arxiv.org/pdf/2108.04036) [J]. arXiv preprint arXiv:2108.04036.
- Hyejun Jeong, Joonyong Hwang, Tai Myung Chung .[ABC-FL: Anomalous and Benign client Classification in Federated Learning](https://arxiv.org/pdf/2108.04551) [J]. arXiv preprint arXiv:2108.04551.
- Haoyu Zhao, Zhize Li, Peter Richtárik .[FedPAGE: A Fast Local Stochastic Gradient Method for Communication-Efficient Federated Learning](https://arxiv.org/pdf/2108.04755) [J]. arXiv preprint arXiv:2108.04755.
- Jiangui Chen, Ruqing Zhang, Jiafeng Guo, Yixing Fan, Xueqi Cheng .[FedMatch: Federated Learning Over Heterogeneous Question Answering Data](https://arxiv.org/pdf/2108.05069) [J]. arXiv preprint arXiv:2108.05069.
- Mengmeng Tian, Yuxin Chen, Yuan Liu, Zehui Xiong, Cyril Leung, Chunyan Miao .[A Contract Theory based Incentive Mechanism for Federated Learning](https://arxiv.org/pdf/2108.05568) [J]. arXiv preprint arXiv:2108.05568.
- Srikanth Chandar, Pravin Chandran, Raghavendra Bhat, Avinash Chakravarthi .[Communication Optimization in Large Scale Federated Learning using Autoencoder Compressed Weight Updates](https://arxiv.org/pdf/2108.05670) [J]. arXiv preprint arXiv:2108.05670.
- Zihan Chen, Kai Fong Ernest Chong, Tony Q. S. Quek .[Dynamic Attention-based Communication-Efficient Federated Learning](https://arxiv.org/pdf/2108.05765) [J]. arXiv preprint arXiv:2108.05765.
- Saber Malekmohammadi, Kiarash Shaloudegi, Zeou Hu, Yaoliang Yu .[An Operator Splitting View of Federated Learning](https://arxiv.org/pdf/2108.05974) [J]. arXiv preprint arXiv:2108.05974.
- Nam Hyeon-Woo, Moon Ye-Bin, Tae-Hyun Oh .[FedPara: Low-rank Hadamard Product Parameterization for Efficient Federated Learning](https://arxiv.org/pdf/2108.06098) [J]. arXiv preprint arXiv:2108.06098.
- Sheng Yue, Ju Ren, Jiang Xin, Deyu Zhang, Yaoxue Zhang, Weihua Zhuang .[Efficient Federated Meta-Learning over Multi-Access Wireless Networks](https://arxiv.org/pdf/2108.06453) [J]. arXiv preprint arXiv:2108.06453.
- Weiming Zhuang, Yonggang Wen, Shuai Zhang .[Joint Optimization in Edge-Cloud Continuum for Federated Unsupervised Person Re-identification](https://arxiv.org/pdf/2108.06493) [J]. arXiv preprint arXiv:2108.06493.
- Daniela Pöhn, Peter Hillmann .[Reference Service Model for Federated Identity Management](https://arxiv.org/pdf/2108.06701) [J]. arXiv preprint arXiv:2108.06701.
- Charlie Hou, Kiran K. Thekumparampil, Giulia Fanti, Sewoong Oh .[Reducing the Communication Cost of Federated Learning through Multistage Optimization](https://arxiv.org/pdf/2108.06869) [J]. arXiv preprint arXiv:2108.06869.
- Lingjuan Lyu, Chen Chen .[A Novel Attribute Reconstruction Attack in Federated Learning](https://arxiv.org/pdf/2108.06910) [J]. arXiv preprint arXiv:2108.06910.
- Sin Kit Lo, Yue Liu, Qinghua Lu, Chen Wang, Xiwei Xu, Hye-Young Paik, Liming Zhu .[Blockchain-based Trustworthy Federated Learning Architecture](https://arxiv.org/pdf/2108.06912) [J]. arXiv preprint arXiv:2108.06912.
- Cengguang Zhang, Junxue Zhang, Di Chai, Kai Chen .[Aegis: A Trusted, Automatic and Accurate Verification Framework for Vertical Federated Learning](https://arxiv.org/pdf/2108.06958) [J]. arXiv preprint arXiv:2108.06958.
- Gary Cheng, Karan Chadha, John Duchi .[Fine-tuning is Fine in Federated Learning](https://arxiv.org/pdf/2108.07313) [J]. arXiv preprint arXiv:2108.07313.
- Ye Xue, Diego Klabjan, Yuan Luo .[Aggregation Delayed Federated Learning](https://arxiv.org/pdf/2108.07433) [J]. arXiv preprint arXiv:2108.07433.
- Chen-Feng Liu, Mehdi Bennis .[Federated Learning with Correlated Data: Taming the Tail for Age-Optimal Industrial IoT](https://arxiv.org/pdf/2108.07504) [J]. arXiv preprint arXiv:2108.07504.
- Dongzhu Liu, Osvaldo Simeone .[Wireless Federated Langevin Monte Carlo: Repurposing Channel Noise for Bayesian Sampling and Privacy](https://arxiv.org/pdf/2108.07644) [J]. arXiv preprint arXiv:2108.07644.
- Chun-Han Yao, Boqing Gong, Yin Cui, Hang Qi, Yukun Zhu, Ming-Hsuan Yang .[Federated Multi-Target Domain Adaptation](https://arxiv.org/pdf/2108.07792) [J]. arXiv preprint arXiv:2108.07792.
- Zilong Zhao, Robert Birke, Aditya Kunar, Lydia Y. Chen .[Fed-TGAN: Federated Learning Framework for Synthesizing Tabular Data](https://arxiv.org/pdf/2108.07927) [J]. arXiv preprint arXiv:2108.07927.
- Lin Ning, Karan Singhal, Ellie X. Zhou, Sushant Prakash .[Learning Federated Representations and Recommendations with Limited Negatives](https://arxiv.org/pdf/2108.07931) [J]. arXiv preprint arXiv:2108.07931.
- Kai Zhang, Yushan Jiang, Lee Seversky, Chengtao Xu, Dahai Liu, Houbing Song .[Federated Variational Learning for Anomaly Detection in Multivariate Time Series](https://arxiv.org/pdf/2108.08404) [J]. arXiv preprint arXiv:2108.08404.
- Sen Cui, Weishen Pan, Jian Liang, Changshui Zhang, Fei Wang .[Fair and Consistent Federated Learning](https://arxiv.org/pdf/2108.08435) [J]. arXiv preprint arXiv:2108.08435.
- Chen Shen, Pochuan Wang, Holger R. Roth, Dong Yang, Daguang Xu, Masahiro Oda, Weichung Wang, Chiou-Shann Fuh, Po-Ting Chen, Kao-Lang Liu, Wei-Chih Liao, Kensaku Mori .[Multi-task Federated Learning for Heterogeneous Pancreas Segmentation](https://arxiv.org/pdf/2108.08537) [J]. arXiv preprint arXiv:2108.08537.
- Zirui Zhu, Ziyi Ye .[Towards More Efficient Federated Learning with Better Optimization Objects](https://arxiv.org/pdf/2108.08577) [J]. arXiv preprint arXiv:2108.08577.
- Ming Xie, Guodong Long, Tao Shen, Tianyi Zhou, Xianzhi Wang, Jing Jiang, Chengqi Zhang .[Multi-Center Federated Learning](https://arxiv.org/pdf/2108.08647) [J]. arXiv preprint arXiv:2108.08647.
- Arsalan Sharifnassab, Saber Salehkaleybar, S. Jamaloddin Golestani .[Order Optimal One-Shot Federated Learning for non-Convex Loss Functions](https://arxiv.org/pdf/2108.08677) [J]. arXiv preprint arXiv:2108.08677.
- Abdullatif Albaseer, Mohamed Abdallah, Ala Al-Fuqaha, Aiman Erbad .[Client Selection Approach in Support of Clustered Federated Learning over Wireless Edge Networks](https://arxiv.org/pdf/2108.08768) [J]. arXiv preprint arXiv:2108.08768.
- Shay Vargaftik, Ran Ben Basat, Amit Portnoy, Gal Mendelson, Yaniv Ben-Itzhak, Michael Mitzenmacher .[Communication-Efficient Federated Learning via Robust Distributed Mean Estimation](https://arxiv.org/pdf/2108.08842) [J]. arXiv preprint arXiv:2108.08842.
- M. Ya. Amusia (1, 2), A. S. Baltenkov (3) ((1) Racah Institute of Physics, the Hebrew University, 91904, Jerusalem, Israel, (2) Ioffe Physical-Technical Institute, 194021, St. Petersburg, Russian Federation, (3) Arifov Institute of Ion-Plasma and Laser Technologies, 100125, Tashkent, Uzbekistan) .[Elastic scattering of slow electrons by carbon nanotubes](https://arxiv.org/pdf/2108.08912) [J]. arXiv preprint arXiv:2108.08912.
- Anirban Das, Shiqiang Wang, Stacy Patterson .[Cross-Silo Federated Learning for Multi-Tier Networks with Vertical and Horizontal Data Partitioning](https://arxiv.org/pdf/2108.08930) [J]. arXiv preprint arXiv:2108.08930.
- Chaouki Ben Issaid, Sumudu Samarakoon, Mehdi Bennis, H. Vincent Poor .[Federated Distributionally Robust Optimization for Phase Configuration of RISs](https://arxiv.org/pdf/2108.09026) [J]. arXiv preprint arXiv:2108.09026.
- Junyu Luo, Jianlei Yang, Xucheng Ye, Xin Guo, Weisheng Zhao .[FedSkel: Efficient Federated Learning on Heterogeneous Systems with Skeleton Gradients Update](https://arxiv.org/pdf/2108.09081) [J]. arXiv preprint arXiv:2108.09081.
- Chenyuan Feng, Howard H. Yang, Deshun Hu, Zhiwei Zhao, Tony Q. S. Quek, Geyong Min .[Mobility-Aware Cluster Federated Learning in Hierarchical Wireless Networks](https://arxiv.org/pdf/2108.09103) [J]. arXiv preprint arXiv:2108.09103.
- Jed Mills, Jia Hu, Geyong Min, Rui Jin, Siwei Zheng, Jin Wang .[Accelerating Federated Learning with a Global Biased Optimiser](https://arxiv.org/pdf/2108.09134) [J]. arXiv preprint arXiv:2108.09134.
- Haowen Lin, Jian Lou, Li Xiong, Cyrus Shahabi .[SemiFed: Semi-supervised Federated Learning with Consistency and Pseudo-Labeling](https://arxiv.org/pdf/2108.09412) [J]. arXiv preprint arXiv:2108.09412.
- Sone Kyaw Pye, Han Yu .[Personalised Federated Learning: A Combinational Approach](https://arxiv.org/pdf/2108.09618) [J]. arXiv preprint arXiv:2108.09618.
- Moming Duan, Duo Liu, Xinyuan Ji, Yu Wu, Liang Liang, Xianzhang Chen, Yujuan Tan .[Flexible Clustered Federated Learning for Client-Level Data Distribution Shift](https://arxiv.org/pdf/2108.09749) [J]. arXiv preprint arXiv:2108.09749.
- Haibo Yang, Xin Zhang, Prashant Khanduri, Jia Liu .[Anarchic Federated Learning](https://arxiv.org/pdf/2108.09875) [J]. arXiv preprint arXiv:2108.09875.
- Manisha Padala, Sankarshan Damle, Sujit Gujar .[Federated Learning Meets Fairness and Differential Privacy](https://arxiv.org/pdf/2108.09932) [J]. arXiv preprint arXiv:2108.09932.
- Virat Shejwalkar, Amir Houmansadr, Peter Kairouz, Daniel Ramage .[Back to the Drawing Board: A Critical Evaluation of Poisoning Attacks on Federated Learning](https://arxiv.org/pdf/2108.10241) [J]. arXiv preprint arXiv:2108.10241.
- Othmane Marfoq, Giovanni Neglia, Aurélien Bellet, Laetitia Kameni, Richard Vidal .[Federated Multi-Task Learning under a Mixture of Distributions](https://arxiv.org/pdf/2108.10252) [J]. arXiv preprint arXiv:2108.10252.
- Hongtao Lv, Zhenzhe Zheng, Tie Luo, Fan Wu, Shaojie Tang, Lifeng Hua, Rongfei Jia, Chengfei Lv .[Data-Free Evaluation of User Contributions in Federated Learning](https://arxiv.org/pdf/2108.10623) [J]. arXiv preprint arXiv:2108.10623.
- Ilyes Mrad, Lutfi Samara, Alaa Awad Abdellatif, Abubakr Al-Abbasi, Ridha Hamila, Aiman Erbad .[Federated Learning for UAV Swarms Under Class Imbalance and Power Consumption Constraints](https://arxiv.org/pdf/2108.10748) [J]. arXiv preprint arXiv:2108.10748.
- Guodong Long, Yue Tan, Jing Jiang, Chengqi Zhang .[Federated Learning for Open Banking](https://arxiv.org/pdf/2108.10749) [J]. arXiv preprint arXiv:2108.10749.
- Guodong Long, Tao Shen, Yue Tan, Leah Gerrard, Allison Clarke, Jing Jiang .[Federated Learning for Privacy-Preserving Open Innovation Future on Digital Health](https://arxiv.org/pdf/2108.10761) [J]. arXiv preprint arXiv:2108.10761.
- Hangyu Zhu, Rui Wang, Yaochu Jin, Kaitai Liang .[PIVODL: Privacy-preserving vertical federated learning over distributed labels](https://arxiv.org/pdf/2108.11444) [J]. arXiv preprint arXiv:2108.11444.
- Nirupam Gupta, Thinh T. Doan, Nitin Vaidya .[Byzantine Fault-Tolerance in Federated Local SGD under 2f-Redundancy](https://arxiv.org/pdf/2108.11769) [J]. arXiv preprint arXiv:2108.11769.
- Yejia Liu, Weiyuan Wu, Lampros Flokas, Jiannan Wang, Eugene Wu .[Enabling SQL-based Training Data Debugging for Federated Learning](https://arxiv.org/pdf/2108.11884) [J]. arXiv preprint arXiv:2108.11884.
- Jiaju Qi, Qihao Zhou, Lei Lei, Kan Zheng .[Federated Reinforcement Learning: Techniques, Applications, and Open Challenges](https://arxiv.org/pdf/2108.11887) [J]. arXiv preprint arXiv:2108.11887.
- Sai Li, Tianxi Cai, Rui Duan .[Targeting Underrepresented Populations in Precision Medicine: A Federated Transfer Learning Approach](https://arxiv.org/pdf/2108.12112) [J]. arXiv preprint arXiv:2108.12112.
- Deepika Saxena, Rishabh Gupta, Ashutosh Kumar Singh .[A Survey and Comparative Study on Multi-Cloud Architectures: Emerging Issues And Challenges For Cloud Federation](https://arxiv.org/pdf/2108.12831) [J]. arXiv preprint arXiv:2108.12831.
- Shengyuan Hu, Zhiwei Steven Wu, Virginia Smith .[Private Multi-Task Learning: Formulation and Applications to Federated Learning](https://arxiv.org/pdf/2108.12978) [J]. arXiv preprint arXiv:2108.12978.
- Chuhan Wu, Fangzhao Wu, Ruixuan Liu, Lingjuan Lyu, Yongfeng Huang, Xing Xie .[FedKD: Communication Efficient Federated Learning via Knowledge Distillation](https://arxiv.org/pdf/2108.13323) [J]. arXiv preprint arXiv:2108.13323.
- Tung T. Vu, Hien Quoc Ngo, Duy T. Ngo, Minh N Dao, Erik G. Larsson .[Energy-Efficient Massive MIMO for Serving Multiple Federated Learning Groups](https://arxiv.org/pdf/2108.13512) [J]. arXiv preprint arXiv:2108.13512.
- Shuai Wang, Dachuan Li, Rui Wang, Qi Hao, Yik-Chung Wu, Derrick Wing Kwan Ng .[Unit-Modulus Wireless Federated Learning Via Penalty Alternating Minimization](https://arxiv.org/pdf/2108.13669) [J]. arXiv preprint arXiv:2108.13669.
- Yen-Hsiu Chou, Shenda Hong, Chenxi Sun, Derun Cai, Moxian Song, Hongyan Li .[GRP-FED: Addressing Client Imbalance in Federated Learning via Global-Regularized Personalization](https://arxiv.org/pdf/2108.13858) [J]. arXiv preprint arXiv:2108.13858.
- Sean M. Hendryx, Dharma Raj KC, Bradley Walls, Clayton T. Morrison .[Federated Reconnaissance: Efficient, Distributed, Class-Incremental Learning](https://arxiv.org/pdf/2109.00150) [J]. arXiv preprint arXiv:2109.00150.
- Yujing Chen, Zheng Chai, Yue Cheng, Huzefa Rangwala .[Asynchronous Federated Learning for Sensor Data with Concept Drift](https://arxiv.org/pdf/2109.00151) [J]. arXiv preprint arXiv:2109.00151.
- Joo Hun Yoo, Hyejun Jeong, Jaehyeok Lee, Tai-Myoung Chung .[Federated Learning: Issues in Medical Application](https://arxiv.org/pdf/2109.00202) [J]. arXiv preprint arXiv:2109.00202.
- Zhifeng Jiang, Wei Wang, Yang Liu .[FLASHE: Additively Symmetric Homomorphic Encryption for Cross-Silo Federated Learning](https://arxiv.org/pdf/2109.00675) [J]. arXiv preprint arXiv:2109.00675.
- Xiang Li, Jiadong Liang, Xiangyu Chang, Zhihua Zhang .[Statistical Estimation and Inference via Local SGD in Federated Learning](https://arxiv.org/pdf/2109.01326) [J]. arXiv preprint arXiv:2109.01326.
- Nasrin Razmi, Bho Matthiesen, Armin Dekorsy, Petar Popovski .[Ground-Assisted Federated Learning in LEO Satellite Constellations](https://arxiv.org/pdf/2109.01348) [J]. arXiv preprint arXiv:2109.01348.
- Johan Ruuskanen, Haorui Peng, Alfred Åkesson, Lars Larsson, Maria Kihl .[FedApp: a Research Sandbox for Application Orchestration in Federated Clouds using OpenStack](https://arxiv.org/pdf/2109.01480) [J]. arXiv preprint arXiv:2109.01480.
- Zelei Liu, Yuanyuan Chen, Han Yu, Yang Liu, Lizhen Cui .[GTG-Shapley: Efficient and Accurate Participant Contribution Evaluation in Federated Learning](https://arxiv.org/pdf/2109.02053) [J]. arXiv preprint arXiv:2109.02053.
- Samhita Kanaparthy, Manisha Padala, Sankarshan Damle, Sujit Gujar .[Fair Federated Learning for Heterogeneous Face Data](https://arxiv.org/pdf/2109.02351) [J]. arXiv preprint arXiv:2109.02351.
- Hang Liu, Zehong Lin, Xiaojun Yuan, Ying-Jun Angela Zhang .[Reconfigurable Intelligent Surface Empowered Over-the-Air Federated Edge Learning](https://arxiv.org/pdf/2109.02353) [J]. arXiv preprint arXiv:2109.02353.
- Sebastian Bischoff, Stephan Günnemann, Martin Jaggi, Sebastian U. Stich .[On Second-order Optimization Methods for Federated Learning](https://arxiv.org/pdf/2109.02388) [J]. arXiv preprint arXiv:2109.02388.
- Kun Zhai, Qiang Ren, Junli Wang, Chungang Yan .[Byzantine-Robust Federated Learning via Credibility Assessment on Non-IID Data](https://arxiv.org/pdf/2109.02396) [J]. arXiv preprint arXiv:2109.02396.
- Liu Yang, Ben Tan, Bo Liu, Vincent W. Zheng, Kai Chen, Qiang Yang .[Practical and Secure Federated Recommendation with Personalized Masks](https://arxiv.org/pdf/2109.02464) [J]. arXiv preprint arXiv:2109.02464.
- John Weldon, Tomas Ward, Eoin Brophy .[Generation of Synthetic Electronic Health Records Using a Federated GAN](https://arxiv.org/pdf/2109.02543) [J]. arXiv preprint arXiv:2109.02543.
- Frank Po-Chen Lin, Seyyedali Hosseinalipour, Sheikh Shams Azam, Christopher G. Brinton, Nicolò Michelusi .[Federated Learning Beyond the Star: Local D2D Model Consensus with Global Cluster Sampling](https://arxiv.org/pdf/2109.03350) [J]. arXiv preprint arXiv:2109.03350.
- Lan Zhang, Xiaoyong Yuan .[FedZKT: Zero-Shot Knowledge Transfer towards Heterogeneous On-Device Models in Federated Learning](https://arxiv.org/pdf/2109.03775) [J]. arXiv preprint arXiv:2109.03775.
- Zachary Charles, Keith Rush .[Iterated Vector Fields and Conservatism, with Applications to Federated Learning](https://arxiv.org/pdf/2109.03973) [J]. arXiv preprint arXiv:2109.03973.
- Zhifeng Jiang, Wei Wang .[System Optimization in Synchronous Federated Training: A Survey](https://arxiv.org/pdf/2109.03999) [J]. arXiv preprint arXiv:2109.03999.
- C. Xiao, S. Wang .[An Experimental Study of Class Imbalance in Federated Learning](https://arxiv.org/pdf/2109.04094) [J]. arXiv preprint arXiv:2109.04094.
- Anastasiia Usmanova (INPG), François Portet (GETALP), Philippe Lalanda (M-PSI), German Vega (M-PSI) .[A distillation-based approach integrating continual learning and federated learning for pervasive services](https://arxiv.org/pdf/2109.04197) [J]. arXiv preprint arXiv:2109.04197.
- Shulai Zhang, Zirui Li, Quan Chen, Wenli Zheng, Jingwen Leng, Minyi Guo .[Dubhe: Towards Data Unbiasedness with Homomorphic Encryption in Federated Learning Client Selection](https://arxiv.org/pdf/2109.04253) [J]. arXiv preprint arXiv:2109.04253.
- Chenhao Xu, Youyang Qu, Yong Xiang, Longxiang Gao .[Asynchronous Federated Learning on Heterogeneous Devices: A Survey](https://arxiv.org/pdf/2109.04269) [J]. arXiv preprint arXiv:2109.04269.
- Zewei Long, Jiaqi Wang, Yaqing Wang, Houping Xiao, Fenglong Ma .[FedCon: A Contrastive Framework for Federated Semi-Supervised Learning](https://arxiv.org/pdf/2109.04533) [J]. arXiv preprint arXiv:2109.04533.
- Yuchen Zhao, Payam Barnaghi, Hamed Haddadi .[Multimodal Federated Learning](https://arxiv.org/pdf/2109.04833) [J]. arXiv preprint arXiv:2109.04833.
- Sheeraz A. Alvi, Yi Hong, Salman Durrani .[Utility Fairness for the Differentially Private Federated Learning](https://arxiv.org/pdf/2109.05267) [J]. arXiv preprint arXiv:2109.05267.
- Ranwa Al Mallah, Godwin Badu-Marfo, Bilal Farooq .[On the Initial Behavior Monitoring Issues in Federated Learning](https://arxiv.org/pdf/2109.05385) [J]. arXiv preprint arXiv:2109.05385.
- Bing Luo, Xiang Li, Shiqiang Wang, Jianwei Huang, Leandros Tassiulas .[Cost-Effective Federated Learning in Mobile Edge Networks](https://arxiv.org/pdf/2109.05411) [J]. arXiv preprint arXiv:2109.05411.
- Jingwei Yi, Fangzhao Wu, Chuhan Wu, Ruixuan Liu, Guangzhong Sun, Xing Xie .[Efficient-FedRec: Efficient Federated Learning Framework for Privacy-Preserving News Recommendation](https://arxiv.org/pdf/2109.05446) [J]. arXiv preprint arXiv:2109.05446.
- Jin Wang, Jia Hu, Jed Mills, Geyong Min .[Federated Ensemble Model-based Reinforcement Learning](https://arxiv.org/pdf/2109.05549) [J]. arXiv preprint arXiv:2109.05549.
- Liwei Che, Zewei Long, Jiaqi Wang, Yaqing Wang, Houping Xiao, Fenglong Ma .[FedTriNet: A Pseudo Labeling Method with Three Players for Federated Semi-supervised Learning](https://arxiv.org/pdf/2109.05612) [J]. arXiv preprint arXiv:2109.05612.
- Gang Yan, Hao Wang, Jian Li .[Critical Learning Periods in Federated Learning](https://arxiv.org/pdf/2109.05613) [J]. arXiv preprint arXiv:2109.05613.
- Hongsheng Hu, Zoran Salcic, Lichao Sun, Gillian Dobbie, Xuyun Zhang .[Source Inference Attacks in Federated Learning](https://arxiv.org/pdf/2109.05659) [J]. arXiv preprint arXiv:2109.05659.
- Lingyang Chu, Lanjun Wang, Yanjie Dong, Jian Pei, Zirui Zhou, Yong Zhang .[FedFair: Training Fair Models In Cross-Silo Federated Learning](https://arxiv.org/pdf/2109.05662) [J]. arXiv preprint arXiv:2109.05662.
- Milan Biswal, Abu Saleh Md Tayeen, Satyajayant Misra .[AMI-FML: A Privacy-Preserving Federated Machine Learning Framework for AMI](https://arxiv.org/pdf/2109.05666) [J]. arXiv preprint arXiv:2109.05666.
- Aritra Mitra, Hamed Hassani, George Pappas .[Exploiting Heterogeneity in Robust Federated Best-Arm Identification](https://arxiv.org/pdf/2109.05700) [J]. arXiv preprint arXiv:2109.05700.
- Muhammad Haris, Kheir Eddine Farfar, Markus Stocker, Sören Auer .[Federating Scholarly Infrastructures with GraphQL](https://arxiv.org/pdf/2109.05857) [J]. arXiv preprint arXiv:2109.05857.
- Jian Xu, Shao-Lun Huang, Linqi Song, Tian Lan .[SignGuard: Byzantine-robust Federated Learning through Collaborative Malicious Gradient Filtering](https://arxiv.org/pdf/2109.05872) [J]. arXiv preprint arXiv:2109.05872.
- Dimitrios Michael Manias, Ibrahim Shaer, Li Yang, Abdallah Shami .[Concept Drift Detection in Federated Networked Systems](https://arxiv.org/pdf/2109.06088) [J]. arXiv preprint arXiv:2109.06088.
- Chanho Park, Seunghoon Lee, Namyoon Lee .[Bayesian AirComp with Sign-Alignment Precoding for Wireless Federated Learning](https://arxiv.org/pdf/2109.06579) [J]. arXiv preprint arXiv:2109.06579.
- Ferheen Ayaz, Zhengguo Sheng, Daxin Tian, Yong Liang Guan .[A Blockchain based Federated Learning for Message Dissemination in Vehicular Networks](https://arxiv.org/pdf/2109.06667) [J]. arXiv preprint arXiv:2109.06667.
- Mehmet Emre Ozfatura, Junlin Zhao, Deniz Gündüz .[Fast Federated Edge Learning with Overlapped Communication and Computation and Channel-Aware Fair Client Scheduling](https://arxiv.org/pdf/2109.06710) [J]. arXiv preprint arXiv:2109.06710.
- Lu Wang, Zhi Wu, Wei Gu, Haifeng Qiu, Shuai Lu .[Hierarchical Electricity and Carbon Trading in Transmission and Distribution Networks Based on Virtual Federated Prosumer](https://arxiv.org/pdf/2109.07213) [J]. arXiv preprint arXiv:2109.07213.
- Wei Zhu, Andrew White, Jiebo Luo .[Federated Learning of Molecular Properties in a Heterogeneous Setting](https://arxiv.org/pdf/2109.07258) [J]. arXiv preprint arXiv:2109.07258.
- Nanqing Dong, Irina Voiculescu .[Federated Contrastive Learning for Decentralized Unlabeled Medical Images](https://arxiv.org/pdf/2109.07504) [J]. arXiv preprint arXiv:2109.07504.
- Seok-Ju Hahn, Minwoo Jeong, Junghye Lee .[Subspace Learning for Personalized Federated Optimization](https://arxiv.org/pdf/2109.07628) [J]. arXiv preprint arXiv:2109.07628.
- Yucheng Ding, Chaoyue Niu, Fan Wu, Shaojie Tang, Chengfei Lv, Yanghe Feng, Guihai Chen .[Federated Submodel Averaging](https://arxiv.org/pdf/2109.07704) [J]. arXiv preprint arXiv:2109.07704.
- Dengsheng Chen, Vince Tan, Zhilin Lu, Jie Hu .[OpenFed: A Comprehensive and Versatile Open-Source Federated Learning Framework](https://arxiv.org/pdf/2109.07852) [J]. arXiv preprint arXiv:2109.07852.
- Yae Jee Cho, Jianyu Wang, Tarun Chiruvolu, Gauri Joshi .[Personalized Federated Learning for Heterogeneous Clients with Clustered Knowledge Transfer](https://arxiv.org/pdf/2109.08119) [J]. arXiv preprint arXiv:2109.08119.
- Changxin Liu, Zirui Zhou, Yang Shi, Jian Pei, Lingyang Chu, Yong Zhang .[Achieving Model Fairness in Vertical Federated Learning](https://arxiv.org/pdf/2109.08344) [J]. arXiv preprint arXiv:2109.08344.
- Tahseen Rabbani, Brandon Feng, Yifan Yang, Arjun Rajkumar, Amitabh Varshney, Furong Huang .[Comfetch: Federated Learning of Large Networks on Memory-Constrained Clients via Sketching](https://arxiv.org/pdf/2109.08346) [J]. arXiv preprint arXiv:2109.08346.
- Borja Rodríguez-Gálvez, Filip Granqvist, Rogier van Dalen, Matt Seigel .[Enforcing fairness in private federated learning via the modified method of differential multipliers](https://arxiv.org/pdf/2109.08604) [J]. arXiv preprint arXiv:2109.08604.
- Haizhou Du, Xiaojie Feng, Qiao Xiang, Haoyu Liu .[Toward Efficient Federated Learning in Multi-Channeled Mobile Edge Network with Layerd Gradient Compression](https://arxiv.org/pdf/2109.08819) [J]. arXiv preprint arXiv:2109.08819.
- Zhenan Fan, Huang Fang, Zirui Zhou, Jian Pei, Michael P. Friedlander, Changxin Liu, Yong Zhang .[Improving Fairness for Data Valuation in Federated Learning](https://arxiv.org/pdf/2109.09046) [J]. arXiv preprint arXiv:2109.09046.
- Shuzhen Chen, Dongxiao Yu, Yifei Zou, Jiguo Yu, Xiuzhen Cheng .[Decentralized Wireless Federated Learning with Differential Privacy](https://arxiv.org/pdf/2109.09142) [J]. arXiv preprint arXiv:2109.09142.
- Md Tamjid Hossain, Shafkat Islam, Shahriar Badsha, Haoting Shen .[DeSMP: Differential Privacy-exploited Stealthy Model Poisoning Attacks in Federated Learning](https://arxiv.org/pdf/2109.09955) [J]. arXiv preprint arXiv:2109.09955.
- Thinh Quang Dinh, Diep N. Nguyen, Dinh Thai Hoang, Pham Tran Vu, Eryk Dutkiewicz .[Enabling Large-Scale Federated Learning over Wireless Edge Networks](https://arxiv.org/pdf/2109.10489) [J]. arXiv preprint arXiv:2109.10489.
- Zeyuan Yin, Ye Yuan, Panfeng Guo, Pan Zhou .[Backdoor Attacks on Federated Learning with Lottery Ticket Hypothesis](https://arxiv.org/pdf/2109.10512) [J]. arXiv preprint arXiv:2109.10512.
- Thinh Quang Dinh, Diep N. Nguyen, Dinh Thai Hoang, Pham Tran Vu, Eryk Dutkiewicz .[In-network Computation for Large-scale Federated Learning over Wireless Edge Networks](https://arxiv.org/pdf/2109.10903) [J]. arXiv preprint arXiv:2109.10903.
- Pietro Cassarà, Alberto Gotta, Lorenzo Valerio .[Federated Feature Selection for Cyber-Physical Systems of Systems](https://arxiv.org/pdf/2109.11323) [J]. arXiv preprint arXiv:2109.11323.
- Eugenio Lomurno, Leonardo Di Perna, Lorenzo Cazzella, Stefano Samele, Matteo Matteucci .[A Generative Federated Learning Framework for Differential Privacy](https://arxiv.org/pdf/2109.12062) [J]. arXiv preprint arXiv:2109.12062.
- Peter Z. Vaillancourt, Bennett Wineholt, Tristan J. Shepherd, Sara C. Pryor, Jeffrey Lantz, Richard Knepper, Rich Wolski, Christopher R. Myers, Ben Trumbore, Resa Reynolds, Jodie Sprouse, David Lifka .[Aristotle Cloud Federation: Container Runtimes Technical Report](https://arxiv.org/pdf/2109.12186) [J]. arXiv preprint arXiv:2109.12186.
- Xutong Mu, Yulong Shen, Ke Cheng, Xueli Geng, Jiaxuan Fu, Tao Zhang, Zhiwei Zhang .[FedProc: Prototypical Contrastive Federated Learning on Non-IID data](https://arxiv.org/pdf/2109.12273) [J]. arXiv preprint arXiv:2109.12273.
- Qingsong Zhang, Bin Gu, Cheng Deng, Songxiang Gu, Liefeng Bo, Jian Pei, Heng Huang .[AsySQN: Faster Vertical Federated Learning Algorithms with Better Computation Resource Utilization](https://arxiv.org/pdf/2109.12519) [J]. arXiv preprint arXiv:2109.12519.
- Antoine Boutet, Thomas Lebrun, Jan Aalmoes, Adrien Baud .[MixNN: Protection of Federated Learning Against Inference Attacks by Mixing Neural Network Layers](https://arxiv.org/pdf/2109.12550) [J]. arXiv preprint arXiv:2109.12550.
- Hanlin Gu, Lixin Fan, Bowen Li, Yan Kang, Yuan Yao, Qiang Yang .[Federated Deep Learning with Bayesian Privacy](https://arxiv.org/pdf/2109.13012) [J]. arXiv preprint arXiv:2109.13012.
- Lixin Fan, Bowen Li, Hanlin Gu, Jie Li, Qiang Yang .[FedIPR: Ownership Verification for Federated Deep Neural Network Models](https://arxiv.org/pdf/2109.13236) [J]. arXiv preprint arXiv:2109.13236.
- Wentao Li, Jiayi Tong, Md.Monowar Anjum, Noman Mohammed, Yong Chen, Xiaoqian Jiang .[Federated Learning Algorithms for Generalized Mixed-effects Model (GLMM) on Horizontally Partitioned Data from Distributed Sources](https://arxiv.org/pdf/2109.14046) [J]. arXiv preprint arXiv:2109.14046.
- Chien-Sheng Yang, Jinhyun So, Chaoyang He, Songze Li, Qian Yu, Salman Avestimehr .[LightSecAgg: Rethinking Secure Aggregation in Federated Learning](https://arxiv.org/pdf/2109.14236) [J]. arXiv preprint arXiv:2109.14236.
- Oscar J. Ciceri, Carlos A. Astudillo, Zuqing Zhu, Nelson L. S. da Fonseca .[Federated Learning over Next-Generation Ethernet Passive Optical Networks](https://arxiv.org/pdf/2109.14593) [J]. arXiv preprint arXiv:2109.14593.
- Haizhou Shi, Youcai Zhang, Zijin Shen, Siliang Tang, Yaqian Li, Yandong Guo, Yueting Zhuang .[Federated Self-Supervised Contrastive Learning via Ensemble Similarity Distillation](https://arxiv.org/pdf/2109.14611) [J]. arXiv preprint arXiv:2109.14611.
- G. Araniti, A. Iera, A. Molinaro, S. Pizzi, F. Rinaldi .[Opportunistic Federation of CubeSat Constellations: a Game-Changing Paradigm Enabling Enhanced IoT Services in the Sky](https://arxiv.org/pdf/2109.14904) [J]. arXiv preprint arXiv:2109.14904.
- Wentao Yu, Jan Freiwald, Sören Tewes, Fabien Huennemeyer, Dorothea Kolossa .[Federated Learning in ASR: Not as Easy as You Think](https://arxiv.org/pdf/2109.15108) [J]. arXiv preprint arXiv:2109.15108.
- Siddhartha Kumar, Reent Schlegel, Eirik Rosnes, Alexandre Graell i Amat .[Coding for Straggler Mitigation in Federated Learning](https://arxiv.org/pdf/2109.15226) [J]. arXiv preprint arXiv:2109.15226.
- Dingzhu Wen, Ki-Jun Jeon, Kaibin Huang .[Federated Dropout -- A Simple Approach for Enabling Federated Learning on Resource Constrained Devices](https://arxiv.org/pdf/2109.15258) [J]. arXiv preprint arXiv:2109.15258.
- Ali Raza, Kim Phuc Tran, Ludovic Koehl, Shujun Li, Xianyi Zeng, Khaled Benzaidi .[Lightweight Transformer in Federated Setting for Human Activity Recognition](https://arxiv.org/pdf/2110.00244) [J]. arXiv preprint arXiv:2110.00244.
- Zhen Chen, Meilu Zhu, Chen Yang, Yixuan Yuan .[Personalized Retrogress-Resilient Framework for Real-World Medical Federated Learning](https://arxiv.org/pdf/2110.00394) [J]. arXiv preprint arXiv:2110.00394.
- Yahya H. Ezzeldin, Shen Yan, Chaoyang He, Emilio Ferrara, Salman Avestimehr .[FairFed: Enabling Group Fairness in Federated Learning](https://arxiv.org/pdf/2110.00857) [J]. arXiv preprint arXiv:2110.00857.
- Do Le Quoc, Christof Fetzer .[SecFL: Confidential Federated Learning using TEEs](https://arxiv.org/pdf/2110.00981) [J]. arXiv preprint arXiv:2110.00981.
- Kavya Kopparapu, Eric Lin .[TinyFedTL: Federated Transfer Learning on Tiny Devices](https://arxiv.org/pdf/2110.01107) [J]. arXiv preprint arXiv:2110.01107.
- Alexandros Karargyris, Renato Umeton, Micah J. Sheller, Alejandro Aristizabal, Johnu George, Srini Bala, Daniel J. Beutel, Victor Bittorf, Akshay Chaudhari, Alexander Chowdhury, Cody Coleman, Bala Desinghu, Gregory Diamos, Debo Dutta, Diane Feddema, Grigori Fursin, Junyi Guo, Xinyuan Huang, David Kanter, Satyananda Kashyap, Nicholas Lane, Indranil Mallick, Pietro Mascagni, Virendra Mehta, Vivek Natarajan, Nikola Nikolov, Nicolas Padoy, Gennady Pekhimenko, Vijay Janapa Reddi, G Anthony Reina, Pablo Ribalta, Jacob Rosenthal, Abhishek Singh, Jayaraman J. Thiagarajan, Anna Wuest, Maria Xenochristou, Daguang Xu, Poonam Yadav, Michael Rosenthal, Massimo Loda, Jason M. Johnson, Peter Mattson .[MedPerf: Open Benchmarking Platform for Medical Artificial Intelligence using Federated Evaluation](https://arxiv.org/pdf/2110.01406) [J]. arXiv preprint arXiv:2110.01406.
- Chuanhao Li, Hongning Wang .[Asynchronous Upper Confidence Bound Algorithms for Federated Linear Bandits](https://arxiv.org/pdf/2110.01463) [J]. arXiv preprint arXiv:2110.01463.
- Priyam Basu, Tiasa Singha Roy, Rakshit Naidu, Zumrut Muftuoglu .[Privacy enabled Financial Text Classification using Differential Privacy and Federated Learning](https://arxiv.org/pdf/2110.01643) [J]. arXiv preprint arXiv:2110.01643.
- Afroditi Papadaki, Natalia Martinez, Martin Bertran, Guillermo Sapiro, Miguel Rodrigues .[Federating for Learning Group Fair Models](https://arxiv.org/pdf/2110.01999) [J]. arXiv preprint arXiv:2110.01999.
- Jinhyun So, Ramy E. Ali, Başak Güler, A. Salman Avestimehr .[Secure Aggregation for Buffered Asynchronous Federated Learning](https://arxiv.org/pdf/2110.02177) [J]. arXiv preprint arXiv:2110.02177.
- Zhilin Wang, Qin Hu .[Blockchain-based Federated Learning: A Comprehensive Survey](https://arxiv.org/pdf/2110.02182) [J]. arXiv preprint arXiv:2110.02182.
- Yuan-Ai Xie, Jiawen Kang, Dusit Niyato, Nguyen Thi Thanh Van, Nguyen Cong Luong, Zhixin Liu, Han Yu .[Securing Federated Learning: A Covert Communication-based Approach](https://arxiv.org/pdf/2110.02221) [J]. arXiv preprint arXiv:2110.02221.
- Yuzhi Yang, Zhaoyang Zhang, Qianqian Yang .[Communication-Efficient Federated Learning with Binary Neural Networks](https://arxiv.org/pdf/2110.02226) [J]. arXiv preprint arXiv:2110.02226.
- Linping Qu, Shenghui Song, Chi-Ying Tsui .[FedDQ: Communication-Efficient Federated Learning with Descending Quantization](https://arxiv.org/pdf/2110.02291) [J]. arXiv preprint arXiv:2110.02291.
- Rishabh Bhardwaj, Tushar Vaidya, Soujanya Poria .[Federated Distillation of Natural Language Understanding with Confident Sinkhorns](https://arxiv.org/pdf/2110.02432) [J]. arXiv preprint arXiv:2110.02432.
- Chaoyang He, Zhengyu Yang, Erum Mushtaq, Sunwoo Lee, Mahdi Soltanolkotabi, Salman Avestimehr .[SSFL: Tackling Label Deficiency in Federated Learning via Personalized Self-Supervision](https://arxiv.org/pdf/2110.02470) [J]. arXiv preprint arXiv:2110.02470.
- Kai Yue, Richeng Jin, Chau-Wai Wong, Huaiyu Dai .[Federated Learning via Plurality Vote](https://arxiv.org/pdf/2110.02998) [J]. arXiv preprint arXiv:2110.02998.
- Mohammad Aghapour, Aidin Ferdowsi, Walid Saad .[Two-Bit Aggregation for Communication Efficient and Differentially Private Federated Learning](https://arxiv.org/pdf/2110.03017) [J]. arXiv preprint arXiv:2110.03017.
- Huanle Zhang, Mi Zhang, Xin Liu, Prasant Mohapatra, Michael DeLucia .[Automatic Tuning of Federated Learning Hyper-Parameters from System Perspective](https://arxiv.org/pdf/2110.03061) [J]. arXiv preprint arXiv:2110.03061.
- Shimaa Naser, Lina Bariah, Sami Muhaidat, Mahmoud Al-Qutayri, Ernesto Damiani, Merouane Debbah, Paschalis C. Sofotasios .[Towards Federated Learning-Enabled Visible Light Communication in 6G Systems](https://arxiv.org/pdf/2110.03319) [J]. arXiv preprint arXiv:2110.03319.
- Hakim Sidahmed, Zheng Xu, Ankush Garg, Yuan Cao, Mingqing Chen .[Efficient and Private Federated Learning with Partially Trainable Networks](https://arxiv.org/pdf/2110.03450) [J]. arXiv preprint arXiv:2110.03450.
- Michael Kamp (1), Jonas Fischer (2), Jilles Vreeken (1) ((1) CISPA Helmholtz Center for Information Security, (2) Max Planck Institute for Informatics) .[Federated Learning from Small Datasets](https://arxiv.org/pdf/2110.03469) [J]. arXiv preprint arXiv:2110.03469.
- Dhruv Guliani, Lillian Zhou, Changwan Ryu, Tien-Ju Yang, Harry Zhang, Yonghui Xiao, Francoise Beaufays, Giovanni Motta .[Enabling On-Device Training of Speech Recognition Models with Federated Dropout](https://arxiv.org/pdf/2110.03634) [J]. arXiv preprint arXiv:2110.03634.
- Kai Yue, Richeng Jin, Ryan Pilgrim, Chau-Wai Wong, Dror Baron, Huaiyu Dai .[Neural Tangent Kernel Empowered Federated Learning](https://arxiv.org/pdf/2110.03681) [J]. arXiv preprint arXiv:2110.03681.
- Thippa Reddy Gadekallu, Quoc-Viet Pham, Thien Huynh-The, Sweta Bhattacharya, Praveen Kumar Reddy Maddikunta, Madhusanka Liyanage .[Federated Learning for Big Data: A Survey on Opportunities, Applications, and Future Directions](https://arxiv.org/pdf/2110.04160) [J]. arXiv preprint arXiv:2110.04160.
- Hamid Mozaffari, Virat Shejwalkar, Amir Houmansadr .[FSL: Federated Supermask Learning](https://arxiv.org/pdf/2110.04350) [J]. arXiv preprint arXiv:2110.04350.
- Naman Agarwal, Peter Kairouz, Ziyu Liu .[The Skellam Mechanism for Differentially Private Federated Learning](https://arxiv.org/pdf/2110.04995) [J]. arXiv preprint arXiv:2110.04995.
- Luong Trung Nguyen, Junhan Kim, Byonghyo Shim .[Gradual Federated Learning with Simulated Annealing](https://arxiv.org/pdf/2110.05178) [J]. arXiv preprint arXiv:2110.05178.
- Chuanting Zhang, Shuping Dang, Basem Shihada, Mohamed-Slim Alouini .[Dual Attention-Based Federated Learning for Wireless Traffic Prediction](https://arxiv.org/pdf/2110.05183) [J]. arXiv preprint arXiv:2110.05183.
- Hui-Po Wang, Sebastian U. Stich, Yang He, Mario Fritz .[ProgFed: Effective, Communication, and Computation Efficient Federated Learning by Progressive Training](https://arxiv.org/pdf/2110.05323) [J]. arXiv preprint arXiv:2110.05323.
- Tien-Ju Yang, Dhruv Guliani, Françoise Beaufays, Giovanni Motta .[Partial Variable Training for Efficient On-Device Federated Learning](https://arxiv.org/pdf/2110.05607) [J]. arXiv preprint arXiv:2110.05607.
- Anh Nguyen, Tuong Do, Minh Tran, Binh X. Nguyen, Chien Duong, Tu Phan, Erman Tjiputra, Quang D. Tran .[Deep Federated Learning for Autonomous Driving](https://arxiv.org/pdf/2110.05754) [J]. arXiv preprint arXiv:2110.05754.
- Yuwei Sun, Ng Chong, Hideya Ochiai .[Privacy-Preserving Phishing Email Detection Based on Federated Learning and LSTM](https://arxiv.org/pdf/2110.06025) [J]. arXiv preprint arXiv:2110.06025.
- Yujie Lu, Chao Huang, Huanli Zhan, Yong Zhuang .[Federated Natural Language Generation for Personalized Dialogue System](https://arxiv.org/pdf/2110.06419) [J]. arXiv preprint arXiv:2110.06419.
- Jinyin Chen, Guohan Huang, Shanqing Yu, Wenrong Jiang, Chen Cui .[Graph-Fraudster: Adversarial Attacks on Graph Neural Network Based Vertical Federated Learning](https://arxiv.org/pdf/2110.06468) [J]. arXiv preprint arXiv:2110.06468.
- Vinay Chakravarthi Gogineni, Stefan Werner, Yih-Fang Huang, Anthony Kuh .[Communication-Efficient Online Federated Learning Framework for Nonlinear Regression](https://arxiv.org/pdf/2110.06556) [J]. arXiv preprint arXiv:2110.06556.
- Martin Beaussart, Felix Grimberg, Mary-Anne Hartley, Martin Jaggi .[WAFFLE: Weighted Averaging for Personalized Federated Learning](https://arxiv.org/pdf/2110.06978) [J]. arXiv preprint arXiv:2110.06978.
- Di-Chun Liang, Chun-Hung Liu, Rung-Hung Gau, Lu Wei .[Federated Learning Over Cellular-Connected UAV Networks with Non-IID Datasets](https://arxiv.org/pdf/2110.07077) [J]. arXiv preprint arXiv:2110.07077.
- Dinh C. Nguyen, Ming Ding, Pubudu N. Pathirana, Aruna Seneviratne, Albert Y. Zomaya .[Federated Learning for COVID-19 Detection with Generative Adversarial Networks in Edge Cloud Computing](https://arxiv.org/pdf/2110.07136) [J]. arXiv preprint arXiv:2110.07136.
- Ziyue Jiang, Yi Ren, Ming Lei, Zhou Zhao .[FedSpeech: Federated Text-to-Speech with Continual Learning](https://arxiv.org/pdf/2110.07216) [J]. arXiv preprint arXiv:2110.07216.
- Yi Liu, Yuanshao Zhu, James J.Q. Yu .[Resource-constrained Federated Edge Learning with Heterogeneous Data: Formulation and Analysis](https://arxiv.org/pdf/2110.07567) [J]. arXiv preprint arXiv:2110.07567.
- Debaditya Shome, Omer Waqar, Wali Ullah Khan .[Federated learning and next generation wireless communications: A survey on bidirectional relationship](https://arxiv.org/pdf/2110.07649) [J]. arXiv preprint arXiv:2110.07649.
- Charles Lu, Jayasheree Kalpathy-Cramer .[Distribution-Free Federated Learning with Conformal Predictions](https://arxiv.org/pdf/2110.07661) [J]. arXiv preprint arXiv:2110.07661.
- Jieming Bian, Zhu Fu, Jie Xu .[FedSEAL: Semi-Supervised Federated Learning with Self-Ensemble Learning and Negative Learning](https://arxiv.org/pdf/2110.07829) [J]. arXiv preprint arXiv:2110.07829.
- Koji Matsuda, Yuya Sasaki, Chuan Xiao, Makoto Onizuka .[FedMe: Federated Learning via Model Exchange](https://arxiv.org/pdf/2110.07868) [J]. arXiv preprint arXiv:2110.07868.
- Man Zeng, Dandan Li, Pei Zhang, Kun Xie, Xiaohong Huang .[Federated Route Leak Detection in Inter-domain Routing with Privacy Guarantee](https://arxiv.org/pdf/2110.07964) [J]. arXiv preprint arXiv:2110.07964.
- Stephanie Holly, Thomas Hiessl, Safoura Rezapour Lakani, Daniel Schall, Clemens Heitzinger, Jana Kemnitz .[Evaluation of Hyperparameter-Optimization Approaches in an Industrial Federated Learning System](https://arxiv.org/pdf/2110.08202) [J]. arXiv preprint arXiv:2110.08202.
- Qin Hu, Shengling Wang, Zeihui Xiong, Xiuzhen Cheng .[Nothing Wasted: Full Contribution Enforcement in Federated Edge Learning](https://arxiv.org/pdf/2110.08330) [J]. arXiv preprint arXiv:2110.08330.
- Jun Luo, Shandong Wu .[FedSLD: Federated Learning with Shared Label Distribution for Medical Image Classification](https://arxiv.org/pdf/2110.08378) [J]. arXiv preprint arXiv:2110.08378.
- Jun Luo, Shandong Wu .[Adapt to Adaptation: Learning Personalization for Cross-Silo Federated Learning](https://arxiv.org/pdf/2110.08394) [J]. arXiv preprint arXiv:2110.08394.
- Yan Shen, Jian Du, Han Zhao, Benyu Zhang, Zhanghexuan Ji, Mingchen Gao .[FedMM: Saddle Point Optimization for Federated Adversarial Domain Adaptation](https://arxiv.org/pdf/2110.08477) [J]. arXiv preprint arXiv:2110.08477.
- Qin Hu, Zhilin Wang, Minghui Xu, Xiuzhen Cheng .[Blockchain and Federated Edge Learning for Privacy-Preserving Mobile Crowdsensing](https://arxiv.org/pdf/2110.08671) [J]. arXiv preprint arXiv:2110.08671.
- Pinyarash Pinyoanuntapong, Tagore Pothuneedi, Ravikumar Balakrishnan, Minwoo Lee, Chen Chen, Pu Wang .[Sim-to-Real Transfer in Multi-agent Reinforcement Networking for Federated Edge Computing](https://arxiv.org/pdf/2110.08952) [J]. arXiv preprint arXiv:2110.08952.
- Qimei Chen, Zehua You, Hao Jiang .[Semi-asynchronous Hierarchical Federated Learning for Cooperative Intelligent Transportation Systems](https://arxiv.org/pdf/2110.09073) [J]. arXiv preprint arXiv:2110.09073.
- Jiahui Geng, Yongli Mou, Feifei Li, Qing Li, Oya Beyan, Stefan Decker, Chunming Rong .[Towards General Deep Leakage in Federated Learning](https://arxiv.org/pdf/2110.09074) [J]. arXiv preprint arXiv:2110.09074.
- Ignavier Ng, Kun Zhang .[Towards Federated Bayesian Network Structure Learning with Continuous Optimization](https://arxiv.org/pdf/2110.09356) [J]. arXiv preprint arXiv:2110.09356.
- Xin Fan, Yue Wang, Yan Huo, Zhi Tian .[BEV-SGD: Best Effort Voting SGD for Analog Aggregation Based Federated Learning against Byzantine Attackers](https://arxiv.org/pdf/2110.09660) [J]. arXiv preprint arXiv:2110.09660.
- Tae Jin Park, Kenichi Kumatani, Dimitrios Dimitriadis .[Tackling Dynamics in Federated Incremental Learning with Variational Embedding Rehearsal](https://arxiv.org/pdf/2110.09695) [J]. arXiv preprint arXiv:2110.09695.
- Mohamad Mestoukirdi, Matteo Zecchin, David Gesbert, Qianrui Li, Nicolas Gresset .[User-Centric Federated Learning](https://arxiv.org/pdf/2110.09869) [J]. arXiv preprint arXiv:2110.09869.
- Chan Yun Hin, Ngai Edith .[FedHe: Heterogeneous Models and Communication-Efficient Federated Learning](https://arxiv.org/pdf/2110.09910) [J]. arXiv preprint arXiv:2110.09910.
- Meirui Jiang, Xiaofei Zhang, Michael Kamp, Xiaoxiao Li, Qi Dou .[TsmoBN: Interventional Generalization for Unseen Clients in Federated Learning](https://arxiv.org/pdf/2110.09974) [J]. arXiv preprint arXiv:2110.09974.
- Atul Sharma, Wei Chen, Joshua Zhao, Qiang Qiu, Somali Chaterji, Saurabh Bagchi .[TESSERACT: Gradient Flip Score to Secure Federated Learning Against Model Poisoning Attacks](https://arxiv.org/pdf/2110.10108) [J]. arXiv preprint arXiv:2110.10108.
- Sannara Ek, François Portet, Philippe Lalanda, German Vega .[A Federated Learning Aggregation Algorithm for Pervasive Computing: Evaluation and Comparison](https://arxiv.org/pdf/2110.10223) [J]. arXiv preprint arXiv:2110.10223.
- Sunwoo Lee, Tuo Zhang, Chaoyang He, Salman Avestimehr .[Layer-wise Adaptive Model Aggregation for Scalable Federated Learning](https://arxiv.org/pdf/2110.10302) [J]. arXiv preprint arXiv:2110.10302.
- Shijie Zhang, Hongzhi Yin, Tong Chen, Zi Huang, Quoc Viet Hung Nguyen, Lizhen Cui .[PipAttack: Poisoning Federated Recommender Systems forManipulating Item Promotion](https://arxiv.org/pdf/2110.10926) [J]. arXiv preprint arXiv:2110.10926.
- Weijing Chen, Guoqiang Ma, Tao Fan, Yan Kang, Qian Xu, Qiang Yang .[SecureBoost+ : A High Performance Gradient Boosting Tree Framework for Large Scale Vertical Federated Learning](https://arxiv.org/pdf/2110.10927) [J]. arXiv preprint arXiv:2110.10927.
- Joost Verbraeken, Martijn de Vos, Johan Pouwelse .[Bristle: Decentralized Federated Learning in Byzantine, Non-i.i.d. Environments](https://arxiv.org/pdf/2110.11006) [J]. arXiv preprint arXiv:2110.11006.
- Sijie Cheng, Jingwen Wu, Yanghua Xiao, Yang Liu, Yang Liu .[FedGEMS: Federated Learning of Larger Server Models via Selective Knowledge Fusion](https://arxiv.org/pdf/2110.11027) [J]. arXiv preprint arXiv:2110.11027.
- Akash Dhasade, Anne-Marie Kermarrec, Rafael Pires .[Guess what? You can boost Federated Learning for free](https://arxiv.org/pdf/2110.11486) [J]. arXiv preprint arXiv:2110.11486.
- Xiaolan Gu, Ming Li, Li Xiong .[PRECAD: Privacy-Preserving and Robust Federated Learning via Crypto-Aided Differential Privacy](https://arxiv.org/pdf/2110.11578) [J]. arXiv preprint arXiv:2110.11578.
- Bingyan Liu, Yifeng Cai, Ziqi Zhang, Yuanchun Li, Leye Wang, Ding Li, Yao Guo, Xiangqun Chen .[DistFL: Distribution-aware Federated Learning for Mobile Scenarios](https://arxiv.org/pdf/2110.11619) [J]. arXiv preprint arXiv:2110.11619.
- Zhuotao Lian, Qinglin Yang, Qingkui Zeng, Chunhua Su .[WebFed: Cross-platform Federated Learning Framework Based on Web Browser with Local Differential Privacy](https://arxiv.org/pdf/2110.11646) [J]. arXiv preprint arXiv:2110.11646.
- Wanchuang Zhu, Benjamin Zi Hao Zhao, Simon Luo, Ke Deng .[MANDERA: Malicious Node Detection in Federated Learning via Ranking](https://arxiv.org/pdf/2110.11736) [J]. arXiv preprint arXiv:2110.11736.
- Hao Chen, Shaocheng Huang, Deyou Zhang, Ming Xiao, Mikael Skoglund, H. Vincent Poor .[Federated Learning over Wireless IoT Networks with Optimized Communication and Resources](https://arxiv.org/pdf/2110.11775) [J]. arXiv preprint arXiv:2110.11775.
- Junxiao Wang, Song Guo, Xin Xie, Heng Qi .[Federated Unlearning via Class-Discriminative Pruning](https://arxiv.org/pdf/2110.11794) [J]. arXiv preprint arXiv:2110.11794.
- Lokesh Nagalapatti, Ramasuri Narayanam .[Game of Gradients: Mitigating Irrelevant Clients in Federated Learning](https://arxiv.org/pdf/2110.12257) [J]. arXiv preprint arXiv:2110.12257.
- Zhenwei Dai, Chen Dun, Yuxin Tang, Anastasios Kyrillidis, Anshumali Shrivastava .[Federated Multiple Label Hashing (FedMLH): Communication Efficient Federated Learning on Extreme Classification Tasks](https://arxiv.org/pdf/2110.12292) [J]. arXiv preprint arXiv:2110.12292.
- Rui Shao, Bochao Zhang, Pong C. Yuen, Vishal M. Patel .[Federated Test-Time Adaptive Face Presentation Attack Detection with Dual-Phase Privacy Preservation](https://arxiv.org/pdf/2110.12613) [J]. arXiv preprint arXiv:2110.12613.
- Xumin Huang, Peichun Li, Rong Yu, Yuan Wu, Kan Xie, Shengli Xie .[FedParking: A Federated Learning based Parking Space Estimation with Parked Vehicle assisted Edge Computing](https://arxiv.org/pdf/2110.12876) [J]. arXiv preprint arXiv:2110.12876.
- Yangchen Li, Ying Cui, Vincent Lau .[Optimization-Based GenQSGD for Federated Edge Learning](https://arxiv.org/pdf/2110.12987) [J]. arXiv preprint arXiv:2110.12987.
- Liam Fowl, Jonas Geiping, Wojtek Czaja, Micah Goldblum, Tom Goldstein .[Robbing the Fed: Directly Obtaining Private Data in Federated Learning with Modified Models](https://arxiv.org/pdf/2110.13057) [J]. arXiv preprint arXiv:2110.13057.
- Zhe Zhang, Shiyao Ma, Jiangtian Nie, Yi Wu, Qiang Yan, Xiaoke Xu, Dusit Niyato .[Semi-Supervised Federated Learning with non-IID Data: Algorithm and System Design](https://arxiv.org/pdf/2110.13388) [J]. arXiv preprint arXiv:2110.13388.
- Xiaohu Wu, Han Yu .[MarS-FL: A Market Share-based Decision Support Framework for Participation in Federated Learning](https://arxiv.org/pdf/2110.13464) [J]. arXiv preprint arXiv:2110.13464.
- Trang-Thi Ho, Yennun-Huang .[DPCOVID: Privacy-Preserving Federated Covid-19 Detection](https://arxiv.org/pdf/2110.13760) [J]. arXiv preprint arXiv:2110.13760.
- Jingwei Sun, Ang Li, Louis DiValentin, Amin Hassanzadeh, Yiran Chen, Hai Li .[FL-WBC: Enhancing Robustness against Model Poisoning Attacks in Federated Learning from a Client Perspective](https://arxiv.org/pdf/2110.13864) [J]. arXiv preprint arXiv:2110.13864.
- Flint Xiaofeng Fan, Yining Ma, Zhongxiang Dai, Wei Jing, Cheston Tan, Bryan Kian Hsiang Low .[Fault-Tolerant Federated Reinforcement Learning with Theoretical Guarantee](https://arxiv.org/pdf/2110.14074) [J]. arXiv preprint arXiv:2110.14074.
- Zhongxiang Dai, Bryan Kian Hsiang Low, Patrick Jaillet .[Differentially Private Federated Bayesian Optimization with Distributed Exploration](https://arxiv.org/pdf/2110.14153) [J]. arXiv preprint arXiv:2110.14153.
- Ruiquan Huang, Weiqiang Wu, Jing Yang, Cong Shen .[Federated Linear Contextual Bandits](https://arxiv.org/pdf/2110.14177) [J]. arXiv preprint arXiv:2110.14177.
- Muhammad Tahir Munir, Muhammad Mustansar Saeed, Mahad Ali, Zafar Ayyub Qazi, Ihsan Ayyub Qazi .[FedPrune: Towards Inclusive Federated Learning](https://arxiv.org/pdf/2110.14205) [J]. arXiv preprint arXiv:2110.14205.
- Honglin Yuan, Warren Morningstar, Lin Ning, Karan Singhal .[What Do We Mean by Generalization in Federated Learning?](https://arxiv.org/pdf/2110.14216) [J]. arXiv preprint arXiv:2110.14216.
- Huayan Guo, Yifan Zhu, Haoyu Ma, Vincent K. N. Lau, Kaibin Huang, Xiaofan Li, Huabin Nong, Mingyu Zhou .[Over-the-Air Aggregation for Federated Learning: Waveform Superposition and Prototype Validation](https://arxiv.org/pdf/2110.14285) [J]. arXiv preprint arXiv:2110.14285.
- Chun-Hung Liu, Kai-Ten Feng, Lu Wei, Yu Luo .[Spatio-Temporal Federated Learning for Massive Wireless Edge Networks](https://arxiv.org/pdf/2110.14578) [J]. arXiv preprint arXiv:2110.14578.
- Shuang Luo, Didi Zhu, Zexi Li, Chao Wu .[Ensemble Federated Adversarial Training with Non-IID data](https://arxiv.org/pdf/2110.14814) [J]. arXiv preprint arXiv:2110.14814.
- Xiao Jin, Pin-Yu Chen, Chia-Yi Hsu, Chia-Mu Yu, Tianyi Chen .[CAFE: Catastrophic Data Leakage in Vertical Federated Learning](https://arxiv.org/pdf/2110.15122) [J]. arXiv preprint arXiv:2110.15122.
- Abdullah M. Alqahtani, Barzan Yosuf, Sanaa H. Mohamed, Taisir E.H. El-Gorashi, Jaafar M.H. Elmirghani .[Energy Efficient Resource Allocation in Federated Fog Computing Networks](https://arxiv.org/pdf/2110.15204) [J]. arXiv preprint arXiv:2110.15204.
- Andrei Afonin, Sai Praneeth Karimireddy .[Towards Model Agnostic Federated Learning Using Knowledge Distillation](https://arxiv.org/pdf/2110.15210) [J]. arXiv preprint arXiv:2110.15210.
- Nasser Aldaghri, Hessam Mahdavifar, Ahmad Beirami .[FeO2: Federated Learning with Opt-Out Differential Privacy](https://arxiv.org/pdf/2110.15252) [J]. arXiv preprint arXiv:2110.15252.
- Shenglong Zhou, Geoffrey Ye Li .[Communication-Efficient ADMM-based Federated Learning](https://arxiv.org/pdf/2110.15318) [J]. arXiv preprint arXiv:2110.15318.
- Yongding Tian, Zhuoran Guo, Jiaxuan Zhang, Zaid Al-Ars .[DFL: High-Performance Blockchain-Based Federated Learning](https://arxiv.org/pdf/2110.15457) [J]. arXiv preprint arXiv:2110.15457.
- Yuchen Zeng, Hongxu Chen, Kangwook Lee .[Improving Fairness via Federated Learning](https://arxiv.org/pdf/2110.15545) [J]. arXiv preprint arXiv:2110.15545.
- Zhiguo Wang, Xintong Wang, Ruoyu Sun, Tsung-Hui Chang .[Federated Semi-Supervised Learning with Class Distribution Mismatch](https://arxiv.org/pdf/2111.00010) [J]. arXiv preprint arXiv:2111.00010.
- Oualid Zari, Chuan Xu, Giovanni Neglia .[Efficient passive membership inference attack in federated learning](https://arxiv.org/pdf/2111.00430) [J]. arXiv preprint arXiv:2111.00430.
- Robert Hönig, Yiren Zhao, Robert Mullins .[DAdaQuant: Doubly-adaptive quantization for communication-efficient Federated Learning](https://arxiv.org/pdf/2111.00465) [J]. arXiv preprint arXiv:2111.00465.
- Shaoming Huang, Pengfei Zhang, Yijie Mao, Lixiang Lian, Yuanming Shi .[Wireless Federated Learning over MIMO Networks: Joint Device Scheduling and Beamforming Design](https://arxiv.org/pdf/2111.00470) [J]. arXiv preprint arXiv:2111.00470.
- Pavana Prakash, Jiahao Ding, Maoqiang Wu, Minglei Shu, Rong Yu, Miao Pan .[To Talk or to Work: Delay Efficient Federated Learning over Mobile Edge Devices](https://arxiv.org/pdf/2111.00637) [J]. arXiv preprint arXiv:2111.00637.
- Manupriya Gupta, Pavas Goyal, Rohit Verma, Rajeev Shorey, Huzur Saran .[FedFm: Towards a Robust Federated Learning Approach For Fault Mitigation at the Edge Nodes](https://arxiv.org/pdf/2111.01074) [J]. arXiv preprint arXiv:2111.01074.
- Ahmed M. Abdelmoniem, Atal Narayan Sahu, Marco Canini, Suhaib A. Fahmy .[Resource-Efficient Federated Learning](https://arxiv.org/pdf/2111.01108) [J]. arXiv preprint arXiv:2111.01108.
- Houssem Sifaou, Geoffrey Ye Li .[Robust Federated Learning via Over-The-Air Computation](https://arxiv.org/pdf/2111.01221) [J]. arXiv preprint arXiv:2111.01221.
- Jossekin Beilharz, Bjarne Pfitzner, Robert Schmid, Paul Geppert, Bert Arnrich, Andreas Polze .[Implicit Model Specialization through DAG-based Decentralized Federated Learning](https://arxiv.org/pdf/2111.01257) [J]. arXiv preprint arXiv:2111.01257.
- Sangjoon Park, Gwanghyun Kim, Jeongsol Kim, Boah Kim, Jong Chul Ye .[Federated Split Vision Transformer for COVID-19 CXR Diagnosis using Task-Agnostic Training](https://arxiv.org/pdf/2111.01338) [J]. arXiv preprint arXiv:2111.01338.
- Fahao Chen, Peng Li, Toshiaki Miyazaki, Celimuge Wu .[FedGraph: Federated Graph Learning with Intelligent Sampling](https://arxiv.org/pdf/2111.01370) [J]. arXiv preprint arXiv:2111.01370.
- Jamie Cui, Cen Chen, Tiandi Ye, Li Wang .[Practical and Light-weight Secure Aggregation for Federated Submodel Learning](https://arxiv.org/pdf/2111.01432) [J]. arXiv preprint arXiv:2111.01432.
- Rehmat Ullah, Di Wu, Paul Harvey, Peter Kilpatrick, Ivor Spence, Blesson Varghese .[FedFly: Towards Migration in Edge-based Distributed Federated Learning](https://arxiv.org/pdf/2111.01516) [J]. arXiv preprint arXiv:2111.01516.
- Tan Li, Linqi Song .[Privacy-Preserving Communication-Efficient Federated Multi-Armed Bandits](https://arxiv.org/pdf/2111.01570) [J]. arXiv preprint arXiv:2111.01570.
- Xun Qian, Rustem Islamov, Mher Safaryan, Peter Richtárik .[Basis Matters: Better Communication-Efficient Second Order Methods for Federated Learning](https://arxiv.org/pdf/2111.01847) [J]. arXiv preprint arXiv:2111.01847.
- Yuxin Shi, Han Yu, Cyril Leung .[A Survey of Fairness-Aware Federated Learning](https://arxiv.org/pdf/2111.01872) [J]. arXiv preprint arXiv:2111.01872.
- Aymeric Dieuleveut (X-DEP-MATHAPP), Gersende Fort (IMT), Eric Moulines (X-DEP-MATHAPP), Geneviève Robin (LaMME) .[Federated Expectation Maximization with heterogeneity mitigation and variance reduction](https://arxiv.org/pdf/2111.02083) [J]. arXiv preprint arXiv:2111.02083.
- Eugene Bagdasaryan, Peter Kairouz, Stefan Mellem, Adrià Gascón, Kallista Bonawitz, Deborah Estrin, Marco Gruteser .[Towards Sparse Federated Analytics: Location Heatmaps under Distributed Differential Privacy with Secure Aggregation](https://arxiv.org/pdf/2111.02356) [J]. arXiv preprint arXiv:2111.02356.
- Ali Anaissi, Basem Suleiman .[A Personalized Federated Learning Algorithm: an Application in Anomaly Detection](https://arxiv.org/pdf/2111.02627) [J]. arXiv preprint arXiv:2111.02627.
- Wensheng Zhang, Trent Muhr .[TEE-based Selective Testing of Local Workers in Federated Learning Systems](https://arxiv.org/pdf/2111.02662) [J]. arXiv preprint arXiv:2111.02662.
- Mohanad Sarhan, Siamak Layeghy, Nour Moustafa, Marius Portmann .[A Cyber Threat Intelligence Sharing Scheme based on Federated Learning for Network Intrusion Detection](https://arxiv.org/pdf/2111.02791) [J]. arXiv preprint arXiv:2111.02791.
- Jie Zhang, Song Guo, Xiaosong Ma, Haozhao Wang, Wencao Xu, Feijie Wu .[Parameterized Knowledge Transfer for Personalized Federated Learning](https://arxiv.org/pdf/2111.02862) [J]. arXiv preprint arXiv:2111.02862.
- Yuzhi Liang, Yixiang Chen .[DVFL: A Vertical Federated Learning Method for Dynamic Data](https://arxiv.org/pdf/2111.03341) [J]. arXiv preprint arXiv:2111.03341.
- Aidmar Wainakh, Ephraim Zimmer, Sandeep Subedi, Jens Keim, Tim Grube, Shankar Karuppayah, Alejandro Sanchez Guinea, Max Mühlhäuser .[Federated Learning Attacks Revisited: A Critical Discussion of Gaps, Assumptions, and Evaluation Setups](https://arxiv.org/pdf/2111.03363) [J]. arXiv preprint arXiv:2111.03363.
- Andreas Grafberger, Mohak Chadha, Anshul Jindal, Jianfeng Gu, Michael Gerndt .[FedLess: Secure and Scalable Federated Learning Using Serverless Computing](https://arxiv.org/pdf/2111.03396) [J]. arXiv preprint arXiv:2111.03396.
- Hongrui Shi, Valentin Radu .[Data Selection for Efficient Model Update in Federated Learning](https://arxiv.org/pdf/2111.03512) [J]. arXiv preprint arXiv:2111.03512.
- Margalit Glasgow, Honglin Yuan, Tengyu Ma .[Sharp Bounds for Federated Averaging (Local SGD) and Continuous Perspective](https://arxiv.org/pdf/2111.03741) [J]. arXiv preprint arXiv:2111.03741.
- Natalia Tomashenko, Salima Mdhaffar, Marc Tommasi, Yannick Estève, Jean-François Bonastre .[Privacy attacks for automatic speech recognition acoustic models in a federated learning framework](https://arxiv.org/pdf/2111.03777) [J]. arXiv preprint arXiv:2111.03777.
- Mohsen Ahmadi, Ali Taghavirashidizadeh, Danial Javaheri, Armin Masoumian, Saeid Jafarzadeh Ghoushchi, Yaghoub Pourasad .[DQRE-SCnet: A novel hybrid approach for selecting users in Federated Learning with Deep-Q-Reinforcement Learning based on Spectral Clustering](https://arxiv.org/pdf/2111.04105) [J]. arXiv preprint arXiv:2111.04105.
- Durmus Alp Emre Acar, Yue Zhao, Ramon Matas Navarro, Matthew Mattina, Paul N. Whatmough, Venkatesh Saligrama .[Federated Learning Based on Dynamic Regularization](https://arxiv.org/pdf/2111.04263) [J]. arXiv preprint arXiv:2111.04263.
- Anna Jobin, Licinia Guettel, Laura Liebig, Christian Katzenbach .[AI Federalism: Shaping AI Policy within States in Germany](https://arxiv.org/pdf/2111.04454) [J]. arXiv preprint arXiv:2111.04454.
- Yukio Ohsawa, Sae Kondo, Teruaki Hayashi .[Feature Concepts for Data Federative Innovations](https://arxiv.org/pdf/2111.04505) [J]. arXiv preprint arXiv:2111.04505.
- Ece Isik-Polat, Gorkem Polat, Altan Kocyigit .[BARFED: Byzantine Attack-Resistant Federated Averaging Based on Outlier Elimination](https://arxiv.org/pdf/2111.04550) [J]. arXiv preprint arXiv:2111.04550.
- Dzmitry Huba, John Nguyen, Kshitiz Malik, Ruiyu Zhu, Mike Rabbat, Ashkan Yousefpour, Carole-Jean Wu, Hongyuan Zhan, Pavel Ustinov, Harish Srinivas, Kaikai Wang, Anthony Shoumikhin, Jesik Min, Mani Malek .[Papaya: Practical, Private, and Scalable Federated Learning](https://arxiv.org/pdf/2111.04877) [J]. arXiv preprint arXiv:2111.04877.
- Fengda Zhang, Kun Kuang, Yuxuan Liu, Long Chen, Chao Wu, Fei Wu, Jiaxun Lu, Yunfeng Shao, Jun Xiao .[Unified Group Fairness on Federated Learning](https://arxiv.org/pdf/2111.04986) [J]. arXiv preprint arXiv:2111.04986.
- Raed Kontar, Naichen Shi, Xubo Yue, Seokhyun Chung, Eunshin Byon, Mosharaf Chowdhury, Judy Jin, Wissam Kontar, Neda Masoud, Maher Noueihed, Chinedum E. Okwudire, Garvesh Raskutti, Romesh Saigal, Karandeep Singh, Zhisheng Ye .[The Internet of Federated Things (IoFT): A Vision for the Future and In-depth Survey of Data-driven Approaches for Federated Learning](https://arxiv.org/pdf/2111.05326) [J]. arXiv preprint arXiv:2111.05326.
- Aleksei Triastcyn, Matthias Reisser, Christos Louizos .[DP-REC: Private & Communication-Efficient Federated Learning](https://arxiv.org/pdf/2111.05454) [J]. arXiv preprint arXiv:2111.05454.
- Zhikun Chen, Daofeng Li, Jinkang Zhu, Sihai Zhang .[DACFL: Dynamic Average Consensus Based Federated Learning in Decentralized Topology](https://arxiv.org/pdf/2111.05505) [J]. arXiv preprint arXiv:2111.05505.
- Xiaowen Cao, Guangxu Zhu, Jie Xu, Shuguang Cui .[Transmission Power Control for Over-the-Air Federated Averaging at Network Edge](https://arxiv.org/pdf/2111.05719) [J]. arXiv preprint arXiv:2111.05719.
- Peichun Li, Xumin Huang, Miao Pan, Rong Yu .[FedGreen: Federated Learning with Fine-Grained Gradient Compression for Green Mobile Edge Computing](https://arxiv.org/pdf/2111.06146) [J]. arXiv preprint arXiv:2111.06146.
- Timon Rückel, Johannes Sedlmeir, Peter Hofmann .[Fairness, Integrity, and Privacy in a Scalable Blockchain-based Federated Learning System](https://arxiv.org/pdf/2111.06290) [J]. arXiv preprint arXiv:2111.06290.
- Guannan Lou, Yuze Liu, Tiehua Zhang, Xi Zheng .[STFL: A Temporal-Spatial Federated Learning Framework for Graph Neural Networks](https://arxiv.org/pdf/2111.06750) [J]. arXiv preprint arXiv:2111.06750.
- Arup Mondal, Yash More, Ruthu Hulikal Rooparaghunath, Debayan Gupta .[Flatee: Federated Learning Across Trusted Execution Environments](https://arxiv.org/pdf/2111.06867) [J]. arXiv preprint arXiv:2111.06867.
- Dario Pasquini, Danilo Francati, Giuseppe Ateniese .[Eluding Secure Aggregation in Federated Learning via Model Inconsistency](https://arxiv.org/pdf/2111.07380) [J]. arXiv preprint arXiv:2111.07380.
- Mohammad Al-Quraan, Lina Mohjazi, Lina Bariah, Anthony Centeno, Ahmed Zoha, Sami Muhaidat, Mérouane Debbah, Muhammad Ali Imran .[Edge-Native Intelligence for 6G Communications Driven by Federated Learning: A Survey of Trends and Challenges](https://arxiv.org/pdf/2111.07392) [J]. arXiv preprint arXiv:2111.07392.
- Amir Hossein Estiri, Muthucumaru Maheswaran .[Attentive Federated Learning for Concept Drift in Distributed 5G Edge Networks](https://arxiv.org/pdf/2111.07457) [J]. arXiv preprint arXiv:2111.07457.
- Nastaran Gholizadeh, Petr Musilek .[Federated Learning with Hyperparameter-based Clustering for Electrical Load Forecasting](https://arxiv.org/pdf/2111.07462) [J]. arXiv preprint arXiv:2111.07462.
- Boning Li, Ananthram Swami, Santiago Segarra .[Power Allocation for Wireless Federated Learning using Graph Neural Networks](https://arxiv.org/pdf/2111.07480) [J]. arXiv preprint arXiv:2111.07480.
- Tuo Zhang, Lei Gao, Chaoyang He, Mi Zhang, Bhaskar Krishnamachari, Salman Avestimehr .[Federated Learning for Internet of Things: Applications, Challenges, and Opportunities](https://arxiv.org/pdf/2111.07494) [J]. arXiv preprint arXiv:2111.07494.
- Minsu Kim, Walid Saad, Mohammad Mozaffari, Merouane Debbah .[On the Tradeoff between Energy, Precision, and Accuracy in Federated Quantized Neural Networks](https://arxiv.org/pdf/2111.07911) [J]. arXiv preprint arXiv:2111.07911.
- Yuezhou Wu, Yan Kang, Jiahuan Luo, Yuanqin He, Qiang Yang .[FedCG: Leverage Conditional GAN for Protecting Privacy and Maintaining Competitive Performance in Federated Learning](https://arxiv.org/pdf/2111.08211) [J]. arXiv preprint arXiv:2111.08211.
- Jing Cao, Zirui Lian, Weihong Liu, Zongwei Zhu, Cheng Ji .[HADFL: Heterogeneity-aware Decentralized Federated Learning Framework](https://arxiv.org/pdf/2111.08274) [J]. arXiv preprint arXiv:2111.08274.
- Kai Liang, Huiru Zhong, Haoning Chen, Youlong Wu .[Wyner-Ziv Gradient Compression for Federated Learning](https://arxiv.org/pdf/2111.08277) [J]. arXiv preprint arXiv:2111.08277.
- Ohad Amosy, Gal Eyal, Gal Chechik .[Inference-Time Unlabeled Personalized Federated Learning](https://arxiv.org/pdf/2111.08356) [J]. arXiv preprint arXiv:2111.08356.
- Shiliang Zhang .[An Energy Consumption Model for Electrical Vehicle Networks via Extended Federated-learning](https://arxiv.org/pdf/2111.08472) [J]. arXiv preprint arXiv:2111.08472.
- Leon Mächler, Ivan Ezhov, Florian Kofler, Suprosanna Shit, Johannes C. Paetzold, Timo Loehr, Benedikt Wiestler, Bjoern Menze .[FedCostWAvg: A new averaging for better Federated Learning](https://arxiv.org/pdf/2111.08649) [J]. arXiv preprint arXiv:2111.08649.
- Dinh C. Nguyen, Quoc-Viet Pham, Pubudu N. Pathirana, Ming Ding, Aruna Seneviratne, Zihuai Lin, Octavia A. Dobre, Won-Joo Hwang .[Federated Learning for Smart Healthcare: A Survey](https://arxiv.org/pdf/2111.08834) [J]. arXiv preprint arXiv:2111.08834.
- Yusuf Efe .[A Vertical Federated Learning Method For Multi-Institutional Credit Scoring: MICS](https://arxiv.org/pdf/2111.09038) [J]. arXiv preprint arXiv:2111.09038.
- Joaquin Delgado Fernandez, Sergio Potenciano Menci, Charles Lee, Gilbert Fridgen .[Secure Federated Learning for Residential Short Term Load Forecasting](https://arxiv.org/pdf/2111.09248) [J]. arXiv preprint arXiv:2111.09248.
- Maxence Noble, Aurélien Bellet, Aymeric Dieuleveut .[Differentially Private Federated Learning on Heterogeneous Data](https://arxiv.org/pdf/2111.09278) [J]. arXiv preprint arXiv:2111.09278.
- Othmane Marfoq, Giovanni Neglia, Laetitia Kameni, Richard Vidal .[Personalized Federated Learning through Local Memorization](https://arxiv.org/pdf/2111.09360) [J]. arXiv preprint arXiv:2111.09360.
- Pinyarash Pinyoanuntapong, Prabhu Janakaraj, Ravikumar Balakrishnan, Minwoo Lee, Chen Chen, Pu Wang .[EdgeML: Towards Network-Accelerated Federated Learning over Wireless Edge](https://arxiv.org/pdf/2111.09410) [J]. arXiv preprint arXiv:2111.09410.
- Han Hu, Xiaopeng Jiang, Vijaya Datta Mayyuri, An Chen, Devu M. Shila, Adriaan Larmuseau, Ruoming Jin, Cristian Borcea, NhatHai Phan .[FLSys: Toward an Open Ecosystem for Federated Learning Mobile Apps](https://arxiv.org/pdf/2111.09445) [J]. arXiv preprint arXiv:2111.09445.
- Zhicheng Zhou, Hailong Chen, Kunhua Li, Fei Hu, Bingjie Yan, Jieren Cheng, Xuyan Wei, Bernie Liu, Xiulai Li, Fuwen Chen, Yongji Sui .[A Novel Optimized Asynchronous Federated Learning Framework](https://arxiv.org/pdf/2111.09487) [J]. arXiv preprint arXiv:2111.09487.
- Christos Louizos, Matthias Reisser, Joseph Soriaga, Max Welling .[An Expectation-Maximization Perspective on Federated Learning](https://arxiv.org/pdf/2111.10192) [J]. arXiv preprint arXiv:2111.10192.
- Henrik Hellström, Viktoria Fodor, Carlo Fischione .[Over-the-Air Federated Learning with Retransmissions (Extended Version)](https://arxiv.org/pdf/2111.10267) [J]. arXiv preprint arXiv:2111.10267.
- Alexander Korochkin (1,2,3), Andrii Neronov (1,4), Guilhem Lavaux (5), Marius Ramsoy (1,5), Dmitri Semikoz (1,2,6) ((1) Universite de Paris, CNRS, Astroparticule et Cosmologie, F-75006 Paris, France (2) Institute for Nuclear Research of the Russian Academy of Sciences, 60th October Anniversary Prospect 7a, Moscow 117312, Russia (3) Novosibirsk State University, Pirogova 2, Novosibirsk, 630090 Russia (4) Laboratory of Astrophysics, Ecole Polytechnique Federale de Lausanne, 1015, Lausanne, Switzerland (5) Institut d'Astrophysique de Paris (IAP), CNRS Sorbonne Universite, UMR 7095, 98 bis bd Arago, F-75014 Paris, France (6) National Research Nuclear University MEPHI (Moscow Engineering Physics Institute), Kashirskoe highway 31, 115409 Moscow, Russia) .[Detectability of large correlation length inflationary magnetic field with Cherenkov telescopes](https://arxiv.org/pdf/2111.10311) [J]. arXiv preprint arXiv:2111.10311.
- Liling Zhang, Xinyu Lei, Yichun Shi, Hongyu Huang, Chao Chen .[Federated Learning with Domain Generalization](https://arxiv.org/pdf/2111.10487) [J]. arXiv preprint arXiv:2111.10487.
- Xinbo Zhao, Lizhao You, Rui Cao, Yulin Shao, Liqun Fu .[Broadband Digital Over-the-Air Computation for Asynchronous Federated Edge Learning](https://arxiv.org/pdf/2111.10508) [J]. arXiv preprint arXiv:2111.10508.
- Hao Chen, Ming Xiao, Zhibo Pang .[Satellite Based Computing Networks with Federated Learning](https://arxiv.org/pdf/2111.10586) [J]. arXiv preprint arXiv:2111.10586.
- Haibo Tian, Fangguo Zhang, Yunfeng Shao, Bingshuai Li .[Secure Linear Aggregation Using Decentralized Threshold Additive Homomorphic Encryption For Federated Learning](https://arxiv.org/pdf/2111.10753) [J]. arXiv preprint arXiv:2111.10753.
- Zhiwei Liu, Liangwei Yang, Ziwei Fan, Hao Peng, Philip S. Yu .[Federated Social Recommendation with Graph Neural Network](https://arxiv.org/pdf/2111.10778) [J]. arXiv preprint arXiv:2111.10778.
- Yan Kang, Yang Liu, Yuezhou Wu, Guoqiang Ma, Qiang Yang .[Privacy-preserving Federated Adversarial Domain Adaption over Feature Groups for Interpretability](https://arxiv.org/pdf/2111.10934) [J]. arXiv preprint arXiv:2111.10934.
- Chaoyang He, Alay Dilipbhai Shah, Zhenheng Tang, Di Fan1Adarshan Naiynar Sivashunmugam, Keerti Bhogaraju, Mita Shimpi, Li Shen, Xiaowen Chu, Mahdi Soltanolkotabi, Salman Avestimehr .[FedCV: A Federated Learning Framework for Diverse Computer Vision Tasks](https://arxiv.org/pdf/2111.11066) [J]. arXiv preprint arXiv:2111.11066.
- Ouiame Marnissi, Hajar El Hammouti, El Houcine Bergou .[Client Selection in Federated Learning based on Gradients Importance](https://arxiv.org/pdf/2111.11204) [J]. arXiv preprint arXiv:2111.11204.
- Tekin Bicer, Xiaodong Yu, Daniel J. Ching, Ryan Chard, Mathew J. Cherukara, Bogdan Nicolae, Rajkumar Kettimuthu, Ian T. Foster .[High-Performance Ptychographic Reconstruction with Federated Facilities](https://arxiv.org/pdf/2111.11330) [J]. arXiv preprint arXiv:2111.11330.
- Shivam Kalra, Junfeng Wen, Jesse C. Cresswell, Maksims Volkovs, Hamid R. Tizhoosh .[ProxyFL: Decentralized Federated Learning through Proxy Model Sharing](https://arxiv.org/pdf/2111.11343) [J]. arXiv preprint arXiv:2111.11343.
- Elnur Gasanov, Ahmed Khaled, Samuel Horváth, Peter Richtárik .[FLIX: A Simple and Communication-Efficient Alternative to Local Methods in Federated Learning](https://arxiv.org/pdf/2111.11556) [J]. arXiv preprint arXiv:2111.11556.
- Xuezhen Tu, Kun Zhu, Nguyen Cong Luong, Dusit Niyato, Yang Zhang, Juan Li .[Incentive Mechanisms for Federated Learning: From Economic and Game Theoretic Perspective](https://arxiv.org/pdf/2111.11850) [J]. arXiv preprint arXiv:2111.11850.
- Jinu Gong, Osvaldo Simeone, Rahif Kassab, Joonhyuk Kang .[Forget-SVGD: Particle-Based Bayesian Federated Unlearning](https://arxiv.org/pdf/2111.12056) [J]. arXiv preprint arXiv:2111.12056.
- Sean Augenstein, Andrew Hard, Kurt Partridge, Rajiv Mathews .[Jointly Learning from Decentralized (Federated) and Centralized Data to Mitigate Distribution Shift](https://arxiv.org/pdf/2111.12150) [J]. arXiv preprint arXiv:2111.12150.
- Deepti Gupta, Olumide Kayode, Smriti Bhatt, Maanak Gupta, Ali Saman Tosun .[Hierarchical Federated Learning based Anomaly Detection using Digital Twins for Smart Healthcare](https://arxiv.org/pdf/2111.12241) [J]. arXiv preprint arXiv:2111.12241.
- Yuwen Yang, Feifei Gao, Jiang Xue, Ting Zhou, Zongben Xu .[Federated Dynamic Neural Network for Deep MIMO Detection](https://arxiv.org/pdf/2111.12260) [J]. arXiv preprint arXiv:2111.12260.
- Zizhen Liu, Si Chen, Jing Ye, Junfeng Fan, Huawei Li, Xiaowei Li .[Efficient Secure Aggregation Based on SHPRG For Federated Learning](https://arxiv.org/pdf/2111.12321) [J]. arXiv preprint arXiv:2111.12321.
- Nasrin Razmi, Bho Matthiesen, Armin Dekorsy, Petar Popovski .[On-Board Federated Learning for Dense LEO Constellations](https://arxiv.org/pdf/2111.12769) [J]. arXiv preprint arXiv:2111.12769.
- Essam Mansour, Kavitha Srinivas, Katja Hose .[Federated Data Science to Break Down Silos [Vision]](https://arxiv.org/pdf/2111.13186) [J]. arXiv preprint arXiv:2111.13186.
- Gozde N. Gunesli, Mohsin Bilal, Shan E Ahmed Raza, Nasir M. Rajpoot .[FedDropoutAvg: Generalizable federated learning for histopathology image classification](https://arxiv.org/pdf/2111.13230) [J]. arXiv preprint arXiv:2111.13230.
- Marcos F. Criado, Fernando E. Casado, Roberto Iglesias, Carlos V. Regueiro, Senén Barro .[Non-IID data and Continual Learning processes in Federated Learning: A long road ahead](https://arxiv.org/pdf/2111.13394) [J]. arXiv preprint arXiv:2111.13394.
- Yangchen Li, Ying Cui, Vincent Lau .[An Optimization Framework for Federated Edge Learning](https://arxiv.org/pdf/2111.13526) [J]. arXiv preprint arXiv:2111.13526.
- Marco Repetto, Davide La Torre, Muhammad Tariq .[Federated Deep Learning in Electricity Forecasting: An MCDM Approach](https://arxiv.org/pdf/2111.13834) [J]. arXiv preprint arXiv:2111.13834.
- Francois Gauthier, Vinay Chakravarthi Gogineni, Stefan Werner, Yih-Fang Huang, Anthony Kuh .[Resource-Aware Asynchronous Online Federated Learning for Nonlinear Regression](https://arxiv.org/pdf/2111.13931) [J]. arXiv preprint arXiv:2111.13931.
- Xubo Yue, Raed Al Kontar .[Federated Gaussian Process: Convergence, Automatic Personalization and Multi-fidelity Modeling](https://arxiv.org/pdf/2111.14008) [J]. arXiv preprint arXiv:2111.14008.
- Matias Mendieta, Taojiannan Yang, Pu Wang, Minwoo Lee, Zhengming Ding, Chen Chen .[Local Learning Matters: Rethinking Data Heterogeneity in Federated Learning](https://arxiv.org/pdf/2111.14213) [J]. arXiv preprint arXiv:2111.14213.
- Fuxun Yu, Weishan Zhang, Zhuwei Qin, Zirui Xu, Di Wang, Chenchen Liu, Zhi Tian, Xiang Chen .[Fed2: Feature-Aligned Federated Learning](https://arxiv.org/pdf/2111.14248) [J]. arXiv preprint arXiv:2111.14248.
- Sixing Yu, Phuong Nguyen, Waqwoya Abebe, Ali Anwar, Ali Jannesari .[SPATL: Salient Parameter Aggregation and Transfer Learning for Heterogeneous Clients in Federated Learning](https://arxiv.org/pdf/2111.14345) [J]. arXiv preprint arXiv:2111.14345.
- Tian Liu, Jun Xia, Xian Wei, Ting Wang, Xin Fu, Mingsong Chen .[Efficient Federated Learning for AIoT Applications Using Knowledge Distillation](https://arxiv.org/pdf/2111.14347) [J]. arXiv preprint arXiv:2111.14347.
- Pedro Miguel Sánchez Sánchez, Alberto Huertas Celdrán, José Rafael Buendía Rubio, Gérôme Bovet, Gregorio Martínez Pérez .[Robust Federated Learning for execution time-based device model identification under label-flipping attack](https://arxiv.org/pdf/2111.14434) [J]. arXiv preprint arXiv:2111.14434.
- Dezhong Yao, Wanning Pan, Yao Wan, Hai Jin, Lichao Sun .[FedHM: Efficient Federated Learning for Heterogeneous Models via Low-rank Factorization](https://arxiv.org/pdf/2111.14655) [J]. arXiv preprint arXiv:2111.14655.
- Zeki Bilgin .[Anomaly Localization in Model Gradients Under Backdoor Attacks Against Federated Learning](https://arxiv.org/pdf/2111.14683) [J]. arXiv preprint arXiv:2111.14683.
- Yongjeong Oh, Namyoon Lee, Yo-Seb Jeon, H. Vincent Poor .[Communication-Efficient Federated Learning via Quantized Compressed Sensing](https://arxiv.org/pdf/2111.15071) [J]. arXiv preprint arXiv:2111.15071.
- Kangsoo Jung, Sayan Biswas, Catuscia Palamidessi .[Establishing the Price of Privacy in Federated Data Trading](https://arxiv.org/pdf/2111.15415) [J]. arXiv preprint arXiv:2111.15415.
- Yangsibo Huang, Samyak Gupta, Zhao Song, Kai Li, Sanjeev Arora .[Evaluating Gradient Inversion Attacks and Defenses in Federated Learning](https://arxiv.org/pdf/2112.00059) [J]. arXiv preprint arXiv:2112.00059.
- Ha Min Son, Moon Hyun Kim, Tai-Myoung Chung .[Compare Where It Matters: Using Layer-Wise Regularization To Improve Federated Learning on Heterogeneous Data](https://arxiv.org/pdf/2112.00407) [J]. arXiv preprint arXiv:2112.00407.
- Yiqiang Chen, Wang Lu, Jindong Wang, Xin Qin, Tao Qin .[Federated Learning with Adaptive Batchnorm for Personalized Healthcare](https://arxiv.org/pdf/2112.00734) [J]. arXiv preprint arXiv:2112.00734.
- Kate Donahue, Jon Kleinberg .[Models of fairness in federated learning](https://arxiv.org/pdf/2112.00818) [J]. arXiv preprint arXiv:2112.00818.
- Zhe Qu, Rui Duan, Lixing Chen, Jie Xu, Zhuo Lu, Yao Liu .[Context-Aware Online Client Selection for Hierarchical Federated Learning](https://arxiv.org/pdf/2112.00925) [J]. arXiv preprint arXiv:2112.00925.
- Manabu Nakanoya, Junha Im, Hang Qiu, Sachin Katti, Marco Pavone, Sandeep Chinchali .[Personalized Federated Learning of Driver Prediction Models for Autonomous Driving](https://arxiv.org/pdf/2112.00956) [J]. arXiv preprint arXiv:2112.00956.
- Shuo Wan, Jiaxun Lu, Pingyi Fan, Yunfeng Shao, Chenghui Peng, Khaled B. Letaief .[How global observation works in Federated Learning: Integrating vertical training into Horizontal Federated Learning](https://arxiv.org/pdf/2112.01039) [J]. arXiv preprint arXiv:2112.01039.
- Mustafa Safa Ozdayi, Murat Kantarcioglu .[The Impact of Data Distribution on Fairness and Robustness in Federated Learning](https://arxiv.org/pdf/2112.01274) [J]. arXiv preprint arXiv:2112.01274.
- Stefán Páll Sturluson, Samuel Trew, Luis Muñoz-González, Matei Grama, Jonathan Passerat-Palmbach, Daniel Rueckert, Amir Alansary .[FedRAD: Federated Robust Adaptive Distillation](https://arxiv.org/pdf/2112.01405) [J]. arXiv preprint arXiv:2112.01405.
- Hankyul Baek, Won Joon Yun, Yunseok Kwak, Soyi Jung, Mingyue Ji, Mehdi Bennis, Jihong Park, Joongheon Kim .[Joint Superposition Coding and Training for Federated Learning over Multi-Width Neural Networks](https://arxiv.org/pdf/2112.02543) [J]. arXiv preprint arXiv:2112.02543.
- Luke Melas-Kyriazi, Franklyn Wang .[Intrinisic Gradient Compression for Federated Learning](https://arxiv.org/pdf/2112.02656) [J]. arXiv preprint arXiv:2112.02656.
- Franziska Boenisch, Adam Dziedzic, Roei Schuster, Ali Shahin Shamsabadi, Ilia Shumailov, Nicolas Papernot .[When the Curious Abandon Honesty: Federated Learning Is Not Private](https://arxiv.org/pdf/2112.02918) [J]. arXiv preprint arXiv:2112.02918.
- Hankyul Baek, Won Joon Yun, Soyi Jung, Jihong Park, Mingyue Ji, Joongheon Kim, Mehdi Bennis .[Communication and Energy Efficient Slimmable Federated Learning via Superposition Coding and Successive Decoding](https://arxiv.org/pdf/2112.03267) [J]. arXiv preprint arXiv:2112.03267.
- Evita Bakopoulou, Jiang Zhang, Justin Ley, Konstantinos Psounis, Athina Markopoulou .[Location Leakage in Federated Signal Maps](https://arxiv.org/pdf/2112.03452) [J]. arXiv preprint arXiv:2112.03452.
- Peyman Tehrani, Francesco Restuccia, Marco Levorato .[Federated Deep Reinforcement Learning for the Distributed Control of NextG Wireless Networks](https://arxiv.org/pdf/2112.03465) [J]. arXiv preprint arXiv:2112.03465.
- Erdun Gao, Junjia Chen, Li Shen, Tongliang Liu, Mingming Gong, Howard Bondell .[Federated Causal Discovery](https://arxiv.org/pdf/2112.03555) [J]. arXiv preprint arXiv:2112.03555.
- Wuxing Xu, Hao Fan, Kaixin Li, Kai Yang .[Efficient Batch Homomorphic Encryption for Vertically Federated XGBoost](https://arxiv.org/pdf/2112.04261) [J]. arXiv preprint arXiv:2112.04261.
- Yuchang Sun, Jiawei Shao, Yuyi Mao, Jun Zhang .[Asynchronous Semi-Decentralized Federated Edge Learning for Heterogeneous Clients](https://arxiv.org/pdf/2112.04737) [J]. arXiv preprint arXiv:2112.04737.
- Wei Deng, Yi-An Ma, Zhao Song, Qian Zhang, Guang Lin .[On Convergence of Federated Averaging Langevin Dynamics](https://arxiv.org/pdf/2112.05120) [J]. arXiv preprint arXiv:2112.05120.
- Tianyi Zhang, Shirui Zhang, Ziwei Chen, Dianbo Liu .[PMFL: Partial Meta-Federated Learning for heterogeneous tasks and its applications on real-world medical records](https://arxiv.org/pdf/2112.05321) [J]. arXiv preprint arXiv:2112.05321.
- Yang Liu, Tianyuan Zou, Yan Kang, Wenhan Liu, Yuanqin He, Zhihao Yi, Qiang Yang .[Batch Label Inference and Replacement Attacks in Black-Boxed Vertical Federated Learning](https://arxiv.org/pdf/2112.05409) [J]. arXiv preprint arXiv:2112.05409.
- Gorka Abad, Stjepan Picek, Aitor Urbieta .[SoK: On the Security & Privacy in Federated Learning](https://arxiv.org/pdf/2112.05423) [J]. arXiv preprint arXiv:2112.05423.
- Zichen Ma, Zihan Lu, Yu Lu, Wenye Li, Jinfeng Yi, Shuguang Cui .[Federated Two-stage Learning with Sign-based Voting](https://arxiv.org/pdf/2112.05687) [J]. arXiv preprint arXiv:2112.05687.
- Chun-Mei Feng, Yunlu Yan, Huazhu Fu, Yong Xu, Ling Shao .[Specificity-Preserving Federated Learning for MR Image Reconstruction](https://arxiv.org/pdf/2112.05752) [J]. arXiv preprint arXiv:2112.05752.
- Konstantinos Gatsis .[Federated Reinforcement Learning at the Edge](https://arxiv.org/pdf/2112.05908) [J]. arXiv preprint arXiv:2112.05908.
- Chendi Zhou, Ji Liu, Juncheng Jia, Jingbo Zhou, Yang Zhou, Huaiyu Dai, Dejing Dou .[Efficient Device Scheduling with Multi-Job Federated Learning](https://arxiv.org/pdf/2112.05928) [J]. arXiv preprint arXiv:2112.05928.
- Yichen Ruan, Carlee Joe-Wong .[FedSoft: Soft Clustered Federated Learning with Proximal Local Updating](https://arxiv.org/pdf/2112.06053) [J]. arXiv preprint arXiv:2112.06053.
- Tanya Roosta, Peyman Passban, Ankit Chadha .[Communication-Efficient Federated Learning for Neural Machine Translation](https://arxiv.org/pdf/2112.06135) [J]. arXiv preprint arXiv:2112.06135.
- Alper Emin Cetinkaya, Murat Akin, Seref Sagiroglu .[Improving Performance of Federated Learning based Medical Image Analysis in Non-IID Settings using Image Augmentation](https://arxiv.org/pdf/2112.06194) [J]. arXiv preprint arXiv:2112.06194.
- Ashwinee Panda, Saeed Mahloujifar, Arjun N. Bhagoji, Supriyo Chakraborty, Prateek Mittal .[SparseFed: Mitigating Model Poisoning Attacks in Federated Learning with Sparsification](https://arxiv.org/pdf/2112.06274) [J]. arXiv preprint arXiv:2112.06274.
- Laizhong Cui, Xiaoxin Su, Yipeng Zhou, Jiangchuan Liu .[Optimal Rate Adaption in Federated Learning with Compressed Communications](https://arxiv.org/pdf/2112.06694) [J]. arXiv preprint arXiv:2112.06694.
- Timothy Stevens, Christian Skalka, Christelle Vincent, John Ring, Samuel Clark, Joseph Near .[Efficient Differentially Private Secure Aggregation for Federated Learning via Hardness of Learning with Errors](https://arxiv.org/pdf/2112.06872) [J]. arXiv preprint arXiv:2112.06872.
- Parikshit Ram, Kaushik Sinha .[Federated Nearest Neighbor Classification with a Colony of Fruit-Flies: With Supplement](https://arxiv.org/pdf/2112.07157) [J]. arXiv preprint arXiv:2112.07157.
- Yifan Niu, Weihong Deng .[Federated Learning for Face Recognition with Gradient Correction](https://arxiv.org/pdf/2112.07246) [J]. arXiv preprint arXiv:2112.07246.
- Huiming Chen, Huandong Wang, Quanming Yao, Yong Li, Depeng Jin, Qiang Yang .[LoSAC: An Efficient Local Stochastic Average Control Method for Federated Optimization](https://arxiv.org/pdf/2112.07839) [J]. arXiv preprint arXiv:2112.07839.
- Francesc Wilhelmi, Lorenza Giupponi, Paolo Dini .[Blockchain-enabled Server-less Federated Learning](https://arxiv.org/pdf/2112.07938) [J]. arXiv preprint arXiv:2112.07938.
- Ji Liu, Lei Mo, Sijia Yang, Jingbo Zhou, Shilei Ji, Haoyi Xiong, Dejing Dou .[Data Placement for Multi-Tenant Data Federation on the Cloud](https://arxiv.org/pdf/2112.07980) [J]. arXiv preprint arXiv:2112.07980.
- Andrii Neronov (1,2), Dmitri Semikoz (1,3,4), Oleg Kalashev (3) ((1) Universite de Paris, CNRS, Astroparticule et Cosmologie, F-75006 Paris, France (2) Laboratory of Astrophysics, Ecole Polytechnique Federale de Lausanne, 1015, Lausanne, Switzerland (3) Institute for Nuclear Research of the Russian Academy of Sciences, 60th October Anniversary Prospect 7a, Moscow 117312, Russia (4) National Research Nuclear University MEPHI (Moscow Engineering Physics Institute), Kashirskoe highway 31, 115409 Moscow, Russia) .[Limit on intergalactic magnetic field from ultra-high-energy cosmic ray hotspot in Perseus-Pisces region](https://arxiv.org/pdf/2112.08202) [J]. arXiv preprint arXiv:2112.08202.
- Xiao Han, Leye Wang, Junjie Wu .[Data Valuation for Vertical Federated Learning: An Information-Theoretic Approach](https://arxiv.org/pdf/2112.08364) [J]. arXiv preprint arXiv:2112.08364.
- Yi Zhou, Parikshit Ram, Theodoros Salonidis, Nathalie Baracaldo, Horst Samulowitz, Heiko Ludwig .[FLoRA: Single-shot Hyper-parameter Optimization for Federated Learning](https://arxiv.org/pdf/2112.08524) [J]. arXiv preprint arXiv:2112.08524.
- Asad Ali, Samin Rahman Khan, Sadman Sakib, Md. Shohrab Hossain, Ying-Dar Lin .[Federated 3GPP Mobile Edge Computing Systems: A Transparent Proxy for Third Party Authentication with Application Mobility Support](https://arxiv.org/pdf/2112.08590) [J]. arXiv preprint arXiv:2112.08590.
- Reent Schlegel, Siddhartha Kumar, Eirik Rosnes, Alexandre Graell i Amat .[CodedPaddedFL and CodedSecAgg: Straggler Mitigation and Secure Aggregation in Federated Learning](https://arxiv.org/pdf/2112.08909) [J]. arXiv preprint arXiv:2112.08909.
- Camila Gonzalez, Christian Harder, Amin Ranem, Ricarda Fischbach, Isabel Kaltenborn, Armin Dadras, Andreas Bucher, Anirban Mukhopadhyay .[Quality monitoring of federated Covid-19 lesion segmentation](https://arxiv.org/pdf/2112.08974) [J]. arXiv preprint arXiv:2112.08974.
- Larry Han, Jue Hou, Kelly Cho, Rui Duan, Tianxi Cai .[Federated Adaptive Causal Estimation (FACE) of Target Treatment Effects](https://arxiv.org/pdf/2112.09313) [J]. arXiv preprint arXiv:2112.09313.
- Feijie Wu, Song Guo, Haozhao Wang, Zhihao Qu, Haobo Zhang, Jie Zhang, Ziming Liu .[From Deterioration to Acceleration: A Calibration Approach to Rehabilitating Step Asynchronism in Federated Optimization](https://arxiv.org/pdf/2112.09355) [J]. arXiv preprint arXiv:2112.09355.
- Krishna Pillutla, Yassine Laguel, Jérôme Malick, Zaid Harchaoui .[Federated Learning with Heterogeneous Data: A Superquantile Optimization Approach](https://arxiv.org/pdf/2112.09429) [J]. arXiv preprint arXiv:2112.09429.
- Sameer Bibikar, Haris Vikalo, Zhangyang Wang, Xiaohan Chen .[Federated Dynamic Sparse Training: Computing Less, Communicating Less, Yet Learning Better](https://arxiv.org/pdf/2112.09824) [J]. arXiv preprint arXiv:2112.09824.
- Vishwa S Parekh, Shuhao Lai, Vladimir Braverman, Jeff Leal, Steven Rowe, Jay J Pillai, Michael A Jacobs .[Cross-Domain Federated Learning in Medical Imaging](https://arxiv.org/pdf/2112.10001) [J]. arXiv preprint arXiv:2112.10001.
- Liang Peng, Nan Wang, Nicha Dvornek, Xiaofeng Zhu, Xiaoxiao Li .[FedNI: Federated Graph Learning with Network Inpainting for Population-Based Disease Prediction](https://arxiv.org/pdf/2112.10166) [J]. arXiv preprint arXiv:2112.10166.
- Yuchang Sun, Jiawei Shao, Yuyi Mao, Jessie Hui Wang, Jun Zhang .[Semi-Decentralized Federated Edge Learning with Data and Device Heterogeneity](https://arxiv.org/pdf/2112.10313) [J]. arXiv preprint arXiv:2112.10313.
- Giulio Zizzo, Ambrish Rawat, Mathieu Sinn, Sergio Maffeis, Chris Hankin .[Certified Federated Adversarial Training](https://arxiv.org/pdf/2112.10525) [J]. arXiv preprint arXiv:2112.10525.
- Meirui Jiang, Zirui Wang, Qi Dou .[HarmoFL: Harmonizing Local and Global Drifts in Federated Learning on Heterogeneous Medical Images](https://arxiv.org/pdf/2112.10775) [J]. arXiv preprint arXiv:2112.10775.
- Vasileios Perifanis, George Drosatos, Giorgos Stamatelatos, Pavlos S. Efraimidis .[FedPOIRec: Privacy Preserving Federated POI Recommendation with Social Influence](https://arxiv.org/pdf/2112.11134) [J]. arXiv preprint arXiv:2112.11134.
- Ozan Aygün, Mohammad Kazemi, Deniz Gündüz, Tolga M. Duman .[Hierarchical Over-the-Air Federated Edge Learning](https://arxiv.org/pdf/2112.11167) [J]. arXiv preprint arXiv:2112.11167.
- Bing Luo, Wenli Xiao, Shiqiang Wang, Jianwei Huang, Leandros Tassiulas .[Tackling System and Statistical Heterogeneity for Federated Learning with Adaptive Client Sampling](https://arxiv.org/pdf/2112.11256) [J]. arXiv preprint arXiv:2112.11256.
- Hung T. Nguyen, Roberto Morabito, Kwang Taik Kim, Mung Chiang .[On-the-fly Resource-Aware Model Aggregation for Federated Learning in Heterogeneous Edge](https://arxiv.org/pdf/2112.11485) [J]. arXiv preprint arXiv:2112.11485.
- Tung T. Vu, Hien Q. Ngo, Minh N. Dao, Duy T. Ngo, Erik G. Larsson, Tho Le-Ngoc .[Energy-Efficient Massive MIMO for Federated Learning: Transmission Designs and Resource Allocations](https://arxiv.org/pdf/2112.11723) [J]. arXiv preprint arXiv:2112.11723.
- Mohamed Ghanem, Fadi Dawoud, Habiba Gamal, Eslam Soliman, Hossam Sharara, Tamer El-Batt .[FLoBC: A Decentralized Blockchain-Based Federated Learning Framework](https://arxiv.org/pdf/2112.11873) [J]. arXiv preprint arXiv:2112.11873.
- Xingyu Li, Zhe Qu, Bo Tang, Zhuo Lu .[FedLGA: Towards System-Heterogeneity of Federated Learning via Local Gradient Approximation](https://arxiv.org/pdf/2112.11989) [J]. arXiv preprint arXiv:2112.11989.
- Jie Zhang, Chen Chen, Bo Li, Lingjuan Lyu, Shuang Wu, Jianghe Xu, Shouhong Ding, Chao Wu .[A Practical Data-Free Approach to One-shot Federated Learning with Heterogeneity](https://arxiv.org/pdf/2112.12371) [J]. arXiv preprint arXiv:2112.12371.
- Chih-Ting Liu, Chien-Yi Wang, Shao-Yi Chien, Shang-Hong Lai .[FedFR: Joint Optimization Federated Framework for Generic and Personalized Face Recognition](https://arxiv.org/pdf/2112.12496) [J]. arXiv preprint arXiv:2112.12496.
- Amrita Roy Chowdhury, Chuan Guo, Somesh Jha, Laurens van der Maaten .[EIFFeL: Ensuring Integrity for Federated Learning](https://arxiv.org/pdf/2112.12727) [J]. arXiv preprint arXiv:2112.12727.
- Irem Ergun, Hasin Us Sami, Basak Guler .[Sparsified Secure Aggregation for Privacy-Preserving Federated Learning](https://arxiv.org/pdf/2112.12872) [J]. arXiv preprint arXiv:2112.12872.
- Haoyu Zhao, Konstantin Burlachenko, Zhize Li, Peter Richtárik .[Faster Rates for Compressed Federated Learning with Client-Variance Reduction](https://arxiv.org/pdf/2112.13097) [J]. arXiv preprint arXiv:2112.13097.
- Yongxin Guo, Tao Lin, Xiaoying Tang .[Towards Federated Learning on Time-Evolving Heterogeneous Data](https://arxiv.org/pdf/2112.13246) [J]. arXiv preprint arXiv:2112.13246.
- Shana Moothedath, Namrata Vaswani .[Fully Decentralized and Federated Low Rank Compressive Sensing](https://arxiv.org/pdf/2112.13412) [J]. arXiv preprint arXiv:2112.13412.
- Tiantian Feng, Hanieh Hashemi, Rajat Hebbar, Murali Annavaram, Shrikanth S. Narayanan .[Attribute Inference Attack of Speech Emotion Recognition in Federated Learning Settings](https://arxiv.org/pdf/2112.13416) [J]. arXiv preprint arXiv:2112.13416.
- Alphan Sahin, Bryson Everette, Safi Shams Muhtasimul Hoque .[Over-the-Air Computation with DFT-spread OFDM for Federated Edge Learning](https://arxiv.org/pdf/2112.13439) [J]. arXiv preprint arXiv:2112.13439.
- Chenxi Zhong, Huiyuan Yang, Xiaojun Yuan .[Over-the-Air Multi-Task Federated Learning Over MIMO Interference Channel](https://arxiv.org/pdf/2112.13603) [J]. arXiv preprint arXiv:2112.13603.
- David Nickel, Frank Po-Chen Lin, Seyyedali Hosseinalipour, Nicolo Michelusi, Christopher G. Brinton .[Resource-Efficient and Delay-Aware Federated Learning Design under Edge Heterogeneity](https://arxiv.org/pdf/2112.13926) [J]. arXiv preprint arXiv:2112.13926.
- Erum Mushtaq, Chaoyang He, Jie Ding, Salman Avestimehr .[SPIDER: Searching Personalized Neural Architecture for Federated Learning](https://arxiv.org/pdf/2112.13939) [J]. arXiv preprint arXiv:2112.13939.
- Hunmin Lee, Yueyang Liu, Donghyun Kim, Yingshu Li .[Robust Convergence in Federated Learning through Label-wise Clustering](https://arxiv.org/pdf/2112.14244) [J]. arXiv preprint arXiv:2112.14244.
- Boxin Zhao, Ziqi Liu, Chaochao Chen, Mladen Kolar, Zhiqiang Zhang, Jun Zhou .[Adaptive Client Sampling in Federated Learning via Online Learning with Bandit Feedback](https://arxiv.org/pdf/2112.14332) [J]. arXiv preprint arXiv:2112.14332.
- Bingyang Chena, Xingjie Zenga, Weishan Zhang .[Federated Learning for Cross-block Oil-water Layer Identification](https://arxiv.org/pdf/2112.14359) [J]. arXiv preprint arXiv:2112.14359.
- Bingyang Chen, Tao Chen, Xingjie Zeng, Weishan Zhang, Qinghua Lu, Zhaoxiang Hou, Jiehan Zhou, Sumi Helal (IEEE Fellow) .[Feature-context driven Federated Meta-Learning for Rare Disease Prediction](https://arxiv.org/pdf/2112.14364) [J]. arXiv preprint arXiv:2112.14364.
- Peixi Liu, Jiamo Jiang, Guangxu Zhu, Lei Cheng, Wei Jiang, Wu Luo, Ying Du, Zhiqin Wang .[Training Time Minimization for Federated Edge Learning with Optimized Gradient Quantization and Bandwidth Allocation](https://arxiv.org/pdf/2112.14387) [J]. arXiv preprint arXiv:2112.14387.
- Shengshan Hu, Jianrong Lu, Wei Wan, Leo Yu Zhang .[Challenges and approaches for mitigating byzantine attacks in federated learning](https://arxiv.org/pdf/2112.14468) [J]. arXiv preprint arXiv:2112.14468.
- Yifan Hua, Kevin Miller, Andrea L. Bertozzi, Chen Qian, Bao Wang .[Efficient and Reliable Overlay Networks for Decentralized Federated Learning](https://arxiv.org/pdf/2112.15486) [J]. arXiv preprint arXiv:2112.15486.


### 2022
- Huanlai Xing, Zhiwen Xiao, Rong Qu, Zonghai Zhu, Bowen Zhao .[An Efficient Federated Distillation Learning System for Multi-task Time Series Classification](https://arxiv.org/pdf/2201.00011) [J]. arXiv preprint arXiv:2201.00011.
- Tengchan Zeng, Omid Semiari, Walid Saad, Mehdi Bennis .[Wireless-Enabled Asynchronous Federated Fourier Neural Network for Turbulence Prediction in Urban Air Mobility (UAM)](https://arxiv.org/pdf/2201.00626) [J]. arXiv preprint arXiv:2201.00626.
- Phillip Rieger, Thien Duc Nguyen, Markus Miettinen, Ahmad-Reza Sadeghi .[DeepSight: Mitigating Backdoor Attacks in Federated Learning Through Deep Model Inspection](https://arxiv.org/pdf/2201.00763) [J]. arXiv preprint arXiv:2201.00763.
- Zhe Zhang, Shiyao Ma, Zhaohui Yang, Zehui Xiong, Jiawen Kang, Yi Wu, Kejia Zhang, Dusit Niyato .[Robust Semi-supervised Federated Learning for Images Automatic Recognition in Internet of Drones](https://arxiv.org/pdf/2201.01230) [J]. arXiv preprint arXiv:2201.01230.
- Amin Eslami Abyane, Derui Zhu, Roberto Medeiros de Souza, Lei Ma, Hadi Hemmati .[Towards Understanding Quality Challenges of the Federated Learning: A First Look from the Lens of Robustness](https://arxiv.org/pdf/2201.01409) [J]. arXiv preprint arXiv:2201.01409.
- Jaemin Shin, Yuanchun Li, Yunxin Liu, Sung-Ju Lee .[Sample Selection with Deadline Control for Efficient Federated Learning on Heterogeneous Clients](https://arxiv.org/pdf/2201.01601) [J]. arXiv preprint arXiv:2201.01601.
- Ali Jadbabaie, Anuran Makur, Devavrat Shah .[Federated Optimization of Smooth Loss Functions](https://arxiv.org/pdf/2201.01954) [J]. arXiv preprint arXiv:2201.01954.
- Jingwen Zhang, Yuezhou Wu, Rong Pan .[Auction-Based Ex-Post-Payment Incentive Mechanism Design for Horizontal Federated Learning with Reputation and Contribution Measurement](https://arxiv.org/pdf/2201.02410) [J]. arXiv preprint arXiv:2201.02410.
- Neelkamal Bhuyan, Sharayu Moharir .[Multi-Model Federated Learning](https://arxiv.org/pdf/2201.02582) [J]. arXiv preprint arXiv:2201.02582.
- Zhenan Fan, Huang Fang, Zirui Zhou, Jian Pei, Michael P. Friedlander, Yong Zhang .[Fair and efficient contribution valuation for vertical federated learning](https://arxiv.org/pdf/2201.02658) [J]. arXiv preprint arXiv:2201.02658.
- Nicole Mitchell, Johannes Ballé, Zachary Charles, Jakub Konečný .[Optimizing the Communication-Accuracy Trade-off in Federated Learning with Rate-Distortion Theory](https://arxiv.org/pdf/2201.02664) [J]. arXiv preprint arXiv:2201.02664.
- Haizhou Liu, Xuan Zhang, Xinwei Shen, Hongbin Sun .[A Fair and Efficient Hybrid Federated Learning Framework based on XGBoost for Distributed Power Prediction](https://arxiv.org/pdf/2201.02783) [J]. arXiv preprint arXiv:2201.02783.
- Xingyu Li, Zhe Qu, Shangqing Zhao, Bo Tang, Zhuo Lu, Yao Liu .[LoMar: A Local Defense Against Poisoning Attack on Federated Learning](https://arxiv.org/pdf/2201.02873) [J]. arXiv preprint arXiv:2201.02873.
- Sai Qian Zhang, Jieyu Lin, Qi Zhang .[A Multi-agent Reinforcement Learning Approach for Efficient Client Selection in Federated Learning](https://arxiv.org/pdf/2201.02932) [J]. arXiv preprint arXiv:2201.02932.
- Tian Dong, Song Li, Han Qiu, Jialiang Lu .[An Interpretable Federated Learning-based Network Intrusion Detection Framework](https://arxiv.org/pdf/2201.03134) [J]. arXiv preprint arXiv:2201.03134.
- Zhenyuan Zhang .[FedDTG:Federated Data-Free Knowledge Distillation via Three-Player Generative Adversarial Networks](https://arxiv.org/pdf/2201.03169) [J]. arXiv preprint arXiv:2201.03169.
- Geeho Kim, Jinkyu Kim, Bohyung Han .[Communication-Efficient Federated Learning with Acceleration of Global Momentum](https://arxiv.org/pdf/2201.03172) [J]. arXiv preprint arXiv:2201.03172.
- Yongkang Wang, Dihua Zhai, Yufeng Zhan, Yuanqing Xia .[RFLBAT: A Robust Federated Learning Algorithm against Backdoor Attack](https://arxiv.org/pdf/2201.03772) [J]. arXiv preprint arXiv:2201.03772.
- Sunwoo Lee, Anit Kumar Sahu, Chaoyang He, Salman Avestimehr .[Partial Model Averaging in Federated Learning: Performance Guarantees and Benefits](https://arxiv.org/pdf/2201.03789) [J]. arXiv preprint arXiv:2201.03789.
- Takuya Fujihashi, Toshiaki Koike-Akino, Takashi Watanabe .[Federated AirNet: Hybrid Digital-Analog Neural Network Transmission for Federated Learning](https://arxiv.org/pdf/2201.04557) [J]. arXiv preprint arXiv:2201.04557.
- Yi Shi, Yalin E. Sagduyu .[Jamming Attacks on Federated Learning in Wireless Networks](https://arxiv.org/pdf/2201.05172) [J]. arXiv preprint arXiv:2201.05172.
- Jialiang Han, Yun Ma, Yudong Han .[Demystifying Swarm Learning: A New Paradigm of Blockchain-based Decentralized Federated Learning](https://arxiv.org/pdf/2201.05286) [J]. arXiv preprint arXiv:2201.05286.
- Guangyuan Shen, Dehong Gao, Libin Yang, Fang Zhou, Duanxiao Song, Wei Lou, Shirui Pan .[Variance-Reduced Heterogeneous Federated Learning via Stratified Client Selection](https://arxiv.org/pdf/2201.05762) [J]. arXiv preprint arXiv:2201.05762.
- Mina Ghanbari (1), Ghader Rezazadeh (2 and 3),  ((1) Mechanical Engineering Department Urmia University of Technology Urmia IRAN, (2) Mechanical Engineering Department Urmia University Urmia IRAN, (3) South Ural State University Chelyabinsk Russian Federation) .[A Physical Perspective to Human Migration Phenomenon](https://arxiv.org/pdf/2201.06119) [J]. arXiv preprint arXiv:2201.06119.
- Yimin Huang, Xinyu Feng, Wanwan Wang, Hao He, Yukun Wang, Ming Yao .[EFMVFL: An Efficient and Flexible Multi-party Vertical Federated Learning without a Third Party](https://arxiv.org/pdf/2201.06244) [J]. arXiv preprint arXiv:2201.06244.
- Afra Mashhadi, Alex Kyllo, Reza M. Parizi .[Fairness in Federated Learning for Spatial-Temporal Applications](https://arxiv.org/pdf/2201.06598) [J]. arXiv preprint arXiv:2201.06598.
- Phung Lai, NhatHai Phan, Abdallah Khreishah, Issa Khalil, Xintao Wu .[Model Transferring Attacks to Backdoor HyperNetwork in Personalized Federated Learning](https://arxiv.org/pdf/2201.07063) [J]. arXiv preprint arXiv:2201.07063.
- Morris Stallmann, Anna Wilbik .[Towards Federated Clustering: A Federated Fuzzy $c$-Means Algorithm (FFCM)](https://arxiv.org/pdf/2201.07316) [J]. arXiv preprint arXiv:2201.07316.
- T. Taleb, I. Afolabi, K. Samdanis, F. Z. Yousaf .[On Multi-domain Network Slicing Orchestration Architecture & Federated Resource Control](https://arxiv.org/pdf/2201.07712) [J]. arXiv preprint arXiv:2201.07712.
- Jake Perazzone, Shiqiang Wang, Mingyue Ji, Kevin Chan .[Communication-Efficient Device Scheduling for Federated Learning Using Stochastic Optimization](https://arxiv.org/pdf/2201.07912) [J]. arXiv preprint arXiv:2201.07912.
- Michael Cho, Afra Mashhadi .[Caring Without Sharing: A Federated Learning Crowdsensing Framework for Diversifying Representation of Cities](https://arxiv.org/pdf/2201.07980) [J]. arXiv preprint arXiv:2201.07980.
- Nuria Rodríguez-Barroso, Daniel Jiménez López, M. Victoria Luzón, Francisco Herrera, Eugenio Martínez-Cámara .[Survey on Federated Learning Threats: concepts, taxonomy on attacks and defences, experimental study and challenges](https://arxiv.org/pdf/2201.08135) [J]. arXiv preprint arXiv:2201.08135.
- Sunder Ali Khowaja, Kapal Dev, Parus Khuwaja, Paolo Bellavista .[Towards Energy Efficient Distributed Federated Learning for 6G Networks](https://arxiv.org/pdf/2201.08270) [J]. arXiv preprint arXiv:2201.08270.
- Afroditi Papadaki, Natalia Martinez, Martin Bertran, Guillermo Sapiro, Miguel Rodrigues .[Minimax Demographic Group Fairness in Federated Learning](https://arxiv.org/pdf/2201.08304) [J]. arXiv preprint arXiv:2201.08304.
- Or Litany, Haggai Maron, David Acuna, Jan Kautz, Gal Chechik, Sanja Fidler .[Federated Learning with Heterogeneous Architectures using Graph HyperNetworks](https://arxiv.org/pdf/2201.08459) [J]. arXiv preprint arXiv:2201.08459.
- Isha Garg, Manish Nagaraj, Kaushik Roy .[TOFU: Towards Obfuscated Federated Updates by Encoding Weight Updates into Gradients from Proxy Data](https://arxiv.org/pdf/2201.08494) [J]. arXiv preprint arXiv:2201.08494.
- Peixi Liu, Guangxu Zhu, Wei Jiang, Wu Luo, Jie Xu, Shuguang Cui .[Vertical Federated Edge Learning with Distributed Integrated Sensing and Communication](https://arxiv.org/pdf/2201.08512) [J]. arXiv preprint arXiv:2201.08512.
- Amir Afaq, Zeeshan Ahmed, Noman Haider, Muhammad Imran .[Blockchain-based Collaborated Federated Learning for Improved Security, Privacy and Reliability](https://arxiv.org/pdf/2201.08551) [J]. arXiv preprint arXiv:2201.08551.
- Dorjan Hitaj, Giulio Pagnotta, Briland Hitaj, Fernando Perez-Cruz, Luigi V. Mancini .[FedComm: Federated Learning as a Medium for Covert Communication](https://arxiv.org/pdf/2201.08786) [J]. arXiv preprint arXiv:2201.08786.
- Guoyang Xie, Jinbao Wang, Yawen Huang, Yuexiang Li, Yefeng Zheng, Feng Zheng, Yaochu Jin .[FedMed-GAN: Federated Domain Translation on Unsupervised Cross-Modality Brain Image Synthesis](https://arxiv.org/pdf/2201.08953) [J]. arXiv preprint arXiv:2201.08953.
- Jingwen Zhang, Yuezhou Wu, Rong Pan .[Online Auction-Based Incentive Mechanism Design for Horizontal Federated Learning with Budget Constraint](https://arxiv.org/pdf/2201.09047) [J]. arXiv preprint arXiv:2201.09047.
- Dhurgham Hassan Mahlool, Mohammed Hamzah Abed .[A Comprehensive Survey on Federated Learning: Concept and Applications](https://arxiv.org/pdf/2201.09384) [J]. arXiv preprint arXiv:2201.09384.
- Chen Wu, Sencun Zhu, Prasenjit Mitra .[Federated Unlearning with Knowledge Distillation](https://arxiv.org/pdf/2201.09441) [J]. arXiv preprint arXiv:2201.09441.
- Wenzhi Fang, Ziyi Yu, Yuning Jiang, Yuanming Shi, Colin N. Jones, Yong Zhou .[Communication-Efficient Stochastic Zeroth-Order Optimization for Federated Learning](https://arxiv.org/pdf/2201.09531) [J]. arXiv preprint arXiv:2201.09531.
- Ninareh Mehrabi, Cyprien de Lichy, John McKay, Cynthia He, William Campbell .[Towards Multi-Objective Statistically Fair Federated Learning](https://arxiv.org/pdf/2201.09917) [J]. arXiv preprint arXiv:2201.09917.
- Yuchang Sun, Jiawei Shao, Songze Li, Yuyi Mao, Jun Zhang .[Stochastic Coded Federated Learning with Convergence and Privacy Guarantees](https://arxiv.org/pdf/2201.10092) [J]. arXiv preprint arXiv:2201.10092.
- Houpu Yao, Jiazhou Wang, Peng Dai, Liefeng Bo, Yanqing Chen .[An Efficient and Robust System for Vertically Federated Random Forest](https://arxiv.org/pdf/2201.10761) [J]. arXiv preprint arXiv:2201.10761.
- Riccardo Zaccone, Andrea Rizzardi, Debora Caldarola, Marco Ciccone, Barbara Caputo .[Speeding up Heterogeneous Federated Learning with Sequentially Trained Superclients](https://arxiv.org/pdf/2201.10899) [J]. arXiv preprint arXiv:2201.10899.
- Giacomo Verardo, Daniel Barreira, Marco Chiesa, Dejan Kostic .[Fast Server Learning Rate Tuning for Coded Federated Dropout](https://arxiv.org/pdf/2201.11036) [J]. arXiv preprint arXiv:2201.11036.
- Grigory Malinovsky, Konstantin Mishchenko, Peter Richtárik .[Server-Side Stepsizes and Sampling Without Replacement Provably Help in Federated Optimization](https://arxiv.org/pdf/2201.11066) [J]. arXiv preprint arXiv:2201.11066.
- Zhenan Fan, Huang Fang, Michael P. Friedlander .[A dual approach for federated learning](https://arxiv.org/pdf/2201.11183) [J]. arXiv preprint arXiv:2201.11183.
- Afaf Taik, Hajar Moudoud, Soumaya Cherkaoui .[Data-Quality Based Scheduling for Federated Edge Learning](https://arxiv.org/pdf/2201.11247) [J]. arXiv preprint arXiv:2201.11247.
- Afaf Taik, Soumaya Cherkaoui .[Electrical Load Forecasting Using Edge Computing and Federated Learning](https://arxiv.org/pdf/2201.11248) [J]. arXiv preprint arXiv:2201.11248.
- Afaf Taik, Zoubeir Mlika, Soumaya Cherkaoui .[Clustered Vehicular Federated Learning: Process and Optimization](https://arxiv.org/pdf/2201.11271) [J]. arXiv preprint arXiv:2201.11271.
- Hajar Moudoud, Soumaya Cherkaoui, Lyes Khoukhi .[Towards a Secure and Reliable Federated Learning using Blockchain](https://arxiv.org/pdf/2201.11311) [J]. arXiv preprint arXiv:2201.11311.
- Tiansheng Huang, Shiwei Liu, Li Shen, Fengxiang He, Weiwei Lin, Dacheng Tao .[Achieving Personalized Federated Learning with Sparse Local Models](https://arxiv.org/pdf/2201.11380) [J]. arXiv preprint arXiv:2201.11380.
- Hanhan Zhou, Tian Lan, Guru Venkataramani, Wenbo Ding .[On the Convergence of Heterogeneous Federated Learning with Arbitrary Adaptive Online Model Pruning](https://arxiv.org/pdf/2201.11803) [J]. arXiv preprint arXiv:2201.11803.
- Jianyu Wang, Hang Qi, Ankit Singh Rawat, Sashank Reddi, Sagar Waghmare, Felix X. Yu, Gauri Joshi .[FedLite: A Scalable Approach for Federated Learning on Resource-constrained Clients](https://arxiv.org/pdf/2201.11865) [J]. arXiv preprint arXiv:2201.11865.
- Jieren Deng, Chenghong Wang, Xianrui Meng, Yijue Wang, Ji Li, Sheng Lin, Shuo Han, Fei Miao, Sanguthevar Rajasekaran, Caiwen Ding .[A Secure and Efficient Federated Learning Framework for NLP](https://arxiv.org/pdf/2201.11934) [J]. arXiv preprint arXiv:2201.11934.
- Irene Tenison, Sai Aravind Sreeramadas, Vaikkunth Mugunthan, Edouard Oyallon, Eugene Belilovsky, Irina Rish .[Gradient Masked Averaging for Federated Learning](https://arxiv.org/pdf/2201.11986) [J]. arXiv preprint arXiv:2201.11986.
- Yuhang Yao, Carlee Joe-Wong .[FedGCN: Convergence and Communication Tradeoffs in Federated Training of Graph Convolutional Networks](https://arxiv.org/pdf/2201.12433) [J]. arXiv preprint arXiv:2201.12433.
- Qiang Meng, Feng Zhou, Hainan Ren, Tianshu Feng, Guochao Liu, Yuanqing Lin .[Improving Federated Learning Face Recognition via Privacy-Agnostic Clusters](https://arxiv.org/pdf/2201.12467) [J]. arXiv preprint arXiv:2201.12467.
- Xizixiang Wei, Cong Shen, Jing Yang, H. Vincent Poor .[Random Orthogonalization for Federated Learning in Massive MIMO Systems](https://arxiv.org/pdf/2201.12490) [J]. arXiv preprint arXiv:2201.12490.
- Tian Liu, Jiahao Ding, Ting Wang, Miao Pan, Mingsong Chen .[Towards Fast and Accurate Federated Learning with non-IID Data for Cloud-Based IoT Applications](https://arxiv.org/pdf/2201.12515) [J]. arXiv preprint arXiv:2201.12515.
- Liam Fowl, Jonas Geiping, Steven Reich, Yuxin Wen, Wojtek Czaja, Micah Goldblum, Tom Goldstein .[Decepticons: Corrupted Transformers Breach Privacy in Federated Learning for Language Models](https://arxiv.org/pdf/2201.12675) [J]. arXiv preprint arXiv:2201.12675.
- Chenghao Huang, Weilong Chen, Yuxi Chen, Shunji Yang, Yanru Zhang .[DearFSAC: An Approach to Optimizing Unreliable Federated Learning via Deep Reinforcement Learning](https://arxiv.org/pdf/2201.12701) [J]. arXiv preprint arXiv:2201.12701.
- Xing Xu, Rongpeng Li, Zhifeng Zhao, Honggang Zhang .[Communication-Efficient Consensus Mechanism for Federated Reinforcement Learning](https://arxiv.org/pdf/2201.12718) [J]. arXiv preprint arXiv:2201.12718.
- Shenglai Zeng, Zonghang Li, Hongfang Yu, Yihong He, Zenglin Xu, Dusit Niyato, Han Yu .[Heterogeneous Federated Learning via Grouped Sequential-to-Parallel Training](https://arxiv.org/pdf/2201.12976) [J]. arXiv preprint arXiv:2201.12976.
- Mahyar Shirvanimoghaddam, Yifeng Gao, Aradhika Guha, Ayoob Salari .[Federated Learning with Erroneous Communication Links](https://arxiv.org/pdf/2201.12991) [J]. arXiv preprint arXiv:2201.12991.
- Tianyue Chu, Alvaro Garcia-Recuero, Costas Iordanou, Georgios Smaragdakis, Nikolaos Laoutaris .[Securing Federated Sensitive Topic Classification against Poisoning Attacks](https://arxiv.org/pdf/2201.13086) [J]. arXiv preprint arXiv:2201.13086.
- Mathieu Even, Laurent Massoulié, Kevin Scaman .[Sample Optimality and All-for-all Strategies in Personalized Federated and Collaborative Learning](https://arxiv.org/pdf/2201.13097) [J]. arXiv preprint arXiv:2201.13097.
- Pedro Miguel Sánchez Sánchez, Alberto Huertas Celdrán, Timo Schenk, Adrian Lars Benjamin Iten, Gérôme Bovet, Gregorio Martínez Pérez, Burkhard Stiller .[Studying the Robustness of Anti-adversarial Federated Learning Models Detecting Cyberattacks in IoT Spectrum Sensors](https://arxiv.org/pdf/2202.00137) [J]. arXiv preprint arXiv:2202.00137.
- Jin-Hyun Ahn, Kyungsang Kim, Jeongwan Koh, Quanzheng Li .[Federated Active Learning (F-AL): an Efficient Annotation Strategy for Federated Learning](https://arxiv.org/pdf/2202.00195) [J]. arXiv preprint arXiv:2202.00195.
- Wonyong Jeong, Sung Ju Hwang .[Factorized-FL: Agnostic Personalized Federated Learning with Kernel Factorization & Similarity Matching](https://arxiv.org/pdf/2202.00270) [J]. arXiv preprint arXiv:2202.00270.
- Sheikh Shams Azam, Seyyedali Hosseinalipour, Qiang Qiu, Christopher Brinton .[Recycling Model Updates in Federated Learning: Are Gradient Subspaces Low-Rank?](https://arxiv.org/pdf/2202.00280) [J]. arXiv preprint arXiv:2202.00280.
- Mohammad Hassan Adeli, Alphan Sahin .[Multi-cell Non-coherent Over-the-Air Computation for Federated Edge Learning](https://arxiv.org/pdf/2202.00506) [J]. arXiv preprint arXiv:2202.00506.
- Yuxin Wen, Jonas Geiping, Liam Fowl, Micah Goldblum, Tom Goldstein .[Fishing for User Data in Large-Batch Federated Learning via Gradient Magnification](https://arxiv.org/pdf/2202.00580) [J]. arXiv preprint arXiv:2202.00580.
- Aleksandar Armacki, Dragana Bajovic, Dusan Jakovetic, Soummya Kar .[Personalized Federated Learning via Convex Clustering](https://arxiv.org/pdf/2202.00718) [J]. arXiv preprint arXiv:2202.00718.
- Jie Ding, Eric Tramel, Anit Kumar Sahu, Shuang Wu, Salman Avestimehr, Tao Zhang .[Federated Learning Challenges and Opportunities: An Outlook](https://arxiv.org/pdf/2202.00807) [J]. arXiv preprint arXiv:2202.00807.
- Chuanhao Li, Hongning Wang .[Communication Efficient Federated Learning for Generalized Linear Bandits](https://arxiv.org/pdf/2202.01087) [J]. arXiv preprint arXiv:2202.01087.
- Seongin Na, Tomáš Krajník, Barry Lennox, Farshad Arvin .[Federated Reinforcement Learning for Collective Navigation of Robotic Swarms](https://arxiv.org/pdf/2202.01141) [J]. arXiv preprint arXiv:2202.01141.
- Jinhyun So, Kevin Hsieh, Behnaz Arzani, Shadi Noghabi, Salman Avestimehr, Ranveer Chandra .[FedSpace: An Efficient Federated Learning Framework at Satellites and Ground Stations](https://arxiv.org/pdf/2202.01267) [J]. arXiv preprint arXiv:2202.01267.
- Zonghang Li, Yihong He, Hongfang Yu, Jiawen Kang, Xiaoping Li, Zenglin Xu, Dusit Niyato .[Data Heterogeneity-Robust Federated Learning via Group Client Selection in Industrial IoT](https://arxiv.org/pdf/2202.01512) [J]. arXiv preprint arXiv:2202.01512.
- Ibrahim Abdul Majeed, Sagar Kaushik, Aniruddha Bardhan, Venkata Siva Kumar Tadi, Hwang-Ki Min, Karthikeyan Kumaraguru, Rajasekhara Duvvuru Muni .[Comparative assessment of federated and centralized machine learning](https://arxiv.org/pdf/2202.01529) [J]. arXiv preprint arXiv:2202.01529.
- Guojun Zhang, Saber Malekmohammadi, Xi Chen, Yaoliang Yu .[Equality Is Not Equity: Proportional Fairness in Federated Learning](https://arxiv.org/pdf/2202.01666) [J]. arXiv preprint arXiv:2202.01666.
- Yifeng Zheng, Shangqi Lai, Yi Liu, Xingliang Yuan, Xun Yi, Cong Wang .[Aggregation Service for Federated Learning: An Efficient, Secure, and More Resilient Realization](https://arxiv.org/pdf/2202.01971) [J]. arXiv preprint arXiv:2202.01971.
- L. P. Barnes, Alex Dytso, H. V. Poor .[Improved Information Theoretic Generalization Bounds for Distributed and Federated Learning](https://arxiv.org/pdf/2202.02423) [J]. arXiv preprint arXiv:2202.02423.
- Leijie Wu, Song Guo, Yaohong Ding, Yufeng Zhan, Jie Zhang .[A Coalition Formation Game Approach for Personalized Federated Learning](https://arxiv.org/pdf/2202.02502) [J]. arXiv preprint arXiv:2202.02502.
- Yicheng Chen, Rick S. Blum, Brian M. Sadler .[Communication Efficient Federated Learning via Ordered ADMM in a Fully Decentralized Setting](https://arxiv.org/pdf/2202.02580) [J]. arXiv preprint arXiv:2202.02580.
- Vasileios Tsouvalas, Tanir Ozcelebi, Nirvana Meratnia .[Privacy-preserving Speech Emotion Recognition through Semi-Supervised Federated Learning](https://arxiv.org/pdf/2202.02611) [J]. arXiv preprint arXiv:2202.02611.
- Y. Li, X. Qin, H. Chen, K. Han, P. Zhang .[Energy-Aware Edge Association for Cluster-based Personalized Federated Learning](https://arxiv.org/pdf/2202.02727) [J]. arXiv preprint arXiv:2202.02727.
- Arup Mondal, Harpreet Virk, Debayan Gupta .[BEAS: Blockchain Enabled Asynchronous & Secure Federated Machine Learning](https://arxiv.org/pdf/2202.02817) [J]. arXiv preprint arXiv:2202.02817.
- Shuang Dai, Fanlin Meng .[Addressing modern and practical challenges in machine learning: A survey of online federated and transfer learning](https://arxiv.org/pdf/2202.03070) [J]. arXiv preprint arXiv:2202.03070.
- Konstantin Burlachenko, Samuel Horváth, Peter Richtárik .[FL_PyTorch: optimization research simulator for federated learning](https://arxiv.org/pdf/2202.03099) [J]. arXiv preprint arXiv:2202.03099.
- Jing Xu, Rui Wang, Kaitai Liang, Stjepan Picek .[More is Better (Mostly): On the Backdoor Attacks in Federated Graph Neural Networks](https://arxiv.org/pdf/2202.03195) [J]. arXiv preprint arXiv:2202.03195.
- Truc Nguyen, My T. Thai .[Preserving Privacy and Security in Federated Learning](https://arxiv.org/pdf/2202.03402) [J]. arXiv preprint arXiv:2202.03402.
- Peiying Zhang, Chao Wang, Chunxiao Jiang, Zhu Han .[Deep Reinforcement Learning Assisted Federated Learning Algorithm for Data Management of IIoT](https://arxiv.org/pdf/2202.03575) [J]. arXiv preprint arXiv:2202.03575.
- Minseok Ryu, Youngdae Kim, Kibaek Kim, Ravi K. Madduri .[APPFL: Open-Source Software Framework for Privacy-Preserving Federated Learning](https://arxiv.org/pdf/2202.03672) [J]. arXiv preprint arXiv:2202.03672.
- Shadi Rahimian, Raouf Kerkouche, Ina Kurth, Mario Fritz .[Practical Challenges in Differentially-Private Federated Survival Analysis of Medical Data](https://arxiv.org/pdf/2202.03758) [J]. arXiv preprint arXiv:2202.03758.
- Christophe Dupuy, Tanya G. Roosta, Leo Long, Clement Chung, Rahul Gupta, Salman Avestimehr .[Learnings from Federated Learning in the Real world](https://arxiv.org/pdf/2202.03925) [J]. arXiv preprint arXiv:2202.03925.
- Tayyebeh Jahani-Nezhad, Mohammad Ali Maddah-Ali, Songze Li, Giuseppe Caire .[SwiftAgg: Communication-Efficient and Dropout-Resistant Secure Aggregation for Federated Learning with Worst-Case Security Guarantees](https://arxiv.org/pdf/2202.04169) [J]. arXiv preprint arXiv:2202.04169.
- Gokberk Elmas, Salman UH Dar, Yilmaz Korkmaz, Emir Ceyani, Burak Susam, Muzaffer Özbey, Salman Avestimehr, Tolga Çukur .[Federated Learning of Generative Image Priors for MRI Reconstruction](https://arxiv.org/pdf/2202.04175) [J]. arXiv preprint arXiv:2202.04175.
- Kang Wei, Jun Li, Chuan Ma, Ming Ding, Sha Wei, Fan Wu, Guihai Chen, Thilina Ranbaduge .[Vertical Federated Learning: Challenges, Methodologies and Experiments](https://arxiv.org/pdf/2202.04309) [J]. arXiv preprint arXiv:2202.04309.
- Yuxi Mi, Jihong Guan, Shuigeng Zhou .[ARIBA: Towards Accurate and Robust Identification of Backdoor Attacks in Federated Learning](https://arxiv.org/pdf/2202.04311) [J]. arXiv preprint arXiv:2202.04311.
- Gilles Callebaut, Jarne Van Mulders, Geoffrey Ottoy, Daan Delabie, Bert Cox, Nobby Stevens, Liesbet Van der Perre .[Techtile -- Open 6G R&D Testbed for Communication, Positioning, Sensing, WPT and Federated Learning](https://arxiv.org/pdf/2202.04524) [J]. arXiv preprint arXiv:2202.04524.
- Addi Ait-Mlouk, Sadi Alawadi, Salman Toor, Andreas Hellander .[FedQAS: Privacy-aware machine reading comprehension with federated learning](https://arxiv.org/pdf/2202.04742) [J]. arXiv preprint arXiv:2202.04742.
- Chunyi Zhou, Yansong Gao, Anmin Fu, Kai Chen, Zhiyang Dai, Zhi Zhang, Minhui Xue, Yuqing Zhang .[PPA: Preference Profiling Attack Against Federated Learning](https://arxiv.org/pdf/2202.04856) [J]. arXiv preprint arXiv:2202.04856.
- Chuhan Wu, Fangzhao Wu, Tao Qi, Yongfeng Huang, Xing Xie .[FedAttack: Effective and Covert Poisoning Attack on Federated Recommendation via Hard Sampling](https://arxiv.org/pdf/2202.04975) [J]. arXiv preprint arXiv:2202.04975.
- Chuhan Wu, Fangzhao Wu, Tao Qi, Yanlin Wang, Yuqing Yang, Yongfeng Huang, Xing Xie .[Game of Privacy: Towards Better Federated Platform Collaboration under Privacy Restriction](https://arxiv.org/pdf/2202.05139) [J]. arXiv preprint arXiv:2202.05139.
- Alberto Bietti, Chen-Yu Wei, Miroslav Dudik, John Langford, Zhiwei Steven Wu .[Personalization Improves Privacy-Accuracy Tradeoffs in Federated Optimization](https://arxiv.org/pdf/2202.05318) [J]. arXiv preprint arXiv:2202.05318.
- Nicolò Dal Fabbro, Subhrakanti Dey, Michele Rossi, Luca Schenato .[A Newton-type algorithm for federated learning based on incremental Hessian eigenvector sharing](https://arxiv.org/pdf/2202.05800) [J]. arXiv preprint arXiv:2202.05800.
- Jiyue Huang, Zilong Zhao, Lydia Y. Chen, Stefanie Roos .[Blind leads Blind: A Zero-Knowledge Attack on Federated Learning](https://arxiv.org/pdf/2202.05877) [J]. arXiv preprint arXiv:2202.05877.
- M.A.P. Chamikara, Dongxi Liu, Seyit Camtepe, Surya Nepal, Marthie Grobler, Peter Bertok, Ibrahim Khalil .[Local Differential Privacy for Federated Learning in Industrial Settings](https://arxiv.org/pdf/2202.06053) [J]. arXiv preprint arXiv:2202.06053.
- Cong Shen, Jing Yang, Jie Xu .[On Federated Learning with Energy Harvesting Clients](https://arxiv.org/pdf/2202.06105) [J]. arXiv preprint arXiv:2202.06105.
- Jie Ma, Guodong Long, Tianyi Zhou, Jing Jiang, Chengqi Zhang .[On the Convergence of Clustered Federated Learning](https://arxiv.org/pdf/2202.06187) [J]. arXiv preprint arXiv:2202.06187.
- Zhilin Wang, Qiao Kang, Xinyi Zhang, Qin Hu .[Defense Strategies Toward Model Poisoning Attacks in Federated Learning: A Survey](https://arxiv.org/pdf/2202.06414) [J]. arXiv preprint arXiv:2202.06414.
- Hyunsu Mun, Youngseok Lee .[FLHub: a Federated Learning model sharing service](https://arxiv.org/pdf/2202.06493) [J]. arXiv preprint arXiv:2202.06493.
- Jingwei Yi, Fangzhao Wu, Bin Zhu, Yang Yu, Chao Zhang, Guangzhong Sun, Xing Xie .[UA-FedRec: Untargeted Attack on Federated News Recommendation](https://arxiv.org/pdf/2202.06701) [J]. arXiv preprint arXiv:2202.06701.
- Ali Hatamizadeh, Hongxu Yin, Pavlo Molchanov, Andriy Myronenko, Wenqi Li, Prerna Dogra, Andrew Feng, Mona G. Flores, Jan Kautz, Daguang Xu, Holger R. Roth .[Do Gradient Inversion Attacks Make Federated Learning Unsafe?](https://arxiv.org/pdf/2202.06924) [J]. arXiv preprint arXiv:2202.06924.
- Fumiyuki Kato, Yang Cao, Masatoshi Yoshikawa .[OLIVE: Oblivious and Differentially Private Federated Learning on Trusted Execution Environment](https://arxiv.org/pdf/2202.07165) [J]. arXiv preprint arXiv:2202.07165.
- Rui Hu, Yanmin Gong, Yuanxiong Guo .[Federated Learning with Sparsified Model Perturbation: Improving Accuracy under Client-Level Differential Privacy](https://arxiv.org/pdf/2202.07178) [J]. arXiv preprint arXiv:2202.07178.
- Rui Liu, Han Yu .[Federated Graph Neural Networks: Overview, Techniques and Challenges](https://arxiv.org/pdf/2202.07256) [J]. arXiv preprint arXiv:2202.07256.
- Jingjing Zheng, Kai Li, Naram Mhaisen, Wei Ni, Eduardo Tovar, Mohsen Guizani .[Exploring Deep Reinforcement Learning-Assisted Federated Learning for Online Resource Allocation in EdgeIoT](https://arxiv.org/pdf/2202.07391) [J]. arXiv preprint arXiv:2202.07391.
- Yawen Wu, Dewen Zeng, Zhepeng Wang, Yi Sheng, Lei Yang, Alaina J. James, Yiyu Shi, Jingtong Hu .[Federated Contrastive Learning for Dermatological Disease Diagnosis via On-device Learning](https://arxiv.org/pdf/2202.07470) [J]. arXiv preprint arXiv:2202.07470.
- Disha Makhija, Xing Han, Nhat Ho, Joydeep Ghosh .[Architecture Agnostic Federated Learning for Neural Networks](https://arxiv.org/pdf/2202.07757) [J]. arXiv preprint arXiv:2202.07757.
- Guochen Yu, Andong Li, Hui Wang, Yutian Wang, Yuxuan Ke, Chengshi Zheng .[DBT-Net: Dual-branch federative magnitude and phase estimation with attention-in-attention transformer for monaural speech enhancement](https://arxiv.org/pdf/2202.07931) [J]. arXiv preprint arXiv:2202.07931.
- Ruixuan Liu, Fangzhao Wu, Chuhan Wu, Yanlin Wang, Lingjuan Lyu, Hong Chen, Xing Xie .[No One Left Behind: Inclusive Federated Learning over Heterogeneous Devices](https://arxiv.org/pdf/2202.08036) [J]. arXiv preprint arXiv:2202.08036.
- Ece Isik-Polat, Gorkem Polat, Altan Kocyigit, Alptekin Temizel .[Evaluation and Analysis of Different Aggregation and Hyperparameter Selection Methods for Federated Brain Tumor Segmentation](https://arxiv.org/pdf/2202.08261) [J]. arXiv preprint arXiv:2202.08261.
- Yanci Zhang, Han Yu .[Towards Verifiable Federated Learning](https://arxiv.org/pdf/2202.08310) [J]. arXiv preprint arXiv:2202.08310.
- Yi Zhou, Parikshit Ram, Theodoros Salonidis, Nathalie Baracaldo, Horst Samulowitz, Heiko Ludwig .[Single-shot Hyper-parameter Optimization for Federated Learning: A General Algorithm & Analysis](https://arxiv.org/pdf/2202.08338) [J]. arXiv preprint arXiv:2202.08338.
- Jianan Chen, Qin Hu, Honglu Jiang .[MMZDA: Enabling Social Welfare Maximization in Cross-Silo Federated Learning](https://arxiv.org/pdf/2202.08362) [J]. arXiv preprint arXiv:2202.08362.
- Howard H. Yang, Zuozhu Liu, Yaru Fu, Tony Q. S. Quek, H. Vincent Poor .[Federated Stochastic Gradient Descent Begets Self-Induced Momentum](https://arxiv.org/pdf/2202.08402) [J]. arXiv preprint arXiv:2202.08402.
- Yuxuan Sun, Sheng Zhou, Zhisheng Niu, Deniz Gündüz .[Time-Correlated Sparsification for Efficient Over-the-Air Model Aggregation in Wireless Federated Learning](https://arxiv.org/pdf/2202.08420) [J]. arXiv preprint arXiv:2202.08420.
- Xingjian Cao, Zonghang Li, Hongfang Yu, Gang Sun .[CoFED: Cross-silo Heterogeneous Federated Multi-task Learning via Co-training](https://arxiv.org/pdf/2202.08603) [J]. arXiv preprint arXiv:2202.08603.
- Hyunsung Cho, Akhil Mathur, Fahim Kawsar .[FLAME: Federated Learning Across Multi-device Environments](https://arxiv.org/pdf/2202.08922) [J]. arXiv preprint arXiv:2202.08922.
- Jianan Chen, Qin Hu, Honglu Jiang .[Social Welfare Maximization in Cross-Silo Federated Learning](https://arxiv.org/pdf/2202.09044) [J]. arXiv preprint arXiv:2202.09044.
- Xingjian Cao, Gang Sun, Hongfang Yu, Mohsen Guizani .[PerFED-GAN: Personalized Federated Learning via Generative Adversarial Networks](https://arxiv.org/pdf/2202.09155) [J]. arXiv preprint arXiv:2202.09155.
- Minseok Ryu, Kibaek Kim .[Differentially Private Federated Learning via Inexact ADMM with Multiple Local Updates](https://arxiv.org/pdf/2202.09409) [J]. arXiv preprint arXiv:2202.09409.
- Andrew Silva, Katherine Metcalf, Nicholas Apostoloff, Barry-John Theobald .[FedEmbed: Personalized Private Federated Learning](https://arxiv.org/pdf/2202.09472) [J]. arXiv preprint arXiv:2202.09472.
- Sotirios Nikoloutsopoulos, Iordanis Koutsopoulos, Michalis K. Titsias .[Personalized Federated Learning with Exact Stochastic Gradient Descent](https://arxiv.org/pdf/2202.09848) [J]. arXiv preprint arXiv:2202.09848.
- David Byrd, Vaikkunth Mugunthan, Antigoni Polychroniadou, Tucker Hybinette Balch .[Collusion Resistant Federated Learning with Oblivious Distributed Differential Privacy](https://arxiv.org/pdf/2202.09897) [J]. arXiv preprint arXiv:2202.09897.
- Jingyang Zhang, Yiran Chen, Hai Li .[Privacy Leakage of Adversarial Training Models in Federated Learning Systems](https://arxiv.org/pdf/2202.10546) [J]. arXiv preprint arXiv:2202.10546.
- Binayak Kar, Widhi Yahya, Ying-Dar Lin, Asad Ali .[A Survey on Offloading in Federated Cloud-Edge-Fog Systems with Traditional Optimization and Machine Learning](https://arxiv.org/pdf/2202.10628) [J]. arXiv preprint arXiv:2202.10628.
- Zhilin Wang, Qin Hu, Ruinian Li, Minghui Xu, Zehui Xiong .[Incentive Mechanism Design for Joint Resource Allocation in Blockchain-based Federated Learning](https://arxiv.org/pdf/2202.10938) [J]. arXiv preprint arXiv:2202.10938.
- Yein Kim, Huili Chen, Farinaz Koushanfar .[Backdoor Defense in Federated Learning Using Differential Testing and Outlier Detection](https://arxiv.org/pdf/2202.11196) [J]. arXiv preprint arXiv:2202.11196.
- Jaehong Yoon, Geon Park, Wonyong Jeong, Sung Ju Hwang .[Bitwidth Heterogeneous Federated Learning with Progressive Weight Dequantization](https://arxiv.org/pdf/2202.11453) [J]. arXiv preprint arXiv:2202.11453.
- Chunhui Zhang, Xiaoming Yuan, Qianyun Zhang, Guangxu Zhu, Lei Cheng, Ning Zhang .[Towards Tailored Models on Private AIoT Devices: Federated Direct Neural Architecture Search](https://arxiv.org/pdf/2202.11490) [J]. arXiv preprint arXiv:2202.11490.
- Jie Zhu, Shenggui Li, Yang You .[Sky Computing: Accelerating Geo-distributed Computing in Federated Learning](https://arxiv.org/pdf/2202.11836) [J]. arXiv preprint arXiv:2202.11836.
- Michal Yemini, Rajarshi Saha, Emre Ozfatura, Deniz Gündüz, Andrea J. Goldsmith .[Robust Federated Learning with Connectivity Failures: A Semi-Decentralized Framework with Collaborative Relaying](https://arxiv.org/pdf/2202.11850) [J]. arXiv preprint arXiv:2202.11850.
- Matthew Ashman, Thang D. Bui, Cuong V. Nguyen, Stratis Markou, Adrian Weller, Siddharth Swaroop, Richard E. Turner .[Partitioned Variational Inference: A Framework for Probabilistic Federated Learning](https://arxiv.org/pdf/2202.12275) [J]. arXiv preprint arXiv:2202.12275.
- Nathalie Baracaldo, Ali Anwar, Mark Purcell, Ambrish Rawat, Mathieu Sinn, Bashar Altakrouri, Dian Balta, Mahdi Sellami, Peter Kuhn, Ulrich Schopp, Matthias Buchinger .[Towards an Accountable and Reproducible Federated Learning: A FactSheets Approach](https://arxiv.org/pdf/2202.12443) [J]. arXiv preprint arXiv:2202.12443.
- Ming Hu, Tian Liu, Zhiwei Ling, Zhihao Yue, Mingsong Chen .[FedCAT: Towards Accurate Federated Learning via Device Concatenation](https://arxiv.org/pdf/2202.12751) [J]. arXiv preprint arXiv:2202.12751.
- Pouya M Ghari, Yanning Shen .[Graph-Assisted Communication-Efficient Ensemble Federated Learning](https://arxiv.org/pdf/2202.13447) [J]. arXiv preprint arXiv:2202.13447.
- Chi-Hua Wang, Wenjie Li, Guang Cheng, Guang Lin .[Federated Online Sparse Decision Making](https://arxiv.org/pdf/2202.13448) [J]. arXiv preprint arXiv:2202.13448.
- Qi Liu (1, 2 and 3), Bo Yang (1, 2 and 3), Zhaojian Wang (1, 2 and 3), Dafeng Zhu (1, 2 and 3), Xinyi Wang (1, 2 and 3), Kai Ma (4), Xinping Guan (1, 2 and 3) ((1) Department of Automation, Shanghai Jiao Tong University, Shanghai, China, (2) Key Laboratory of System Control and Information Processing, Ministry of Education of China, Shanghai, China, (3) Shanghai Engineering Research Center of Intelligent Control and Management, Shanghai, China, (4) School of Electrical Engineering, Yanshan University, Qinhuangdao, China.) .[Asynchronous Decentralized Federated Learning for Collaborative Fault Diagnosis of PV Stations](https://arxiv.org/pdf/2202.13606) [J]. arXiv preprint arXiv:2202.13606.
- Dongjun Hwang, Hyunsu Mun, Youngseok Lee .[Improving Response Time of Home IoT Services in Federated Learning](https://arxiv.org/pdf/2202.13626) [J]. arXiv preprint arXiv:2202.13626.
- Lidia Fantauzzo, Eros Fani', Debora Caldarola, Antonio Tavera, Fabio Cermelli, Marco Ciccone, Barbara Caputo .[FedDrive: Generalizing Federated Learning to Semantic Segmentation in Autonomous Driving](https://arxiv.org/pdf/2202.13670) [J]. arXiv preprint arXiv:2202.13670.
- Marvin Xhemrishi, Alexandre Graell i Amat, Eirik Rosnes, Antonia Wachter-Zeh .[Computational Code-Based Privacy in Coded Federated Learning](https://arxiv.org/pdf/2202.13798) [J]. arXiv preprint arXiv:2202.13798.
- Yunchuan Zhang, Dongzhu Liu, Osvaldo Simeone .[Leveraging Channel Noise for Sampling and Privacy via Quantized Federated Langevin Monte Carlo](https://arxiv.org/pdf/2202.13932) [J]. arXiv preprint arXiv:2202.13932.


## Blogs && Tutorials
- [Learn to adapt Flower for your use-case](https://flower.dev/blog)
- [Flower](https://flower.dev/docs/example_walkthrough_pytorch_mnist.html)
- [Online Comic from Google AI on Federated Learning](https://federated.withgoogle.com/)
- [PPT][thormacy/Federated-Learning](https://github.com/thormacy/Federated-Learning/tree/master/PPT)
- [Federated Learning: Collaborative Machine Learning without Centralized Training Data](https://ai.googleblog.com/2017/04/federated-learning-collaborative.html) - Google AI Blog 2017
- [Under The Hood of The Pixel 2: How AI Is Supercharging Hardware](https://ai.google/stories/ai-in-hardware/)
- [An Introduction to Federated Learning](http://vision.cloudera.com/an-introduction-to-federated-learning/)
- [Federated learning: Distributed machine learning with data locality and privacy](https://blog.fastforwardlabs.com/2018/11/14/federated-learning.html)
- [Federated Learning: The Future of Distributed Machine Learning](https://medium.com/syncedreview/federated-learning-the-future-of-distributed-machine-learning-eec95242d897)
- [Federated Learning for Wake Word Detection](https://medium.com/snips-ai/federated-learning-for-wake-word-detection-c8b8c5cdd2c5)
- [An Open Framework for Secure and Privated AI](https://medium.com/@ODSC/an-open-framework-for-secure-and-private-ai-96c1891a4b)
- [A Brief Introduction to Differential Privacy](https://medium.com/georgian-impact-blog/a-brief-introduction-to-differential-privacy-eacf8722283b)
- [An Overview of Federated Learning](https://medium.com/datadriveninvestor/an-overview-of-federated-learning-8a1a62b0600d). This blog introduces some challenges of federated learning, including *Inference Attack* and *Model Poisoning*.
- [PySyft](https://github.com/OpenMined/PySyft/tree/dev/examples/tutorials)
- [tensorflow TFF](https://www.tensorflow.org/federated/tutorials/federated_learning_for_image_classification)
- [open-intelligence/federated-learning-chinese](https://github.com/open-intelligence/federated-learning-chinese)
- [杨强：联邦学习](https://mp.weixin.qq.com/s/5FTrG5SZey2yeIbuyT3HoQ)
- [联邦学习的研究及应用](https://mp.weixin.qq.com/s?src=11&timestamp=1555896266&ver=1561&signature=ZtLlc7qakNAdw8hV3dxaB30PxtK9hAshYsIxccFf-D4eJrUw6YKQcqD0lD3SDMEn4egQTafUZr429er7SueP6HKLTr*uFKfr6JuHc3OvfdJ-uExiEJStHFynC65htbLp&new=1)
- [杨强：GDPR对AI的挑战和基于联邦迁移学习的对策](https://zhuanlan.zhihu.com/p/42646278)
- [联邦学习的研究与应用](https://aisp-1251170195.file.myqcloud.com/fedweb/1553845987342.pdf)
- [Federated Learning and Transfer Learning for Privacy, Security and Confidentiality](https://aisp-1251170195.file.myqcloud.com/fedweb/1552916850679.pdf) (AAAI-19)
- [GDPR, Data Shortage and AI](https://aisp-1251170195.file.myqcloud.com/fedweb/1552916659436.pdf) (AAAI-19)
- [GDPR, Data Shortage and AI](https://aaai.org/Conferences/AAAI-19/invited-speakers/#yang) (AAAI-19 Invited Talk)
- [video][GDPR, Data Shortage and AI](https://vimeo.com/313941621) - Qiang Yang, AAAI 2019 Invited Talk
- [谷歌发布全球首个产品级移动端分布式机器学习系统，数千万手机同步训练](https://www.jiemian.com/article/2853096.html)
- [clara-federated-learning](https://blogs.nvidia.com/blog/2019/12/01/clara-federated-learning/)
- [What is Federated Learning](https://blogs.nvidia.com/blog/2019/10/13/what-is-federated-learning/) - Nvidia 2019
- [nvidia-uses-federated-learning-to-create-medical-imaging-ai](https://venturebeat.com/2019/10/13/nvidia-uses-federated-learning-to-create-medical-imaging-ai/)
- [federated-learning-technique-predicts-hospital-stay-and-patient-mortality](https://venturebeat.com/2019/03/25/federated-learning-technique-predicts-hospital-stay-and-patient-mortality/)
- [pubmed](https://www.ncbi.nlm.nih.gov/pubmed/29500022)
- [google-mayo-clinic-partnership-patient-data](https://www.statnews.com/2019/09/10/google-mayo-clinic-partnership-patient-data/)
- [webank-clustar](https://www.digfingroup.com/webank-clustar/)
- [Private AI-Federated Learning with PySyft and PyTorch](https://towardsdatascience.com/private-ai-federated-learning-with-pysyft-and-pytorch-954a9e4a4d4e)
- [Federated Learning in 10 lines of PyTorch and PySyft](https://blog.openmined.org/upgrade-to-federated-learning-in-10-lines/)
- [A beginners Guided to Federated Learning](https://hackernoon.com/a-beginners-guide-to-federated-learning-b29e29ba65cf). Federated Learning was born at the intersection of on-device AI, blockchain, and edge computing/IoT.
- [video][Federated Learning: Machine Learning on Decentralized Data (Google I/O'19)](https://www.youtube.com/watch?v=89BGjQYA0uE)
- [video][TensorFlow Federated (TFF): Machine Learning on Decentralized Data ](https://www.youtube.com/watch?v=1YbPmkChcbo)
- [video][Federated Learning: Machine Learning on Decentralized Data](https://www.youtube.com/watch?v=89BGjQYA0uE)
- [video][Federated Learning](https://www.youtube.com/watch?v=xJkY3ehX_MI)
- [video][Making every phone smarter with Federated Learning](https://www.youtube.com/watch?v=gbRJPa9d-VU) - Google, 2018
- [video][Secure and Private AI Udacity](https://classroom.udacity.com/courses/ud185)


## Framework
- [FederatedAI/FATE](https://github.com/FederatedAI/FATE);   [DOC](https://fate.readthedocs.io/en/latest/index.html);   [VIDEO](https://edu.51cto.com/lesson/513105)
- [jd-9n/9nfl](https://github.com/jd-9n/9nfl)
- [tensorflow/federated](https://github.com/tensorflow/federated)
- [LatticeX-Foundation/Rosetta](https://github.com/LatticeX-Foundation/Rosetta)
- [bytedance/fedlearner](https://github.com/bytedance/fedlearner)
- [FedML-AI/FedML](https://github.com/FedML-AI/FedML)
- [IBM/federated-learning-lib](https://github.com/IBM/federated-learning-lib)
- [OpenMined/PySyft](https://github.com/OpenMined/PySyft)
- [PaddlePaddle/PaddleFL](https://github.com/PaddlePaddle/PaddleFL)
- [flower](https://flower.dev/)
- [facebookresearch/CrypTen](https://github.com/facebookresearch/CrypTen)
- [SMILELab-FL/FedLab](https://github.com/SMILELab-FL/FedLab)
- [cyqclark/fedlearn-algo](https://github.com/cyqclark/fedlearn-algo)
- [scaleoutsystems/fedn](https://github.com/scaleoutsystems/fedn)
- [intel/openfl](https://github.com/intel/openfl)
- [NVIDIA Clara](https://developer.nvidia.com/clara)
- [EasyFL-AI/EasyFL](https://github.com/EasyFL-AI/EasyFL)
- [xaynetwork/xaynet](https://github.com/xaynetwork/xaynet)
- [google/fedjax](https://github.com/google/fedjax)
- [alibaba/FederatedScope](https://github.com/alibaba/FederatedScope)
- [secretflow隐语](https://github.com/secretflow)
- [deltampc](https://deltampc.com/)
- [epfml/disco](https://github.com/epfml/disco)
- [FederalLab/OpenFed](https://github.com/FederalLab/OpenFed)

## Projects
- [osu-crypto/libPSI](https://github.com/osu-crypto/libPSI)
- [shashigharti/federated-learning-on-raspberry-pi](https://github.com/shashigharti/federated-learning-on-raspberry-pi)
- [shaoxiongji/federated-learning](https://github.com/shaoxiongji/federated-learning)
- [mccorby](https://github.com/mccorby)
- [roxanneluo/Federated-Learning](https://github.com/roxanneluo/Federated-Learning)
- [dvc](https://dvc.org/) # unknown
- [papersdclub/Differentially_private_federated_learning](https://github.com/papersdclub/Differentially_private_federated_learning)
- [AshwinRJ/Federated-Learning-PyTorch](https://github.com/AshwinRJ/Federated-Learning-PyTorch)
- [OpenMined/PyVertical](https://github.com/OpenMined/PyVertical)
- [GalaxyLearning/GFL](https://github.com/GalaxyLearning/GFL/blob/master/README_cn.md)
- [LabeliaLabs/distributed-learning-contributivity](https://github.com/LabeliaLabs/distributed-learning-contributivity)
- [ownership-labs/OpenHealth](https://github.com/ownership-labs/OpenHealth)
- [wnma3mz/flearn](https://github.com/wnma3mz/flearn)
- [FELToken/federated-learning-token](https://github.com/FELToken/federated-learning-token)


## Datasets && Benchmark
- [Federated iNaturalist/Landmarks](https://github.com/google-research/google-research/tree/master/federated_vision_datasets)
- [DIDL][A Performance Evaluation of Federated Learning Algorithms](https://www.researchgate.net/profile/Gregor_Ulm/publication/329106719_A_Performance_Evaluation_of_Federated_Learning_Algorithms/links/5c0fabcfa6fdcc494febf907/A-Performance-Evaluation-of-Federated-Learning-Algorithms.pdf)
- Gregor Ulm, Emil Gustavsson, Mats Jirstrand .[Functional Federated Learning in Erlang (ffl-erl)](https://arxiv.org/pdf/1808.08143) [J]. arXiv preprint arXiv:1808.08143.
- Caldas S, Duddu S M K, Wu P, et al. [Leaf: A benchmark for federated settings](https://arxiv.org/abs/1812.01097)[J]. arXiv preprint arXiv:1812.01097, 2018. <br> [code:[Github](https://github.com/TalwalkarLab/leaf);[website](https://leaf.cmu.edu/)];[code-pytorch](https://github.com/SMILELab-FL/FedLab-benchmarks/tree/master/fedlab_benchmarks/leaf)
- [Edge AIBench: Towards Comprehensive End-to-end Edge Computing Benchmarking](https://arxiv.org/abs/1908.01924)
- Jiahuan Luo, Xueyang Wu, Yun Luo, Anbu Huang, Yunfeng Huang, Yang Liu, Qiang Yang .[Real-World Image Datasets for Federated Learning](https://arxiv.org/pdf/1910.11089) [J]. arXiv preprint arXiv:1910.11089.
- Yang Liu, Zhuo Ma, Ximeng Liu, Zhuzhu Wang, Siqi Ma, Ken Ren .[Revocable Federated Learning: A Benchmark of Federated Forest](https://arxiv.org/pdf/1911.03242) [J]. arXiv preprint arXiv:1911.03242.
- Vaikkunth Mugunthan, Anton Peraire-Bueno, Lalana Kagal .[PrivacyFL: A simulator for privacy-preserving and secure federated learning](https://arxiv.org/pdf/2002.08423) [J]. arXiv preprint arXiv:2002.08423.
- Lifeng Liu, Fengda Zhang, Jun Xiao, Chao Wu .[Evaluation Framework For Large-scale Federated Learning](https://arxiv.org/pdf/2003.01575) [J]. arXiv preprint arXiv:2003.01575.
- Sixu Hu, Yuan Li, Xu Liu, Qinbin Li, Zhaomin Wu, Bingsheng He .[The OARF Benchmark Suite: Characterization and Implications for Federated Learning Systems](https://arxiv.org/pdf/2006.07856) [J]. arXiv preprint arXiv:2006.07856.[code](https://github.com/Xtra-Computing/OARF)
- Weiming Zhuang, Yonggang Wen, Xuesen Zhang, Xin Gan, Daiying Yin, Dongzhan Zhou, Shuai Zhang, Shuai Yi .[Performance Optimization for Federated Person Re-identification via Benchmark Analysis](https://arxiv.org/pdf/2008.11560) [J]. arXiv preprint arXiv:2008.11560. <br> [code:[cap-ntu/FedReID](https://github.com/cap-ntu/FedReID)]
- [SMILELab-FL/FedLab-benchmarks](https://github.com/SMILELab-FL/FedLab-benchmarks)
- [Federated Learning on Non-IID Data Silos: An Experimental Study](https://arxiv.org/abs/2102.02079);<br>[code](https://github.com/Xtra-Computing/NIID-Bench)
- [FedGraphNN: A Federated Learning System and Benchmark for Graph Neural Networks](https://arxiv.org/abs/2104.07145);<br>[code](https://github.com/FedML-AI/FedGraphNN)



## Scholars
- [Yang Qiang](https://scholar.google.com/citations?hl=en&user=1LxWZLQAAAAJ)
- [H. Brendan McMahan](https://scholar.google.com/citations?user=iKPWydkAAAAJ&hl=en)
- [jakub konečný](https://scholar.google.com/citations?user=4vq7eXQAAAAJ&hl=en)
- [H. Vincent Poor](https://ee.princeton.edu/people/h-vincent-poor)
- [Hao Ye](https://scholar.google.ca/citations?user=ok7OWEAAAAAJ&hl=en)
- [Ye Li](http://liye.ece.gatech.edu/)



## Conferences and Workshops
- [FL-ICML 2020](http://federated-learning.org/fl-icml-2020/) - Organized by IBM Watson Research.
- [FL-IBM 2020](https://federated-learning.bitbucket.io/ibm2020/) - Organized by IBM Watson Research and Webank.
- [FL-NeurIPS 2019](http://federated-learning.org/fl-neurips-2019/) - Organized by Google, Webank, NTU, CMU.
- [FL-IJCAI 2019](https://www.ijcai19.org/workshops.html) - Organized by Webank.
- [Google Federated Learning workshop](https://sites.google.com/view/federated-learning-2019/home) - Organized by Google.


## Company
- [Adap](https://adap.com/en)
- [Snips](https://snips.ai/); [Snips](https://www.theverge.com/2019/11/21/20975607/sonos-buys-snips-ai-voice-assistant-privacy)
- [Privacy.ai](https://privacy.ai/)
- [OpenMined](https://www.openmined.org/)
- [Arkhn](https://arkhn.org/en/)
- [Scaleout](https://scaleoutsystems.com/)
- [MELLODDY](https://www.melloddy.eu/)
- [DataFleets](https://www.datafleets.com/)
- [baidu PaddleFL](https://github.com/PaddlePaddle/PaddleFL)
- [Owkin](https://owkin.com/): Medical research
- [XAIN](https://www.xain.io/) [[Github]](https://github.com/xainag/xain-fl): Automated Invoicing
- [S20](https://www.s20.ai/): Multiple third party collaboration
- [google TensorFlow](https://github.com/tensorflow/federated)
- [bytedance](https://github.com/bytedance/fedlearner)
- [JD](https://github.com/jd-9n/9nfl)
- [平安蜂巢](.)
- [nvidia clare](https://developer.nvidia.com/clara) 
- [huawei NAIE](https://console.huaweicloud.com/naie/)
- [冰鉴](.)
- [数犊科技](https://www.sudoprivacy.com/)
- [同态科技-迷雾计算](https://www.ttaicloud.com/)
- [TalkingData](https://sdmk.talkingdata.com/#/home/datasecurity)
- [融数联智](https://www.udai.link/)
- [算数力科技-CompuTa](https://www.computa.com/)
- [摩联科技](https://www.aitos.io/index/index/index.html)
- [ARPA-ARPA隐私计算协议](https://arpachain.io/)
- [趣链科技-BitXMesh可信数据网络](https://bitxmesh.com/)

### 联邦学习工具基础能力测评
| 公司 | 产品 |认证|通过时间|
| :-----:| :----: |:---:|:---:|
|同盾控股有限公司 |[同盾智邦知识联邦平台](https://www.tongdun.cn/ai/solution/aiknowledge)|信通院认证|2020.12|
|腾讯云计算(北京)有限责任公司| 腾讯神盾Angel PowerFL联邦计算平台|信通院认证|2020.12|
|翼健（上海）信息科技有限公司| [翼数坊XDP隐私安全计算平台](https://www.basebit.me/)|信通院认证|2020.12|
|京东云计算有限公司| 京东智联云联邦学习平台|信通院认证|2020.12|
|京东数科海益信息科技有限公司| [联邦模盒](https://www.jddglobal.com/products/union-learn)|信通院认证|2020.12|
|杭州锘崴信息科技有限公司| [锘崴信联邦学习平台](https://www.nvxclouds.com/)|信通院认证|2020.12|
|[深圳前海新心数字科技有限公司](https://www.xinxindigits.com/about/services)| 新心数述联邦学习平台|信通院认证|2020.12|
|深圳前海微众银行股份有限公司| [联邦学习云服务平台](https://cn.fedai.org/)|信通院认证|2020.12|
|上海富数科技有限公司| [阿凡达安全计算平台](https://www.fudata.cn/federated-machine-learning)|信通院认证|2020.12|
|天翼电子商务有限公司| CTFL天翼联邦学习平台|信通院认证|2020.12|
|中国电信股份有限公司云计算分公司| 天翼云诸葛AI-联邦学习平台|信通院认证|2020.12|
|厦门渊亭信息科技有限公司| [DataExa-Insight人工智能中台系统](http://www.dataexa.com/product/insight)|信通院认证|2020.12|
|光之树（北京）科技有限公司| [云间联邦学习平台](https://www.guangzhishu.com/)|信通院认证|2020.12|
|神谱科技（上海）有限公司| [神谱科技Seceum联邦学习系统](http://www.seceum.com/home.html)|信通院认证|2020.12|
|深圳市洞见智慧科技有限公司| [洞见数智联邦平台（INSIGHTONE）](https://www.insightone.cn/)|信通院认证|2020.12|
|[星环信息科技（上海）有限公司](https://www.transwarp.io/transwarp/index.html)| 星环联邦学习软件|信通院认证|2020.12|
|华控清交信息科技（北京）有限公司| [清交PrivPy多方计算平台](https://www.tsingj.com/)|信通院认证|2020.12|
|腾讯云计算（北京）有限责任公司 |腾讯云联邦学习应用平台软件|信通院认证|2020.12|
|浙江天猫技术有限公司|DataTrust阿里云隐私增强计算软件|信通院认证|2021.6|
|北京火山引擎科技有限公司|火山引擎隐私计算平台|信通院认证|2021.6|
|深圳致星科技有限公司(星云Clustar)|星云隐私计算平台|信通院认证|2021.6|
|云从科技集团股份有限公司|云从隐私计算平台|信通院认证|2021.6|
|北京瑞莱智慧科技有限公司|隐私保护机器学习平台RealSecure|信通院认证|2021.6|
|北京九章云极科技有限公司|DataCanvas FL联邦学习平台|信通院认证|2021.6|
|天冕信息技术(深圳)有限公司|天冕联邦学习平台|信通院认证|2021.6|
|华为云计算技术有限公司|可行智能计算服务TICS|信通院认证|2021.6|
|度小满科技(北京)有限公司|貔貅隐私计算平台|信通院认证|2021.6|
|北京神州泰岳智能数据技术有限公司|数联盈|信通院认证|2021.6|
|中移系统集成有限公司(雄安产业研究院)|中移联邦计算服务平台|信通院认证|2021.6|
|阿里云计算有限公司|阿里云机器学习PAI|信通院认证|2021.6|
|医渡云(北京)技术有限公司|多方安全计算平台(YIDUMANDA)|信通院认证|2021.6|
|联易融数字科技集团有限公司|蜂隐联邦学习平台|信通院认证|2021.6|
|百融云创科技股份有限公司|百融INDRA-隐私计算平台|信通院认证|2021.12|
|亚信科技(中国)有限公司|亚信科技联邦学习平台AISWare AI FL|信通院认证|2021.12|
|北京三快在线科技有限公司|美团联邦学习平台|信通院认证|2021.12|
|联通(广东)产业互联网有限公司|密算魔方|信通院认证|2021.12|
|福州数据技术研究院有限公司|SOLAR数据共享平台|信通院认证|2021.12|
|信也科技|信也联邦学习平台|信通院认证|2021.12|
|中国电子科技网络信息安全有限公司|区块链联邦计算系统|信通院认证|2021.12|
|华为技术有限公司|iMaster NAIE联邦学习部署服务|信通院认证|2021.12|
|上海游昆信息技术有限公司|Mob联邦学习平台|信通院认证|2021.12|
|杭州卷积云科技有限公司|卷积云联邦学习平台|信通院认证|2021.12|
|上海零数科技有限公司|零数联邦学习平台|信通院认证|2021.12|
|科大讯飞股份有限公司|图聆·抱朴联邦学习平台|信通院认证|2021.12|
|中国人寿财产保险股份有限公司|天元数创平台|信通院认证|2021.12|
|杭州比智科技有限公司|奇点云联邦学习系统|信通院认证|2021.12|
|上海浦东发展银行股份有限公司|波塞冬联邦学习平台|信通院认证|2021.12|
|北京冲量在线科技有限公司|冲量数据互联平台|信通院认证|2021.12|
|续科天下(北京)科技有限公司|与日数据隐私数据连接平台yConnect|信通院认证|2021.12|
|第四范式(北京)技术有限公司|云知隐私计算平台|信通院认证|2021.12|
|南京三眼精灵信息科技有限公司|智力共享平台·知脑|信通院认证|2021.12|
|招商银行|慧点隐私计算平台|信通院认证|2021.12|
|建信金融科技有限责任公司|数据安全计算平台|信通院认证|2021.12|
|北京百度网讯科技有限公司|点石联邦学习平台|信通院认证|2021.12|
|北京融数联智科技有限公司|善数隐私计算平台|信通院认证|2022.06|
|重庆大司空信息科技有限公司|建筑大数据平台|信通院认证|2022.06|
|杭州趣链科技有限公司|趣链联邦学习软件|信通院认证|2022.06|
|神州融安数字科技(北京)有限公司|融安隐私计算平台|信通院认证|2022.06|
|神州融安科技(北京)有限公司|融安隐私计算平台|信通院认证|2022.06|
|随行付支付有限公司|结行联邦学习平台|信通院认证|2022.06|
|北京数牍科技有限公司|Tusita隐私计算平台|信通院认证|2022.06|
|杭州半云科技有限公司|半云隐私计算平台|信通院认证|2022.06|
|北京八分量信息科技有限公司|八分量隐私计算平台|信通院认证|2022.06|
|国网智能电网研究院有限公司|"智数"电力隐私计算平台|信通院认证|2022.06|
|北京众尖同屏数字科技有限公司|吉利数科联邦学习平台|信通院认证|2022.06|
|银联商务股份有限公司|银联商务隐私计算平台|信通院认证|2022.06|
|蚂蚁区块链科技(上海)有限公司|蚂蚁链摩斯安全计算平台|信通院认证|2022.06|
|国广清科(北京)科技有限公司|青稞隐私计算平台|信通院认证|2022.06|


``` [腾讯fele](https://cloud.tencent.com/product/fele)```

### 联邦学习性能专项评测
| 公司 | 产品 |认证|通过时间|
| :-----:| :----: |:---:|:---:|
|华控清交信息科技(北京)有限公司|清交PrivPy多方计算平台|信通院认证|2021.06|
|浙江天猫技术有限公司|DataTrust阿里云隐私增强计算软件|信通院认证|2021.06|
|上海富数科技有限公司|阿凡达安全计算平台|信通院认证|2021.06|
|深圳市洞见智慧科技有限公司|洞见数智联邦平台(INSIGHTONE)|信通院认证|2021.06|
|腾讯云(北京)有限责任公司|腾讯神盾Angel PowerFL隐私计算平台|信通院认证|2021.06|
|上海光之树科技有限公司|隐私计算平台|信通院认证|2021.12|
|京东城市(北京)数字科技有限公司|联邦数字网关系统|信通院认证|2021.12|
|京东科技控股股份有限公司|京东万象隐私计算开放平台|信通院认证|2021.12|
|杭州锘崴信息科技有限公司|锘崴信联邦学习平台|信通院认证|2022.06|
|翼健(上海)信息科技有限公司|翼数坊XDP隐私安全计算平台|信通院认证|2022.06|
|神州融安数字科技(北京)有限公司|融安隐私计算平台|信通院认证|2022.06|
|上海浦东发展银行股份有限公司|波塞冬联邦学习产品|信通院认证|2022.06|
|中国人寿财产保险股份有限公司|天元数创平台|信通院认证|2022.06|
|深圳致星科技有限公司|星云隐私计算平台|信通院认证|2022.06|
|国网智能电网研究院有限公司|"智数"电力隐私计算平台|信通院认证|2022.06|


### 联邦学习性能大规模专项评测
| 公司 | 产品 |认证|通过时间|
| :-----:| :----: |:---:|:---:|
|北京数牍科技有限公司|Tusita隐私计算平台|信通院认证|2022.06|
|北京百度网讯科技有限公司|百度点石联邦学习平台|信通院认证|2022.06|
|蚂蚁区块链科技(上海)有限公司|蚂蚁链模式安全计算平台|信通院认证|2022.06|


### 联邦学习安全专项评测
| 公司 | 产品 |认证|通过时间|
| :-----:| :----: |:---:|:---:|
|深圳市洞见智慧科技有限公司|洞见数智联邦平台(INSIGHTONE)|信通院认证|2021.12|
|蚂蚁金服(杭州)网络技术有限公司|蚂蚁隐私计算隐语平台|信通院认证|2021.12|
|北京蚂蚁云金融信息服务有限公司|蚂蚁隐私计算隐语平台(和上面是同一个)|信通院认证|2021.12|
|北京火山引擎科技有限公司|火山引擎Jcddak联邦学习平台|信通院认证|2021.12|
|蓝象智联(杭州)科技有限公司|GAIA隐私计算平台|信通院认证|2021.12|
|腾讯云计算(北京)有限责任公司|腾讯云联邦学习应用平台ANgel PowerFL|信通院认证|2021.12|
|上海富数科技有限公司|阿凡达安全计算平台|信通院认证|2021.12|
|杭州锘崴信息科技有限公司|锘崴信联邦学习平台|信通院认证|2022.06|
神州融安数字科技(北京)有限公司|融安隐私计算平台||信通院认证|2022.06|
|北京三快在线科技有限公司|美团隐私计算平台|信通院认证|2022.06|
|上海浦东发展银行股份有限公司|波塞冬联邦学习产品|信通院认证|2022.06|
|国网智能电网研究院有限公司|"智数"电力隐私计算平台|信通院认证|2022.06|
|北京百度网讯科技有限公司|百度点石联邦学习平台|信通院认证|2022.06|
|北京瑞莱智慧科技有限公司|RealSecure隐私保护机器学习平台[简称RSC]|信通院认证|2022.06|


### 多方安全计算工具基础能力评测
| 公司 | 产品 |认证|通过时间|
| :-----:| :----: |:---:|:----:|
|蚂蚁区块链科技(上海)有限公司| [蚂蚁链摩斯安全计算平台（MORSE）](https://antchain.antgroup.com/products/morse)|信通院认证|2019.12|
|腾讯云计算(北京)有限责任公司| 腾讯神盾Angel PowerFL联邦计算平台|信通院认证|2019.12|
|华控清交信息科技(北京)有限公司|华控清交多方安全计算平台|信通院认证|2019.12|
|北京百度网讯科技有限公司|百度点石|信通院认证|2019.12|
|上海富数科技有限公司| [阿凡达安全计算平台](https://www.fudata.cn/federated-machine-learning)|信通院认证|2019.12|
|杭州趣链科技有限公司|趣链联邦计算软件|信通院认证|2020.06|
|北京数牍科技有限公司|Tusita多方安全隐私计算平台|信通院认证|2020.06|
|同盾科技有限公司|同盾智邦学习平台|信通院认证|2020.06|
|厦门渊亭信息科技有限公司|DataExa-Insight人工智能中台|信通院认证|2020.06|
|深圳市洞见智慧科技有限公司|洞见安全多方数据智能平台|信通院认证|2020.06|
|蚂蚁智信(杭州)信息计算有限公司|共享智能平台|信通院认证|2020.06|
|北京百度网讯科技有限公司|联邦计算平台|信通院认证|2020.06|
|北京百度网讯科技有限公司|百度智能云度信金融安全计算平台|信通院认证|2020.06|
|天翼电子商务有限公司|密流安全计算平台|信通院认证|2020.06|
|北京融数联智科技有限公司|UPAI安全计算平台|信通院认证|2020.06|
|蓝象智联(杭州)科技有限公司|GAIA·Edge|信通院认证|2020.12|
|腾讯云计算(北京)有限责任公司|腾讯神盾Angel PowerFL联邦计算平台|信通院认证|2020.12|
|深圳前海微众银行股份有限公司|联邦学习云服务平台|信通院认证|2020.12|
|上海富数科技有限公司|阿凡达安全计算平台|信通院认证|2020.12|
|矩阵元技术(深圳)有限公司|矩阵元隐私计算服务系统|信通院认证|2020.12|
|蚂蚁区块链科技(上海)有限公司|蚂蚁链摩斯安全计算平台(MORSE)|信通院认证|2020.12|
|浙江天猫技术有限公司|DataTrust阿里云隐私增强计算软件|信通院认证|2021.6|
|上海凯馨信息科技有限公司|凯馨多方安全计算平台|信通院认证|2021.6|
|深圳市云计算科技有限公司|ELF隐私计算服务平台|信通院认证|2021.6|
|杭州金智塔科技有限公司|金智塔隐私计算平台|信通院认证|2021.6|
|南京三眼精灵信息技术有限公司|智力共享平台·数链|信通院认证|2021.6|
|北京瑞莱智慧科技有限公司|隐私保护机器学习平台RealSecure|信通院认证|2021.6|
|联易融数字科技集团有限公司|蜂密隐私计算平台|信通院认证|2021.6|
|医渡云(北京)技术有限公司|多方安全计算平台(YIDUMANDA)|信通院认证|2021.6|
|深圳市洞见智慧科技有限公司|洞见数智联邦平台(INSIGHTONE)|信通院认证|2021.6|
|苏州同济区块链研究院有限公司|梧桐隐私计算平台WPC|信通院认证|2021.6|
|第四范式(北京)技术有限公司|云知隐私计算平台|信通院认证|2021.12|
|上海光之树科技有限公司|隐私计算平台|信通院认证|2021.12|
|中移(苏州)软件技术有限公司|多方安全计算平台|信通院认证|2021.12|
|三未信安科技股份有限公司|多方安全计算数据安全平台|信通院认证|2021.12|
|中投国信(北京)科技发展有限公司|多方安全计算平台|信通院认证|2021.12|
|海智讯通(上海)智能科技有限公司|爱前台电商多方安全计算系统|信通院认证|2021.12|
|招商银行|慧点隐私计算平台|信通院认证|2021.12|
|京东科技控股股份有限公司|京东万象隐私计算开放平台|信通院认证|2021.12|
|翼健(上海)信息科技有限公司|翼数坊XDP隐私安全计算平台|信通院认证|2021.12|
|优刻得科技股份有限公司|安全屋安全多方计算产品|信通院认证|2021.12|
|神州融安数字科技(北京)有限公司|融安隐私计算平台|信通院认证|2022.06|
|神州融安科技(北京)有限公司|融安隐私计算平台|信通院认证|2022.06|
|北京数牍科技有限公司|Tusita隐私计算平台|信通院认证|2022.06|
|北京三快在线科技有限公司|美团隐私计算平台|信通院认证|2022.06|
|中国人寿财产保险股份有限公司|天元数创平台|信通院认证|2022.06|
|杭州煋辰数智科技有限公司|"星际"安全多方联合计算平台|信通院认证|2022.06|
|亚信科技(中国)有限公司|亚信隐私计算平台AISWare MPC|信通院认证|2022.06|
|联通数字科技有限公司|联通链隐私计算平台|信通院认证|2022.06|
|蚂蚁区块链科技(上海)有限公司|蚂蚁链摩斯安全计算平台|信通院认证|2022.06|
|杭州萝卜智能技术有限公司|数密院隐私计算平台[简称Data phi]|信通院认证|2022.06|
|国广清科(北京)科技有限公司|青稞隐私计算平台|信通院认证|2022.06|



### 多方安全计算性能专项评测
| 公司 | 产品 |认证|通过时间|
| :-----:| :----: |:---:|:---:|
|华控清交信息科技(北京)有限公司|清交PrivPy多方计算平台|信通院认证|2021.06|
|上海富数科技有限公司|阿凡达安全计算平台|信通院认证|2021.06|
|深圳市洞见智慧科技有限公司|洞见数智联邦平台|信通院认证|2021.06|
|腾讯云(北京)有限责任公司|腾讯神盾Angel PowerFL 隐私计算平台|信通院认证|2021.06|
|杭州趣链科技有限公司|趣链联邦计算软件|信通院认证|2021.06|
|杭州金智塔科技有限公司|金智塔隐私计算平台|信通院认证|2021.12|
|浙江天猫技术有限公司|DataTrust阿里云隐私增强计算软件|信通院认证|2021.12|
|翼健(上海)信息科技有限公司|翼数坊XDP隐私安全计算平台|信通院认证|2022.06|
|中国人寿财产保险股份有限公司|天元数创平台|信通院认证|2022.06|

### 多方安全计算性能大规模专项评测
| 公司 | 产品 |认证|通过时间|
| :-----:| :----: |:---:|:---:|
|神州融安数字科技(北京)有限公司|融安隐私计算平台|信通院认证|2022.06|
|北京数牍科技有限公司|Tusita隐私计算平台|信通院认证|2022.06|
|蚂蚁区块链科技(上海)有限公司|蚂蚁链摩斯安全计算平台|信通院认证|2022.06|

### 多方安全计算安全专项评测
| 公司 | 产品 |认证|通过时间|
| :-----:| :----: |:---:|:---:|
|矩阵元技术(深圳)有限公司|JUGO隐私计算平台|信通院认证|2021.12|
|深圳市洞见智慧科技有限公司|洞见数智联邦平台(INSIGHTONE)|信通院认证|2021.12|
|蚂蚁金服(杭州)网络技术有限公司|蚂蚁隐私计算隐语平台|信通院认证|2021.12|
|北京蚂蚁云金融信息服务有限公司|蚂蚁隐私计算隐语平台(也是隐语)|信通院认证|2021.12|
|杭州金智塔科技有限公司|金智塔隐私计算平台|信通院认证|2022.06|
|神州融安数字科技(北京)有限公司|融安隐私计算平台|信通院认证|2022.06|
|北京瑞莱智慧科技有限公司|RealSecure隐私保护机器学习平台[简称RSC]|信通院认证|2022.06|
|北京百度网讯科技有限公司|百度点石联邦学习平台|信通院认证|2022.06|


### 可信执行环境计算平台基础能力评测
| 公司 | 产品 |认证|通过时间|
| :-----:| :----: |:---:|:---:|
|北京冲量在线科技有限公司| [冲量数据互联平台](http://www.impulse.top/)|信通院认证|2020.12|
|翼健（上海）信息科技有限公司| [翼数坊XDP隐私安全计算平台](https://www.basebit.me/)|信通院认证|2020.12|
|上海隔镜信息科技有限公司| [天禄多方安全计算平台](https://www.trustmirror.com/product/index.html)|信通院认证|2020.12|
|杭州锘崴信息科技有限公司| [锘崴信联邦学习平台](https://www.nvxclouds.com/)|信通院认证|2020.12|
|蚂蚁智信（杭州）信息技术有限公司| [共享智能平台](https://blockchain.antgroup.com/solutions/tdsp)|信通院认证|2020.12|
|华为技术有限公司| [可信智能计算服务TICS](https://www.huaweicloud.com/product/tics.html)|信通院认证|2020.12|
|蚂蚁区块链科技（上海）有限公司|  [蚂蚁链数据隐私服务](https://blockchain.antgroup.com/products/openchain)|信通院认证|2020.12|
|浙江天猫技术有限公司|DataTrust阿里云隐私增强计算软件|信通院认证|2021.06|
|北京百度网讯科技有限公司|点石安全计算平台(MesaTEE)|信通院认证|2021.06|
|零幺宇宙(上海)科技有限公司|光笺可信执行环境|信通院认证|2021.06|
|天翼电子商务有限公司|PrivTorrent密流安全计算平台|信通院认证|2021.06|
|西安纸贵互联网科技有限公司|纸数魔方-基于区块链的可信执行环境数据计算平台|信通院认证|2021.06|
|光之树(杭州)科技有限公司|天机可信计算平台|信通院认证|2021.06|
|北京熠智科技有限公司|典枢数据合作平台|信通院认证|2021.12|
|第四范式(北京)技术有限公司|云知隐私计算平台|信通院认证|2021.12|
|中国电子系统技术有限公司|CECloud数据安全沙箱系统|信通院认证|2021.12|
|京东科技控股股份有限公司|京东万象隐私计算平台|信通院认证|2022.06|
|中国电信股份有限公司北京分公司|AI智算平台|信通院认证|2022.06|
|杭州安恒信息技术股份有限公司|安全岛数据共享访问控制系统|信通院认证|2022.06|
|武汉天喻信息产业股份有限公司|BluePPC-T|信通院认证|2022.06|


### 区块链辅助隐私计算基础能力评测
| 公司 | 产品 |认证|通过时间|
| :-----:| :----: |:---:|:---:|
|北京冲量在线科技有限公司|冲量数据互联平台|信通院认证|2021.06|
|天翼电子商务有限公司|大禹-天翼数据融通平台|信通院认证|2021.06|
|深圳前海微众银行股份有限公司|多方大数据隐私计算平台WeDPR-PPC|信通院认证|2021.06|
|汉州安恒信息技术股份有限公司|安全岛数据共享访问控制系统DAS-SMPC|信通院认证|2021.06|
|杭州趣链科技有限公司|趣链联邦计算软件|信通院认证|2021.06|
|联易融数字科技集团有限公司|蜂密隐私计算平台|信通院认证|2021.06|
|深圳市洞见智慧科技有限公司|洞见数智联邦平台(INSIGHTONE)|信通院认证|2021.06|
|京东数科海益信息科技有限公司|万象隐私计算平台|信通院认证|2021.06|
|京信数据科技有限公司|京信数据安全可信计算平台|信通院认证|2021.12|
|杭州医康慧莲科技股份有限公司|Arya隐私计算平台|信通院认证|2021.12|
|西安纸贵互联网科技有限公司|纸数魔方-区块链辅助的隐式计算平台|信通院认证|2021.12|
|奇安信科技集团股份有限公司|奇安信网神数据交易沙箱系统|信通院认证|2021.12|
|上海光之树科技有限公司|隐私计算平台|信通院认证|2021.12|
|深圳壹账通智能科技有限公司|加马区块链隐私计算协作平台|信通院认证|2021.12|
|北京融数联智科技有限公司|善数隐私计算平台|信通院认证|2022.06|
|北京国双科技有限公司|国双联邦计算系统|信通院认证|2022.06|

### 隐私计算金融场景专项评测
| 公司 | 产品 |认证|通过时间|
| :-----:| :----: |:---:|:---:|
|北京百度网讯科技有限公司|百度点石联邦学习平台|信通院认证|2022.06|
|北京冲量在线科技有限公司|冲量数据互联平台|信通院认证|2022.06|
|深圳市洞见智慧科技有限公司|洞见数智联邦平台(INSIGHTONE)|信通院认证|2022.06|


## 参考来源

- [第一至四批通过产品详情（中国信通院“可信隐私计算”产品测评体系升级上线）](https://mp.weixin.qq.com/s?__biz=MzkwNjE4ODkxNg==&mid=2247485137&idx=1&sn=6b30fb7e35f45e5eac53dd773d665dbc&scene=21#wechat_redirect)
- [第五批通过产品详情（中国信通院公布第五批可信隐私计算评测结果）](https://mp.weixin.qq.com/s?__biz=MzkwNjE4ODkxNg==&mid=2247485137&idx=1&sn=6b30fb7e35f45e5eac53dd773d665dbc&scene=21#wechat_redirect)
- [中国信通院公布第六批可信隐私计算评测结果](https://mp.weixin.qq.com/s/0Jv0nhBedWXFSBceRstxdw)

