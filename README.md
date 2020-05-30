# Effect of a treatment over trauma patients


[(Traumabase®], (http://www.traumabase.eu) is a a growing database built from the collaboration between several trauma centres in France.
Severe trauma represents one of the most common cause of death in patients 16-45 years of age. Several initiatives have been undertaken to provide
support and tools for doctors, to help them assess their best practices and provide an efficient response to increasing health challenges.

The data is confidential and as such cannot be shared on any outside platform.

In this project, we studied the effect of tranexamic acid, a treatment administered to patients suffering heavy bleeding consecutive to a head trauma.
We used a raw dataset of initially 7000 rows and 250 features, with both categorical and continuous variables. We performed an investigation 
of the missing values according to their class (missing completely at random, missing at random and missing not at random).
With an eye on the former, we critically imputed missing data through two different methods, random forests and factorial analysis for mixed data (FAMD), for comparison purposes. 
We then ran a descriptive analysis using principal components analysis (PCA) and hierarchical clustering. We determined the most relevant variables, their correlation with cranian trauma,
and found three relevant clusters of patients exhibiting similar characteristics. We validated our findings with doctors.
Afterwards, in order to measure the effect of the treatment over mortality, we had to use several causal inference techniques. 
Indeed, tranexamic acid is predominantly administered to patients in hemorrhagic shock with a high risk of dying. 
This reveals an attribution bias and tends to skew the average treatment effect.
To account for the covariates, we tried matching, inverse propensity weighting (IPW), and double robust estimators.


