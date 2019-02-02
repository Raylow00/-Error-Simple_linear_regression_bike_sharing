# linear_regression_bike_sharing
This is my first self-learnt machine learning algorithm where I use the simple linear regression method to estimate the user count for bike sharing based on the normalized temperatures. However, the algorithm is not perfect as the feature selected does not show a strong relationship with the label. Nonetheless, this is my first trial in machine learning.

**********************************************
Outcome of project:
The dataset proposed here is the dataset for bike sharing systems in a specific place. For a set of conditions like weather situation, temperature, season, workday and humidity levels, the user count for bike sharing system changes. The features are mostly discrete values (seasons represented by values from 1-4, workday represented by numbers from 1-6, and many more) which cause most of the problems as simple linear regression cannot be appropriately used in this dataset. 


R-2 score: -0.76
Explanation: 
- Other variables are controlled and isolated. Howwever, in fact, they are crucial in determining the output accurately.
- The feature ( normalized temperature ) does not show linear or direct relationship with the label, and a linear model might not be the best to display the relationship.

The many variables that affect the user count of bike sharing system might lead to a better model using multiple linear regression. Experiments on this dataset will continue to be done. 


***Update: Note that the relationship between certain features and labels are not apparent and might not even show relation with regards to each other, but this is merely a practice for me to test out my knowledge on linear regression.


**********************************************
Dataset is provided by:

[1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

@article{
	year={2013},
	issn={2192-6352},
	journal={Progress in Artificial Intelligence},
	doi={10.1007/s13748-013-0040-3},
	title={Event labeling combining ensemble detectors and background knowledge},
	url={http://dx.doi.org/10.1007/s13748-013-0040-3},
	publisher={Springer Berlin Heidelberg},
	keywords={Event labeling; Event detection; Ensemble learning; Background knowledge},
	author={Fanaee-T, Hadi and Gama, Joao},
	pages={1-15}
}

=========================================
Contact
=========================================	
For further information about this dataset please contact Hadi Fanaee-T (hadi.fanaee@fe.up.pt)
