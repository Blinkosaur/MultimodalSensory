# Project Title: 

**  A Piscivore’s Guide to Its Perceptual Universe: 
 ** Multimodal sensory strategies during foraging in two predatory fishes 

# Project Location: 

Santa Catalina Island, California - Wrigley Marine Science Center


# Below are descriptions for our two datasets used in the provided R script 


# DATASET 1 : Multimodal_Data.csv

** This data set has columns for:**
 
 Site - Sites 1-15 (location)
 
 Visual_Cue - neutral (grey block), shape (fish model), move (moving fish model)
 
 Odor_Cue - water (control) or odor (anchovy juice)
 
 Combo - treatment combination (combines visual, odor cues, taste)
 
 Observer - name of researcher watching the footage (maya, gabby, dani)
 
 Date - Date of trial
 
 Zip_Color - color of zip tie on apparatus (pink, yellow, blue)
 
 Species - fish species that visited trial
 
 Max_Number	- maximum number of a species observed at a single time within the frame
 
 Arrival_Frame - time to arrive per species
 
 Time_to_Touch - time to touch the model with face per species
 
 Duration_Frame	- total duration at least 1 individual of a species was within the frame
 
 Duration_Facial_Contact - total duration at least 1 individual of a species had facial contact with the model
 
 Frame_Bite -  # of bites for frame per species
 
 Zip_Bite - # of bites for zip ties per species
 
 Total_Structure_Bite - Frame + Zip bites, any part of apparatus
 
 Model_Bite	- # of bites for visual model per species
 
 Selfie - # of camera investigations per species
 
 Non-Eel_SubAdult	- max number of observed juvenile individuals per species
 
 Non-Eel_Adult	Notes	- max number of observed adult individuals per species

 
 
# DATASET 2: Multi_YN.csv

This dataset pulls info from dataset 1 to track the frequency each species visited a particular treatment at a particular site to track the % of times a species arrived - if a species showed up for a trial, we recorded that as a "yes", and if they did not that is a "no". 

**This datset contains columns:**

Site - Sites 1-15 (location)

Combo - treatment combination (combines visual, odor cues, taste)

Zip_Color - color of zip tie on apparatus (pink, yellow, blue)

Kelp_Bass - yes/no if a kelp bass showed up

Moray - yes/no if a moray showed up

Garibaldi - yes/no if a garibaldi showed up

Any_Fish? - yes/no if any of the species showed up
