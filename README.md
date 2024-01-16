# Epilepsy-Detection
This dataset was generated with a motive to build pre-dictive epilepsy diagnosis model and publically avail-able since 2020. It was generated on a similar acqui-sition and settings i.e., sampling frequency, bandpassﬁltering and number of signals and time duration asof University of Bonn. It has overcome the limitationsfaced by University of Bonn dataset such as diﬀerentEEG recording (inter-cranial and scalp) for healthy andepileptic patients [11]. All the data were taken exclu-sively using surface EEG electrodes for 15 healthy andepileptic patients.

Reference : https://www.researchgate.net/publication/353654102_Open_and_free_EEG_datasets_for_epilepsy_diagnosis

The data consisting of EEG signal values across multiple text files is loaded into a Pandas dataframe.The file names are extracted and stored in the ‘FileName‘ column while the signal values are stored in the ‘Value‘ column. Preprocessing steps involve:
1 Removing everything after the underscore from file names to generalize them
2 Converting the values to float datatype.
3 Grouping by file name and aggregating values into lists
4 Adding a label column indicating 1 for epileptic (E) patients and 0 for healthy (H) based on file name.
This project presents with 4 models that are used to train the dataset and prediction. Each prediction Multiple supervised learning models are trained and evaluated. These models are namely Logistic Regression, SVC, Random Forest and Ensemble Learning.

ALong with that we wrote a review paper for this too.
