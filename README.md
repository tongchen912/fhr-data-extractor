# fhr-data-extractor

Extract 30-minute fetal heart rate (FHR) signals with less than 50% missing data prior to delivery. 

## Project Structure
extract_fhr/
├── main.py # Main script to run extraction
├── io.py # Functions to load delivery data and FHR files
├── filter.py # Logic to filter based on missing data
└── utils.py # Helper functions