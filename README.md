# Inferential-Statistics Project

# Introduction

Breast cancer is the most common type of cancer in women and is the second most common cause of death in developed countries. About 1 in 8 women are diagnosed with breast cancer in their lifetime. There's a good chance of recovery if it's detected at an early stage. Hence, it is very crucial to understand the know-how of the disease and save people's lives.

    1. Title: Haberman's Survival Data Set
    
    2. Sources: 
          Donor: Tjen-Sien Lim (limt '@' stat.wisc.edu) (Date: 1999-03-04)
    
    3. Dataset Information: 
          The dataset contains cases from a study that was conducted between 1958 and 1970 at the University of 
          Chicago's Billings Hospital on the survival of patients who had undergone surgery for breast cancer.
    
    4. Number of Instances: 306
    
    5. Number of Attributes: 3
    
    6. Attribute Information:
          1. Age of patient at time of operation (numerical)
          2. Patient's year of operation (year - 1900, numerical)
          3. Number of positive axillary nodes detected (numerical)
          4. Survival status (class attribute)
              1. the patient survived 5 years or longer
              2. the patient died within 5 year
              
    7. Missing values: No


# Research Question and Hypothesis

By looking at the dataset attribute information, I think the number of positive axillary nodes detected feature would play a huge role in classification of whether there is a breast cancer or not. Therefore, the research question would be like - Are patients with lower number of positive axillary nodes detected more likely to survive? Our hypothesis goes like this: 

    H0 = There is no relationship between number of positive axillary nodes detected and survival status; u1 = u2 (u1 - u2 = 0)
    Ha = Patients with lower number of positive axillary nodes detected are more likely to survive; u1 < u2 (u1 - u2 < 0)

A positive axillary nodes are lymph nodes in the area of armpit to which cancer has spread (wikipedia). That means, fewer number of positive axillary nodes detected in a person is more likely to survive. This prediction of what result might be can be prove by using statistical test.

# Experimental Design 
    
    


