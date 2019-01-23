## Stealing controlled ML model related information

***
### ML-based Stealing Attack

<p>Leveraging the query inputs and outputs, model description can be stolen by equation-solving, patch-finding and linear least square methods, while training samples can be stolen by model inversion attack, the GAN attack, and membership inference attack.</p>

<p align="center"><img width="725" alt="attack_ml" src="https://user-images.githubusercontent.com/13388819/51515245-040df880-1e67-11e9-9ac6-a25db9fac554.png"></p> 
<p align="center">Fig 3. The ML-based Stealing Attack Against ML Model Related Information</p>


***
### Data source



|Related paper         | Data source          | Introduction|
|:-------------|:------------------|:------|
|[7][9] |[GSShappiness](https://github.com/ftramer/Steal-ML/blob/master/data/GSShappiness.csv) |Dataset used for model extraction taken from GSS survey|
|[7] |[steak](https://github.com/ftramer/Steal-ML/blob/master/data/steak.csv) |Dataset used for model extraction taken from Steak survey |
|[7][11] |[Adult(Income)](https://archive.ics.uci.edu/ml/datasets/Adult) |Predict whether income exceeds $50K/yr based on census data. Also known as "Census Income" dataset. |
|[7][8] |[Iris](https://archive.ics.uci.edu/ml/datasets/Iris) |A best known database in the pattern recognition literature. |
|[7] |[Optical Recognition of Handwritten Digits Data Set](https://archive.ics.uci.edu/ml/datasets/Optical+Recognition+of+Handwritten+Digits) |Normalized bitmaps of handwritten digits from a preprinted form |
|[7] |[Breast Cancer Wisconsin (Original)](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Original%29) |Original Wisconsin Breast Cancer Database |
|[7] |[Mushroom](https://archive.ics.uci.edu/ml/datasets/Mushroom) |Mushrooms described in terms of physical characteristics; classification: poisonous or edible |
|[7][8] |[Diabetes](https://archive.ics.uci.edu/ml/datasets/Diabetes) |Diabetes patient records were obtained from two sources: an automatic electronic recording device and paper records. |
|[8] |[Geographical Original of Music](https://archive.ics.uci.edu/ml/datasets/Geographical+Original+of+Music) |Instances in this dataset contain audio features extracted from 1059 wave files. |
|[8] |[UJIIndoorLoc](https://archive.ics.uci.edu/ml/datasets/UJIIndoorLoc) |A Multi-Building Multi-Floor indoor localization database to test Indoor Positioning System that rely on WLAN/WiFi fingerprint.|
|[8] |[Madelon](https://archive.ics.uci.edu/ml/datasets/Madelon) |An artificial dataset, which was part of the NIPS 2003 feature selection challenge. |
|[8] |[Bank Marketing](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing) |Related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe a term deposit (variable y). |
|[9] |[FiveThirtyEight](https://fivethirtyeight.com/features/how-americans-like-their-steak/)  |Sharing the data and code behind some of our articles and graphics. |
|[10][11] |[MNIST](http://yann.lecun.com/exdb/mnist/) |The benchmark dataset of choice in several deep learning applications. It consists of handwritten grayscale images of digits ranging from 0 to 9. Each image is of 32 × 32 pixels and centered. |
|[10] |[AT&T dataset of faces](https://www.kaggle.com/sivarajh/olivetti-faces) |a.k.a. Olivetti dataset of faces. Consists of grayscale images of faces of several persons taken in different positions. |
|[11][12] |[CIFAR](https://www.cs.toronto.edu/~kriz/cifar.html) | CIFAR-10 and CIFAR-100 are benchmark datasets used to evaluate image recognition algorithms |
|[11][12] |[Purchase](https://www.kaggle.com/c/acquire-valued-shoppers-challenge/data) | Acquire aalued shoppers: Predict which shoppers will become repeat buyers. This data captures the process of offering incentives (a.k.a. coupons) to a large number of customers and forecasting those who will become loyal to the product. |
|[11] |[Foursquare dataset](https://sites.google.com/site/yangdingqi/home/foursquare-dataset) |Set of mobile users’ location “check-ins” in the Foursquare social network, restricted to the Bangkok area and collected from April 2012 to September 2013 |
|[11][12] |[Texas hospital stays](https://www.dshs.texas.gov/THCIC/Hospitals/Download.shtm) |This dataset is based on the Hospital Discharge Data public use files with information about inpatients stays in several health facilities,8 released by the Texas Department of State Health Services from 2006 to 2009. |
|[13] |[Criteo Kaggle](https://www.kaggle.com/c/criteo-display-ad-challenge) |Display Advertising Challenge: the goal of this challenge is to benchmark the most accurate ML algorithms for click-through rate (CTR) estimation. |
|[13] |[Criteo Full](http://labs.criteo.com/2015/03/criteo-releases-its-new-dataset/) |A new dataset which is an extended version of the Kaggle click prediction dataset. |
|[13] |[MovieLens](https://grouplens.org/datasets/movielens/) |Available rating data sets from the MovieLens web site (http://movielens.org). The data sets were collected over various periods of time. |




***
### More information on the data source



|Data source         | Release by whom          | Sample data |
|:-------------|:------------------|:------|
|[UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php) |University of Massachusetts Amherst  |[UCI Machine Learning Repository: Data Sets](https://archive.ics.uci.edu/ml/datasets.html) |
|[FiveThirtyEight](https://data.fivethirtyeight.com/) |N/A | [steak-risk-survey.csv](https://fivethirtyeight.com/features/how-americans-like-their-steak/) |
|[The Database of Faces](https://www.cl.cam.ac.uk/research/dtg/attarchive/facedatabase.html) |AT&T Laboratories Cambridge | The ORL Database of Faces |
|[Foursquare dataset](https://sites.google.com/site/yangdingqi/home/foursquare-dataset) |Dingqi Yang |NYC Restaurant Rich Dataset (Check-ins, Tips, Tags) |
|[Criteo Dataset Archives](http://labs.criteo.com/category/dataset/) |CriteoLabs |Google experiments with Tensorflow on Criteo Dataset |
|[Grouplens Dataset](https://grouplens.org/) |GroupLens |[WikiLens](https://grouplens.org/) |




***
### Code source


|Related paper         | Code resource          | Introduction |
|:-------------|:------------------|:------|
|[7] |[Model extraction attacks on Machine-Learning-as-a-Service platforms](https://github.com/ftramer/Steal-ML)  |Python implementation of extraction attacks against Machine Learning models including utilized datasets |
|[9] |[Model-Inversion-Attack](https://github.com/yashkant/Model-Inversion-Attack) |A TensorFlow Implementation of the Model Inversion Attack |
|[11] |[Membership Inference Attack](https://github.com/csong27/membership-inference) |Python code for Membership Inference Attack against Machine Learning Models |
|[12] |[Membership Privacy using Adversarial Regularization](https://github.com/SPIN-UMass/ML-Privacy-Regulization) |Python code for Machine Learning with Membership Privacy using Adversarial Regularization with dataset usage |



***
### Related tools



|Tool         | Release by whom          | Tip |
|:-------------|:------------------|:------|
|[Amazon SageMaker](https://aws.amazon.com/sagemaker/): ML services - Build, train, and deploy machine learning models fast |Amazon Company |[How it works?](https://docs.aws.amazon.com/sagemaker/latest/dg/how-it-works.html) |
|[BigML](https://bigml.com/): A ML service offers an easy-to-use interface for user to import user's data and get predictions out of it  |BigML Inc. |[How it works?](https://bigml.com/how_it_works) |
|[CLOUD MACHINE LEARNING ENGINE](https://cloud.google.com/ml-engine/): Build superior models and deploy them into production |Google Cloud |[How to use?](https://cloud.google.com/ml-engine/docs/tensorflow/how-tos) |




[back](index.md)
