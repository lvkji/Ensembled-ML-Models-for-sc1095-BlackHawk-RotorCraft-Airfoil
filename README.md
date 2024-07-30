Project Description
The project focuses on generating Machine Learning models for the sc1095 rotorcraft airfoil using various model ensembling techniques. The objective is to improve aerodynamic performance by optimizing the lift, drag, and moment measurements. Utilizing the Automated Machine Learning Pipeline (AMPL) on the High Performance Computing system (Carpenter), various ensembling methods such as Bagging, Bootstrap Aggregation, Random Forest, Averaging, and Stacking were employed. These techniques help reduce bias and enhance the reliability of the final model output. 
Improved airfoil designs can lead to better efficiency, reduced fuel consumption, increased safety, and longer range, ultimately lowering government expenses and boosting rotorcraft performance.


Directory Structure:

├── <ampl_dir>
│   ├── <ampl_code_dir>
│   │   ├── <ampl>
│   │   │   ├──<docs>
│   │   │   ├──<examples>
│   │   │   ├──<src>
│   │   │   ├──<tests> 
│   ├── <all_run_dir>
│   │   ├── <dataset1_run_dir>
│   │   │   ├── <data_dir>
│   │   │   │   ├── <data1.csv>
│   │   │   ├── <config_file.yml>
│   │   ├── <dataset2_run_dir>
│   │   │   ├── <data_dir>
│   │   │   │   ├── <data2.sqlite>
│   │   │   ├── <config_file1.yml>
│   │   │   ├── <config_file2.yml>
