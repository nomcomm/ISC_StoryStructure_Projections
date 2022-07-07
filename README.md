Analysis for Schmälzle & Coauthors (in preparation)
=============================================

Data and analysis code for describe *How shared brain activity varies over the course of a narrative in regions associated with social cognition and story comprehension* [PaperDocument](https://docs.google.com/document/d/1WEPfLmclLzrgoL3ftYaeC-xrPiKiuByI2KZtbIc4zak/edit?usp=sharing) [External Link]

Link to our [GoogleDriveFolder](https://drive.google.com/open?id=1OXinny2IFYgE0VHj1tY2jeE2PMYLW4av)

***

<img align="right" width=250px src=data/explainer_fig.png> 



### Code

-  The analyses are documented in the order they appear in the paper in the scripts folder

### Data

-   The most relevant data are shared in the data folder. Additional data can be reproduced by downloading and extracting data from the [source dataset](https://openneuro.org/datasets/ds000228/versions/1.1.0).

### Dependencies

-   Python, Anaconda, Nilearn, (BrainIAK), seaborn, Nibable. The [Anaconda](http://continuum.io/downloads) distribution should provide you with most of what you need. Install the python37 version that is appropriate for your operating system. Then, in a [terminal/conda prompt], 

1) first clone the repository "git clone https://github.com/nomcomm/medianeuroscience_project.git", 

2) then step into the folder "cd medianeuroscience_project", 

3) enter "conda env create -f environment.yml" to create a conda environment on your system

4) once the environment is installed, enter "jupyter notebook". This should fire up a jupyter-notebook. 

5) Navigate to the scripts folder and exectute the code.

[Troubleshooting](TROUBLESHOOTING.md)

2020 \| Ralf Schmaelzle & The Media Neuroscience Team
