# Machine Learning Based Cyber Attacks Targeting on Controlled Information: A Survey

Everything about code sources, datasets and data sources mentioned in the survey paper "Machine Learning Based Cyber Attacks Targeting on Controlled Information: A Survey".

_ _ _

## Table of contents
* Research articles by areas 
* Data and code sources used by attacks
  * Stealing controlled user activities information
  * Stealing controlled ML model related information
  * Stealing controlled authentication inforamtion
  
_ _ _

### Research articles by areas
- [1] Stealing controlled user activities using kernel data - attack with timing analysis: [No pardon for the interruption: New inference attacks on android through interrupt timing analysis (S&P, 2016)](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7546515)

- [2] Stealing controlled user activities using kernel data - attack with timing analysis: [ProcHarvester: Fully Automated Analysis of Procfs Side-Channel Leaks on Android (ACM Asia CCS, 2018)](https://rspreitzer.github.io/publications/proc/asiaccs-2018-paper-2.pdf)

- [3] Stealing controlled user activities using kernel data - iOS side-channel attack: [OS-level Side Channels without Procfs: Exploring Cross-App Information Leakage on iOS (NDSS, 2018)](http://web.cse.ohio-state.edu/~zhang.834/papers/ndss18a.pdf) 

- [4] Stealing controlled user activities using kernel data - protect using privacy mechanism: [Mitigating Storage Side Channels Using Statistical Privacy Mechanisms (ACM CCS, 2015)](https://dl.acm.org/citation.cfm?id=2813645)

- [5] Stealing controlled user activities using sensor data - sensor-based attack: [Leave Your Phone at the Door: Side Channels that Reveal Factory Floor Secrets (ACM CCS, 2016)](http://seclab.illinois.edu/wp-content/uploads/2016/10/CCS_2016___3D_Printer.pdf)

- [6] Stealing controlled user activities using sensor data - protect using context-aware sensor-based detector: [6thSense: A Context-aware Sensor-based Attack Detector for Smart Devices (USENIX, 2017)](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-sikder.pdf)

- [7] Stealing controlled ML model description - stealing parameters attack: [Stealing Machine Learning Models via Prediction APIs (USENIX, 2016)](https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_tramer.pdf)

- [8] Stealing controlled ML model description - stealing hyperparameters attack: [Stealing Hyperparameters in Machine Learning (S&P, 2018)](https://arxiv.org/pdf/1802.05351.pdf)

- [9] Stealing controlled ML model's training data - model inversion attack & defence: [Model inversion attacks that exploit confidence information and basic countermeasures (ACM CCS, 2015)](http://www.cs.cmu.edu/~mfredrik/papers/fjr2015ccs.pdf) 

- [10] Stealing controlled ML model's training data - the GAN attack: [Deep Models Under the GAN: Information Leakage from Collaborative Deep Learning (ACM CCS, 2017)](https://arxiv.org/pdf/1702.07464.pdf)

- [11] Stealing controlled ML model's training data - membership inference attack: [Membership Inference Attacks Against Machine Learning Models (S&P, 2017)](https://arxiv.org/pdf/1610.05820.pdf)

- [12] Stealing controlled ML model's training data - protect with adversarial regularization: [Machine Learning with Membership Privacy using Adversarial Regularization (ACM CCS, 2018)](https://arxiv.org/pdf/1807.05852.pdf)

- [13] Stealing controlled ML model's training data - protect with count featurization: [Pyramid: Enhancing Selectivity in Big Data Protection with Count Featurization (S&P, 2017)](https://arxiv.org/pdf/1705.07512.pdf)

- [14] Stealing controlled keystroke data for authentication - keystroke inference attack: [When Good Becomes Evil: Keystroke Inference with Smartwatch (ACM CCS, 2015)](https://staff.ie.cuhk.edu.hk/~khzhang/my-papers/2015-ccs-swatch.pdf)

- [15] Stealing controlled keystroke data for authentication - video-assisted keystroke inference attack: [VISIBLE: Video-Assisted Keystroke Inference from Tablet Backside Motion (NDSS, 2016)](https://pdfs.semanticscholar.org/9545/077902d9ea3444894b43b6d14ff16f5dc06c.pdf)

- [16] Stealing controlled secret keys for authentication - attack with TLB cache data: [Translation Leak-aside Buffer: Defeating Cache Side-channel Protections with TLB Attacks (USENIX, 2018)](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-gras.pdf)

- [17] Stealing controlled secret keys for authentication - attack & protect with CPU cache data: [A software approach to defeating side channels in last-level caches (ACM CCS, 2016)](http://delivery.acm.org/10.1145/2980000/2978324/p871-zhou.pdf?ip=101.176.75.238&id=2978324&acc=OA&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E8A0A9AC1EB2AB412&__acm__=1548111551_9e024df16fa23252e5ccb855eb9c7681)

- [18] Stealing controlled password data for authentication - online password guessing attack: [Targeted Online Password Guessing: An Underestimated Threat (ACM CCS, 2016)](http://eprints.lancs.ac.uk/85017/1/ccs16.pdf)

- [19] Stealing controlled password data for authentication - attack with semantic pattern analysis: [On the semantic patterns of passwords and their security impact (NDSS, 2014)](https://www.researchgate.net/profile/Christopher_Collins5/publication/269196925_On_the_Semantic_Patterns_of_Passwords_and_their_Security_Impact/links/589299aa92851cda256a3638/On-the-Semantic-Patterns-of-Passwords-and-their-Security-Impact.pdf)

- [20] Stealing controlled password data for authentication - protect with modeling password guessability: [Fast, Lean, and Accurate: Modeling Password Guessability Using Neural Networks (USENIX, 2016)](https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_melicher.pdf)

_ _ _
### Code source

|Related paper         | Code resource          | Introduction |
|:-------------|:------------------|:------|
|[2] |[ProcHarvester](https://github.com/iaik/procharvester)  |This is the Proof-of-Concept implementation of ProcHarvester - a tool fully automated analysis of Procfs side-channel leaks on Android. |
|[7] |[Model extraction attacks on Machine-Learning-as-a-Service platforms](https://github.com/ftramer/Steal-ML)  |Python implementation of extraction attacks against Machine Learning models including utilized datasets |
|[9] |[Model-Inversion-Attack](https://github.com/yashkant/Model-Inversion-Attack) |A TensorFlow Implementation of the Model Inversion Attack |
|[11] |[Membership Inference Attack](https://github.com/csong27/membership-inference) |Python code for Membership Inference Attack against Machine Learning Models |
|[12] |[Membership Privacy using Adversarial Regularization](https://github.com/SPIN-UMass/ML-Privacy-Regulization) |Python code for Machine Learning with Membership Privacy using Adversarial Regularization with dataset usage |


_ _ _
### Dataset sources used by attacks

_ _ _
#### Stealing controlled user activities information
|Related paper         | Data source          | Introduction|
|:-------------|:------------------|:------|
|[1]       |[Unlock Pattern](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7546515) |Experimental dataset for unlock pattern inference attack enumerated in Appendix of paper [1]|
|[1][2][3] |[Google Paly](https://play.google.com/store)  |Offical app store for the Android operating system |
|[3]       |[Alexa Top Website](https://www.alexa.com/topsites)      |List of top 500 global websites |
|[3]       |[Moz Top Website](https://moz.com/top500)          |List of the top 500 registered domains (∗.example.com) ranked by the number of linking root domains |
|[6]       |[MPU6500 Sensor](https://www.invensense.com/wp-content/uploads/2015/02/MPU-6500-Datasheet2.pdf)  |MPU-6500 Product Specification including Gyroscope and Accelerometer sensor |


_ _ _
#### Stealing controlled ML model related information
|Related paper         | Data source          | Introduction|
|:-------------|:------------------|:------|
|[7][9] |[GSShappiness](https://github.com/ftramer/Steal-ML/blob/master/data/GSShappiness.csv) |Dataset used for model extraction taken from GSS survey|
|[7] |[steak](https://github.com/ftramer/Steal-ML/blob/master/data/steak.csv) |Dataset used for model extraction taken from Steak survey |
|[7][11] |Adult(Income)](https://archive.ics.uci.edu/ml/datasets/Adult) |Predict whether income exceeds $50K/yr based on census data. Also known as "Census Income" dataset. |
|[7][8] |[Iris](https://archive.ics.uci.edu/ml/datasets/Iris) |A best known database in the pattern recognition literature. |
|[7] |[Optical Recognition of Handwritten Digits Data Set](https://archive.ics.uci.edu/ml/datasets/Optical+Recognition+of+Handwritten+Digits) |Normalized bitmaps of handwritten digits from a preprinted form |
|[7] |[Breast Cancer Wisconsin (Original) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Original%29) |Original Wisconsin Breast Cancer Database |
|[7] |[Mushroom Data Set](https://archive.ics.uci.edu/ml/datasets/Mushroom) |Mushrooms described in terms of physical characteristics; classification: poisonous or edible |
|[7][8] | [Diabetes](https://archive.ics.uci.edu/ml/datasets/Diabetes) |Diabetes patient records were obtained from two sources: an automatic electronic recording device and paper records. |
|[8] |[Geographical Original of Music Data Set](https://archive.ics.uci.edu/ml/datasets/Geographical+Original+of+Music) |Instances in this dataset contain audio features extracted from 1059 wave files. |
|[8] |[UJIIndoorLoc Data Set](https://archive.ics.uci.edu/ml/datasets/UJIIndoorLoc) |A Multi-Building Multi-Floor indoor localization database to test Indoor Positioning System that rely on WLAN/WiFi fingerprint.|
|[8] |[Madelon Data Set](https://archive.ics.uci.edu/ml/datasets/Madelon) |An artificial dataset, which was part of the NIPS 2003 feature selection challenge. |
|[8] |[Bank Marketing Data Set](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing) |Related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe a term deposit (variable y). |
|[9] |[FiveThirtyEight](https://fivethirtyeight.com/features/how-americans-like-their-steak/)  |Sharing the data and code behind some of our articles and graphics. |
|[10][11] |[MNIST](http://yann.lecun.com/exdb/mnist/) |The benchmark dataset of choice in several deep learning applications. It consists of handwritten grayscale images of digits ranging from 0 to 9. Each image is of 32 × 32 pixels and centered. |
|[10] |[AT&T dataset of faces](https://www.kaggle.com/sivarajh/olivetti-faces) |a.k.a. Olivetti dataset of faces. Consists of grayscale images of faces of several persons taken in different positions. |
|[11][12] |[CIFAR](https://www.cs.toronto.edu/~kriz/cifar.html) | CIFAR-10 and CIFAR-100 are benchmark datasets
used to evaluate image recognition algorithms |
|[11][12] |[Purchase](https://www.kaggle.com/c/acquire-valued-shoppers-challenge/data) | Acquire aalued shoppers: Predict which shoppers will become repeat buyers. This data captures the process of offering incentives (a.k.a. coupons) to a large number of customers and forecasting those who will become loyal to the product. |
|[11] |[Foursquare dataset](https://sites.google.com/site/yangdingqi/home/foursquare-dataset) |Set of mobile users’ location “check-ins” in the Foursquare social network, restricted to the Bangkok area and collected from April 2012 to September 2013 |
|[11][12] |[Texas hospital stays](https://www.dshs.texas.gov/THCIC/Hospitals/Download.shtm) |This dataset is based on the Hospital Discharge Data public use files with information about inpatients stays in several health facilities,8 released by the Texas Department of State Health Services from 2006 to 2009. |
|[13] |[Criteo Kaggle](https://www.kaggle.com/c/criteo-display-ad-challenge) |Display Advertising Challenge: the goal of this challenge is to benchmark the most accurate ML algorithms for click-through rate (CTR) estimation. |
|[13] |[Criteo Full](http://labs.criteo.com/2015/03/criteo-releases-its-new-dataset/) |A new dataset which is an extended version of the Kaggle click prediction dataset. |
|[13] |[MovieLens](https://grouplens.org/datasets/movielens/) |Available rating data sets from the MovieLens web site (http://movielens.org). The data sets were collected over various periods of time. |

_ _ _
#### Stealing controlled authentication inforamtion
|Related paper         | Dataset          | Introduction|
| -------------------- |:----------------:| --------:|
|[5]|Synthetic obfuscation C code|5 obfuscating transformations apply to each of 4608 synthetic C programs with security check. Totally, 23,040 synthetic obfuscation C programs are included in this dataset.|
|[14]|Sythetic network graph|A simple graph represented by four main node patterns: “center of a star”, “edge of a star”, “bridge nodes” (connecting stars/cliques), and “clique nodes”.|



[back](https://github.com/skyInGitHub/Machine-Learning-Based-Cyber-Attacks-Targeting-on-Controlled-Information-A-Survey)
