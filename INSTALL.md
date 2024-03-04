1. If you do not already have Python installed, please follow these instructions: 

    Download the latest version of Anaconda for your specific operating system here: https://docs.anaconda.com/free/anaconda/install/index.html 

  
2. Next, you’ll want to set up a git environment and clone our repository:

    First, we need to install git bash to be able to run the commands necessary to clone our files (also known as a repository)
  
        Download your operating systems version of git bash here: https://git-scm.com/downloads

    Next, we need to clone the repository to the computer:
    
        Open the newly installed git bash and navigate to a location you would like the repository stored in.
            Heres a few helpful commands (exclude all qutation marks):
                "ls" will lsit all directories in the current file path
                "cd <directory_name>" will switch to a directory within the file path. Please replace "<directory_name>" with a corresponding directory in the path
                "cd .." will move back in case one accidentally moves to a directory they do not want to be in

    Now that we have moved to the directory we want to clone the repository in, now lets clone the repository:
    
        git clone mazure21/Kellanova (github.com) 
    
    With the repository now cloned, run the following command to move into the repository and its contents:
    
        cd <project-directory-name> (you’ll want to replace project-directory-name with the directory you cloned the repository into)


3. Now that the repository has been cloned locally to the computer, we now need to open it with our newly installed Anaconda software:

    Open the Anaconda Navigator on your computer and on the front page there will be several different environments for running python. 
    We want to use "jupyter notebook." Search for "jupyter notebook" and click launch to open a locally hosted jupyter notebook environment.

    From here, using the file directory prompted by jupyter notebook, navigate to where the reposiory was cloned to from above, and open the main jupyter notebook file containing our code. 
    These jupyter notebook files will always end with a file type of ".ipynb" (Will include the name for this file later.)


4. With the main .ipynb file open in jupyter, we now need to install the necessary libraries to run the provided notebook.

    Go back to the original page that opened up jupyter hub. This should be the page with the files and directories on it, and NOT the tab with the main file opened. 

    While in this tab, at the top right of the screen there is a drop down labeled "New", click this and select the "terminal" option.

        Now that we are in the terminal, we need to run a command to install all the necessary libraries for our notebook. In the terminal, please run the following command:

          pip install pandas numpy seaborn 

    After running this command, the necessary libraries associated with our project notebook will be installed.


5. The next step is to make sure that the data is also in the same repository that was just cloned:

    The data will not be in the cloned repository, so we need to add it ourselves. To do this:

        The data files for our project will be named:
          PLN_TO_ITM_WK (KNA_COMRCL)_PLN_TO_ITM_WK.csv
          EDT_3P (KG_HADOOP) Prod_EDT_3P.csv

    Open the file navigator on your computer and navigate to the location of the repository. Move into the repository, and paste the two previous files into the repository.
    If done correctly, the data files will be in the same folder that the main .ipynb notebook is in.


6. With the data now moved into the repository, we are now ready to run the notebook:

     To run an individual cell in jupyter, press shift and enter at the same time.
     To run all cells in the jupyter notebook, press ctrl, alt, shift and enter all at the same time (ctrl and alt with the left hand and shift enter with the right hand)


7. Assuming everything above has been done properly, all cells should execute and show our code.



