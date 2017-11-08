# Using Collaborative Filtering to Recommend Alternative Movies

## Case Study
The customer service team at Netflix has started to receive user complaints about Netflix having a limited catalog of movies. In response, the product team has decided that they want to suggest similar movies as a consolation to users that can't find their desired movie. The product team has asked their top two data scientist, Debbie and Juan Carlos, to create an algorithm that allows a user to receive suggested movies when their searched for movie is not available.


## Stakeholders
1. Product Team: This team has requested the ability to provide a user with suggested movies when the user is not able to find the specific movie they want to watch.
2. Customer Service Team: This team expects that the new feature will reduce the number of user complains about the movies not being available on their library.

## Success Metrics
* The number of user complaints related to a movie not being available should show statistically significant decreases after the feature is implemented.
* The number of people that watch a recommended movie should increase while the number of user complaints decreases.


## Part 1 directory:
* The approach to the development of version 1 of the algorithm has been detailed in the notebooks files located in the “Part 1” subdirectory.
* To run the notebook found in the Part 1 follow these instruction:
    * Navigate to the "part_1" folder of the directory.
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
    * Depending on your OS run the repective line below to activate the environment needed for the notebook.
    ```text
    Windows:            activate rec
    macOS and Linux:    source activate rec

    ```
    * This line will run jupyter lab on your machine making avaialble on port 8888.
    ```text
    jupyter-lab Collaborative_Filtering_Part_1.ipynb
    ```



