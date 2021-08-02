![](https://raw.githubusercontent.com/williamniemiec/ml-ppc/master/docs/img/logo/logo.jpg)

<h1 align='center'>Machine Learning - Prime Path Coverage (PPC)</h1>
<p align='center'>Research on predicting the value of Prime Path Coverage (PPC) through machine learning.</p>
<p align="center">
	<a href="https://github.com/williamniemiec/ml-ppc/blob/master/LICENSE"><img src="https://img.shields.io/github/license/williamniemiec/ml-ppc" alt="License"></a>
</p>
<hr />

## ❇ Introduction
The work aims to evaluate the possibility of predicting the value of Prime Path Coverage (PPC) through machine learning, being useful to assess whether a set of software tests has good chances of detecting potential failures in that system. 

One of the challenges of the software testing activity is to assess the quality of the generated tests and their effectiveness in detecting failures. One way to make this assessment is to identify the obligations that the test must fulfill and assess whether they have all been met by the test. However, depending on the chosen coverage criterion, this assessment can lead to hasty conclusions. There are several test coverage criteria, but one of the most accurate ones is PPC. However, there are few tools available that use such criteria. Based on this context, we work with the estimation of PPC through machine learning, which will receive metrics from the source code as input and will return an estimated value for the PPC. 

To evaluate our solution, we used 12 open-source projects, 8 of which were used for internal validation and 4 for external validation. In addition, we evaluated 3 different metrics availability scenarios: using only source code metrics (SCM model), only Edge Coverage (EC model) and using both (SCM + EC model). The results obtained were positive, the best model being the SCM + EC, with an average absolute error of approximately 6%, and, therefore, allowed the assessment of test coverage as expected. The results are relevant, given the difficulty of finding software that evaluate tests using the PPC coverage criterion. Because it is a practical way for the tester to discover PPC and because it is a high quality criterion, we believe that the work will contribute to the development of software with greater reliability. 

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

## 📁 Files

### /
|        Name        |Type|Description|
|----------------|-------------------------------|-----------------------------|
|docs |`Directory`|Documentation files|
|out   |`Directory`| Exported files    |
|src     |`Directory`| Source files|

## 🤝 Contribution
- [Keslley Lima](https://github.com/keslleylima)
- [Érika Cota](https://www.inf.ufrgs.br/site/docente/erika-fernandes-cota/)
