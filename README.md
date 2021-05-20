# Abstract 

## Background  

In critically ill infants, the position of a peripherally inserted central catheter (PICC) must be confirmed frequently, as the tip may move from its original position and run the risk of hyperosmolar vascular damage or extravasation into surrounding spaces. Automated detection of PICC tip position holds great promise for alerting bedside clinicians to non-central PICCs.  

## Objectives  

This research seeks to use natural language processing (NLP) and supervised machine learning (ML) techniques to predict PICC tip position based primarily on text analysis of radiograph reports from infants with an upper extremity PICC. 

## Methods  

Radiographs containing a PICC line in infants under 6 months old were manually classified into 12 anatomical locations based on the radiologist’s textual report of the PICC line’s tip. After categorization, we performed a 70/30 train/test split and benchmarked the performance of 7 different (neural network, support vector machine, naïve bayes, decision tree, random forest, AdaBoost, K-nearest neighbors) supervised ML algorithms. After optimization, we calculated accuracy, precision, and recall of each algorithm’s ability to correctly categorize the stated location of the PICC tip. 

## Results  

17,337 radiographs met criteria for inclusion and were labeled manually. Interrater agreement was 99.1%. Support vector machines and neural networks yielded accuracies as high as 98% in identifying PICC tips in central versus non-central position (binary outcome) and accuracies as high as 95% when attempting to categorize the individual anatomical location (12-category outcome).  

## Conclusion  

Our study shows that ML classifiers can automatically extract the anatomical location of PICC tips from radiology reports. Two ML classifiers, support vector machine (SVM) and a neural network, obtained top accuracies in both binary and multiple category predictions. Implementing these algorithms in a neonatal intensive care unit as a clinical decision support system may help clinicians address PICC line position. 

Keywords: Supervised Machine Learning, Natural language processing, Clinical Decision Support System, Radiology information systems, Patient Safety 
