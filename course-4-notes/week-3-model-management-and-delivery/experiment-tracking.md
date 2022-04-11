# Experiment Tracking

Why is it important?

* To duplicate results
* To make reliable comparisons between models
* To manage code/data versions, hyperparameters, environments, and metrics.
* To make these experiments available to the team and enable collaboration.

{% hint style="info" %}
Note: Jupyter Notebooks are good for initial analysis like EDA and model prototyping. But there is a limitation when moving these into a Production environment. Because of this, it is important to move from a single file code into **modular code**.
{% endhint %}

Tracking runtime parameters can be done with:

* Config files (json, yaml).
* Entering the parameters in the command line.

![Source: DeepLearnig.ai](<../../.gitbook/assets/image (13).png>)

### Tools for Experiment Tracking

* [Neptune](https://neptune.ai)
* [Weights & Biases](https://wandb.ai/site)
* Logging metrics with [TensorBoard](https://www.tensorflow.org/tensorboard)
* For Data versioning:
  * [Pachyderm](https://www.pachyderm.com)
  * [DVC](https://dvc.org)
  * [Deltalake](https://delta.io)
  * [Git LFS](https://git-lfs.github.com)

{% hint style="info" %}
Note: All these ML tools are useful to reach an optimum model, but it is equally important to keep in mind the Business Goals (time to deliver, budget, latency, computational cost). _It may not be worth tracking experiments that will last 1-2 months if your client is asking for a model for next week._
{% endhint %}
