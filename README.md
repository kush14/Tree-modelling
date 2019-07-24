# Tree-modelling

Parkinson’s Disease (PD) is a degenerative neurological disorder marked by decreased dopamine levels in the brain. It manifests itself through a deterioration of movement, including the presence of tremors and stiffness. There is commonly a marked effect on speech, including dysarthria (difficulty articulating sounds), hypophonia (lowered volume), and monotone (reduced pitch range). Additionally, cognitive impairments and changes in mood can occur, and risk of dementia is increased.

Traditional diagnosis of Parkinson’s Disease involves a clinician taking a neurological history of the patient and observing motor skills in various situations. Since there is no definitive laboratory test to diagnose PD, diagnosis is often difficult, particularly in the early stages when motor effects are not yet severe. Monitoring progression of the disease over time requires repeated clinic visits by the patient. An effective screening process, particularly one that doesn’t require a clinic visit, would be beneficial. Since PD patients exhibit characteristic vocal features, voice recordings are a useful and non-invasive tool for diagnosis. If machine learning algorithms could be applied to a voice recording dataset to accurately diagnosis PD, this would be an effective screening step prior to an appointment with a clinician.

The data & attributes information for this project is available at https://archive.ics.uci.edu/ml/machine-learning-databases/parkinsons/The data consists of those diagnosed with Parkinson Disease and those who do not.


Steps followed for this project :-
1.	Loading the dataset
2.	EDA on raw data to get a feel of the data in terms of number of structure of the file, number of attributes, types of attributes and a general idea of likely challenges in the dataset.
3.	Using univariate & bivariate analysis to check the individual attributes for their basic statistic such as central values, spread, tails etc.
4.	Splitting the dataset into training and test set in the ratio of 70:30 
5.	Creating the model using “entropy” method of reducing the entropy and fit it to training data. 
6.	Testing the model on test data and finding out the accuracy achieved. Also, showing various metrics such as accuracy and confusion matrix. 
7.	Using regularization parameters/hyperparamter tuning of max_depth, min_sample_leaf to recreate the model and assesing how accuracy changes.
8.	Finally, implementing Random Forest to check for improvement in accuracy.
