# PCOS prediction in women using ML models

![techstack1](https://camo.githubusercontent.com/0562f16a4ae7e35dae6087bf8b7805fb7e664a9e7e20ae6d163d94e56b94f32d/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f707974686f6e2d3336373041303f7374796c653d666f722d7468652d6261646765266c6f676f3d707974686f6e266c6f676f436f6c6f723d666664643534)
![techstack2](https://camo.githubusercontent.com/4487725c400789fceb3e540abc5b7cabe5dee39b7e4c91e1e906fccd26416cbd/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50616e6461732d3243324437323f7374796c653d666f722d7468652d6261646765266c6f676f3d70616e646173266c6f676f436f6c6f723d7768697465)
![techstack3](https://camo.githubusercontent.com/6eca86d3f9f9e48719c4958f16f78d98197b34f8928976e7b4c241d906f08738/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4e756d70792d3737374242343f7374796c653d666f722d7468652d6261646765266c6f676f3d6e756d7079266c6f676f436f6c6f723d7768697465)
![techstack4](https://camo.githubusercontent.com/c484268661eef28f84e4888611778267794c78a0b2df7f16025d3f85f6227225/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f7363696b69745f6c6561726e2d4637393331453f7374796c653d666f722d7468652d6261646765266c6f676f3d7363696b69742d6c6561726e266c6f676f436f6c6f723d7768697465)
![techstack5](https://camo.githubusercontent.com/d102f36336d423527ee41f7c0bc360743b7544bb7304cf129abc3a75bccbeab6/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4a7570797465722d4633373632362e7376673f267374796c653d666f722d7468652d6261646765266c6f676f3d4a757079746572266c6f676f436f6c6f723d7768697465)
![techstack6](https://camo.githubusercontent.com/dd83d4a334eab7ada034c13747d9e2237182826d32e3fda6629740b6e02f18d8/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f6c61622d4639414230303f7374796c653d666f722d7468652d6261646765266c6f676f3d676f6f676c65636f6c616226636f6c6f723d353235323532)


## Overview of the problem statement

Polycystic ovary syndrome (PCOS) as stated by (Polycystic Ovary Syndrome (PCOS), 2022) is a disorder occurring in women who are most commonly in their childbearing age in which ovaries produce abnormal levels of male sex hormones namely androgens which otherwise are produced in very small amounts in women. The term polycystic syndrome is termed after its effects on the ovaries, women with PCOS develop small fluid-filled cysts in the ovaries. 

Women with PCOS are prone to other serious health conditions like insulin resistance eventually resulting in weight gain and obesity etc. Therefore, prior detection of the symptoms or detecting the potential for an individual to develop this condition could result in requisite steps towardprevention.

In this report, I have leveraged the potential of predictive analytics and machine learning algorithms to analyze and explore the relationship between the different biometric variables, and have trained different machine learning models to learn the hidden patterns and further have used them for predicting the presence of PCOS in individuals.

## Dataset

The dataset that is used as a part of this project comprises data collected from 10 different hospitals across India. The dataset contains information on all the physical and clinical parameters used to detect the presence of Polycystic ovary syndrome in women. This dataset was downloaded directly from the Kaggle data repository.

## The code and the process

Please check the pdf document above in this repository consisting of the end-to-end entire process.

## Conclusion based on the performance evaluation metrics

Now that I have successfully developed a model with different machine learning algorithms,we can now compare these models based on their performance metrics. 
False negative rate: metric plays a key role in model evaluation when it comes to medical datasets, False negative rate emphasizes on the percentage of samples which are falsely predicted as Negative. 

Here it is observed that both our models Linear regression and Decision Tree Classifier have a False negative rate of 28.30% and 26.41% , research Ferrer-Urbina et al. (2023) shows that the accepted threshold for false negatives is 25% and hence this could prove to be risky especially when working with the medical data, these women who have been falsely detected to not have PCOS are at risk and hence might miss out on necessary treatments for PCOS. Accuracy, Recall and Precision evaluation metrics: The decision tree classifier model performed better on both the other metrics except on the precision metric.




