# MLP - 2021, bike sharing

## Phase one

In phase one there are two subtasks, our notebooks for them are:

 - subtask 1: fit a model to all the data. This is the file all_data.ipynb
 - subtask 2: fit a model to each station. We have two notebooks here, for different usecases. The first, by_station.ipynb, predicts for stations already in the training data.
 - The second, by_station_ensemble.ipynb, builds an ensemble from each station's model, and can be used to predict for new stations
 
 ## Phase two
 
 Here we use a set of 1200 linear models which have been fit on a year's data for unseen stations to construct an ensemble. This can be found in part_2.ipynb
 
 ## Phase three
 
 Here we combine the ensembles from phase one and two into a new ensemble. This is in part_3.ipynb.
