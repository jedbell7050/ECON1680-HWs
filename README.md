# Homework 1 Preliminaries

This repository contains instruction on how to get started for homework 1.

1. Download and install Python/Anaconda onto your computer:

    First, you need to install python 3.x and packages for scientific computation on your computer. I recommend you download and install the Anaconda distribution of python because it comes with the majority of packages you will need. An additional bonus of working with Anaconda is it has multiple environments for editing and running python code, including Spyder and Jupyter.  Go here to begin downloading the individual edition of Anaconda (Windows, Mac, Linux): https://www.anaconda.com/products/individual 

    Students are expected to work in python for this class. If you need a refresher on the language, here are additional resources for learning python:
 
    - http://www.codecademy.com/en/tracks/python
    - http://www.learnpython.org
    - The book “Learning Python” by Mark Lutz

    I recommend using Spyder or Jupyter so that you can edit and run python code in an interactive environment on your computer.

2. Packages to install for this assignment

    a. You will need to install the Nasdaq data link, nltk, and wordcloud using conda, pip, or pip3 install in the terminal for Mac or Linux computers, and the Anaconda Prompt for Windows computers. If not using Anaconda, you can use pip install for nltk and wordcloud. You also need to install Jupyter if you want to do your homework on Jupyter notebook. You can install these packages through running the following commands:

    ```
    pip install nasdaq-data-link
    conda install nltk
    conda install wordcloud
    pip install notebook
    ```

3. Set up Github account and connect to Github Classroom for Econ 1680:

    For the assignments in this class you will be expected to submit your code into a git repository in our Github Classroom. Github is a website that allows coders to manage, store, track, and share code. Github is both helps with building good coding habits and a great way to showcase your code for future employers and institutions. Your project files and assignments will be stored in a private repository for Econ 1680 that only you, the professor, and the teaching assistant can see. A repository contains your files and each file’s history.

    a. From Homework Assignment 1 page in Canvas, click on the HW 1 invitation link to access the course GitHub repository. You will be prompted to connect to the Github Classroom.

    b. Link your GitHub account to the classroom: either log into your GitHub Account or set up a free account on GitHub. You can sign up for an account at: https://github.com/signup. When you click into the Github Classroom, you will be prompted to log in to your account to link your Github Account to your identifier in the Econ 1680 Github classroom. Note: we will be able to see your linked username, so please make sure your Github username is appropriate and professional. (5 points)

4. There are three ways you can work with the git repository: by using commands in your computer terminal prompt, by using GitHub Desktop, or by manually downloading files from the git repository. I recommend using the first two options so you can learn how to use git, practice the git workflow, and have version control for your codes.
    
    a. To clone the assignment, open your terminal and go to the directory you want to place the homework assignment in. Then run the following command:

    ```
    git clone https://github.com/Econ1680-MLTAEcon-Spring2022/hw<homework number>-<your github username>.git
    ```

    [Here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) is also a helpful guide for how cloning works. 

    If you haven't set up Github in your terminal before, running the command above may ask you for your personal access token. You can find how to generate your personal access token [here](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token). 

    To enter the homework directory, run:

    ```
    cd hw<homework number>-<your github username>
    ```

    To run the Jupyter notebook, do:

    ```
    jupyter notebook HW1.ipynb
    ```

    b. Download the GitHub Desktop (https://desktop.github.com/). Once you log into your GitHub account in the GitHub Desktop, you will be able to select "hw1-<username>" repository in the top left corner and view the files of the repository in Finder if you have a Mac or in your Folders if you have a Windows. 

    When you open and work on files, then save them, edits you make will show up in the GitHub Desktop app. You must label and describe your changes and the select "Commit to main" and "Push to Origin" to have your files sumbit to the GitHub repository online.

    If you haven't set up Github in your terminal before, running the command above may ask you for your personal access token. You can find how to generate your personal access token [here](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token). 

    c. To download the homework assignment directly, you may click on HW1.docx and in the repository above. Then you will need to create your own .py file and run the code using Python in the terminal or using Spyder through Anaconda. I **do not** recommend this option as it side steps the git workflow and does not give you version control.

4. Submitting the assignment to Github and to Canvas:

    a. What to submit:
    
      - If you use .py file for code: submit the .py file and a pdf of your completed HW1.docx to both GitHub and to Canvas.
    
      - If you use a Jupyter Notebook: submit the notebooks to GitHub, save the notebook as a pdf and submit it to Canvas.
    
        To save the notebook as a pdf, you need to first download pandoc following [this instruction](https://pandoc.org/installing.html).

        Once pandoc is installed, you can simply go into your activated jupyter notebook page, and click on *File > Download as > PDF via LaTex (.pdf).*

    b. How to submit assignment using the Terminal: 
    
      - To commit your changes, simply go into the homework directory by running:
        ```
        cd PATH_TO_YOUR_HW_DIRECTORY/hw<homework number>-<your github username>/
        ```
      - Add and commit the changes by running:
        ```
        git add .
        git commit -m "type in your custom git message"
        ```
      - And push your changes by running:
        ```
        git push origin main
        ```
    c. How to submit assignment using the GitHub Desktop:

     - When you open and work on files, then save them, edits you make will show up in the GitHub Desktop app. You must label and describe your changes.
     - Select "Commit to main" and "Push to Origin" to have your files sumbit to the GitHub repository online.
    
    d. How to manually submit assignments (not recommended):
    
      - You may also add your files to the repository by clicking the "Add File" in the top right above the repository in GitHub. Then you must load your HW1.pdf and HW1.py code and select "Commit Changes."
    
    
