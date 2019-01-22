# Machine Learning Based Cyber Attacks Targeting on Controlled Information: A Survey

Everything about the datasets and data sources mentioned in the survey paper "Machine Learning Based Cyber Attacks Targeting on Controlled Information: A Survey".

_ _ _

## Table of contents
* Research articles by areas 
* Data sources used by attacks
  * Stealing controlled user activities information
  * Stealing controlled ML model related information
  * Stealing controlled authentication inforamtion
  
_ _ _

### Research articles by areas
- [1] Stealing controlled user activities using kernel data - attack with timing analysis: [No pardon for the interruption: New inference attacks on android through interrupt timing analysis (S&P, 2016)](https://www.researchgate.net/profile/Zhou_Li24/publication/306304394_No_Pardon_for_the_Interruption_New_Inference_Attacks_on_Android_Through_Interrupt_Timing_Analysis/links/5a57ae3445851529a2edbd18/No-Pardon-for-the-Interruption-New-Inference-Attacks-on-Android-Through-Interrupt-Timing-Analysis.pdf)

- [2] Stealing controlled user activities using kernel data - attack with timing analysis: [ProcHarvester: Fully Automated Analysis of Procfs Side-Channel Leaks on Android (ACM Asia CCS, 2018)](https://rspreitzer.github.io/publications/proc/asiaccs-2018-paper-2.pdf)

- [3] Stealing controlled user activities using kernel data - iOS side-channel attack: [OS-level Side Channels without Procfs: Exploring Cross-App Information Leakage on iOS (NDSS, 2018)](http://web.cse.ohio-state.edu/~zhang.834/papers/ndss18a.pdf) 

- [4] Stealing controlled user activities using kernel data - protect using privacy mechanism: [Mitigating Storage Side Channels Using Statistical Privacy Mechanisms (ACM CCS, 2015)](http://delivery.acm.org/10.1145/2820000/2813645/p1582-xiao.pdf?ip=101.176.75.238&id=2813645&acc=OA&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E8A0A9AC1EB2AB412&__acm__=1548109844_6c1cf52609d70310cf4b692aac1e7a7b)

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
### Dataset sources used by attacks

_ _ _
#### Stealing controlled user activities information
|Related paper         | Dataset          | Introduction |
| -------------------- |:----------------:| --------:|
|[1][2]     | [VERIS community database](http://veriscommunity.net/index.html) | The vocabulary for event recording and incident sharing|
|[1]    | [Hackmageddon](https://www.hackmageddon.com/)      | Information security timelines and statistics  |
|[1] | [Web Hacking Incidents Database](http://projects.webappsec.org/w/page/13246995/Web-Hacking-Incident-Database)|  Recording web hacking incident |
|[3]|[VirusTotal](https://www.virustotal.com/en/faq/)| Analyzing suspicious files and URLs to detect types of malware|
|[3]|[National Software Reference Library (NSRL)](https://www.nist.gov/software-quality-group/national-software-reference-library-nsrl)| Providing a reference data set (RDS) of benign software|
|[3][10]|[Symantec’s Worldwide Intelligence Network Environment (WINE)](https://www.symantec.com/)| Security related data set, including malware, vulnerabilty exploited and so on|
|[17]|[KEIO, WIDE-08 and WIDE-09 traces](http://mawi.wide.ad.jp/mawi/)|Public traffic data repository|
|[10]|[ExploitDB](https://www.exploit-db.com/)|Offensive Security’s Exploit Database Archive|
|[10]|[Microsoft’s Exploitability Index](https://technet.microsoft.com/en-us/security/cc998259.aspx)|Recording exploitability information|

_ _ _
#### Stealing controlled ML model related information
|Related paper         | Dataset          | Introduction|
| -------------------- |:----------------:| --------:|
|[6]| [Open recursive projects](http://openresolverproject.org/)|Open Resolvers pose a significant threat to the global network infrastructure by answering recursive queries for hosts outside of its domain. They are utilized in DNS Amplification attacks and pose a similar threat as those from Smurf attacks commonly seen in the late 1990s. A list of 32 million resolvers that respond to queries in some fashion are collected in this project.|
|[6]|[Verisign. Inc](https://www.verisign.com)|Verisign, Inc. is an American company based in Reston, Virginia, United States that operates a diverse array of network infrastructure, including two of the Internet's thirteen root nameservers, the authoritative registry for the .com, .net, and .name generic top-level domains and the .cc and .tv country-code top-level domains, and the back-end systems for the .jobs, .gov, and .edu top-level domains. Verisign also offers a range of security services, including managed DNS, distributed denial-of-service (DDoS) attack mitigation and cyber-threat reporting.|
|[6]|[Alexa Web Information Service](https://docs.aws.amazon.com/AlexaWebInfoService/latest/index.html)|The Alexa Web Information Service (AWIS) offers a platform for creating innovative Web solutions and services based on Alexa's vast information about web sites, accessible with a web services API. |
|[6][14]|[University of Oregon Route Views Project](http://www.routeviews.org/routeviews/)|The University's Route Views project was originally conceived as a tool for Internet operators to obtain real-time BGP information about the global routing system from the perspectives of several different backbones and locations around the Internet.|
|[6]|[Spoofer project](https://www.caida.org/projects/spoofer/)|The team is developing and supporting open-source software tools to assess and report on the deployment of source address validation (SAV) best anti-spoofing practices|
|[6]|[Zmap](https://github.com/zmap/zmap)|Zmap is a modular, open-source network scanner specifically architected to perform Internet-wide scans and capable of surveying the entire IPv4 address space in under 45 minutes from user space on a single machine, approaching the theoretical maximum speed of gigabit Ethernet.|

_ _ _
#### Stealing controlled authentication inforamtion
|Related paper         | Dataset          | Introduction|
| -------------------- |:----------------:| --------:|
|[5]|Synthetic obfuscation C code|5 obfuscating transformations apply to each of 4608 synthetic C programs with security check. Totally, 23,040 synthetic obfuscation C programs are included in this dataset.|
|[14]|Sythetic network graph|A simple graph represented by four main node patterns: “center of a star”, “edge of a star”, “bridge nodes” (connecting stars/cliques), and “clique nodes”.|



