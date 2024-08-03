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
1. Read in data two or more csv files.
2. Clean data and perform a pandas merge with two datasets.
3. Make a Tableau dashboard to visualize data.
4. Utilize a virtual environment.
5. Annotate code with markdown cells with clear comments in Jupyter Notebook.

## Summary of Findings
The Euro when compared to the US Dollar looks to be a steady contender until the 2008s Great Recession and the subsequent US Housing Market Crash a couple weeks later where it nosedived almost 11% from €1.2297 to €1.4393 from the beginning of that year to September of that year. It did, however, recover 2 months later on 11/04/2008 on the day of the US Presidential Election, which saw Barack Hussein Obama as the winner and President Elect. 2 of these 3 important events mentioned have origins primarily from the United States with the Recession also mostly originating from the failed banks in America and creating a domino effect with failed banks around the world that snowballed into the Great Recession. These events point to the fact that the US based events do definitely affect the value and the buying power of the Euro currency.

Following the previous events, the Euro stabilizes in the €1.30~ range for the next few years. It next saw a dramatic drop during the Arab Spring's ongoing uprising, where many Middle Eastern nations had revolutions and government instability for most of 2011 and the Euro peaked at €1.4844, which is it's highest ever when looking at the data within this study, during the Syrian Uprising. This gives us insight on another external region affecting the Euro currency's value and how those forces can change the outlook of a world renowned medium of exchange.

The next important point seen in the cleaned data is on the date 5/18/2012 when Facebook Inc.'s IPO was offered. From here on out, the Euro climbed in value from €1.2802 to €1.0818 when Brexit talks began on 3/29/2017. Brexit was the withdrawal of the United Kingdom from the European Union since being a member state of the European Union's previous predecessor, the European Communities since 1973. This event was very much an internal affair for the European Union and therefore the Euro currency but as the data shows, the valuation of the Euro was not affected much from the date the talks began for Brexit until it was finally implemented almost 3 years later on 1/31/2020. The change in value when compared to an exchange of 1 US Dollar shows a drop of €0.0212 in value during this time.

The 2020 US Presidential Election saw the Euro drop to €1.1642 hinting at the growing instability of US politics. The US Capitol Attack devalued the Euro against the US Dollar almost 6% to €1.2300. President Biden's Inauguration saw the Euro gain 1.5% back in value to €1.2138. 

By the time of the Russian invasion of Ukraine occurred on 2/24/2022, the Euro had recovered from its previous low and gained 7% in value to €1.1305. Following this, 2022s Inflation Rise was reported at the end of the first half of 2022. The inflation rate was reported to be 9.1%, a record high since the early 1980s in the US. Not being influenced by further economic instability in the United States, the Euro saw a gain of 8% in value to €1.0446 during this very time when the highest ever inflation rate in recent history was reported in the United States. 

To summarize all of my findings in this study, initially the Euro had been fluctuating in the €1.30 range starting in November of 2004 excluding the dips and gains mentioned earlier but following the 2016 Presidential Election, the Euro saw a dramatic gain in value and has since come very close to being on par with the US Dollar. This study shows that although the US economy, politics and overall instability do greatly affect the worth of the Euro, sometimes even more so than it's own internal challenges, it has seen a steady gain in value and has come out to be a very close contender to the US Dollar on the world stage with its prowess in buying power.