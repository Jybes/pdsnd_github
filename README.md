### Date created
This project was created on November 19, 2019 while this README file was created on December 12, 2019.

### Project Title
The project is titled **Bikeshare**

### Description
The project is a web application that allows users to interact with the bicycle sharing data of three states in the United States of America: *Chicago, New York City, and Washington DC*. Once run, it asks the user to enter the state for which information is needed, the month, and the day. After collecting these information, it would then display, in the following order, data for:
1. Time statistics:
    * the most common month
    * the most common day of week
    * the most common start hour

2. Station statistics:
    * the most commonly used start station
    * the most commonly used end station
    * the most frequent combination of start station and end station trip

3. Trip duration statistics:
    * the total travel time
    * the mean travel time

4. Users statistics:
    * the counts of user types
    * the counts of gender types
    * the earliest, most recent, and most common year of birth

5. Raw data statistics: Here it ask the user if they would like to see the first five rows of the raw data. If yes, it will display the data and ask if they would like to see the next five rows, continuing until the user chooses otherwise.

### Files used
The files used for this project are chicago.csv, new_york_city.csv and washington.csv

### Minor bugs
Under the **display_data** function, when the user chooses not to see more of the raw data, the application still goes ahead to ask them if they would like to see the first five rows of data, instead of just just going ahead to ask if they would like to restart.

### Credits
The following sites were used extensively in the course of the project:
1. [Pandas](https://pandas.pydata.org/pandas-docs/stable/)
2. [Python](https://docs.python.org/3/reference/index.html)
3. [Stackoverflow](https://stackoverflow.com/)
