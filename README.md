# Ann-Assignment-3

#  credit dataset
The dataset contains the following columns:  
clientid: Unique identifier for the client.    
income: The income of the client.  
age: The age of the client.  
loan: The loan amount.  
default: Whether the client has defaulted (0 = no, 1 = yes)   

# Preprocessing Steps:  
Handling Missing Values: Check for missing values and decide how to handle them.  
Handling Outliers: Identify and manage any outliers.    
Feature Scaling: Scale numeric features such as income, age, and loan.  
Encoding Categorical Variables: If necessary (though none seem present here).  
Feature Engineering: Any derived features that might be useful.  

# finding missing values and outliers  
The dataset contains:  
Missing Values: 3 missing values in the age column.  
Outliers:  
The minimum age is negative (-52.42), which is unrealistic    

# Preprocessing Plan:  
Handle Missing Values: Impute missing values in age.  
Fix Outliers: Address the negative age value.  
Feature Scaling: Standardize income, age, and loan using scaling.  
​
The dataset has been preprocessed with the following changes:  

Missing values in the age column were imputed with the mean.  
Negative ages were replaced with the median age.
Feature scaling was applied to the income, age, and loan columns using standardization  
