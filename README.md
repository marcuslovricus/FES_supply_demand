# FES_supply_demand
Code for calculating supply of and demand for forest ecosystem services in Europe. Data necessary to run the code can be found at https://zenodo.org/records/12699294
There are multiple versions of data. Use the version that is uploaded in August of 2025. 
The data provided at Zenodo is for all forests. There are also separate data-sets with supply and demand information coming from surveys. Coordinates are removed from this survey set as this is sensitive information. You can still run the code, just remove the coordinates from the list of columns. 

There are three files:
1. Vector embeddings. This is to get numerical representations  of satelite images.
2. FES_training_extrapolation. This is to train ML / Keras models and then extrapolate it, i.e. use it to predict supply and demand for FES across Europe
3. FES_analysis. These are different analyzes of the FES supply and demand. 
