# Data Science Assignment - Togashi Dataset
This is the repositary for the Data Science Assignment

This is code (notebook.ipynb) in order to curate and analyse temperature data for 695 phytopathogenic microbes from the Togashi dataset. Mainly, to be used to create references for future lab experiments and models. Specifically, the code was used to curate a dataset for the cardinal temperatures (maximum, minimum, and optimimum) of Fusarium species and identify if these temperature ranges are influenced by life processes of the pathogens. However, code can be used for other phytopathogens. For more information on the dataset then refer to: https://datadryad.org/stash/dataset/doi:10.5061/dryad.tqjq2bvw6#methods

To run:
  1. Donwload all avalaible files in the repositary into a working directory or just the notebook
  2. For full dataset then refer to 'https://raw.githubusercontent.com/Vasili-28/Data-Science-Assignment/refs/heads/main/Supplementary_Data_Togashi_FINAL.csv' or download it from the repositary
  3. For 'Fusarium only' dataset then refer to 'https://raw.githubusercontent.com/Vasili-28/Data-Science-Assignment/refs/heads/main/filtered_fusarium_species.csv' or download it from the repositary. If using the Fusarium only dataset, then skip Set Up section of the notebook.ipynb and use the url or download it from the repositary
  4. Import all necessary libraries (run first cell of the notebook,ipynb) which include:
     - pandas
     - matplotlib.pyplot
     - seaborn
     - scipy.stats
     - from scipy.stats import kruskal
     - from scipy.stats import mannwhitneyu
     - from itertools import combinations
  5. Change the final dataset with other avalaible varaibles in the dataset if necessary
  6. Edit code to ensure you subset the genus or species for different phytopathogens
  7. If downloading .png files then edit image name
  8. End of the notebook contains optional code for a pairwise comparison test if Kruskall Wallis test is significant for further analysis

Output of the code creates a pivot table that shows the mean cardinal temperatures for Fusarium species alongside a box plot illustrating mean cardinal temperatures. Another box plot was produced for temperature ranges of various life processes of Fusarium species and the results of a Kruskall Wallis Test which was non-sginificant. Desecriptive statistics was also produced for cardinal temperatures of different species and life processes. Finally, this code is used as a method to create a reference for future comparisons for experiments and modelling with newly collected field samples.


 
