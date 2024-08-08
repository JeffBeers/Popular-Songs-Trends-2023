# Popular-Songs-Trends-2023

## Overview
In this project, we will clean and analyze data from the spotify-2023.csv, and spotify-2024.csv files.

The project has 3 goals:
- Idenitify the most-common musical attribute values of all 2023 Spotify songs.
- Count the occurances of the most-common attribute values within the entire spotify-2023.csv file, as well as within only the top-10 most streamed songs of 2023.
- Merge the two csv files, and track the top-10 songs' stream count growth from 2023-2024.

## Data Sources

I have renamed the original datasets for this project. You can find the original data sources below:

spotify-2023.csv
- https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023
spotify-2024.csv
- https://www.kaggle.com/datasets/nelgiriyewithana/most-streamed-spotify-songs-2024/data

## Setup

Before you begin, you will need to meet the following requirements:

- Install Python. This project was developed using Python 3.12.2. If you don't have Python installed or if you need to upgrade your current version, you can download it from the [official Python website](https://www.python.org/downloads/).
- You have installed Git, which is necessary to clone the repository. If you don't have Git installed, you can download it from the [official Git website](https://git-scm.com/downloads).

1. **Clone Repository**
    ```sh
   git clone https://github.com/JeffBeers/Popular-Songs-Trends-2023
   ```

2. **Navigate to Cloned Repository**
    ```sh
   cd Popular-Songs-Trends-2023
   ```

3. **Set up a virtual environment**

    By using a virtual environment, you can isolate the dependencies for each project, ensuring that they don’t interfere with one another. You can create a virtual environment using the following command:

   On Windows:

   ```
   python -m venv venv
   ```

   On macOS and Linux:

   ```
   python3 -m venv venv
   ```

   This will create a new virtual environment named `venv` in your current directory.

4. **Activate the virtual environment**

   On Windows:

   ```
   .\venv\Scripts\activate
   ```

   On macOS and Linux:

   ```
   source venv/bin/activate
   ```
5. **Install the required packages**

   Install the required packages by running the following command:

   ```
   pip install -r requirements.txt
   ```

6. **Run the ```Popular-Songs-Trends-2023.ipynb``` file:**
    - Using Visual Studio Code, open the `.ipynb` file and run the cells using the run button that appears at the top left of each cell.

7. **Deactivate Environment When Finished**
    
    Type `deactivate` in your terminal when you are finished running the project.


## Visualizations

Visualizations of the findings for this project can be viewed on my [Tableau Public workbook]
(https://public.tableau.com/app/profile/jeffery.beers/viz/Popular-Songs-Trends-2023-tableau/Story1?publish=yes)

## Project Features

**Category 1: Loading Data:**
- Read TWO data files (CSV).

**Category 2: Clean and Operate the Data While Combining Them:**
- Clean your data and perform a pandas merge with your two data sets, then calculate some new values based on the new data set. 

**Category 3: Visualize / Present Your Data:**
- Make a Tableau dashboard to display your data.
  
**Category 4: Best Practices:**
- Utilize a virtual environment and include instructions in your README on how the user should set one up
- List dependencies in a requirement.txt file.

**Category 5: Interpretation of Your Data:**
- Annotate your code with markdown cells in Jupyter Notebook, write clear code comments, and have a well-written README.md. 
