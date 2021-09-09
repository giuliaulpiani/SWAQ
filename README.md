# SWAQ
This is the code to produce the two quality-controlled SWAQ datafiles (csv format) as in the TERN repository:  

https://portal.tern.org.au/schools-weather-air-sydney-nsw/22077  

Cite as:  
Hart, M. , Maharaj, A. , Di Virgilio, G. , Ulpiani, G. (2021): Schools Weather and Air Quality (SWAQ) – Quality Controlled Urban Dataset – Sydney (NSW). Version 1.0.0. Terrestrial Ecosystem Research Network (TERN). Dataset. https://doi.org/10.5281/zenodo.5016296  

It is written in very plain Python language for use also by beginners in Google Colab, a collaborative environment that runs in Google Drive. 
When using the code: 

- create a folder in Drive containing the code itself and the dummy_swaq_data.csv dataset. 
This dataset contains approximately 2-month data in the original format retrieved from the SWAQ Cloud, prior to time alignment;  

- make sure to update the project_folder in the "Import packages" section (first section) accordingly.  

In addition to “YYYY-MM-DD_Raw.csv” where flags supplement but do not alter the original data and “YYYY-MM-DD_Cleaned.csv” that contains a ready-to-use cleaned dataset, 
the code generates the "swaq_data_aligned&amp;resampled.xlsx" Excel file with the original dataset aligned in time (no quality control).  
NB: to avoid any issues, please do not alter any names in the code.
