## Stealing controlled authentication information

### ML-based Stealing Attack

***
<p>The controlled authentication information mainly contains keystroke data, secret keys and password data. As shown in Fig 4, classification models or probabilistic models are trained to steal the controlled authentication information. Leveraging the acceleration, acoustic and video information, we review the attack stealing these keystroke information. We also investigate the attack stealing controlled secret key information via analyzing the state of targeted cache set. Moreover, we study the password guessing attack by analyzing the password patterns with ML techniques.</p>

<p align="center"><img width="725" alt="attack_authen" src="https://user-images.githubusercontent.com/13388819/51515290-33246a00-1e67-11e9-99fb-8fe2a1b99609.png"></p> 
<p align="center">Fig 4. The ML-based Stealing Attack Against Authentication Information</p>


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
|[Amazon SageMaker](https://aws.amazon.com/sagemaker/): ML services - Build, train, and deploy machine learning models fast |Amazon Company |[How it works?](https://docs.aws.amazon.com/sagemaker/latest/dg/how-it-works.html) |
|[BigML](https://bigml.com/): A ML service offers an easy-to-use interface for user to import user's data and get predictions out of it  |BigML Inc. |[How it works?](https://bigml.com/how_it_works) |
|[CLOUD MACHINE LEARNING ENGINE](https://cloud.google.com/ml-engine/): Build superior models and deploy them into production |Google Cloud |[How to use?](https://cloud.google.com/ml-engine/docs/tensorflow/how-tos) |




[back](https://github.com/skyInGitHub/Machine-Learning-Based-Cyber-Attacks-Targeting-on-Controlled-Information-A-Survey)

