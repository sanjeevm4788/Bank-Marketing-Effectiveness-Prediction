
# Bank Marketing Effectiveness Prediction

### Problem Description 

The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. The classification goal is to predict if the client will subscribe a term deposit (variable y).


### Features of our dataset:

#### Bank Client Data:

* Age: Age of the client
* Job : Profession of the client
* marital : marital status (Whether the client is married, single or divorced)
* Education : Highest level of education of the particular client
* default: Whether the client has defaulted or not
* housing: Whether the client has a housing loan? 
* loan: Whether the client has a personal loan? 

#### Related with the last contact of the current campaign:

* contact: Information on how the client was contacted (unknown, cellular, telephone)
* month: last contact month of year ('jan', 'feb', 'mar', ..., 'nov', 'dec')
* day_of_week: last contact day of the week ('mon','tue','wed','thu','fri')

#### Other attributes: 

* campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
* pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
* previous: number of contacts performed before this campaign and for this client (numeric)
* poutcome: outcome of the previous marketing campaign ('failure','nonexistent','success')


#### Output variable (desired target):
* y - Whether the client subscribed a term deposit or not? ('yes','no')

## <b> Approaching the Problem Statement: </b>

* Developed the model using multiple machine learning algorithms like RandomForest, KNN, Logistic Regression, Decision Tree, XGBoost.
* Employed processing techniques like outlier treatment using IQR, encoding categorical features using target encode, feature selection using correlation heatmap, chi square contingency test and ExtraTreesClassifier.
* Used AUC_ROC score to select the high performing model.
