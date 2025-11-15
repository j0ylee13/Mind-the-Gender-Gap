# Mind-the-Gender-Gap
An exploration on the differences in employment patterns across genders in the UK. (Study Group 2 final project for Data Visualisation)

## About
Studies show that within the UK, more women than men enrol in higher education and ultimately attain better educational outcomes. In “The Quiet Revolution That Transformed Women’s Employment, Education, and Family” (2006), Claudia Goldin describes how the social and economic transformations leading up to the 1960s led more women to enter the workforce and raised expectations for them to work full-time. Despite this, more recent official statistics from the OECD and the UK government show that women are more likely to work part-time jobs than men. Using 2011 UK Census data on education and childcare, we explore reasons why women’s educational advantage has not translated proportionally into full-time workforce participation.

**We ask:**
What is the observed gap in hours worked between men and women in the UK?
How much do factors such as geography, age, and industry of employment contribute to this discrepancy?
After controlling for relevant factors, to what extent can the residual gap in hours worked be attributed to gender discrimination?

## Our data
(I.) [2011 Census in England and Wales: Teaching file](https://www.ons.gov.uk/peoplepopulationandcommunity/educationandchildcare/datasets/2011censusteachingfile)
(II.) [Classifications and codes in the microdata teaching file](https://www.ons.gov.uk/census/2011census/2011censusdata/censusmicrodata/microdatateachingfile/variablelist) 

## Methodology
**Step 1: Data Cleaning**
- First we mapped categorical data from the variable dictionary (II) to the numerical representations in the dataset (I)
- Next we structured the target variable (hours worked) into standard intervals to allow for OLS modelling​

**Step 2: Exploratory Data Analysis + Visualizations**
- Kernel density estimation plot to compare the distribution of hours worked for women v. men
- Bar chart to visualize patterns in occupations by gender
- Interactive map of hours worked by county
  
**Step 3: Modeling**
- Estimation of hours worked for men and women with OLS regression
- Decomposition of the observed gap in mean hours worked using the Oaxaca-Blinder decomposition​ method

  ## Conclusion

  ### FILL IN 
