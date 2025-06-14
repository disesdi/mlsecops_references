# MLSecOps Reference Repository

*A curated repo for papers, books, & other media on machine learning operations (MLOps), adversarial machine learning, AIML policy and compliance, & more.*

*Read my work on AI Security:*

> **[Securing AIML Systems in the Age of Information Warfare](https://zenodo.org/records/13905972)**
> 
> A novel AI/machine learning security operations (AI/MLSecOps) architecture, including systems for operationalized security, auditing, data threat, and information warfare detection, along with OODA Loop-based game theoretic modeling of information warfare in AI/ML systems, and boolean path threat modeling & cyber resiliency metrics adapted to the canonical MLOps development cycle.
>
>  **[AI-DAL: Towards Security Design Assurance for Artificial Intelligence Systems in Production](https://zenodo.org/records/13905960)**
>
> The rise of artificial intelligence applications in society, and their accompanying security concerns, has created a need for regulatory oversight that is auditable, actionable, and adaptable to a rapidly changing technological landscape. Methods from safety-critical software engineering, particularly aerospace, are adapted to use in production AIML to aid both practitioners and regulators in establishing design thresholds for AIML system security. Assignment of AI Design Assurance Levels (AI-DAL) to projects/components, along with production of related compliance artifacts, is proposed as a means of consistently applying appropriate design requirements based on a system’s potential adverse impact.

## Contents:

* [AIML Security Surveys & Taxonomies](README.md#aiml-security-surveys--taxonomies)
* [Adversarial AIML Attacks](README.md#adversarial-aiml-attacks)
     * [Adversarial AIML Overview](README.md#adversarial-aiml-overview)
     * [Data Poisoning Attacks](README.md#data-poisoning-attacks)
     * [Membership Inference Attacks](README.md#membership-inference-attacks)
     * [Differential Privacy Attacks](README.md#differential-privacy-attacks)
* [AIML Security for Cyber-Physical Systems & IoT](README.md#aiml-security-for-cyber-physical-systems--iot)
* [AIML Cloud Security](README.md#aiml-cloud-security)
* [AIML Intrusion & Malware Detection Systems](README.md#aiml-intrusion--malware-detection-systems)
* [Federation](README.md#federation)
* [MLOps](README.md#mlops)
    * [MLOps Overview](README.md#mlops-overview)
    * [MLOps, SecOps and Failure Modes & Effects Analysis (FMEA)](README.md#mlops-secops-and-failure-modes--effects-analysis-fmea)
    * [MLOps Supply Chain & Data](README.md#mlops-supply-chain--data)
    * [MLOps for Edge & IoT](README.md#mlops-for-edge--iot)
    * [MLOps Policy & Compliance](README.md#mlops-policy--compliance)
* [Threat Modeling & Secure Design](README.md#threat-modeling--secure-design)
* [Datasets](README.md#datasets)
* [LLM Security](README.md#llm-security)
* [Agentic AI](README.md#agentic-ai)


## AIML Security Surveys & Taxonomies

Barreno, Marco, Blaine Nelson, Anthony D. Joseph and J. Doug Tygar. “The security of machine learning.” Machine Learning 81 (2010): 121-148.

Brundage, Miles, Shahar Avin, Jack Clark, Helen Toner, Peter Eckersley, Ben Garfinkel, Allan Dafoe, Paul Scharre, Thomas Zeitzoff, Bobby Filar, H. Anderson, Heather Roff, Gregory C. Allen, Jacob Steinhardt, Carrick Flynn, Seán Ó hÉigeartaigh, Simon Beard, Haydn Belfield, Sebastian Farquhar, Clare Lyle, Rebecca Crootof, Owain Evans, Michael Page, Joanna J. Bryson, Roman V. Yampolskiy and Dario Amodei. “The Malicious Use of Artificial Intelligence: Forecasting, Prevention, and Mitigation.” ArXiv abs/1802.07228 (2018): n. pag.

Kaloudi, Nektaria and Jingyue Li. “The AI-Based Cyber Threat Landscape.” ACM Computing Surveys (CSUR) 53 (2020): 1 - 34.

Bae, Ho, Jaehee Jang, Dahuin Jung, Hyemi Jang, Heonseok Ha and Sungroh Yoon. “Security and Privacy Issues in Deep Learning.” ArXiv abs/1807.11655 (2018): n. pag.

Chen, Huaming and M Ali Babar. “Security for Machine Learning-based Software Systems: a survey of threats, practices and challenges.” ArXiv abs/2201.04736 (2022): n. pag.

Liu, Ximeng, Lehui Xie, Yaopeng Wang, Jian Zou, Jinbo Xiong, Zuobin Ying and Athanasios V. Vasilakos. “Privacy and Security Issues in Deep Learning: A Survey.” IEEE Access 9 (2021): 4566-4593.

Muñoz-González, Luis and Emil C. Lupu. “The Security of Machine Learning Systems.” AI in Cybersecurity (2018): n. pag.

Singh, Shivani, Razia Sulthana, Tanvi Shewale, Vinay Chamola, Abderrahim Benslimane and Biplab Kumar Sikdar. “Machine-Learning-Assisted Security and Privacy Provisioning for Edge Computing: A Survey.” IEEE Internet of Things Journal 9 (2022): 236-260.

Rosenberg, Ishai, Asaf Shabtai, Yuval Elovici and Lior Rokach. “Adversarial Machine Learning Attacks and Defense Methods in the Cyber Security Domain.” ACM Computing Surveys (CSUR) 54 (2021): 1 - 36.

Qiu, Shilin, Qihe Liu, Shijie Zhou and Chunjiang Wu. “Review of Artificial Intelligence Adversarial Attack and Defense Technologies.” Applied Sciences (2019): n. pag.

Masys, Anthony, Mamoun Alazab and Mingjian Tang. “Deep Learning Applications for Cyber Security.” Deep Learning Applications for Cyber Security (2019): n. pag.

Wang, Xianmin, Jing Li, Xiaohui Kuang, Yu‐an Tan and Jin Li. “The security of machine learning in an adversarial setting: A survey.” J. Parallel Distributed Comput. 130 (2019): 12-23.

Salloum, Said A., Muhammad Turki Alshurideh, Ashraf Elnagar and Khaled F. Shaalan. “Machine Learning and Deep Learning Techniques for Cybersecurity: A Review.” International Conferences on Artificial Intelligence and Computer Vision (2020).

Li, Jian-hua. “Cyber security meets artificial intelligence: a survey.” Frontiers of Information Technology & Electronic Engineering 19 (2018): 1462-1474.

Xin, Yang, Lingshuang Kong, Zhi Liu, Yuling Chen, Yanmiao Li, Hongliang Zhu, Mingcheng Gao, Haixia Hou and Chunhua Wang. “Machine Learning and Deep Learning Methods for Cybersecurity.” IEEE Access 6 (2018): 35365-35381.

Rodríguez, Eva, Beatriz Otero, Norma Gutiérrez and Ramon Canal. “A Survey of Deep Learning Techniques for Cybersecurity in Mobile Networks.” IEEE Communications Surveys & Tutorials 23 (2021): 1920-1955.

Mahdavifar, Samaneh and Ali A. Ghorbani. “Application of deep learning to cybersecurity: A survey.” Neurocomputing 347 (2019): 149-176.

Dixit, Priyanka and Sanjay Silakari. “Deep Learning Algorithms for Cybersecurity Applications: A Technological and Status Review.” Comput. Sci. Rev. 39 (2021): 100317.

Liu, Qiang, Pan Li, Wentao Zhao, Wei Cai, Shui Yu and Victor C. M. Leung. “A Survey on Security Threats and Defensive Techniques of Machine Learning: A Data Driven View.” IEEE Access 6 (2018): 12103-12117.

Kong, Zixiao, Jingfeng Xue, Yong Wang, Lu Huang, Zequn Niu and Feng Li. “A Survey on Adversarial Attack in the Age of Artificial Intelligence.” Wirel. Commun. Mob. Comput. 2021 (2021): 4907754:1-4907754:22.

Chakraborty, Anirban, Manaar Alam, Vishal Dey, Anupam Chattopadhyay and Debdeep Mukhopadhyay. “Adversarial Attacks and Defences: A Survey.” ArXiv abs/1810.00069 (2018): n. pag.

Raji, Inioluwa Deborah, Andrew Smart, Rebecca N. White, Margaret Mitchell, Timnit Gebru, Ben Hutchinson, Jamila Smith-Loud, Daniel Theron and Parker Barnes. “Closing the AI accountability gap: defining an end-to-end framework for internal algorithmic auditing.” Proceedings of the 2020 Conference on Fairness, Accountability, and Transparency (2020): n. pag.

[top](README.md#mlsecops-reference-repository)

## Adversarial AIML Attacks

### Adversarial AIML Overview

Kurakin, Alexey, Ian J. Goodfellow and Samy Bengio. “Adversarial Machine Learning at Scale.” ArXiv abs/1611.01236 (2016): n. pag.

Narodytska, Nina and Shiva Prasad Kasiviswanathan. “Simple Black-Box Adversarial Attacks on Deep Neural Networks.” 2017 IEEE Conference on Computer Vision and Pattern Recognition Workshops (CVPRW) (2017): 1310-1318.

Oseni, Ayodeji, Nour Moustafa, Helge Janicke, Peng Liu, Zahir Tari and Athanasios V. Vasilakos. “Security and Privacy for Artificial Intelligence: Opportunities and Challenges.” ArXiv abs/2102.04661 (2021): n. pag.

Clements, Joseph, Yuzhe Yang, Ankur A Sharma, Hongxin Hu and Yingjie Lao. “Rallying Adversarial Techniques against Deep Learning for Network Security.” 2021 IEEE Symposium Series on Computational Intelligence (SSCI) (2019): 01-08.

Biggio, Battista and Fabio Roli. “Wild Patterns: Ten Years After the Rise of Adversarial Machine Learning.” Proceedings of the 2018 ACM SIGSAC Conference on Computer and Communications Security (2017): n. pag.

Kuppa, Aditya, Slawomir Grzonkowski, Muhammad Rizwan Asghar and Nhien-An Le-Khac. “Black Box Attacks on Deep Anomaly Detectors.” Proceedings of the 14th International Conference on Availability, Reliability and Security (2019): n. pag.

Lin, Zilong, Yong-yu Shi and Zhi Xue. “IDSGAN: Generative Adversarial Networks for Attack Generation against Intrusion Detection.” Pacific-Asia Conference on Knowledge Discovery and Data Mining (2018).

Akhtar, Naveed and Ajmal S. Mian. “Threat of Adversarial Attacks on Deep Learning in Computer Vision: A Survey.” IEEE Access 6 (2018): 14410-14430.

Tramèr, Florian, Fan Zhang, Ari Juels, Michael K. Reiter and Thomas Ristenpart. “Stealing Machine Learning Models via Prediction APIs.” ArXiv abs/1609.02943 (2016): n. pag.

Wu, Baoyuan, Li Liu, Zihao Zhu, Qin Liu, Zhaofeng He and Siwei Lyu. “Attacks in Adversarial Machine Learning: A Systematic Survey from the Life-cycle Perspective.” (2023).

[top](README.md#mlsecops-reference-repository)

### Data Poisoning Attacks

Geiping, Jonas, Liam Fowl, W. Ronny Huang, Wojciech Czaja, Gavin Taylor, Michael Moeller and Tom Goldstein. “Witches' Brew: Industrial Scale Data Poisoning via Gradient Matching.” ArXiv abs/2009.02276 (2020): n. pag.

Schwarzschild, Avi, Micah Goldblum, Arjun Gupta, John P. Dickerson and Tom Goldstein. “Just How Toxic is Data Poisoning? A Unified Benchmark for Backdoor and Data Poisoning Attacks.” International Conference on Machine Learning (2020).

Lécuyer, Mathias, Vaggelis Atlidakis, Roxana Geambasu, Daniel J. Hsu and Suman Sekhar Jana. “On the Connection between Differential Privacy and Adversarial Robustness in Machine Learning.” ArXiv abs/1802.03471 (2018): n. pag.

Tramèr, Florian, R. Shokri, Ayrton San Joaquin, Hoang M. Le, Matthew Jagielski, Sanghyun Hong and Nicholas Carlini. “Truth Serum: Poisoning Machine Learning Models to Reveal Their Secrets.” Proceedings of the 2022 ACM SIGSAC Conference on Computer and Communications Security (2022): n. pag.

Steinhardt, Jacob, Pang Wei Koh and Percy Liang. “Certified Defenses for Data Poisoning Attacks.” ArXiv abs/1706.03691 (2017): n. pag.

[top](README.md#mlsecops-reference-repository)

### Membership Inference Attacks

Shokri, R., Marco Stronati, Congzheng Song and Vitaly Shmatikov. “Membership Inference Attacks Against Machine Learning Models.” 2017 IEEE Symposium on Security and Privacy (SP) (2016): 3-18.

Hu, Hongsheng, Zoran A. Salcic, Lichao Sun, Gillian Dobbie, P. Yu and Xuyun Zhang. “Membership Inference Attacks on Machine Learning: A Survey.” ACM Computing Surveys (CSUR) 54 (2021): 1 - 37.

Hu, Hongsheng, Zoran A. Salcic, Lichao Sun, Gillian Dobbie, P. Yu and Xuyun Zhang. “Membership Inference Attacks on Machine Learning: A Survey.” ACM Computing Surveys (CSUR) 54 (2021): 1 - 37.

Salem, A., Yang Zhang, Mathias Humbert, Mario Fritz and Michael Backes. “ML-Leaks: Model and Data Independent Membership Inference Attacks and Defenses on Machine Learning Models.” ArXiv abs/1806.01246 (2018): n. pag.

Carlini, Nicholas, Steve Chien, Milad Nasr, Shuang Song, A. Terzis and Florian Tramèr. “Membership Inference Attacks From First Principles.” 2022 IEEE Symposium on Security and Privacy (SP) (2021): 1897-1914.

Hilprecht, Benjamin, Martin Härterich and Daniel Bernau. “Monte Carlo and Reconstruction Membership Inference Attacks against Generative Models.” Proceedings on Privacy Enhancing Technologies 2019 (2019): 232 - 249.

Choquette-Choo, Christopher A., Florian Tramèr, Nicholas Carlini and Nicolas Papernot. “Label-Only Membership Inference Attacks.” ArXiv abs/2007.14321 (2020): n. pag.

Li, Zheng and Yang Zhang. “Membership Leakage in Label-Only Exposures.” Proceedings of the 2021 ACM SIGSAC Conference on Computer and Communications Security (2020): n. pag.

Salem, A., Apratim Bhattacharyya, Michael Backes, Mario Fritz and Yang Zhang. “Updates-Leak: Data Set Inference and Reconstruction Attacks in Online Learning.” USENIX Security Symposium (2019).

Nasr, Milad, R. Shokri and Amir Houmansadr. “Machine Learning with Membership Privacy using Adversarial Regularization.” Proceedings of the 2018 ACM SIGSAC Conference on Computer and Communications Security (2018): n. pag.

Song, Liwei and Prateek Mittal. “Systematic Evaluation of Privacy Risks of Machine Learning Models.” USENIX Security Symposium (2020).

Truex, Stacey, Ling Liu, Mehmet Emre Gursoy, Lei Yu and Wenqi Wei. “Towards Demystifying Membership Inference Attacks.” ArXiv abs/1807.09173 (2018): n. pag.

Li, Zheng and Yang Zhang. “Label-Leaks: Membership Inference Attack with Label.” ArXiv abs/2007.15528 (2020): n. pag.

Yeom, Samuel, Irene Giacomelli, Matt Fredrikson and Somesh Jha. “Privacy Risk in Machine Learning: Analyzing the Connection to Overfitting.” 2018 IEEE 31st Computer Security Foundations Symposium (CSF) (2017): 268-282.

Long, Yunhui, Vincent Bindschaedler, Lei Wang, Diyue Bu, Xiaofeng Wang, Haixu Tang, Carl A. Gunter and Kai Chen. “Understanding Membership Inferences on Well-Generalized Learning Models.” ArXiv abs/1802.04889 (2018): n. pag.

Zou, Yang, Zhikun Zhang, Michael Backes and Yang Zhang. “Privacy Analysis of Deep Learning in the Wild: Membership Inference Attacks against Transfer Learning.” ArXiv abs/2009.04872 (2020): n. pag.

Liu, Yugeng, Rui Wen, Xinlei He, A. Salem, Zhikun Zhang, Michael Backes, Emiliano De Cristofaro, Mario Fritz and Yang Zhang. “ML-Doctor: Holistic Risk Assessment of Inference Attacks Against Machine Learning Models.” USENIX Security Symposium (2021).

Rahimian, Shadi, Tribhuvanesh Orekondy and Mario Fritz. “Sampling Attacks: Amplification of Membership Inference Attacks by Repeated Queries.” ArXiv abs/2009.00395 (2020): n. pag.

He, Xinlei, Zheng Li, Weilin Xu, Cory Cornelius and Yang Zhang. “Membership-Doctor: Comprehensive Assessment of Membership Inference Against Machine Learning Models.” ArXiv abs/2208.10445 (2022): n. pag.

Wang, Chen, Gaoyang Liu, Haojun Huang, Weijie Feng, Kai Peng and Lizhe Wang. “MIASec: Enabling Data Indistinguishability Against Membership Inference Attacks in MLaaS.” IEEE Transactions on Sustainable Computing 5 (2020): 365-376.

Long, Yunhui, Lei Wang, Diyue Bu, Vincent Bindschaedler, Xiaofeng Wang, Haixu Tang, Carl A. Gunter and Kai Chen. “A Pragmatic Approach to Membership Inferences on Machine Learning Models.” 2020 IEEE European Symposium on Security and Privacy (EuroS&P) (2020): 521-534.

Tramèr, Florian, R. Shokri, Ayrton San Joaquin, Hoang M. Le, Matthew Jagielski, Sanghyun Hong and Nicholas Carlini. “Truth Serum: Poisoning Machine Learning Models to Reveal Their Secrets.” Proceedings of the 2022 ACM SIGSAC Conference on Computer and Communications Security (2022): n. pag.

Li, Jiacheng, Ninghui Li and Bruno Ribeiro. “Membership Inference Attacks and Defenses in Classification Models.” Proceedings of the Eleventh ACM Conference on Data and Application Security and Privacy (2020): n. pag.

Ye, Jiayuan, Aadyaa Maddi, Sasi Kumar Murakonda and R. Shokri. “Enhanced Membership Inference Attacks against Machine Learning Models.” Proceedings of the 2022 ACM SIGSAC Conference on Computer and Communications Security (2021): n. pag.

Farokhi, Farhad and Mohamed Ali Kâafar. “Modelling and Quantifying Membership Information Leakage in Machine Learning.” ArXiv abs/2001.10648 (2020): n. pag.

Balle, Borja, Giovanni Cherubin and Jamie Hayes. “Reconstructing Training Data with Informed Adversaries.” 2022 IEEE Symposium on Security and Privacy (SP) (2022): 1138-1156.

[top](README.md#mlsecops-reference-repository)

### Differential Privacy Attacks

Liu, Changchang, Supriyo Chakraborty and Prateek Mittal. “Dependence Makes You Vulnberable: Differential Privacy Under Dependent Tuples.” Network and Distributed System Security Symposium (2016).

Truex, Stacey, Ling Liu, Mehmet Emre Gursoy, Wenqi Wei and Lei Yu. “Effects of Differential Privacy and Data Skewness on Membership Inference Vulnerability.” 2019 First IEEE International Conference on Trust, Privacy and Security in Intelligent Systems and Applications (TPS-ISA) (2019): 82-91.

Rahman, Md.Atiqur, Tanzila Rahman, Robert Laganière and Noman Mohammed. “Membership Inference Attack against Differentially Private Deep Learning Model.” Trans. Data Priv. 11 (2018): 61-79.

Cao, Yang, Masatoshi Yoshikawa, Yonghui Xiao and Li Xiong. “Quantifying Differential Privacy under Temporal Correlations.” 2017 IEEE 33rd International Conference on Data Engineering (ICDE) (2016): 821-832.

Jin, Jiankai, Eleanor McMurtry, Benjamin I. P. Rubinstein and Olga Ohrimenko. “Are We There Yet? Timing and Floating-Point Attacks on Differential Privacy Systems.” 2022 IEEE Symposium on Security and Privacy (SP) (2021): 473-488.

Cao, Yang, Masatoshi Yoshikawa, Yonghui Xiao and Li Xiong. “Quantifying Differential Privacy in Continuous Data Release Under Temporal Correlations.” IEEE Transactions on Knowledge and Data Engineering 31 (2017): 1281-1295.

Kato, Fumiyuki, Yang Cao and Masatoshi Yoshikawa. “Preventing Manipulation Attack in Local Differential Privacy using Verifiable Randomization Mechanism.” ArXiv abs/2104.06569 (2021): n. pag.

Zhang, Bo, Ruotong Yu, Haipei Sun, Yanying Li, Jun Xu and Wendy Hui Wang. “Privacy for All: Demystify Vulnerability Disparity of Differential Privacy against Membership Inference Attack.” ArXiv abs/2001.08855 (2020): n. pag.

Zhao, Jun, Junshan Zhang and H. Vincent Poor. “Dependent Differential Privacy for Correlated Data.” 2017 IEEE Globecom Workshops (GC Wkshps) (2017): 1-7.

Murakami, Takao and Yusuke Kawamoto. “Utility-Optimized Local Differential Privacy Mechanisms for Distribution Estimation.” USENIX Security Symposium (2018).

Humphries, Thomas, Matthew Rafuse, Lindsey Tulloch, Simon Oya, Ian Goldberg and Florian Kerschbaum. “Differentially Private Learning Does Not Bound Membership Inference.” ArXiv abs/2010.12112 (2020): n. pag.

Haney, Samuel, Damien Desfontaines, Luke Hartman, Ruchit Shrestha and Michael Hay. “Precision-based attacks and interval refining: how to break, then fix, differential privacy on finite computers.” ArXiv abs/2207.13793 (2022): n. pag.

Holohan, Naoise and Stefano Braghin. “Secure Random Sampling in Differential Privacy.” European Symposium on Research in Computer Security (2021).

Yan, Haonan, Xiaoguang Li, Hui Li, Jiamin Li, Wenhai Sun and Fenghua Li. “Monitoring-Based Differential Privacy Mechanism Against Query Flooding-Based Model Extraction Attack.” IEEE Transactions on Dependable and Secure Computing 19 (2021): 2680-2694.

Meiser, Sebastian and Esfandiar Mohammadi. “Tight on Budget?: Tight Bounds for r-Fold Approximate Differential Privacy.” Proceedings of the 2018 ACM SIGSAC Conference on Computer and Communications Security (2018): n. pag.

Gao, Jie, Ruobin Gong and Fang-Yi Yu. “Subspace Differential Privacy.” AAAI Conference on Artificial Intelligence (2021).

Almadhoun, Nour, Erman Ayday and Özgür Ulusoy. “Differential privacy under dependent tuples - the case of genomic privacy.” Bioinformatics (2019): n. pag.

Ji, Tianxi, Pan Li, Emre Yilmaz, Erman Ayday, Yanfang Ye and Jinyuan Sun. “Differentially Private Binary- and Matrix-Valued Data Query: An XOR Mechanism.” Proc. VLDB Endow. 14 (2021): 849-862.

Almadhoun, Nour, Erman Ayday and Özgür Ulusoy. “Inference attacks against differentially private query results from genomic datasets including dependent tuples.” Bioinformatics 36 (2020): i136 - i145.

Wang, Hongya, Zhengquan Xu, Shan Jia, Ying Xia and Xu Zhang. “Why current differential privacy schemes are inapplicable for correlated data publishing?” World Wide Web 24 (2020): 1-23.

Boenisch, Franziska, Philip Sperl and Konstantin Böttinger. “Gradient Masking and the Underestimated Robustness Threats of Differential Privacy in Deep Learning.” ArXiv abs/2105.07985 (2021): n. pag.

Chen, Junjie, Wendy Hui Wang and Xinghua Shi. “Differential Privacy Protection Against Membership Inference Attack on Machine Learning for Genomic Data.” bioRxiv (2020): n. pag.

Choi, Seung Geol, Dana Dachman-Soled, Mukul Kulkarni and Arkady Yerukhimovich. “Differentially-Private Multi-Party Sketching for Large-Scale Statistics.” Proceedings on Privacy Enhancing Technologies 2020 (2020): 153 - 174.

Rassouli, Borzoo, Fernando E. Rosas and Deniz Gündüz. “Data Disclosure Under Perfect Sample Privacy.” IEEE Transactions on Information Forensics and Security 15 (2019): 2012-2025.

Liu, Changchang, Xi He, Thee Chanyaswad, Shiqiang Wang and Prateek Mittal. “Investigating Statistical Privacy Frameworks from the Perspective of Hypothesis Testing.” Proceedings on Privacy Enhancing Technologies 2019 (2019): 233 - 254.

Wang, Jincheng, Zhuohua Li, John C.S. Lui and Mingshen Sun. “Topology-Theoretic Approach To Address Attribute Linkage Attacks In Differential Privacy.” IEEE INFOCOM 2021 - IEEE Conference on Computer Communications Workshops (INFOCOM WKSHPS) (2021): 1-6.

[top](README.md#mlsecops-reference-repository)

## AIML Security for Cyber-Physical Systems & IoT

Olowononi, Felix O., Danda B. Rawat and Chunmei Liu. “Resilient Machine Learning for Networked Cyber Physical Systems: A Survey for Machine Learning Security to Securing Machine Learning for CPS.” IEEE Communications Surveys & Tutorials 23 (2021): 524-552.

Kim, Sangjun and Kyung-Joon Park. “A Survey on Machine-Learning Based Security Design for Cyber-Physical Systems.” Applied Sciences 11 (2021): 5458.

Freitas de Araujo-Filho, Paulo, Georges Kaddoum, Divanilson R. Campelo, Aline Gondim Santos, David Macêdo and C. Zanchettin. “Intrusion Detection for Cyber–Physical Systems Using Generative Adversarial Networks in Fog Environment.” IEEE Internet of Things Journal 8 (2020): 6247-6256.

Tan, Sen, Josep M. Guerrero, Peilin Xie, Renke Han and Juan. C. Vasquez. “Brief Survey on Attack Detection Methods for Cyber-Physical Systems.” IEEE Systems Journal 14 (2020): 5329-5339.

Khalid, Faiq, Semeen Rehman and Muhammad Akmal Shafique. “Overview of Security for Smart Cyber-Physical Systems.” (2020).

Keliris, Anastasis, Hossein Salehghaffari, Brian R. Cairl, Prashanth Krishnamurthy, Michail Maniatakos and Farshad Khorrami. “Machine learning-based defense against process-aware attacks on Industrial Control Systems.” 2016 IEEE International Test Conference (ITC) (2016): 1-10.

Sarkar, Esha, Hadjer Benkraouda and Michail Maniatakos. “I came, I saw, I hacked: Automated Generation of Process-independent Attacks for Industrial Control Systems.” Proceedings of the 15th ACM Asia Conference on Computer and Communications Security (2020): n. pag.

Castellanos, John Henry, Martín Ochoa, Alvaro A. Cárdenas, Owen Arden and Jianying Zhou. “AttkFinder: Discovering Attack Vectors in PLC Programs using Information Flow Analysis.” Proceedings of the 24th International Symposium on Research in Attacks, Intrusions and Defenses (2021): n. pag.

Bernieri, Giuseppe, Mauro Conti and Federico Turrin. “KingFisher: an Industrial Security Framework based on Variational Autoencoders.” Proceedings of the 1st Workshop on Machine Learning on Edge in Sensor Systems (2019): n. pag.

Conti, Mauro, Denis Donadel and Federico Turrin. “A Survey on Industrial Control System Testbeds and Datasets for Security Research.” IEEE Communications Surveys & Tutorials 23 (2021): 2248-2294.

Schuster, Franka, Fabian Malte Kopp, Andreas Paul and Hartmut König. “Attack and Fault Detection in Process Control Communication Using Unsupervised Machine Learning.” 2018 IEEE 16th International Conference on Industrial Informatics (INDIN) (2018): 433-438.

Tushar, Wayes, Chau Yuen, T. K. Saha, Sohrab Nizami, Mollah Rezaul Alam, David B. Smith and H. Vincent Poor. “A Survey of Cyber-Physical Systems From a Game-Theoretic Perspective.” IEEE Access 11 (2023): 9799-9834.

Wickramasinghe, Chathurika S., Daniel L. Marino, Kasun Amarasinghe and Milos Manic. “Generalization of Deep Learning for Cyber-Physical System Security: A Survey.” IECON 2018 - 44th Annual Conference of the IEEE Industrial Electronics Society (2018): 745-751.

Al-garadi, Mohammed Ali, Amr M. Mohamed, Abdulla Khalid Al-Ali, Xiaojiang Du, Ihsan Ali and Mohsen Guizani. “A Survey of Machine and Deep Learning Methods for Internet of Things (IoT) Security.” IEEE Communications Surveys & Tutorials 22 (2018): 1646-1685.

Asharf, Javed, Nour Moustafa, Hasnat Khurshid, Essam Soliman Debie, Waqas Haider and Abdul Wahab. “A Review of Intrusion Detection Systems Using Machine and Deep Learning in Internet of Things: Challenges, Solutions and Future Directions.” Electronics (2020): n. pag.

Hussain, Fatima, Rasheed Hussain, Syed Ali Hassan and Ekram Hossain. “Machine Learning in IoT Security: Current Solutions and Future Challenges.” IEEE Communications Surveys & Tutorials 22 (2019): 1686-1721.

Zaman, Shakila, Khaled Alhazmi, Mohammed A. S. Aseeri, Muhammad R. Ahmed, Risala Tasin Khan, M. Shamim Kaiser and Mufti Mahmud. “Security Threats and Artificial Intelligence Based Countermeasures for Internet of Things Networks: A Comprehensive Survey.” IEEE Access 9 (2021): 94668-94690.

Xiao, Liang, Xiaoyue Wan, Xiaozhen Lu, Yanyong Zhang and Di Wu. “IoT Security Techniques Based on Machine Learning: How Do IoT Devices Use AI to Enhance Security?” IEEE Signal Processing Magazine 35 (2018): 41-49.

Restuccia, Francesco, Salvatore D’oro and Tommaso Melodia. “Securing the Internet of Things in the Age of Machine Learning and Software-Defined Networking.” IEEE Internet of Things Journal 5 (2018): 4829-4842.

Sagduyu, Yalin Evren, Yi Shi and Tugba Erpek. “IoT Network Security from the Perspective of Adversarial Deep Learning.” 2019 16th Annual IEEE International Conference on Sensing, Communication, and Networking (SECON) (2019): 1-9.

Sagduyu, Yalin Evren, Yi Shi, Tugba Erpek, William C. Headley, Bryse Flowers, George Stantchev and Zhuo Lu. “When Wireless Security Meets Machine Learning: Motivation, Challenges, and Research Directions.” ArXiv abs/2001.08883 (2020): n. pag.

Luo, Zhengping, Shangqing Zhao, Zhuo Lu, Yalin Evren Sagduyu and Jie Xu. “Adversarial machine learning based partial-model attack in IoT.” Proceedings of the 2nd ACM Workshop on Wireless Security and Machine Learning (2020): n. pag.

Shi, Yi, Yalin Evren Sagduyu, Tugba Erpek and Mustafa Cenk Gursoy. “How to Attack and Defend NextG Radio Access Network Slicing With Reinforcement Learning.” IEEE Open Journal of Vehicular Technology 4 (2021): 181-192.

Shi, Yi and Yalin Evren Sagduyu. “Adversarial Machine Learning for Flooding Attacks on 5G Radio Access Network Slicing.” 2021 IEEE International Conference on Communications Workshops (ICC Workshops) (2021): 1-6.

Pirayesh, Hossein and Huacheng Zeng. “Jamming Attacks and Anti-Jamming Strategies in Wireless Networks: A Comprehensive Survey.” IEEE Communications Surveys & Tutorials 24 (2021): 767-809.

Adesina, Damilola, Chung-Chu George Hsieh, Yalin Evren Sagduyu and Lijun Qian. “Adversarial Machine Learning in Wireless Communications using RF Data: A Review.” IEEE Communications Surveys & Tutorials (2020): n. pag.

Sadeghi, Meysam and Erik G. Larsson. “Adversarial Attacks on Deep-Learning Based Radio Signal Classification.” IEEE Wireless Communications Letters 8 (2018): 213-216.

Manoj, B. R., Meysam Sadeghi and Erik G. Larsson. “Adversarial Attacks on Deep Learning Based Power Allocation in a Massive MIMO Network.” ICC 2021 - IEEE International Conference on Communications (2021): 1-6.

Peng, Shengliang, Shujun Sun and Yu-dong Yao. “A Survey of Modulation Classification Using Deep Learning: Signal Representation and Data Preprocessing.” IEEE Transactions on Neural Networks and Learning Systems 33 (2021): 7020-7038.

Sagduyu, Yalin Evren, Tugba Erpek and Yi Shi. “Adversarial Machine Learning for 5G Communications Security.” ArXiv abs/2101.02656 (2021): n. pag.

Bao, Zhida, Yun Lin, Sicheng Zhang, Zixin Li and Shiwen Mao. “Threat of Adversarial Attacks on DL-Based IoT Device Identification.” IEEE Internet of Things Journal 9 (2022): 9012-9024.

Bout, Emilie, Valeria Loscrí and Antoine Gallais. “How Machine Learning Changes the Nature of Cyberattacks on IoT Networks: A Survey.” IEEE Communications Surveys & Tutorials 24 (2022): 248-279.

Shi, Yi and Yalin Evren Sagduyu. “Membership Inference Attack and Defense for Wireless Signal Classifiers with Deep Learning.” ArXiv abs/2107.12173 (2021): n. pag.

Davaslioglu, Kemal and Yalin Evren Sagduyu. “Trojan Attacks on Wireless Signal Classification with Adversarial Machine Learning.” 2019 IEEE International Symposium on Dynamic Spectrum Access Networks (DySPAN) (2019): 1-6.

Kim, Brian, Yalin Evren Sagduyu, Kemal Davaslioglu, Tugba Erpek and Sennur Ulukus. “Channel-Aware Adversarial Attacks Against Deep Learning-Based Wireless Signal Classifiers.” IEEE Transactions on Wireless Communications PP (2020): 1-1.

Luo, Zhengping, Shangqing Zhao, Zhuo Lu, Jie Xu and Yalin Evren Sagduyu. “When Attackers Meet AI: Learning-Empowered Attacks in Cooperative Spectrum Sensing.” IEEE Transactions on Mobile Computing 21 (2019): 1892-1908.

[top](README.md#mlsecops-reference-repository)

## AIML Cloud Security

Nassif, Ali Bou, Manar Abu Talib, Qassim Nasir, Halah Albadani and Fatima Mohamad Dakalbab. “Machine Learning for Cloud Security: A Systematic Review.” IEEE Access 9 (2021): 20717-20735.

Tabrizchi, Hamed and Marjan Kuchaki Rafsanjani. “A survey on security challenges in cloud computing: issues, threats, and solutions.” The Journal of Supercomputing (2020): 1-40.

Salman, Tara, Deval Bhamare, Aiman Erbad, Raj Jain and Mohammed Samaka. “Machine Learning for Anomaly Detection and Categorization in Multi-Cloud Environments.” 2017 IEEE 4th International Conference on Cyber Security and Cloud Computing (CSCloud) (2017): 97-103.

Abbasi, Hossein, Naser Ezzati-Jivan, Martine Bellaïche, Chamseddine Talhi and Michel R. Dagenais. “Machine Learning-Based EDoS Attack Detection Technique Using Execution Trace Analysis.” Journal of Hardware and Systems Security 3 (2019): 164-176.

Bhamare, Deval, Tara Salman, Mohammed Samaka, Aiman Erbad and Raj Jain. “Feasibility of Supervised Machine Learning for Cloud Security.” 2016 International Conference on Information Science and Security (ICISS) (2016): 1-5.

[top](README.md#mlsecops-reference-repository)

## AIML Intrusion & Malware Detection Systems

Grosse, Kathrin, Nicolas Papernot, Praveen Manoharan, Michael Backes and Patrick Mcdaniel. “Adversarial Perturbations Against Deep Neural Networks for Malware Classification.” ArXiv abs/1606.04435 (2016): n. pag.

Alatwi, Huda Ali and Charles Morisset. “Adversarial Machine Learning In Network Intrusion Detection Domain: A Systematic Review.” ArXiv abs/2112.03315 (2021): n. pag.

Martins, Nuno, José Magalhães Cruz, Tiago Cruz and Pedro Henriques Abreu. “Adversarial Machine Learning Applied to Intrusion and Malware Scenarios: A Systematic Review.” IEEE Access 8 (2020): 35403-35419.

Kilincer, Ilhan Firat, Fatih Ertam and Abdulkadir Şengür. “Machine learning methods for cyber security intrusion detection: Datasets and comparative study.” Comput. Networks 188 (2021): 107840.

Conti, Mauro, Denis Donadel and Federico Turrin. “A Survey on Industrial Control System Testbeds and Datasets for Security Research.” IEEE Communications Surveys & Tutorials 23 (2021): 2248-2294.

Ferrag, Mohamed Amine, L. Maglaras, Sotiris K. Moschoyiannis and Helge Janicke. “Deep learning for cyber security intrusion detection: Approaches, datasets, and comparative study.” J. Inf. Secur. Appl. 50 (2020): n. pag.

Gamage, Sunanda and Jagath Samarabandu. “Deep learning methods in network intrusion detection: A survey and an objective comparison.” J. Netw. Comput. Appl. 169 (2020): 102767.

Kocher, Geeta and Gulshan Kumar. “Machine learning and deep learning methods for intrusion detection systems: recent developments and challenges.” Soft Computing 25 (2021): 9731 - 9763.

Apruzzese, Giovanni, Mauro Andreolini, Luca Ferretti, Mirco Marchetti and Michele Colajanni. “Modeling Realistic Adversarial Attacks against Network Intrusion Detection Systems.” Digital Threats: Research and Practice (DTRAP) 3 (2021): 1 - 19.

Gümüşbaş, Dilara, Tülay Yıldırım, Angelo Genovese and Fabio Scotti. “A Comprehensive Survey of Databases and Deep Learning Methods for Cybersecurity and Intrusion Detection Systems.” IEEE Systems Journal 15 (2020): 1717-1731.

AbhishekV, A, S Binny, R JohanT, Nithin Raj and Vishal Thomas. “Federated Learning: Collaborative Machine Learning without Centralized Training Data.” international journal of engineering technology and management sciences (2022): n. pag.

[top](README.md#mlsecops-reference-repository)

## Federation

Enthoven, David and Zaid Al-Ars. “An Overview of Federated Deep Learning Privacy Attacks and Defensive Strategies.” ArXiv abs/2004.04676 (2020): n. pag.

Liu, Haizhou, Xuan Zhang, Xinwei Shen and Hongbin Sun. “A Federated Learning Framework for Smart Grids: Securing Power Traces in Collaborative Learning.” ArXiv abs/2103.11870 (2021): n. pag.

Cao, Tien-Dung, Hong Linh Truong, Tram Truong-Huu and Minh-Tri Nguyen. “Enabling Awareness of Quality of Training and Costs in Federated Machine Learning Marketplaces.” (2022).

Ekmefjord, Morgan, Addi Ait-Mlouk, Sadi Alawadi, Mattias Åkesson, Desislava Stoyanova, Ola Spjuth, Salman Zubair Toor and Andreas Hellander. “Scalable federated machine learning with FEDn.” 2022 22nd IEEE International Symposium on Cluster, Cloud and Internet Computing (CCGrid) (2021): 555-564.

Wainakh, Aidmar, Ephraim Zimmer, Sandeep Subedi, Jens Keim, Tim Grube, Shankar Karuppayah, Alejandro Sánchez Guinea and Max Mühlhäuser. “Federated Learning Attacks Revisited: A Critical Discussion of Gaps, Assumptions, and Evaluation Setups.” Sensors (Basel, Switzerland) 23 (2021): n. pag.

Naseri, Mohammad, Jamie Hayes and Emiliano De Cristofaro. “Toward Robustness and Privacy in Federated Learning: Experimenting with Local and Central Differential Privacy.” ArXiv abs/2009.03561 (2020): n. pag.

Rodr'iguez-Barroso, Nuria, Daniel Jim'enez L'opez, M. Victoria Luz'on, Francisco Herrera and Eugenio Martínez-Cámara. “Survey on Federated Learning Threats: concepts, taxonomy on attacks and defences, experimental study and challenges.” ArXiv abs/2201.08135 (2022): n. pag.

Naseri, Mohammad, Jamie Hayes and Emiliano De Cristofaro. “Local and Central Differential Privacy for Robustness and Privacy in Federated Learning.” Proceedings 2022 Network and Distributed System Security Symposium (2020): n. pag.

Liu, Peng, Xiangru Xu and Wen Wang. “Threats, attacks and defenses to federated learning: issues, taxonomy and perspectives.” Cybersecurity 5 (2022): 1-19.

Yin, Xuefei, Yanming Zhu and Jiankun Hu. “A Comprehensive Survey of Privacy-preserving Federated Learning.” ACM Computing Surveys (CSUR) 54 (2021): 1 - 36.

Boenisch, Franziska, Adam Dziedzic, R. Schuster, Ali Shahin Shamsabadi, Ilia Shumailov and Nicolas Papernot. “When the Curious Abandon Honesty: Federated Learning Is Not Private.” ArXiv abs/2112.02918 (2021): n. pag.

Pasquini, Dario, Danilo Francati and Giuseppe Ateniese. “Eluding Secure Aggregation in Federated Learning via Model Inconsistency.” Proceedings of the 2022 ACM SIGSAC Conference on Computer and Communications Security (2021): n. pag.

Wen, Yuxin, Jonas Geiping, Liam Fowl, Micah Goldblum and Tom Goldstein. “Fishing for User Data in Large-Batch Federated Learning via Gradient Magnification.” International Conference on Machine Learning (2022).

Gupta, Samyak, Yangsibo Huang, Zexuan Zhong, Tianyu Gao, Kai Li and Danqi Chen. “Recovering Private Text in Federated Learning of Language Models.” ArXiv abs/2205.08514 (2022): n. pag.

Fowl, Liam, Jonas Geiping, Steven Reich, Yuxin Wen, Wojtek Czaja, Micah Goldblum and Tom Goldstein. “Decepticons: Corrupted Transformers Breach Privacy in Federated Learning for Language Models.” ArXiv abs/2201.12675 (2022): n. pag.

Wu, Jing, Munawar Hayat, Min Zhou and Mehrtash Harandi. “Defense against Privacy Leakage in Federated Learning.” ArXiv abs/2209.05724 (2022): n. pag.

Fowl, Liam, Jonas Geiping, Wojciech Czaja, Micah Goldblum and Tom Goldstein. “Robbing the Fed: Directly Obtaining Private Data in Federated Learning with Modified Models.” ArXiv abs/2110.13057 (2021): n. pag.

Maddock, Samuel, Alexandre Sablayrolles and Pierre Stock. “CANIFE: Crafting Canaries for Empirical Privacy Measurement in Federated Learning.” ArXiv abs/2210.02912 (2022): n. pag.

Liu, Yi, Ruihui Zhao, Jiawen Kang, Abdulsalam Yassine, Dusit Tao Niyato and Jia-Jie Peng. “Towards Communication-Efficient and Attack-Resistant Federated Edge Learning for Industrial Internet of Things.” ACM Transactions on Internet Technology (TOIT) 22 (2020): 1 - 22.

[top](README.md#mlsecops-reference-repository)

## MLOps

### MLOps Overview

Kreuzberger, Dominik, Niklas Kühl and Sebastian Hirschl. “Machine Learning Operations (MLOps): Overview, Definition, and Architecture.” ArXiv abs/2205.02302 (2022): n. pag.

Symeonidis, Georgios, Evangelos Nerantzis, Apostolos Kazakis and George A. Papakostas. “MLOps - Definitions, Tools and Challenges.” 2022 IEEE 12th Annual Computing and Communication Workshop and Conference (CCWC) (2022): 0453-0460.

Lwakatare, Lucy Ellen, Ivica Crnkovic and J. Bosch. “DevOps for AI – Challenges in Development of AI-enabled Applications.” 2020 International Conference on Software, Telecommunications and Computer Networks (SoftCOM) (2020): 1-6.

Honkanen, Tapani, Jonny Odwyer and Vesa Salminen. “Multidisciplinary Teamwork in Machine Learning Operations (MLOps).” Human Factors, Business Management and Society (2022): n. pag.

Raji, Inioluwa Deborah, Indra Elizabeth Kumar, Aaron Horowitz and Andrew D. Selbst. “The Fallacy of AI Functionality.” 2022 ACM Conference on Fairness, Accountability, and Transparency (2022): n. pag.

Mäkinen, Sasu, Henrik Skogström, Eero Laaksonen and Tommi Mikkonen. “Who Needs MLOps: What Data Scientists Seek to Accomplish and How Can MLOps Help?” 2021 IEEE/ACM 1st Workshop on AI Engineering - Software Engineering for AI (WAIN) (2021): 109-112.

Paleyes, Andrei, Raoul-Gabriel Urma and Neil D. Lawrence. “Challenges in Deploying Machine Learning: A Survey of Case Studies.” ACM Computing Surveys 55 (2020): 1 - 29.

Wan, Zhiyuan, Xin Xia, David Lo and Gail C. Murphy. “How does Machine Learning Change Software Development Practices?” IEEE Transactions on Software Engineering 47 (2021): 1857-1871.

Granlund, Tuomas, Aleksi Kopponen, Vlad Stirbu, Lalli Myllyaho and Tommi Mikkonen. “MLOps Challenges in Multi-Organization Setup: Experiences from Two Real-World Cases.” 2021 IEEE/ACM 1st Workshop on AI Engineering - Software Engineering for AI (WAIN) (2021): 82-88.

Ruf, Philipp, Manav Madan, Christoph Reich and Djaffar Ould-Abdeslam. “Demystifying MLOps and Presenting a Recipe for the Selection of Open-Source Tools.” Applied Sciences (2021): n. pag.

John, Meenu Mary, Helena Holmström Olsson and J. Bosch. “Towards MLOps: A Framework and Maturity Model.” 2021 47th Euromicro Conference on Software Engineering and Advanced Applications (SEAA) (2021): 1-8.

Renggli, Cédric, Luka Rimanic, Nezihe Merve Gurel, Bojan Karlavs, Wentao Wu and Ce Zhang. “A Data Quality-Driven View of MLOps.” IEEE Data Eng. Bull. 44 (2021): 11-23.

Granlund, Tuomas, Aleksi Kopponen, Vlad Stirbu, Lalli Myllyaho and Tommi Mikkonen. “MLOps Challenges in Multi-Organization Setup: Experiences from Two Real-World Cases.” 2021 IEEE/ACM 1st Workshop on AI Engineering - Software Engineering for AI (WAIN) (2021): 82-88.

Shankar, Shreya, Rolando Garcia, Joseph M. Hellerstein and Aditya G. Parameswaran. “Operationalizing Machine Learning: An Interview Study.” ArXiv abs/2209.09125 (2022): n. pag.

Matsui, Beatriz Mayumi Andrade and Denise H. Goya. “MLOps: Five Steps to Guide its Effective Implementation.” 2022 IEEE/ACM 1st International Conference on AI Engineering – Software Engineering for AI (CAIN) (2022): 33-34.

Matsui, Beatriz Mayumi Andrade and Denise H. Goya. “MLOps: A Guide to its Adoption in the Context of Responsible AI.” 2022 IEEE/ACM 1st International Workshop on Software Engineering for Responsible Artificial Intelligence (SE4RAI) (2022): 45-49.

John, Meenu Mary, Helena Holmström Olsson and J. Bosch. “Towards MLOps: A Framework and Maturity Model.” 2021 47th Euromicro Conference on Software Engineering and Advanced Applications (SEAA) (2021): 1-8.

Dyck, Andrej, Ralf Penners and Horst Lichter. “Towards Definitions for Release Engineering and DevOps.” 2015 IEEE/ACM 3rd International Workshop on Release Engineering (2015): 3-3.

Silva, Lucas Cardoso, Fernando Rezende Zagatti, Bruno Silva Sette, Lucas Nildaimon dos Santos Silva, Daniel Lucrédio, Diego Furtado Silva and Helena de Medeiros Caseli. “Benchmarking Machine Learning Solutions in Production.” 2020 19th IEEE International Conference on Machine Learning and Applications (ICMLA) (2020): 626-633.

Karamitsos, Ioannis, Saeed Albarhami and Charalampos Apostolopoulos. “Applying DevOps Practices of Continuous Automation for Machine Learning.” Inf. 11 (2020): 363.

Garg, Satvik, Pradyumn Pundir, Geetanjali Rathee, Piyush Kumar Gupta, Somya Garg and Saransh Ahlawat. “On Continuous Integration / Continuous Delivery for Automated Deployment of Machine Learning Models using MLOps.” 2021 IEEE Fourth International Conference on Artificial Intelligence and Knowledge Engineering (AIKE) (2021): 25-28.

Baier, Lucas, Fabian Jöhren and Stefan Seebacher. “Challenges in the Deployment and Operation of Machine Learning in Practice.” European Conference on Information Systems (2019).

Giray, Görkem. “A Software Engineering Perspective on Engineering Machine Learning Systems: State of the Art and Challenges.” J. Syst. Softw. 180 (2020): 111031.

Mart'inez-Fern'andez, Silverio, Justus Bogner, Xavier Franch, Marc Oriol, Julien Siebert, Adam Trendowicz, Anna Maria Vollmer and Stefan Wagner. “Software Engineering for AI-Based Systems: A Survey.” ACM Transactions on Software Engineering and Methodology (TOSEM) 31 (2021): 1 - 59.

Habibullah, Khan Mohammad and Jennifer Horkoff. “Non-functional Requirements for Machine Learning: Understanding Current Use and Challenges in Industry.” 2021 IEEE 29th International Requirements Engineering Conference (RE) (2021): 13-23.

Symeonidis, Georgios, Evangelos Nerantzis, Apostolos Kazakis and George A. Papakostas. “MLOps - Definitions, Tools and Challenges.” 2022 IEEE 12th Annual Computing and Communication Workshop and Conference (CCWC) (2022): 0453-0460.

Mäkinen, Sasu, Henrik Skogström, Eero Laaksonen and Tommi Mikkonen. “Who Needs MLOps: What Data Scientists Seek to Accomplish and How Can MLOps Help?” 2021 IEEE/ACM 1st Workshop on AI Engineering - Software Engineering for AI (WAIN) (2021): 109-112.

Siddappa, Prathima. “Towards Addressing MLOps Pipeline Challenges: Practical Guidelines Based on a Multivocal Literature Review.” (2022).

Granlund, Tuomas, Aleksi Kopponen, Vlad Stirbu, Lalli Myllyaho and Tommi Mikkonen. “MLOps Challenges in Multi-Organization Setup: Experiences from Two Real-World Cases.” 2021 IEEE/ACM 1st Workshop on AI Engineering - Software Engineering for AI (WAIN) (2021): 82-88.

Muralidhar, Nikhil, Sathappah Muthiah, Patrick Butler, Manish Jain, Yu Yu, Katy Burne, Weipeng Li, David Jones, Prakash Arunachalam, Hays 'Skip' McCormick and Naren Ramakrishnan. “Using AntiPatterns to avoid MLOps Mistakes.” ArXiv abs/2107.00079 (2021): n. pag.

Borg, Markus. “Agility in Software 2.0 - Notebook Interfaces and MLOps with Buttresses and Rebars.” International Conference on Lean and Agile Software Development (2021).

Mei, Songzhu, Cong Liu, Qinglin Wang and Huayou Su. “Model Provenance Management in MLOps Pipeline.” 2022 The 8th International Conference on Computing and Data Engineering (2022): n. pag.

Tamburri, Damian Andrew. “Sustainable MLOps: Trends and Challenges.” 2020 22nd International Symposium on Symbolic and Numeric Algorithms for Scientific Computing (SYNASC) (2020): 17-23.

Alla, Sridhar and Suman Kalyan Adari. “What Is MLOps?” (2020).

Zhou, Yue, Yue Yu and Bo Ding. “Towards MLOps: A Case Study of ML Pipeline Platform.” 2020 International Conference on Artificial Intelligence and Computer Engineering (ICAICE) (2020): 494-500.

Banerjee, Amit, Chien-Chia Chen, Chien-Chun Hung, Xiaobo Huang, Yifan Wang and Razvan Chevesaran. “Challenges and Experiences with MLOps for Performance Diagnostics in Hybrid-Cloud Enterprise Software Deployments.” USENIX Conference on Operational Machine Learning (2020).

Shankar, Shreya, Rolando Garcia, Joseph M. Hellerstein and Aditya G. Parameswaran. “Operationalizing Machine Learning: An Interview Study.” ArXiv abs/2209.09125 (2022): n. pag.

Spjuth, Ola, Jens Frid and Andreas Hellander. “The machine learning life cycle and the cloud: implications for drug discovery.” Expert Opinion on Drug Discovery 16 (2021): 1071 - 1079.

Ranawana, Romesh M. and Asoka S. Karunananda. “An Agile Software Development Life Cycle Model for Machine Learning Application Development.” 2021 5th SLAAI International Conference on Artificial Intelligence (SLAAI-ICAI) (2021): 1-6.

Ishikawa, Fuyuki and Yutaka Matsuno. “Evidence-driven Requirements Engineering for Uncertainty of Machine Learning-based Systems.” 2020 IEEE 28th International Requirements Engineering Conference (RE) (2020): 346-351.

Silva, Lucas Cardoso, Fernando Rezende Zagatti, Bruno Silva Sette, Lucas Nildaimon dos Santos Silva, Daniel Lucrédio, Diego Furtado Silva and Helena de Medeiros Caseli. “Benchmarking Machine Learning Solutions in Production.” 2020 19th IEEE International Conference on Machine Learning and Applications (ICMLA) (2020): 626-633.

“MLOps-Standardizing the Machine Learning Workflow.” (2021).

Siddique, Umair. “SafetyOps.” ArXiv abs/2008.04461 (2020): n. pag.

John, Meenu Mary. “Design Methods and Processes for ML/DL models.” (2021).

Luu, Hien. “Managing the Machine Learning Life Cycle.” (2021).

Heck, Petra, Gerard Schouten and Luís Cruz. “A Software Engineering Perspective on Building Production-Ready Machine Learning Systems.” Advances in Business Information Systems and Analytics (2021): n. pag.

Banerjee, Amit, Chien-Chia Chen, Chien-Chun Hung, Xiaobo Huang, Yifan Wang and Razvan Chevesaran. “Challenges and Experiences with MLOps for Performance Diagnostics in Hybrid-Cloud Enterprise Software Deployments.” USENIX Conference on Operational Machine Learning (2020).

Horkoff, Jennifer. “Non-Functional Requirements for Machine Learning: Challenges and New Directions.” 2019 IEEE 27th International Requirements Engineering Conference (RE) (2019): 386-391.

[top](README.md#mlsecops-reference-repository)

### MLOps, SecOps and Failure Modes & Effects Analysis (FMEA)

Myllyaho, Lalli, Mikko Raatikainen, Tomi Männistö, Jukka K. Nurminen and Tommi Mikkonen. “On Misbehaviour and Fault Tolerance in Machine Learning Systems.” ArXiv abs/2109.07989 (2021): n. pag.

Mauri, Lara and Ernesto Damiani. “Modeling Threats to AI-ML Systems Using STRIDE.” Sensors (Basel, Switzerland) 22 (2022): n. pag.

Rismani, Shalaleh, Renee Marie Shelby, Andrew Smart, Edgar W. Jatho, Joshua A. Kroll, AJung Moon and Negar Rostamzadeh. “From plane crashes to algorithmic harm: applicability of safety engineering frameworks for responsible ML.” ArXiv abs/2210.03535 (2022): n. pag.

Malhotra, Yogesh. “How You Can Implement Well-Architected ‘Zero Trust’ Hybrid-Cloud Computing Beyond ‘Lift and Shift’: Cloud-Enabled Digital Innovation at Scale with Infrastructure as Code (IaC), DevSecOps and MLops.” SSRN Electronic Journal (2022): n. pag.

Rismani, Shalaleh, Renee Marie Shelby, Andrew Smart, Edgar W. Jatho, Joshua A. Kroll, AJung Moon and Negar Rostamzadeh. “From plane crashes to algorithmic harm: applicability of safety engineering frameworks for responsible ML.” ArXiv abs/2210.03535 (2022): n. pag.

Li, Jamy J. and Mark H. Chignell. “FMEA-AI: AI fairness impact assessment using failure mode and effects analysis.” AI and Ethics 2 (2022): 837 - 850.

Kumar, Ram Shankar Siva, David R. O'Brien, Kendra Albert, Salomé Viljöen and Jeffrey Snover. “Failure Modes in Machine Learning Systems.” ArXiv abs/1911.11034 (2019): n. pag.

Spring, Jonathan M., April Galyardt, Allen D. Householder and Nathan M. VanHoudnos. “On managing vulnerabilities in AI/ML systems.” New Security Paradigms Workshop 2020 (2020): n. pag.

Kalin, Josh, David Noever and Matthew Ciolino. “Color Teams for Machine Learning Development.” ArXiv abs/2110.10601 (2021): n. pag.

Mauri, Lara and Ernesto Damiani. “STRIDE-AI: An Approach to Identifying Vulnerabilities of Machine Learning Assets.” 2021 IEEE International Conference on Cyber Security and Resilience (CSR) (2021): 147-154.

Papernot, Nicolas, Patrick Mcdaniel, Arunesh Sinha and Michael P. Wellman. “SoK: Security and Privacy in Machine Learning.” 2018 IEEE European Symposium on Security and Privacy (EuroS&P) (2018): 399-414.

Papernot, Nicolas. “A Marauder's Map of Security and Privacy in Machine Learning: An overview of current and future research directions for making machine learning secure and private.” Proceedings of the 11th ACM Workshop on Artificial Intelligence and Security (2018): n. pag.

Evtimov, I., Weidong Cui, Ece Kamar, Emre Kıcıman, Tadayoshi Kohno and Jerry Zheng Li. “Security and Machine Learning in the Real World.” ArXiv abs/2007.07205 (2020): n. pag.

Bieringer, Lukas, Kathrin Grosse, Michael Backes and Katharina Krombholz. “Mental Models of Adversarial Machine Learning.” ArXiv abs/2105.03726 (2021): n. pag.

Kumar, Ram Shankar Siva, Magnus Nyström, John Lambert, Andrew Marshall, Mario Goertzel, Andi Comissoneru, Matt Swann and Sharon Xia. “Adversarial Machine Learning - Industry Perspectives.” CompSciRN: Other Cybersecurity (2020): n. pag.

Boenisch, Franziska, Verena Battis, Nicolas Buchmann and Maija Poikela. ““I Never Thought About Securing My Machine Learning Systems”: A Study of Security and Privacy Awareness of Machine Learning Practitioners.” Proceedings of Mensch und Computer 2021 (2021): n. pag.

Xiong, Pulei, Scott Buffett, Shahrear Iqbal, Philippe Lamontagne, Mohammad Saiful Islam Mamun and Heather Molyneaux. “Towards a Robust and Trustworthy Machine Learning System Development.” J. Inf. Secur. Appl. 65 (2021): 103121.

Papernot, Nicolas, Patrick Mcdaniel, Arunesh Sinha and Michael P. Wellman. “Towards the Science of Security and Privacy in Machine Learning.” ArXiv abs/1611.03814 (2016): n. pag.

[top](README.md#mlsecops-reference-repository)

### MLOps Supply Chain & Data

Bou'e, Laurent, Pratap Kunireddy and Pavle Suboti'c. “A Data Source Dependency Analysis Framework for Large Scale Data Science Projects.” ArXiv abs/2212.07951 (2022): n. pag.

Jakubik, Johannes, Michael Vossing, Niklas Kuhl, Jannis Walk and Gerhard Satzger. “Data-centric Artificial Intelligence.” ArXiv abs/2212.11854 (2022): n. pag.

Renggli, Cédric, Luka Rimanic, Nezihe Merve Gurel, Bojan Karlavs, Wentao Wu and Ce Zhang. “A Data Quality-Driven View of MLOps.” IEEE Data Eng. Bull. 44 (2021): 11-23.

Ruf, Philipp, Manav Madan, Christoph Reich and Djaffar Ould-Abdeslam. “Demystifying MLOps and Presenting a Recipe for the Selection of Open-Source Tools.” Applied Sciences (2021): n. pag.

Sculley, D., Gary Holt, Daniel Golovin, Eugene Davydov, Todd Phillips, Dietmar Ebner, Vinay Chaudhary, Michael Young, Jean-François Crespo and Dan Dennison. “Hidden Technical Debt in Machine Learning Systems.” NIPS (2015).

[top](README.md#mlsecops-reference-repository)

### MLOps for Edge & IoT

Ruf, Philipp, Christoph Reich and Djaffar Ould-Abdeslam. “Aspects of Module Placement in Machine Learning Operations for Cyber Physical Systems.” 2022 11th Mediterranean Conference on Embedded Computing (MECO) (2022): 1-6.

Leroux, Sam, Pieter Simoens, Meelis Lootus, Kartik Thakore and Akshay Sharma. “TinyMLOps: Operational Challenges for Widespread Edge AI Adoption.” 2022 IEEE International Parallel and Distributed Processing Symposium Workshops (IPDPSW) (2022): 1003-1010.

Antonini, Mattia, Miguel Pincheira, Massimo Vecchio and Fabio Antonelli. “An Adaptable and Unsupervised TinyML Anomaly Detection System for Extreme Industrial Environments.” Sensors (2023): n. pag.

Ruf, Philipp, Christoph Reich and Djaffar Ould-Abdeslam. “Aspects of Module Placement in Machine Learning Operations for Cyber Physical Systems.” 2022 11th Mediterranean Conference on Embedded Computing (MECO) (2022): 1-6.

Fujii, Tiago Yukio, Victor Takashi Hayashi, Reginaldo Arakaki, Wilson Vicente Ruggiero, Romeo Bulla, Fabio Hirotsugu Hayashi and Khalil Ahmad Khalil. “A Digital Twin Architecture Model Applied with MLOps Techniques to Improve Short-Term Energy Consumption Prediction.” Machines (2021): n. pag.

“Edge MLOps framework for AIoT applications.” (2020).

Fujii, Tiago Yukio, Victor Takashi Hayashi, Reginaldo Arakaki, Wilson Vicente Ruggiero, Romeo Bulla, Fabio Hirotsugu Hayashi and Khalil Ahmad Khalil. “A Digital Twin Architecture Model Applied with MLOps Techniques to Improve Short-Term Energy Consumption Prediction.” Machines (2021): n. pag.

Antonini, Mattia, Miguel Pincheira, Massimo Vecchio and Fabio Antonelli. “Tiny-MLOps: a framework for orchestrating ML applications at the far edge of IoT systems.” 2022 IEEE International Conference on Evolving and Adaptive Intelligent Systems (EAIS) (2022): 1-8.

Sinkevych, Oleh, Yaroslav Boyko and Lyubomyr Monastyrskyy. “MLOps BASED PROTOTYPE OF AI SYSTEM FOR EDGE COMPUTING.” Electronics and Information Technologies (2022): n. pag.

Raj, Emmanuel, David Buffoni, Magnus Westerlund and Kimmo Ahola. “Edge MLOps: An Automation Framework for AIoT Applications.” 2021 IEEE International Conference on Cloud Engineering (IC2E) (2021): 191-200.

Vuppalapati, Chandrasekar, Anitha Ilapakurti, Karthik Chillara, Sharat Kedari and Vanaja Mamidi. “Automating Tiny ML Intelligent Sensors DevOPS Using Microsoft Azure.” 2020 IEEE International Conference on Big Data (Big Data) (2020): 2375-2384.

Almurshed, Osama, Panos Patros, Victoria Huang, Michael Mayo, Melanie Ooi, Ryan Chard, Kyle Chard, Omer Farooq Rana, Harshaan Nagra, Matt Baughman and Ian T. Foster. “Adaptive Edge-Cloud Environments for Rural AI.” 2022 IEEE International Conference on Services Computing (SCC) (2022): 74-83.

[top](README.md#mlsecops-reference-repository)

### MLOps Policy & Compliance

Henry, Jazmia. “MLOps: A Primer for Policymakers on a New Frontier in Machine Learning.” ArXiv abs/2301.05775 (2023): n. pag.

Benjamens, Stan, Pranavsingh Dhunnoo and Bertalan Meskó. “The state of artificial intelligence-based FDA-approved medical devices and algorithms: an online database.” NPJ Digital Medicine 3 (2020): n. pag.

Veale, Michael and Frederik J. Zuiderveen Borgesius. “Demystifying the Draft EU Artificial Intelligence Act — Analysing the good, the bad, and the unclear elements of the proposed approach.” Computer Law Review International 22 (2021): 97 - 112.

Jobin, Anna, Marcello Ienca and Effy Vayena. “Artificial Intelligence: the global landscape of ethics guidelines.” ArXiv abs/1906.11668 (2019): n. pag.

Granlund, Tuomas, Vlad Stirbu and Tommi Mikkonen. “Towards Regulatory-Compliant MLOps: Oravizio’s Journey from a Machine Learning Experiment to a Deployed Certified Medical Product.” SN Computer Science 2 (2021): n. pag.

Eale, M Ichael V. “SLAVE TO THE ALGORITHM ? WHY A ‘ RIGHT TO AN EXPLANATION ’ IS PROBABLY NOT THE REMEDY YOU ARE LOOKING FOR.” (2017).

Wu, Eric, Kevin Wu, Roxana Daneshjou, David Ouyang, Daniel E. Ho and James Zou. “How medical AI devices are evaluated: limitations and recommendations from an analysis of FDA approvals.” Nature Medicine 27 (2021): 582 - 584.

Brand, Dirk. “Algorithmic Decision-making and the Law.” JeDEM: eJournal of eDemocracy and Open Government 12 (2020): 114-131.

Selbst, Andrew D. and Julia E. Powles. “"Meaningful Information" and the Right to Explanation.” FAT (2017).

Petkova, Bilyana. “Federal Trade Commission Privacy Law and Policy.” International Journal of Constitutional Law 14 (2016): 781-783.

Granlund, Tuomas, Vlad Stirbu and Tommi Mikkonen. “Towards Regulatory-Compliant MLOps: Oravizio’s Journey from a Machine Learning Experiment to a Deployed Certified Medical Product.” SN Computer Science 2 (2021): n. pag.

Veale, Michael and Lilian Edwards. “Clarity, surprises, and further questions in the Article 29 Working Party draft guidance on automated decision-making and profiling.” Comput. Law Secur. Rev. 34 (2018): 398-404.

Kaminski, Margot E. and Gianclaudio Malgieri. “Algorithmic Impact Assessments under the GDPR: Producing Multi-layered Explanations.” Cybersecurity (2019): n. pag.

Metcalf, Jacob, Emanuel Moss, Elizabeth Anne Watkins, Ranjit Singh and Madeleine Clare Elish. “Algorithmic Impact Assessments and Accountability: The Co-construction of Impacts.” Proceedings of the 2021 ACM Conference on Fairness, Accountability, and Transparency (2020): n. pag.

Havens, John C. and Ali G. Hessami. “From Principles and Standards to Certification.” Computer 52 (2019): 69-72.

McGeveran, William. “The Duty of Data Security.” Social Science Research Network (2019): n. pag.

Hoffmann-Riem, Wolfgang. “Artificial Intelligence as a Challenge for Law and Regulation.” (2019).

Mitrou, Lilian. “Data Protection, Artificial Intelligence and Cognitive Services: Is the General Data Protection Regulation (GDPR) ‘Artificial Intelligence-Proof’?” Tilburg: TILT Law & Technology Working Paper Series (Topic) (2018): n. pag.

Calo, Ryan. “Robotics and the Lessons of Cyberlaw.” California Law Review 103 (2014): 513.

Shankar, Shreya and Aditya G. Parameswaran. “Towards Observability for Machine Learning Pipelines.” ArXiv abs/2108.13557 (2022): n. pag.

Veale, Michael, Reuben Binns and Lilian Edwards. “Algorithms that remember: model inversion attacks and data protection law.” Philosophical transactions. Series A, Mathematical, physical, and engineering sciences 376 (2018): n. pag.

[top](README.md#mlsecops-reference-repository)

## Threat Modeling & Secure Design

Shostack, Adam. “Threat Modeling: Designing for Security.” (2014).

Khan, Rafiullah, Kieran McLaughlin, David M. Laverty and Sakir Sezer. “STRIDE-based threat modeling for cyber-physical systems.” 2017 IEEE PES Innovative Smart Grid Technologies Conference Europe (ISGT-Europe) (2017): 1-6.

Myagmar, Suvda, Adam J. Lee and William Yurcik. “Threat Modeling as a Basis for Security Requirements.” (2005).

[top](README.md#mlsecops-reference-repository)

## Datasets

Yavanoglu, Ozlem and Murat Aydos. “A review on cyber security datasets for machine learning algorithms.” 2017 IEEE International Conference on Big Data (Big Data) (2017): 2186-2193.

Bhuyan, Monowar H., Dhruba Kumar Bhattacharyya and Jugal Kumar Kalita. “Towards Generating Real-life Datasets for Network Intrusion Detection.” Int. J. Netw. Secur. 17 (2015): 683-701.

Erokhin, Sergey and A. P. Zhuravlev. “A Comparative Analysis of Public Cyber Security Datasets.” 2020 Systems of Signal Synchronization, Generating and Processing in Telecommunications (SYNCHROINFO) (2020): 1-7.

Devi, M. S. Girija and Manisha J. Nene. “Scarce Attack Datasets and Experimental Dataset Generation.” 2018 Second International Conference on Electronics, Communication and Aerospace Technology (ICECA) (2018): 1112-1116.

Banoth, Lalu, Mamidi Sri Sai Teja, M Saicharan and N Jaya Chandra. “A Survey of Data Mining and Machine Learning Methods for Cyber Security Intrusion Detection.” International Journal of Research 4 (2017): 406-412.

Khraisat, Ansam, Iqbal Gondal, Peter Vamplew and Joarder Kamruzzaman. “Survey of intrusion detection systems: techniques, datasets and challenges.” Cybersecur. 2 (2019): 20.

Cordero, Carlos Garcia, Emmanouil Vasilomanolakis, Aidmar Wainakh, M. Mühlhäuser and Simin Nadjm-Tehrani. “On Generating Network Traffic Datasets with Synthetic Attacks for Intrusion Detection.” ACM Transactions on Privacy and Security (TOPS) 24 (2019): 1 - 39.

Vu, Ly and Quang Uy Nguyen. “Handling Imbalanced Data in Intrusion Detection Systems using Generative Adversarial Networks.” Journal of Research and Development on Information and Communication Technology (2020): n. pag.

Ferriyan, Andrey, Achmad Husni Thamrin, Keiji Takeda and Jun Murai. “Generating Network Intrusion Detection Dataset Based on Real and Encrypted Synthetic Attack Traffic.” Applied Sciences (2021): n. pag.

Damaševičius, Robertas, Algimantas Venčkauskas, Šarūnas Grigaliūnas, Jevgenijus Toldinas, Nerijus Morkevičius, Tautvydas Aleliunas and Paulius Smuikys. “LITNET-2020: An Annotated Real-World Network Flow Dataset for Network Intrusion Detection.” Electronics (2020): n. pag.

Hindy, Hanan, David Brosset, Ethan Bayne, Amar Kumar Seeam, Christos Tachtatzis, Robert C. Atkinson and Xavier J. A. Bellekens. “A Taxonomy of Network Threats and the Effect of Current Datasets on Intrusion Detection Systems.” IEEE Access 8 (2020): 104650-104675.

Garg, Satvik, Pradyumn Pundir, Geetanjali Rathee, Piyush Kumar Gupta, Somya Garg and Saransh Ahlawat. “On Continuous Integration / Continuous Delivery for Automated Deployment of Machine Learning Models using MLOps.” 2021 IEEE Fourth International Conference on Artificial Intelligence and Knowledge Engineering (AIKE) (2021): 25-28.

Koroniotis, Nickolaos, Nour Moustafa, Elena Sitnikova and Benjamin P. Turnbull. “Towards the Development of Realistic Botnet Dataset in the Internet of Things for Network Forensic Analytics: Bot-IoT Dataset.” Future Gener. Comput. Syst. 100 (2018): 779-796.

Sharafaldin, Iman, Arash Habibi Lashkari and Ali A. Ghorbani. “Toward Generating a New Intrusion Detection Dataset and Intrusion Traffic Characterization.” International Conference on Information Systems Security and Privacy (2018).

Gogoi, Prasanta, Monowar H. Bhuyan, Dhruba Kumar Bhattacharyya and Jugal Kumar Kalita. “Packet and Flow Based Network Intrusion Dataset.” International Conference on Contemporary Computing (2012).

Shiravi, Ali, Hadi Shiravi, Mahbod Tavallaee and Ali A. Ghorbani. “Toward developing a systematic approach to generate benchmark datasets for intrusion detection.” Comput. Secur. 31 (2012): 357-374.

Ring, Markus, Sarah Wunderlich, Dominik Grüdl, Dieter Landes and Andreas Hotho. “Flow-based benchmark data sets for intrusion detection.” (2017).

Thomas, Ciza, Vishwas Sharma and N. Balakrishnan. “Usefulness of DARPA dataset for intrusion detection system evaluation.” SPIE Defense + Commercial Sensing (2008).

Sperotto, Anna, Ramin Sadre, Frank E. van Vliet and Aiko Pras. “A Labeled Data Set for Flow-Based Intrusion Detection.” IEEE International Workshop on IP Operations and Management (2009).

Kendall, Kristopher R.. “A Database of Computer Attacks for the Evaluation of Intrusion Detection Systems.” (1999).

Dua, Sumeet and Xian Du. “Data Mining and Machine Learning in Cybersecurity.” (2011).

[top](README.md#mlsecops-reference-repository)

## LLM Security

Wu, Fangzhou, Ning Zhang, Somesh Jha, Patrick Drew McDaniel and Chaowei Xiao. “A New Era in LLM Security: Exploring Security Concerns in Real-World LLM-based Systems.” ArXiv abs/2402.18649 (2024): n. Pag.

Yao, Yifan, Jinhao Duan, Kaidi Xu, Yuanfang Cai, Eric Sun and Yue Zhang. “A Survey on Large Language Model (LLM) Security and Privacy: The Good, the Bad, and the Ugly.” ArXiv abs/2312.02003 (2023): n. Pag.

Peng, Benji, Keyu Chen, Ming Li, Pohsun Feng, Ziqian Bi, Junyu Liu and Qian Niu. “Securing Large Language Models: Addressing Bias, Misinformation, and Prompt Attacks.” ArXiv abs/2409.08087 (2024): n. pag.

## Agentic AI

Masterman, Tula, Sandi Besen, Mason Sawtell and Alex Chao. “The Landscape of Emerging AI Agent Architectures for Reasoning, Planning, and Tool Calling: A Survey.” ArXiv abs/2404.11584 (2024): n. Pag.

Shavit, Yonadav, Sandhini Agarwal, Miles Brundage, Steven Adler Cullen O’Keefe, Rosie Campbell, Teddy Lee, Pamela Mishkin, Tyna Eloundou, Alan Hickey, Katarina Slama, Lama Ahmad, Paul McMillan, Alex Beutel, Alexandre Passos and David G. Robinson. “Practices for Governing Agentic AI Systems.”

Putta, Pranav, Edmund Mills, Naman Garg, Sumeet Ramesh Motwani, Chelsea Finn, Divyansh Garg and Rafael Rafailov. “Agent Q: Advanced Reasoning and Learning for Autonomous AI Agents.” ArXiv abs/2408.07199 (2024): n. Pag.

Yu, Miao, Fanci Meng, Xinyun Zhou, Shilong Wang, Junyuan Mao, Linsey Pang, Tianlong Chen, Kun Wang, Xinfeng Li, Yongfeng Zhang, Bo An and Qingsong Wen. “A Survey on Trustworthy LLM Agents: Threats and Countermeasures.” ArXiv abs/2503.09648 (2025): n. pag.

Khan, Raihan, Sayak Sarkar, Sainik Kumar Mahata and Edwin Jose. “Security Threats in Agentic AI System.” ArXiv abs/2410.14728 (2024): n. Pag.

He, Feng, Tianqing Zhu, Dayong Ye, Bo Liu, Wanlei Zhou and Philip S. Yu. “The Emerged Security and Privacy of LLM Agent: A Survey with Case Studies.” ArXiv abs/2407.19354 (2024): n. Pag.

Xinyi Hou, Yanjie Zhao, Shenao Wang, Haoyu Wang "Model Context Protocol (MCP) : Landscape, Security Threats, and Future Research Directions" ArXiv abs/2503.23278 (2025)

[top](README.md#mlsecops-reference-repository)

