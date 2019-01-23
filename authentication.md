## Stealing controlled authentication information


***
### ML-based Stealing Attack

<p>The controlled authentication information mainly contains keystroke data, secret keys and password data. As shown in Fig 4, classification models or probabilistic models are trained to steal the controlled authentication information. Leveraging the acceleration, acoustic and video information, we review the attack stealing these keystroke information. We also investigate the attack stealing controlled secret key information via analyzing the state of targeted cache set. Moreover, we study the password guessing attack by analyzing the password patterns with ML techniques.</p>

<p align="center"><img width="725" alt="attack_authen" src="https://user-images.githubusercontent.com/13388819/51515290-33246a00-1e67-11e9-99fb-8fe2a1b99609.png"></p> 
<p align="center">Fig 4. The ML-based Stealing Attack Against Authentication Information</p>



***
### Data source


|Related paper         | Data source          | Introduction|
|:-------------|:------------------|:------|
|[14]       |Acceleration dataset | The acceleration data are processed to extract the data points relevant to movements between keystrokes |
|[18]       |[Dodonew](https://raidforums.com/Thread-Dodonew-Database-Leaked-Download)      |Data was obtained from the Chinese website known as Dodonew.com and contained 16M accounts. The data is plaintext. |
|[18]       |[CSDN leaked password dataset](https://gist.github.com/cpylua/2708012)          |CSDN - web services for programmer - leaked passwords summary |
|[18][19]   |[Rockyou](https://wiki.skullsecurity.org/Passwords)  |Rockyou leaked passwords dataset |
|[18]       |[Rootkit](https://thehackernews.com/2011/02/rootkitcom-database-leaked-by-anonymous.html) |Rootkit.com database leaked by Anonymous Hackers |
|[18]       |[Yahoo Password Frequency Corpus](https://figshare.com/articles/Yahoo_Password_Frequency_Corpus/2057937) |This dataset includes sanitized password frequency lists collected from Yahoo in May 2011. |
|[18][20]   |[000webhost](http://www.forbes.com/sites/thomasbrewster/2015/10/28/000webhost-database-leak/) |13 Million Passwords Appear To Have Leaked From This Free Web Host |
|[20]       |PGS Training set |Password Guessability Service (PGS) used by a [research work](https://www.usenix.org/system/files/conference/usenixsecurity15/sec15-paper-ur.pdf). This set totals 33 million passwords and 5.9 million natural-language words.|
|[20]       |1class8  |Passwords collected for a [research study](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6234434) which passwords are longer than eight characters. |
|[20]       |1class16 |Passwords collected for a [research study](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6234434) which passwords are longer than sixteen characters. |
|[20]       |3class12 |Passwords collected for a [research study](https://dl.acm.org/citation.cfm?id=2557377) which passwords must contain at least three character classes (uppercase letters, lowercase letters, symbols, digits) and be at least twelve characters long. |
|[20]       |4class8  |Passwords collected for a [research study](https://www.cylab.cmu.edu/_files/pdfs/tech_reports/CMUCyLab13013.pdf) which passwords must contain all four character classes and be at least eight characters long. |


***
### More information on the data source

|Data source         | Release by whom          | Sample data |
|:-------------|:------------------|:------|
|[SkullSecurity - Passwords](https://wiki.skullsecurity.org/Passwords) |skullsecurity.org  |hotmail leaked password |
|[Yahoo Password Frequency Corpus](https://figshare.com/articles/Yahoo_Password_Frequency_Corpus/2057937) | Joseph Bonneau | yahoo-activity-login-<30d |



***
### Code source


|Related paper         | Code resource          | Introduction |
|:-------------|:------------------|:------|
|[20] |[neural_network_cracking](https://github.com/cupslab/neural_network_cracking)  |Neural Network with passwords. This Python program uses a neural network to guess passwords. This is software used and maintained by students for a research project and likely will have many bugs and issues. |




[back](index.md)

