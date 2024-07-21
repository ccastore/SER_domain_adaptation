# SER_domain_adaptation
 Speech emotion recognition domain adaptation.

## Repository Structure
The project is organized into two main folders and a main program file.

- data/: Contains the data of all databases and their respective labels.
- modelos/: Contains the base models in 4 initial configurations of 𝑧 with dimensionalities of 2, 3 and 4.
- emo_retrain: Main program for retraining emotional models.


## Running the Main Program
To run the emo_retrain program, you need to configure the following parameters:

- cls_borders (bool): Show the classifier borders. Possible values: True or False.
- test_contour (bool): Show the test data. Possible values: True or False.
- train_contour (bool): Show the train data. Possible values: True or False.
- colors (list): A list of colors to show the different emotions.
- selection_method (str): Selection method. Possible values: random, kmeans_fixed, or kmeans_fixed_mov.
- number_of_steps (int): Number of steps for retraining.
- rep (int): Number of repetitions of the experiment.