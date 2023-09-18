#Correlation Graph Generation

This repository contains a Python script that generates correlation graphs comparing predicted/simplified values with original values from a dataset.

Description

The script reads data from CSV files, processes it, and generates correlation graphs comparing two sets of values:

Original values vs. Simplified values
Original values vs. Predicted values
These graphs are helpful for visualizing the accuracy and reliability of predictions made by a machine learning model, especially in the context of building energy modeling.

Dependencies

pandas
numpy
matplotlib
os
Usage

Clone this repository:
bash

git clone <repository_url>
Install the required dependencies:

pip install pandas numpy matplotlib
Modify the paths in the script to point to your input CSV files and desired output directory.
Run the script:

python plot_correlation_graph.py
This will generate correlation graphs and save them as PDF files in the specified output directory.

Visualization

The generated graphs utilize the following color scheme:

EUI: Purple
Solar Gain: Orange
Cooling: Blue
Heating: Red
Each graph also contains a reference line (y=x) to easily compare the predicted/simplified values with the original values.

Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

License

MIT
