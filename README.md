# Raman-Spectra-Data

In this repository, we collected the datasets used for the experimental computations of our paper **"An Integrated Computational Pipeline for Machine Learning-Driven Diagnosis based on Raman Spectra of saliva samples"**. For the Covid dataset saliva samples, health records, and clinical data were acquired at IRCCS Fondazione Don Carlo Gnocchi ONLUS, Santa Maria Nascente Hospital, Milano, Italy, and Centro Spalenza Hospital, Rovato, Italy between 16th April 2020 to July 2020 (Further information regarding the acquisition protocol and the dataset are available in the paper). In the other case, PD patients and CTRL were recruited after accessing IRCCS Fondazione Don Carlo Gnocchi, in Milan (Italy) between October 2017 and June 2020. AD participants were recruited at Istituto Auxologico Italiano, IRCCS Department of Neurology and Laboratory of Neuroscience (Further information regarding the acquisition protocol and the dataset are available in the paper).
For both datasets, the spectra were acquired at the Labion laboratory at IRCCS Fondazione Don Carlo Gnocchi ONLUS. 

### Data
The two datasets are contained in two folders: **covid_dataset** and **pd_ad_dataset**.
Each folder contains a csv called **user_information**, with the following information:

 - user_id -> patient's unique identifier
 - category -> category of the patients
 - label -> label associated to the category

The data are contained in a single folder for each patient. Each patient's folder contains the following files:

- spectra.csv -> file representing all the spectra of the patient (it is worth to recalling that an average of 25 samples have been collected for each patient)
- raman_shift.csv -> file representing the raman shift of the spectra for the patient
- user_information.csv -> user_id, category and label of the patient

The same structure is replicated for both datasets.

For any **information** it is possible to contact:

- Marco Piazza (marco.piazza@unimib.it)
- Alice Gualerzi (agualerzi@dongnocchi.it)
