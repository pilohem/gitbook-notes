# Model Monitoring

#### Why it matters?

* Spot Data Skews
* Prevent model  staleness
* Negative feedback loops

#### ML Monitoring (Functional Monitoring)

* Predictive performance
* Changes in serving data
* Metrics used during training
* Characteristics of features

#### System Monitoring (Non-Functional Monitoring)

* System Performance
* System status
* System reliability

### Observability in ML

measures how well the internal states of a system can be inferred by knowing the inputs and outputs.

Goal: prevent or act upon system failures. Recommend actions and raise alerts.



When monitoring the Inputs of a model it is good to check that:

* The input values fall within an allowed set or range
* There is a change in the distributions of the inputs
* Check these in different slices of the data, not only the whole data set.

#### Logging in ML

![Source: DeepLearnig.ai](<../../.gitbook/assets/image (7).png>)





