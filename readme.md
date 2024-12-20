# Project Overview

This project explores two statistical methods for parameter estimation in a two-dimensional model, focusing on Maximum Likelihood Estimation (MLE) and sWeights. The model consists of signal and background components defined over two variables,  X  and  Y , with specific probability distributions. The study investigates the performance of both methods using parametric bootstrapping and likelihood fitting techniques. Key objectives include comparing bias, uncertainty, and computational efficiency for different estimation approaches. The analysis aims to identify the most suitable method for parameter estimation in various scenarios.

## Folder and File Structure


```plaintext
YM432/
│
├── Report/
│   └── S1_Coursework_Report.pdf     # Report for this coursework
│
├── results/                         # Directory to all saved results
│   ├── results_lambda.json          
│   ├── results_ppf.json             
│   ├── results_sweights.json        
│   ├── time_benchmark_results.json  
│   └── true_value_hits.json         
│
├── .gitignore                       
├── readme.md                        
├── requirements.txt                 
├── S1_coursework.ipynb              # Main code          
└── S1_Coursework.pdf                

```



## How to Set Up the Environment

1. **Using Conda**:

   - Navigate to the directory containing `requirements.txt`:
     ```bash
     cd <path to requirements.txt>
     ```

   - Create a virtual environment:
     ```bash
     conda env create -n <venv_name> python=3.9 -y
     ```

   - Activate the virtual environment:
     ```bash
     conda activate <venv_name>
     ```

   - Install the dependencies:
     ```bash
     pip install --no-cache-dir -r requirements.txt
     ```

2. **Select the Environment in Your IDE**:
   - Choose `<venv_name>` as the active environment in your IDE (e.g., VS Code, PyCharm, JupyterLab).

## Notes

- Some cells in the Jupyter notebooks may start with `WARNING` because they require a long runtime. For these cells, the results have been saved and the computation cell has been commented out. The next cell will load the results for convenience.

## Declaration of Auto Generation Tools

This project leverages AI tools to assist in the development process. Specifically:
- **Code**: Portions of the code were generated using ChatGPT-4o based on pseudocode and instructions provided by the author.
- **Report**: The project report and documentation were created using ChatGPT-4o, guided by the author's detailed instructions.

However, all ideas, concepts, and the overall project structure are entirely the author's own.

## License

This project is licensed under the terms specified in the `LICENSE` file.
