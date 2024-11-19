# FRASE Data Analysis

## Description

The **Fluorescence Resonance Energy Transfer (FRET)-based mHTT Aggregate Seeding Assay** is a biophysical assay used to monitor the aggregation of Huntingtin Exon 1 (HttEx1) over a time course. This assay is versatile and can be employed to study HttEx1 aggregation kinetics, test the efficacy of aggregation inhibitors, or evaluate the seeding activity of biological Htt samples.

This assay requires two fluorescently labeled proteins:
- **GST-Ex1Q48-CyPet**
- **GST-Ex1Q48-YPet**

For more details on the experimental setup, refer to the publication:
> A. Ast, A. Buntru, F. Schindler, et al. *mhtt seeding activity: A marker of disease progression and neurotoxicity in models of Huntington’s disease*. Molecular Cell, 71:675–688.e6, 2018.  
> [DOI:10.1016/j.molcel.2018.07.033](https://doi.org/10.1016/j.molcel.2018.07.033)

This Jupyter Notebook is designed to analyze FRASE data from this system using a 384-well plate and a Tecan reader. It automates the data analysis workflow, taking raw data and experimental designs as input to produce meaningful insights and visualizations.

## Input Requirements

This script requires the following two input files in `.csv` format:

1. **Pipetting Scheme:** Contains the layout of the 384-well plate, specifying the contents of each well.
2. **Raw Data File:** The data exported directly from the Tecan reader.

## Features

- Processes raw data and maps it to the experimental layout.
- Filters unwanted data (e.g., blanks, controls).
- Produces visualizations for tracking aggregation kinetics.
- Outputs cleaned data and results in a format ready for publication or further analysis.

## Usage

### Local Execution
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   
2.	Upload the required input files (.csv) when prompted.

### Google Colab

You can run this notebook directly on Google Colab for free:

	1.	Click the Open in Colab button above.
	2.	Upload the required .csv files when prompted.
	3.	Follow the instructions in the notebook to process and visualize your data.
---

## Contribution

Contributions are welcome! Feel free to open issues or submit pull requests.

---

## Contact

For questions or issues, contact me at andreagtzq@gmail.com

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Colab notebook

Run this notebook on Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/andreaquezada/frase_dataanalysis/blob/main/Frase_dataAnalysis_v4.ipynb)
