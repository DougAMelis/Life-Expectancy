# Life-Expectancy

This is a project that uses multiple linear regression to predict life expectancy. It showcases the entire data science workflow, from data collection to results.

The models predict life expectancy within a country based on the GDP per capita in current USD, mean BMI, prevalence of obesity, incidence and prevalence of HIV/AIDS, alcohol consumption per capita (15+) in liters, prevalence of diabetes, and the rate of immunization coverage estimates among 1-year-olds for ten different vaccines. The vaccines used were BCG, Diphtheria tetanus toxoid and pertussis (DTP3), Hib3, Hepatitis B (HepB3), PAB, Polio (Pol3), the Pneumococcal conjugate vaccines (PCV3), Rotavirus vaccines (RotaC), and both doses of the Measles-containing-vaccine (MCV1 and MCV2).

The data used for this project is collected through a variety of sources, but all files are .csv and in the data folder.
The file LifeExpectancy.Rmd performs the data cleaning and preprocessing, and builds and compares several multiple linear regression models.
The file LifeExpectancy.docx is the formatted output of the rmd file.



Sources:
* World Health Organization - life expectancy at birth, alcohol consumption, and immunization coverage
* NCD Risk Factor Collaboration - mean BMI, prevalence of obesity, and prevalence of diabetes
* World Bank - GDP per capita
* Global Change Data Lab - prevalence and incidence of HIV/AIDS
