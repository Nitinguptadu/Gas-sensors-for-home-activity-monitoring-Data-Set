# Gas-sensors-for-home-activity-monitoring-Data-Set

kaggle soloution provided by me link https://www.kaggle.com/gauravgawade951999/gas-sensors-for-home-activity-monitoring-data-set/kernels


Abstract: 100 recordings of a sensor array under different conditions in a home setting: background, wine and banana presentations. The array includes 8 MOX gas sensors, and humidity and temperature sensors.  Source:  Creators: Flavia Huerta,Gaurav Gawade Ramon Huerta, University of California San Diego, USA  Donors: Flavia Huerta Ramon Huerta, University of California San Diego, USA (rhuerta â€˜@â€™ ucsd.edu) Thiago Mosqueiro, University of California San Diego, USA (thmosqueiro â€˜@â€™ ucsd.edu) Jordi Fonollosa, Institute for Bioengineering of Catalunya, Spain (jfonollosa â€˜@â€™ ibecbarcelona.eu) Nikolai Rulkov, University of California San Diego, USA ( nrulkov â€˜@â€™ ucsd.edu ) Irene Rodriguez-Lujan, Universidad Autonoma de Madrid, Spain ( Irene.rodriguez â€˜@â€™ uam.es )  Data Set Information:  This dataset has recordings of a gas sensor array composed of 8 MOX gas sensors, and a temperature and humidity sensor. This sensor array was exposed to background home activity while subject to two different stimuli: wine and banana. The responses to banana and wine stimuli were recorded by placing the stimulus close to the sensors. The duration of each stimulation varied from 7min to 2h, with an average duration of 42min. This dataset contains a set of time series from three different conditions: wine, banana and background activity. There are 36 inductions with wine, 33 with banana and 31 recordings of background activity. One possible application is to discriminate among background, wine and banana.  This dataset is composed of two files: HTsensordataset.dat (zipped), where the actual time series are stored, and the HTSensormetadata.dat, where metadata for each induction is stored. Each induction is uniquely identified by an id in both files. Thus, metadata for a particular induction can be easily found by matching columns id from each file.  We also made available python scripts to exemplify how to import, organize and plot our data. The scripts are available on GitHub: https://github.com/gauravgawade951999/gauravgit  For each induction, we include one hour of background activity prior to and after the stimulus presentation. Time series were recorded at one sample per second, with minor variations at some data points due to issues in the wireless communication. For details on which sensors were used and how the time series is organized, see Attribute Information below.



The metadata stored in file HTSensormetadata.dat is divided in the following columns:

id: identification of the induction, to be matched with id in file HTSensordataset.dat;
date: day, month and year when this induction was recorded;
class: what was used to generate this induction (wine, banana or background);
t0: time in hours in which the induction started (represents the time zero in file HTSensordataset.dat);
dt: interval that this induction lasted.
Attribute Information:

The dataset is composed of 100 snippets of time series, each being a single induction or background activity. On total, there are 919438 points. For each induction, the time when the stimulus was presented is set to zero. For the actual time, see column t0 of the metadata file. In file HTSensordataset.dat, each column has a title according to the following

id: identification of the induction, to be matched with id in file HTSensormetadata.dat;
time: time in hours, where zero is the start of the induction;
R1 â€“ R8: value of each of the 8 MOX sensors resistance at that time;
Temp.: measurement of temperature in Celsius at that time;
Humidity: measurement of humidity in percent at that time.
Temperature and humidity were measured using the Sensirion SHT75. The 8 MOX sensors are commercially available from Figaro, and are detailed below:
R1: TGS2611
R2: TGS2612
R3: TGS2610
R4: TGS2600
R5: TGS2602
R6: TGS2602
R7: TGS2620
R8: TGS2620

Relevant Papers:

Ramon Huerta, Thiago Mosqueiro, Jordi Fonollosa, Nikolai Rulkov, Irene Rodriguez-Lujan. Online Decorrelation of Humidity and Temperature in Chemical Sensors for Continuous Monitoring. Chemometrics and Intelligent Laboratory Systems 2016.

Citation Request:

Ramon Huerta, Thiago Mosqueiro, Jordi Fonollosa, Nikolai Rulkov, Irene Rodriguez-Lujan. Online Decorrelation of Humidity and Temperature in Chemical Sensors for Continuous Monitoring. Chemometrics and Intelligent Laboratory Systems 2016.
