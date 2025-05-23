# Biomedical Data Analysis Portfolio
## Overview
This repository contains scripts developed for image-based cell analysis, focusing on identifying and quantifying features such as active and inactive invadopodia, matrix degradation, and cell areas. The project demonstrates my proficiency in Python programming, image processing, and data visualization, essential skills in biological data analysis and other scientific computing fields.

## Project Motivation
Cell biology and other scientific fields often require automated methods to analyze cell images for quantitative data extraction. This project provides a framework for identifying and quantifying cell features from image masks, a crucial step in understanding cell behavior and function. The analysis can be adapted for various applications, from biomedical research to machine learning in imaging.

## Features
### Automated Image Processing: 
Analyzes sets of mask images to extract quantitative data on cell features.
### Feature Identification:
Distinguishes active invadopodia, inactive invadopodia, early invadopodia, and matrix degradation using overlap-based criteria.
### Batch Processing: 
Efficiently processes multiple images to generate statistical summaries.
### Data Visualization: 
Plots feature areas by cell type to provide insights into cellular behavior and characteristics.
## Skills and Technologies
### Programming Languages: 
Python
### Libraries: 
numpy, opencv-python, matplotlib, seaborn, pandas
### Techniques: 
Image segmentation, binary masking, pixel-based analysis, data processing and visualization, batch processing

Setup
Requirements
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/image_analysis_portfolio.git
Navigate to the project folder:
bash
Copy code
cd image_analysis_portfolio
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Usage
Batch Processing: Use batch_processing.py to analyze all masks in a directory and generate summary results.
bash
Copy code
python batch_processing.py --directory path/to/masks
Visualization: Generate plots by cell type to visualize feature areas across experiments.
python
Copy code
from batch_processing import plot_results_by_cell_type
plot_results_by_cell_type(results_df)
Example Results
Below are example results visualized from the scripts, showing the relative areas occupied by cell features across cell types.
Include example plots here, like bar charts or segmentation images.

## Applications and Future Work
This project could be extended to incorporate machine learning for feature detection and analysis, or adapted to analyze different cell structures in various biological research contexts. Future work may also include integrating more complex image processing techniques, like texture analysis, or applying these methods in other scientific fields, such as environmental imaging or materials science.

## Contact
If you have any questions or would like to discuss this project further, please feel free to reach out via LinkedIn or email me at [rodriguez.gutierrez.dan@gmail.com].


