# Managing Model Versions

Model versioning format (this is a proposal, not an established standard)

Version: **MAJOR.MINOR.PIPELINE**

* **MAJOR**: Incompatibility in the data or target variable.
* **MINOR**: Model performance is improved.
* **PIPELINE**: Some parts in the model pipeline are changed.

#### Model  Lineage

* All the steps, processes used/implemented to recreate a given version of the model.
* The set of Artifacts: all the information needed to preprocess data and generate a given result (_code, data, configurations, model_)
* This can be done with most of the ML Frameworks.

#### Model Registry

![Source: DeepLearnig.ai](<../../../.gitbook/assets/image (5).png>)

A model registry also promotes model search and discovery, as well as collaboration between teams.

Examples:

* Azure ML Model Registry
* SAS Model Registry
* Google AI Platform
* Algortihmia
