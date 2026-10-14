# Data Science Wine Quality Project

This notebook explores the relationships between wine chemical properties and quality.

-----------------------------------
### Prerequisites
The code should run with any version of Python 3.  
No specific version of any package is required.  

The dataset can be downloaded using `ucimlrepo`, however a local copy of the dataset has been included.

The Following Libraries are needed to run this project:
- numpy $\geq$ 2.4.2
- pandas $\geq$ 2.3.0
- matplotlib $\geq$ 3.11.1
- seaborn == 0.13.2
- ucimlrepo == 0.0.7
- scikit-learn == 1.9.1

To install these libraries execute:  
`pip install -r requirements.txt`

-----------------------------------
### Project Motivation

For this project I was interested in exploring:  
- How do alcohol content and volatile acidity jointly influence wine quality?  
- Are the distinct chemical profiles that differentiate high-quality wines(7-9) from mid-quality wines(5-6)?  
- Which chemical features contribute most to prediction errors, and what does that reveal about the limitations of using chemistry alone to predict wine quality?  

-----------------------------------
### Files

There are 4 files included:  
- the notebook file
- winequality-red.csv
- winequality-white.csv
- winequality-names.csv

-----------------------------------
### Results

The main findings of the code can be found in a blog post [here](https://medium.com/@danielzbarnes/can-chemistry-predict-taste-8170e4203ba9?postPublishedType=initial)

-----------------------------------
### Licensing, Authors and Acknowledgements

Dataset: [Wine Quality - UCI Machine Learning](https://archive.ics.uci.edu/dataset/186/wine+quality)  

P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis.  
  Modeling wine preferences by data mining from physicochemical properties.  
  In Decision Support Systems, Elsevier, 47(4):547-553. ISSN: 0167-9236.  

  Available at: [@Elsevier] http://dx.doi.org/10.1016/j.dss.2009.05.016  
                [Pre-press (pdf)] http://www3.dsi.uminho.pt/pcortez/winequality09.pdf  
              [bib] http://www3.dsi.uminho.pt/pcortez/dss09.bib  

- [License](https://github.com/danielzbarnes/data-science-wine-quality-project/blob/main/LICENSE) GNU General Public License v3.0



