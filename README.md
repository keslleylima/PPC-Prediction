![](https://raw.githubusercontent.com/williamniemiec/ml-ppc/master/docs/img/logo/logo.jpg)

<h1 align='center'>Machine Learning - Prime Path Coverage (PPC)</h1>
<p align='center'>Research on predicting the value of Prime Path Coverage (PPC) through machine learning.</p>
<p align="center">
	<a href="https://jupyter-notebook.readthedocs.io/en/stable/"><img src="https://img.shields.io/badge/Jupyter-Notebook-D0008F.svg" alt="Jupyter Compatibility"></a>
	<a href="https://github.com/williamniemiec/ml-ppc/blob/master/LICENSE"><img src="https://img.shields.io/github/license/williamniemiec/ml-ppc" alt="License"></a>
	<a href="https://github.com/williamniemiec/ml-ppc/releases"><img src="https://img.shields.io/github/v/release/williamniemiec/ml-ppc" alt="Release"></a>
</p>
<hr />

### Replication Package: Predicting Prime Path Coverage Using Regression Analysis at Method Level

## ❇ Introduction
The work aims to evaluate the possibility of predicting the value of Prime Path Coverage (PPC) through machine learning, being useful to assess whether a set of software tests has good chances of detecting potential failures in that system. 

One of the challenges of the software testing activity is to assess the quality of the generated tests and their effectiveness in detecting failures. One way to make this assessment is to identify the obligations that the test must fulfill and assess whether they have all been met by the test. However, depending on the chosen coverage criterion, this assessment can lead to hasty conclusions. There are several test coverage criteria, but one of the most accurate ones is PPC. However, there are few tools available that use such criteria. Based on this context, we work with the estimation of PPC through machine learning, which will receive metrics from the source code as input and will return an estimated value for the PPC. 

In this work, we evaluate the opportunity of using machine learning algorithms to estimate the prime-path coverage of a test suite at the method level.  We followed the Knowledge Discovery in Database process and a dataset built from 9 real-world projects to devise three regression models for prime-path prediction. We compare four different machine learning algorithms and conduct a fine-grained feature analysis to investigate the factors that most impact the prediction accuracy. Our experiments results showed that the best predictive model uses as input data only five source code metrics and one basic test coverage metric. Our evaluation shows that the best model achieves an MAE of 0.016 (1,6%) on the cross-validation (internal validation) and an MAE of 0.06 (6%) on the external validation. Finally, the discussion of the results demonstrates the relevance of test coverage features for model prediction accuracy.


## ✔ Requiremens
- sklearn;
- scipy;
- matplotlib;
- imblearn;
- seaborn;
- pandas;
- numpy.

## 🗺 Architecture
![schema](https://raw.githubusercontent.com/williamniemiec/ml-ppc/master/docs/img/architecture/schema.png?raw=true)


## 🚩 Changelog
Details about each version are documented in the [releases section](https://github.com/williamniemiec/ml-ppc/releases).

## 🤝 Contribution
- [Keslley Lima](https://github.com/keslleylima)
- [William Niemiec](https://github.com/williamniemiec)
- [Érika Cota](https://www.inf.ufrgs.br/site/docente/erika-fernandes-cota/)

## 📁 Files

### /
|        Name        |Type|Description|
|----------------|-------------------------------|-----------------------------|
|docs |`Directory`|Documentation files|
|out   |`Directory`| Exported files    |
|src     |`Directory`| Source files|
