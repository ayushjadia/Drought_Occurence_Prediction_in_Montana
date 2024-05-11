# Drought Prediction in Montana
In this project we are going to predict the occurence and severity of drought based on the meterological data. 
Drought is classified into 5 categories which are : D0, D1, D2, D3, D4 these denotes severity of drought in increasing order. 
In our data corresponding to each county (Montana state is divided into 56 counties) we have metorological columns and drought columns. Drought columns comprises of 6 columns namely "None" "D0" "D1" "D2" "D3" "D4" "DSCI" where data correspnding to each row corresponds to percentage area of county that has corresponding drought severity (*None denote no drought*).
The "DSCI" value is standard measure for calcluating average drought severity in a place. It is determined as: (DSCI= 1*D0+2*D1+3*D2+4*D3+5*D5).
We are going to predict the DSCI value of overall Montana state in this proect . However this model can also be used to predict severity for specific counties by some small tweaks. 
