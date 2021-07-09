# SDV Urbanization Method Evalutation BURG2021
## Introduction
This analysis draws upon previous research into urbanization and human skeletal sexual dimorphism variation (Feiler 2019, Feiler et al. 2019). Due to the complex intersection of life history factors that act upon the human body in an urban setting, variation in standard nonmetric sex estimationt traits may occur. According to allocation theory, individuals who experience more environmental stress (such as poor nutrition, increased disease prevealence, increase exposure to polution, increases socioeconmic inequality, and more) will have less metabolic energy to spend on activity, maintenance, storage, or growth/reproduction (Agarwal 2016, Gray and Wolfe 1980, Hill 1993, Hill and Hurtado 1996, Kuzawa 2005, Waxenbaum and Feiler 2021). Therefore, the health consequences of urban envirnoments may influence populational adult morphology and sexual dimorphism. 

In previous interations of this research, two statistical methods were employed to test two different hypotheses: 
- Greene's t-test for testing populational shifts to a hypergracile or robust morhology with no change in sexual dimorphism
- one-way ANOVA for testing variation in the degree of sexual dimorphism between the populations in question.

However, it was suggested that one-way ANOVAs would produce the same results and reduce the complexity of the statistical procedures. In addition, the first iterations of these statistical procedures were conducted using SPSS, a powerful but exclusive statistical program. 

This experiment aims to reconduct the statistical procedures of Feiler (2019)'s masters thesis using the same data using R, a free coding language with great statistical power. In addition, this experiment will compare the original statistical methods to the suggested new procedures. An analysis of any variation in the results, the accessibility , and the computational requirements of the two methods will also be conducted. 

The present study ultimately aims to illuminate the most accessible, affordable, and time-saving method for assessing health and sexual dimorphism variation between urban and rural skeletal samples, thereby improving anthropological research regarding urbanization in the future.

## Repository Roadmap
In the interest of open access research, all documents and data included in this repository were used directly while developing the .Rscripts. In this repo, the following are included:
- README.md, an introduction and explanation into the research presented in this repo, including results, discussion, and an accurate documentation of the steps taken. 
- Settlement_Dimorphism_Data.csv, the cleaned data used throughout this experiment containing the biological data of all the indidivudals used in this study. For further information regarding the assignment of sex and age category to each individual, the scoring procedures utlized, and the samples in question, please refer to Feiler's (2019) masters thesis.
- Original_Statistics.R, an R script that recreates the original statistical procedures conducted in Feiler's (2019) masters thesis.
- Revised_Statisics.R, an R script that modifies the statistical procedures to use one-way ANOVAs only.
- Method_Evaluation.R, an R script that analyzes the code and results of Original_Statistics.R and Revised_Statistics.R for similarity, accessibility, and processing power necessary for each method. 
- Abstract.docx, the abstract submission document for BURG2021, the BABAO funded virtual Bioarchaeology of Urbanization Research Group conference, based upon the results of the present study.

## Works Cited
Agarwal, S.C. 2016. Bone morphologies and histories: Life course approaches in bioarchaeology. Yearbook of Physical Anthropology 159: S130-S149. http://doi.wiley.com/10.1002/ajpa.22905.

Feiler, M.E. 2019. Sex and the cities: Urbanization's influence on sexual dimorphism in the post-Medieval Dutch (masters thesis). Universiteit Leiden, Leiden, NL. 

Feiler, M.E., S.A. Schrader, C.L. Burrell, and M. Hoogland. 2019. Sex and the cities: Urbanization's influence on sexual dimorphism in the post-Medieval Dutch (conference poster). 21st Annual Conference of the British Association for Biological Anthropology and Osteoarchaeology, London, September 2019.

Gray, J.P., and L.D. Wolfe, 1980. Height and sexual dimorphism of stature among human societies. American Journal of Physical Anthropology 53 (3): 441–56. https://doi.org/10.1002/ajpa.1330530314.

Hill, K. 1993. Life history theory and evolutionary anthropology. Evolutionary Anthropology: Issues, News, and Reviews 2 (3): 78–88. https://doi.org/10.1002/evan.1360020303.

Hill, K. and A.M. Hurtado. 1996. Aché life history: The ecology and demography of a foraging people. New York City, NY: Aldine de Gruyter. 

Kuzawa, C.W. 2005. Fetal origins of developmental plasticity: Are fetal cues reliable predictors of future nutritional environments? American Journal of Human Biology, 17(1): 5-21. https://doi.org/10.1002/ajhb.20091.

Waxenbaum, E.B. and M.E. Feiler. 2020. Influence of climatic stress on nonmetric sexually dimorphic features of the skull and pelvis. American Journal of Human Biology, e23559. https://doi.org/10.1002/ajhb.23559
