# Data-Modeling-with-Apache-Cassandra
Event Data Processing for Apache Cassandra
This Python code is designed to process event data files and create a consolidated CSV file that can be used for Apache Cassandra tables.

Prerequisites
Before running this code, ensure that you have the following Python packages installed:

pandas
cassandra
re
os
glob
numpy
json
csv
Getting Started
Clone the repository or download the code files to your local machine.
Open the Python script Apache_Cassandra.ipynb in your preferred Jupyter notebook.
Usage
Open the Jupyter notebook 

Copy code
python Apache_Cassandra.ipynb
The script will process the event data files in the event_data directory and its subdirectories.

It will create a consolidated CSV file named event_datafile_new.csv that contains the extracted data.

The total number of rows in the new CSV file will be printed to the console.

Output
After running the script, you will have a new CSV file named event_datafile_new.csv in the same directory as the Apache_Cassandra.ipynb notebook. This file can be used for further analysis or for creating Apache Cassandra tables.

Notes
Make sure that the event data files are in CSV format and follow a consistent structure.
I gave three example files if you should put them in a folder named data your code will work without any problem
The script assumes that the event data files have a header row, which will be skipped during processing.
The script will overwrite the event_datafile_new.csv file if it already exists in the directory.
If you want to modify the output file name or location, you can edit the csv_file_path variable in the code.
