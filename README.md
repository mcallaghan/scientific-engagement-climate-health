# scientific-engagement-climate-health
This repository contains code to create the indicator on scientific engagement for the lancet european countdown report on climate and health

- `0_get_data.ipynb` Retrieves document and annotation data from a private database and writes csv files
- `1_classifier.ipynb` Trains a classifier to predict inclusion/exclusion and impacts/mitigation/adaptation
- `2_topic_model.ipynb` Loads a previously trained topic model (from database) and fits the included documents
- `3_extract_places.ipynb` Extracts place names using Mordecai
- `3b_fix_summarise_places.ipynb` Fixes common place name mistakes
- `3c_get_institution_locations.ipynb` Extracts countries from institution locations (requires database access)
- `4_figures.ipynb` Produces figures detailing where and when studies are found
