# How is the Euro/USD exchange rate affected by American and world events?

## About
Greetings! This data analysis project will look at the Euro/USD exchange rate and find evidence to correlate how it can be affected by world events that stem sometimes from here at home in the United States or other nations. There will be instances where the events might make you think that the exchange should be dramatic but the data will say otherwise! The data being used primarily is the exchange rate of the Euro vs. 1 US Dollar between the dates of 11/30/2003 and 7/29/2022. The other data set with important world events is a csv I created by mapping out dates for important US and World Events with the region where the origination of those very events occur.

The Jupyter notebook takes the csv files, cleans and merges them, then exports them as csv files in the Results folder to be used for visualization in Tableau.

## Data Source
CSVs:
- [Kaggle Euro to USD Conversion EURUSDX.csv](https://www.kaggle.com/datasets/neelgajare/euro-to-usd-conversion)
- [World_Events.csv] Self researched important dates and events and created a csv file

### Instructions:

Before you begin, ensure you have met the following requirements:

- You have installed Python. This project was developed using Python 3.12.2. If you don't have Python installed or if you need to upgrade your current version, you can download it from the [official Python website](https://www.python.org/downloads/).
- You have installed Git, which is necessary to clone the repository. If you don't have Git installed, you can download it from the [official Git website](https://git-scm.com/downloads).
- Open a new terminal in your IDE making sure it's a powershell terminal.

Follow these steps to run the project on your local machine:

1. **Clone the repository**

    Navigate to the directory where you want the cloned repository to be placed by using the ```cd``` command in your terminal followed by the path of the directory.

    Then you can clone this repository by running the following command in your terminal:

   ```
   git clone https://github.com/codeydude/Euro_Exchange_World_Events.git
   ```

2. **Navigate to the cloned directory**

   Change your current directory to the cloned repository's directory Euro_Exchange_World_Events

3. **Set up a virtual environment**
    It's recommended to create a virtual environment to keep the project's dependencies isolated from your system's Python environment. You can create a virtual environment using the following command:

    
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

    Activate the virtual environment by using the following command:

    On Windows:

    ```
    .\venv\Scripts\activate
    ```

    On macOS and Linux:

    ```
    source venv/bin/activate
    ```

5. Refer to and install the packages listed in the requirements.txt file. To do so, run the following command:
    ```
    pip install -r requirements.txt 
    ```
    OR 
    ```
    pip3 install -r requirements.txt
    ```

6. Ensure modules are installed and Python is updated to at least version 3.12.

7. Open and run euro_world_events.ipynb.

8. To deactivate the virtual environment when you're done, simply type `deactivate` in your terminal.

9. Refer to my [Tableau dashboard](https://public.tableau.com/app/profile/lavin.lalchandani/viz/Eurovs_WorldEvents/Dashboard1) for visualized data.

### Features:
1. Read in data of two or more csv files.
2. Cleaned data and performed a pandas merge with two datasets, then calculated new values based on the new dataset.
3. Made a Tableau dashboard to visualize data.
4. Utilized a virtual environment.
5. Annotated code with markdown cells with clear comments in Jupyter Notebook.
