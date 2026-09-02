# OpenScope Repository - Sarvestani Lab

## Install Dependencies
can include the anaconda environment set up and etc.

## Set up config file
1. Install dotenv: `pip install dotenv`
2. Create a new `config.env` file in the same directory as `average_rf.ipynb`
3. Add the following contents:
    ```sql
    FULL_DATA_DIR=/Volumes/My Passport/001568
    SAMPLE_DATA_DIR=/Users/serenazhu/sarvestani_lab/000021
    ```
    Change the values of the directories according to your local filepath. `FULL_DATA_DIR` is the directory with the full data, `SAMPLE_DATA_DIR` is where you want to download the sample .nwb file.