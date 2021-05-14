This is a repository that contains a notebook that runs a logistic regression model on a mushrooms dataset to classify them as edible or poisonous. Some of the code for the feature selection is inspired from this [link](https://towardsdatascience.com/categorical-feature-selection-via-chi-square-fc558b09de43). <br>
Further there is some visualisation and interpretation done using odds ratio explanations which can be better understood [here](https://www.notion.so/A-failed-trail-of-mushrooms-c86a29fdd0704db6b2db7f9491f47428#04850b4c419d4543bd7f06a471f6d126)

The odds ratio values for all categorical variable types with respect to a reference type can be found in `mushroom_explanations.csv`. If a categorical feature has possible values red, blue, green, the value that is first in the alphabetically sorted list of these values, which is green in this case, will be taken as reference and odds ratio will be shown for the other values with respect to green. <br>
The raw dataset used for the entire exercise is `mushrooms.xlsx`. <br>
I will add comments to the notebook sometime in the future, although there is not much to understand.<br>
An unrelated blog post I wrote that this inspired can be found [here]().
