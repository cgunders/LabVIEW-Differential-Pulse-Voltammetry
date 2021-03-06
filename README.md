# LabVIEW-Differential-Pulse-Voltammetry

Differential Pulse Voltammetry program written in LabVIEW 2016

![alt text](https://github.com/cgunders/LabVIEW-Differential-Pulse-Voltammetry/blob/master/DPV-diagram.png "Differential Pulse Voltammetry VI Diagram")

This program is for the generation of a voltage waveform and recording of current during a two electrode differential pulse voltammetry experiment. The analog inputs of the National Instruments card are connected to the voltage monitor and filtered current output of a Dagan Chem-Clamp voltammeter. Gain and filtering are controlled through the Chem-Clamp. The voltage on the electrodes is controlled by the Chem-Clamp and is externally controlled by the LabVIEW card.

Enclosed is the LabVIEW file written in LabVIEW 2016 64-bit along with Mathscript 2016 and NI DAQ 2016, both 64-bit. Also included is the VI snippet and 3 images of the front panel after recording the oxidation of 1 mM ferrocene methanol (FcMeOH) in 100 mM potassium chloride (KCl) at different scan rates of 20 mV/s, 200 mV/s, and 2 V/s. Other pulse parameters are shown. The working electrode is a 12.7 um diameter gold electrode and the reference/counter electrode is a Ag/AgCl quasi-reference electrode. 

![alt text](https://github.com/cgunders/LabVIEW-Differential-Pulse-Voltammetry/blob/master/DPV-20mVps.png "20 mV/s Differential Pulse Voltammetry of 1 mM FcMeOH in 100 mM KCl")

![alt text](https://github.com/cgunders/LabVIEW-Differential-Pulse-Voltammetry/blob/master/DPV-200mVps.png "200 mV/s Differential Pulse Voltammetry of 1 mM FcMeOH in 100 mM KCl")

![alt text](https://github.com/cgunders/LabVIEW-Differential-Pulse-Voltammetry/blob/master/DPV-2Vps.png "2 V/s Differential Pulse Voltammetry of 1 mM FcMeOH in 100 mM KCl")
