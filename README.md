# Part 1: Using Collaborative Filtering to Recommend Alternative Movies

## Case Study
The customer service team at Netflix has started to receive user complaints about Netflix having a limited catalog of movies. In response, the product team has decided that they want to suggest similar movies as a consolation to users that can't find their desired movie. The product team has asked their top two data scientist, Debbie and Juan Carlos, to create an algorithm that allows a user to receive suggested movies when their searched for movie is not available.


## Stakeholders
1. Product Team: This team has requested the ability to provide a user with suggested movies when the user is not able to find the specific movie they want to watch.
2. Customer Service Team: This team expects that the new feature will reduce the number of user complaints about the movies not being available on their library.

## Success Metrics
* The number of user complaints related to a movie not being available should show statistically significant decreases after the feature is implemented.
* The number of people who watch a recommended movie should increase while the number of user complaints decreases.

# Part 2: Using TensorFlow Wide & Deep with LASSO regression to make movie recommendations

We've used TensorFlow's Wide & Deep model to predict movie ratings, and also made an extension to the model by implementing LASSO regression for improved feature selection. For full details, refer to the subdirectory "Part_2".

## To run the code in any subdirectory, do the following:
* To run the notebook found in the Part 1 or Part 2 follow these instructions:
    * Navigate to the "part_1" or "part_2" folder of the directory.
    * Run this code if you do not have conda installed in your machine.
    ```text
    wget http://repo.continuum.io/miniconda/Miniconda3-3.7.0-Linux-x86_64.sh -O ~/miniconda.sh
    bash ~/miniconda.sh -b -p $HOME/miniconda
    export PATH="$HOME/miniconda/bin:$PATH"
    ```
    * This line will create a file with all the libraries needed for the notebook to run.
    ```text
    conda env create -f environment.yml
    ```
    * Depending on your OS run the respective line below to activate the environment needed for the notebook.
    ```text
    Windows:            activate rec
    macOS and Linux:    source activate rec

    ```
    * For Part 1, this line will run jupyter lab on your machine making it available on port 8888.
    ```text
    jupyter-lab Collaborative_Filtering_Part_1.ipynb
    ```
    * For Part 2, this line will run jupyter lab on your machine making it available on port 8888.
    ```text
    jupyter-lab Wide-Deep-Lasso.ipynb
    ```


