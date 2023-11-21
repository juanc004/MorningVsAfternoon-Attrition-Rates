# MorningVsAfternoon-Attrition-Rates

## Overview

This project aims to investigate the impact of changing the timing of the Water Confidence (WCD) training sessions on the attrition rates of trainees. Historically, WCD sessions took place in the afternoon. However, starting from course 2206 (on 9/29/22), the WCD training was shifted to the morning. This analysis focuses on understanding the effects of this change on the overall attrition rates of the trainees.

## Objectives

- Import data from CSV files into a structured format.
- Convert date formats for easier manipulation and comparison.
- Apply statistical and visual techniques to analyze attrition rates.
- Generate PDF reports summarizing key insights.

## Features

- **Data Import**: Reading data from CSV files into a Pandas DataFrame for subsequent analysis.
- **Data Cleaning**: Converting the 'Date' column to a datetime format for easier date-based operations.
- **Data Analysis**: Applying statistical methods and creating visualizations to understand attrition patterns due to the change in training session timings.
- **Report Generation**: Creating PDF reports for sharing insights and visualizations.
- **Image Processing**: Additional functionalities related to image analysis, if applicable.

## Libraries Used

- [Pandas](https://pandas.pydata.org/) for data manipulation and analysis.
- [Matplotlib](https://matplotlib.org/) for data visualization.
- [fpdf](https://pyfpdf.readthedocs.io/en/latest/) for generating PDF reports.
- [PIL](https://pillow.readthedocs.io/en/stable/) for image processing.
- [re](https://docs.python.org/3/library/re.html) for regular expressions.
- [Numpy](https://numpy.org/) for numerical computations.

## Installation

1. Clone this repository to your local machine.
   ```bash
   git clone [repository_url]
   ```
2. Navigate to the project directory.
   ```bash
   cd [project_directory]
   ```
3. Install the required dependencies.
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter Notebook `P-635_PDI_Attrition.ipynb`.
2. Execute the notebook to run the analysis.

## License

For licensing information, see the `LICENSE.md` file.

## Contributing

For guidelines on how to contribute to this project, please refer to the `CONTRIBUTING.md` file.
