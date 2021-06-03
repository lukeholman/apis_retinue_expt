# Data

* `blinded_behaviour_data.csv`: this is the blinded version of the dataset, that was transcribed from the videos. The columns are:
    * tray (this corresponds to the experimental block; the 12 dishes in each block were kept on a tray)
    * dish (the Petri dish being recorded; a number from 1-12)
    * start_touch (the time point that a bee began to contact the lure, e.g. 06:38 means 6 minutes and 38s after the start of recording)
    * end_touch (the time point that a bee ended contact with the lure)

* `unblinded_behaviour_data.csv`: this is the unblinded version of the dataset. The additional columns are:
    * hive (the hive from which the bees came; three named hives)
    * treatment (the pheromone treatment applied to the lure in the focal Petri dish; 1 of the 12 possible treatments)
    * number_bees (the number of bees in the Petri dish; typically 5, occasionally 4)
    * touch_duration (the number of seconds the bee was in contact with the lure, calculated from the start and end times)

* `metadata_for_each_dish_and_tray.csv`: data about each Petri dish in the experiment. The one pertinent variable is the number of bees in the dish (typically 5, occasionally 4).

* `blind_codes.csv`: spreadsheet used to assign hive and treatment information to each Petri dish in each block (the data were unblinded after finishing data collection and creating the `blinded_behaviour_data.csv` dataset)
