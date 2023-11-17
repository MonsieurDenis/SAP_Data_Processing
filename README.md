**Overview**

This repository contains Python code utilizing the pandas library to process results from SAP2000, a Structural Analysis and Design Software. The code focuses on analyzing a row of piles, extracting forces and bending moments from nodes associated with these piles, and generating a summary table.

**Project Structure**

Data_Processing_From_SAP.ipynb: Jupyter Notebook containing the Python code for processing SAP2000 results.

Output_table.csv: CSV file containing the generated summary table with information on maximum and minimum vertical and horizontal forces, as well as minimum and maximum bending moments.

**Requirements**

Python 3.x

pandas library (pip install pandas)

**How to Use**

Open and run the sap2000_analysis.ipynb Jupyter Notebook.

Ensure the required Python libraries (pip install pandas) are installed.

Execute the cells in the notebook to process SAP2000 results and generate the output table.

Included an example of an output file from SAP2000 so please have a good to see how it works and what is the idea behind it

**Output**

The generated output_table.csv provides detailed information on the analyzed piles, including:

Maximum and minimum vertical forces.

Maximum and minimum horizontal forces.

Maximum and minimum bending moments.

**Contributing**

Contributions are welcome! If you find any issues or have improvements to suggest, please open an issue or submit a pull request.
