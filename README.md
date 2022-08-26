# An investigation of XGBoost-based algorithm for breast cancer classification

## Reference

If you found this code useful in your reseach, please cite:

**An investigation of XGBoost-based algorithm for breast cancer classification**\
Liew, Xin Yu, Nazia Hameed, and Jeremie Clos\
Machine Learning with Applications\
2021
```
@article{LIEW2021100154,
  title = {An investigation of XGBoost-based algorithm for breast cancer classification},
  author = {Xin Yu Liew and Nazia Hameed and Jeremie Clos},
  journal = {Machine Learning with Applications},
  year = {2021}
}
```
## License

This repository is licensed under the terms of the GNU GPLv3 license.

## Dataset
* To obtain the dataset for this project visit this [(Google Drive)](https://drive.google.com/drive/folders/1JwLRvkkvZowtWnMi7TfiFdHjyNj9lbXX?usp=sharing)

## Folder description
* The folder dataset/Original is obtained from [(BreakHis)](https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/)
* The folder dataset/ColourNormalized is obtained by running the MATLAB file: /main_code/MATLAB/ColourNormalization.m
* The folder final_model folder contains: (1) DenseNet201 files that has save models in h5 file format for feature extraction (2) XGBoost files that has save models in pkl file format for classification
* Jupyter Notebook: Model training and testing files for classification with output results

## Access options
### Using Google Colab 
* Visit [(Google Colab)](https://colab.research.google.com/)
* File > Open notebook > GitHub > "Enter link"
### Using VS Code
* Install VS Code
* Install the Packages using this command line: pip install requirements.txt
* Select the Python environment (with the Jupyter package)
* Open .ipynb files via VS Code
* Once eveything is set up, you'll can view the Jupyter notebook interface with the "Jupyter Server" indicator at the top right
* Make sure the setting "Jupyter: Use Notebook Editor" is enabled

*Note: Additionally, /main_code/Python_file/ contains python files generated from google colab. A Google Colab Pro version with 25GB RAM is used in this project for training.*
