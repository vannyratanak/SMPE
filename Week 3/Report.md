# Laboratory Notebook for a user pointing experiment

###### *Empirical evaluation of [Fitts’s law](https://en.wikipedia.org/wiki/Fitts%27s_law): Fork this small [project](https://gricad-gitlab.univ-grenoble-alpes.fr/coutrixc/m2r_pointingxp)*

## General organization
#### *data/*
This folder contains both raw and processed experimental data that is returned from the experimental software.

- RawData : the raw data  as returned from the experimental software.
- MeanMTData : the processed mean movement times as returned from the experimental software.

#### *analysis/*
This folder contains my R markdown script used to analyze the data collected from the experiment.

## Experimental Reports
#### *Experimental task*
I used the implementation of a [pointing experiment from Ergonomics Web at Cornell University](https://ergo.human.cornell.edu/FittsLaw/FittsLaw.html). On this Webpage, one can gather data for controlled 1D user pointing experiments.

#### *Experimental variables* 
I ran the experiment from the above Webpage with 1, 2 and 4 widths and with 16, 32 and 64 distances, with 6 trials for each combination.

#### *Data collected*
I ran 2 experiments and get the following datas collected

- Teacher experiment:

        MT = 1001.293 + 140.589 × log(A/W + 1) with R2 = 0.218

- 1st experiment:
        
        W(1,2,4); Amp(16,32,64); 6 trial
        MT = 328.025 + 137.603 × log(A/W + 1) with R2 = 0.604
        Error: 94

- 2nd experiment:
        
        W(1,2,4); Amp(16,32,64); 6 trial
        MT = 501.167 + 10.220 × log(A/W + 1) with R2 = 0.003
        Error: 797

### *Discussion*

After run experiments there seem to be different in results. 
The difference in results—particularly due to several factors:

- User Differences: Variations in individual participants’ precision, speed, or familiarity with the task can lead to significant performance differences. For instance, if the we approached the task differently, it could result in different values.

- Fatigue or Learning Effects: In the second experiment, I tired to be inconsistent, which could explain the high error count.

In short, high participant error rates and possible differences in task setup or execution likely caused the observed variability