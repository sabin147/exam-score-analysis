# Exam Time vs Score — Statistical Analysis

**Type:** Academic Mini Project  
**Institution:** Roskilde University  
**Course:** BC4-8: Statistical Models  
**Authors:** Sabin Ghimire, Gabriel Nørrelykke K. Kihara, Cabdi Raxman Mohamed Aadan, Jiaxu Yang, Divine Agbogah  
**Year:** 2025

## Research Question

Do students who spend more time on an exam get higher scores?

## Dataset

134 observations with two variables: Time (seconds) and Score.

## Methods

- Descriptive statistics (mean, std, IQR)
- Normality testing via Q-Q plots and histograms
- 95% Confidence intervals
- Linear regression (Time vs Score)
- Log-transformation analysis
- Pearson and Spearman correlation

## Key Finding

No significant correlation between time spent and score achieved.  
Both variables follow a normal distribution.  
Log-transformed time follows an even stronger normal distribution.

## Run It
```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels jupyter
jupyter notebook exam-score-analysis.ipynb
```

## Note

Dataset (`exam.csv`) not included as it was provided by the course instructor.

## License

MIT License — Copyright (c) 2025 Sabin Ghimire et al.
