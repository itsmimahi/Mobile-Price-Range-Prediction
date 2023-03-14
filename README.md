## Mobile Price Range Prediction (Supervised ML - Classification)


### Problem Statement:
In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is.

![mobile price range](https://user-images.githubusercontent.com/105766113/224974492-79fc0932-548c-498b-98ba-6663c6cac727.jpg)



### Data Description:

* Battery_power - Total energy a battery can store in one time measured in mAh
* Blue - Has bluetooth or not
* Clock_speed - speed at which microprocessor executes instructions
* Dual_sim - Has dual sim support or not
* Fc - Front Camera mega pixels
* Four_g - Has 4G or not
* Int_memory - Internal Memory in Gigabytes
* M_dep - Mobile Depth in cm
* Mobile_wt - Weight of mobile phone
* N_cores - Number of cores of processor
* Pc - Primary Camera mega pixels
* Px_height - Pixel Resolution Height
* Px_width - Pixel Resolution Width
* Ram - Random Access Memory in Mega Bytes
* Sc_h - Screen Height of mobile in cm
* Sc_w - Screen Width of mobile in cm
* Talk_time - longest time that a single battery charge will last when you are
* Three_g - Has 3G or not
* Touch_screen - Has touch screen or not
* Wifi - Has wifi or not
* Price_range - This is the target variable with value of
* 0 (low cost)

* 1 (medium cost)

* 2 (high cost)

* 3 (very high cost)

### Challenges:


   1. Data Cleaning
   2. Data Analysis
   3. Classifying Mobile Price Range 
	 
### Model Summary :

Proceed with reading the data, and then perform data analysis. The practice of examining data using analytical or statistical methods in order to identify meaningful information is known as data analysis. After data analysis, we will find out the data distribution and data types. We will train multiple classification algorithms to predict the output. We will also compare the outputs.


### Conclusion :

 ![image](https://user-images.githubusercontent.com/105766113/224977396-3b185c98-275d-4213-b423-024ae20f5e50.png)

* Implemented various classification algorithm, out of which SVM(Support Vector machine) algorithm gave the best performance after hyper parameter tuning with 99% train accuracy and 97 % test accuracy .

* XG Boost is the second best model which gave good performance after hyper parameter tuning with  100% train accuracy and 91% test accuracy score.

* K-Nearest Neighbour perform very worst.



### Certificate-

![Mobile price range prediction](https://user-images.githubusercontent.com/105766113/224979929-fc85680e-1343-4883-a3eb-a6e9f7fad39f.png)

