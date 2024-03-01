Predictive Maintenance task comparison using the SDME-P C++ Library on a Microcontroller
============

Optional project of the [Streaming Data Analytics](http://emanueledellavalle.org/teaching/streaming-data-analytics-2022-23/) course provided by [Politecnico di Milano](https://www11.ceda.polimi.it/schedaincarico/schedaincarico/controller/scheda_pubblica/SchedaPublic.do?&evn_default=evento&c_classe=811164&polij_device_category=DESKTOP&__pj0=0&__pj1=1b82965d3c68857e2087d3f3b98a9e40).

Student: **[To be assigned]**

The project will use the C++ library SDME-P1 on an Arduino Portenta H7 simulator2 or a physical Arduino Portenta H73 to solve a classification task. The aim is to train several models on SDME-P on an Arduino Portenta H7 simulator/physical device and to compare their performance w.r.t. the relative models trained on River and MOA.

More in practice, for the AI4I 2020 Predictive Maintenance Dataset4, you have to train and test the KNN, SAM KNN, HT, ARF, and SRP models in SDME-P on an Arduino Portenta H7 simulator/physical device, and in MOA and River on your Pc, to predict if there is a failure or not.
About the data ingestion to the Arduino, follow the way it was done in the master thesis.

You should use the following metrics to compare the results:
- Accuracy
- Balanced Accuracy
- Geometric Mean
- CohenKappa

Moreover, you should keep track of the Time, CPU and RAM usage to test and train the models. The project must also include some plots to better show the results.

You are required to create a .c file with the code for testing the models in SDME-P, a .sh or .java file with the code for testing the models in MOA, and a .py or .ipynb file for testing the models in River. All the results must be collected in a .ipynb file to be compared. You must include comments for the principal instructions, and you are allowed to import external py modules. Additionally, ensure you thoroughly comment on the comparison results using various plots associated with the different metrics. Finally, again, in the final .ipynb file, briefly discuss the conclusions that can be drawn from the experiment.

If the Arduino Portenta H7 simulator is unavailable, we will give you a physical Arduino Portenta H7. Moreover, we will also give you the SDME-P code after signing an NDA disclosure.
![image](https://github.com/Streaming-Data-Analytics/2023-2024_Motus-SDMEP-comparisonPdM/assets/82282137/96e382bc-083c-4f8a-a9df-04b1b0b47ce4)


## Note for Students

* Clone the created repository offline;
* Add your name and surname into the Readme file;
* Make any changes to your repository, according to the specific assignment;
* Add a `requirement.txt` file for code reproducibility and instructions on how to replicate the results;
* Add an open-source license, e.g., Apache 2.0;
* Commit your changes to your local repository;
* Push your changes to your online repository.
