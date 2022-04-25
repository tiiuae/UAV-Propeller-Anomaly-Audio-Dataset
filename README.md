# UAV Propeller Anomaly Audio Data Set

This data set is released with the publication **[REAL-WORLD ON-BOARD UAV AUDIO DATA SET FOR PROPELLER ANOMALIES](https://github.com/tiiuae/UAV-Propeller-Anomaly-Audio-Dataset/blob/main/REAL-WORLD%20ON-BOARD%20UAV%20AUDIO%20DATA%20SET%20FOR%20PROPELLER%20ANOMALIES.pdf)**, which is accepted at [ICASSP 2022](https://2022.ieeeicassp.org/).

Propeller are an important subsystem of a UAV (also known as a drone). Audio data can be used to detect propeller damage, which improves the resilience and safety of the UAV system.

The audio data set consists of audio recordings of in-door missions, which were captured from take-off to landing. The number of broken propellers is varied from 0 to 4, inclusive. The data set contains samples of each propeller configuration. 

## Details of the Data Set

The audio data is divided into 4 classes - Normal, 1-Broken, 2-Broken, 3_4-Broken Propellers. Each class directory contains sub-directory for each configuration. Each configuration directory is divided into 4 different mission types: square or figure eight (f8), clockwise (cw)  or counter-clockwise (ccw). Each audio recording that belongs to a specific mission type is stored within these directories. 

The configuration directories denote the positions of broken (1) and intact (0) propellers. The propeller position were labelled 1,2,3,4, and for example a 
configuration 0011 would have intact propellers in positions 1,2 and broken propellers in 3 and 4, making this configuration a member of 2-broken class.

