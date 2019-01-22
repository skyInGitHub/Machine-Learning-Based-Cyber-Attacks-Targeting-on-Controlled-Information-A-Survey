## Stealing controlled user activities information

### ML-based Stealing Attack

***
<p> According to utilized kernel data and sensor data, controlled user activities information were stolen with timing analysis and frequency analysis. For the attack using kernel data, we review the attack utilizing the interrupt sources like procfs and OS-level information like memory, network, and file system information. The sensor information can reveal the controlled user activity information indirectly, i.e. acoustic and magnetic data.</p>

<p align="center"><img width="725" alt="attack_activity" src="https://user-images.githubusercontent.com/13388819/51515178-cdd07900-1e66-11e9-92d4-3f36e5510d29.png"></p> 
<p align="center">Fig. The ML-based Stealing Attack Against User Activities Information</p>


### Data source

***


|Related paper         | Data source          | Introduction|
|:-------------|:------------------|:------|
|[1]       |[Unlock Pattern](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7546515) |Experimental dataset for unlock pattern inference attack enumerated in Appendix of paper [1]|
|[1][2][3] |[Google Paly](https://play.google.com/store)  |Offical app store for the Android operating system |
|[3]       |[Alexa Top Website](https://www.alexa.com/topsites)      |List of top 500 global websites |
|[3]       |[Moz Top Website](https://moz.com/top500)          |List of the top 500 registered domains (∗.example.com) ranked by the number of linking root domains |
|[6]       |[MPU6500 Sensor](https://www.invensense.com/wp-content/uploads/2015/02/MPU-6500-Datasheet2.pdf)  |MPU-6500 Product Specification including Gyroscope and Accelerometer sensor |



### More information on the data source


***


|Data source         | Release by whom          | Sample data |
|:-------------|:------------------|:------|
|[Google Play](https://play.google.com/store?hl=en) |Google Technical company  |[Android Apps](https://play.google.com/store/apps?hl=en) |
|[MPU6500 Sensor](https://www.invensense.com/wp-content/uploads/2015/02/MPU-6500-Datasheet2.pdf) |InvenSense | [Gyroscope & Accelerometer Datasheet](https://www.invensense.com/wp-content/uploads/2015/02/MPU-6500-Datasheet2.pdf) |


### Related tools

***




|Tool         | Release by whom          | Tip |
|:-------------|:------------------|:------|
|[monkeyrunner](https://developer.android.com/studio/test/monkeyrunner/): Test applications and devices at the functional/framework level |[Android Developers](https://developer.android.com/studio/intro/) |[Mobile App Testing Tutorial for beginners android](https://www.youtube.com/watch?v=mTIdoDEuXrM&t=2s) |
|[ProcHarvester](https://github.com/IAIK/ProcHarvester): Analyze the procfs on Android-based devices for possible information leaks |Spreitzer et al |[README](https://github.com/IAIK/ProcHarvester/blob/master/README.md) |
|[Cycript](http://www.cycript.org/): Explore and modify running applications |Jay Freeman (saurik) |[How to use?](http://www.cycript.org/manual/) |
|[WEKA](https://www.cs.waikato.ac.nz/ml/weka/): A collection of machine learning algorithms for data mining tasks |University of Waikato | [How to run?](https://machinelearningmastery.com/how-to-run-your-first-classifier-in-weka/) |



[back](https://github.com/skyInGitHub/Machine-Learning-Based-Cyber-Attacks-Targeting-on-Controlled-Information-A-Survey)
