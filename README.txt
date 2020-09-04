Download the source data file from the link provided: https://drive.google.com/file/d/1XhiVHb127mTvpM0LG8TkbvGtDURYcY9N/view?usp=sharing
The source data is also mapped into the individual folders for running the code chunks.

We have separated the codes into the different stages of our project by folders labelled from '1_' to '3_'.
In each folder, we have included the codes and input datasets for the codes.

Detailed Instructions before executing each folder is provided below:

1_Exploratory Data Analysis

- Drop the downloaded source data onto the 'Input File'
- Execute the notebook labelled as 'Master File - EDA + Network Structure.ipynb'
- The outputs are stored as .CSV files under the sub-folder 'Clean_data_files_Community' which will be used as input for '2_Community Detection'
- The outputs for folium plots are stored under the sub-folder 'Folium_Output'.

2_Community Detection

- Replace the path directory to match with your system's location for Basemap package installed before executing further
- Extract the 2 jupyter notebooks by unzipping the 'Community Detection Notebooks.zip' folder and save the files in the same destination
- Now, execute the notebook labelled as 'Community detection.ipynb' from the unzipped 'Community Detection Notebooks.zip' folder
- Next, execute the notebook labelled as 'Centrality on Communities.ipynb'from the 'Community Detection Notebooks.zip' folder
- The community detection output files in html format can be found under the sub-folder 'Output files_for_Community'

3_Network Classification

- Drop the downloaded source data onto the 'Input File'
- Execute the notebook labelled as 'Network Classification.ipynb'
- Misc_Files are used for intermediate code operations
