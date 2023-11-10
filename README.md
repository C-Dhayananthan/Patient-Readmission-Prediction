# Patient-Readmission-Prediction
The dataset comprises 49 columns, encompassing various aspects of patient information, diagnosis reports, and medications.
Raw dataset Diabetes 130-US hospitals for years 1999-2008 Data Set can be found hear. The dataset represents 10 years (1999-2008) of clinical care at 130 US hospitals and integrated delivery networks. It includes over 50 features representing patient and hospital outcomes. Information was extracted from the database for encounters that satisfied the following criteria.
In this dataset, you have 3 different outputs:

* No readmission;
* A readmission in less than 30 days (this situation is not good, because maybe your treatment was not appropriate);
* A readmission in more than 30 days (this one is not so good as well the last one, however, the reason can be the state of the patient.
* In this context, you can see different objective functions for the problem. You can try to figure out situations where the patient will not be readmitted, or if their are going to be readmitted in less than 30 days (because the problem can the the treatment), etc… Make your choice and let's help them creating new approaches for the problem.

## Training and Validation Accuracy:

The machine learning model achieved a training accuracy of 66% and a validation accuracy of 55% for class zero (non-readmission patients). This indicates a moderate level of predictive performance on the provided data.
The overall accuracy of 63% suggests that the model's performance is influenced by the balance between the classes and might need further refinement.

The initial model shows some predictive capability, further refinement and exploration of feature engineering, model selection, and validation strategies are crucial for enhancing the accuracy of this model
