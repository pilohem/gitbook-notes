# Model  Decay

ML models in production operate in dynamic environments. So the ground truth is constantly changing.

### Causes of Model Drift

* Data Drift
  * Statistical properties (mean, variance) of Input data changes, and the trained model is no longer relevant for the new changed data. Examples: changes in the data due to seasonality, changes in consumer preferences, the addition of new products...
* Concept Drift
  * Relatioship between features and labels changes. The meaning of what you are trying to predict changes

Eventually these types of drift impact the performance of the model, so it is important to monitor and detect on time.





