# GWPCA_Workshops
GWPCA workshops
# Geographically Weighted PCA Workshop: Introductions and Uses
Organizers: 

- Dr Paul Harris (Eco-informatics Scientist, Rothamsted Research, UK) 
- Prof Alexis Comber (Chair of Spatial Data Analytics, University of Leeds, UK).  

Both have contributed to key advances in Geographical Weighted Models and the GWmodel R package.

# Description and Background: 
In many geographical studies, principal components analysis (PCA) is applied without consideration for spatial effects, and in doing so, tends to provide an incomplete understanding of a given process. In such circumstances, a spatial adaptation of PCA can be adopted, one of which is geographically weighted (GW) PCA (i.e. GWPCA). The workshop will introduce GWPCA and frame it within the wider GW modelling framework - where focus moves away from the popular GW Regression (GWR) model to GWPCA instead. Techniques are illustrated using environmental, remotely-sensed and social-economic data sets. Attendees will learn how to conduct and interpret a GWPCA, together with how to use its outputs for a variety of spatial problems.

# Detail: 
GWPCA is a localized version of PCA that is an exploratory tool for investigating spatial heterogeneity in the structure of multivariate data. It not only provides a useful investigative tool, but also lends itself to the many uses of PCA at a localised scale. The workshop will demonstrate how to calibrate a GWPCA - including how to determine the spatial scale of each localised PCA, conduct associated tests, and ways to visualize the copious amounts of GWPCA output. Following this core introduction to GWPCA, the workshop will present three key uses of GWPCA: (i) to detect multivariate spatial outliers; (ii) to optimally re-design a multivariate spatial monitoring network; and (iii) to provide multivariate spatial input variables to improve spatial classification accuracy – all extensions of GWPCA developed by the workshop organisers.

# Scope and novelty of the workshop: 
GWPCA is a localized version of PCA that is an exploratory tool for investigating spatial heterogeneity in the structure of multivariate data. It not only provides a useful investigative tool, but also lends itself to the many uses of PCA at a localised scale. The workshop will demonstrate how to calibrate a GWPCA - including how to determine the spatial scale of each localised PCA, conduct associated tests, and ways to visualize the copious amounts of GWPCA output. Following this core introduction to GWPCA, the workshop will present three key uses of GWPCA: (i) to detect multivariate spatial outliers; (ii) to optimally re-design a multivariate spatial monitoring network; and (iii) to provide multivariate spatial input variables to improve spatial classification accuracy – all extensions of GWPCA developed by the workshop organisers.

# Workshop content
This 1-day workshop will consist of a series of lectures and practicals. The expected number of participants – 20 to 25 anf the workshop will have a ethos of *more doing and less talking*. The tentative outline for the day is as follows: 

-	9:00am Introductions
-	9:30-9:50 Lecture 1: Intro to Geographically Weighted Models (AC)
-	09:50 Practical 1: Intro to GWmodel
-	10:30am Break
-	10:50-11:10: Lecture 2: Intro to PCA and GWPCA (PH)
-	11:10am Practical 2: PCA and GWPCA in R with GWmodel
-	1:00pm Lunch
-	2:00-2:20 Lecture 3: GWPCA for outlier detection (PH)
-	2:20pm Practical 3: GWPCA for outlier detection
-	3:00-3:20 Lecture 4: GWPCA for network design (AC)
-	3:20pm Practical 4: GWPCA for network design
-	4:00pm Break
-	4:20-4:40 Lecture 5: GWPCA for spatial classification (AC)
-	4:40pm Practical 5: GWPCA for spatial classification
-	5:30pm Wrap up and Finish

# Requirements: 

A laptop computer with R installed. Experience of R is essential for this workshop, as is some rudimentary knowledge of statistics. Data and bespoke R code will be developed and shared as part of the workshop and attendees are encouraged to bring their own data for analysis during the workshop.

# References

Harris P, Brunsdon C, Charlton M (2011) Geographically weighted principal components analysis.  International Journal of Geographical Information Science 25 (10):1717-1736

Harris P, Brunsdon C, Charlton M, Juggins S, Clarke A (2014) Multivariate spatial outlier detection using robust geographically weighted methods.  Mathematical Geosciences 46(1) 1-31

Harris P, Clarke A, Juggins S, Brunsdon C, Charlton M (2014) Geographically weighted methods and their use in network re-designs for environmental monitoring. Stochastic Environmental Research and Risk Assessment 28: 1869-1887

Harris P, Clarke A, Juggins S, Brunsdon C, Charlton M (2015) Enhancements to a geographically weighted principal components analysis in the context of an application to an environmental data set.  Geographical Analysis 47: 146-172

Gollini I, Lu B, Charlton M, Brunsdon C, Harris P (2015) GWmodel: an R Package for exploring Spatial Heterogeneity using Geographically Weighted Models. Journal of Statistical Software 63(17): 1-50

Comber A, Harris P, Tsutsumida N (2016) Improving land cover classification using texture variables outputted from a geographically weighted principal components analysis. ISPRS Journal of Photogrammetry and Remote Sensing 119: 347-360

Tsutsumida N, Harris P, Comber A (2017) The application of a geographically weighted principal components analysis for exploring 23 years of goat population change across Mongolia. Annals of the Association of American Geographers 107(5): 1060-1074

